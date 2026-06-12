# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 354 | Hosts that connected within the last 24 hours. |
| hosts-3d | 905 | Hosts that connected within the last 3 days. |
| hosts-1w | 1566 | Hosts that connected within the last 7 days. |
| hosts-3w | 6721 | Hosts that connected within the last 21 days. |
| hosts-1m | 10114 | Hosts that connected within the last month. |
| hosts-3m | 21248 | Hosts that connected within the last 3 months. |
| users-1d | 675 | Usernames used to connect within the last 24 hours. |
| users-3d | 1154 | Usernames used to connect within the last 3 days. |
| users-1w | 1630 | Usernames used to connect within the last 7 days. |
| users-3w | 4308 | Usernames used to connect within the last 21 days. |
| users-1m | 5167 | Usernames used to connect within the last month. |
| users-3m | 9834 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1567 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6961 | Passwords used to connect within the last 3 days. |
| passwords-1w | 9110 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57809 | Passwords used to connect within the last 21 days. |
| passwords-1m | 65650 | Passwords used to connect within the last month. |
| passwords-3m | 119306 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 3 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 11 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 57 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 64 | Destinations of proxy attempts within the last month. |
| destinations-3m | 136 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 24 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 27 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 31 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 164 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 419 | Payloads execution attempts within the last month. |
| payloads-3m | 812 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 3 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 10 | New hosts that connected within the last month. |
| new-hosts-3m | 69 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 3 | New usernames used to connect within the last 21 days. |
| new-users-1m | 10 | New usernames used to connect within the last month. |
| new-users-3m | 69 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 165 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 601 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1026 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 6675 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10024 | New passwords used to connect within the last month. |
| new-passwords-3m | 48996 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 62 | New payloads execution attempts within the last 3 months. |
