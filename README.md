# PhishIndex Threat Blocklist

A comprehensive, regularly updated blocklist designed to protect against phishing, malware, and other security threats.

---

## What's Included

| Data Type | Description | Formats | Update Frequency |
| -------- | -------- | -------- | :------: |
| **Malicious Domains** | Automatically collected list of phishing and malware domains from our own threat intelligence tools and external sources. | JSON, TXT, Adblock | Every 2 hours |
| **IP Logger Domains** | Domains used by IP logging services that can facilitate doxxing and online harassment. | JSON, TXT, Adblock | Manually updated |
| **Free Hosting Providers** | Services that offer free website hosting on subdomains (e.g., yoursite.weebly.com) are frequently exploited for phishing campaigns due to ease of setup. | JSON, TXT, Adblock | Manually updated |
| **URL Shorteners** | URL shortening services are commonly used to bypass security detection systems. | JSON, TXT, Adblock | Manually updated |
| **Tracking Parameters** | URL parameters used for tracking, including UTM and similar identifiers. | JSON, TXT | Manually updated |

---

## Compatible Tools

This blocklist works with most major ad blockers and security tools, including **AdGuard**, **AdGuard Home**, **Pi-hole**, **uBlock Origin**, **Brave** (aggressive mode), and **Adblock Plus**.

If you need a different type of format: **[Contact us](https://phishindex.com/contact)**. We are happy to include more formats if there is a need for it.

---

## License

The PhishIndex URL blocklist is released under the **MIT License**, allowing use for both personal and commercial projects. You're free to redistribute, modify, and relicense the data as needed as long as you comply with the license.

---

## Data Sources

Our malicious domain data comes from:
- Our own threat intelligence tools
- Destroylist - https://github.com/phishdestroy/destroylist
- PhishTank - https://phishtank.com (via https://github.com/Zaczero/pihole-phishtank)
- URLAbuse - https://urlabuse.com (CC BY 4.0)


We automatically process and refine this data to remove false positives and ensure proper formatting so we cannot always be fully sure if any modifications were made. Specifically regarding the URLabuse source, we automatically extract the URLs from the JSON formatting, remove the protocols (https://, http://, www.) and no other modifications are made. See [external_licenses.md](https://github.com/PhishIndex/phishindex-blocklist/blob/main/external_licenses.md) for the licenses of the external data sources where including a copy of the original license is required. 

---

## Support

- **General inquiries:** [phishindex.com/contact](https://phishindex.com/contact) (Report false positives / false negatives here for data categories other than malicious domains)
- **Report malicious domains or false positives:** [phishindex.com/report_url](https://phishindex.com/report_url) (Report false positives / false negatives for ONLY malicious domains here)
