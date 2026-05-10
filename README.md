# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 624 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1704 | Hosts that connected within the last 3 days. |
| hosts-1w | 2857 | Hosts that connected within the last 7 days. |
| hosts-3w | 6227 | Hosts that connected within the last 21 days. |
| hosts-1m | 8081 | Hosts that connected within the last month. |
| hosts-3m | 23092 | Hosts that connected within the last 3 months. |
| users-1d | 780 | Usernames used to connect within the last 24 hours. |
| users-3d | 1650 | Usernames used to connect within the last 3 days. |
| users-1w | 1957 | Usernames used to connect within the last 7 days. |
| users-3w | 3141 | Usernames used to connect within the last 21 days. |
| users-1m | 3646 | Usernames used to connect within the last month. |
| users-3m | 11408 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1855 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6166 | Passwords used to connect within the last 3 days. |
| passwords-1w | 14514 | Passwords used to connect within the last 7 days. |
| passwords-3w | 44871 | Passwords used to connect within the last 21 days. |
| passwords-1m | 52206 | Passwords used to connect within the last month. |
| passwords-3m | 116038 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 11 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 18 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 19 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 22 | Destinations of proxy attempts within the last month. |
| destinations-3m | 119 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 44 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 57 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 110 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 163 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 200 | Payloads execution attempts within the last month. |
| payloads-3m | 640 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 8 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 9 | New hosts that connected within the last month. |
| new-hosts-3m | 67 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 8 | New usernames used to connect within the last 21 days. |
| new-users-1m | 9 | New usernames used to connect within the last month. |
| new-users-3m | 67 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 54 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 354 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 765 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4295 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 9058 | New passwords used to connect within the last month. |
| new-passwords-3m | 50479 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 6 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 48 | New payloads execution attempts within the last 3 months. |
