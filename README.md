# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 446 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1441 | Hosts that connected within the last 3 days. |
| hosts-1w | 3616 | Hosts that connected within the last 7 days. |
| hosts-3w | 10250 | Hosts that connected within the last 21 days. |
| hosts-1m | 13760 | Hosts that connected within the last month. |
| hosts-3m | 21371 | Hosts that connected within the last 3 months. |
| users-1d | 1119 | Usernames used to connect within the last 24 hours. |
| users-3d | 1790 | Usernames used to connect within the last 3 days. |
| users-1w | 2692 | Usernames used to connect within the last 7 days. |
| users-3w | 18211 | Usernames used to connect within the last 21 days. |
| users-1m | 19620 | Usernames used to connect within the last month. |
| users-3m | 23327 | Usernames used to connect within the last 3 months. |
| passwords-1d | 13913 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 17317 | Passwords used to connect within the last 3 days. |
| passwords-1w | 45059 | Passwords used to connect within the last 7 days. |
| passwords-3w | 89856 | Passwords used to connect within the last 21 days. |
| passwords-1m | 110254 | Passwords used to connect within the last month. |
| passwords-3m | 141581 | Passwords used to connect within the last 3 months. |
| destinations-1d | 7 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 8 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 8 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 57 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 64 | Destinations of proxy attempts within the last month. |
| destinations-3m | 74 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 20 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 34 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 76 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 277 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 309 | Payloads execution attempts within the last month. |
| payloads-3m | 399 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 3 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 15 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 25 | New hosts that connected within the last month. |
| new-hosts-3m | 32 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 3 | New usernames used to connect within the last 7 days. |
| new-users-3w | 15 | New usernames used to connect within the last 21 days. |
| new-users-1m | 25 | New usernames used to connect within the last month. |
| new-users-3m | 32 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 295 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1472 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2300 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 29711 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 46164 | New passwords used to connect within the last month. |
| new-passwords-3m | 74825 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 3 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 15 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 24 | New payloads execution attempts within the last month. |
| new-payloads-3m | 31 | New payloads execution attempts within the last 3 months. |
