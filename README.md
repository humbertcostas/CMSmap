CMSmap
======

CMSmap is a python open source CMS (Content Management System) scanner that automates the process 
of detecting security flaws of the most popular CMSs. The main purpose of CMSmap is to integrate common vulnerabilities 
for different types of CMSs in a single tool. 

At the moment, CMSs supported by CMSmap are WordPress, Joomla and Drupal.

Please note that this project is an early state. As such, you might find bugs, flaws or mulfunctions.
Use it at your own risk!

Usage
=====
	CMSmap tool v0.3 - Simple CMS Scanner
	Author: Mike Manzotti mike.manzotti@dionach.com
	Usage: cmsmap.py -u <URL>
			-u, --url      target URL (e.g. 'https://abc.test.com:8080/')
			-v, --verbose  verbose mode (Default: false)
			-t, --threads  number of threads (Default: 5)
			-U, --usr      username or file
			-P, --psw      password or file
			-h, --help
	
	Example: cmsmap.py -u https://example.com
			 cmsmap.py -u https://example.com -U admin -P passwords.txt


Disclaimer
=====
Usage of CMSmap for attacking targets without prior mutual consent is illegal. 
It is the end user's responsibility to obey all applicable local, state and federal laws. 
Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program.