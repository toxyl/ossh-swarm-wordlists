# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 576 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1189 | Hosts that connected within the last 3 days. |
| hosts-1w | 2677 | Hosts that connected within the last 7 days. |
| hosts-3w | 8172 | Hosts that connected within the last 21 days. |
| hosts-1m | 10660 | Hosts that connected within the last month. |
| hosts-3m | 23866 | Hosts that connected within the last 3 months. |
| users-1d | 2940 | Usernames used to connect within the last 24 hours. |
| users-3d | 3502 | Usernames used to connect within the last 3 days. |
| users-1w | 3951 | Usernames used to connect within the last 7 days. |
| users-3w | 6299 | Usernames used to connect within the last 21 days. |
| users-1m | 6658 | Usernames used to connect within the last month. |
| users-3m | 15349 | Usernames used to connect within the last 3 months. |
| passwords-1d | 18610 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 26278 | Passwords used to connect within the last 3 days. |
| passwords-1w | 49078 | Passwords used to connect within the last 7 days. |
| passwords-3w | 60987 | Passwords used to connect within the last 21 days. |
| passwords-1m | 63692 | Passwords used to connect within the last month. |
| passwords-3m | 107044 | Passwords used to connect within the last 3 months. |
| destinations-1d | 16 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 41 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 41 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 83 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 86 | Destinations of proxy attempts within the last month. |
| destinations-3m | 219 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 44 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 100 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 210 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 334 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 356 | Payloads execution attempts within the last month. |
| payloads-3m | 844 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 16 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 16 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 24 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 31 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 31 | New hosts that connected within the last month. |
| new-hosts-3m | 60 | New hosts that connected within the last 3 months. |
| new-users-1d | 16 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 16 | New usernames used to connect within the last 3 days. |
| new-users-1w | 24 | New usernames used to connect within the last 7 days. |
| new-users-3w | 31 | New usernames used to connect within the last 21 days. |
| new-users-1m | 31 | New usernames used to connect within the last month. |
| new-users-3m | 60 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 7377 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 8003 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 10171 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 17209 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 18295 | New passwords used to connect within the last month. |
| new-passwords-3m | 47414 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 1 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 3 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 3 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 3 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 5 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 7 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 7 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 15 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 16 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 16 | New payloads execution attempts within the last month. |
| new-payloads-3m | 34 | New payloads execution attempts within the last 3 months. |
