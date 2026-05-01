# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 420 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1099 | Hosts that connected within the last 3 days. |
| hosts-1w | 2520 | Hosts that connected within the last 7 days. |
| hosts-3w | 5981 | Hosts that connected within the last 21 days. |
| hosts-1m | 8267 | Hosts that connected within the last month. |
| hosts-3m | 24503 | Hosts that connected within the last 3 months. |
| users-1d | 669 | Usernames used to connect within the last 24 hours. |
| users-3d | 1164 | Usernames used to connect within the last 3 days. |
| users-1w | 1643 | Usernames used to connect within the last 7 days. |
| users-3w | 2698 | Usernames used to connect within the last 21 days. |
| users-1m | 3273 | Usernames used to connect within the last month. |
| users-3m | 13721 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2176 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 26831 | Passwords used to connect within the last 3 days. |
| passwords-1w | 30435 | Passwords used to connect within the last 7 days. |
| passwords-3w | 48821 | Passwords used to connect within the last 21 days. |
| passwords-1m | 68399 | Passwords used to connect within the last month. |
| passwords-3m | 123861 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 5 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 10 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 14 | Destinations of proxy attempts within the last month. |
| destinations-3m | 196 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 27 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 34 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 85 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 135 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 148 | Payloads execution attempts within the last month. |
| payloads-3m | 704 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 3 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 5 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 12 | New hosts that connected within the last month. |
| new-hosts-3m | 80 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 3 | New usernames used to connect within the last 3 days. |
| new-users-1w | 5 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 12 | New usernames used to connect within the last month. |
| new-users-3m | 80 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 137 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 572 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1612 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 8060 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 12228 | New passwords used to connect within the last month. |
| new-passwords-3m | 59343 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 1 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 2 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 3 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 5 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 8 | New payloads execution attempts within the last month. |
| new-payloads-3m | 51 | New payloads execution attempts within the last 3 months. |
