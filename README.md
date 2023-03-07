# privacy
Privacy, Security, and Digital Sovereignty handbook


# Introduction

This is a guide that first goes over why this is important and then I go over my personal setup and strategies I use. The main goal of this write-up is to inform people and discuss ideas on how individuals to acheive privacy and security.

# Why Privacy, Security, Data and Software Sovereignty is Important.

## Digital Security
If you do a lot of very important things (media, communication, work, etc) digitally or if you store a of assets (bank account, sensitive info, etc) digitally, you are going to want it to be private and secure. The internet can be a highly adversarial environment. Digital security is a form of self defense.

## Digital Privacy
Privacy ultimately ties closely with basic human rights (freedom, democracy, freedom of speech, property rights, etc.)

The way I think about privacy and security is that it really just an means to an end. I would rather just be able to go about my day doing things I enjoy rather than thinking about how I am digitally vulnerable. Full privacy should be something that is given as an option and that is non-negotiable. Right now it is marketed to us as a feature.

## Digital Sovereignty
I highly recommend reading ["WhatsApp and the domestication of users"](https://seirdy.one/posts/2021/01/27/whatsapp-and-the-domestication-of-users/). The TL;DR of this article is WhatsApp is the perfect example of how mainstream digital services get users locked in to their service to ultimately exploit users and then the importance of (libre software)[https://web.archive.org/web/20230227222905/https://www.gnu.org/philosophy/free-software-even-more-important.html] (if you dont know what that is, watch [Richard Stallman’s TED talk](https://www.fsf.org/blogs/rms/20140407-geneva-tedx-talk-free-software-free-society/) to get an idea of it). 

Rather then using a service because of its convenience, we should consider its privacy, security, governance and how much sovereignty the users have. Sometimes there is a spectrum and trade off between convenience versus privacy and security. I just think it is a trade off we need to be aware of and willing to accept. Take a browse into https://tosdr.org/ and things like (Transparency Reports)[https://transparencyreport.google.com/?hl=en]. These big tech companies do not protect your privacy and I am not okay with the government having a backdoor into our private data. All of these government

It takes a lot of learning and work to opt-out into alternative solutions, therefore I am writing I am sharing my current solution for review and discussion. 

This is also a longer discussion so feel free to contact me if you want to discuss further.

# Resources I used

## Websites

+ [Anonymous Planet](https://anonymousplanet.org/) - I highly recommended reading through this guide and it’s foot notes. This will take a lot of time but it is well worth it. Read the section “Understanding some basics of how some information can lead back to you and how to mitigate some:” to learn about how identifiable you are on “Clearnet” (internet without TOR/VPN) and the possibilities RFID, WI-FI, IP addresses, etc.  
+ [Privacy Guides](https://www.privacyguides.org/en/) - Go through the knowledge base, think about your threat model (what you want to protect) and look through all its recommended tools. 
+ [The New Oil](https://www.thenewoil.org) - good guide for beginners for practical advice. 
+ https://www.privacytools.io/ -  I do not like all its recommendations but a good source to consider
+ https://privsec.dev/ - still going through this one.

## Books

+ Michael Bazzel - [Extreme Privacy: What it Takes to Disappear 4th edition](https://www.amazon.com/Extreme-Privacy-What-Takes-Disappear/dp/B0898YGR58)- This is the book that introduced me to privacy. The author worked at the FBI in intelligence previously.

+ Michael Bazzel - [OSINT 10th edition - Great book to get into Open Source Intelligence](https://www.amazon.com/OSINT-Techniques-Resources-Uncovering-Information/dp/B0BRDLYX75). You can uncover a lot of info with an email or phone number. It gets even more interesting when you get into breached data and stealer logs for security research purposes.

## Youtube/Odysee

+ Sun Knudsen - [Youtube](https://www.youtube.com/@SunKnudsen) - Sun is a self proclaimed security and privacy researcher. He previosly worked on an analytics tool (Lickstats), realized the invasiveness in tracking technologies. He does a really good job with his videos in explaining and offering step by step guides along with an updated guide on his [website](https://sunknudsen.com). I really like his transparent and personable personality and how he seeks his work to be peer reviewed.
+ Mental Outlaw - [Odysee](https://odysee.com/@AlphaNerd:8) - Kenny is a Linux enthusiast & network engineer. His videos are  commentary around recent tech events, Linux related stuff, digital privacy, and some rants. He does a really good job of explaining stuff.
+ Techlore - [Youtube](https://www.youtube.com/channel/UCs6KfncB4OV6Vug4o_bzijg) - I have not watched that many Techlore videos but they are good for a less technical audience.
+ [Luke Smith](https://www.youtube.com/@LukeSmithxyz/videos) - mostly videos on Linux, some on privacy. He is about being independent and sovereign in every sense. He might be a bit radical and even alt right by some standards. I personally think he has a pretty interesting perspective on things and he explains himself pretty well.
+ [The Hated One](https://www.youtube.com/@TheHatedOne) - I mostly watched the ones on TOR
+ 

# My Current Set Up and Strategies

## Note on implementing these strategies

Reach out if you need help with anything. I can help. Also, there is no elitism or moral superiority in whatever decision you make.

# Mobile Devices

Consider [this video](https://yewtu.be/watch?v=QUYODQB_2wQ) by the Wall Street Journal. If you put you sensitive data and functionality on your phone you are going to want to make it secure. Also, reconsider what you put on your phone and the worst case scenario if someone has access to it.

I have a iPhone and I also use GrapheneOS with a Pixel 6a.  I am slowly transitioning from iPhone to GrapheneOS.

# Computers

Having one computer be both secure/private and usable/convenient is impossible. The key to it is compartmentalization. Maybe something like [this](https://invisiblethingslab.com/resources/2014/Software_compartmentalization_vs_physical_separation.pdf). 

## Linux

I recently bought a Thinkpad and I run Ubuntu, Mint and Tails off of it. Still playing around and trying to learn.

## MacOS

+ [DrDuh Github Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide) - I am still going through this list.
+ [Little Snitch](https://obdev.at/products/littlesnitch/index.html) as a Application Firewall to control all network calls that are made. (LuLu is a open source alternative) Sun Knudsen has a video about how to use Little Snitch, why it is so important. 

The most general advice I can give is go through all the settings and change it to how you see fit. I do not sign into apple ID and I do not recommend using iCloud and Siri.

# Web Browsers

I mostly use Brave and Firefox. I have not spend enough time on browser set up yet. I use [Firefox Containers](https://support.mozilla.org/en-US/kb/containers) and uBlock Origin to control the network calls. I recommend going through [Arkenfox's firefox settings](https://github.com/arkenfox/user.js/). There are a lot of other browsers to consider like Librewolf or an ungoogled Chromium.

# Encrypted Storage & Backups

I use [Veracrypt](https://veracrypt.fr/en/Home.html) containers to store all my sensitive data. That container is encrypted password. You can even have a hidden volume for plausible denability. In a later section, I will list out what I store in there to give you an idea. I backup this container on multiple USB flash drives, SD cards, and Proton Drive. I have given a copy to a few friends and family so in any case of emergency I can have them send me that container.

## Files to put in a USB/SD card backup

+ Bitwarden Password Manager backed up as csv
+ KeePassXC files like one for Recovery Codes, 2FA reset codes.
+ Contacts
+ PGP/SSH keys
+ Identification Document (passport, drivers, birth certificate, health insurance etc.)
+ Personal Docs

## VPNs

There are a lot of ads around VPNs and I think it has created a misconception on how they give you privacy. The only thing VPNs do is shift your trust from your ISP to your VPN provider. VPNs help you achieve privacy by concealing our IP address from websites you visit.

I currently use Proton VPN when browsing the internet. I am thinking about trying out https://njal.la/vpn/ or Mullvad VPN. And then eventually setting up my own VPN server with a privacy conscious web hosting service. ([something like this](https://www.youtube.com/watch?app=desktop&v=7yC-gJtl9mQ))

## Email with email masking service

I currently use Protonmail. 

For most, if you use the same email address for a lot of things, it is very closely tied to your real identity. With OSINT a lot of information can be uncovered with that email address. This is why you should use a email forwarding service.

I currently use Simple Login. For anything that is not important, I provide an alias email address that gets forwarded to a Inbox Folder.

Here is my email strategy and addresses that I have

+ real.name@pm.me : This is considered a public email address. Provided to anyone that already knows my real identity. These will probably 
+ numbers@pm.me : This is a generic email without any personal identifying information. I try to keep these addresses as non-public as possible because I use them with important services like financial services. I think there are still some 4 digit domains with @pm.me still available.

I have a lot of other email addresses but feel free to compartmentalize whatever you want. Like maybe one for purchases, alias names, etc.

I have also exported all my emails out of old gmail and set up a forwarding/delete to a masked email.

# Password Manager

It is very important to use a Password Managers. Security researchers unanimously agree that you must be using a password manager. It is so suprising to me how many people do not use one. If you do not use one, you are probably reusing passwords. People that claim that are not reusing passwords probably claim that they “have their own algorithm“. That is not secure because it is probably not hard to decode or decrypt that “algorithm” once 1 of them gets breached and what makes that password unique depends on the name of the service.

I currently use a Bitwarden Premium ($10/year) for 2FA and trusted emergency access. 

I use multiple (KeePassXC)[https://keepassxc.org/] vaults (which are just files) for more sensitive secrets like recovery codes, 2FA reset codes, backup codes (those 3 are literally the same thing?), SSH keys, PGP keys, a few not all of my BIP 39 seed phrases, etc.

KeePassXC is more secure because it drastically reduces the attack surface of not being hosted in a cloud server and also reduces 3rd party risk.

## Making a good Master Password

Making a good Master password or passphrase is not easy but extremely important. I recommend watching Computerphile video and Sun Knudsen cover how password entropy works. A good master password should be memorable and have more than 40 bits of entropy (maybe more depending on your threat model). Consider writing it down and then destroying that piece of paper when you are confident you memorized it.

### Idea of a list of passwords you actually do need to memorize

+ "master password" to password manager and veracrypt hidden containers
+ password to unlock laptop and devices and Metamask other wallets etc. (this is a weak password, less than 8 characters)
+ 4 PIN number for ATM cards, ledger device etc.
+ very weak password for outer volume veracrypt.

# 2FA

The order of preference of 2FA is

+ Hardware key like (Yubikey, Onlykey, Nitrokey, Solokey, etc)
+ TOTP Authenticators like (Authy, Aegis, etc)
+ Email
+ Phone number

It is important to use 2FA because it significantly increases your security and much harder to hack you.

# Phone numbers and VOIP numbers

It is likely the phone number you give out is very closely tied to your identity with data brokers like truecaller. Your friends saved your number and then apps will harvest your contacts data when you sync it. I “retired my 10+ year phone number by porting it over to my google voice number.

If you want to text/call with Twilio or Telnyx VOIP numbers. You can host your own version of this [VOIP app](https://github.com/0perationPrivacy/VoIP) with the instructions [here](https://inteltechniques.com/voip.suite.html). Or you can use the [hosted one](https://voip.operationprivacy.com/). 

An easier and free option is to use Google Voice. This is what I use when anonymity is not important and a VOIP number is accepted.

If you are price insensitive, https://crypton.sh is a solid service for a non-VOIP private number.

# Messaging Texting Platforms

Privacy Guides covers this section pretty well. Signal has great E2EE encryption. It has pretty good user adaption.

Matrix is great as a open platform and protocol. I really like the mission they are striving for. I will try to create my own Matrix server when I get a chance.

The thing getting to private text messaging is incredibly difficult because 2 people need to be on the same protocol or platform. Adaption of using something just slightly more difficult is so difficult and network effects are incredibly strong. Probably much stronger than you think. I currently have iMessage with an email but I really want to delete it. Once I delete it, I will be unable to contact some people unless its SMS text and that is actually worse.

# Social Media

I deleted all the data on FB, IG. The only thing holding me back from deleting/deactivating them is the friend connection I have. Once I figure out a way to export them, I will probably delete the account. I want to get to a point where I do not need these platforms with closed ecosystems to manage that for me.

In the long run, Social Media usage has been a net negative on me. I also think it is mostly a net negative for most unless you make money on them or you have extreme discipline to only use certain features.

Use https://libredirect.github.io/ as a proxy to browse social media.

# RSS Feed

RSS is a open protocol to subscribe to any media. I really like it because it gives you full control over your news feed. It is important to curate your own information diet. I currently use Fluent Reader but I am still working on building out my feed.

# Payment

For transactions and payments I want to more privacy. I use privacy.com. 

More info on Monero XMR will be added later.

AML/CFT (Anti-Money Laundering/Combating the Financing of Terrorism) is a euphemism for warrantless surveillance.  All your banking activity is reported to the government. The 4th amendment is not doing anything anymore.

# Digital Assets / Cryptocurrency

I use a Ledger to generate my BIP39 seed phrase, which is a 24 seed phrase. I write it down on paper and put it in a safe place. I am only comfortable writing this down even though it is not the best for OpSec (Operational Security) because I store the majority of the assets in the 25th Passphrase wallets. Read more here [Ledger](https://www.ledger.com/academy/passphrase-an-advanced-security-feature). I then use BIP39 passphrase or “25th passphrase“ memorize it and back it up in a KeePassXC vault. BIP39 passphrase provides plausible deniability, similarly to hidden volumes on Veracrypt.

# PGP

OpenPGP is a open standard for signing and encrypting. It is used in the Gnu/Linux world and for email encryption. If you are a developer that contributes to open source or wants to release software independently, you need your own PGP keys so people can verify that the software was released by you. If not, you need to rely on Apple App Store and Google Play Store as gatekeepers to release software.

# OSINT

Bellingcat's Online Investigation Toolkit [bit.ly/bcattools]
https://docs.google.com/spreadsheets/d/18rtqh8EG2q1xBo2cLNyhIDuK9jrPGwYr9DI2UncoqJQ/htmlview#

# Software I use

+ https://standardnotes.com/
+ https://vscodium.com/


# Contact
+ Signal +1 737 201 1700
+ Matrix https://matrix.to/#/@carrybell:matrix.org
+ [SimpleX](https://simplex.chat/contact#/?v=1-2&smp=smp%3A%2F%2FSkIkI6EPd2D63F4xFKfHk7I1UGZVNn6k1QWZ5rcyr6w%3D%40smp9.simplex.im%2Fo3BDYTTERKYtumjYtTVW_TXC0tEfRvyO%23%2F%3Fv%3D1-2%26dh%3DMCowBQYDK2VuAyEA8f8ZdvWpvSNk8JzCBr2Mu7ARBQkB3TUXXDgveQrUlFE%253D%26srv%3Djssqzccmrcws6bhmn77vgmhfjmhwlyr3u7puw4erkyoosywgl67slqqd.onion)

# FAQ

## Is Apple good with privacy and security?
No, I think a lot of people are deceived by their marketing. Apple is only good with privacy and security against 3rd party applications in a way that benefits themselves. They strongly enforce a closed ecosystem and act as gatekeepers. Their ["Standard data protection"](https://support.apple.com/en-us/HT202303) holds the encryption keys in their data centers so you have no sovereignty. Consider this list in TOSDR [![](https://shields.tosdr.org/en_158.svg)](https://tosdr.org/en/service/158)



