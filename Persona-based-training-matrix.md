> [[Wiki|Home]] ▸ [[Security culture]] ▸ **Persona-based training matrix**

This page introduces a **persona-based framework with which to approach information (infosec), operations (opsec), and especially communications security (comsec).**

> 📝 💡 This material is not intended to be an end-user resource, but rather a resource for digital security and communications privacy trainers or teachers. Its goal is to provide a resource to **meet the following challenge: "how do we teach [threat modeling](https://ssd.eff.org/en/module/introduction-threat-modeling), without ever saying the word 'threat model' or using any other jargon, to people who don't want to have to care about digital/computer security, but know that they need to care anyway?"** This material is intended to constructively supplement, not replace, existing resources compiled elsewhere. The focus is on filling in gaps left by other guides and highlighting appropriate practices at certain levels of concern; this is a scaffold on which to hang [[the rest of your security training education|InfoSec#for-defenders]].

There are two types of personas consisting of three broad groupings. These two types, "defenders" (you) and "attackers" (them), are laid out according to their group's capabilities, creating a three-by-three matrix. This matrix is linearized and inter-linked below.

1. [Motivation](#motivation)
1. [The matrix](#the-matrix)
1. [Personas](#personas)
    1. [Defenders](#defenders)
       1. [Individuals](#individuals)
       1. [Organizers and Journalists](#organizers-and-journalists)
       1. [Targeted Activists](#targeted-activists)
    1. [Attackers](#attackers)
       1. [Random Assholes](#random-assholes)
       1. [Assholes with Resources](#assholes-with-resources)
       1. [The State](#the-state)

> 📝 Editor's note: Please read about [the process we're using to create this material](#triage).
> 
> 🚧 TK-TODO: This matrix was used in [the Better Angels's "Practical digital security" workshop](https://github.com/betterangels/better-angels/wiki/Practical-digital-security); figure out the best way to consolidate/contribute to this or that resource in tandem.

# Motivation

We created this "persona-based" framework with which to approach information (infosec), operations (opsec), and especially communications security (comsec) for several reasons. Based in our own experiences and our observations that many efforts to encourage less-technical people to adopt security best practices have failed, we note that the way most of these efforts fail are not random. Rather, they exhibit specific patterns.

Nevertheless, communications security ("[COMSEC](https://en.wikipedia.org/wiki/Communications_security)") is a critical practice both for maintaining personal privacy and for sustaining any larger-scale resistance against the nearly hegemonic systems of domination and oppression we face in our day-to-day lives. Although many guides for actualizing this practice already exist, most display biases that make them more useful for certain kinds of "activists" over others. Some resources use inaccessible and exclusionary language, either by using unclear jargon or by making insensitive assumptions about gender or race.

The failure modes we most commonly observed are:

1. Often, we are unable to find information appropriate to the specific threats we face. That is, most security guides assume our only adversary is the NSA. This is *absurd*, and most people are correctly ignoring advice from these guides.
1. Security guides use highly technical concepts and jargon terms before introducing their fundamental principles. For instance, describing a "public key infrastructure" is in an article written for laypeople is nonsensical because there is never a time when those three words are uttered in sequence unless you are a computer security professional. Most people like us who may be struggling to make rent cannot be reasonably expected to understand what this means.
1. Often, "experts" simply demand that people take too many actions in too short a time. This is exacerbated by the clickbait nature of news, with lists of "tips" that don't thoroughly explain what each "tip" is or why it's useful. Confused readers are bombarded with a list of *many* things they don't understand, so they naturally feel overwhelmed and shut down.

These are on top of the implicit (cis)sexism and capitalist framing of many of these guides, which are simply so pervasive that we consider an exhaustive accounting of these obstacles superfluous here.

# The matrix

<table border="1" cellpadding="10" cellspacing="0">
  <caption>
    <p>How to use this persona-based threat modeling matrix:</p>
    <ol>
      <li>You are a "defender" (a given row). Find yourself there.</li>
      <li>Your concern(s) map to a given "attacker" (a given column). Find your attacker.</li>
      <li>Find the cell at which these two personas intersect. Everything listed in the cells above and to the left of your cell applies to you, too.</li>
      <li>Start at the top-left cell and read the advice from left-to-right, top-to-bottom, until you reach your cell. Then stop worrying. :)</li>
    </ol>
  </caption>
  <tr>
    <th></th>
    <th></th>
    <th colspan="3"><a href="#attackers">Attackers</a></th>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th><a href="#random-assholes">Random Assholes</a></th>
    <th><a href="#assholes-with-resources">Assholes with Resources</a></th>
    <th><a href="#the-state">The State</a></th>
  </tr>
  <tr>
    <th rowspan="3"><a href="#defenders">Defenders</a></th>
    <th><a href="#individuals">Individuals</a></th>
    <td>
      [[Individuals vs Random Assholes|Security training: Individuals versus Random Assholes#individuals-versus-random-assholes]]
    </td>
    <td>
      [[Individuals vs Assholes with Resources|Security training: Individuals versus Assholes with Resources#individuals-versus-assholes-with-resources]]
    </td>
    <td>
      <a href="#individuals-vs-the-state">Individuals vs The State</a>
    </td>
  </tr>
  <tr>
    <th><a href="#organizers-and-journalists">Organizers and Journalists</a></th>
    <td>
      [[Organizers &amp; Journalists vs Random Assholes|Security training: Organizers and Journalists versus Random Assholes#organizers-and-journalists-versus-random-assholes]]
    </td>
    <td>
      [[Organizers &amp; Journalists vs Assholes with Resources|Security training: Organizers and Journalists versus Assholes with Resources#organizers-and-journalists-versus-assholes-with-resources]]
    </td>
    <td>
      <a href="#organizers--journalists-vs-the-state">Organizers &amp; Journalists vs The State</a>
    </td>
  </tr>
  <tr>
    <th><a href="#targeted-activists">Targeted Activists</a></th>
    <td>
      <a href="#targeted-activists-vs-random-assholes">Targeted Activists vs Random Assholes</a>
    </td>
    <td>
      <a href="#targeted-activists-vs-assholes-with-resources">Targeted Activists vs Assholes with Resources</a>
    </td>
    <td>
      <a href="#targeted-activists-vs-the-state">Targeted Activists vs The State</a>
    </td>
  </tr>
</table>

# Personas

In the context of this resource, a "persona" is simply a coarse grouping of entities, divided into two opposing categories: "defenders" and "attackers." There are three defenders per persona category.

## Defenders:

A "defender" is a [persona](#personas) that roughly describes one "half" of a given threat model. Defenders in our framework are:

* **[Individuals](#individuals):** people responsible for themselves
* **[Organizers and Journalists](#organizers-and-journalists):** people responsible for other people as well
* **[Targeted Activists](#targeted-activists):** you know who you are

### Individuals

An "individual," for our purposes, is any person who is primarily concerned with *their own* privacy and security. This can be:

* A citizen of a country who uses social media to post about their mundane daily activities.
* An employee of a corporation who uses company resources (either hardware, software, or network infrastructure) to perform personal tasks such as banking, emailing, and so on.
* A member of an oppressed group who faces threats other individuals may not, such as a woman with a jilted ex-lover, an undocumented immigrant, people of color, queer youth, and so on.

### Organizers and Journalists

An "organizer," for our purposes, is any person whose safety concerns extend to other people as well as themselves, for any reason. This notably includes "journalists" because, by definition, they are responsible for the safety of their source as well as themselves, but can also include other roles as well. Some examples of other social roles who our framework considered "organizers" include:

* System administrators responsible for maintaining the information systems of companies or community groups
* Community organizers (activists) who take some part in explicit political activity
* Individuals who engage in controversial subcultures and practices, despite not being "explicitly political" about it, such as people who run or simply participate regularly in LGBT or mental health support groups, and so on.

### Targeted Activists

If you are a "targeted activist," you probably know who you are because you've self-identified yourself to yourself as one, and we'll just leave it at that.

## Attackers

An "attacker" is a [persona](#personas) that roughly describes one "half" of a given threat model. Attackers in our framework are:

* **[Random Assholes](#random-assholes):** malicious individuals, harassers or unsophisticated mobs
* **[Assholes with Resources](#assholes-with-resources):** organized hate groups, rogue cops, more sophisticated / technical Random Assholes, more dedicated assholes (e.g. "jilted lovers" with resources)  
* **[The State](#the-state):** Governments, surveillance apparatus & multinational corporations (Wal-Mart, Apple+Google+Facebook, etc.)

### Random Assholes

A "random asshole," for our purposes, is an individual or uncoordinated mob whose intent is to cause malicious harm. This can include:

* Twitter eggs, individual Trump supporters, and so on
* A (relatively *un*skilled) person who holds a grudge against you for some reason
* Racist co-workers
* Loosely coordinated mobs of trolls and hate-mongers such as Stormfront, "4chan," and so on

### Assholes with Resources

The ambiguous part of this persona is the "resources" part. This can mean a number of different things in practice, but the unifying thread is that there is some additional capability that these specific assholes have that "random assholes" don't. That distinction means that "assholes with resources" could be:

* A jilted ex-lover who happens to be an employee of a company such as Google or Facebook that has access to your personal information
* Technically skilled individuals with grudges
* Unethical app/web service developers, even and perhaps especially the "well-intentioned" ones
* Government or law enforcement employees (who are acting without formal backing from their agency) such as rogue cops
* Organized "cybercrime" groups who have some cyber-attack infrastructure in place for other means (botnet herders, phishers, and so on)

### The State

For our purposes, "The State" is an attacker persona that combines multinational corporations and governments, because corporations and governments tend to have similar if not identical resources and also often act in tandem/cooperation with one another to achieve their ends. This means that "The State" can, concretely, include entities such as:

* Advertising-funded corporations such as Google and Facebook
* "Vertically integrated" tech companies such as Apple
* Intelligence community organizations such as the CIA, NSA, and so on
* Surveillance companies/cyberweapon manufacturers, including intelligence community contractors

# "Z-axis" aspects:

> 🚧 TK-TODO: This parts needs a closer look:
> 
> 1. Read through the list, categorizing each line item along a "z-axis"
> 1. Group the line items according to their z-axis
>     * **What about line items matching more than one z-axis; place in both subheads or just the one?

* Technical: "Categories" from [PRISM-Break](https://prism-break.org/en/all/), i.e., what to do for server security versus what to do for device/endpoint security versus what to do for data in motion/at rest.
* Behavior/habitual: [data management](https://myshadow.org/) and/or security hygiene best practices
* Financial: issues relating specifically to currency systems (which are de-facto surveillance apparati by definition)

# Individuals vs. The State

## Data management

* Encrypt your phone/laptop disk at rest (FileVault, Android Encryption, LUKS/cryptsetup)
* Make sure you read the privacy terms/terms of service/terms and policies of a service you sign up for. Remember, when you sign up for a online service, you are agreeing on a contract.
* Make sure you can actually delete your account after signing up and keep in mind that some services keep your data forever (even if you requested a deletion). You can use [Just delete me's](http://backgroundchecks.org/justdeleteme/) service so it warns you on how difficult is it to delete an account on the service you are currently browsing.
* Remember that using a service from a foreign country, you are subjected (in some terms) by their law, so make sure you go through the following check list (also make sure you do the same for your local service).
  1. Does the foreign/local service store your data in your country?
  1. Does the foreign/local service share any personal data with the government or any third party?
  1. Does the foreign/local service requires any personal data that may harm you in the future? If so, ask what they do with this information.
  1. Does the foreign/local service have any history with the government/police or any "privacy/corruption" scandal?
  1. Does the foreign/local service keep a [Canary Statement](https://en.wikipedia.org/wiki/Warrant_canary)? Check [Canary Watch](https://canarywatch.org) to see if your service is listed there, and if not, mail them asking if they keep such information public.

## Security hygiene and habits

* Use passphrases, not biometric unlock features such as fingerprints
* Use passphrases for locking your phone instead of PIN or Pattern.
* Use cash whenever possible, not a credit card or electronic payment system
* If you **need** to use credit-card to buy something (and you are currently based in US), use a random credit-card for each service. You can get that at [Privacy.com](https://privacy.com/).
* Switch your default search provider to a Google-alternative
* Uninstall the Facebook/Twitter/etc. apps and use the mobile web versions of these sites
* [Audit your Android device's app permissions](http://www.howtogeek.com/230683/how-to-manage-app-permissions-on-android-6.0/) and revoke any permissions granted to apps that enable features you don't use
* Use temporary emails/identities when making temporary use of services: use a [temporary email](https://temp-mail.org/en/) ([FakeMailGenerator.com](http://fakemailgenerator.com/) and similar sites) for that, and [fake names, birth dates and etc.](http://fakenamegenerator.com/) to go along with that temporary identity
* If possible, don't use hardware received from employer for personal use. (Why? "[Employee monitoring](https://www.privacyrights.org/consumer-guides/workplace-privacy-and-employee-monitoring).")
  * Similarly, never tell your boss/employer the passwords to personal accounts, even if "required" to by employment contracts (these clauses are illegal).
* Check the validity of the lock icon in your Web browser's address bar (TLS certificate validation practices)
* Don't use the default DNS your network provides, most of them are used for surveillance and profiling. Use [DNSCrypt](https://dnscrypt.org/) instead or the DNS provided by [OpenNIC Project](https://www.opennicproject.org/).

## Helpful tools

* Use certificate transparency monitoring tools ([like Facebook's](https://developers.facebook.com/tools/ct/)) to further check the trustworthiness of a given certificate (but, because FB is shit, they require you be logged in to a FB account)
* Use [TermsOfService;Didn't Read](https://tosdr.org/) to get up-to-speed on legal terms for a given service you're considering using.
* Turn off JavaScript using blockers such as [ScriptSafe](https://chrome.google.com/webstore/detail/scriptsafe/oiigbmnaadbkfbmpbfijlflahbdbdgdf) and [NoScript](https://noscript.net/) and re-enable it only on sites you purposefully visit
* Use [HTTPS Everywhere](https://www.eff.org/https-everywhere%20) so you make sure you send data to the service using HTTPS and not HTTP.

Also, a guide: [Digital Security Tips for Protesters](https://www.eff.org/deeplinks/2016/11/digital-security-tips-for-protesters)

# Organizers & Journalists vs. The State

## Security hygiene and habits

* Use alternate service providers (don't use Google's GMail)
* Ideally, use *decentralized* alternate services/networks
  * Have a Jabber+OMEMO fallback for Signal (for the truly frightening case where Signal is censored)
* [Secure your SSH servers](https://stribika.github.io/2015/01/04/secure-secure-shell.html).
* Use [DNS CAA](https://en.wikipedia.org/wiki/DNS_Certification_Authority_Authorization) records to help cut down on TLS certificate spoofing.

## Helpful tools

* Use Tor!!!!!11! (or a VPN)
* Host sites somewhere safe (privacytools.io)
* Consider [setting up an `.onion` service to access your site/domain](https://riseup.net/en/security/network-security/tor/onionservices-best-practices)
* Journalistic organizations should consider [SecureDrop](https://securedrop.org/)
* Use [MAT](https://mat.boum.org/) (or another tool) to remove document metadata before sharing online (specially if you need to protects your source)

# Targeted activists vs. Assholes with Resources

* Use the "High" security level in your TorBrowser (disables JavaScript, HTML5 Web Fonts, etc.)
* [Use dedicated virtual machines for specific purposes](https://theintercept.com/2015/09/16/getting-hacked-doesnt-bad/) to open documents you don't trust, and take other specialized tasks
* Clean/audit your device's root TLS certificate stores (for instance, with [RootCertificateCheck](http://www.ghacks.net/2015/04/05/scan-your-windows-computer-for-untrusted-root-certificates/))

# Targeted activists vs. The State

# Security hygiene and habits

* [Don't maintain long-term OpenPGP keys](https://blog.filippo.io/giving-up-on-long-term-pgp/), try following the suggestions in [Operational PGP](https://gist.github.com/grugq/03167bed45e774551155) instead

## Helpful tools

* encrypted email (GPG)
* Use [Qubes](https://www.qubes-os.org/), a hardened and security compartmentalized operating system generally
* Use [Tails](https://tails.boum.org/) for handling specific, extremely sensitive material

* * *

# Triage

> 📝 This list of links is a completely *unsorted* link-dump. These links need to be:
> 
> 1. Read (and, of course, actually understood) by an editor.
> 1. That editor should determine if the resource linked is useful and not already covered with more clarity at a different resource.
> 1. If useful, the material in these links needs to be incorporated somewhere into the appropriate place in the matrix, above.
> 
> Everyone is encouraged to add new links to this list as they wish; someone will eventually come back around and more thoroughly evaluate its contents. This also means, of course, that you shouldn't take "our word" (lol) for anything linked below.

* [CommunityRED: Scrub your personal data from the Internet](https://medium.com/@CommunityRED/feeling-scared-me-too-6ff2300e6836")
* [Install Google Authenticator for your accounts](https://support.google.com/accounts/answer/1066447?hl=en)
* [Lifehacker: Everyone's trying to track what you do on the Web. Here's how to stop them](https://lifehacker.com/5887140/everyones-trying-to-track-what-you-do-on-the-web-heres-how-to-stop-them)
* [Privacy Rights Clearinghouse's Consumer Guide on Workplace Privacy and Employee Monitoring](https://www.privacyrights.org/consumer-guides/workplace-privacy-and-employee-monitoring)
* [How to protect yourself against ICE raids](http://jlovelaw.com/updates/latest-news/157-how-to-protect-yourself-against-ice-raids)
* [Stanford University: Surveillance law](http://online.stanford.edu/course/surveillance-law)
* [A gentle introduction to threats and how to defend against them](https://maymay.net/blog/2015/07/28/cryptoparty-albuquerque-a-gentle-introduction-to-threats-and-how-to-defend-against-them/)" - A video and a heavily-hyperlinked transcript of a presentation for CryptoParty Albuquerque in 2015.
* [Know Your (Digital) Rights](https://maymay.net/blog/2015/08/08/cryptoparty-albuquerque-know-your-digital-rights/) - A legal primer from CryptoParty Albuquerque, in 2015.
* [MacOS security and Privacy guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide) - A solid and complete guide on securing your MacOS system. You can skip to the sections you want to secure and follow the guide as you want.
* [Current Digital Security Resources, 2016 Edition](https://medium.com/@mshelton/current-digital-security-resources-5c88ba40ce5c)
* [Security training resources for security trainers, Winter 2016](https://medium.com/@geminiimatt/security-training-resources-for-security-trainers-winter-2016-edition-4d10670ef8d3)