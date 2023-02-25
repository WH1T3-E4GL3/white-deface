![deface](https://user-images.githubusercontent.com/118425907/221365125-c93c6c73-e1f7-46b3-8a5c-3a58f77d1387.jpg)


## Author
<a href="https://github.com/WH1T3 L'/"><img title="Github" src="https://img.shields.io/badge/WH173-E4GL3-brightgreen?style=for-the-badge&logo=github"></a>
## Support
[![Instagram](https://img.shields.io/badge/TELEGRAM-red?style=for-the-badge&logo=telegram)](https://t.me/Ka_KsHi_HaTaKe)

# WHITE-DEFACE
This is a simple tool to automatically deface vulnerable websites.

It uses WebDav vulnerability to exploit.
This script sends a PUT requests to the websites given in the targets.txt file. Unauthenticated requests will be accepted and your html script will be uploaded in the website. You will get the link with your script whch you can see it. (sometimes it defaces the homepage directly.)

You need to put your website urls in the targets.txt file and put your deface script in the same folder ie: white-deface. then use the tool


    ⚠️Script kiddies and copy pasters step back, I done a lot effort in making this, dont just copy paste either fork or contobute to this repo.⚠️

# Note

⚠️Only defaces websites with WebDAV vulnerability(Accepts unauthenticated PUT requests)⚠️

# Installation
____________________

    $ apt update -y && apt upgrade -y
    $ pkg install git -y
    $ pkg install python -y
    $ pip2 install requests
    $ git clone https://github.com/WH1T3-E4GL3/white-deface.git
    $ cd white-deface
    $ pip install -r requirements.txt
    $ git pull
    $ python white-deface.py
   
   
# Single installation command
_______________________________________

    apt update -y && apt upgrade -y && pkg install git -y && pkg install python -y && pip2 install requests && git clone https://github.com/WH1T3-E4GL3/white-deface.git && cd white-deface && pip install -r requirements.txt && git pull && python white-deface.py
  
Tool used for vulnerable website defacing

Tool devoloped by white eagle.

Github   : https://github.com/WH1T3-E4GL3

Telegram : https://t.me/Ka_KsHi_HaTaKe


# What the code does


The code is a simple program in Python that attempts to upload a provided HTML file to multiple websites as specified in a target file named "targets.txt". The uploaded HTML file is intended to replace the content of the index page on the target websites. The program uses the "requests" library to handle the HTTP requests. The user is asked to input the name or path of the HTML file to be uploaded. If the file is found, the program then reads the contents of the file and the "targets.txt" file, which contains a list of target websites. The program then loops through each website in the list and attempts to upload the HTML file using a HTTP PUT request. If the upload is successful, a message is displayed indicating that the upload was successful. If the upload fails, a message is displayed indicating that the upload failed.


# ***screenshorts***

# Kali linux:

![whitedeface](https://user-images.githubusercontent.com/118425907/221367054-c8fe2afa-c17f-425f-ab56-10db4217b9e3.png)


# Termux :


![termux](https://user-images.githubusercontent.com/118425907/221367115-684ddd94-fcb3-4b6b-be79-4a0e889b5739.jpg)
