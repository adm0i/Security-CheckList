[![Awesome](https://awesome.re/badge-flat2.svg)](https://github.com/zbetcheckin/Security_list)
[![Financial Contributors on Open Collective](https://opencollective.com/personal-security-checklist/all/badge.svg?label=financial+contributors)](https://opencollective.com/personal-security-checklist) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/LICENSE-CC_BY_4.0-00a2ff?&style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Contributors](https://img.shields.io/github/contributors/lissy93/personal-security-checklist?color=%23ffa900&style=flat-square)](https://github.com/Lissy93/personal-security-checklist/graphs/contributors)

# Personal Security Checklist

> A curated checklist of tips to protect your dgital security and privacy

**Too long? 🦒** See the [TLDR version](/2_TLDR_Short_List.md) instead.

#### See Also
- [Why Privacy & Security Matters](/0_Why_It_Matters.md)
- [Privacy-Respecting Software](/5_Privacy_Respecting_Software.md)
- [Privacy & Security Gadgets](/6_Privacy_and-Security_Gadgets.md)
- [Further Links + More Awesome Stuff](/4_Privacy_And_Security_Links.md)

## Contents

[![-](https://i.ibb.co/0ZV22MT/1-passwords.png) Passwords](#passwords)<br>
[![-](https://i.ibb.co/thf142G/2-2fa.png) 2 Factor Authentication](#2-factor-authentication)<br>
[![-](https://i.ibb.co/N7D7g6D/3-web.png) Browsing the Web](#browser-and-search)<br>
[![-](https://i.ibb.co/7yQq5Sx/5-email.png) Email](#emails)<br>
[![-](https://i.ibb.co/HT2DTcC/6-social.png) Social Media](#social-media)<br>
[![-](https://i.ibb.co/NjHcZJc/4-vpn.png) Networking](#networking)<br>
[![-](https://i.ibb.co/J255QkL/7-devices.png) Mobile Phones](#mobile-devices)<br>
[![-](https://i.ibb.co/SvMPntJ/10-os.png) Personal Computers](#personal-computers)<br>
[![-](https://i.ibb.co/3N3mszQ/9-router.png) Smart Home](#smart-home)<br>

## Passwords

Most reported data breaches are caused by the use of weak, default or stolen passwords (according to [this Verizon report](http://www.verizonenterprise.com/resources/reports/rp_dbir-2016-executive-summary_xg_en.pdf)). Massive amounts of private data have been, and will continue to be stolen because of this.

Use strong passwords, which can't be easily guessed or cracked. Length is more important than complexity (at least 12+ characters), although it's a good idea to get a variety of symbols. Ideally you should use a different and secure password to access each service you use. To securely manage all of these, a password manager is usually the best option. [This guide](https://heimdalsecurity.com/blog/password-security-guide/) gives a lot more detail about choosing and managing passwords.

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Use a strong password** | Recommended | Try to get a good mixture of upper and lower-case letters, numbers and symbols. Avoid names, places and dictionary words where possible, and aim to get a decent length (a minimum of 12+ characters is ideal). Have a look at [HowSecureIsMyPassword.net](https://howsecureismypassword.net) and [How Long will it take to Crack my Password](https://www.betterbuys.com/estimating-password-cracking-times/) to get an idea of what a strong password is. See [this guide](https://securityinabox.org/en/guide/passwords/) for more information.
**Don’t save your password in browsers** | Recommended | Most modern browsers offer to save your credentials when you log into a site. Don’t allow this! As they are not always encrypted, hence can allow someone to gain easy access into your accounts. Also do not store passwords in a .txt file or any other unencrypted means. Ideally use a reputable password manager.
**Use different passwords for each account you have** | Recommended | If your credentials for one site get compromised, it can give hackers access to your other online accounts. So it is highly recommended not to reuse the same passwords. Again, the simplest way to manage having many different passwords, is to use a [password manager](https://en.wikipedia.org/wiki/Password_manager). Good options include [BitWarden](https://bitwarden.com), [1Password](https://1password.com), or for an offline app without sync [KeePass](https://keepass.info) / [KeePassXC](https://keepassxc.org).
**Be cautious when logging in on someone else’s device** | Recommended | When using someone else's machine, ensure that you're in a private session (like Incognito mode, Ctrl+Shift+N) so that nothing gets saved. Ideally you should avoid logging into your accounts on other people's computer, since you can't be sure their system is clean. Be especially cautious of public machines, or when accessing any of your secure accounts (email, banking etc.).
**Avoid password hints** | Optional | Some sites allow you to set password hints. Using this feature makes it easier for hackers.
**Never answer online security questions truthfully** | Optional | If a site asks  security questions (such as place of birth, mother's maiden name or first car etc), don't provide real answers. It is a trivial task for hackers to find out this information. Instead, create a password inside your password manager to store your fictitious answer.
**Don’t use a 4-digit PIN to access your phone** | Optional | Don’t use a short PIN to access your smartphone or computer. Instead, use a text password. Pins or numeric passphrases are much easier crack, (A 4-digit pin has 10,000 combinations, compared to 7.4 million for a 4-character alpha-numeric code).
**Use an offline password manager** | Advanced | Consider an offline password manager, encrypted by a strong password. If you work across two or more computers, this could be stored on an encrypted USB. [KeePass](http://keepass.info/) is a strong choice.
**If possible, try to avoid biometric and hardware-based authentication** | Advanced | Fingerprint sensors, face detection and voice recognition are all hackable. Where possible replace these with traditional strong passwords.

**See also** [Recommended Password Managers](/5_Privacy_Respecting_Software.md#password-managers)


## 2-Factor Authentication

This is a more secure method of logging in, where you supply not just your password, but also an additional code usually from a device that only you have access to.

Check which websites support multi-factor authentication: [twofactorauth.org](https://twofactorauth.org)

**2FA Apps**: [Authy](https://authy.com/) *(with encrypted sync- not open source)*,   [Authenticator Plus](https://www.authenticatorplus.com), [Microsoft Authenticator](https://www.microsoft.com/en-us/account/authenticator) and [LastPassAuthenticator](https://lastpass.com/auth/) (synced with your LastPass). For open source Android-only apps, see [Aegis](https://getaegis.app), [FreeOTP](https://play.google.com/store/apps/details?id=org.fedorahosted.freeotp) and [AndOTP](https://play.google.com/store/apps/details?id=org.shadowice.flocke.andotp). [See more](/5_Privacy_Respecting_Software.md#2-factor-authentication)

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Enable 2FA on Security Critical Sites** | Recommended | In account settings, enable 2-factor authentication. Ideally do this for all your accounts, but at a minimum for all security-critical logins, (including your password manager, emails, finance and social sites).
**Keep backup codes safe** | Recommended | When you enable 2FA, you'll be given a few one-time codes to download, in case you ever lose access to your authenticator app or key. It's important to keep these safe, either encrypt and store them on a USB, or print them on paper and store them somewhere secure like a locked safe. Delete them from your computer once you've made a backup, in case your PC is compromised.
**Don't use SMS to receive OTPs** | Optional | Although SMS 2FA is certainly better than nothing, there are many weaknesses in this system, (such as SIM-swapping) ([read more](https://www.theverge.com/2017/9/18/16328172/sms-two-factor-authentication-hack-password-bitcoin)). Therefore avoid enabling SMS OTPs, even as backups.
**Don't use your Password Manager to store 2FA tokens** | Optional | One of the quickest approaches is to use the same system that stores your passwords, to also generate and fill OTP tokens, both LastPass and 1Password have this functionality. However if a malicious actor is able to gain access to this, they will have both your passwords, and your 2FA tokens, for all your online accounts. Instead use a separate authenticator from your password manager.
**Consider a hardware 2FA Key** | Optional | A physical 2FA key generates an OTP when inserted. Have a look at [NitroKey](https://www.nitrokey.com/) (open source), [YubiKey](https://www.yubico.com/) or [Solo Key](https://amzn.to/2Fe5Icw). You can also use it as a secondary method (in case your phone is lost or damaged). If this is your backup 2FA method, it should be kept somewhere secure, such as a locked safe, or if you use as physical key as your primary 2FA method, then keep it on you at all times.

**See also** [Recommended 2FA Apps](/5_Privacy_Respecting_Software.md#2-factor-authentication)


## Browser and Search

Most modern web browsers support add-ons and extensions. These can access anything that you do online so avoid installing anything that may not be legitimate and check permissions first. Be aware that every website that you interact with, including search engines, will likely be keeping records of all your activity. Last year Kaspersky reported [over a million data exploits caused by malicious sites](https://securelist.com/it-threat-evolution-q1-2017-statistics/78475/).

For more browser security pointers, check out: [Here’s How To Get Solid Browser Security](https://heimdalsecurity.com/blog/ultimate-guide-secure-online-browsing/).

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Deactivate ActiveX** | Recommended | [ActiveX](https://en.wikipedia.org/wiki/ActiveX) is a browser extension API that is only supported by Microsoft Internet Explorer. It's enabled by default but is barely used for legitimate plugins these days. However, it gives plugins so much control that ActiveX malware is still around and as dangerous as ever. See [this article](https://www.howtogeek.com/162282/what-activex-controls-are-and-why-theyre-dangerous/) for more details. Better yet, use a modern browser instead of Internet Explorer. Note that Microsoft Edge doesn't support ActiveX.
**Disable Flash** | Recommended | Adobe Flash is infamous for its history of security vulnerabilities (a few of which you can [read about here](https://www.comparitech.com/blog/information-security/flash-vulnerabilities-security/)). See [this guide](https://www.howtogeek.com/222275/how-to-uninstall-and-disable-flash-in-every-web-browser/), on how to disable Flash player, or [this guide for more details on how dangerous it can be](https://www.tomsguide.com/us/disable-flash-how-to,news-21335.html). Adobe will end support for Flash Player in December 2020.
**Block Trackers** | Recommended | Consider installing a browser extension, such as [Privacy Badger](https://www.eff.org/privacybadger), to stop advertisers from tracking you in the background.
**Block scripts from bad origin** | Recommended | Use an extension such as [uBlock Origin](https://github.com/gorhill/uBlock), to block anything being loaded from an external or unverified origin.
**Force HTTPS only traffic** | Recommended | Using an extension such as [HTTPS Everywhere](https://www.eff.org/https-everywhere), will force all sites to load securely.
**Only use trusted browser add-ons and extensions** | Recommended | Both Firefox and Chrome web stores allow you to check what permissions/access rights an extension requires before you install it. Check the reviews. Only install extensions you really need, and removed those which you haven't used in a while. Extensions are able to see, log or modify anything you do in the browser, and some innocent looking browser apps, have malicious intentions.
**Always keep your browser up-to-date** | Recommended | Browser vulnerabilities are constantly being discovered and patched, so it’s important to keep it up to date, to avoid a zero-day exploit. You can [see which browser version your using here](https://www.whatismybrowser.com/), or follow [this guide](https://www.whatismybrowser.com/guides/how-to-update-your-browser/) for instructions on how to update.
**Use a private search engine** | Optional | Google tracks, logs and stores everything you do, but also displays biased results. Take a look at [DuckDuckGo](https://duckduckgo.com) or [StartPage](https://www.startpage.com). Neither store cookies nor cache anything. [Read more](https://hackernoon.com/data-privacy-concerns-with-google-b946f2b7afea) about Google Search Privacy.
**Consider a privacy browser** | Optional | Google openly collects usage data on Chrome usage, as does Apple and Microsoft. Switching to a privacy-focused browser will minimize background data collection, cross-origin cookies and third-party scrips. A popular option is [Brave Browser](https://brave.com/?ref=ali721), or [Firefox](https://www.mozilla.org/en-GB/firefox/new/) with a [few tweeks](https://restoreprivacy.com/firefox-privacy). Others include [Bromite](https://www.bromite.org/), [Epic Browser](https://www.epicbrowser.com/index.html) or [Comodo](https://www.comodo.com/home/browsers-toolbars/browser.php), [see more](/5_Privacy_Respecting_Software.md#browsers). The most secure option is [Tor Browser](https://www.torproject.org/).
**Use DNS-over-HTTPS** | Optional | Traditional DNS makes requests in plain text for everyone to see. It allows for eavesdropping and manipulation of DNS data through man-in-the-middle attacks. Whereas [DNS-over-HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) performs DNS resolution via the HTTPS protocol, meaning data between you and your DNS resolver is encrypted. You can follow [this guide to enable in Firefox](https://support.mozilla.org/en-US/kb/firefox-dns-over-https), for see [CoudFlares 1.1.1.1 Docs](https://1.1.1.1/help).
**Disable WebRTC** | Optional | [WebRTC](https://webrtc.org/) allows high-quality audio/video communication and peer-to-peer file-sharing straight from the browser. However it can pose as a privacy leak, especially if you are not using a proxy or VPN. In FireFox WebRTC can be disabled, by searching for, and disabling `media.peerconnection.enabled` in about:config. For other browsers, the [WebRTC-Leak-Prevent](ttps://github.com/aghorler/WebRTC-Leak-Prevent) extension can be installed. [uBlockOrigin](https://github.com/gorhill/uBlock) also allows WebRTC to be disabled. To learn more, [check out this guide](https://buffered.com/privacy-security/how-to-disable-webrtc-in-various-browsers/).
**Don't Connect to Open WiFi networks** | Optional | Browsing the internet while using public or open WiFi may leave you vulnerable to man-in-the-middle attacks, malware distribution and snooping. Some hotspots may also be unencrypted, or even malicious. If you do need to briefly use a public WiFi network, ensure you disable file sharing, only visit HTTPS websites and use a VPN. Also remove the network from your saved WiFi list after. See the [networking](#networking) section for more details.
**Use Tor** | Advanced | [The Tor Project](https://www.torproject.org/) provides a browser that encrypts and routes your traffic through multiple nodes, keeping users safe from interception and tracking. The main drawbacks are speed and user experience, as well as the possibility of DNS leaks from other programs (see [potential drawbacks](https://github.com/Lissy93/personal-security-checklist/issues/19)) but generally Tor is one of the most secure browser options for anonymity on the web.

**Use different browsers, for different tasks** | Advanced | Compartmentalizing your activity can make it significantly harder for a malicious actor, company or government to get a clear picture of you through your browsing activity. This may include doing online shopping on 1 browser, using another browser, such as Tor for general browsing, and then a 3rd for, say social media.
**Disable JavaScript** | Advanced | Many modern web apps are JavaScript based, so disabling it will greatly decrease your browsing experience. But if you really want to go all out, then it will really reduce your attack surface. Read more about the growing [risk of JavaScript malware](https://heimdalsecurity.com/blog/javascript-malware-explained/).
**Route all desktop traffic via Tor** | Advanced | [Whonix](https://www.whonix.org/) allows for fail-safe, automatic, and desktop-wide use of the Tor network. It's based on Debian, and runs in a virtual machine. Straight-forward to install on Windows, OSX or Linux.

**Recommended Software**
- [Privacy Browsers](/5_Privacy_Respecting_Software.md#browsers)
- [Non-Tracking Search Engines](/5_Privacy_Respecting_Software.md#search-engines)
- [Browser Extensions for Security](/5_Privacy_Respecting_Software.md#browser-extensions)


## Emails

Nearly 50 years since the first email was sent, they’re still very much a big part of our day-to-day life, and will probably continue to be for the near future. So considering how much trust we put in them, it’s surprising how fundamentally insecure this infrastructure is. Email-related fraud [is on the up](https://www.csoonline.com/article/3247670/email/email-security-in-2018.html), and without taking basic measures you could be at risk. 

If a hacker gets access to your emails, it provides a gateway for your other accounts to be compromised, therefore email security is paramount for your digital safety.

It's strongly advised not to use non end-to-end encrypted email, if you can't you should at least follow these guides for simple steps to improve security: [Yahoo](https://heimdalsecurity.com/blog/complete-guide-e-mail-security/#yahoo), [Gmail](https://heimdalsecurity.com/blog/complete-guide-e-mail-security/#gmail), [Outlook](https://heimdalsecurity.com/blog/complete-guide-e-mail-security/#outlook) and [AOL](https://heimdalsecurity.com/blog/complete-guide-e-mail-security/#aol). The easiest way to stay protected is to use a secure mail provider, such as [ProtonMail](https://protonmail.com/) or [Tutanota](https://tutanota.com/).

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Have more than one email address** | Recommended | Keeping your important and safety-critical messages separate from trivial subscriptions such as newsletters is a very good idea. Be sure to use different passwords. This will also make recovering a compromised account after an email breach easier.
**Keep security in mind when logging into emails** | Recommended | Your email account is one of the most important to protect with a secure password. Only sync your emails with your phone, if it is secured (encrypted with password). Don’t allow your browser to save your email password. Prevent man-in-the-middle attacks by only logging in on a secured browser.
**Always be wary of phishing and scams** | Recommended | If you get an email from someone you don’t recognize, don’t reply, don’t click on any links, and absolutely don’t download an attachment. Keep an eye out for senders pretending to be someone else, such as your bank, email provider or utility company. Check the domain, read it, ensure it’s addressed directly to you, and still don’t give them any personal details. Check out [this guide, on how to spot phishing emails](https://heimdalsecurity.com/blog/abcs-detecting-preventing-phishing/).
**Disable automatic loading of remote content in emails** | Recommended | Sometimes advertisers send emails which make reference to remote images, fonts, etc. If these remote resources are loaded automatically, they indicate to the sender that this specific email was received by you.
**Don’t share sensitive information over email** | Optional | Emails are very very easily intercepted. Also you can’t know how secure your recipient's environment is. Don’t share anything personal, such as bank details, passwords, and confidential information over email. Ideally, don’t use email as a primary method of communication.
**Don’t connect third-party apps to your email account** | Optional | If you give a third-party app (like Unroll.me) full access to your inbox, this makes you vulnerable to cyber attacks. The app can be compromised and, as a consequence, cyber criminals would gain unhindered access to all your emails and their contents.
**Consider switching to a more secure email provider** | Optional | Email providers such as [ProtonMail](https://protonmail.com), [CounterMail](https://countermail.com), [HushMail](https://www.hushmail.com/tapfiliate/?tap_a=44784-d2adc0&tap_s=724845-260ce4&program=hushmail-for-small-business) (for business users) or [MailFence](https://mailfence.com?src=digitald) allow for end-to-end encryption, full privacy as well as more security-focused features. See [this guide](https://github.com/OpenTechFund/secure-email) for details of the inner workings of these services.
**Use Aliasing / Anonymous Forwarding** | Advanced | Email aliasing allows messages to be sent to [anything]@my-domain.com and still land in your primary inbox. Effectively allowing you to use a different, unique email address for each service you sign up for. This means if you start receiving spam, you can block that alias and determine which company leaked your email address. <br>[Anonaddy](https://anonaddy.com) is an open source anonymous email forwarding service allowing you to create unlimited email aliases, with a free plan. As is [33Mail](http://33mail.com/Dg0gkEA), and this feature is also included with [ProtonMail](https://protonmail.com/pricing)'s Visionary package.

**See also** [Recommended Encrypted Email Providers](/5_Privacy_Respecting_Software.md#encrypted-email)

## Social Media

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Check your privacy settings** | Recommended | Most social networks allow you to control your privacy settings. Ensure that your profile can only be viewed by people who are in your friends list, and you know personally.
**Only put info on social media that you wouldn’t mind being public** | Recommended | Even with tightened security settings, don’t put anything online that you wouldn’t want to be seen by anyone other than your friends. Don’t rely solely on social networks security.
**Don’t give social networking apps permissions they don’t need** | Recommended | By default many of the popular social networking apps will ask for permission to access your contacts, your call log, your location, your messaging history etc.. If they don’t need this access, don’t grant it.
**Revoke access for apps your no longer using** | Recommended | Instructions: [Facebook](https://www.facebook.com/settings?tab=applications), [Twitter](https://twitter.com/settings/applications), [LinkedIn](https://www.linkedin.com/psettings/third-party-applications), [Instagram](https://www.instagram.com/accounts/manage_access/).
**Use a secure email provider** | Optional | Most email providers completely invade your privacy intercepting both messages sent and received. [ProtonMail](https://protonmail.com) is a secure email provider, that is open source and offers end-to-end encryption. There are alternative secure mail providers (such as [CounterMail](https://countermail.com), [HushMail](https://www.hushmail.com) and [MailFence](https://mailfence.com))- but [ProtonMail](https://protonmail.com) has both a clear interface and strong security record.
**Remove metadata before uploading media** | Optional | Most smartphones and some cameras automatically attach a comprehensive set of additional data to each photograph. This usually includes things like time, date, location, camera model, user etc. Remove this data before uploading. See [this guide](https://www.makeuseof.com/tag/3-ways-to-remove-exif-metadata-from-photos-and-why-you-might-want-to/) for more info.
**Don’t have any social media accounts** | Advanced | It may seem a bit extreme, but if you're serious about data privacy and security, stay away from entering information on any social media platform.

**Recommended Software**
- [Alternative Social Media](/5_Privacy_Respecting_Software.md#social-networks)
- [Alternative Video Platforms](/5_Privacy_Respecting_Software.md#video-platforms)
- [Alternative Blogging Platforms](/5_Privacy_Respecting_Software.md#blogging-platforms)
- [News Readers and Aggregation](/5_Privacy_Respecting_Software.md#news-readers-and-aggregation)

## Networking

This section covers how you connect your devices to the internet, including configuring your router and setting up a VPN.

A Virtual Private Network (VPN) protects your IP, and allows you to more securely connect to the internet. Use it when connecting to public WiFi or to restrict your ISP from seeing all sites you've visited. Note: VPNs are not a perfect solution and it is important to select a reputable provider, to entrust your data with. Tor provides greater anonymity.

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Use a VPN** | Recommended | Use a reputable, paid-for VPN. Choose one which does not keep logs and preferably is not based under a [5-eyes](https://en.wikipedia.org/wiki/Five_Eyes) jurisdiction. See [That One Privacy Site](https://thatoneprivacysite.net/) for a detailed comparison. As of 2020, [NordVPN](https://nordvpn.com/) and [SurfShark](https://surfshark.com/) are both good all-rounders (for speed, simplicity and security), and [Mullvad](https://mullvad.net/), [OVPN](https://www.ovpn.com/en) and [DoubleHop](https://www.doublehop.me/) are excellent for security.
**Don’t use a default router password** | Recommended | Change your router password- [here is a guide as to how](https://www.lifewire.com/how-to-change-your-wireless-routers-admin-password-2487652).
**Use WPA2** | Recommended | WPA and WEP make it very easy for a hacker to gain access to your router. Use a [WPA2](https://en.wikipedia.org/wiki/Wi-Fi_Protected_Access) password instead. Ensure it is strong: 12+ alpha-numeric characters, avoiding dictionary words.
**Keep router firmware up-to-date** | Recommended | Manufacturers release firmware updates that fix security vulnerabilities, implement new standards and sometimes add features/ improve the performance your router. It's important to have the latest firmware installed, to avoid a malicious actor exploiting an un-patched vulnerability. You can usually update your router by navigating to [192.168.0.1](192.168.0.1) or [192.168.1.1](192.168.1.1) in your browser, entering the credentials on the sticker on the back of you of your router (not your WiFi password!), and following the on-screen instructions. Or follow a guide from your routers manufacturer: [Asus](https://www.asus.com/support/FAQ/1005484/), [D-Link](https://eu.dlink.com/uk/en/support/faq/routers/mydlink-routers/dir-810l/how-do-i-upgrade-the-firmware-on-my-router), [Linksys (older models)](https://www.linksys.com/us/support-article?articleNum=140365), [NetGear](https://kb.netgear.com/23442/How-do-I-update-my-NETGEAR-router-s-firmware-using-the-Check-button-in-the-router-web-interface) and [TP-Link](https://www.tp-link.com/us/support/faq/688/). Newer Linksys and Netgear routers update automatically, as does Google's router.
**Configure your router to use VPN** | Optional | If you set your VPN up on your router, then data from all devices on your home network is encrypted as it leaves the LAN. Again, it's important to select a secure VPN provider, as they will see what your ISP previously had been logging. Follow a guide from your router manufacturer or VPN provider, or see [this article](https://www.howtogeek.com/221889/connect-your-home-router-to-a-vpn-to-bypass-censorship-filtering-and-more/) to get started. Note that depending on your internet connection, and VPN provider, this could slow down your internet.
**Protect against DNS leaks** | Optional | When using a VPN, it is extremely important to exclusively use the DNS server of your VPN provider. For OpenVPN, you can add: `block-outside-dns` to your config file (which will have the extension `.ovn` or `.conf`). If you are unable to do this, then see [this article](https://www.dnsleaktest.com/how-to-fix-a-dns-leak.html) for further instructions. You can check for leaks, using a [DNS Leak Test](https://www.dnsleaktest.com/)
**Use a secure VPN Protocol** | Optional | [OpenVPN](https://en.wikipedia.org/wiki/OpenVPN) is widely used, and currently considered as a secure [tunneling protocol](https://en.wikipedia.org/wiki/Tunneling_protocol), it's also open source, lightweight and efficient. [L2TP](https://en.wikipedia.org/wiki/Layer_2_Tunneling_Protocol) can be good, but only when configured correctly, whereas it's much harder to go wrong with OpenVPN. Don't use [PPTP](https://en.wikipedia.org/wiki/Point-to-Point_Tunneling_Protocol), which  is now legacy, and not considered secure, and avoid [SSTP](https://en.wikipedia.org/wiki/Secure_Socket_Tunneling_Protocol) (proprietary, owned by Microsoft and due to lack of transparency, could be vulnerable to exploits). [IKEv2](https://en.wikipedia.org/wiki/Internet_Key_Exchange) and the new [WireGuard](https://www.wireguard.com/) protocol *(experimental)* are also good options.
**Avoid the free router from your ISP** | Optional | Typically they’re manufactured cheaply in bulk in China, and firmware updates which fix crucial security flaws aren’t released regularly. Consider an open source based router, such as [Turris MOX](https://www.turris.cz/en/mox/overview/)
**Ideally hide your SSID** | Optional | An SSID (or Service Set Identifier) is simply your network name. If it is not visible, it is much less likely to be targeted. You can usually hide it after logging into your router admin panel, [see here for more details](https://www.lifewire.com/hide-your-wireless-network-from-your-internet-leeching-neighbors-2487655).
**Whitelist MAC Addresses** | Optional | As well as a strong password, and hidden SSID, you can whitelist MAC addresses in your router settings, disallowing any unknown devices to immediately connect to your network, even if they know your credentials. A malicious actor can bypass this, by cloning their address to appear the same as one of your trusted devices, but it will add an extra step for them.
**Secure DNS** | Advanced | Use [DNS-over-HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) which performs DNS resolution via the HTTPS protocol, encrypting data between you and your DNS resolver. See [CoudFlares 1.1.1.1 Docs](https://1.1.1.1/help) for more details. Don't use Google DNS or other services which collect a lot of data.
**Use the Tor Network** | Advanced | VPNs have their weaknesses, since the provider knows your real details, whereas Tor is anonymous. For optimum security, route all your internet traffic through the Tor network. On Linux you can use [TorSocks](https://gitweb.torproject.org/torsocks.git) and [Privoxy](https://www.privoxy.org/), for Windows you can use [Whonix](https://www.whonix.org/), and on OSX [follow thsese instructions](https://maymay.net/blog/2013/02/20/howto-use-tor-for-all-network-traffic-by-default-on-mac-os-x/). Finally, you can use [OnionPi](https://learn.adafruit.com/onion-pi/overview) to use Tor for all your connected devices, by [configuring a Raspberry Pi to be a Tor Hotspot](https://lifehacker.com/how-to-anonymize-your-browsing-with-a-tor-powered-raspb-1793869805)
**Change your Router's Default IP** | Advanced | Modifying your router admin panels default IP address will makes it more difficult for malicious scripts in your web browser targeting local IP addresses, as well as adding an extra step for local network hackers
**Kill unused processes and services on your router** | Advanced | Services like Telnet and SSH (Secure Shell) that provide command-line access to devices should never be exposed to the internet and should also be disabled on the local network unless they're actually needed. In general, [any service that’s not used should be disabled](https://www.securityevaluators.com/knowledge/case_studies/routers/soho_service_hacks.php) to reduce attack surface.
**Disable WiFi on all Devices** | Advanced | Connecting to even a secure WiFi network increases your attack surface. Disabling your home WiFi and connect each device via Ethernet, and turning off WiFi on your phone and using a USB-C/ Lightening to Ethernet cable will protect against WiFi exploits, as Edward Snowden [says here](https://twitter.com/snowden/status/1175431946958233600?lang=en).

**Recommended Software** 
- [Virtual Private Networks](/5_Privacy_Respecting_Software.md#virtual-private-networks)
- [Mix Networks](/5_Privacy_Respecting_Software.md#mix-networks)
- [Open Source Proxies](/5_Privacy_Respecting_Software.md#proxies)
- [DNS Providers](/5_Privacy_Respecting_Software.md#dns)
- [Firewalls](/5_Privacy_Respecting_Software.md#firewalls)
- [Network Analysis Tools](/5_Privacy_Respecting_Software.md#network-analysis)


## Mobile Devices

Most smartphone apps run in the background, collecting and logging data, making network requests and ultimately creating a clear picture of who you are, just from your data. This is a big problem from both a security and privacy perspective.  

Even non-smart phones, (and even when the screen is off) are constantly connecting to the nearest cell phone towers, (it does this by broadcasting its IMEI and MEID number). The towers then relay this information, along with any communications, to your mobile carrier, who will store these records indefinitely. The movements of your phone are the movements of you as a person, so all phone proximity and data records can always be linked directly back to you. So whenever your phone is on, there is a record of your presence at that place, being created and maintained by companies.

SMS texting and traditional phone calls are not secure, so it's important to avoid using that to send or receive anything secure (such as log in codes, OTPs or any personal details). Instead use encrypted messaging, like Signal whenever you can. Be wary of who you share your phone number with.

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Turn off connectivity features that aren’t being used** | Recommended | When you're not using WiFi, Bluetooth, NFC or anything else, turn those features off. These are commonly used to easily hack individuals.
**Keep app count to a minimum** | Recommended | Uninstall apps that you don’t need or use regularly. As apps often run in the background, slowing your device down, but also collecting data.
**Don’t grant apps permissions that they don’t need** | Recommended | If an app doesn’t need access to your camera, don’t grant it access. Same with any features of your phone, be wary about what each app has access to.
**Only install Apps from official source** | Recommended | Applications on Apple App Store and Google Play Store are scanned and cryptographically signed, making them less likely to be malicious. Avoid downloading .apk or .ipa files from unverified source. Also check the reviews before downloading a new application.
**Only Charge your Device from a Trusted Source** | Recommended | When you charge your device via USB in a public space, it is possible for malicious actors to gain full access to your device, via [AT Commands](https://en.wikipedia.org/wiki/Hayes_command_set). You can read more about this at https://atcommands.org/ or from [this seminar](https://www.usenix.org/node/217625). To protect yourself, either only charge your phone from trusted sources, or use a [USB Data Blocker](https://amzn.to/30amhja). A Data blocker allows your phone to charge, while blocking the data transfer wires, blocking this exploit or any file transfers to run. ([PortaPow](https://portablepowersupplies.co.uk/) is recommended, since it still allows for fast-charge.) Available in both [USB-A](https://amzn.to/309kPh3) and [USB-C](https://amzn.to/39Wh5nJ).
**Set up a mobile carrier PIN** | Recommended | [SIM hijacking](https://securelist.com/large-scale-sim-swap-fraud/90353/) is when a hacker is able to get your mobile number transferred to their sim (often through social engineering your mobile carrier). This then allows them to receive 2FA SMS codes (enabling them to access your secure accounts, such as banking), or to pose as you. The easiest way to protect against this is to set up a PIN through your mobile provider, thus disallowing anyone without this PIN to make any changes to your account. The PIN should not be easily guessable, and it is important that you remember it, or store is somewhere secure. Using a non-SMS based 2FA method will reduce the damage that can be done if someone is able to take control of your SIM. [Read more](https://us.norton.com/internetsecurity-mobile-sim-swap-fraud.html) about the sim swap scam.
**Opt-out of personal ads** | Optional | In order for ads to be personalized, Google collects data about you, you can slightly reduce the amount they collect by opting-out of seeing personalized ads. See [this guide](https://www.androidguys.com/tips-tools/how-to-disable-personalized-ads-on-android/), for Android instructions.
**Erase after too many login attempts** | Optional | To protect against an attacker brute forcing your pin, if you lose your phone, set your device to erase after too many failed login attempts. See [this iPhone guide](https://www.howtogeek.com/264369/how-to-erase-your-ios-device-after-too-many-failed-passcode-attempts/). You can also do this via Find my Phone, but this increased security comes at a cost of decreased privacy.
**Monitor Trackers** | Optional | A tracker is a piece of software meant to collect data about you or your usages. [εxodus](https://reports.exodus-privacy.eu.org/en/) is a great service which lets you search for any app, by its name, and see which trackers are embedded in it. They also have [an app](https://play.google.com/store/apps/details?id=org.eu.exodus_privacy.exodusprivacy) which shows trackers and permissions for all your installed apps.
**Install a Firewall** | Optional | To prevent applications from leaking privacy-sensitive data, you can install a firewall app. This will make it easier to see and control which apps are making network requests in the background, and allow you to block specific apps from roaming when the screen is turned off. For Android, check out [NetGuard](https://www.netguard.me/), and for iOS there is [LockDown](https://apps.apple.com/us/app/lockdown-apps/id1469783711), both of which are open source. Alternatively there is [NoRootFirewall](https://play.google.com/store/apps/details?id=app.greyshirts.firewall) *Android*, [XPrivacy](https://github.com/M66B/XPrivacy) *Android (root required)*, [Fyde](https://apps.apple.com/us/app/fyde-mobile-security-access/) *iOS* and [Guardian Firewall](https://guardianapp.com/) *iOS*.
**Use secure, privacy-respecting apps** | Optional | Mainstream apps have a reputation for not respecting the privacy of their users, and they're usually closed-source meaning vulnerabilities can be hidden. [Prism-Break](https://prism-break.org) maintains a list of better alternatives, see [Android](https://prism-break.org/en/categories/android/) and [iOS](https://prism-break.org/en/categories/ios/).
**Use Signal, instead of SMS** | Optional | SMS may be convenient, but it's [not secure](https://www.fortherecordmag.com/archives/0315p25.shtml). [Signal](https://signal.org) is both the most secure and private option. [Silence](https://silence.im/) (encrypted SMS), [Threema](https://threema.ch), [Wire](https://wire.com/en/)(enterprise) and [Riot](https://about.riot.im/) are also encrypted.[iMessage](https://techcrunch.com/2014/02/27/apple-explains-exactly-how-secure-imessage-really-is/) and [WhatsApp](https://www.whatsapp.com) do claim to be [end-to-end-encrypted](https://signal.org/blog/whatsapp-complete/), but since they are not open source, verifying this is harder, and the private companies which own them (Apple and Facebook), have a questionable reputation when it comes to protecting users privacy. Keep in mind that although the transmission may be secured, messages can still be read if your or your recipients' devices have been compromised.
**Avoid using your real phone number when signing up for an account or service** | Optional | Where possible, avoid giving out your real phone number while creating accounts online. You can create phone numbers using services such as [Google Voice](https://voice.google.com) or [Skype](https://www.skype.com/en/features/online-number/). For temporary usage you can use a service like [iNumbr](https://www.inumbr.com) that generates a phone number that forwards messages and calls to your main number.
**Watch out for Stalkerware** | Optional | This is a malware that is installed directly onto your device by someone you know (partner, parent, boss etc.). It allows them to see your location, messages and other app data remotely. The app likely won't show up in your app draw, (but may visible in Settings --> Applications --> View All). Sometimes they can be disguised as a non-conspicuous app (such as a game, flashlight or calculator) which initially don't appear suspicious at all. Look out for unusual battery usage, network requests or high device temperature. If you suspect that stalkerware is on your device, the best way to get rid of it is through a factory reset. See [this guide](https://blog.malwarebytes.com/stalkerware/2019/10/how-to-protect-against-stalkerware-a-murky-but-dangerous-mobile-threat/) for more details.
**Sandbox Mobile Apps** | Advanced | Prevent permission-hungry apps from accessing your private data with [Island](https://play.google.com/store/apps/details?id=com.oasisfeng.island). It is a sandbox environment to clone selected apps and isolate them from accessing your personal data outside the sandbox (including call logs, contacts, photos and etc.) even if related permissions are granted. 
**Consider Orbot** | Advanced | [Orbot](https://guardianproject.info/apps/orbot/) provides a system-wide [Tor](https://www.torproject.org/) connection. Although more secure than a VPN, it will be slower- see [Networking](#networking) section for more details.
**Consider running a custom ROM if you have an Android device** | Advanced | Your default OS tracks information about your usage, and app data, constantly. Consider a privacy-focused custom ROM, such as [Lineage](https://lineageos.org) or [CopperheadOS](https://copperhead.co/android/).

**Recommended Software**
- [Mobile Apps, for Security + Privacy](/5_Privacy_Respecting_Software.md#mobile-apps)
- [Encrypted Messaging](/5_Privacy_Respecting_Software.md#encrypted-messaging)
- [Mobile Operation Systems](/5_Privacy_Respecting_Software.md#mobile-operating-systems)

## Personal Computers

Although Windows and OS X are easy to use and convenient, they both are far from secure. Your OS provides the interface between hardware and your applications, so if compromised can have detrimental effects.

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Keep your OS up-to-date** | Recommended | Microsoft, Apple and Google release regular OS updates, which fix security flaws. Always keep your device updated.
**Enable Firewall** | Recommended | A firewall is a program which monitors the incoming and outgoing traffic on your network, and blocks requests based on rules set during its configuration. Properly configured, a firewall can protect against some (but not all) attempts to remotely access your computer. <br>Follow these instructions to enable your firewall in [Windows](https://support.microsoft.com/en-us/help/4028544/windows-10-turn-windows-defender-firewall-on-or-off), [Mac OS](https://support.apple.com/en-us/HT201642), [Ubuntu](https://wiki.ubuntu.com/UncomplicatedFirewall) and other [Linux ditros](https://www.tecmint.com/start-stop-disable-enable-firewalld-iptables-firewall)
**Attach only known and trusted external hardware** | Recommended | Over the years there have been a variety of vulnerabilities in each major operating system relating to connecting untrusted hardware. In some cases the hardware talks to the host computer in a way the host computer does not expect, exploiting a vulnerability and directly infecting the host
**Don't charge unknown mobile devices from your PC** | Optional | If friends or colleagues want to charge their devices via USB, do not do this through your computers ports (unless you have a data blocker). By default the phone will want to sync to the host computer, but there is also specially crafted malware which takes advantage of the face that computers naturally trust connected USB devices. The owner of the phone may not even realize their device is infected
**Encrypt and Backup Important Files** | Optional | Backing up your phone can help keep your important data safe, if your device is lost, stolen or broken. But if you put your backup encrypted in the cloud, cloud providers will have access to it (if you don't pay for the service, then you are the product!). <br>[Cryptomator](https://cryptomator.org/) is an open source tool that makes this easy. It also works alongside [MountainDuck](https://mountainduck.io/) for mounting your remote drives on Windows and Mac. Other non-open-source options are [BoxCrypter](https://www.boxcryptor.com/), [Encrypto](https://macpaw.com/encrypto) and [odrive](https://www.odrive.com/).
**Uninstall Adobe Acrobat** | Optional | Adobe Acrobat was designed in a different age, before the Internet. Acrobat has had vulnerabilities that allowed specially crafted PDFs to load malware onto your system for the last two decades. Undoubtedly more vulnerabilities remain. You can use your browser to view PDFs, and browser-based software for editing
**Consider Switching to Linux** | Optional | Linux is considerably [more secure](https://www.pcworld.com/article/202452/why_linux_is_more_secure_than_windows.html) than both OSX and Windows. Some distros are still more secure than others, so it’s worth choosing the right one to get a balance between security and convenience.
**Avoid PC Apps that are not secure** | Optional | Mainstream apps have a reputation for not respecting the privacy of their users, and they're usually closed-source meaning vulnerabilities can be hidden. See here for compiled list of secure PC apps for [Windows](https://prism-break.org/en/categories/windows/), [OSX](https://prism-break.org/en/categories/macos/) and [Linux](https://prism-break.org/en/categories/gnu-linux/).
**Use a Security-Focused Distro** | Advanced | [QubeOS](https://www.qubes-os.org/) is based on “security by compartmentalization”, where each app is sandboxed. [Whonix](https://www.whonix.org/) is based on Tor, so 100% of your traffic will go through the onion router. [Tails](https://tails.boum.org/) is specifically designed to be run on a USB key and is ideal if you don’t want to leave a trace on the device your booting from. [Subgraph](https://subgraph.com/) is an “adversary resistant computing platform”, but also surprisingly easy to use
**Password protect your BIOS and drives** | Advanced | A BIOS or UEFI password helps to make an inexperienced hacker's life a little bit harder if they get a hold of your PC or hard drive, [here is a guide on how to do it](https://www.howtogeek.com/186235/how-to-secure-your-computer-with-a-bios-or-uefi-password/).
**Canary Tokens** | Advanced | Network breaches happen, but the longer it takes for you to find out about it, the more damage is done. A canary token is like a hacker honeypot, something that looks appealing to them once they've gained access to your system. When they open the file, unknowingly to them, a script is run which will not only alert you of the breach, but also grab some of the hackers system details. <br>[CanaryTokens.org](https://canarytokens.org/generate) and [BlueCloudDrive](https://blueclouddrive.com/generate) are excellent sites, that you can use to generate your tokens. Then just leave them somewhere prominent on your system. [Learn more](https://blog.thinkst.com/p/canarytokensorg-quick-free-detection.html) about canary tokens, or see [this guide](https://resources.infosecinstitute.com/how-to-protect-files-with-canary-tokens/) for details on how to create them yourself.

**Recommended Software**
- [File Encryption](/5_Privacy_Respecting_Software.md#file-encryption)
- [AV and Malware Prevention](/5_Privacy_Respecting_Software.md#anti-virus-and-malware-prevention)
- [Operating Systems](/5_Privacy_Respecting_Software.md#operating-systems)

## Smart Home

Home assistants (such as Google Home, Alexa and Siri) and other internet connected devices collect large amounts of personal data (including voice samples, location data, home details and logs of all interactions). Since you have limited control on what is being collected, how it's stored, and what it will be used for, this makes it hard to recommend any consumer smart-home products to anyone who cares about privacy and security.

Security vs Privacy: There are many smart devices on the market that claim to increase the security of your home while being easy and convenient to use (Such as [Cave Burglar Alarm](https://amzn.to/2Rx83Fb), [Blink Cam](https://amzn.to/30ylzg9), [Yale Lock](https://amzn.to/2tnQzDv) and [Ring Doorbell](https://amzn.to/2ufQ1zi) to name a few). These devices may appear to make security easier, but there is a trade-off in terms of privacy: as they collect large amounts of personal data, and leave you without control over how this is stored or used. The security of these devices is also questionable, since many of them can be (and are being) hacked, allowing an intruder to bypass detection with minimum effort.

The most privacy-respecting option, would be to not use "smart" internet-connected devices in your home, and not to rely on a security device that requires an internet connection. But if you do, it is important to fully understand the risks of any given product, before buying it. Then adjust settings to increase privacy and security. The following checklist will help mitigate the risks associated with internet-connected home devices.

**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**Rename devices to not specify brand/model** | Recommended | If your device name shows what brand or model it is, it will make it easier for a malicious actor launch an attack targeting a specific device. For example avoid names like "Nest Cam", "Yale Lock YRD 256" or "Hive Thermostat". It's usually easy to change the device's default name.
**Disable microphone and camera when not in use** | Recommended | Smart speakers and other voice controlled devices store sound clips on a server (and sometimes monitored by employees to improve the speech detection), any accidental recordings could disclose sensitive or personal data. A targeted attack could also allow someone to gain control of a microphone/ camera, so using the hardware switch to turn it off will help protect from that.
**Understand what data is collected, stored and transmitted** | Recommended | Before purchasing any smart home device, do some research - and ensure that you understand, and are comfortable with what is being collected and how it is stored and used. Don't buy devices that share anything with third parties, and check the data [breach]([https://www.dehashed.com/breach](https://www.dehashed.com/breach)) database.
**Set privacy settings, and opt out of sharing data with third parties** | Recommended | Once installed, go to settings in the app, and under privacy ensure the strictest options are selected. Usually by default, the most possible data is being collected.
**Don't link your smart home devices to your real identity** | Recommended | Use a unique user name and password which does not identify you, your family, your location or any other personal details. When creating an account for a new smart home device, do not sign up/log in with Facebook, Google or any other third-party service.
**Keep firmware up-to-date** | Recommended | Ensure firmware versions on smart devices are up-to-date and software patches have been applied. Most smart home apps will notify you when a new firmware version is available, so all you have to do it accept and install.
**Protect your Network** | Recommended | On many smart home devices, anybody connected to your home WiFi is able to view the device content (such as camera footages, or motion statistics). So ensure that your WiFi and home networks are properly secured with a strong password and up-to-date firmware. (See the [Router Section](#your-router) for more details)
**Be wary of wearables** | Optional | Wearable smart devices allow companies to log even more data than ever before; they can track your every move to know exactly where you are and what you are doing at any given time. Again, you as the consumer have no control over what is done with that data.
**Don't connect your home's critical infrastructure to the Internet** | Optional | While a smart thermostat, burglar alarm, smoke detector and other appliances may seem convenient, they by design can be accessed remotely, meaning a hacker can gain control of your entire home, without even needing to be nearby. And by breaching multiple devices, the effects can be very serious.
**Don't use Alexa/ Google Home** | Optional | It is a known fact that voice-activated assistants collect a lot of personal data. Consider switching to [MyCroft](https://mycroft.ai/) which is an open source alternative, with much better privacy.
**Monitor your home network closely** | Optional | Check your local network for suspicious activity. One of the easier methods to do this is with [FingBox](https://amzn.to/38mdw8F), but you can also do it directly [through some routers](https://www.howtogeek.com/222740/how-to-the-monitor-the-bandwidth-and-data-usage-of-individual-devices-on-your-network/). 
**Deny Internet access where possible** | Advanced | If possible deny the device/ app internet access, and use it only on your local network. You can configure a firewall to block certain devices from sending or receiving from the internet. 
**Assess risks** | Advanced | Assess risks with your audience and data in mind: Be mindful of whose data is being collected, e.g. kids. Manage which devices can operate when (such as turning cameras off when you are at home, or disabling the internet for certain devices at specific times of day)

**Recommended Software**
- [Home Automation](/5_Privacy_Respecting_Software.md#home-automation)
- [AI Voice Assistants](/5_Privacy_Respecting_Software.md#ai-voice-assistants)


## Sensible Computing

Many data breaches, hacks and attacks are caused by human error. The following list contains steps you should take, to reduce the risk of this happening to you. Many of them are common sense, but it's worth takin note of.


**Security** | **Priority** | **Details and Hints**
--- | --- | ---
**If an email asks you to take a sensitive action, verify it first** | Recommended | Emails are easy for an attacker to spoof, and it is unfortunately common practice. So whenever an email asks you to take a sensitive action, call the company first, to verify it is authentic
**Don’t Trust Your Popup Notifications** | Recommended | It is a trivial task for a malicious actor to deploy fake pop-ups, either on your PC, phone or browser. If you click a popup, ensure the URL is correct before entering any information
**Never Leave Device Unattended** | Recommended | Even with a strong password, it's straight-forward to retrieve the data from your phone or computer (unless it is encrypted). If you lose your device, and have find my phone enabled, then remotely erase it
**Prevent Camfecting** | Recommended | It is a good idea to invest in some webcam covers, and microphone blockers to protect against [*camfecting*](https://en.wikipedia.org/wiki/Camfecting), where a malicious actor, or app is able spy on you and your physical space, without your knowledge. See  [this guide](https://blog.malwarebytes.com/hacking-2/2019/09/15000-webcams-vulnerable-how-to-protect-webcam-hacking/) for more tips. Mute home assistants, (Alexa, Google Home and Siri) when you are not using them, or at least when you are discussing anything sensitive or anything conversation involving personal details
**Stay protected from shoulder surfers** | Recommended | Be sure to not let anyone 'shoulder surf' (read what is on your screen, when in public space). As they may be able to gather sensitive information about you. You could apply a privacy screen to your [laptop](https://amzn.to/2H7pOX7) and [mobile](https://amzn.to/39oHWrA), in order to restrict data being read from an angle
**Educate yourself about phishing attacks** | Recommended | Phishing is an attempt to obtain sensitive information (like an account password) by disguising as a trustworthy person or company. In recent years phishing attacks have become increasingly sophisticated and hackers are learning to use data that people put on the web to create highly specific and targeted attacks. Check the URL before entering any information. Understand the context- were you expecting the email or message, does it feel normal? Employ general good security practices will also help: Use 2FA, don't reuse passwords, close accounts you no longer use and backup your data. See these guides on: [How to Protect against Common Phishing Attacks](https://www.tripwire.com/state-of-security/security-awareness/6-common-phishing-attacks-and-how-to-protect-against-them) and [The Anatomy of a Phishing Email](https://www.howtogeek.com/58642/online-security-breaking-down-the-anatomy-of-a-phishing-email/)
**Watch out for Stalkerware** | Recommended | This is a malware that is installed directly onto your device by someone you know (partner, parent, boss etc). It allows them to see your location, messages and other app data remotely. The app likely won't show up in your app draw, (but may visible in Settings --> Applications --> View All). Sometimes they can be disguised as a non-conspicuous app (such as a game, flashlight or calculator) which initially don't appear suspicious at all. Look out for unusual battery usage, network requests or high device temperature. If you suspect that stalker ware is on your device, the best way to get rid of it is through a factory reset
**Install Reputable Software from Trusted Sources** | Recommended | It may seem obvious, but so much of the malware many PC users encounter is often as a result of accidentally downloading and installing bad software. Also, some legitimate applications try to offer you slightly dodgy freeware (such as toolbars, anti-virus, and other utilities). Be sure to pay attention while completing the installation process. Only download software from legitimate sources (often this isn't the top result in Google) so it's important to double check before downloading. Before installing, check it in [Virus Total](https://www.virustotal.com), which scans installable files using multiple AV checkers
**Store personal data securely** | Recommended | Backing up important data is important. But ensure that all information that is stored on your phone/laptop, USB or in a cloud is encrypted. That way, if it is accessed by a hacker (which unfortunately is all too common), it will be almost impossible for them to get to your personal files. For USB devices, see [VeraCrypt](https://www.veracrypt.fr/en/Home.html). For cloud backup, see [Cryptomator](https://cryptomator.org), and for your phone and laptop, see [this guide](https://www.howtogeek.com/260507/psa-encrypt-your-pc-phone-and-tablet-now.-youll-regret-it-later-if-you-dont)
**Do not assume a site is secure, just because it is `HTTPS`** | Recommended | Unlike HTTP, data sent over HTTPS is encrypted. However that does not mean you should trust that website by default. HTTPS Certificates can be obtained by anybody, so a cloned or scam site may have a valid certificate (as denoted by the padlock icon). Always check the URL, and don't enter any personal details unless you are certain a website is legitimate. Avoid entering data on any site that is not HTTPS
**Use Credit Cards, or Virtual Cards when paying online** | Optional | There are risks involved in entering your card details on any website. Credit cards have better consumer protection, compared to debit or bank cards, meaning you are more likely to be recompensated for fraudulent transactions. Better still, paying with a virtual, 1-time card will mean that even if those credentials are compromised a hacker will not be able to lift any of your money. [Privacy.com](https://privacy.com/join/VW7WC) offer virtual payment cards for that you can use anywhere on the internet, as does [Revolut Premium](revolut.ngih.net/Q9jdx)
**Review application permissions** | Optional | Ensure that no app have unnecessary access to your photos, camera, location, contacts, microphone, call logs etc. See these guides for how to manage app permissions on [Android](https://www.howtogeek.com/230683/how-to-manage-app-permissions-on-android-6.0) and [iOS](https://www.howtogeek.com/211623/how-to-manage-app-permissions-on-your-iphone-or-ipad). On Android, there is a great app called [Exodus Privacy](https://play.google.com/store/apps/details?id=org.eu.exodus_privacy.exodusprivacy), that displays all permissions, and trackers for each of your installed apps
**Opt-out of data sharing** | Optional | Many apps and services automatically opt you in for data collection and sharing. Often this data is sold onto third-parties, who buy customer logs from many companies, and are therefore able to combine them together and easily deduce your identity, and combine it with your habits, purchases, personal details, location etc. For instructions on how to opt-out, see [Simple Opt Out](https://simpleoptout.com)
**Review and update social media privacy** | Optional | Companies regularly update their terms, and that often leads to you being opted back. Check you Facebook, Twitter, Google etc. activity and privacy settings. See also [re-consent](https://github.com/cliqz-oss/re-consent) and [Jumbo](https://www.jumboprivacy.com) which are tools aimed at making this clearer and easier
**Compartmentalize** | Advanced | [Compartmentalization](https://en.wikipedia.org/wiki/Compartmentalization_(information_security)) is where to keep several categories of digital activity and files totally separate from each other. It means that if one area is breached, then an attacker will only have a proportion of your data, and the rest will still be safe. For example, store your work and personal files on separate devices, or use different web browsers for different types of activity, or even run certain tasks in a contained VM or on a separate device (such as having a work phone, and personal phone, or using a separate browser for social media/ chat rooms, or even running a VM for using specialist software)
**Use anonymous payment methods** | Advanced | Paying online with credit or debit card involves entering personal details, including name and residential address. Paying with cryptocurrency will not require you to enter any identifiable information. Both [Monero](https://www.getmonero.org) and [Zcash](https://z.cash/) are totally anonymous, and so best for privacy. See also: [Anonymous Payment Methods](/5_Privacy_Respecting_Software.md#payment-methods)

**See also**: [Online Tools](/5_Privacy_Respecting_Software.md#online-tools)

----

#### There's more to check out!
- [Why Privacy & Security Matters](/0_Why_It_Matters.md)
- [Privacy-Respecting Software](/5_Privacy_Respecting_Software.md)
- [Privacy & Security Gadgets](/6_Privacy_and-Security_Gadgets.md)
- [Further Links + More Awesome Stuff](/4_Privacy_And_Security_Links.md)

#### Other Awesome Security Lists
- @sbilly/[awesome-security](https://github.com/sbilly/awesome-security)
- @0x4D31/[awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection)
- @hslatman/[awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence)
- @PaulSec/[awesome-sec-talks](https://github.com/PaulSec/awesome-sec-talks)
- @Zbetcheckin/[security_list](https://github.com/zbetcheckin/Security_list)

[See More](/4_Privacy_And_Security_Links.md#other-github-security-lists)

----

## Notes

*Thanks for visiting, hope you found something useful here :) Contributions are welcome, and much appreciated - to propose an edit [raise an issue](https://github.com/Lissy93/personal-security-checklist/issues/new/choose), or [open a PR](https://github.com/Lissy93/personal-security-checklist/pull/new/master). See: [`CONTRIBUTING.md`](/.github/CONTRIBUTING.md).*

*I owe a lot of thanks others who've conducted research, written papers, developed software all in the interest of privacy and security. Full attributions and references found in [`ATTRIBUTIONS.md`](/ATTRIBUTIONS.md).*

*Disclaimer: This is not an exhaustive list, and aims only to be taken as guide.*

*Licensed under [Creative Commons, CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © [Alicia Sykes](https://aliciasykes.com) 2020*

[![Attribution 4.0 International](https://licensebuttons.net/l/by/3.0/88x31.png)](/LICENSE.md)

---

Get in touch 📬

[![Alicia Sykes on Twitter](https://img.shields.io/twitter/follow/Lissy_Sykes?style=social&logo=twitter)](https://twitter.com/Lissy_Sykes)
[![Alicia Sykes on GitHub](https://img.shields.io/github/followers/lissy93?label=Lissy93&style=social)](https://github.com/Lissy93)
[![Alicia Sykes on Mastodon](https://img.shields.io/mastodon/follow/1032965?domain=https%3A%2F%2Fmastodon.social)](https://mastodon.social/web/accounts/1032965)
[![Alicia Sykes on Keybase](https://img.shields.io/badge/aliciasykes--lightgrey?style=social&logo=Keybase)](https://keybase.io/aliciasykes)
[![Alicia Sykes's PGP](https://img.shields.io/badge/PGP--lightgrey?style=social&logo=Let%E2%80%99s%20Encrypt)](https://keybase.io/aliciasykes/pgp_keys.asc)
[![Alicia Sykes's Website](https://img.shields.io/badge/aliciasykes.com--lightgrey?style=social&logo=Tencent%20QQ)](https://aliciasykes.com)

----

Found this helpful? Consider sharing it with others, to help them also improve their digital security 😇

[![Share on Twitter](https://img.shields.io/badge/Share-Twitter-17a2f3?style=for-the-badge&logo=Twitter)](http://twitter.com/share?text=Check%20out%20the%20Personal%20Cyber%20Security%20Checklist-%20an%20ultimate%20list%20of%20tips%20for%20protecting%20your%20digital%20security%20and%20privacy%20in%202020%2C%20with%20%40Lissy_Sykes%20%F0%9F%94%90%20%20%F0%9F%9A%80&url=https://github.com/Lissy93/personal-security-checklist)
[![Share on LinkedIn](https://img.shields.io/badge/Share-LinkedIn-0077b5?style=for-the-badge&logo=LinkedIn)](
http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=https://github.com/Lissy93)
[![Share on Facebook](https://img.shields.io/badge/Share-Facebook-4267b2?style=for-the-badge&logo=Facebook)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A//github.com/Lissy93/personal-security-checklist&title=The%20Ultimate%20Personal%20Cyber%20Security%20Checklist&summary=%F0%9F%94%92%20A%20curated%20list%20of%20100%2B%20tips%20for%20protecting%20digital%20security%20and%20privacy%20in%202020&source=)
[![Share on Mastodon](https://img.shields.io/badge/Share-Mastodon-56a7e1?style=for-the-badge&logo=Mastodon)](https://mastodon.social/web/statuses/new?text=Check%20out%20the%20Ultimate%20Personal%20Cyber%20Security%20Checklist%20by%20%40Lissy93%20on%20%23GitHub%20%20%F0%9F%94%90%20%E2%9C%A8)


## Contributors

### Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/Lissy93/personal-security-checklist/graphs/contributors"><img src="https://opencollective.com/personal-security-checklist/contributors.svg?width=890&button=false" /></a>

### Financial Contributors

Become a financial contributor and help us sustain our community. [[Contribute](https://opencollective.com/personal-security-checklist/contribute)]

#### Individuals

<a href="https://opencollective.com/personal-security-checklist"><img src="https://opencollective.com/personal-security-checklist/individuals.svg?width=890"></a>

#### Organizations

Support this project with your organization. Your logo will show up here with a link to your website. [[Contribute](https://opencollective.com/personal-security-checklist/contribute)]

<a href="https://opencollective.com/personal-security-checklist/organization/0/website"><img src="https://opencollective.com/personal-security-checklist/organization/0/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/1/website"><img src="https://opencollective.com/personal-security-checklist/organization/1/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/2/website"><img src="https://opencollective.com/personal-security-checklist/organization/2/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/3/website"><img src="https://opencollective.com/personal-security-checklist/organization/3/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/4/website"><img src="https://opencollective.com/personal-security-checklist/organization/4/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/5/website"><img src="https://opencollective.com/personal-security-checklist/organization/5/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/6/website"><img src="https://opencollective.com/personal-security-checklist/organization/6/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/7/website"><img src="https://opencollective.com/personal-security-checklist/organization/7/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/8/website"><img src="https://opencollective.com/personal-security-checklist/organization/8/avatar.svg"></a>
<a href="https://opencollective.com/personal-security-checklist/organization/9/website"><img src="https://opencollective.com/personal-security-checklist/organization/9/avatar.svg"></a>
