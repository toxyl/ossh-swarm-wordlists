# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 422 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1069 | Hosts that connected within the last 3 days. |
| hosts-1w | 2174 | Hosts that connected within the last 7 days. |
| hosts-3w | 6075 | Hosts that connected within the last 21 days. |
| hosts-1m | 8352 | Hosts that connected within the last month. |
| hosts-3m | 24795 | Hosts that connected within the last 3 months. |
| users-1d | 661 | Usernames used to connect within the last 24 hours. |
| users-3d | 977 | Usernames used to connect within the last 3 days. |
| users-1w | 1458 | Usernames used to connect within the last 7 days. |
| users-3w | 2403 | Usernames used to connect within the last 21 days. |
| users-1m | 5709 | Usernames used to connect within the last month. |
| users-3m | 15341 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8887 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 28380 | Passwords used to connect within the last 3 days. |
| passwords-1w | 34106 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57554 | Passwords used to connect within the last 21 days. |
| passwords-1m | 84695 | Passwords used to connect within the last month. |
| passwords-3m | 127751 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 5 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 12 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 62 | Destinations of proxy attempts within the last month. |
| destinations-3m | 199 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 32 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 71 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 78 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 130 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 255 | Payloads execution attempts within the last month. |
| payloads-3m | 711 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 4 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 42 | New hosts that connected within the last month. |
| new-hosts-3m | 76 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 4 | New usernames used to connect within the last 21 days. |
| new-users-1m | 42 | New usernames used to connect within the last month. |
| new-users-3m | 76 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 263 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 690 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1896 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9090 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 29508 | New passwords used to connect within the last month. |
| new-passwords-3m | 60813 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 3 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 3 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 29 | New payloads execution attempts within the last month. |
| new-payloads-3m | 49 | New payloads execution attempts within the last 3 months. |
