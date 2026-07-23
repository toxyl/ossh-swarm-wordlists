# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 396 | Hosts that connected within the last 24 hours. |
| hosts-3d | 919 | Hosts that connected within the last 3 days. |
| hosts-1w | 1637 | Hosts that connected within the last 7 days. |
| hosts-3w | 3903 | Hosts that connected within the last 21 days. |
| hosts-1m | 5217 | Hosts that connected within the last month. |
| hosts-3m | 17300 | Hosts that connected within the last 3 months. |
| users-1d | 1189 | Usernames used to connect within the last 24 hours. |
| users-3d | 2413 | Usernames used to connect within the last 3 days. |
| users-1w | 3332 | Usernames used to connect within the last 7 days. |
| users-3w | 4924 | Usernames used to connect within the last 21 days. |
| users-1m | 6179 | Usernames used to connect within the last month. |
| users-3m | 10419 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3166 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 5537 | Passwords used to connect within the last 3 days. |
| passwords-1w | 7941 | Passwords used to connect within the last 7 days. |
| passwords-3w | 23585 | Passwords used to connect within the last 21 days. |
| passwords-1m | 31228 | Passwords used to connect within the last month. |
| passwords-3m | 83203 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 14 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 16 | Destinations of proxy attempts within the last month. |
| destinations-3m | 88 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 34 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 51 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 137 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 233 | Payloads execution attempts within the last month. |
| payloads-3m | 696 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 0 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 2 | New hosts that connected within the last month. |
| new-hosts-3m | 19 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 0 | New usernames used to connect within the last 21 days. |
| new-users-1m | 2 | New usernames used to connect within the last month. |
| new-users-3m | 19 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 240 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 697 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1420 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 3178 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 5502 | New passwords used to connect within the last month. |
| new-passwords-3m | 20758 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 2 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 0 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 2 | New payloads execution attempts within the last month. |
| new-payloads-3m | 17 | New payloads execution attempts within the last 3 months. |
