# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 458 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1515 | Hosts that connected within the last 3 days. |
| hosts-1w | 3529 | Hosts that connected within the last 7 days. |
| hosts-3w | 9057 | Hosts that connected within the last 21 days. |
| hosts-1m | 12092 | Hosts that connected within the last month. |
| hosts-3m | 29911 | Hosts that connected within the last 3 months. |
| users-1d | 1015 | Usernames used to connect within the last 24 hours. |
| users-3d | 1480 | Usernames used to connect within the last 3 days. |
| users-1w | 2090 | Usernames used to connect within the last 7 days. |
| users-3w | 6754 | Usernames used to connect within the last 21 days. |
| users-1m | 7913 | Usernames used to connect within the last month. |
| users-3m | 29330 | Usernames used to connect within the last 3 months. |
| passwords-1d | 5831 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 17881 | Passwords used to connect within the last 3 days. |
| passwords-1w | 35236 | Passwords used to connect within the last 7 days. |
| passwords-3w | 58755 | Passwords used to connect within the last 21 days. |
| passwords-1m | 62048 | Passwords used to connect within the last month. |
| passwords-3m | 158343 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 3 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 47 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 49 | Destinations of proxy attempts within the last month. |
| destinations-3m | 90 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 28 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 31 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 38 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 134 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 141 | Payloads execution attempts within the last month. |
| payloads-3m | 400 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 4 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 7 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 65 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 83 | New hosts that connected within the last month. |
| new-hosts-3m | 539 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 4 | New usernames used to connect within the last 3 days. |
| new-users-1w | 5 | New usernames used to connect within the last 7 days. |
| new-users-3w | 9 | New usernames used to connect within the last 21 days. |
| new-users-1m | 10 | New usernames used to connect within the last month. |
| new-users-3m | 96 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 291 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 905 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2231 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 6925 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 8325 | New passwords used to connect within the last month. |
| new-passwords-3m | 85012 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 4 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 5 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 6 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 6 | New payloads execution attempts within the last month. |
| new-payloads-3m | 38 | New payloads execution attempts within the last 3 months. |
