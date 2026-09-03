# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 1409 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2056 | Hosts that connected within the last 3 days. |
| hosts-1w | 3615 | Hosts that connected within the last 7 days. |
| hosts-3w | 6324 | Hosts that connected within the last 21 days. |
| hosts-1m | 8162 | Hosts that connected within the last month. |
| hosts-3m | 15255 | Hosts that connected within the last 3 months. |
| users-1d | 1632 | Usernames used to connect within the last 24 hours. |
| users-3d | 2338 | Usernames used to connect within the last 3 days. |
| users-1w | 2998 | Usernames used to connect within the last 7 days. |
| users-3w | 4233 | Usernames used to connect within the last 21 days. |
| users-1m | 5162 | Usernames used to connect within the last month. |
| users-3m | 10473 | Usernames used to connect within the last 3 months. |
| passwords-1d | 12286 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 19260 | Passwords used to connect within the last 3 days. |
| passwords-1w | 26813 | Passwords used to connect within the last 7 days. |
| passwords-3w | 59124 | Passwords used to connect within the last 21 days. |
| passwords-1m | 65027 | Passwords used to connect within the last month. |
| passwords-3m | 96164 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 2 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 6 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 17 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 18 | Destinations of proxy attempts within the last month. |
| destinations-3m | 40 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 14 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 44 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 56 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 70 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 73 | Payloads execution attempts within the last month. |
| payloads-3m | 278 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 2 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 4 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 5 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 14 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 15 | New hosts that connected within the last month. |
| new-hosts-3m | 17 | New hosts that connected within the last 3 months. |
| new-users-1d | 2 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 4 | New usernames used to connect within the last 3 days. |
| new-users-1w | 5 | New usernames used to connect within the last 7 days. |
| new-users-3w | 14 | New usernames used to connect within the last 21 days. |
| new-users-1m | 15 | New usernames used to connect within the last month. |
| new-users-3m | 17 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 5252 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 8054 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 10651 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 32731 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 34405 | New passwords used to connect within the last month. |
| new-passwords-3m | 44145 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 1 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 3 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 4 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 6 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 2 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 3 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 4 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 13 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 14 | New payloads execution attempts within the last month. |
| new-payloads-3m | 16 | New payloads execution attempts within the last 3 months. |
