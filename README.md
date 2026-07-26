# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 175 | Hosts that connected within the last 24 hours. |
| hosts-3d | 528 | Hosts that connected within the last 3 days. |
| hosts-1w | 1411 | Hosts that connected within the last 7 days. |
| hosts-3w | 3731 | Hosts that connected within the last 21 days. |
| hosts-1m | 5048 | Hosts that connected within the last month. |
| hosts-3m | 16912 | Hosts that connected within the last 3 months. |
| users-1d | 558 | Usernames used to connect within the last 24 hours. |
| users-3d | 1380 | Usernames used to connect within the last 3 days. |
| users-1w | 3065 | Usernames used to connect within the last 7 days. |
| users-3w | 4737 | Usernames used to connect within the last 21 days. |
| users-1m | 6082 | Usernames used to connect within the last month. |
| users-3m | 10432 | Usernames used to connect within the last 3 months. |
| passwords-1d | 878 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 2222 | Passwords used to connect within the last 3 days. |
| passwords-1w | 7077 | Passwords used to connect within the last 7 days. |
| passwords-3w | 23027 | Passwords used to connect within the last 21 days. |
| passwords-1m | 30023 | Passwords used to connect within the last month. |
| passwords-3m | 81770 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 2 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 4 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 7 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 16 | Destinations of proxy attempts within the last month. |
| destinations-3m | 88 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 9 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 12 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 35 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 115 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 149 | Payloads execution attempts within the last month. |
| payloads-3m | 689 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 0 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 0 | New hosts that connected within the last month. |
| new-hosts-3m | 19 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 0 | New usernames used to connect within the last 21 days. |
| new-users-1m | 0 | New usernames used to connect within the last month. |
| new-users-3m | 19 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 59 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 302 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1093 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 3004 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 4975 | New passwords used to connect within the last month. |
| new-passwords-3m | 19949 | New passwords used to connect within the last 3 months. |
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
| new-payloads-1m | 0 | New payloads execution attempts within the last month. |
| new-payloads-3m | 17 | New payloads execution attempts within the last 3 months. |
