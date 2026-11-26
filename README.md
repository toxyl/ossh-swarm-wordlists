# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 753 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1535 | Hosts that connected within the last 3 days. |
| hosts-1w | 3595 | Hosts that connected within the last 7 days. |
| hosts-3w | 8955 | Hosts that connected within the last 21 days. |
| hosts-1m | 12798 | Hosts that connected within the last month. |
| hosts-3m | 32163 | Hosts that connected within the last 3 months. |
| users-1d | 1040 | Usernames used to connect within the last 24 hours. |
| users-3d | 1548 | Usernames used to connect within the last 3 days. |
| users-1w | 2274 | Usernames used to connect within the last 7 days. |
| users-3w | 3631 | Usernames used to connect within the last 21 days. |
| users-1m | 6516 | Usernames used to connect within the last month. |
| users-3m | 30058 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8115 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 11037 | Passwords used to connect within the last 3 days. |
| passwords-1w | 13582 | Passwords used to connect within the last 7 days. |
| passwords-3w | 50414 | Passwords used to connect within the last 21 days. |
| passwords-1m | 60872 | Passwords used to connect within the last month. |
| passwords-3m | 148825 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 12 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 39 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 57 | Destinations of proxy attempts within the last month. |
| destinations-3m | 105 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 57 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 64 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 90 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 165 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 201 | Payloads execution attempts within the last month. |
| payloads-3m | 476 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 23 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 149 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 174 | New hosts that connected within the last month. |
| new-hosts-3m | 581 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 18 | New usernames used to connect within the last 7 days. |
| new-users-3w | 105 | New usernames used to connect within the last 21 days. |
| new-users-1m | 109 | New usernames used to connect within the last month. |
| new-users-3m | 179 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 926 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1328 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2037 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9597 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 13523 | New passwords used to connect within the last month. |
| new-passwords-3m | 71400 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 4 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 15 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 15 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 21 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 17 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 87 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 87 | New payloads execution attempts within the last month. |
| new-payloads-3m | 113 | New payloads execution attempts within the last 3 months. |
