# Data2Decisions
# KRYPTRONICS- Software Installation README 

This software uses two directories for its installation. One is a public directory, and one is a private, or secure directory.
Kryptronic software installs in two different directories to separate what should be public content from what should be
private content, for security purposes. All directories you create and all files you upload during this software installation
should have permissions set to executable (CHMOD 755 on linux/unix systems, Full Control for Everyone on Windows
Servers).
You will either be installing Kryptronic software in the document root of your website, so it uses a URL like
'http://domain.com/', or in a subdirectory in your document root, so it uses a URL like 'http://domain.com/store/', or
something similar. 


## Get Started 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

#### List of files in the repository
* Earthquake
* IRS_Scam
* SamesexMarraige-Abortion
* License
* Readme.md

### Document Root Installation

If you are installing in the document root, create your private directory as follows. Your public directory is your document
root, already set up, and we're calling it /public_html below, but it may be named /httpdocs, /www or something completely
different:

```
/private
/public_html 
```
###Subdirectory Installation
If you are installing in a subdirectory in your document root, create your public and private directories as follows. We're
calling your document root /public_html below, but it may be named /httpdocs, /wwwd or something completely different: 

```
/private
/public_html/store 

```
### Security Tip

Pick a location for your private installation directory that's not web-accessible. In other words, choose a
directory outside of your website's document root. The private directory must be writable by the webserver process, but
does not have to be web accessible. 

## Unzip and Upload Installation Files

Unzip the Software Installation Package referenced in the first step, and upload all of it's contents to the public installation
directory you created in the previous step. The files you'll need to upload are: 

```
admin.php
index.php
installer.php
readme.pdf
license.pdf 
```

## Run the Installer Script 


Lastly, open your browser software (Chrome, Firefox, Safari, MSIE) and navigate to the installer.php file at a URL like
http://domain.com/installer.php or http://domain.com/store/installer.php, depending on your installation setup. The Step by
Step Installation Guide will take you through the rest of the process... 

## Authors

* **Shravya Shruthi** - *Initial work* - [spathala](https://github.com/spathala)

See also the list of [contributors](https://github.com/spathala/Data2Decisions/graphs/contributors) who participated in this project.

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* http://central.kryptronic.com/public/docs/readme.pdf
