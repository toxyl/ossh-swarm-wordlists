# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 932 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1870 | Hosts that connected within the last 3 days. |
| hosts-1w | 3348 | Hosts that connected within the last 7 days. |
| hosts-3w | 6650 | Hosts that connected within the last 21 days. |
| hosts-1m | 8381 | Hosts that connected within the last month. |
| hosts-3m | 22616 | Hosts that connected within the last 3 months. |
| users-1d | 877 | Usernames used to connect within the last 24 hours. |
| users-3d | 1206 | Usernames used to connect within the last 3 days. |
| users-1w | 2056 | Usernames used to connect within the last 7 days. |
| users-3w | 3175 | Usernames used to connect within the last 21 days. |
| users-1m | 3662 | Usernames used to connect within the last month. |
| users-3m | 10347 | Usernames used to connect within the last 3 months. |
| passwords-1d | 32694 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 49018 | Passwords used to connect within the last 3 days. |
| passwords-1w | 50817 | Passwords used to connect within the last 7 days. |
| passwords-3w | 58003 | Passwords used to connect within the last 21 days. |
| passwords-1m | 63374 | Passwords used to connect within the last month. |
| passwords-3m | 119353 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 8 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 15 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 22 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 22 | Destinations of proxy attempts within the last month. |
| destinations-3m | 122 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 132 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 274 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 293 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 390 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 405 | Payloads execution attempts within the last month. |
| payloads-3m | 862 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 6 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 8 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 13 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 15 | New hosts that connected within the last month. |
| new-hosts-3m | 72 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 6 | New usernames used to connect within the last 3 days. |
| new-users-1w | 8 | New usernames used to connect within the last 7 days. |
| new-users-3w | 13 | New usernames used to connect within the last 21 days. |
| new-users-1m | 15 | New usernames used to connect within the last month. |
| new-users-3m | 72 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 445 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1237 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1636 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4345 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 7775 | New passwords used to connect within the last month. |
| new-passwords-3m | 49621 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 2 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 2 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 4 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 6 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 9 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 11 | New payloads execution attempts within the last month. |
| new-payloads-3m | 55 | New payloads execution attempts within the last 3 months. |
