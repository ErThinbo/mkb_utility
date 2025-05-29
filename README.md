📂 scripts/ - Subdomain Enumeration Tools

This folder contains four Bash scripts designed to collect subdomains of a given domain using publicly available OSINT sources. Each script requires a domain as an argument and saves the results in a corresponding .txt file using anew to avoid duplicates.

🔹 get_subdomains.sh
Fetches subdomains from crt.sh, a certificate transparency log search engine. It extracts subdomains based on SSL certificate records.

🔹 alienvault_subs.sh
Uses the AlienVault OTX API to perform passive DNS lookups and gather subdomains seen by AlienVault sensors.

🔹 urlscan_subs.sh
Queries urlscan.io for domains found in historical scans related to the target domain, extracting discovered subdomains.

🔹 webarchive_subs.sh
Pulls archived URLs from the Wayback Machine (web.archive.org) and extracts subdomains based on historical data.


