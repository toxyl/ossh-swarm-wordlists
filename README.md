# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 646 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1652 | Hosts that connected within the last 3 days. |
| hosts-1w | 3525 | Hosts that connected within the last 7 days. |
| hosts-3w | 9084 | Hosts that connected within the last 21 days. |
| hosts-1m | 12512 | Hosts that connected within the last month. |
| hosts-3m | 31374 | Hosts that connected within the last 3 months. |
| users-1d | 1164 | Usernames used to connect within the last 24 hours. |
| users-3d | 1732 | Usernames used to connect within the last 3 days. |
| users-1w | 2239 | Usernames used to connect within the last 7 days. |
| users-3w | 3882 | Usernames used to connect within the last 21 days. |
| users-1m | 7662 | Usernames used to connect within the last month. |
| users-3m | 29802 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4261 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 8669 | Passwords used to connect within the last 3 days. |
| passwords-1w | 20439 | Passwords used to connect within the last 7 days. |
| passwords-3w | 55121 | Passwords used to connect within the last 21 days. |
| passwords-1m | 61170 | Passwords used to connect within the last month. |
| passwords-3m | 151894 | Passwords used to connect within the last 3 months. |
| destinations-1d | 5 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 13 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 32 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 46 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 58 | Destinations of proxy attempts within the last month. |
| destinations-3m | 103 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 35 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 53 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 69 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 166 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 198 | Payloads execution attempts within the last month. |
| payloads-3m | 465 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 7 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 32 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 79 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 139 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 188 | New hosts that connected within the last month. |
| new-hosts-3m | 571 | New hosts that connected within the last 3 months. |
| new-users-1d | 7 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 32 | New usernames used to connect within the last 3 days. |
| new-users-1w | 77 | New usernames used to connect within the last 7 days. |
| new-users-3w | 104 | New usernames used to connect within the last 21 days. |
| new-users-1m | 106 | New usernames used to connect within the last month. |
| new-users-3m | 179 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 261 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 929 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2805 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10133 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 13697 | New passwords used to connect within the last month. |
| new-passwords-3m | 73847 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 2 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 5 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 14 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 15 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 15 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 22 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 7 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 31 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 75 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 86 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 86 | New payloads execution attempts within the last month. |
| new-payloads-3m | 114 | New payloads execution attempts within the last 3 months. |
