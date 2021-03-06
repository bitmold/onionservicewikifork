> [[Wiki|Home]] ▸ **InfoSec**

Cool stuff for "[the Cyber](https://www.theatlantic.com/technology/archive/2016/09/trumps-incoherent-ideas-about-the-cyber/501839/)" that tech antifa folks have played around with/contributed to/enjoyed pentesting in the past.

> 🔰 Are you a newbie and feeling a little overwhelmed by this page? Try our [[starting recommendations|Getting started on InfoSec]].

1. [At AnarchoTechNYC](#at-anarchotechnyc)
1. [CTFs and Hacking Games](#ctfs-and-hacking-games)
    1. [CTFs](#ctfs)
        1. [CTF calendars and archives](#ctf-calendars-and-archives)
        1. [Beginner CTFs](#beginner-ctfs)
    1. [Hacking challenges](#hacking-challenges)
    1. [Cyberwarfare ranges](#cyberwarfare-ranges)
1. [Labs and practice VMs](#labs-and-practice-vms)
    1. [Deliberately vulnerable systems](#deliberately-vulnerable-systems)
1. [Lesson plans and guidance](#lesson-plans-and-guidance)
    * [More lesson material](#more-lesson-material)
1. [For defenders](#for-defenders)
1. [Other lists](#other-lists)

# At AnarchoTechNYC

* [[CTF team]], a semi-private cybersecurity study group that puts the "ethical" back into "ethical hacking."
* [[Lockpicking club]], a locksport practice session and meditative discussion circle featuring those most ubiquitous of doorway decorations.

See also [[Activities and events]].

# CTFs and Hacking Games

[**Capture The Flag competitions (CTFs)**](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) are sets of puzzles intended to distill the essence of many aspects of professional computer security work into a single short-lived exercise that is objectively measurable. Most competitions are free to participate, and some even award prizes to winners. They are often associated with a conference or event, so are open only at certain times, run for a short while, then close and rank the participants according to the competition's scoring rules.

[**Wargames**](https://en.wikipedia.org/wiki/Wargame_(hacking)), sometimes also called **hacking challenges**, are stand-alone puzzlers that are always available (they are not associated with a time or event). Typically, they are organized into levels that get progressively harder as you solve more of them. Some hacking/wargame sites also organize challenges into categories based on the skills you need to solve them.

**Deliberately vulnerable systems**, or deliberately exploitable apps, are bundled software packages that are intentionally designed to be practice targets for exploitation attempts. These tools sometimes contain self-describing tutorials or exercise descriptions so that they can be used as a self-contained educational course. They are a noteworthy variant of wargames that can be played "offline" because you can download them to your own computer, like a practice lab.

**Cyberwarfare Ranges** are digital live-fire ranges, semi-private inter-networks where participants can set up and attack other participant's servers and services for educational purposes. They are typically heavily firewalled and accessible only with an invitation and/or through a VPN tunnel; think of them like the digital equivalent of paintball arenas or live-fire gun ranges.

> ℹ️ **A note on netiquette.** While each of these gaming styles offer educational opportunities, most have slightly different etiquette. For instance, it's customary for participants to publish solutions to the challenges presented during CTF competitions in the form of writeups on blogs, but this is discouraged by many hacking challenge sites. Take a moment to familiarize yourself with the publisher of the challenge you're tackling before you publish your solution to the whole Internet, as you may be spoiling the fun of the game for others.

> 💡 **There are more resources on this wiki.** If you do end up tackling some of these hacking puzzlers, you'll definitely find some help elsewhere on this wiki, or the [AnarchoTechNYC CTF team's wiki](https://github.com/AnarchoTechNYC/CTF/wiki). For instance, sooner rather than later you'll find yourself [[identifying data formats]] you never recognized before.

## CTFs

Anarcho-Tech NYC fields [[our own team(s)|CTF team]], which is a friendly but invite-only cybersecurity study group. Our team participates sporadically in CTF competitions worldwide in order to provide our collective members legal and safe opportunities to hone our hacking skills; we rarely score well because "points" (like "money") is not our focus. If you are looking for a team to join but are not an Anarcho-Tech NYC member, you might find it fun to hang out with the [OpenToAll team](http://opentoallctf.com/) on IRC.

### CTF calendars and archives

Hundreds of upcoming CTFs are listed at:

* [CTFTime.org](https://ctftime.org/) - List of upcoming CTFs to compete in, central (unofficial) directory of teams, and archive of previous challenge write-ups for educational purposes.
* [CapTF Calendar](http://captf.com/calendar/) - Google Calendar of various CTFs.

### Beginner CTFs

Most CTF competitions and platforms are designed for very experienced computer security professionals. While these can be a fantastic way to hone existing skills, they are often not well-suited for gaining a foundational familiarity with a given technology or class of security vulnerabilities because they expect players to have been exposed to at least some elements of these issues in the course of their prior professional experience. In contrast, beginner CTFs are designed to gamify such first-exposure experiences, either explicitly as in the case of supplementary exercises for (middle or high) school studens, or as a stand-alone educational tool.

* [PicoCTF](https://picoctf.com/)

  An always-open game targeted for high school students but useful for anyone who is just starting out in computer security. Available games are [PicoCTF 2013](https://2013.picoctf.com/), [PicoCTF 2014](https://2014.picoctf.com/), [PicoCTF 2017](https://2017.picoctf.com/), [PicoCTF 2018](https://2018game.picoctf.com/), and [PicoCTF 2019](https://2019game.picoctf.com/).

* [PACTF](https://pactf.com/)

* [TJCTF](https://tjctf.org/)

## Hacking challenges

* [CTFLearn](https://ctflearn.com/)

  A crowdsourced collection of practice problems ranging from beginner to expert difficulty. Accounts are free, and anyone can post problems, solve problems, or share news about CTFs. Kind of like a [HackerRank](https://www.hackerrank.com/) or [CodeWars](https://www.codewars.com/) for cybersecurity challenges.

* [Ghost in the Shellcode](http://ghostintheshellcode.com/)

  An annual capture-the-flag contest that takes place every winter—generally in January, but sometimes in February.

* [Microcorruption](https://www.microcorruption.com)

  The fact that this wargame can be played entirely in your browser makes it really great if you are new to reverse engineering and binary exploitation as you do not have to worry about learning GDB or other tools to get going. It's still really fun even if you are not new. The levels start out simple -- grabbing a key from memory, basic stack smashing -- and get more complicated as defensive measures are enabled and the reversing task is made more complicated by obfuscation.

* [SmashTheStack](http://www.smashthestack.org/)

  🚧 TK-TODO (needs a good, succinct description)

* [Cryptopals](http://cryptopals.com)

  Learn how cryptosystems are built and how they are attacked. By the same creators as Microcorruption.

* [Pwn Adventure](http://pwnadventure.com/)

  Pwn Adventure 3: Pwnie Island is a limited-release, first-person, true open-world MMORPG set on a beautiful island where anything could happen. That's because this game is intentionally vulnerable to all kinds of silly hacks! Flying, endless cash, and more are all one client change or network proxy away.

* [Over the Wire](http://overthewire.org)

  This is a series of games played over SSH. Each level corresponds to a user with a shell account on the game server. There's a set of binaries with their setuid flags set. The tasks are typically in the form of: exploit the binary, become the next user, repeat. Unlike micorcorruption, there's no nice webapp debugger, so you'll need to learn GDB, [radare2](http://radare.org) or something. I thought these were really fun, and because the environment is a lot less controlled than microcorruption, I learned a lot about how subtle factors can foil your exploit.

* [Under the Wire](https://www.underthewire.tech/)

  This series of challenges focuses on teaching the Windows PowerShell CLI and is inspired by the earlier *Over the Wire* challenges.

* [io](http://io.netgarage.org), [io64](http://io.netgarage.org:8064), [ioarm](http://188.166.114.127)
  
  Like Over the Wire, the io games are played over SSH with the goal of escalating privileges to advance levels. Home to a great IRC channel too.

* [Exploit Exercises](https://exploit-exercises.com/)

  A variety of virtual machines, documentation and challenges that can be used to learn about a variety of computer security issues such as privilege escalation, vulnerability analysis, exploit development, debugging, reverse engineering, and general cyber security issues. 

* [BreakThiSQLi](http://breakthisqli.rf.gd/)

  SQL injection challenges by increasing difficulty. Fun for the whole database family!

* [Audi-1's SQLI Labs](https://github.com/Audi-1/sqli-labs)

  Series of intentionally vulnerable PHP scripts that you can install on a server for the purpose of learning SQL injection techniques.

* [CanYouHack.Us](https://canyouhack.us/)

  Mixture of Web and binary security challenges.

* [id0-rsa](https://id0-rsa.pub/)

  Cryptography challenges.

* [pwnable.kr](https://pwnable.kr/)

  More memory corruption. Most levels are vulnerable services running on a particular port. You can exploit them remotely to get a shell, read a "flag" file, and register it with the website to be awarded "points."

* [Reversing.kr](https://reversing.kr/)

  A couple dozen diverse reverse engineering challenges, including Java programs, Windows executables, Linux binaries, and more.

* [RingZer0team.com](https://ringzer0team.com/)

  Several hundred challenges across numerous cybersecurity categories that you can tackle on your own time. Also includes a leaderboard and encourages participants to post write-ups of their solutions to the hacking puzzles, so you can learn from others' successful hacks.

* [HackMethod Challenge](http://challenge.hackmethod.com/)

  Month-long "Capture the Flag" and "Root the Box" style challenges, appearing monthly, and with a rolling scoreboard. They also provide (some) guidance in the form of a [roadmap](https://hackmethod.com/roadmap/) that may help guide you through some of their challenges. (But see also [#Lesson plans and guidance](#lesson-plans-and-guidance), below.)

* [Hack The Box](https://hackthebox.eu/)

  Rotating selection of hacking challenges and penetration testing practice labs offered on a freemium model (free tier and paid tiers) for individuals and university or corporate education programs. Registering an account is required to participate.

* [HackThis!!](https://www.hackthis.co.uk/levels/)

  Categorized sets of hacking challenges in various security domains that earn points and bragging rights on a community scoreboard.

* [HackThisSite](https://www.hackthissite.org/)

  An older (mid-2000's era) set of challenges in Web, IRC, steganograhy, and a few other categories. Notable partly for its hacktivist co-founder, [Jeremy Hammond](https://en.wikipedia.org/wiki/Jeremy_Hammond), famed member of [the Anonymous-affiliated group LulzSec](https://arstechnica.com/tech-policy/2013/05/lulzsec-member-jeremy-hammond-pleads-guilty-to-stratfor-hack/). While outdated, most of the hacking challenges (called "missions") on this site are still decent practice for technology basics that haven't changed much such as fundamental crypto maths, the HTTP protocol, and JavaScript exploitation techniques.

* [HackerTest.net](http://www.hackertest.net/)

  A set of increasingly difficult hacking "levels."

* [Hacker101](https://www.hacker101.com/)

  Free class for Web security structured as a set of video lessons, some covering multiple topics, some covering a single one. Additionally, there are coursework levels where you can hunt for bugs and experiment with exploitation in practice. As you work through the video content, try out the coursework to see what you can find!

* [W3Challs](https://w3challs.com/)

  Mostly a community site and forum, but has a number of categorized challenges as well, including a couple entirely about writing Web scraping programs.

* [Root Me](https://root-me.org/)

  A collection of a couple hundred stand-alone online challenges and several dozen practice labs ("virtual environments") in a variety of categories.

* [Enigma Group](https://www.enigmagroup.org/)

  A set of challenges in categories such as cryptography, steganography, and Web exploitation "cover[ing] the exploits listed in the OWASP Top 10 Project [to] teach members the many other types of exploits that are found in today's applications; thus, helping them to become better programmers in the mean time."

* [WTHack - OnlineCTF.com](https://www.onlinectf.com/)

  A user-submitted collection of practice problems in various categories. Accounts are free, and anyone can post problems, solve problems, or share news about CTFs. Similar in functionality to [CTFLearn](https://ctflearn.com/).

* [HackCenter](https://hackcenter.com/)

  A free-to-use "training platform designed to teach anyone the actionable skills needed to be effective in cybersecurity." Built by ForAllSecure, Inc., which provides cybersecurity training services, the site serves as an industry recruiting tool by running competitive CTFs. Usefully, the hacking challenges remain accessible and solvable after the competitions have ended, making the site akin to the explicitly educational [PicoCTF](https://picoctf.com/). Consider signing up with a fake name and other false details to avoid being marketed at down the line.

* [ROP Emporium](https://ropemporium.com/)

  Learn return-oriented programming through a series of challenges designed to teach ROP techniques in isolation, with minimal reverse-engineering and bug-hunting. Includes a beginner's guide to help newcomers learn the basics of ROP techniques, and a set of increasingly difficult challenges. Good for practicing how to write this specific kind of exploit development.

* [RPISEC's Modern Binary Exploitation](https://github.com/RPISEC/MBE) (CSCI 4968)

  This repository contains the materials as developed and used by [RPISEC](http://rpis.ec) to teach Modern Binary Exploitation at [Rensselaer Polytechnic Institute](http://rpi.edu) in Spring 2015. This was a university course developed and run solely by students to teach skills in vulnerability research, reverse engineering, and binary exploitation.

* [Network Forensics Puzzle Contest](https://forensicscontest.com/)

  Set of network forensics puzzles run as part of regular contests.

* [Rebootuser's HackLAB Challenges](https://www.rebootuser.com/?page_id=1041)

  🚧 TODO: Description needed.

* [XSS Game](https://xss-game.appspot.com/)

  Google's free and interactive cross-site scripting (XSS) training course offering "recruits" (you) the opportunity to safely and legally explore how to find and exploit XSS bugs.

* [PortSwigger Web Security Academy](https://portswigger.net/web-security)

  "The Web Security Academy contains high-quality learning materials, interactive vulnerability labs, and video tutorials. You can learn at your own pace, wherever and whenever suits you. Best of all, everything is free!" (Requires registration.)

* [Malware Traffic Analysis](https://malware-traffic-analysis.net/)

  A source for packet capture files and malware samples that, by the Summer of 2013, has published over 1,600 blog entries about malicious network traffic. Almost every post on this site has pcap files or malware samples (or both). There are also numerous malware traffic analysis exercises useful for gaining experience analyzing the communication of malware infections, along with tutorials that can help train you in network forensics.

* [flAWS.cloud](http://flaws.cloud/) and [flAWS2.cloud](http://flaws2.cloud/)

  This set of games/tutorials teaches you AWS (Amazon Web Services) security concepts. The challenges are focused on AWS specific issues, so no buffer overflows, XSS, etc. You can play by getting hands-on-keyboard or just click through the hints to learn the concepts and go from one level to the next without playing.

# Cyberwarfare ranges

* [Arizona Cyberwarfare Range](https://web.archive.org/web/20170211144448/http://azcwr.org/)

# Labs and practice VMs

* [FuzzySecurity: Tutorials](https://www.fuzzysecurity.com/tutorials.html)
* [Hacking Lab](https://www.hacking-lab.com)
* [Janos Gyerik's "Hacking contest on a Live CD"](http://www.janosgyerik.com/hacking-contest-on-a-live-cd/)
* [Labtainers](https://github.com/mfthomps/Labtainers)
* [Malware Unicorn Workshops](https://securedorg.github.io/)
* [Open Security Training](http://opensecuritytraining.info/)
* [Penteseter Lab](https://PentesterLab.com)
* [PentestIT Labs](https://lab.pentestit.ru/)
* [Root Me](https://root-me.org/)
* [VulnHub](https://www.vulnhub.com)

## Deliberately vulnerable systems

* [OWASP Vulnerable Web Applications Directory Project](https://owasp.org/www-project-vulnerable-web-applications-directory/)

  The OWASP Vulnerable Web Applications Directory Project (VWAD) is a comprehensive and well maintained registry of all known intentionally vulnerable Web applications currently available for legal security and vulnerability testing of various kinds. Notable items include [Google Gruyere](http://google-gruyere.appspot.com/), the [Damn Vulnerable Web Application](http://www.dvwa.co.uk/), and [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project).

* [Damn Vulnerable iOS App](http://damnvulnerableiosapp.com/)

  "[T]his application can be used by mobile security enthusiasts and students to learn or review the basics of mobile application security." Supplemental guides can be found on [the author's site's DVIA page](https://n0where.net/damn-vulnerable-ios-app-dvia/).

* [HackSys Extreme Vulnerable Windows Driver](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver)

  The HackSys Extreme Vulnerable Driver is an intentionally vulnerable Windows driver developed for security enthusiasts to learn and polish their exploitation skills at the Windows Kernel level.

* [OWASP iGoat Tool Project](https://www.owasp.org/index.php/OWASP_iGoat_Tool_Project)

  Learning tool for iOS developers (iPhone, iPad, etc.). It was inspired by the WebGoat project, and has a similar conceptual flow to it. As such, iGoat is a safe environment where iOS developers can learn about the major security pitfalls they face as well as how to avoid them. It is made up of a series of lessons that each teach a single (but vital) security lesson.

* [OWASP MSTG Hacking Playground](https://github.com/OWASP/MSTG-Hacking-Playground)

  Collection of iOS and Android mobile apps, that are intentionally build insecure. These apps are used as examples to demonstrate different vulnerabilities explained in the the [OWASP Mobile Security Testing Guide](https://github.com/OWASP/owasp-mstg/).

* [Damn Vulnerable Router Firmware (DVRF)](https://github.com/praetorian-inc/DVRF)

  "The goal of this project is to simulate a real world environment to help people learn about other CPU architectures outside of the x86_64 space. This project will also help people get into discovering new things about hardware." Supplemental guides can be found on the author's blog: [1](https://p16.praetorian.com/blog/getting-started-with-damn-vulnerable-router-firmware-dvrf-v0.1), [2](https://p16.praetorian.com/blog/reversing-and-exploiting-embedded-devices-part-1-the-software-stack).

* [vulnserver](https://github.com/stephenbradshaw/vulnserver)

  Vulnserver is a multithreaded Windows based TCP server that listens for client connections on port 9999 (by default) and allows the user to run a number of different commands that are vulnerable to various types of exploitable buffer overflows.
# Lesson plans and guidance

This section contains a curated, ordered list of supplementary educational content in an effort to provide those who want it with a suggested course "to go from start to finish." Although listed "in order," there are no rules for how you go about your own education. Many topics reference related subjects, or provide only a shallow examination of them so if you find something confusing, consider jumping around a bit until you feel more at ease, or take a break and watch one of our [[favorite conference talks]] from years past.

1. [Hacker Highschool](http://hackerhighschool.org/)  
    Exceptionally friendly and thorough introduction to penetration testing ("hacking") and general security concepts written with teenagers in mind. Perfect for people who want a more guided path to learning network security and computer exploitation basics. Pair with [PicoCTF](https://picoctf.com/) ([described above](#recommended-ctfs)).
1. [Build a Computer from First Principles - Nand2Tetris](http://nand2tetris.org/)  
    A freely available course and textbook for self-learners about the construction of modern, full-scale computer systems—hardware and software. The course follows a bottom-up path beginning with how simple electrical circuits can store information (i.e., "computer memory") all the way through to the workings of a modern laptop. The lectures, book chapters and projects are modular, so you can pursue subsets of them in any desired order and scope. The chapters and projects related to memory storage, the assembler, and the parser have profound implications for and are thus particularly relevant to security.

    Alternatively, try [NandGame.com](http://nandgame.com/).
1. [Linux From Scratch](http://www.linuxfromscratch.org/)  
    These free guidebooks offer step-by-step instruction manuals for building a GNU/Linux system entirely from source code. (If you don't know what "a GNU/Linux system" is, read about [Why Linux Is Better](http://www.whylinuxisbetter.net/) first.) Being able to build directly from source, rather than rely on difficult-to-inspect binary packages distributed by vendors, offers extreme advantages to security-conscious users, so it's wise to gain experience doing this. After completing the main guide, additional guides focus on particular interest areas. Of these, the "[Hardened Linux From Scratch](http://www.linuxfromscratch.org/hlfs/)" guidebook, which "focuses on building an LFS system with heightened security," is of special note as it walks you through the process of configuring many of GNU/Linux's built-in security features. (Pair with [Michiel Derhaeg's "Build Linux" tutorial](https://github.com/MichielDerhaeg/build-linux).)
1. [CTF Field Guide](https://trailofbits.github.io/ctf/)  
    A handy companion guide for learning an interdisciplinary set of skills in infosec, with a mind towards practicing them by puzzling out various CTF challenges.
1. [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/)  
    A free guide by the makers of the free software exploitation framework known as Metasploit covering the basics of its use through a hands-on introduction in a practice environment against a pre-configured and deliberately vulnerable Linux system. Rather than expect this walk-through to explain the details of exploitation, use this guide to get a feel for the overall process of vulnerability discovery, assessment, exploitation, and persistence so that later guides that reference Metasploit and its numerous utilities are already at least cursorily familiar to you.
1. [Lecture Series: Introductory x86 (32 bit)](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)  
    A series of video lectures from Xeno Kovah's 2 day "Introductory x86" class in Fall of 2010. This is one of the more comprehensive free video resources for learning low-level programming (assembly language) and provides much of the background knowledge required to understand machine instructions and operation, for later use in exploit development ("shellcode") and reverse engineering. If you're having fun, continue on to [ARM Assembly Basics from Azeria Labs](https://azeria-labs.com/writing-arm-assembly-part-1/).
1. [Reverse Engineering for Beginners](https://beginners.re/)  
    A free e-book providing a complete study guide for learning how to analyze raw computer instructions and recover meaningful source code in the process. It provides [practice exercises](https://challenges.re/) for those with a modest existing understanding of compiled languages like C or Java to work through and explanations of each step in the process. Pair with [Malware Unicorn's Reverse Engineering 101 workshop](https://securedorg.github.io/RE101/).
1. [Programming Linux Anti-Reversing Techniques](https://leanpub.com/anti-reverse-engineering-linux)  
    A free e-book, with an accompanying pre-compiled binary, that "teaches the reader how to code and analyze well known anti-reversing techniques for Linux. The book shows how a reverse engineer analyzes a binary using tools like IDA, Radare2, GDB, readelf, and more." Useful for learning reverse engineering beginners. Its [companion repositories can be found on GitHub](https://github.com/antire-book).
1. [Crypto 101](https://www.crypto101.io/)  
    A free and condensed practical introductory course on cryptography, "freely available for programmers of all ages and skill levels." The book's Forward says it "starts with very simple primitives, and gradually introduces new ones, demonstrating why they’re necessary. Eventually, all of this is put together into complete, practical cryptosystems, such as TLS, GPG and OTR. The goal of this book is not to make anyone a cryptographer or a security researcher. The goal of this book is to understand how complete cryptosystems work from a bird’s eye view, and how to apply them in real software."
1. [A Graduate Course in Applied Cryptography](http://toc.cryptobook.us)  
    A free textbook developed for use in Stanford's and New York University's computer science and mathematics departments covering cryptography. A beginning reader can read though the book to learn how cryptographic systems work and why they are secure. Some knowledge of basic algebra and probability is assumed but you do not need prior experience with graduate-level mathematics courses to utilize this book. (See also [Coursera.org's Cryptography I course](https://www.coursera.org/learn/crypto), taught by one of this book's co-authors.) Use this text if you are already well-versed with the material covered in "Crypto 101" (above).

## More lesson material

* [Internet Security - Weaknesses and Targets (WT 2016/17)](https://www.tele-task.de/archive/series/overview/1130/)

  Lectures by Prof. Dr. Christoph Meinel on "Internet Security - Weaknesses and Targets" gives a detailed introduction on problems concerning Internet and intranet security. After starting with some remarks on risk analysis and computer crimes, security weaknesses and targets are discussed in detail. The lecture concludes with the discussion on possibilities to detect attacks and intrusions and ethical issuses are introduced as well.

* [The Cuckoo’s Egg: Tracking a Spy Through the Maze of Computer Espionage](https://en.wikipedia.org/wiki/The_Cuckoo%27s_Egg)

  The compellingly written non-fiction account of an astronomer turned system administrator named [Cliff Stoll](https://en.wikipedia.org/wiki/Clifford_Stoll) who, during his second day on the job, discovers an accounting error that leads to a highly personal and high-stakes hunt for a hacker attempting to infiltrate CIA and NSA computer systems. The events in the book take place in the mid-1980's, so the book offers a remarkable historic context on security system implementations and the humans who administered those systems at the time. Highly suggested reading material that's a little more exciting and a lot less dry than a textbook.

# For defenders

* [PrivacyTools.io](https://privacytools.io/)

  Simply start at the top and read down the page for an introduction to various privacy tools and relevant legal concepts. Each section provides a limited set of specific recommendations to follow up on. This is as brief a guided introduction to privacy issues and what to do about them as it gets. (For a more complete reference of privacy-enhancing software, see [PRISM-Break.org](https://prism-break.org/).)

* [Me and My Shadow](https://myshadow.org/)

  Start here if you're unconvinced that you "have something to hide." This site offers an accessible deep-dive into research about the data industry, how advertisers and communication service providers (like [Facebook](https://myshadow.org/lost-in-small-print/facebooks-data-policy) and [Google](https://myshadow.org/lost-in-small-print/googles-privacy-policy)) track you online, what they do with your information, and what you can do about it. It includes several [short privacy guides](https://myshadow.org/increase-your-privacy) along with a helpful [interactive visualization breaking down which activity leaves what type of data trail](https://myshadow.org/trace-my-shadow) and even an "[8-day data detox](https://myshadow.org/detox)" plan.

* [DIY Feminist Cybersecurity](https://hackblossom.org/resources/)

  A thorough walk-through showing how to implement basic and intermediate cybersecurity best practices, geared for oppressed groups whose likely adversary are trolls, white supremacists, and other individuals or mob-sized malicious actors. Written with careful explanations and a good grasp of the state of the art. Highly recommended reading for the politically conscious defender.

* [DIY Cybersecurity for Domestic Violence](https://hackblossom.org/domestic-violence/)

  A super-accessible guide providing "imminent technical support to survivors of domestic violence." This resource can be of use both to people facing intimate partner or domestic violence scenarios as well as anyone seeking a more focused guide regarding adversaries who are not State-level actors.

* [Crash Override Network // Resources](http://www.crashoverridenetwork.com/resources.html)

  A meta-list of additional resources written, compiled, and maintained by the Crash Override Network, including links to purpose-built guides such as [Prevent Doxing](http://www.crashoverridenetwork.com/preventingdoxing.html) and additional pointers to third-party explainers, such as the [Nonconsensual Intimate Images ("Revenge Porn") Removal Guide](https://www.cybercivilrights.org/online-removal/).

* [Feminist Frequency: Speak Up and Stay Safe(r)](https://onlinesafety.feministfrequency.com/en/)

  "This guide is for anyone who fears they might be targeted, or who is already under attack, for speaking their mind online, but is especially designed for women, people of color, trans and genderqueer people, and everyone else whose existing oppressions are made worse by digital violence. It details best security practices for social media, email, online gaming, website platforms, and ensuring privacy of personal information online, as well as the documentation and reporting of harassment, and caring for yourself emotionally during an online attack. You don’t need any specialized knowledge to use this guide – just basic computer and internet skills." Pair with the Crash Override Network's Prevent Doxing guide, linked above.

* [Surveillance Self-Defense](https://ssd.eff.org/)

  The [Electronic Frontier Foundation](https://eff.org/)'s comprehensive guide to using privacy-enhancing technologies for defending yourself and your friends from (primarily corporate and State) surveillance. You can [read it like a book, from beginning to end](https://ssd.eff.org/en/index), or you can jump to tutorials on specific tools, advice about choosing the tools in the first place ("[threat modeling](https://ssd.eff.org/en/module/introduction-threat-modeling)" for a [specific kind of user](https://ssd.eff.org/en/playlist)). Similar to [Security In a Box](https://securityinabox.org/).

* [Security In a Box](https://securityinabox.org/)

  A set of comprehensive guides to tools, tactics, and procedures for staying safer online and while using modern day necessities, like phones. The site is organized into sections covering basic principles ("Tactics Guides"), step-by-step instructions for specific tools ("Tool Guides"), and advice for people of specific demographics ("Community Guides") such as [women who are human rights defenders](https://securityinabox.org/en/women-hrds/). Similar to the [Electronic Frontier Foundation's Surveillance Self-Defense](https://ssd.eff.org/).

* [Exposing the Invisible: Watching Out for Yourself](https://exposingtheinvisible.org/resources/watching-out-yourself/)

  The [Tactical Technology Collective](https://tacticaltech.org/)'s "[Exposing the Invisible](https://exposingtheinvisible.org/)" project includes its own self-defense resource listing geared specifically for people using the Internet to conduct journalistic investigations. Notably, this resource includes discussions of how to more safely and [anonymously publish the results of investigations online](https://exposingtheinvisible.org/resources/watching-out-yourself/domain-games). Pair with the [Info-Activism How To Guide](https://howto.informationactivism.org/).

* [GenderSec: Zen and the Art of Making Technology Work for You](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual)

  The "complete manual" of personal digital security maintained by the Tactical Tech Collective's GenderSec Wiki. Available in English and in [Spanish](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual/es).

* [Digital Privacy at the U.S. Border](https://www.eff.org/wp/digital-privacy-us-border-2017)

  A detailed report regarding the special-case risks travelers face at the United States border circa 2017. The report includes suggestions for what to do before, during, and after crossing the border to protect your personal data, privacy, and legal rights from violation by border agents.

* [Current Digital Security Resources](https://medium.com/@mshelton/current-digital-security-resources-5c88ba40ce5c)

   A meta-list of additional security training resources for defenders in various situations, curated by digital security trainers making commitments update the list regularly. (This resource is probably more useful for trainers than it is for students, but it is useful nonetheless.) See also our own [[Persona-based training matrix]].

* [Radical Servers](https://riseup.net/en/security/resources/radical-servers)

  A directory of dozens of radical server projects around the world where you can get free or low-cost email, chat, VPN, social media, and other anti-corporate services. The tools available to you on one or more of these servers can be used as drop-in replacements for the so-called "free" services offered by corporations funded by surveillance capitalism, such as GMail, Facebook, Twitter, OneDrive, Dropbox, and so on. See also [LibreProjects.net](http://libreprojects.net/) for another view of the same information, and [AlternativeTo.net's "Open Source Self-Hosted" directory](https://alternativeto.net/platform/self-hosted/?license=opensource) for details about the free software powering these anti-corporate services, themselves.

# Other lists

* [android-security-awesome](https://github.com/ashishb/android-security-awesome)
* [awesome-ai-security](https://github.com/RandomAdversary/Awesome-AI-Security)
* [awesome-anti-censorship](https://github.com/danoctavian/awesome-anti-censorship)
* [awesome-appsec](https://github.com/paragonie/awesome-appsec)
* [awesome-aws](https://github.com/donnemartin/awesome-aws)
* [awesome-chaos-engineering](https://github.com/dastergon/awesome-chaos-engineering)
* [awesome-ctf](https://github.com/apsdehal/awesome-ctf)
* [awesome-cyber-security](https://github.com/fabionoth/awesome-cyber-security)
* [awesome-cyber-skills](https://github.com/joe-shenouda/awesome-cyber-skills)
* [awesome-cybersecurity-blueteam](https://github.com/meitar/awesome-cybersecurity-blueteam)
* [Awesome-Cybersecurity-Datasets](https://github.com/shramos/Awesome-Cybersecurity-Datasets)
* [awesome-decentralized-finance](https://github.com/ong/awesome-decentralized-finance)
* [awesome-devsecops](https://github.com/devsecops/awesome-devsecops)
* [awesome-firmware-security](https://github.com/PreOS-Security/awesome-firmware-security)
* [awesome-forensics](https://github.com/Cugu/awesome-forensics)
* [awesome-fuzzing](https://github.com/secfigo/awesome-fuzzing)
* [awesome-hacking](https://github.com/jekil/awesome-hacking)
* [awesome-hacking (meta-list)](https://github.com/Hack-with-Github/Awesome-Hacking)
* [awesome-hacking-tools](https://github.com/m4ll0k/Awesome-Hacking-Tools)
* [awesome-honeypots](https://github.com/paralax/awesome-honeypots)
* [awesome-incident-response](https://github.com/meirwah/awesome-incident-response)
* [awesome-industrial-control-system-security](https://github.com/hslatman/awesome-industrial-control-system-security)
* [awesome-infosec](https://github.com/onlurking/awesome-infosec)
* [awesome-iocs](https://github.com/sroberts/awesome-iocs)
* [awesome-linux-rootkits](https://github.com/milabs/awesome-linux-rootkits)
* [awesome-lockpicking](https://github.com/meitar/awesome-lockpicking)
* [awesome-macos](https://github.com/iCHAIT/awesome-macOS)
* [awesome-malware-analysis](https://github.com/rshipp/awesome-malware-analysis)
* [awesome-network-automation](https://github.com/networktocode/awesome-network-automation)
* [awesome-osint](https://github.com/jivoi/awesome-osint)
* [awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools)
* [awesome-pentest](https://github.com/enaqx/awesome-pentest)
* [awesome-pentest-cheat-sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets)
* [awesome-reversing](https://github.com/tylerph3/awesome-reversing)
* [awesome-red-teaming](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming)
* [awesome-sandbox-evasion](https://github.com/seifreed/awesome-sandbox-evasion)
* [awesome-sec-talks](https://github.com/PaulSec/awesome-sec-talks)
* [awesome-security-hardening](https://github.com/decalage2/awesome-security-hardening)
* [awesome-security-trivia](https://github.com/qazbnm456/awesome-security-trivia)
* [awesome-shodan-queries](https://github.com/jakejarvis/awesome-shodan-queries)
* [awesome-social-engineering](https://github.com/v2-dev/awesome-social-engineering)
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin)
* [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection)
* [awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence)
* [awesome-tor](https://github.com/ajvb/awesome-tor)
* [awesome-vehicle-security](https://github.com/jaredthecoder/awesome-vehicle-security)
* [awesome-virtualization](https://github.com/Wenzel/awesome-virtualization)
* [awesome-vulnerable](https://github.com/kaiiyer/awesome-vulnerable)
* [awesome-web-hacking](https://github.com/infoslack/awesome-web-hacking)
* [awesome-web-security](https://github.com/qazbnm456/awesome-web-security)
* [awesome-windows](https://github.com/Awesome-Windows/Awesome)
* [awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening)
* [confsec](https://github.com/cryptax/confsec)
* [osx-security-awesome](https://github.com/kai5263499/osx-security-awesome)
* [mgeeky/Penetration-Testing-Tools](https://github.com/mgeeky/Penetration-Testing-Tools)
* [zardus/ctf-tools](https://github.com/zardus/ctf-tools)
* [Aman Hardikar's mindmaps](http://www.amanhardikar.com/mindmaps.html)
* [Black Hat Arsenal Tools](https://github.com/toolswatch/blackhat-arsenal-tools)
* [CapTF.com's Practice CTF List](http://captf.com/practice-ctf/)
* [Exploitee.rs](https://www.exploitee.rs/)
* [Infosec Reference](https://github.com/rmusser01/Infosec_Reference)
* [MalwareAnalysis.Tools](http://malwareanalysis.tools/)
* [NetSec Focus - Learning Resources](https://docs.google.com/spreadsheets/d/1TD8KTRXvXwy1yU6s7Nz_JuNh7b7fa7pINZuHOVjtAAg/htmlview)
* [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
* [Security Now Curricula](http://wiki.twit.tv/wiki/Talk:Security_Now#Curricula)
* [Sneakerhax's Getting Started Resources](https://github.com/sneakerhax/Resources/blob/master/links/getting-started.md)
* [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge)

***

See also:

* related pages: [[Security culture]], [[NetSec]], [[PhySec]]
* [NYC-InfoSec.com](https://www.nyc-infosec.com/) - Calendar of infosec-related events in the New York City area.
* [New York Security Community](http://nysec.isis.poly.edu/)- Informal meetup of infosec professionals in NYC.
* [Objective-See.com](https://objective-see.com/) - Security-focused tools specifically designed for Apple's macOS.