# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 809 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1668 | Hosts that connected within the last 3 days. |
| hosts-1w | 4275 | Hosts that connected within the last 7 days. |
| hosts-3w | 8998 | Hosts that connected within the last 21 days. |
| hosts-1m | 10995 | Hosts that connected within the last month. |
| hosts-3m | 23354 | Hosts that connected within the last 3 months. |
| users-1d | 969 | Usernames used to connect within the last 24 hours. |
| users-3d | 1458 | Usernames used to connect within the last 3 days. |
| users-1w | 2357 | Usernames used to connect within the last 7 days. |
| users-3w | 4590 | Usernames used to connect within the last 21 days. |
| users-1m | 5787 | Usernames used to connect within the last month. |
| users-3m | 14284 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8266 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 19714 | Passwords used to connect within the last 3 days. |
| passwords-1w | 28297 | Passwords used to connect within the last 7 days. |
| passwords-3w | 38415 | Passwords used to connect within the last 21 days. |
| passwords-1m | 45609 | Passwords used to connect within the last month. |
| passwords-3m | 122279 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 35 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 45 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 55 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 61 | Destinations of proxy attempts within the last month. |
| destinations-3m | 214 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 30 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 48 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 167 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 209 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 276 | Payloads execution attempts within the last month. |
| payloads-3m | 781 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 6 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 8 | New hosts that connected within the last month. |
| new-hosts-3m | 134 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 6 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 8 | New usernames used to connect within the last month. |
| new-users-3m | 134 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 469 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1478 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4323 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 7298 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10608 | New passwords used to connect within the last month. |
| new-passwords-3m | 61781 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 11 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 1 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 1 | New payloads execution attempts within the last month. |
| new-payloads-3m | 79 | New payloads execution attempts within the last 3 months. |
