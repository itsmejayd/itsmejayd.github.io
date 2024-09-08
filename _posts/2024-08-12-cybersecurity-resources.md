---
title: "Cybersecurity Resources"
excerpt_separator: "<!--more-->"
categories:
  - Blog
  - Resources Directory
tags:
  - cybersecurity
  - information security
  - network security
  - operations security
  - password security
  - hacking
  - CTF
  - RFID
  - threat maps
  - encryption
toc: true
toc_sticky: true
---

This page is basically a [directory](https://jackyan.com/blog/2023/09/bring-back-the-human-curated-web-directory/) of links.<!--more--> I have a hodgepodge of useful bookmarks accumulated over time in a yet-to-be-well-organized bookmark directory and I wanted to group up a few of them for specific topics (this page being for links related to some basic cybersec/infosec/netsec/opsec stuff). I figured I might as well post it here for my own reference and so others might get use from it! These links are not necessarily in any particular order, though I’ll probably provide a brief description of each.

---
---

<p>&nbsp;</p>
## Cyber Threat Maps:
### What is a cyber threat map?
* 'Cyberattack maps, also called cyber threat maps, are visual representations of real-time or historical cyberattacks on networks, devices and computer systems...Cyberattack maps leverage data analysis and visualization tools to provide insights into the nature and scope of cyber threats, such as:
    * Location
    * Frequency
    * Attack type
* Some visualization techniques include heat maps, graphs and timelines so that users understand the information more easily.'
([paraphrased from splunk](https://www.splunk.com/en_us/blog/learn/cyberattack-maps.html))

### [Check Point Cyber Threat Map](https://threatmap.checkpoint.com/)
![Screenshot of website](/assets/images/cybersecurity_resources_images/checkpoint_threatmap.png)
* Provides a real-time visualization of cyberattacks worldwide.
* Displays data on the sources and targets of attacks, showing the volume and types of threats detected.
* The map is dynamic, with attacks represented as lines connecting the origin to the destination, providing insight into global cyber threat patterns.

### [Digital Attack Map (depricated)](https://www.digitalattackmap.com)
![Screenshot of website](/assets/images/cybersecurity_resources_images/digitalattackmap.png)
* This one *was* my favorite, but it seems the site hasn't been updating since 2021. Still interesting to check it out to see the design and sources/methods of a cool threat map dashboard. Also useful for historical attack data analysis.

<p>&nbsp;</p>
## Educational Resources:
### [OST2 (OpenSecurityTraining2)](https://p.ost2.fyi/courses)
![Screenshot of website](/assets/images/cybersecurity_resources_images/ost2.png)
* OST2 is an educational platform offering free, advanced cybersecurity training through detailed courses and resources, focusing on topics like reverse engineering, malware analysis, and system internals.

### [picoCTF](https://play.picoctf.org/login)
![Screenshot of website](/assets/images/cybersecurity_resources_images/picoctf.png)
* picoCTF (pico = small, CTF = capture the flag) is a free, online cybersecurity competition designed for students, offering interactive challenges that teach computer security and hacking techniques in a gamified format.

<p>&nbsp;</p>
## Career Information/Resources:
### [Cyber Seek](https://www.cyberseek.org/)
* CyberSeek.org is a tool that offers interactive maps, heat charts, and career pathways to visualize the cybersecurity job market, highlighting in-demand roles, required certifications, and career progression opportunities. It’s designed to support job seekers, educators, and employers in addressing the cybersecurity talent gap.
    * [Cybersecurity supply/demand heat map](https://www.cyberseek.org/heatmap.html)
    * [Career Pathway](https://www.cyberseek.org/certifications.html)

<p>&nbsp;</p>
## Miscellaneous Tools:
(some basic yet useful resources):
### [PGP Encryption](https://www.openpgp.org/software/)
* OpenPGP.org is the official site for the OpenPGP standard, which provides encryption for secure email communication. It offers resources and tools like GnuPG, a widely-used software for encrypting and signing data, along with guidelines for implementing OpenPGP in various applications to enhance privacy and security.

### [Cover Your Tracks](https://coveryourtracks.eff.org/)
![Screenshot of website](/assets/images/cybersecurity_resources_images/coveryourtracks.png)
* "Cover Your Tracks is two things: a tool for users to understand how unique and identifiable their browser makes them online, and a research project to uncover the tools and techniques of online trackers and test the efficacy of privacy add-ons." ([from their about page](https://coveryourtracks.eff.org/about))

### [BugMeNot](https://bugmenot.com/)
![Screenshot of website](/assets/images/cybersecurity_resources_images/bugmenot.png)
* BugMeNot.com is a website that provides shared login credentials for various websites that require registration or login to access content. The idea behind BugMeNot is to allow users to bypass the registration process on sites where they may only need temporary access or do not want to share personal information.

### [PowerShell Network Monitoring](https://www.cyberdrain.com/monitoring-with-powershell-monitoring-network-traffic/)
* An interesting article on using PowerShell scripts for monitoring network bandwidth, link speeds, and metered connections, aiming to optimize network performance and prevent issues, especially for mobile users.

<p>&nbsp;</p>
## Password Managers:
(YOU SHOULD BE USING ONE, PLEASE USE ONE)

The managers most people may be familiar with are the ones built into google chrome or iOS ("autofill password"). These are good to use, and I would recommend using them over not using anything... but I do think I only trust them as much as I trust google or apple generally... which is less than I trust open source, non profit, 3rd party verifiable things.

### What is a password manager?
* A password manager securely stores and organizes passwords in an encrypted database, allowing users to manage multiple passwords with a single master password. It helps generate strong, unique passwords and can autofill credentials on websites, enhancing both security and convenience by reducing the risk of using weak or repeated passwords.

### [KeePass](https://keepass.info/download.html)
* This software is open source and non profit!
* Provides official versions of the KeePass password manager, including the main program, plugins, and additional resources. It offers various versions for Windows and portable options, along with detailed installation instructions and links to source code and older versions.

### [KeePassXC](https://keepassxc.org)
* This software is open source and non profit!
* Offers a cross-platform, community-driven variant of KeePass, with enhanced features and a more modern interface. It provides download links for Windows, macOS, and Linux, along with documentation, security details, and community resources.

### What is the difference between KeePass and KeePassXC?
* KeePass is the original password manager, while KeePassXC is a community-developed fork focused on cross-platform compatibility and additional features.
* For most use cases and for more convenience I would recommend KeePassXC .

<p>&nbsp;</p>
## RFID Hacking & Security:
* [Exploitation of Radio Frequency Technologies Through the use of Microcontrollers](https://www.iaria.org/conferences2020/fileseLmL20/eLmL_58009.pdf)

* [A 2018 practical guide to hacking NFC/RFID](https://smartlockpicking.com/slides/Confidence_A_2018_Practical_Guide_To_Hacking_RFID_NFC.pdf)

* [Step-by-Step Tutorial: How to Copy or Clone Access Cards and Key Fobs](https://www.getkisi.com/blog/how-to-copy-access-cards-and-keyfobs)

<p>&nbsp;</p>
