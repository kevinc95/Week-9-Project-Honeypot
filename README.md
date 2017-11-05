# Project 9 - Honeypot

Time spent: **16** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

Honeypots deployed: 
* mhn-honeypot-1: Ubuntu - Dionaea with HTTP
* mhn-honeypot-2: Ubuntu - ElasticHoney 
* mhn-honeypot-3: Ubuntu - Kippo as vulnerable Juniper Netscreen
* mhn-honeypot-4: Ubuntu - Amun
* mhn-honeypot-5: Ubuntu - Suricata

Issues:
* Most of the issues I encountered came from setting up the the VMs. Since this assignment was more vague in its instructions, I ran into a lot of issues, such as no traffic on the Attack page, unable to download files, issues setting up, etc. However I was able to figure them out eventually after a lot of help.

Number of Attacks:
* HoneyPot 1: 1504
* HoneyPot 2: 0
* HoneyPot 3: 1257
* HoneyPot 4: 3151
* HoneyPot 5: 371
* Total: 6283

Top 5 Attacker IPs:
* China - 118.186.36.50 - 1099 Attacks
* USA - 24.111.136.238 - 195 Attacks
* France - 62.210.146.201 - 175 Attacks
* China - 123.206.207.134 - 114 Attacks
* Taiwan - 220.143.24.39 - 113 Attacks

Top 5 Attacked Ports:
* 445 - 1870 Times
* 22 - 1376 Times
* 23 - 999 Times
* 3389 - 979 Times
* 5060 - 209 Times

Remaining Questions:
* I'm not quite sure why HoneyPot 2, ElasticHoney, did not get any attacks. It could have been because I did not set up the HoneyPot correctly, or attackers simply did not want to attack it. The other HoneyPots definitely seemed more desirable compared to ElasticHoney.