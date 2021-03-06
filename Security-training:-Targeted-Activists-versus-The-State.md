> [[Wiki|Home]] ▸ [[Security culture]] ▸ [[Persona-based training matrix]] ▸ **Security training: Targeted Activists versus The State**

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
      [[Organizers &amp; Journalists vs Assholes with Resources|Security training: Organizers and Journalists versus Assholes with Resources#organizers-and-journalists-versus-assholes-with-resources]]
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
      <strong>Targeted Activists vs The State</strong>
    </td>
  </tr>
</table>

# Targeted Activists versus The State

## Prerequisites

Before you dive too deeply into this practice material, you should first explore the following lower-hanging fruit in the following order:

1. [[Security training: Individuals versus Random Assholes]]
1. [[Security training: Individuals versus Assholes with Resources]]
1. [[Security training: Individuals versus The State]]
1. [[Security training: Organizers and Journalists versus Random Assholes]]
1. [[Security training: Organizers and Journalists versus Assholes with Resources]]
1. [[Security training: Organizers and Journalists versus The State]]
1. [[Security training: Targeted Activists versus Random Assholes]]
1. [[Security training: Targeted Activists versus Assholes with Resources]]

## Practices

* [Don't maintain long-term OpenPGP keys](https://blog.filippo.io/giving-up-on-long-term-pgp/), try following the suggestions in [Operational PGP](https://gist.github.com/grugq/03167bed45e774551155) instead
* Use *only* hardware you trust:
  * Replace any commercial firmware on your devices with [LibreBoot](https://libreboot.org/).
  * If you can't use LibreBoot, at least [patch your Intel-based logic boards](https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00075&languageid=en-fr) against CVE-2017-5689 (see [Wikipedia](https://en.wikipedia.org/wiki/Intel_Active_Management_Technology#Silent_Bob_is_Silent)). (See [this HowToGeek article for more on the legitimate use of Intel ME](https://www.howtogeek.com/56538/how-to-remotely-control-your-pc-even-when-it-crashes/).)
* "Use encrypted email." (OpenPGP/GPG/PGP)
    * [GPGTools.org](https://gpgtools.org/) for macOS, optionally without a paid license via [Libmacgpg-free](https://github.com/macgpg/libmacgpg-free)
* Use [Qubes](https://www.qubes-os.org/), a hardened and security compartmentalized operating system generally
* Use [Tails](https://tails.boum.org/) for handling specific, extremely sensitive material
* [Create an anonymous Signal phone number with Android](https://yawnbox.com/2015/03/14/create-an-anonymous-textsecure-and-redphone-phone-number/)
* Completely disable the Intel ME subsystem in your hardware:
    * [Step-by-step guide to disabling the Intel Management Engine (Gentoo Wiki)](https://wiki.gentoo.org/wiki/Sakaki%27s_EFI_Install_Guide/Disabling_the_Intel_Management_Engine)
    * [me_cleaner](https://github.com/corna/me_cleaner)
* Enable the [Speculative store bypass disable (SSBD) bit](https://blogs.technet.microsoft.com/srd/2018/05/21/analysis-and-mitigation-of-speculative-store-bypass-cve-2018-3639/) in your BIOS/UFI/firmware/hardware systems.