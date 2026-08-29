# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 862 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1696 | Hosts that connected within the last 3 days. |
| hosts-1w | 2546 | Hosts that connected within the last 7 days. |
| hosts-3w | 5365 | Hosts that connected within the last 21 days. |
| hosts-1m | 6667 | Hosts that connected within the last month. |
| hosts-3m | 15172 | Hosts that connected within the last 3 months. |
| users-1d | 758 | Usernames used to connect within the last 24 hours. |
| users-3d | 1236 | Usernames used to connect within the last 3 days. |
| users-1w | 1659 | Usernames used to connect within the last 7 days. |
| users-3w | 3301 | Usernames used to connect within the last 21 days. |
| users-1m | 4586 | Usernames used to connect within the last month. |
| users-3m | 10097 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2969 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6636 | Passwords used to connect within the last 3 days. |
| passwords-1w | 13194 | Passwords used to connect within the last 7 days. |
| passwords-3w | 44200 | Passwords used to connect within the last 21 days. |
| passwords-1m | 49608 | Passwords used to connect within the last month. |
| passwords-3m | 92173 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 18 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 19 | Destinations of proxy attempts within the last month. |
| destinations-3m | 79 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 27 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 44 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 44 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 70 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 74 | Payloads execution attempts within the last month. |
| payloads-3m | 364 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 4 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 4 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 11 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 11 | New hosts that connected within the last month. |
| new-hosts-3m | 16 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 4 | New usernames used to connect within the last 3 days. |
| new-users-1w | 4 | New usernames used to connect within the last 7 days. |
| new-users-3w | 11 | New usernames used to connect within the last 21 days. |
| new-users-1m | 11 | New usernames used to connect within the last month. |
| new-users-3m | 16 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 543 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1586 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2988 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 23895 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 25055 | New passwords used to connect within the last month. |
| new-passwords-3m | 38941 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 2 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 2 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 3 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 3 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 3 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 4 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 4 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 11 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 11 | New payloads execution attempts within the last month. |
| new-payloads-3m | 15 | New payloads execution attempts within the last 3 months. |
