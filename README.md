# Footprinting-and-reconnaissance-using-public-tools
## 🎯 Objectives

- Understand the difference between Footprinting and Reconnaissance
- Perform passive footprinting using OSINT tools
- Identify potential information leakage

## 🧠 Introduction

This lab focuses on Footprinting and Reconnaissance, which are the first phases of ethical hacking.

- Reconnaissance: Gathering general information about a target
- Footprinting: Collecting detailed data to identify potential entry points

Target used:
- samsung.com

## 🛠️ Tools Used
- whois
- nslookup
- shodan
- mxtoolbox
- sublister
- wappalyzer

## 1️⃣ Tools: whois
Whois is an Internet protocol that is used to query databases to obtain information about the registration of a domain name

Run this command to see the results:
```
whois samsung.com
```
```
example output:-

Domain Name : samsung.com
Registry Domain ID: 1521529_DOMAIN_COM-VRSN
Registrar WHOIS Server: whois.co.kr
Registrar URL: https://www.whois.co.kr
Updated Date: 2025-10-22T07:00:50Z
Creation Date: 1994-11-29T05:00:00Z
Registrar Registration Expiration Date: 2026-11-28T05:00:00Z
Registrar: Whois Corp.
```

## 2️⃣ Tools: nslookup
nslookup is used to query DNS servers to find IP addresses, domain records, and troubleshoot network connectivity

Run this command to see the results:
```
nslookup samsung.com
```
```
expected output:-

Server:         1.1.1.1
Address:        1.1.1.1#53

Non-authoritative answer:
Name:   samsung.com
Address: 211.45.27.231
```


## 3️⃣ Tools: shodan
Shodan is a search engine for internet‑connected devices that indexes service “banners” HTTP headers, and other metadata from IPv4 address space to reveal exposed systems and configuration risks

Links: https://www.shodan.io/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 4️⃣ Tools: mxtoolbox
Mxtoolbox is used to diagnose, monitor, and troubleshoot infrastructure issues which is allows you to run multiple network diagnostic tests from a single interface.

Links: https://mxtoolbox.com/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 5️⃣ Tools: Sublist3r
Sublist3r is designed to enumerate subdomains of websites using OSINT

Run this command to see the results:

```
sublist3r -d samsung.com
```
```
Findings:-

www.samsung.com
account.samsung.com
chn.account.samsung.com
policies.account.samsung.com
status.account.samsung.com
terms.account.samsung.com
us.account.samsung.com
v3.account.samsung.com
aims.samsung.com
www.aims.samsung.com
allshareplay.samsung.com
remote.america.samsung.com
careers.ap.samsung.com
support.apac.samsung.com
apahflfit2015.samsung.com
www.apahflfit2015.samsung.com
apps.samsung.com
btool.apps.samsung.com
www.btool.apps.samsung.com
careplus.apps.samsung.com
health.apps.samsung.com
www.health.apps.samsung.com
internet.apps.samsung.com
closeby.internet.apps.samsung.com
```


## 6️⃣ Tools: Wappalyzer
Wappalyzer is a technology profiler and browser extension that identifies the software, frameworks, CMS, analytics, and tools powering websites

Links: https://www.wappalyzer.com/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 7️⃣ Tools: Wappalyzer
Wappalyzer is a technology profiler and browser extension that identifies the software, frameworks, CMS, analytics, and tools powering websites

Links: https://www.wappalyzer.com/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 8️⃣ Tools: netcraft
Netcraft used to discover and explore websites and subdomains associated with a specific domain

Links: https://searchdns.netcraft.com/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 9️⃣ Tools: Pentest Tools
Pentest Tools is a cloud-based platform that provides an all-in-one toolkit for penetration testing and vulnerability assessment

Links: https://pentest-tools.com/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.

## Reverse Image Search
## Tools: Google Image

Reverse image search will let us know:

- Find where an image appears online
- Identify the source of the image
- Discover related images or info

Links: https://www.google.com/imghp?hl=EN

Just insert or drag the photo that have saved and click the search button.

Findings:
- Image found on multiple websites
- Possible source identified
- Related images discovered


## Metadata
Based on this tables, use the links to open the source and run the commands on kali linux to get the result of the photo given.

|   Tools              |  Command                 | Links                                    |
| --------             | --------                 | --------------                           |
| exiftool             | exiftool ocean.jpg       |https://exif.tools/                       |
| hexeditor            | hexeditor computer.jpg   |https://hexed.it/                         |
| binwalk              | binwalk dog.jpg          |                                          |
| binwalk              | binwalk -e dog.jpg       |                                          |
| binwalk              | cd _dog.jpg.extracted/   |                                          |
| strings              | strings computer.jpg     |https://www.dcode.fr/strings-extractor    |
| file (check fie)     | Cell 2                   |file solitaire.exe                        |
| file (check file)    | Cell 4                   |file rubiks.jpg                           |


## 🔟 Tools: Wayback Machine
Wayback Machine is used to view archived versions of web pages across time

Links: https://archive.org/ and https://pastebin.com/j1UnKA7m

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.


## 11 Tools: Whatsmyname
Whatsmyname is an OSINT tool designed for enumerating usernames across a wide array of websites

Links: https://whatsmyname.app/

In search engine insert domain name:
```
samsung.com
```
The result will show up all the details.



