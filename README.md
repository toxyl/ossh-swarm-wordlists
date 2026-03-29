# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 519 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1535 | Hosts that connected within the last 3 days. |
| hosts-1w | 2601 | Hosts that connected within the last 7 days. |
| hosts-3w | 8157 | Hosts that connected within the last 21 days. |
| hosts-1m | 10596 | Hosts that connected within the last month. |
| hosts-3m | 24559 | Hosts that connected within the last 3 months. |
| users-1d | 692 | Usernames used to connect within the last 24 hours. |
| users-3d | 1026 | Usernames used to connect within the last 3 days. |
| users-1w | 4491 | Usernames used to connect within the last 7 days. |
| users-3w | 6978 | Usernames used to connect within the last 21 days. |
| users-1m | 7398 | Usernames used to connect within the last month. |
| users-3m | 16040 | Usernames used to connect within the last 3 months. |
| passwords-1d | 15935 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 23248 | Passwords used to connect within the last 3 days. |
| passwords-1w | 45264 | Passwords used to connect within the last 7 days. |
| passwords-3w | 75214 | Passwords used to connect within the last 21 days. |
| passwords-1m | 77498 | Passwords used to connect within the last month. |
| passwords-3m | 119533 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 19 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 49 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 85 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 91 | Destinations of proxy attempts within the last month. |
| destinations-3m | 225 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 25 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 44 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 117 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 341 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 357 | Payloads execution attempts within the last month. |
| payloads-3m | 861 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 4 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 7 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 31 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 45 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 46 | New hosts that connected within the last month. |
| new-hosts-3m | 75 | New hosts that connected within the last 3 months. |
| new-users-1d | 4 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 7 | New usernames used to connect within the last 3 days. |
| new-users-1w | 31 | New usernames used to connect within the last 7 days. |
| new-users-3w | 45 | New usernames used to connect within the last 21 days. |
| new-users-1m | 46 | New usernames used to connect within the last month. |
| new-users-3m | 75 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 5657 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 6603 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 17007 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 25470 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 26684 | New passwords used to connect within the last month. |
| new-passwords-3m | 56417 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 2 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 4 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 4 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 3 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 5 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 19 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 27 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 28 | New payloads execution attempts within the last month. |
| new-payloads-3m | 46 | New payloads execution attempts within the last 3 months. |
