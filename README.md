# Arzenal 

*This repository is just an archive of tools used both in CTF challenges and daily use.*

--------------

Binary
---------------------
* [Checksec](https://raw.githubusercontent.com/RobinDavid/checksec/master/checksec.sh)

    Checksec is a bash script to check executable properties like (PIE, RELRO, PaX, Canaries, ASLR).

Defeating UAC
---------------------
* [UACME](https://github.com/hfiref0x/UACME)

    Defeating Windows User Account Control by abusing built-in Windows AutoElevate backdoor

Discovery
---------------------
* [GoBuster](https://github.com/OJ/gobuster)

    A directory, files and also DNS brute-forcer written in go. 

Enumeration
----------------------
* [Smtp-User-Enum](http://pentestmonkey.net/tools/user-enumeration/smtp-user-enum)

    Username guessing tool primarily for use against the SMTP service

Information Gathering
---------------------
* [DNSEnum](https://github.com/fwaeytens/dnsenum)

    Multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks.
    There is also a [bash version](https://github.com/theMiddleBlue/DNSenum) of the same tool, that works great and could be    combined with shodan.    

Linux Post-Exploitation
-----------------------
* [Kernelpop](https://github.com/spencerdodd/kernelpop)

    kernelpop is a framework for performing automated kernel vulnerability enumeration and exploitation on Linux and Mac.

MITM
---------------------
* [Responder](https://github.com/lgandx/Responder)

    An excellent tool to abuse of LLMNR and NBT-NS weakness capturing victims NTMLv1/v2 hashes and relaying them for authentication to other systems. It comes with many useful tools as [MultiRelay](https://github.com/lgandx/Responder/blob/master/tools/MultiRelay.py).
    
Powershell Utilities
----------------------
* [Empire](https://github.com/EmpireProject/Empire)

     Empire is a post-exploitation framework that implements the ability to run PowerShell agents without needing powershell.exe, rapidly deployable post-exploitation modules

* [Invoke-CradleCrafter](https://github.com/danielbohannon/Invoke-CradleCrafter)

    A PowerShell v2.0+ compatible PowerShell remote download cradle generator and obfuscator.

* [Invoke-Obfuscation](https://github.com/danielbohannon/Invoke-Obfuscation)

    A PowerShell v2.0+ compatible PowerShell command and script obfuscator

* [Nishang](https://github.com/samratashok/nishang)

    Nishang is a framework and collection of scripts and payloads which enables usage of PowerShell for offensive security, penetration testing and red teaming. 

* [Posh-SecMod](https://github.com/darkoperator/Posh-SecMod)

    A collection of Powershell v3.0 post-exploitation moludes

* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit)

    A collection of offensive Powershell modules

Steganography
---------------------
* [Stegsolve](http://www.caesum.com/handbook/stego.htm)
   
    Java tool that tries different renditions of image in order to reveal something hidden. ([direct download](http://www.caesum.com/handbook/Stegsolve.jar)).
    
Web Services / Resources
---------------------

* [FactorDB](http://factordb.com)

    This a tool used to store known factorizations for any number. It can be used to check for known factors, check for primality, calculate group orders and so on.

* [G0tmi1k: Linux enumeration](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)

    This is a mixture of really useful commands to get information out of linux. It's just a **basic & rough guide**.

* [GTFOBins](https://gtfobins.github.io/)

    GTFOBins is a curated list of Unix binaries that can be exploited by an attacker to bypass local security restrictions.
    It contains legitimate functions that can help to escalate or maintain elevated privileges, transfer files, spawn shells adn facilitate the other post-exploitations tasks.

* [JS Beautifier Online](https://www.cleancss.com/javascript-beautify/)

    A simple web app that unminifies and beautifies js and html codes. It works very well, probably one of the best out there.
    It offers also many other services, such as formatters, encoders, hash generators and so on.

* [LOLBAS](https://lolbas-project.github.io/)

    LOLBAS is a list of windows binaries, scripts and libraries that can be exploited by an attacker to bypass local security restrictions. It inspired GTFOBins!
 
* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings/)

    A list of useful payloads and bypass tecniques. 
    
* [NPiet Online](https://www.bertnase.de/npiet/npiet-execute.php)

    A simple web service to solve Piet programs. Piet is a programming language in which programs look like abstract paintings. 
