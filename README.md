
![Alt text](https://github.com/Insolent-M1nx/File-Bouncer/blob/master/filebouncer.PNG?raw=true "File-Bouncer")

File Bouncer is a Program Developed in Go with the sole purpose of performing analysis on .png files to determine if they are potentially embedded with malicious code. 

![Alt text](https://github.com/Insolent-M1nx/File-Bouncer/blob/master/fb2.PNG?raw=true "File-Bouncer")

Simply select the file you wish to analyze and File Bouncer will perform a hex dump and check end line paramters to ensure your PNG file is not packed after IEND (a common tactic for .png borne malware | Lokibot etc.)
