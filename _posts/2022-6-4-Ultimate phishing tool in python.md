---
title: PyPhisher
desc: Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.
layout: post
category: Termux
keywords: termux
usemathjax: false
---

<h1 align="center">PyPhisher</h1>

### [+] Description :

***Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.***

### [+] Installation

##### Install primary dependencies (git and python)

 - For Debian
    - ```sudo apt install git python -y```
 - For Arch
    - ```sudo pacman -S git python --noconfirm```
 - For Fedora
    - ```sudo yum install git python -y```
 - For Termux
    - ```pkg install git python -y```

##### Clone this repository

 - ```git clone https://github.com/KasRoudra/PyPhisher```

##### Enter the directory
 - ```cd PyPhisher```

##### Run the tool
 - ```python3 pyphisher.py```

#### Or, directly run

```bash
wget https://raw.githubusercontent.com/KasRoudra/PyPhisher/main/pyphisher.py && python3 pyphisher.py
```

#### Options

```bash
usage: pyphisher.py [-h] [-p PORT] [-o OPTION]
                    [--update | --no-update]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  PyPhisher's server port [ Default : 8080 ]
  -o OPTION, --option OPTION
                        PyPhisher's template index [ Default : null ]
  --update, --no-update
                        Check for update (default: True)
```

### Features:

 - Multi platform (Supports most linux)
 - 65 Website templates
 - Dual Tunneling (Ngrok and Cloudflared)
 - Easy to use
 - Possible error diagnoser
 - Built-in masking of url
 - Custom masking of url
 - Portable file (Can be run from any directory)
 - Get IP Address and many other details along with login credentials

### Requirements

 - `Python(3)`
 - `PHP`
 - `Curl`
 - `Unzip`
 - `Wget`
 - 100MB storage 
 
If not found, all of the required packages will be installed on first run

#### Tested on

 - `Termux`
 - `Kali-Linux`

## Usage

1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured

<h1 align="center">Example</h1>

![PyPhisher](https://raw.githubusercontent.com/KasRoudra/PyPhisher/main/files/pyphisher.gif)

## Video Tutorial
<a href="https://rebrand.ly/pyphishervideo">PyPhisher Video</a>

## [+] Disclaimer
***This tool is developed for educational purposes. Here it demonstrates how phishing works. If anybody wants to gain unauthorized access to someones social media, he/she may try out this at his/her own risk. You have your own responsibilities and you are liable to any damage or violation of laws by this tool. The author is not responsible for any misuse of PyPhisher!***
