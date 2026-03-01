# PhishIndex Threat Blocklist 
Welcome!

This regularly updated blocklist contains several types of data, primarily relating to cybersecurity.

| Data Type | Description  |  Formats | Update Schedule |
| -------- | -------- | -------- | :------: |
| Malicious Domains   | Heavily automated list containing malicious domains, mainly phishing but also sometimes malware. These are mainly from external sources as listed below, but sometimes include our own threat intelligence. |   JSON, TXT, ADBLOCK   | Automated (every 2 hours)|
| IP Logger Domains    | Manually updated list containing domains used by certain IP logging service providers to track user IP addresses, which might potentially lead to doxxing. These type of services are often used by online communities to coordinate harassment.  | JSON, TXT, ADBLOCK |  Manual (every 3 months) |
| Domain Hosting Providers  | Manually updated list containing services which allow users to host a website free of charge on their domain like randomwebsite.weebly.com. These are heavily favored by threat actors to conduct phishing campaings as they are easy to create. | JSON, TXT, ADBLOCK |Manual (every 3 months) |
| URL Shorteners | Manually updated list containing domains used by URL Shortening services. These types of services can and often are used by attackers to evade detections from security providers. | JSON, TXT, ADBLOCK |Manual (every 3 months) |

#
**Data accuracy:**
Per our License, this software and/or data is provided as is without warranty of any kind. However, we do try to still be as accurate as possible, so:

- If you encounter a false positive (aka things that SHOULDN'T have been flagged) in any of our data, please notify us as soon as possible via the methods outlined in the "Contact" section. For the malicious domains collected from external sources, you'll need to contact them to remove false positives.

- If there are any false negatives (aka things that SHOULD have been flagged), please also notify us as soon as possible via the methods outlined in the "Contact" section.
#
## Threat Intelligence Sources
We rely on the amazing work of the cybersecurity community to ensure protection for everyone. Special thanks to them for helping us protect the web.

For some of the malicious domains,
- We use https://github.com/Phishing-Database/Phishing.Database. Their license can be found here: https://github.com/Phishing-Database/Phishing.Database/blob/master/LICENSE.
- We also use https://github.com/Zaczero/pihole-phishtank to get data from https://phishtank.com. Their license can be found here: https://github.com/Zaczero/pihole-phishtank/blob/main/LICENSE. 

As we automate the collection of these links, we cannot always be certain but there is a good chance modifications were made, like removing false positives or ensuring proper formatting. The full text of their license can be found in [external_licenses.md](https://github.com/PhishIndex/phishindex-blocklist/blob/main/external_licenses.md).

#
## Contact
To report malicious activity or false positives, go to phishindex.com/report. 

To contact us, visit phishindex.com/contact.
