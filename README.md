# awesome-wifi-security
A collection of (not-so, yet) awesome resources related to 802.11 security, tools and other things 

## Table of Contents
###TKIP Security
[Practical attacks against WEP and WPA (2008)] (http://dl.aircrack-ng.org/breakingwepandwpa.pdf)

[An Improved Attack on TKIP (2009)  ] (http://link.springer.com/chapter/10.1007/978-3-642-04766-4_9#page-1)

[Cryptanalysis of IEEE 802.11i TKIP] (http://download.aircrack-ng.org/wiki-files/doc/tkip_master.pdf)


[Enhanced TKIP Michael Attacks (2010)] (http://download.aircrack-ng.org/wiki-files/doc/enhanced_tkip_michael.pdf)

[Plaintext Recovery Attacks Against WPA/TKIP (2013)] (https://eprint.iacr.org/2013/748.pdf)

[Practical verification of WPA-TKIP vulnerabilities (2013)](https://lirias.kuleuven.be/bitstream/123456789/401042/1/wpatkip.pdf)

[On the security of RC4 in TLS (USENIX, 2013)] (http://www.isg.rhul.ac.uk/tls/RC4biases.pdf)

[All Your Biases Belong to Us: Breaking RC4 in WPA-TKIP and TLS (USENIX, 2015)] (https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-vanhoef.pdf)

[A Security Analysis of the WPA-TKIP and TLS Security Protocols (PhD Thesis, 2016)] (https://lirias.kuleuven.be/bitstream/123456789/543228/1/thesis.pdf)

[Predicting and Abusing WPA2/802.11 Group Keys (2016)] (http://papers.mathyvanhoef.com/33c3-broadkey-slides.pdf)


###WiFi Protected Setup (WPS)
####Papers
[Brute forcing Wi-Fi Protected Setup (2011)] (https://sviehb.files.wordpress.com/2011/12/viehboeck_wps.pdf)

[An Investigation into the Wi-Fi Protected Setup PIN of the Linksys WRT160N v2 (2012)](http://ro.ecu.edu.au/cgi/viewcontent.cgi?article=1139&context=ism)

[Offline bruteforce attack on wifi protected setup (*Pixie dust attack*, 2014)] (http://archive.hack.lu/2014/Hacklu2014_offline_bruteforce_attack_on_wps.pdf)

####Tools
[Pixiewps] (https://github.com/wiire/pixiewps): An offline WPS bruteforce utility

[Reaver-wps-fork-t6x] (https://github.com/t6x/reaver-wps-fork-t6x): community edition of Reaver (which includes the Pixie Dust attack)

[Bully] (https://github.com/aanarchyy/bully): new implementation of the WPS brute force attack, written in C.

###Online Cracking Services for PSK

* [Crackq] (https://hashcrack.org/crackq): online distributed GPU-accelerated password cracker designed to help penetration testers and network auditors identify weak passwords
* [http://www.onlinehashcrack.com/] (http://www.onlinehashcrack.com/)
* [http://wpa.darkircop.org/](http://wpa.darkircop.org/)

* [https://www.gpuhash.me/] (https://www.gpuhash.me/)

* [https://hashcrack.org/] (https://hashcrack.org/)

* [Database of vulnerable Wi-Fi Network: router-db.com] (https://router-db.com/)

### WPA-Enterprise
#### Eduroam
[MITM Attack Model against eduroam (2013)] (http://www.eduroam.zm/Maninmiddle.pdf)

[A Practical Investigation of Identity Theft Vulnerabilities in Eduroam (2015)]
 (https://www.syssec.rub.de/media/infsec/veroeffentlichungen/2015/05/07/eduroam_WiSec2015.pdf)

[Server Certificate Practices in Eduroam (2015)] (http://services.geant.net/cbp/Knowledge_Base/Wireless/Documents/cbp-33_server-certificate-practices-in-eduroam.pdf): Best practice document

[Evil Twin Vulnerabilities in Wi-Fi Networks (Bachelor Thesis, 2016)] (http://www.cs.ru.nl/bachelorscripties/2016/Matthias_Ghering___4395727___Evil_Twin_Vulnerabilities_in_Wi-Fi_Networks.pdf)





### Attacks
####KARMA

[Attacking automatic Wireless network selection (2005)] (https://www.trailofbits.com/resources/attacking_automatic_network_selection_paper.pdf)

[Why do Wi-Fi Clientes disclose their PNL for Free Still Today? (2015)] (http://blog.dinosec.com/2015/02/why-do-wi-fi-clients-disclose-their-pnl.html)

[Instant KARMA might still gets you (2015)] (https://insights.sei.cmu.edu/cert/2015/08/instant-karma-might-still-get-you.html)

####Evil Twin

[Infernal twin] (https://n0where.net/automated-evil-twin-attack/)

[Evil Twin vulnerabilities in Wi-Fi networks (Master Thesis, 2016)] (http://www.cs.ru.nl/bachelorscripties/2016/Matthias_Ghering___4395727___Evil_Twin_Vulnerabilities_in_Wi-Fi_Networks.pdf)

###Wireless Routers 

[Scrutinizing WPA2 Password Generating Algorithms in Wireless Routers (WOOT, 2015)](https://www.usenix.org/system/files/conference/woot15/woot15-paper-lorente.pdf)

###Rogue AP 
####Documentation
[Manna from heaven: Improving the state of rogue AP attacks (2015)] (https://www.sensepost.com/blog/2015/improvements-in-rogue-ap-attacks-mana-1-2/): 
* [Video] (https://www.youtube.com/watch?v=i2-jReLBSVk)
* [Slides] (https://defcon.org/images/defcon-22/dc-22-presentations/White-deVilliers/DEFCON-22-Dominic-White-Ian-de-Villiers-Manna-from-Heaven-Detailed-UPDATED.pdf)

####Tools
[hostapd-mana](https://github.com/sensepost/hostapd-mana): hostapd with the attacks described in Defcon 22, and with the ability to rogue EAP access points.

### Privacy
####Papers
[Tracking unmodified smartphones using Wi-Fi monitors (2012)](https://www.cs.uic.edu/pub/Bits/Musa/musa-eriksson-sensys12.pdf)

[Show me your SSIDs; I will show who you are (2012)] (https://blog.rootshell.be/2012/01/12/show-me-your-ssids-ill-tell-who-you-are/)

[Signals from the Crowd: Uncovering Social Relationships through Smartphone Probe (2013, SIGCOM)]
(http://conferences.sigcomm.org/imc/2013/papers/imc148-barberaSP106.pdf)

[I know who you will meet this evening! Linking wireless devices using Wi-Fi probe requests (2012) ] (http://www.nicta.com.au/publications/research-publications/?pid=5583)

[Is Your Android Device Telling the World Where You've Been? (2014)] (http://goo.gl/3XezqR) 

How talkative is your mobile device?: an experimental study of Wi-Fi probe requests (2015)
* [Paper] (https://frdgr.ch/wp-content/uploads/2015/06/Freudiger15.pdf)
* [Slides] (https://frdgr.ch/wp-content/uploads/2015/06/Freudiger.Wisec_.pptx)

[Why MAC Address Randomization is not Enough: An Analysis of Wi-Fi Network Discovery Mechanisms
(2016)] (http://papers.mathyvanhoef.com/asiaccs2016.pdf)
















