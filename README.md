# Overview

This repository is a living document of the lists currently in use for my implementations of PiHole. The primary focus for this collection is to block as many ads, trackers, and call homes as possible. This list has not been de-duplicated.

Current stats, at time of last commit, are:

![](/assets/piholestats.png)

# Environment

SOHO with ~100 clients
rPi 3b

# Future Tasks
- [X] Group lists in to categories for use in group management (kids devices, IoT, etc)
- [ ] Consolidate lists to remove duplicates
- [ ] Integrate with MISP/CTI feeds to create a list of domains assocated with known IOCs

# Lists
## Adverts and Trackers
* https://adaway.org/hosts.txt
* https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt
* https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt
* https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt
* https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&showintro=0&mimetype=plaintext
* https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt
* https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt
* https://www.github.developerdan.com/hosts/lists/tracking-aggressive-extended.txt
* https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/AmazonFireTV.txt
* https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt
* https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt
* https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts
* https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts
* https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts
* https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt
* https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts
* https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt
* https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
* https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts
* https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt
* https://v.firebog.net/hosts/AdguardDNS.txt
* https://v.firebog.net/hosts/Admiral.txt
* https://v.firebog.net/hosts/Easylist.txt
* https://v.firebog.net/hosts/Easyprivacy.txt
* https://v.firebog.net/hosts/neohostsbasic.txt
* https://v.firebog.net/hosts/Prigent-Ads.txt
* https://v.firebog.net/hosts/static/w3kbl.txt
* https://winhelp2002.mvps.org/hosts.txt

## Porn
* https://energized.pro/unified/formats/hosts.txt

## Malware, Phishing, or Adware
* ~~https://bitbucket.org/ethanr/dns-blacklists/raw/8575c9f96e5b4a1308f2f12394abd86d0927a4a0/bad_lists/andiant_APT1_Report_Appendix_D.txt~~ **dead link** 
* https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-malware.txt
* https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt
* https://phishing.army/download/phishing_army_blocklist_extended.txt
* https://raw.githubusercontent.com/HorusTeknoloji/TR-PhishingList/master/url-lists.txt
* https://raw.githubusercontent.com/DandelionSprout/adfilt/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt
* https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts
* https://raw.githubusercontent.com/matomo-org/referrer-spam-blacklist/master/spammers.txt
* https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt
* https://raw.githubusercontent.com/Spam404/lists/master/main-blacklist.txt
* https://s3.amazonaws.com/lists.disconnect.me/simple_malvertising.txt
* https://someonewhocares.org/hosts/zero/hosts
* https://urlhaus.abuse.ch/downloads/hostfile/
* https://v.firebog.net/hosts/Prigent-Crypto.txt
* https://v.firebog.net/hosts/Prigent-Malware.txt
* https://v.firebog.net/hosts/Shalla-mal.txt








