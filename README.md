# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 770 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1696 | Hosts that connected within the last 3 days. |
| hosts-1w | 3329 | Hosts that connected within the last 7 days. |
| hosts-3w | 8630 | Hosts that connected within the last 21 days. |
| hosts-1m | 11846 | Hosts that connected within the last month. |
| hosts-3m | 27226 | Hosts that connected within the last 3 months. |
| users-1d | 2578 | Usernames used to connect within the last 24 hours. |
| users-3d | 3854 | Usernames used to connect within the last 3 days. |
| users-1w | 5201 | Usernames used to connect within the last 7 days. |
| users-3w | 8511 | Usernames used to connect within the last 21 days. |
| users-1m | 13433 | Usernames used to connect within the last month. |
| users-3m | 29019 | Usernames used to connect within the last 3 months. |
| passwords-1d | 5528 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 7819 | Passwords used to connect within the last 3 days. |
| passwords-1w | 30241 | Passwords used to connect within the last 7 days. |
| passwords-3w | 52465 | Passwords used to connect within the last 21 days. |
| passwords-1m | 66091 | Passwords used to connect within the last month. |
| passwords-3m | 153765 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 10 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 31 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 38 | Destinations of proxy attempts within the last month. |
| destinations-3m | 77 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 34 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 81 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 85 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 105 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 127 | Payloads execution attempts within the last month. |
| payloads-3m | 371 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 1 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 1 | New hosts that connected within the last month. |
| new-hosts-3m | 34 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 1 | New usernames used to connect within the last 21 days. |
| new-users-1m | 1 | New usernames used to connect within the last month. |
| new-users-3m | 34 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 640 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1487 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2498 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 5350 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10587 | New passwords used to connect within the last month. |
| new-passwords-3m | 82168 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 1 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 1 | New payloads execution attempts within the last month. |
| new-payloads-3m | 33 | New payloads execution attempts within the last 3 months. |
