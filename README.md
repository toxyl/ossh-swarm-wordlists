# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 581 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1769 | Hosts that connected within the last 3 days. |
| hosts-1w | 3600 | Hosts that connected within the last 7 days. |
| hosts-3w | 9334 | Hosts that connected within the last 21 days. |
| hosts-1m | 11293 | Hosts that connected within the last month. |
| hosts-3m | 23916 | Hosts that connected within the last 3 months. |
| users-1d | 1273 | Usernames used to connect within the last 24 hours. |
| users-3d | 2061 | Usernames used to connect within the last 3 days. |
| users-1w | 2464 | Usernames used to connect within the last 7 days. |
| users-3w | 4971 | Usernames used to connect within the last 21 days. |
| users-1m | 5415 | Usernames used to connect within the last month. |
| users-3m | 14282 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8563 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 27866 | Passwords used to connect within the last 3 days. |
| passwords-1w | 32919 | Passwords used to connect within the last 7 days. |
| passwords-3w | 44984 | Passwords used to connect within the last 21 days. |
| passwords-1m | 50397 | Passwords used to connect within the last month. |
| passwords-3m | 124835 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 14 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 44 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 59 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 67 | Destinations of proxy attempts within the last month. |
| destinations-3m | 219 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 95 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 104 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 125 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 268 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 300 | Payloads execution attempts within the last month. |
| payloads-3m | 844 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 7 | New hosts that connected within the last month. |
| new-hosts-3m | 134 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 7 | New usernames used to connect within the last month. |
| new-users-3m | 134 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 553 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1905 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4076 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 8944 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 11787 | New passwords used to connect within the last month. |
| new-passwords-3m | 63785 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 11 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 1 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 1 | New payloads execution attempts within the last month. |
| new-payloads-3m | 83 | New payloads execution attempts within the last 3 months. |
