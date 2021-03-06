> [[Wiki|Home]] ▸ [[Security culture]] ▸ [[Persona-based training matrix]] ▸ **Security training: Organizers and Journalists versus Assholes with Resources**

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
    <th colspan="3">[[Attackers|Persona-based training matrix#attackers]]</th>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th>[[Random Assholes|Persona-based training matrix#random-assholes]]</th>
    <th>[[Assholes with Resources|Persona-based training matrix#assholes-with-resources]]</th>
    <th>[[The State|Persona-based training matrix#the-state]]</th>
  </tr>
  <tr>
    <th rowspan="3">[[Defenders|Persona-based training matrix#defenders]]</th>
    <th>[[Individuals|Persona-based training matrix#individuals]]</th>
    <td>
      [[Individuals vs Random Assholes|Security training: Individuals versus Random Assholes#individuals-versus-random-assholes]]
    </td>
    <td>
      [[Individuals vs Assholes with Resources|Security training: Individuals versus Assholes with Resources#individuals-versus-assholes-with-resources]]
    </td>
    <td>
      [[Individuals vs The State|Security training: Individuals versus The State#individuals-versus-the-state]]
    </td>
  </tr>
  <tr>
    <th>[[Organizers and Journalists|Persona-based training matrix#organizers-and-journalists]]</th>
    <td>
      [[Organizers &amp; Journalists vs Random Assholes|Security training: Organizers and Journalists versus Random Assholes#organizers-and-journalists-versus-random-assholes]]
    </td>
    <td>
      <strong>Organizers &amp; Journalists vs Assholes with Resources</strong>
    </td>
    <td>
      [[Organizers &amp; Journalists vs The State|Security Training: Organizers and Journalists versus The State#organizers-and-journalists-versus-the-state]]
    </td>
  </tr>
  <tr>
    <th>[[Targeted Activists|Persona-based training matrix#targeted-activists]]</th>
    <td>
      [[Targeted Activists vs Random Assholes|Security training: Targeted Activists versus Random Assholes#targeted-activists-versus-random-assholes]]
    </td>
    <td>
      [[Targeted Activists vs Assholes with Resources|Security training: Targeted Activists versus Assholes with Resources#targeted-activists-versus-assholes-with-resources]]
    </td>
    <td>
      [[Targeted Activists vs The State|Security training: Targeted Activists versus The State#targeted-activists-versus-the-state]]
    </td>
  </tr>
</table>

# Organizers and Journalists versus Assholes with Resources

## Prerequisites

Before you dive too deeply into this practice material, you should first explore the following lower-hanging fruit in the following order:

1. [[Security training: Individuals versus Random Assholes]]
1. [[Security training: Individuals versus Assholes with Resources]]
1. [[Security training: Organizers and Journalists versus Random Assholes]]

## Practices

* Audit your webserver for information disclosure vulns ([a thorough treatment of webdev security things](https://github.com/FallibleInc/security-guide-for-developers)):
    * Turn off "directory listings" on your webserver
    * [WordPress users should follow these guidelines](http://www.wpbeginner.com/wordpress-security/)
* Use alternatives to Google Docs such as pad.RiseUp.net or share.RiseUp.net, etc.
* Prevent spoofing of emails claiming to be from your domain by [implementing DKIM](https://scotthelme.co.uk/email-security-dkim/) for email services you provide
    * Use the [ValiMail Domain Checker](http://www.valimail.com/dmarc/domain-checker) to check that your domain is correctly configured to be able to accept and relay validated/authenticated email.
    * Use [DKIM Verifier for Thunderbird](https://addons.mozilla.org/thunderbird/addon/dkim-verifier/) to test your (or anyone else's) DKIM setup in your email client.
* On your server(s), use [LetsEncrypt](https://letsencrypt.org/) to enable TLS connections (for Web+Mail+any hosted service)
    * Specify a [CAA (Certificate Authority Authorization) DNS record](https://en.wikipedia.org/wiki/DNS_Certification_Authority_Authorization) for your domain to assert only your CA of choice (like Let's Encrypt) should issue certificates for your domain.
* Use [Tor](https://torproject.org/) to hide your physical-world location
* Consider placing your own domain behind CloudFlare to hide your server's origin
* Replace Facebook (or other similar) group chats with secure messenger (e.g., Signal) group chats
* Turn off all logging by the services you run you don't regularly look at. (Configure per-service or using [`logrotate(8)`](https://linux.die.net/man/8/logrotate) `rotate 0` and `shred` configuration options.)
* [Test RSA keys you've generated against the ROCA vulnerability](https://keychest.net/roca) and re-key if necessary.
* Use a hardware second factor (an "authentication dongle") on [sites that support hardware-enforced second factor authentication support](http://www.dongleauth.info/).
* Whitelist external USB, Thunderbolt, etc. devices with tools such as [USBGuard](https://usbguard.github.io/).
* If you run an Intel motherboard, [change the default Intel AMT BIOS password from its default of `admin`](http://support.radmin.com/index.php?/Knowledgebase/Article/View/9/9/how-to-set-up-intel-amt-features).