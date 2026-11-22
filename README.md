# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 744 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1721 | Hosts that connected within the last 3 days. |
| hosts-1w | 3681 | Hosts that connected within the last 7 days. |
| hosts-3w | 9101 | Hosts that connected within the last 21 days. |
| hosts-1m | 12545 | Hosts that connected within the last month. |
| hosts-3m | 31545 | Hosts that connected within the last 3 months. |
| users-1d | 1076 | Usernames used to connect within the last 24 hours. |
| users-3d | 1639 | Usernames used to connect within the last 3 days. |
| users-1w | 2238 | Usernames used to connect within the last 7 days. |
| users-3w | 3744 | Usernames used to connect within the last 21 days. |
| users-1m | 7530 | Usernames used to connect within the last month. |
| users-3m | 29859 | Usernames used to connect within the last 3 months. |
| passwords-1d | 6007 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 8099 | Passwords used to connect within the last 3 days. |
| passwords-1w | 20398 | Passwords used to connect within the last 7 days. |
| passwords-3w | 54529 | Passwords used to connect within the last 21 days. |
| passwords-1m | 60974 | Passwords used to connect within the last month. |
| passwords-3m | 148033 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 10 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 16 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 46 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 58 | Destinations of proxy attempts within the last month. |
| destinations-3m | 103 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 28 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 51 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 70 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 169 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 202 | Payloads execution attempts within the last month. |
| payloads-3m | 469 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 17 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 78 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 137 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 188 | New hosts that connected within the last month. |
| new-hosts-3m | 565 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 17 | New usernames used to connect within the last 3 days. |
| new-users-1w | 76 | New usernames used to connect within the last 7 days. |
| new-users-3w | 103 | New usernames used to connect within the last 21 days. |
| new-users-1m | 106 | New usernames used to connect within the last month. |
| new-users-3m | 176 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 150 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 611 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2799 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9655 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 13720 | New passwords used to connect within the last month. |
| new-passwords-3m | 71368 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 4 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 14 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 15 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 15 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 21 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 16 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 75 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 86 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 86 | New payloads execution attempts within the last month. |
| new-payloads-3m | 112 | New payloads execution attempts within the last 3 months. |
