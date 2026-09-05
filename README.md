# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 1551 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2943 | Hosts that connected within the last 3 days. |
| hosts-1w | 4140 | Hosts that connected within the last 7 days. |
| hosts-3w | 7234 | Hosts that connected within the last 21 days. |
| hosts-1m | 9173 | Hosts that connected within the last month. |
| hosts-3m | 15977 | Hosts that connected within the last 3 months. |
| users-1d | 1325 | Usernames used to connect within the last 24 hours. |
| users-3d | 2690 | Usernames used to connect within the last 3 days. |
| users-1w | 3351 | Usernames used to connect within the last 7 days. |
| users-3w | 4593 | Usernames used to connect within the last 21 days. |
| users-1m | 5414 | Usernames used to connect within the last month. |
| users-3m | 10518 | Usernames used to connect within the last 3 months. |
| passwords-1d | 9160 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 25227 | Passwords used to connect within the last 3 days. |
| passwords-1w | 34592 | Passwords used to connect within the last 7 days. |
| passwords-3w | 66061 | Passwords used to connect within the last 21 days. |
| passwords-1m | 70501 | Passwords used to connect within the last month. |
| passwords-3m | 97145 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 14 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 23 | Destinations of proxy attempts within the last month. |
| destinations-3m | 44 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 21 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 45 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 58 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 73 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 79 | Payloads execution attempts within the last month. |
| payloads-3m | 282 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 4 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 6 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 15 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 17 | New hosts that connected within the last month. |
| new-hosts-3m | 19 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 4 | New usernames used to connect within the last 3 days. |
| new-users-1w | 6 | New usernames used to connect within the last 7 days. |
| new-users-3w | 15 | New usernames used to connect within the last 21 days. |
| new-users-1m | 17 | New usernames used to connect within the last month. |
| new-users-3m | 19 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 2700 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 10386 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 14872 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 37146 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 39392 | New passwords used to connect within the last month. |
| new-passwords-3m | 48870 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 3 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 6 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 4 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 5 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 14 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 16 | New payloads execution attempts within the last month. |
| new-payloads-3m | 18 | New payloads execution attempts within the last 3 months. |
