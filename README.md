# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 795 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2253 | Hosts that connected within the last 3 days. |
| hosts-1w | 3843 | Hosts that connected within the last 7 days. |
| hosts-3w | 8642 | Hosts that connected within the last 21 days. |
| hosts-1m | 10340 | Hosts that connected within the last month. |
| hosts-3m | 22060 | Hosts that connected within the last 3 months. |
| users-1d | 877 | Usernames used to connect within the last 24 hours. |
| users-3d | 1549 | Usernames used to connect within the last 3 days. |
| users-1w | 2109 | Usernames used to connect within the last 7 days. |
| users-3w | 3536 | Usernames used to connect within the last 21 days. |
| users-1m | 4525 | Usernames used to connect within the last month. |
| users-3m | 10089 | Usernames used to connect within the last 3 months. |
| passwords-1d | 16784 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 21315 | Passwords used to connect within the last 3 days. |
| passwords-1w | 51731 | Passwords used to connect within the last 7 days. |
| passwords-3w | 61352 | Passwords used to connect within the last 21 days. |
| passwords-1m | 64116 | Passwords used to connect within the last month. |
| passwords-3m | 119407 | Passwords used to connect within the last 3 months. |
| destinations-1d | 19 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 38 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 39 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 47 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 58 | Destinations of proxy attempts within the last month. |
| destinations-3m | 139 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 53 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 95 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 118 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 382 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 474 | Payloads execution attempts within the last month. |
| payloads-3m | 860 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 2 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 9 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 11 | New hosts that connected within the last month. |
| new-hosts-3m | 74 | New hosts that connected within the last 3 months. |
| new-users-1d | 2 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 9 | New usernames used to connect within the last 21 days. |
| new-users-1m | 11 | New usernames used to connect within the last month. |
| new-users-3m | 74 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 1818 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 2738 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 3186 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 7027 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 7990 | New passwords used to connect within the last month. |
| new-passwords-3m | 49390 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 6 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 8 | New payloads execution attempts within the last month. |
| new-payloads-3m | 61 | New payloads execution attempts within the last 3 months. |
