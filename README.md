Pedro sucks!

About me 😸
===========

A cinephile, there's nothing I like more than going to the movies (preferably with
others!) and eat some popcorn. I can watch just about anything, from superhero flicks to
period dramas to slapstick comedy. Some of the best movies I've ever watched are so
bad... but so, so good.

Professionally... let's just say I've been around. Started off as a
[structural engineer][cerne], but soon migrated to developing
[software for engineers][ftool] for a while. After a hiatus doing an MBA, went on to
work in the [financial industry][nch] doing data science. Looking to make more of an
impact, I went off to work with...

The Google Open Source Security Team (GOSST 👻)
===============================================

<img align="right"
 style="padding-left: 20px"
 src="https://user-images.githubusercontent.com/15221358/206766965-c4bf9258-39da-4851-b39a-57e8475d6b47.png">

GOSST was created in response to the 
[increasing supply-chain attacks][sonatype] on projects that consume open-source code.
It works along with the Linux Foundation's
[Open Source Security Foundation (OpenSSF)][ossf] to improve the security of the
open-source ecosystem. GOSST and the OpenSSF develop solutions to make open-source
software safer at scale. See here for [info][open-source-at-google] on Google's
open-source initiatives.

I'm part of a GOSST sub-team responsible for working hand-in-hand with the open-source
community. We focus on helping individual [critical projects][critical-projects]
increase their security. Our goals are to:

- develop specific approaches for each project;
- suggest solutions or enhancements that fit the project's needs and don't overburden
maintainers;
- talk with maintainers about our suggestion or about any other solutions they might
prefer;
- implement the changes and submit them as PRs;
- collect all feedback to be shared with the rest of GOSST and the OpenSSF.

Security Solutions
------------------

See below some of the tools developed by GOSST and the OpenSSF:

- [Scorecard][scorecard]: automated checks to evaluate a project's security practices
and suggest improvements as needed;
- [SLSA][slsa] (pronounced "salsa"): a standard and protocol to ensure an artifact's
provenance, guaranteeing it comes from the expected location and process. This aims to
prevent tampering and improve the integrity of infrastructure and consumed packages;
- [Sigstore][sigstore]: keyless signing and verification of artifacts;
- [OSS-FUZZ][oss-fuzz]: automated [fuzzing][fuzzing] at scale;
- [OSV][osv]: a human- and machine-readable database of vulnerabilities that
maps affected software versions across open source ecosystems;
- [GUAC][guac]: graph database of security metadata ([in development][guac-gh]).


[cerne]: https://www.cerneengenharia.com/
[critical-projects]: https://github.com/ossf/wg-securing-critical-projects
[ftool]: https://www.ftool.com.br/Ftool/
[fuzzing]: https://en.wikipedia.org/wiki/Fuzzing
[guac]: https://security.googleblog.com/2022/10/announcing-guac-great-pairing-with-slsa.html
[guac-gh]: https://github.com/guacsec/guac
[nch]: https://nchbrasil.com.br/
[ossf]: https://openssf.org/
[open-source-at-google]: https://opensource.googleblog.com/2021/08/metrics-spikes-and-uncertainty-open-source-contribution-during-a-global-pandemic.html
[scorecard]: https://securityscorecards.dev/
[sigstore]: https://www.sigstore.dev/
[slsa]: https://slsa.dev/
[sonatype]: https://www.sonatype.com/resources/state-of-the-software-supply-chain-2021
[oss-fuzz]: https://github.com/google/oss-fuzz
[osv]: https://osv.dev/
