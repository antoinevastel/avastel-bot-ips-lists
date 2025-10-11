# Avastel Proxy Bot IPs Lists

> ## 🚨 News  
> You can now **search and look up proxy IP addresses for free** using the new [Proxy IP Lookup UI](https://deviceandbrowserinfo.com/data/ips/proxies/search).  
> It provides **manual access to the full 15M+ proxy IP database** collected over the last 30 days — with **no quota or login required** for human users.  
> Use it to quickly check if an IP was recently active as a proxy, or to explore proxy infrastructure patterns interactively.


## Overview

This repository provides free, regularly updated lists of IP addresses associated with proxy infrastructure commonly used by bots.  
All lists are updated **daily**.

Three different lists are available:

- **1 day proxy bot IPs**: [avastel-proxy-bot-ips-1day.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-1day.txt)
- **5 days proxy bot IPs blocklist**: [avastel-proxy-bot-ips-blocklist-5days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-5days.txt)
- **8 days proxy bot IPs blocklist**: [avastel-proxy-bot-ips-blocklist-8days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-8days.txt)

Each list is designed to help developers, fraud analysts, and security researchers detect and mitigate automated traffic more effectively.


## How to use these lists
### 1 day proxy bot IPs

- A **daily sample** of proxy IPs observed in the last 24 hours.
- All IPs are **verified** as having been used as proxies.
- **Caution**: These may be shared IPs and should not be directly blocked.
- Recommended usage: **risk scoring**, **secondary fraud signals**, or **bot behavior enrichment**.

### 5 days and 8 days proxy bot IPs blocklists

- **Blocklists** based on IPs observed over the past 5 and 8 days, respectively.
- IPs are aggregated into **ranges** with an associated **confidence score**:
  - **Score 1**: very high confidence, safe to block.
  - **Lower scores**: potential for human users mixed in (use with caution).
- Recommended usage: **direct blocking** based on confidence scores or **layered detection strategies**.


## About the data

The proxy IPs included in these lists come from my own detection systems.  
I do **not rely on any third-party datasets**.

Data sources include:
- Residential proxies
- Data center proxies
- ISP proxies
- Free proxy servers

All IPs are **independently verified** to ensure they were actively functioning as proxies at the time of collection.


## Access to a larger proxy IP database

This open source project offers a reliable starting point, covering **more than 200,000 IPs**, updated daily.

For teams or businesses needing:
- **More frequent updates** (every 2 hours),
- **Access to a broader proxy dataset** (over 15 million active proxy IPs),
- **Extended history** (up to 30 days of proxy activity),

you can learn more about the larger [proxy detection database](https://deviceandbrowserinfo.com/product/proxies-ips).

A **free plan** is available, and access to the full database can be arranged for evaluation on request.


## License

The data in this repository is released under the [MIT License](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/LICENSE).

You are free to use it in any project, including commercial projects.  
If you find the project useful, adding a link back to this repository is appreciated.


