Software Security
=================

### Trivia
Professor Axel Legay (axel.legay@uclouvain.be)
Academic year 2018-2019 (Q2)

## Introduction
Objectives:
* Make sure that a system does what it is intended to do.
* Understand and mitigate vulnerabilities in systems as much as possible.

Examination:
* Oral exam (60%, 100% if 2nd session)
* 2 Group Projects (40%)

Books:
* Main book: "Hacking, the art of exploitation"
* Other books available in the slides

>**Security** is protection against voluntary malicious actions. Cannot be quantified.

>**Safety** is protection against unintended consequences. Safety helps security. Can have statistics on hardware life duration.

>**Cyber security** reduces risks to limit their impact.

A side effect of cyber security is not to obfuscate, but it can be a side effect. Security has a financial cost.

Malicious actors are composed of various groups. Attackers, hosts, re-sellers, ... They seek financial reward, blackmails, intelligence, resources, ideologies. Hacking has many impacts on private life, including loss of privacy and/or data, identity thefts, financial losses.

#### Security triad
* Disponibility : Data can be accessed when needed by those who are allowed.
* Integrity : Data must be exact and complete.
* Confidentiality : Data can only be accessed by those who are allowed.

Risk = Attackers * Vulnerability * Impact

There are methods to evaluate the risks, dedicated or not, free or not. This class is focused on vulnerabilities of softwares.

### Attack Classification
* **Indiscriminate attacks:** wide-ranging and global, without specific target.
* **Destructive attacks:** inflicting damage on specific organisation
* **Cyberwarfare attacks:** politically motivated destructive attacks (related to sabotage and espionage).
* **Government espionage attack:** stealing government information.
* **Corporate espionage attack:** staling proprietary methods. (example of the UK that attacked Belgacom in 2013, they managed to gain geolocalization of people).

### Vulnerabilities
>**Vulnerability** is a weakness of the asset (software, human), exploited by the attacker (threat).

The timeline of an attack is not clearly defined but in general:
1. Spy: find a vulnerability
2. Intrusion: Exploit the vulnerability to access the system
3. Escalation/spread: Escalade privileges (get root)
4. Attack: Break one or more cyber security attribute
5. Disappear: Erase your traces

In this course, we will limit ourselves to a few attack types and we won't see step 5. *Professor reminds us to only try this in secured and private environments and to not try on real systems as it could lead to legal actions.*
