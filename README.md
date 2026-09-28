# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 554 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1403 | Hosts that connected within the last 3 days. |
| hosts-1w | 3497 | Hosts that connected within the last 7 days. |
| hosts-3w | 9545 | Hosts that connected within the last 21 days. |
| hosts-1m | 13848 | Hosts that connected within the last month. |
| hosts-3m | 21878 | Hosts that connected within the last 3 months. |
| users-1d | 2070 | Usernames used to connect within the last 24 hours. |
| users-3d | 4321 | Usernames used to connect within the last 3 days. |
| users-1w | 5151 | Usernames used to connect within the last 7 days. |
| users-3w | 19683 | Usernames used to connect within the last 21 days. |
| users-1m | 21621 | Usernames used to connect within the last month. |
| users-3m | 25133 | Usernames used to connect within the last 3 months. |
| passwords-1d | 5298 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 21982 | Passwords used to connect within the last 3 days. |
| passwords-1w | 34184 | Passwords used to connect within the last 7 days. |
| passwords-3w | 87310 | Passwords used to connect within the last 21 days. |
| passwords-1m | 112608 | Passwords used to connect within the last month. |
| passwords-3m | 144546 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 8 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 9 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 46 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 59 | Destinations of proxy attempts within the last month. |
| destinations-3m | 75 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 23 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 31 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 73 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 260 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 303 | Payloads execution attempts within the last month. |
| payloads-3m | 400 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 16 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 22 | New hosts that connected within the last month. |
| new-hosts-3m | 33 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 16 | New usernames used to connect within the last 21 days. |
| new-users-1m | 22 | New usernames used to connect within the last month. |
| new-users-3m | 33 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 796 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 2850 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4636 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 29080 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 47675 | New passwords used to connect within the last month. |
| new-passwords-3m | 77080 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 4 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 16 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 21 | New payloads execution attempts within the last month. |
| new-payloads-3m | 32 | New payloads execution attempts within the last 3 months. |
