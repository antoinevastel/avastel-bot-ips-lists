# Avastel Proxy Bot IPs Lists

## News

The project is active again, the lists are updated daily!
For the moment, I expose only 3 proxy bot IPs lists:
- 1 day proxy bots IPs: [avastel-proxy-bot-ips-blocklist-1day.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-1day.txt)
- 5 days proxy bots IPs block list: [avastel-proxy-bot-ips-blocklist-5days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-5days.txt)
- 8 days proxy bots IPs blocklist: [avastel-proxy-bot-ips-blocklist-8days.txt](https://github.com/antoinevastel/avastel-bot-ips-lists/blob/master/avastel-proxy-bot-ips-blocklist-8days.txt)



## How to use these lists?

The 1 day proxy bots IPs **IS NOT** a block list. It is a sample of proxy IP addresses observed in the last 24 hours.
These IPs have been verified, which means I guarantee that they have been used as proxies within the last 24 hours.
However, these may be shared IP addresses used by human users and bots. 
You should not probably block these IPs since it may impact your users experience.
However, you can use it to build your own bot detection/fraud detection logic.

The 5 days and 8 days proxy bots IPs blocklists **ARE** blocklists. 
These two lists are updated daily and computed on proxy IPs observed in the last 5 and 8 days.
I only include IP ranges that have a high chance of being used by bots.
For each IP range, I include a confidence score.
A score of 1 means that it's perfectly safe to block this IP range, while a lower score means that it's more risky to block the whole range.

## Looking for more bot IPs data?
These proxy IP lists of this project contain only a sample of the proxy bot IPs I observe.
I created a curated database of bot proxy IP addresses, updated continuously.
Learn more about [the proxy detection database](https://deviceandbrowserinfo.com/product/proxies-ips).

The free plan enables you to get access to the latest 20K distinct proxy IPs, updated every 6 hours.

We also offer paid plans with a much larger number of proxy IPs, updated every 2 hours:
- Pro plan: 50K distinct IPs, updated every 2 hours;
- Business plan: all proxy IPs from the last 3 days, updated every 2 hours;
- Reseller plan: all proxy IPs from the last 7 days, updated every 2 hours;

