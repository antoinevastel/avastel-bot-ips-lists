# Avastel proxy bot IPs lists

## 📘 Overview

This repository provides free, regularly updated lists of IP addresses associated with proxy infrastructure used by bots.  
All lists are updated daily.

Available lists:

- 📅 **1 day proxy bot IPs**  
  Daily sample of **500k verified proxy IPs** observed in the last 24 hours.  
  [avastel-proxy-bot-ips-1day.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-1day.txt)

- 🛑 **5 days proxy bot IPs blocklist**  
  [avastel-proxy-bot-ips-blocklist-5days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-5days.txt)

- 🛑 **8 days proxy bot IPs blocklist**  
  [avastel-proxy-bot-ips-blocklist-8days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-8days.txt)

These lists help developers, fraud analysts, and security teams detect and mitigate automated/bot traffic.

## 🔍 Check if an IP is a proxy

You can manually search any IP using the **Proxy IP Lookup** page:  
https://deviceandbrowserinfo.com/data/ips/proxies/search

This tool provides access to the full dataset of **about 25M proxy IPs** active in the last 30 days.  
Useful for confirming recent proxy activity or exploring proxy patterns interactively.

## 🧭 How to use these lists

### 📅 1 day proxy bot IPs

- Contains **500k proxy IPs** observed in the last 24 hours.  
- All IPs are independently verified as proxies.  
- These IPs are often shared, so direct blocking is not recommended.  
- Best for **risk scoring**, **behavioral enrichment**, and **secondary signals**.

### 🛡️ 5 days and 8 days proxy bot blocklists

- Aggregated blocklists built from proxies observed over 5 or 8 days.  
- IPs are grouped into ranges with a confidence score:  
  - **Score 1**: very high confidence, appropriate for blocking  
  - Lower scores: may include mixed traffic  
- Best for **direct blocking**, **rate limiting**, or **layered detection strategies**.

## 📡 About the data

All proxy IPs come from my own detection systems.  
No third-party datasets are used.

The lists include proxies from:

- Residential proxy networks  
- Data center proxy providers  
- ISP proxy infrastructure  
- Free or public proxy servers  

Each IP is independently validated to confirm it acted as a proxy at the time of collection.

## 📂 Access to a larger proxy IP database

This repository provides more than 500,000 verified proxy IPs updated daily.

For teams that need deeper coverage:

- Updates every 2 hours  
  - **About 25 million** active proxy IPs  
  - Up to 30 days of proxy activity history  

Learn more:  
https://deviceandbrowserinfo.com/product/proxies-ips

A free plan is available. Full access can be provided for evaluation.

## 📄 License

The data is released under the MIT License.

You can use it in any project, including commercial applications.  
If the project is helpful, linking back to this repository is appreciated.
