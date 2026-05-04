# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 481 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1125 | Hosts that connected within the last 3 days. |
| hosts-1w | 2230 | Hosts that connected within the last 7 days. |
| hosts-3w | 6044 | Hosts that connected within the last 21 days. |
| hosts-1m | 7716 | Hosts that connected within the last month. |
| hosts-3m | 24205 | Hosts that connected within the last 3 months. |
| users-1d | 740 | Usernames used to connect within the last 24 hours. |
| users-3d | 1073 | Usernames used to connect within the last 3 days. |
| users-1w | 1577 | Usernames used to connect within the last 7 days. |
| users-3w | 2839 | Usernames used to connect within the last 21 days. |
| users-1m | 3191 | Usernames used to connect within the last month. |
| users-3m | 13221 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1973 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 3491 | Passwords used to connect within the last 3 days. |
| passwords-1w | 28976 | Passwords used to connect within the last 7 days. |
| passwords-3w | 47711 | Passwords used to connect within the last 21 days. |
| passwords-1m | 53592 | Passwords used to connect within the last month. |
| passwords-3m | 120052 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 5 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 8 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 15 | Destinations of proxy attempts within the last month. |
| destinations-3m | 109 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 34 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 81 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 119 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 153 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 180 | Payloads execution attempts within the last month. |
| payloads-3m | 617 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 3 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 7 | New hosts that connected within the last month. |
| new-hosts-3m | 73 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 3 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 7 | New usernames used to connect within the last month. |
| new-users-3m | 73 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 103 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 336 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1066 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 7099 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10325 | New passwords used to connect within the last month. |
| new-passwords-3m | 56208 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 5 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 5 | New payloads execution attempts within the last month. |
| new-payloads-3m | 48 | New payloads execution attempts within the last 3 months. |
