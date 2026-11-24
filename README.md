# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 493 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1759 | Hosts that connected within the last 3 days. |
| hosts-1w | 3648 | Hosts that connected within the last 7 days. |
| hosts-3w | 8966 | Hosts that connected within the last 21 days. |
| hosts-1m | 12612 | Hosts that connected within the last month. |
| hosts-3m | 31753 | Hosts that connected within the last 3 months. |
| users-1d | 851 | Usernames used to connect within the last 24 hours. |
| users-3d | 1146 | Usernames used to connect within the last 3 days. |
| users-1w | 2127 | Usernames used to connect within the last 7 days. |
| users-3w | 3391 | Usernames used to connect within the last 21 days. |
| users-1m | 7016 | Usernames used to connect within the last month. |
| users-3m | 29748 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2258 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6776 | Passwords used to connect within the last 3 days. |
| passwords-1w | 19943 | Passwords used to connect within the last 7 days. |
| passwords-3w | 49269 | Passwords used to connect within the last 21 days. |
| passwords-1m | 60030 | Passwords used to connect within the last month. |
| passwords-3m | 147392 | Passwords used to connect within the last 3 months. |
| destinations-1d | 2 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 14 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 39 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 57 | Destinations of proxy attempts within the last month. |
| destinations-3m | 104 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 23 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 35 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 61 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 161 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 202 | Payloads execution attempts within the last month. |
| payloads-3m | 471 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 79 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 144 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 186 | New hosts that connected within the last month. |
| new-hosts-3m | 575 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 71 | New usernames used to connect within the last 7 days. |
| new-users-3w | 102 | New usernames used to connect within the last 21 days. |
| new-users-1m | 106 | New usernames used to connect within the last month. |
| new-users-3m | 176 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 35 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 278 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2422 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9148 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 13083 | New passwords used to connect within the last month. |
| new-passwords-3m | 70626 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 13 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 15 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 15 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 21 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 69 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 86 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 86 | New payloads execution attempts within the last month. |
| new-payloads-3m | 112 | New payloads execution attempts within the last 3 months. |
