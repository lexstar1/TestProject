# Threat Hunting Resources

# Platforms and Tools
- [MITRE ATT&CK](https://attack.mitre.org/wiki/Main_Page) - A curated knowledge base and model for cyber adversary behavior, reflecting the various phases of an adversary’s lifecycle and the platforms they are known to target.
- [MITRE CAR](https://car.mitre.org/wiki/Main_Page) - The Cyber Analytics Repository (CAR) is a knowledge base of analytics developed by MITRE based on the Adversary Tactics, Techniques, and Common Knowledge (ATT&CK™) adversary model.
- [MITRE ATT&CK Navigator](https://mitre.github.io/attack-navigator/enterprise/)([source code](https://github.com/mitre/attack-navigator)) - The ATT&CK Navigator is designed to provide basic navigation and annotation of ATT&CK matrices, something that people are already doing today in tools like Excel.
- [HELK](https://github.com/Cyb3rWard0g/HELK) - A Hunting ELK (Elasticsearch, Logstash, Kibana) with advanced analytic capabilities.
- [osquery](https://osquery.io/) - An operating system instrumentation framework for Windows, OS X (macOS), Linux, and FreeBSD. It exposes an operating system as a high-performance relational database.
- [osquery-configuration](https://github.com/palantir/osquery-configuration) - A repository for using osquery for incident detection and response.
- [DetectionLab](https://github.com/clong/DetectionLab/) - Vagrant & Packer scripts to build a lab environment complete with security tooling and logging best practices.
- [Sysmon-DFIR](https://github.com/MHaggis/sysmon-dfir) - Sources, configuration and how to detect evil things utilizing Microsoft Sysmon.
- [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config) - Sysmon configuration file template with default high-quality event tracing.
- [sysmon-modular](https://github.com/olafhartong/sysmon-modular) - A repository of sysmon configuration modules. It also includes a [mapping](https://github.com/olafhartong/sysmon-modular/blob/master/attack_matrix/README.md) of Sysmon configurations to MITRE ATT&CK techniques.
- [Revoke-Obfuscation](https://github.com/danielbohannon/Revoke-Obfuscation) - PowerShell Obfuscation Detection Framework.
- [Invoke-ATTACKAPI](https://github.com/Cyb3rWard0g/Invoke-ATTACKAPI) - A PowerShell script to interact with the MITRE ATT&CK Framework via its own API.
- [Unfetter](https://github.com/unfetter-analytic/unfetter) - A reference implementation provides a framework for collecting events (process creation, network connections, Window Event Logs, etc.) from a client machine and performing CAR analytics to detect potential adversary activity.
- [NOAH](https://github.com/giMini/NOAH) - PowerShell No Agent Hunting.
- [PSHunt](https://github.com/Infocyte/PSHunt) - Powershell Threat Hunting Module.
- [Flare](https://github.com/austin-taylor/flare) - An analytical framework for network traffic and behavioral analytics.
- [go-audit](https://github.com/slackhq/go-audit) - An alternative to the auditd daemon that ships with many distros.
- [sqhunter](https://github.com/0x4D31/sqhunter) - A simple threat hunting tool based on osquery, Salt Open and Cymon API.
- [Alerting and Detection Strategies Framework](https://github.com/palantir/alerting-detection-strategy-framework) - A framework for developing alerting and detection strategies.
- [A Simple Hunting Maturity Model](http://detect-respond.blogspot.com.au/2015/10/a-simple-hunting-maturity-model.html) - The Hunting Maturity Model describes five levels of organizational hunting capability, ranging from HMM0 (the least capability) to HMM4 (the most).
- [The Pyramic of Pain](http://detect-respond.blogspot.com.au/2013/03/the-pyramid-of-pain.html) - The relationship between the types of indicators you might use to detect an adversary's activities and how much pain it will cause them when you are able to deny those indicators to them.
- [A Framework for Cyber Threat Hunting](http://sqrrl.com/media/Framework-for-Threat-Hunting-Whitepaper.pdf)
- [The PARIS Model](http://threathunter.guru/blog/the-paris-model/) - A model for threat hunting.
- [Cyber Kill Chain](https://www.lockheedmartin.com/us/what-we-do/aerospace-defense/cyber/cyber-kill-chain.html) - It is part of the Intelligence Driven Defense® model for identification and prevention of cyber intrusions activity. The model identifies what the adversaries must complete in order to achieve their objective.
- [The DML Model](http://ryanstillions.blogspot.com.au/2014/04/the-dml-model_21.html) - The Detection Maturity Level (DML) model is a capability maturity model for referencing ones maturity in detecting cyber attacks.
- [Endgame Hunt Cycle](http://pages.endgame.com/rs/627-YBU-612/images/Endgame%20Hunt%20Methodology%20POV%203.24.16.pdf)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [Sigma](https://github.com/Neo23x0/sigma) - Generic Signature Format for SIEM Systems


## Videos

- [SANS Threat Hunting and IR Summit 2017](https://www.youtube.com/playlist?list=PLfouvuAjspTr95R60Kt7ZcoerR6tYoCLA)
- [SANS Threat Hunting and IR Summit 2016](https://www.youtube.com/playlist?list=PLfouvuAjspTokaa-LdUHqszL-KACkCsKT)
- [BotConf 2016 - Advanced Incident Detection and Threat Hunting using Sysmon and Splunk](https://www.youtube.com/watch?v=vv_VXntQTpE)
- [BSidesCharm 2017 - Detecting the Elusive: Active Directory Threat Hunting](https://www.youtube.com/watch?v=9Uo7V9OUaUw)
- [BSidesAugusta 2017 - Machine Learning Fueled Cyber Threat Hunting](https://www.youtube.com/watch?v=c-c-IQ5pFXw)
- [Toppling the Stack: Outlier Detection for Threat Hunters](https://www.youtube.com/watch?v=7q7GGg-Ws9s)
- [BSidesPhilly 2017 - Threat Hunting: Defining the Process While Circumventing Corporate Obstacles](https://www.youtube.com/watch?v=bDdsGBCUa8I)
- [Black Hat 2017 - Revoke-Obfuscation: PowerShell Obfuscation Detection (And Evasion) Using Science](https://www.youtube.com/watch?v=x97ejtv56xw)
- [DefCon 25 - MS Just Gave the Blue Team Tactical Nukes](https://www.youtube.com/watch?v=LUtluTaEAUU)
- [BSides London 2017 - Hunt or be Hunted](https://www.youtube.com/watch?v=19H7j_sZcKc)
- [SecurityOnion 2017 - Pivoting Effectively to Catch More Bad Guys](https://www.youtube.com/watch?v=_QVhMPGtIeU)
- [SkyDogCon 2016 - Hunting: Defense Against The Dark Arts](https://www.youtube.com/watch?v=mKxGulV2Z74)
- [BSidesAugusta 2017 - Don't Google 'PowerShell Hunting'](https://www.youtube.com/watch?v=1mfVPLPxKTc)
- [BSidesAugusta 2017 - Hunting Adversaries w Investigation Playbooks & OpenCNA](https://www.youtube.com/watch?v=8qM-DnmHNv8)
- [Visual Hunting with Linked Data](https://www.youtube.com/watch?v=98MrgfTFeMo)
- [RVAs3c - Pyramid of Pain: Intel-Driven Detection/Response to Increase Adversary's Cost](https://www.youtube.com/watch?v=zlAWbdSlhaQ)
- [BSidesLV 2016 - Hunting on the Endpoint w/ Powershell](https://www.youtube.com/watch?v=2MrrOxsJk_M)
- [Derbycon 2015 - Intrusion Hunting for the Masses A Practical Guide](https://www.youtube.com/watch?v=MUUseTJp3jM)
- [BSides DC 2016 - Practical Cyborgism: Getting Start with Machine Learning for Incident Detection](https://www.youtube.com/watch?v=2FvP7nwb2UE&feature=youtu.be)
- [SANS Webcast 2018 - What Event Logs? Part 1: Attacker Tricks to Remove Event Logs](https://www.youtube.com/watch?v=7JIftAw8wQY)
- [Threat Hunting Academy](https://threathunting.org)
