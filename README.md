# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 338 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1384 | Hosts that connected within the last 3 days. |
| hosts-1w | 2570 | Hosts that connected within the last 7 days. |
| hosts-3w | 6554 | Hosts that connected within the last 21 days. |
| hosts-1m | 8990 | Hosts that connected within the last month. |
| hosts-3m | 25763 | Hosts that connected within the last 3 months. |
| users-1d | 564 | Usernames used to connect within the last 24 hours. |
| users-3d | 1053 | Usernames used to connect within the last 3 days. |
| users-1w | 1514 | Usernames used to connect within the last 7 days. |
| users-3w | 2427 | Usernames used to connect within the last 21 days. |
| users-1m | 5868 | Usernames used to connect within the last month. |
| users-3m | 15671 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1927 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6191 | Passwords used to connect within the last 3 days. |
| passwords-1w | 11386 | Passwords used to connect within the last 7 days. |
| passwords-3w | 45162 | Passwords used to connect within the last 21 days. |
| passwords-1m | 85049 | Passwords used to connect within the last month. |
| passwords-3m | 129677 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 3 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 28 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 68 | Destinations of proxy attempts within the last month. |
| destinations-3m | 204 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 28 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 34 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 107 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 160 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 326 | Payloads execution attempts within the last month. |
| payloads-3m | 742 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 17 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 50 | New hosts that connected within the last month. |
| new-hosts-3m | 80 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 17 | New usernames used to connect within the last 21 days. |
| new-users-1m | 50 | New usernames used to connect within the last month. |
| new-users-3m | 80 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 300 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1769 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4333 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 17577 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 31436 | New passwords used to connect within the last month. |
| new-passwords-3m | 63126 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 13 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 36 | New payloads execution attempts within the last month. |
| new-payloads-3m | 49 | New payloads execution attempts within the last 3 months. |
