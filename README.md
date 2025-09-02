<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./azul-text-glitched.dark.svg">
  <img alt="Azul Logo ('AZUL' spelt in a glitched font)" src="./azul-text-glitched.light.svg" width="60%">
</picture>

<br>
<br>

Azul is a malware repository, analytical engine and clustering suite dedicated to handling malware. 
It is designed to be highly scalable, and store tens of millions of samples. It continuously updates
file results as updates to detection logic are authored.

Azul was created to improve productivity of reverse engineers. Manual reverse engineering can take
hours to get basic IOCs out of samples, days to determine capabilities of malware, and months to get
an in depth understanding of families of malware.

Through use of Azul, the outputs of this manual analysis can be inserted into an automated workflow.
This can remove the need for re-analysis of similar samples of malware. Usage of Azul can identify
variants of a family of malware though techniques beyond Yara rules.

Azul does not perform binary triage, i.e. it does not identify if files are malicious. Anything stored
in Azul should be identified as suspicious or malicious either through binary triage tools 
like [Assemblyline](https://github.com/CybercentreCanada/assemblyline), or through incident response
activities / threat hunting / honeypots.

Azul is an official product of the Australian Signals Directorate.

## Getting Started

Documentation for getting started can be found in Azul's [documentation](https://asd-azul.github.io).

## Getting Help

If you are experiencing an issue with Azul, please raise an issue in this repository (other repositories
have issue reporting disabled given how many there are). Support is best effort for Azul.

Experiencing a cyber security incident? Visit <https://cyber.gov.au> or call 1300 292 371 (1300 CYBER 1)
to report cybersecurity incidents and access alerts and advisories. We cannot provide cyber incident
advice through this forum.

## Licencing

Azul is [licenced](./license.md) under the MIT Licence. Docker images ship with dependencies that may be
licenced differently; it is your responsibility to validate that these meet your needs.

