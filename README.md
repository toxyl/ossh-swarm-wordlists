# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 302 | Hosts that connected within the last 24 hours. |
| hosts-3d | 679 | Hosts that connected within the last 3 days. |
| hosts-1w | 2123 | Hosts that connected within the last 7 days. |
| hosts-3w | 7477 | Hosts that connected within the last 21 days. |
| hosts-1m | 10310 | Hosts that connected within the last month. |
| hosts-3m | 22249 | Hosts that connected within the last 3 months. |
| users-1d | 553 | Usernames used to connect within the last 24 hours. |
| users-3d | 854 | Usernames used to connect within the last 3 days. |
| users-1w | 2570 | Usernames used to connect within the last 7 days. |
| users-3w | 4481 | Usernames used to connect within the last 21 days. |
| users-1m | 5031 | Usernames used to connect within the last month. |
| users-3m | 9804 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1346 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 3249 | Passwords used to connect within the last 3 days. |
| passwords-1w | 15788 | Passwords used to connect within the last 7 days. |
| passwords-3w | 59085 | Passwords used to connect within the last 21 days. |
| passwords-1m | 65529 | Passwords used to connect within the last month. |
| passwords-3m | 120582 | Passwords used to connect within the last 3 months. |
| destinations-1d | 9 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 10 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 29 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 57 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 67 | Destinations of proxy attempts within the last month. |
| destinations-3m | 140 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 22 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 23 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 58 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 172 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 428 | Payloads execution attempts within the last month. |
| payloads-3m | 886 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 3 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 10 | New hosts that connected within the last month. |
| new-hosts-3m | 74 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 3 | New usernames used to connect within the last 21 days. |
| new-users-1m | 10 | New usernames used to connect within the last month. |
| new-users-3m | 74 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 213 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 341 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1723 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 7017 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 9754 | New passwords used to connect within the last month. |
| new-passwords-3m | 50877 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 63 | New payloads execution attempts within the last 3 months. |
