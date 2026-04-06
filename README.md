# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 462 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1247 | Hosts that connected within the last 3 days. |
| hosts-1w | 3019 | Hosts that connected within the last 7 days. |
| hosts-3w | 6928 | Hosts that connected within the last 21 days. |
| hosts-1m | 10440 | Hosts that connected within the last month. |
| hosts-3m | 26010 | Hosts that connected within the last 3 months. |
| users-1d | 888 | Usernames used to connect within the last 24 hours. |
| users-3d | 1054 | Usernames used to connect within the last 3 days. |
| users-1w | 1527 | Usernames used to connect within the last 7 days. |
| users-3w | 5407 | Usernames used to connect within the last 21 days. |
| users-1m | 7440 | Usernames used to connect within the last month. |
| users-3m | 16304 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8044 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 9931 | Passwords used to connect within the last 3 days. |
| passwords-1w | 31489 | Passwords used to connect within the last 7 days. |
| passwords-3w | 78537 | Passwords used to connect within the last 21 days. |
| passwords-1m | 85659 | Passwords used to connect within the last month. |
| passwords-3m | 127670 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 8 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 11 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 65 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 95 | Destinations of proxy attempts within the last month. |
| destinations-3m | 230 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 28 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 33 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 89 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 284 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 399 | Payloads execution attempts within the last month. |
| payloads-3m | 906 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 6 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 49 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 56 | New hosts that connected within the last month. |
| new-hosts-3m | 85 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 6 | New usernames used to connect within the last 7 days. |
| new-users-3w | 49 | New usernames used to connect within the last 21 days. |
| new-users-1m | 56 | New usernames used to connect within the last month. |
| new-users-3m | 85 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 699 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1214 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 3598 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 26732 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 31906 | New passwords used to connect within the last month. |
| new-passwords-3m | 62398 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 5 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 3 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 34 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 35 | New payloads execution attempts within the last month. |
| new-payloads-3m | 53 | New payloads execution attempts within the last 3 months. |
