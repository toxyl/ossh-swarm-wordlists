# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 237 | Hosts that connected within the last 24 hours. |
| hosts-3d | 634 | Hosts that connected within the last 3 days. |
| hosts-1w | 1134 | Hosts that connected within the last 7 days. |
| hosts-3w | 3356 | Hosts that connected within the last 21 days. |
| hosts-1m | 4824 | Hosts that connected within the last month. |
| hosts-3m | 16517 | Hosts that connected within the last 3 months. |
| users-1d | 732 | Usernames used to connect within the last 24 hours. |
| users-3d | 1545 | Usernames used to connect within the last 3 days. |
| users-1w | 2431 | Usernames used to connect within the last 7 days. |
| users-3w | 4596 | Usernames used to connect within the last 21 days. |
| users-1m | 5632 | Usernames used to connect within the last month. |
| users-3m | 10405 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1231 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 2915 | Passwords used to connect within the last 3 days. |
| passwords-1w | 6658 | Passwords used to connect within the last 7 days. |
| passwords-3w | 18307 | Passwords used to connect within the last 21 days. |
| passwords-1m | 27523 | Passwords used to connect within the last month. |
| passwords-3m | 80675 | Passwords used to connect within the last 3 months. |
| destinations-1d | 0 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 3 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 3 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 7 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 14 | Destinations of proxy attempts within the last month. |
| destinations-3m | 87 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 10 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 30 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 30 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 101 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 138 | Payloads execution attempts within the last month. |
| payloads-3m | 683 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 0 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 0 | New hosts that connected within the last month. |
| new-hosts-3m | 14 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 0 | New usernames used to connect within the last 21 days. |
| new-users-1m | 0 | New usernames used to connect within the last month. |
| new-users-3m | 14 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 117 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 258 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 509 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 2653 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 4103 | New passwords used to connect within the last month. |
| new-passwords-3m | 19424 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 1 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 0 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 0 | New payloads execution attempts within the last month. |
| new-payloads-3m | 13 | New payloads execution attempts within the last 3 months. |
