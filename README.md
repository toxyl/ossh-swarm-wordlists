# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 244 | Hosts that connected within the last 24 hours. |
| hosts-3d | 735 | Hosts that connected within the last 3 days. |
| hosts-1w | 1498 | Hosts that connected within the last 7 days. |
| hosts-3w | 4042 | Hosts that connected within the last 21 days. |
| hosts-1m | 5105 | Hosts that connected within the last month. |
| hosts-3m | 17408 | Hosts that connected within the last 3 months. |
| users-1d | 1051 | Usernames used to connect within the last 24 hours. |
| users-3d | 1823 | Usernames used to connect within the last 3 days. |
| users-1w | 2931 | Usernames used to connect within the last 7 days. |
| users-3w | 4923 | Usernames used to connect within the last 21 days. |
| users-1m | 5914 | Usernames used to connect within the last month. |
| users-3m | 10153 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1225 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 2969 | Passwords used to connect within the last 3 days. |
| passwords-1w | 7116 | Passwords used to connect within the last 7 days. |
| passwords-3w | 22444 | Passwords used to connect within the last 21 days. |
| passwords-1m | 29724 | Passwords used to connect within the last month. |
| passwords-3m | 83592 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 5 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 6 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 14 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 17 | Destinations of proxy attempts within the last month. |
| destinations-3m | 88 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 12 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 39 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 90 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 136 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 232 | Payloads execution attempts within the last month. |
| payloads-3m | 694 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 0 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 2 | New hosts that connected within the last month. |
| new-hosts-3m | 20 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 0 | New usernames used to connect within the last 21 days. |
| new-users-1m | 2 | New usernames used to connect within the last month. |
| new-users-3m | 20 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 94 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 599 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 889 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 3512 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 5258 | New passwords used to connect within the last month. |
| new-passwords-3m | 21090 | New passwords used to connect within the last 3 months. |
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
| new-payloads-3m | 18 | New payloads execution attempts within the last 3 months. |
