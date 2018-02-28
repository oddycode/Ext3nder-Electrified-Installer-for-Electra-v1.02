# Ext3nder-Electrified-Installer-for-Electra-v1.02
/! USE AT YOUR OWN RISKS !\
I TESTED THIS PACKAGE ON 2 DEVICES (iPhone 7) RUNNING IOS 11.0 AND ELECTRA V1.02 AND IT WORKS PERFECTLY. 
I AM NOT RESPONSABLE OF POTENTIAL DAMAGES OR YOUR UTILISATION OF MY .DEB FILE/EXT3NDER

I updated myself the Ext3nder installer that julioverne has released for Electra betas. This .deb file is the result of some hours of work because I'm new in IOS tweaks.
At the begining, I was doing it because I love touching files of my device, and because I wanted to use Ext3nder, but it wasn't updated. This package should be used by me and ONLY me, but a friend told me to publish it on github. I said "why not!". So I'm here.
Please consider I AM NOT A DEVELOPER. I am only a curious Electra user.

This package is based on "Ext3nder Electrified for Electra betas" by Julioverne (I don't completely remember if it's him).

To install it, 
1 : download the .deb file 
2 : SSH into your device (by using WinSCP or another software)
3 : Copy the .deb file in /electra (NOTE : You can copy it anywhere. Copy it where you want. You can copy it in the root of your phone if you want)
4 : open an ssh terminal (PuTTY, etc..)
5 : type "cd {path of the .deb file}
6 : type "dpkg -i Ext3nder-electrified-final.deb" (NOTE : If the .deb file has another name, replace "Ext3nder-electrified-final.deb" by "YourFileName.deb"
7 : It's finished!
Enjoy Ext3nder
NOTE : If you want to install it manually, extract the .deb file, and run the "install.sh". Because if you do it completely manually, it wont work. (Well.. for me it didn't work).
If you want to uninstall it, you can use the "uninstall.sh" file in the root of your device, or you can do it from Cydia. You'll see "Ext3nder Installer" installed in Cydia. You safely can remove it by using the "Uninstall" button of Cydia.

If someone wants to upload this .deb on his own Cydia Repository, I agree. BUT remember I'm not a developer. Just an Electra User. I'd like you to send me a message saying "Hey Laizrod. Can I upload "your" .deb on my repo?" And I'll answer "Yes, of course you can ^^"

If you need to say "thank you" to someone, you need to say it to Julioverne ^^


                                                           KNOWN ISSUES:
 "I removed Ext3nder by using Cydia and the icon is still here!"
 - run uicache
 "I installed it, but the icon doesn't show/or the app crashes on launch"
 - use "uninstall.sh" in the root of you device, then uninstall it via Cydia
 "How to use Ext3nder?"
 - Guys ! WHAT THE F**K. THAT'S NOT ISSUE MY DUDE. If you don't know how to use Ext3nder, check on the Internet ^^ (Don't worry, it's easy). BUT. I have to tell you something. Individual "resign" button doesn't work. That's not my fault. "Ext3nder-Electrified for Electra betas" had this bug too. This tool won't resign apps not signed by you. If you installed an IPA from Tutuapp (or any other tool like it) it won't work. To automatically sign an IPA file (like Electra), turn "AUTO SIGNER IPA" on, and (with an SSH software like WinSCP) upload your ipa file into "/var/mobile/Documents/Ext3nder/AutoSign".

I think I told everything.
If you have a question, a suggestion, or an issue, even if I'm not a developer, I will trying to help you ^^
