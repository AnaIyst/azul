<p align=center>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./azul-text-glitched.dark.svg">
    <img alt="Azul Logo ('AZUL' spelt in a glitched font)" src="./azul-text-glitched.light.svg" width="60%">
  </picture>
</p>

Azul is a malware knowledge base designed for malware achiving, analytics and clustering.
It is designed to be highly scalable, and store hundreds of millions of samples. It continuously
updates file results as updates to detection logic are authored.

Azul was created to improve the productivity of reverse engineers. Manual reverse engineering can take
hours to get basic IOCs out of samples, days to determine the capabilities of malware, and months to get
an in-depth understanding of malware families.

Reverse engineers can use Azul to to turn common analysis steps into analysis plugins,
which can be used as part of an automated workflow.
This reduces the need for manual re-analysis of similar samples of malware, and can assist in identifying
variants of a malware family through techniques beyond [Yara](https://virustotal.github.io/yara/) rules.

Azul does not perform binary triage; that is, it does not identify whether files are malicious. 
Anything stored in Azul should first be identified as suspicious or malicious either through binary triage tools 
like [Assemblyline](https://github.com/CyberCentreCanada/assemblyline),
or through incident response activities / threat hunting / honeypots.

Azul is an official product of the Australian Signals Directorate.

## Getting started

Documentation for getting started can be found in Azul's [documentation](https://asd-azul.github.io).

## Getting help

If you are experiencing a problem with Azul, please raise an issue in this repository
(other repositories have issue reporting disabled given how many there are).
Support for Azul does not have a guaranteed response time, and is provided on a "best-effort" basis.

Experiencing a cyber security incident? Visit <https://cyber.gov.au> or call 1300 292 371 (1300 CYBER 1)
to report cybersecurity incidents and access alerts and advisories. The Azul team cannot provide cyber incident advice.

## Licensing

Azul is [licensed](./license.md) under the MIT Licence. Docker images ship with included dependencies that may be
licensed differently; it is your responsibility to verify that these licences permit your intended use.
