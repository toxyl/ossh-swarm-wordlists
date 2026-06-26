# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 363 | Hosts that connected within the last 24 hours. |
| hosts-3d | 870 | Hosts that connected within the last 3 days. |
| hosts-1w | 1620 | Hosts that connected within the last 7 days. |
| hosts-3w | 3936 | Hosts that connected within the last 21 days. |
| hosts-1m | 7547 | Hosts that connected within the last month. |
| hosts-3m | 19406 | Hosts that connected within the last 3 months. |
| users-1d | 576 | Usernames used to connect within the last 24 hours. |
| users-3d | 1046 | Usernames used to connect within the last 3 days. |
| users-1w | 1849 | Usernames used to connect within the last 7 days. |
| users-3w | 3673 | Usernames used to connect within the last 21 days. |
| users-1m | 5347 | Usernames used to connect within the last month. |
| users-3m | 8323 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1557 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 4091 | Passwords used to connect within the last 3 days. |
| passwords-1w | 6749 | Passwords used to connect within the last 7 days. |
| passwords-3w | 17216 | Passwords used to connect within the last 21 days. |
| passwords-1m | 53605 | Passwords used to connect within the last month. |
| passwords-3m | 102758 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 1 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 4 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 18 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 63 | Destinations of proxy attempts within the last month. |
| destinations-3m | 100 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 19 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 133 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 144 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 167 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 277 | Payloads execution attempts within the last month. |
| payloads-3m | 731 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 2 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 5 | New hosts that connected within the last month. |
| new-hosts-3m | 38 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 2 | New usernames used to connect within the last 21 days. |
| new-users-1m | 5 | New usernames used to connect within the last month. |
| new-users-3m | 38 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 351 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 829 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1441 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 3748 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 9097 | New passwords used to connect within the last month. |
| new-passwords-3m | 35733 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 3 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 4 | New payloads execution attempts within the last month. |
| new-payloads-3m | 35 | New payloads execution attempts within the last 3 months. |
