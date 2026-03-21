# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 512 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1506 | Hosts that connected within the last 3 days. |
| hosts-1w | 3576 | Hosts that connected within the last 7 days. |
| hosts-3w | 9317 | Hosts that connected within the last 21 days. |
| hosts-1m | 11204 | Hosts that connected within the last month. |
| hosts-3m | 23931 | Hosts that connected within the last 3 months. |
| users-1d | 1222 | Usernames used to connect within the last 24 hours. |
| users-3d | 1959 | Usernames used to connect within the last 3 days. |
| users-1w | 2548 | Usernames used to connect within the last 7 days. |
| users-3w | 5034 | Usernames used to connect within the last 21 days. |
| users-1m | 5400 | Usernames used to connect within the last month. |
| users-3m | 14332 | Usernames used to connect within the last 3 months. |
| passwords-1d | 31103 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 33276 | Passwords used to connect within the last 3 days. |
| passwords-1w | 38212 | Passwords used to connect within the last 7 days. |
| passwords-3w | 48522 | Passwords used to connect within the last 21 days. |
| passwords-1m | 53234 | Passwords used to connect within the last month. |
| passwords-3m | 126209 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 43 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 59 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 66 | Destinations of proxy attempts within the last month. |
| destinations-3m | 218 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 103 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 129 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 270 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 293 | Payloads execution attempts within the last month. |
| payloads-3m | 839 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 8 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 8 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 9 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 15 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 15 | New hosts that connected within the last month. |
| new-hosts-3m | 142 | New hosts that connected within the last 3 months. |
| new-users-1d | 8 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 8 | New usernames used to connect within the last 3 days. |
| new-users-1w | 9 | New usernames used to connect within the last 7 days. |
| new-users-3w | 15 | New usernames used to connect within the last 21 days. |
| new-users-1m | 15 | New usernames used to connect within the last month. |
| new-users-3m | 142 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 892 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1915 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4255 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9706 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 12137 | New passwords used to connect within the last month. |
| new-passwords-3m | 64624 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 2 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 2 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 2 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 2 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 2 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 13 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 8 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 8 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 8 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 9 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 9 | New payloads execution attempts within the last month. |
| new-payloads-3m | 91 | New payloads execution attempts within the last 3 months. |
