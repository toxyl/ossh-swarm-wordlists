# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 678 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1347 | Hosts that connected within the last 3 days. |
| hosts-1w | 2329 | Hosts that connected within the last 7 days. |
| hosts-3w | 5878 | Hosts that connected within the last 21 days. |
| hosts-1m | 8487 | Hosts that connected within the last month. |
| hosts-3m | 24867 | Hosts that connected within the last 3 months. |
| users-1d | 662 | Usernames used to connect within the last 24 hours. |
| users-3d | 980 | Usernames used to connect within the last 3 days. |
| users-1w | 1473 | Usernames used to connect within the last 7 days. |
| users-3w | 2463 | Usernames used to connect within the last 21 days. |
| users-1m | 5564 | Usernames used to connect within the last month. |
| users-3m | 15254 | Usernames used to connect within the last 3 months. |
| passwords-1d | 5831 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 15212 | Passwords used to connect within the last 3 days. |
| passwords-1w | 35027 | Passwords used to connect within the last 7 days. |
| passwords-3w | 48651 | Passwords used to connect within the last 21 days. |
| passwords-1m | 85374 | Passwords used to connect within the last month. |
| passwords-3m | 125148 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 12 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 47 | Destinations of proxy attempts within the last month. |
| destinations-3m | 194 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 64 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 69 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 81 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 133 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 207 | Payloads execution attempts within the last month. |
| payloads-3m | 707 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 3 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 43 | New hosts that connected within the last month. |
| new-hosts-3m | 75 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 3 | New usernames used to connect within the last 21 days. |
| new-users-1m | 43 | New usernames used to connect within the last month. |
| new-users-3m | 75 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 453 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1258 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2115 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 8727 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 29877 | New passwords used to connect within the last month. |
| new-passwords-3m | 61206 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 3 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 30 | New payloads execution attempts within the last month. |
| new-payloads-3m | 48 | New payloads execution attempts within the last 3 months. |
