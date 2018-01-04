
# Containerization

Running all these tools in your host OS can be problematic.

The goal of this effort is to make it possible (not necessary, but possible) to run each of these tools within a container.

This has some advantages:

* Decouple the tool from its environment.
* Insulate this toolkit from upstream entropy in the respective tools' projects.

## The Plan

Some tools may already have container images, some may have Dockerfiles, others may require new effort in 
containerization, and yet others may not be a good fit for containerization.

Let us explore that list here:

| Tool | Comment | Should be Containerized? | in DockerHub? | Has Dockerfile? | Ready to Containerize? |
|--|--|--|--|--|--|
| [doork](https://github.com/AeonDave/doork) | Passive Vulnerability Auditor | ? | ? | ? | ? |
| [BruteX](https://github.com/1N3/BruteX) | Automatically brute force all services running on a target | ? | ? | ? | ? |
| [arachni](https://github.com/Arachni/arachni) | Web Application Security Scanner Framework | ? | ? | ? | ? |
| [XSStrike](https://github.com/UltimateHackers/XSStrike) | Crawl, fuzz and bruteforce parameters for XSS | ? | ? | ? | ? |
| [Crips](https://github.com/Manisso/Crips) | IP Tools To quickly get information about IP Address's, Web Pages and DNS records | ? | ? | ? | ? |
| [weeman](https://github.com/samyoyo/weeman) | HTTP Server for phishing | ? | ? | ? | ? |
| [gabriel.py](http://pastebin.com/raw/Szg20yUh) | FTP Server auth bypass exploit | ? | ? | ? | ? |
| [ch01.py](http://pastebin.com/raw/Y0cqkjrj) | Test open web shells | ? | ? | ? | ? |
| [bsqlbf.pl](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/bsqlbf-v2/bsqlbf-v2-7.pl) | Shitty SQL injection utility | ? | ? | ? | ? |
| [atscan.pl](https://github.com/AlisamTechnology/ATSCAN) | Advanced Search & Mass Exploit Scanner | ? | ? | ? | ? |
| [comix](https://github.com/stasinopoulos/commix) | OS command injection and exploitation tool | ? | ? | ? | ? |
| [pixiewps](https://github.com/wiire/pixiewps) | bruteforce offline the WPS PIN | ? | ? | ? | ? |
| [VBulletinRCE](http://pastebin.com/raw/eRSkgnZk) | RCE for VBulletin | ? | ? | ? | ? |
| [JoomlaRCE](http://pastebin.com/raw/EX7Gcbxk) | RCE for Joomla | ? | ? | ? | ? |
| [IsInURL](https://github.com/googleinurl/SCANNER-INURLBR) | Multi-purpose vulnerability scanner | ? | ? | ? | ? |

