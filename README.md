# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 634 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1783 | Hosts that connected within the last 3 days. |
| hosts-1w | 3641 | Hosts that connected within the last 7 days. |
| hosts-3w | 10552 | Hosts that connected within the last 21 days. |
| hosts-1m | 12839 | Hosts that connected within the last month. |
| hosts-3m | 20286 | Hosts that connected within the last 3 months. |
| users-1d | 890 | Usernames used to connect within the last 24 hours. |
| users-3d | 2003 | Usernames used to connect within the last 3 days. |
| users-1w | 3706 | Usernames used to connect within the last 7 days. |
| users-3w | 18856 | Usernames used to connect within the last 21 days. |
| users-1m | 19204 | Usernames used to connect within the last month. |
| users-3m | 23055 | Usernames used to connect within the last 3 months. |
| passwords-1d | 31773 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 36097 | Passwords used to connect within the last 3 days. |
| passwords-1w | 45695 | Passwords used to connect within the last 7 days. |
| passwords-3w | 102026 | Passwords used to connect within the last 21 days. |
| passwords-1m | 112508 | Passwords used to connect within the last month. |
| passwords-3m | 139589 | Passwords used to connect within the last 3 months. |
| destinations-1d | 0 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 2 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 29 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 56 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 62 | Destinations of proxy attempts within the last month. |
| destinations-3m | 72 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 28 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 36 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 50 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 263 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 271 | Payloads execution attempts within the last month. |
| payloads-3m | 475 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 20 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 27 | New hosts that connected within the last month. |
| new-hosts-3m | 33 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 20 | New usernames used to connect within the last 21 days. |
| new-users-1m | 27 | New usernames used to connect within the last month. |
| new-users-3m | 33 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 171 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 344 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2174 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 40799 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 48642 | New passwords used to connect within the last month. |
| new-passwords-3m | 73803 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 1 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 4 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 7 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 19 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 26 | New payloads execution attempts within the last month. |
| new-payloads-3m | 32 | New payloads execution attempts within the last 3 months. |
