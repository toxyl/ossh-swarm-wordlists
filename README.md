# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 531 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1204 | Hosts that connected within the last 3 days. |
| hosts-1w | 2610 | Hosts that connected within the last 7 days. |
| hosts-3w | 6509 | Hosts that connected within the last 21 days. |
| hosts-1m | 10431 | Hosts that connected within the last month. |
| hosts-3m | 26201 | Hosts that connected within the last 3 months. |
| users-1d | 519 | Usernames used to connect within the last 24 hours. |
| users-3d | 975 | Usernames used to connect within the last 3 days. |
| users-1w | 1370 | Usernames used to connect within the last 7 days. |
| users-3w | 5425 | Usernames used to connect within the last 21 days. |
| users-1m | 6155 | Usernames used to connect within the last month. |
| users-3m | 16343 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1830 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 9982 | Passwords used to connect within the last 3 days. |
| passwords-1w | 15696 | Passwords used to connect within the last 7 days. |
| passwords-3w | 77608 | Passwords used to connect within the last 21 days. |
| passwords-1m | 85364 | Passwords used to connect within the last month. |
| passwords-3m | 128490 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 9 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 59 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 91 | Destinations of proxy attempts within the last month. |
| destinations-3m | 230 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 26 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 31 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 38 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 278 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 389 | Payloads execution attempts within the last month. |
| payloads-3m | 892 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 49 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 55 | New hosts that connected within the last month. |
| new-hosts-3m | 85 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 49 | New usernames used to connect within the last 21 days. |
| new-users-1m | 55 | New usernames used to connect within the last month. |
| new-users-3m | 85 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 163 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 918 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2661 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 25605 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 31973 | New passwords used to connect within the last month. |
| new-passwords-3m | 62940 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 5 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 34 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 34 | New payloads execution attempts within the last month. |
| new-payloads-3m | 53 | New payloads execution attempts within the last 3 months. |
