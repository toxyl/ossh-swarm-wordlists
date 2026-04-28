# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 435 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1284 | Hosts that connected within the last 3 days. |
| hosts-1w | 2682 | Hosts that connected within the last 7 days. |
| hosts-3w | 5965 | Hosts that connected within the last 21 days. |
| hosts-1m | 8456 | Hosts that connected within the last month. |
| hosts-3m | 24567 | Hosts that connected within the last 3 months. |
| users-1d | 526 | Usernames used to connect within the last 24 hours. |
| users-3d | 1028 | Usernames used to connect within the last 3 days. |
| users-1w | 1511 | Usernames used to connect within the last 7 days. |
| users-3w | 2442 | Usernames used to connect within the last 21 days. |
| users-1m | 3037 | Usernames used to connect within the last month. |
| users-3m | 13846 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4623 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 8370 | Passwords used to connect within the last 3 days. |
| passwords-1w | 21997 | Passwords used to connect within the last 7 days. |
| passwords-3w | 47103 | Passwords used to connect within the last 21 days. |
| passwords-1m | 71174 | Passwords used to connect within the last month. |
| passwords-3m | 124462 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 9 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 29 | Destinations of proxy attempts within the last month. |
| destinations-3m | 195 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 60 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 80 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 86 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 132 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 180 | Payloads execution attempts within the last month. |
| payloads-3m | 704 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 3 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 4 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 18 | New hosts that connected within the last month. |
| new-hosts-3m | 77 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 3 | New usernames used to connect within the last 7 days. |
| new-users-3w | 4 | New usernames used to connect within the last 21 days. |
| new-users-1m | 18 | New usernames used to connect within the last month. |
| new-users-3m | 77 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 158 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 805 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2298 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 8103 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 20195 | New passwords used to connect within the last month. |
| new-passwords-3m | 59902 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 3 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 4 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 14 | New payloads execution attempts within the last month. |
| new-payloads-3m | 50 | New payloads execution attempts within the last 3 months. |
