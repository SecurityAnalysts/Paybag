# Paybag

Create metasploit payload easily using Paybag

![Screenshot](https://user-images.githubusercontent.com/32305505/99352267-56d06400-28c8-11eb-8aa3-a7da8e85e337.jpg)


# Installation

1) git clone https://github.com/Deadpool2000/Paybag.git
2) cd Paybag
3) pip3 install -r requirements.txt
4) python3 paybag.py


# What's New in v1.1?

1) Bugs Fixed
2) Added new payload options
3) Removed OSX support
4) User can select LHOST from table


# Usage

**1) Create a payload**
- Create a payload by just giving LHOST and LPORT and send it to victim.

**2) Start Listner**
- After creating payload,send it to victim & execute it on victim machine.
- After execution,Select **'Start Listner'**,select LHOST from table and enter LPORT which used while creating payload.
- Now wait until a successfull connection.

**3) Launch Metasploit**
- Start Metasploit using **Launch Metasploit** option.

-----------------------------------------------------------------------------------------------------

### All payloads are stored in 'payload' folder.

-----------------------------------------------------------------------------------------------------

### Tested on - Ubuntu 20.04, Kali linux & Termux

-----------------------------------------------------------------------------------------------------

### If you have any issue regarding this,report an issue [here](https://github.com/Deadpool2000/Paybag/issues)

