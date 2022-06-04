---
title: Instagram Hack
desc: instahack is a bash based script which is officially made to test password strength of instagram account from termux with bruteforce attack and. This tool works on both rooted Android device and Non-rooted Android device.
layout: post
category: Termux
keywords: termux
usemathjax: false
---

<p align="center">
<a href="https://github.com/evildevill/instahack"><img title="instahack" width="50%" src="https://raw.githubusercontent.com/evildevill/instahack/master/assets/20210219_144319.jpg"></a>
</p>

## ABOUT TOOL :

instahack is a bash based script which is officially made to test password strength of instagram account from termux with bruteforce attack and. This tool works on both rooted Android device and Non-rooted Android device.

## How?

| We use , **tor** to change our ip once blocked for many tries and continue attack.
| Since the official api is not a hacker wants, So we use the **InstagramAPK signature** to stay **anonymous!**
| And we also **save** the **progress** so that even in network interruption we can avoid breaking the computer!

 **See the 'Algorimthm' section down below for more hackery!**


## What?

| **Instahack** is a slick bash script to perform  **brute force** attack against **Instagram** ,   
| this script can **bypass** login limiting on wrong passwords ,  so basically it can test **infinite number of passwords**.
| Instahack is **proved** and can test **over 6M** passwords on a single instagram account with **less resource** as possible
| This script mimics the activities of the official **instagram android app** and sends request over **tor** so you are secure ,
| but if your **tor** installation is **misconfigured** then the blame is on you.

## Features

* instahack Scripting

* Resumes Attacks when the same wordlist is used on the same Username
* Dumps successfully cracked accounts in the dump
* Maximum Customization! ( This includes multiple attack vectors! )
* Fast and Clean Code , no ugly selenum drivers! ( Pure Requests )
* Elegant Tor Identity Change with Stem ( Tor's Official Library for Python )


**Depends on**:to r ,  requests , requests[socks] , stem

### TESTED ON :

* Termux
* Kali Linux

## FEATURES :
* [+] Insta OSINT !
* [+] Insta Bruteforce !
* [+] Instagram stable api !
* [+] Multi Thrading
* [+] Twitter Bruteforce
* [+] Updated maintainence !
* [+] tor usage !
* [+] Easy for Beginners !

## REQUIREMENTS

```bash
$ sudo easy_install3 -U pip # you have to install python3-setuptools , update pip
$ sudo pip3 install requests --upgrade
$ sudo pip3 install requests[socks]
$ sudo pip3 install stem
```

## INSTALLATION [Termux] :

```bash
 apt-get update -y
 apt-get upgrade -y
 apt-get install python -y
 apt-get install python2 -y
 apt-get install git -y
 apt-get install wget -y
 apt-get install curl -y
 git clone https://github.com/evildevill/instahack.git
 cd instahack
 bash setup_env.sh
 bash instahack.sh
```


###   Configuring Tor server to open control port


open your **tor configuration** file usually located at **/etc/tor/torrc**

```bash
 $ sudo vim /etc/tor/torrc # open it with your text editor
```

**search** for the file for this **specific section**

 ## The port on which Tor will listen for local connections from Tor
 ## controller applications, as documented in control-spec.txt.
 # ControlPort 9051
 
**uncomment** 'ControlPort' by deleting the **#** before 'ControlPort' , **now save the file and restart your tor server**

**now you are ready to crack any instagram account , make sure your tor configuration matched ~/instapy-config.json** 

```
[+]--Now you need internet connection to continue further process...
[+]--You can select any option by clicking on your keyboard
[+]--Note:- Don't delete any of the scripts included in core files
[+]--new session and start TOR (tor) before starting the attack
```

## USAGE OPTIONS [Termux] :

__INFORMATION GATHERING__ :
- From this option you can gather information about your target

__AUTO ATTACK__ :
- From this option you can start attack aon default pass list of tool.

__MANUAL ATTACK__ :
- From this option you can select manual pass list and try to attack.

__ABOUT__ :
- From this option you can know more about author.

__UPDATE__ :
- From this option you can update instahack tool if updates are available for that.

__EXIT__ :
- From this option you can exit from tool 

## SCREEN SHOTS [Termux]

<br>
<p align="center">
<img width="75%" src="https://raw.githubusercontent.com/evildevill/instahack/master/assets/Screenshot_20220323_221439.jpg"/> <br>
<img width="75%" src="https://raw.githubusercontent.com/evildevill/instahack/master/assets/Screenshot_20210920_062617.jpg"/>
</p>

## WARNING : 
***This tool is only for educational purpose. If you use this tool for other purposes except education we will not be responsible in such cases.***
