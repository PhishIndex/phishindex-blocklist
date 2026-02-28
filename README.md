# PhishIndex Threat Blocklist 
This blocklist is primarily used by the PhishIndex browser extension to detect and flag malicious links. We combine data from open source blocklists and our own threat intelligence. Three seperate blocklists exist:
- All_urls includes both the External URLs, and the PhishIndex URLs.
- External_urls are collected from the threat intelligence sources as outlined below.
- PhishIndex_urls are discovered and collected by us or our automated systems and do not include links from the threat intelligence sources.   

## Threat Intelligence Sources
We rely on the amazing work of the cybersecurity community to ensure protection for everyone. Special thanks to them for helping us protect the web.

- We use https://github.com/Phishing-Database/Phishing.Database. Their license can be found here: https://github.com/Phishing-Database/Phishing.Database/blob/master/LICENSE.

- We also use https://github.com/Zaczero/pihole-phishtank to get data from https://phishtank.com. Their license can be found here: https://github.com/Zaczero/pihole-phishtank/blob/main/LICENSE. 



As we automate the collection of these links, we cannot always be certain but there is a good chance modifications were made, like removing false positives or ensuring proper formatting. The full text of their license can be found in [Other/External_licenses.md](https://github.com/PhishIndex/phishindex-blocklist/blob/main/Other/External_licenses.md)


## Contact
To report malicious activity or false positives, go to phishindex.com/report. 

To contact us, visit phishindex.com/contact.

