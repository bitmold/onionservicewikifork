> [[Wiki|Home]] ▸ [[Activities and events]] ▸ [[Trivia night]] ▸ **Challenge exports**

Simple archival space for various runs of our own or affiliated [[Trivia night]] that have been shared.

# [Hacker Trivia Night, May 2020](https://techlearningcollective.com/events/2020/05/event-2020-05-29-hacker-trivia-night-restaurant-and-bar-night)

This challenge set is in FBCTF's JSON format. See the [FBCTF FAQ](https://github.com/facebookarchive/fbctf/wiki/FAQ#how-can-i-mass-create-and-import-levels-such-as-quizzes-and-flags) for more details.

```json
{
    "levels": [
        {
            "type": "quiz",
            "title": "Weasel words",
            "active": true,
            "description": "Which of the following are email providers that automatically and by default encrypt all of your outgoing email?\n\nA) GMail\nB) RiseUp\nC) ProtonMail\nD) Mailinator\nE) None of the above\nF) All of the above",
            "entity_iso_code": "BY",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "E",
            "hint": "\"Automatically and by default\" means the original, 'factory settings' configuration of the service. \"All outgoing email\" means email that gets copied to your Sent folder.",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "\"Aren't you worried about Signal not being secure?\"",
            "active": true,
            "description": "Under what conditions would the Signal Private Messenger app not be able to protect the confidentiality of your messages?\nA) Device compromise\nB) Legal subpoena\nC) Network eavesdropping\nD) Compromised Signal Server\nE)Rogue Signal server\nF) Signal servers go down",
            "entity_iso_code": "GB",
            "category": "Quiz",
            "points": 25,
            "bonus": 0,
            "bonus_dec": 4,
            "bonus_fix": 30,
            "flag": "A",
            "hint": "What is \"end-to-end\" encryption for?",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "FU HODL GANG",
            "active": true,
            "description": "In what year was the first commercial digital currency company founded?",
            "entity_iso_code": "JP",
            "category": "Quiz",
            "points": 5,
            "bonus": 0,
            "bonus_dec": 0,
            "bonus_fix": 30,
            "flag": "1990",
            "hint": "The same technology that makes BitCoin addresses possible, public key encryption, was used in this early attempt as well.",
            "penalty": 3,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Easy Dox",
            "active": true,
            "description": "You get a disappearing Signal message from your friend informing you of a new \"alt-right\" group whose website claims it is active in your neighborhood. Your friend wants to know the legal identities of the site operators. What is the first tool you run?",
            "entity_iso_code": "US",
            "category": "Quiz",
            "points": 25,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "whois",
            "hint": "Who is the registered domain owner?",
            "penalty": 15,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "What's in a lock icon?",
            "active": true,
            "description": "When your Web browser displays a healthy green lock icon near the address bar, indicating that certain portions of your Web browsing activity have been \"secured,\" which of the following are nevertheless visible to a passive, third-party eavesdropper?\nA) The entire URL you are loading.\nB) The page contents.\nC) Your IP address.\nD) The page contents and your IP address.\nE) The Web browser you are using.\nF) The domain name of the site you are visiting and your IP address.",
            "entity_iso_code": "BR",
            "category": "Quiz",
            "points": 25,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "F",
            "hint": "The lock icon signifies the use of HTTPS, which indicates the use of TLS to encapsulate HTTP protocol traffic. What must remain unencrypted on the outside of the TLS wrapper in order for your Web browser to receive a sensible reply?",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Rumpelstiltskin",
            "active": true,
            "description": "The three inventors of this critical technology had the initials RR, AS, and LA. What first name does the \"L\" refer to?",
            "entity_iso_code": "IR",
            "category": "Quiz",
            "points": 25,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "Leonard",
            "hint": "An equivalent technology was independently invented by a second trio about a decade prior but was classified for many years.",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "TOS;DR",
            "active": true,
            "description": "You are creating your profile on a hip, new dating site. You prefer to fudge the facts on some of the profile fields (age, weight, etc.) when asked. What is the strictest possible legal penalty you could face if your embellishments are discovered by an overzealous government prosecutor (i.e., District Attorney)?\n\nA) Misdemeanor conviction\nB) Felony conviction and 5 years\nC) Felony conviction and 10 years\nD) Felony conviction and 20 years\nE) You must pay a fine\nF) Account suspension",
            "entity_iso_code": "DE",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "D",
            "hint": "Supplying fake information in the process of using a computer system may legally constitute computer fraud.",
            "penalty": 6,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Ogres are like onions",
            "active": true,
            "description": "In the Tor onion routing scheme, a packet must traverse a minimum number of Tor servers (a \"hop\") in order to protect both the sender (its source) and the receiver (the destination) from eavesdroppers outside of the Tor network and within the network itself. What is the minimum number of hops through the Tor network a packet must take in order to have this quality of protection?",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 30,
            "bonus": 15,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "3",
            "hint": "How many different types of Tor nodes are there?",
            "penalty": 15,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "VPS vs. Tor",
            "active": true,
            "description": "For reasons, you require an extraordinarily secure and anonymous connection to the public Internet. At your disposal is the Tor network, a VPN provider, and a C2 (Command and Control) server you can use for any purpose. Which of the following configurations do you use for maximum security and the highest anonymity guarantees to build your connection?\n]nA) VPN only; VPNs are safer than Tor\nB) Tor only; Tor is safer than a VPN\nC) Both: connect to the VPN first, then anonymize your connection through Tor\nD) Both: connect to Tor first, then secure your connection through the VPN\nE) Both, plus a Tor bridge on the C2 server: connect to the Tor bridge first, then the Tor network, then the VPN\nF) Neither VPN or Tor; there are far better tools available",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 30,
            "bonus": 15,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "E",
            "hint": "It's not paranoia if they're really out to get you.",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Little Bobby Tables",
            "active": true,
            "description": "You get a frantic call from your friend who runs a campaign website saying their homepage has been replaced with a hateful message. During your analysis of the site's Web server logs, you see the following snippet:\n\n```\n200.123.45.67 - - [02\/Jul\/2018:22:07:14 -0500] \"GET \/ HTTP\/1.1\" 200 487\n200.123.45.67 - - [02\/Jul\/2018:22:22:02 -0500] \"GET \/index.aspx?page=contact HTTP\/1.1\" 200 23049\n200.123.45.67 - - [02\/Jul\/2018:22:22:24 -0500] \"GET \/index.aspx?page=' HTTP\/1.1\" 500 23513\n200.123.45.67 - - [02\/Jul\/2018:22:22:09 -0500] \"GET \/index.aspx?page=' or 1=1--  HTTP\/1.1\" 200 23381\n29.231.97.105 - - [02\/Jul\/2018:22:18:56 -0500] \"GET \/ HTTP\/1.1\" 200 487\n29.231.97.105 - - [02\/Jul\/2018:22:19:23 -0500] \"GET \/index.aspx?page=contact HTTP\/1.1\" 200 23049\n```\n\nWhat is the most salient course of action you should advise your friend to take?\n\nA) Fixing the homepage is enough, as the XSS attack is temporary.\nB) Fix the homepage and reset all user passwords.\nC) Completely wipe the server and rebuild the database and website from a backup.\nD) Completely wipe the server, patch the `index.aspx` script, rebuild the database and website from a backup, and send emails to every subscribed user informing them of the breach.\nE) Restore the website files from a recent backup to fix the homepage, then change all user passwords, but retain the current database.\nF) Fix the homepage, then change hosting providers.",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 35,
            "bonus": 20,
            "bonus_dec": 10,
            "bonus_fix": 30,
            "flag": "D",
            "hint": "At what line in the log is the first indication of an error present?",
            "penalty": 15,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Special secure delivery",
            "active": true,
            "description": "When sending encrypted e-mails using S\/MIME, your mail program may write additional metadata on the metaphorical envelope of your e-mail that describes the quality of security applied to the message. What is the recommended way for an e-mail program to describe that an S\/MIME-encrypted message was encrypted, but not signed?",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 35,
            "bonus": 30,
            "bonus_dec": 10,
            "bonus_fix": 30,
            "flag": "smime-type=enveloped-data",
            "hint": "RFC 3851 describes the \"Secure\/Multipurpose Internet Mail Extensions\" message specification.",
            "penalty": 15,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "More than you bargained for?",
            "active": true,
            "description": "Which of the following are risks associated with using free Wi-Fi such as a hotspot at a caf\u00e9, restaurant, or park?\n\nA) You might connect to websites you didn't intend by succumbing to a machine-in-the-middle (MITM) attack.\nB) You might unknowingly install malware when connecting using a \"captive portal\" log on page.\nC) The other people using the same Wi-Fi network as you can see which websites you're visiting.\nD) You could be sharing your physical whereabouts and movement with advertising companies.\nE) None of the above; public Wi-Fi is always perfectly safe.\nF) All of the above.",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 15,
            "bonus": 12,
            "bonus_dec": 4,
            "bonus_fix": 30,
            "flag": "F",
            "hint": "Well, how safe are public water fountains?",
            "penalty": 5,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Cleaning the cookie jar",
            "active": true,
            "description": "You should consider clearing both your Web browser's \"cache\" and \"cookies\" when\u2026\n\nA) \u2026you need to free up more space on your hard disk drive.\nB) \u2026you see a \"Your connection is not secure\" error when loading a web page.\nC) \u2026a website you're visiting is loading but not working properly and you want to reload it \"from scratch.\"\nD) \u2026you are trying to stop targeted advertising from appearing on your Facebook page.\nE) \u2026you want to hide your IP address from the website you are visiting.\nF) \u2026a video or audio file is not loading quickly enough.",
            "entity_iso_code": "FR",
            "category": "Quiz",
            "points": 20,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "C",
            "hint": "",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "VPS vs. Tor",
            "active": true,
            "description": "For reasons, you require an extraordinarily secure and anonymous connection to the public Internet. At your disposal is the Tor network, a VPN provider, and a C2 (Command and Control) server you can use for any purpose. Which of the following configurations do you use for maximum security and the highest anonymity guarantees to build your connection?\n]nA) VPN only; VPNs are safer than Tor\nB) Tor only; Tor is safer than a VPN\nC) Both: connect to the VPN first, then anonymize your connection through Tor\nD) Both: connect to Tor first, then secure your connection through the VPN\nE) Both, plus a Tor bridge on the C2 server: connect to the Tor bridge first, then the Tor network, then the VPN\nF) Neither VPN or Tor; there are far better tools available",
            "entity_iso_code": "ES",
            "category": "Quiz",
            "points": 30,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "E",
            "hint": "It's not paranoia if they're really out to get you.",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Little Bobby Tables",
            "active": true,
            "description": "You get a frantic call from your friend who runs a campaign website saying their homepage has been replaced with a hateful message. During your analysis of the site's Web server logs, you see the following snippet:\n\n```\n200.123.45.67 - - [02\/Jul\/2018:22:07:14 -0500] \"GET \/ HTTP\/1.1\" 200 487\n200.123.45.67 - - [02\/Jul\/2018:22:22:02 -0500] \"GET \/index.aspx?page=contact HTTP\/1.1\" 200 23049\n200.123.45.67 - - [02\/Jul\/2018:22:22:24 -0500] \"GET \/index.aspx?page=' HTTP\/1.1\" 500 23513\n200.123.45.67 - - [02\/Jul\/2018:22:22:09 -0500] \"GET \/index.aspx?page=' or 1=1--  HTTP\/1.1\" 200 23381\n29.231.97.105 - - [02\/Jul\/2018:22:18:56 -0500] \"GET \/ HTTP\/1.1\" 200 487\n29.231.97.105 - - [02\/Jul\/2018:22:19:23 -0500] \"GET \/index.aspx?page=contact HTTP\/1.1\" 200 23049\n```\n\nWhat is the most salient course of action you should advise your friend to take?\n\nA) Fixing the homepage is enough, as the XSS attack is temporary.\nB) Fix the homepage and reset all user passwords.\nC) Completely wipe the server and rebuild the database and website from a backup.\nD) Completely wipe the server, patch the `index.aspx` script, rebuild the database and website from a backup, and send emails to every subscribed user informing them of the breach.\nE) Restore the website files from a recent backup to fix the homepage, then change all user passwords, but retain the current database.\nF) Fix the homepage, then change hosting providers.",
            "entity_iso_code": "CA",
            "category": "Quiz",
            "points": 35,
            "bonus": 0,
            "bonus_dec": 10,
            "bonus_fix": 30,
            "flag": "D",
            "hint": "At what line in the log is the first indication of an error present?",
            "penalty": 15,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "More than you bargained for?",
            "active": true,
            "description": "Which of the following are risks associated with using free Wi-Fi such as a hotspot at a caf\u00e9, restaurant, or park?\n\nA) You might connect to websites you didn't intend by succumbing to a machine-in-the-middle (MITM) attack.\nB) You might unknowingly install malware when connecting using a \"captive portal\" log on page.\nC) The other people using the same Wi-Fi network as you can see which websites you're visiting.\nD) You could be sharing your physical whereabouts and movement with advertising companies.\nE) None of the above; public Wi-Fi is always perfectly safe.\nF) All of the above.",
            "entity_iso_code": "GT",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 4,
            "bonus_fix": 30,
            "flag": "F",
            "hint": "Well, how safe are public water fountains?",
            "penalty": 5,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Cleaning the cookie jar",
            "active": true,
            "description": "You should consider clearing both your Web browser's \"cache\" and \"cookies\" when\u2026\n\nA) \u2026you need to free up more space on your hard disk drive.\nB) \u2026you see a \"Your connection is not secure\" error when loading a web page.\nC) \u2026a website you're visiting is loading but not working properly and you want to reload it \"from scratch.\"\nD) \u2026you are trying to stop targeted advertising from appearing on your Facebook page.\nE) \u2026you want to hide your IP address from the website you are visiting.\nF) \u2026a video or audio file is not loading quickly enough.",
            "entity_iso_code": "MX",
            "category": "Quiz",
            "points": 20,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "C",
            "hint": "",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Gone fishing",
            "active": true,
            "description": "Which of the following are examples of \"phishing\" attacks?\n\nA) You check your email to find one stating that your PayPal account will be deactivated unless you click on a re-activation link.\nB) You log on to a Wi-Fi hotspot to check your Facebook, but the green padlock is missing from your browser's Web address bar.\nC) You receive a voicemail informing you that you have won an all-expense paid cruise and giving you a number to dial to claim your prize.\nD) As you're reading your favorite blog, a pop-up appears informing you that your computer has a virus and offers a link to download an anti-virus program.\nE) You get a txt message from a friend with a very short link asking you if the photo behind the link is really you.\nF) All of the above.",
            "entity_iso_code": "VN",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "F",
            "hint": "",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Alphabet soup",
            "active": true,
            "description": "Controlling many computers from a single keyboard simultaneously is something that many system administrators regularly do for legitimate purposes. However, when an attacker is doing something similar and the computers they are controlling don't legally belong to them, the computers they are controlling are part of\u2026\n\nA) a DDoS attack.\nB) a kettle.\nC) a coven.\nD) a botnet.\nE) an OS.\nF) SQL.",
            "entity_iso_code": "ZW",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "D",
            "hint": "",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Easier than herding cats",
            "active": true,
            "description": "Which of the following activities would a hacker's botnet not be particularly well-suited to accomplish?\n\nA) Network reconnaisance.\nB) DDoS attacks.\nC) Data exfiltraion.\nD) Network proxying.\nE) Sending spam.\nF) Compute parallelization.",
            "entity_iso_code": "NG",
            "category": "Quiz",
            "points": 15,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 30,
            "flag": "A",
            "hint": "",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Defund, divest, and abolish",
            "active": true,
            "description": "Between the dates of January 1, 2015 and May 29, 2020 how many people are known to have been killed by police officers across the United States?",
            "entity_iso_code": "AU",
            "category": "Quiz",
            "points": 50,
            "bonus": 0,
            "bonus_dec": 5,
            "bonus_fix": 10,
            "flag": "5338",
            "hint": "Relevant datasets are available in unexpected places, such as software code hosting sites.",
            "penalty": 10,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Looters in Blue",
            "active": true,
            "description": "As of fiscal year 2018, what was the annual budget of the New York City Police Department?",
            "entity_iso_code": "CU",
            "category": "Quiz",
            "points": 10,
            "bonus": 2,
            "bonus_dec": 2,
            "bonus_fix": 6,
            "flag": "5600000000",
            "hint": "Enter the number in decimal without punctuation. Make sure you have the correct number of zeros.",
            "penalty": 0,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "Never forget",
            "active": true,
            "description": "Well before the World Trade Center buildings were destroyed on September 11th, the National Security Agency was developing a mass surveillance program under the guidance of Thomas Drake, who would later be ousted from the secretive spy agency after he became a whistleblower trying to warn the American public that their government had become \"completely unchained from the Constitution.\" What was the name of the surveillance system Drake helped develop before it became known to the world in a bombshell New York Times article in 2004 under its new name, Operation Stellar Wind?",
            "entity_iso_code": "ZM",
            "category": "Quiz",
            "points": 35,
            "bonus": 15,
            "bonus_dec": 5,
            "bonus_fix": 20,
            "flag": "ThinThread",
            "hint": "One word, rhymes with \"tim said.\"",
            "penalty": 5,
            "links": [],
            "attachments": []
        },
        {
            "type": "quiz",
            "title": "FTP",
            "active": true,
            "description": "When converted into hexadecimal, the decimal number 44,203 reveals a profound truth. How is the hexadecimal number written?",
            "entity_iso_code": "EG",
            "category": "Quiz",
            "points": 30,
            "bonus": 5,
            "bonus_dec": 5,
            "bonus_fix": 15,
            "flag": "ACAB",
            "hint": "Spelled like DEADBEEF, not 0xDEADBEEF.",
            "penalty": 5,
            "links": [],
            "attachments": []
        }
    ]
}
```