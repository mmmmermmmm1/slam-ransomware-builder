<p align="center">
 <img width="1568px" src="https://www.dropbox.com/s/xqxoemwep6njkf4/Captura.png" align="center" alt="slam ransomware builder" />
</p>
<p align="center">
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/AnderMoralDiaz/slam-ransomware-builder?style=for-the-badge">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/andermoraldiaz/slam-ransomware-builder?style=for-the-badge">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/andermoraldiaz/slam-ransomware-builder?style=for-the-badge">
<img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/andermoraldiaz/slam-ransomware-builder?style=for-the-badge">
<img alt="GitHub all releases" src="https://img.shields.io/github/downloads/andermoraldiaz/slam-ransomware-builder/total?style=for-the-badge">
<img alt="GitHub release (release name instead of tag name)" src="https://img.shields.io/github/v/release/andermoraldiaz/slam-ransomware-builder?include_prereleases&style=for-the-badge">
</p>
<p align="center">
 <h2 align="center">slam ransomware builder</h2>
</p>
 a ransomware compiler that uses the AES256 encryption algorithm, uses vulnerabilities of all kinds and is 100% configurable. In the future the following functions will be added: ransomware mbr, screen locker and LogonUI overwriter
 it has features that NO OTHER COMPILER HAS, it is completely free and easy to use.
 use it on Windows 10-11 on others OS it will not work (but the ransomware generated works fine in windows 7 upwards).

- the mbr ransomware builder is in development
- the screenlocker builder will be developed in the future
- other tools will be developed in the future

## Features

- customized ransom note, you can add variables such as the ip, the name and personal id of the victim, a list of encrypted files, etc...
- you can change the victim's wallpaper
- you can set a custom encryption password
- you can change the ransom note name and extension of the encrypted files.
- you can choose which directories to encrypt from the list, and if they are not in the list, you can add the paths yourself.
- you can choose which extensions to encrypt or encrypt all files
- if there is no internet you can make the ransomware inactive and add a fake error message, as soon as wifi is available the ransomware will start encrypting.
- you can empty the Recycle Bin.
- you can make the ransomware start when you turn on the pc and only encrypt files that are not already encrypted.
- you can make the ransomware ask for administrator permissions.
- you can make the ransomware have administrator permissions WITHOUT ASKING
- you can change the version, description, copyright, icon and all exe information.
- you can change the byte skipping, this is very useful because if you set different bytes than the defaults ONLY YOU will be able to create the decryptor.
- you can run a cmd command, very useful to disable the task manager etc... you will also have a list with commands that I recommend you to add.
- you can send information to a server, when someone gets infected you will get a notification with the time of infection, the id etc... it is very easy to configure.
- you can delete backups.
- you can "auto destroy" the exe, that is to say, when you finish infecting the vicitma, the exe will be deleted.
- you can put it in critical process mode, so if you stop the infection by taskkill or task manager it will cause a bsod.
- you can infect the usb, it will create a copy of the virus with the name you want in all the usb connected.
- you can add custom c# code, with no limits, you will also have a code list that I recommend you, but make sure you know what you are doing (see below);
- you can make a system notification with the icon and message of your choice (I guess this only works on windows 10-11)
- the builder is available in English and Spanish.
- you can set any color in the background or in the text, set a random color every time you start the program or set the builder to rainbow mode.
- you can view a log while compiling the ransomware to see the bugs or whatever, logs are also saved.
- the password is base64 encrypted to make it slightly more difficult to extract the password if the ransomware is decompiled.

## info

>currently the builder is in version 1.5 alpha, it is an alpha because I have not tested it well and there may be some bugs, but it is unlikely to 80%.
the changes of each version are in the releases
## Installation

>download slam ransomware builder installer and click the corresponding buttons, it is important that while you have the program installed you deactivate the antivirus or create an exception in the C:\slam_ransomware_builder folder.

## Images
#### main form
![](https://www.dropbox.com/s/b3xakj67ip9ipf2/principal.PNG?dl=1)
#### settings form
![](https://www.dropbox.com/s/j09rf5bq9y91t7v/ajustes.PNG?dl=1)
#### advanced form 1
![](https://www.dropbox.com/s/o745xrfdhax9cad/a1.PNG?dl=1)
#### advanced form 2
![](https://www.dropbox.com/s/flv5pi72vhuoiaq/a2.PNG?dl=1)
#### advanced form 3
![](https://www.dropbox.com/s/apzh3gipii8shnb/a3.PNG?dl=1)
#### advanced form 4
![](https://www.dropbox.com/s/77dgg47dkvfdnt4/a4.PNG?dl=1)
#### server form
![](https://www.dropbox.com/s/nob2p32nhwmco4r/server.PNG?dl=1)

#### many thanks to:
[![](https://reporoster.com/stars/AnderMoralDiaz/slam-ransomware-builder)](https://github.com/AnderMoralDiaz/slam-ransomware-builder/stargazers)
[![](https://reporoster.com/forks/AnderMoralDiaz/slam-ransomware-builder)](https://github.com/AnderMoralDiaz/slam-ransomware-builder/network/members)

## contact me

<a href="https://youtube.com/UCBF5fDnI8r3fM0pjIPxRsZg">
      <img alt="YouTube" src="https://img.shields.io/badge/YouTube-1E4174?style=for-the-badge&logo=youtube&logoColor=white" />
</a>
<a href="https://instagram.com/_ander_man_">
      <img alt="Instagram" src="https://img.shields.io/badge/Instagram-1E4174?style=for-the-badge&logo=Instagram&logoColor=white" />
</a>
<a href="https://mailto:salchichaybacon@gmail.com">
      <img alt="Gmail" src="https://img.shields.io/badge/gmail-1E4174?style=for-the-badge&logo=Gmail&logoColor=white" />
</a>
<a href="https://twitch.tv/andermoral">
      <img alt="Twitch" src="https://img.shields.io/badge/Twitch-1E4174?style=for-the-badge&logo=Twitch&logoColor=white" />
</a>
<a href="https://discord.gg/eXEskBfhy5">
      <img alt="discord" src="https://img.shields.io/badge/discord-1E4174?style=for-the-badge&logo=discord&logoColor=white" />
</a>
