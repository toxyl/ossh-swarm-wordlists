# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 708 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1994 | Hosts that connected within the last 3 days. |
| hosts-1w | 4086 | Hosts that connected within the last 7 days. |
| hosts-3w | 8701 | Hosts that connected within the last 21 days. |
| hosts-1m | 12330 | Hosts that connected within the last month. |
| hosts-3m | 28773 | Hosts that connected within the last 3 months. |
| users-1d | 1247 | Usernames used to connect within the last 24 hours. |
| users-3d | 1950 | Usernames used to connect within the last 3 days. |
| users-1w | 3929 | Usernames used to connect within the last 7 days. |
| users-3w | 6949 | Usernames used to connect within the last 21 days. |
| users-1m | 12574 | Usernames used to connect within the last month. |
| users-3m | 29149 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3049 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 8777 | Passwords used to connect within the last 3 days. |
| passwords-1w | 22592 | Passwords used to connect within the last 7 days. |
| passwords-3w | 56591 | Passwords used to connect within the last 21 days. |
| passwords-1m | 67735 | Passwords used to connect within the last month. |
| passwords-3m | 156144 | Passwords used to connect within the last 3 months. |
| destinations-1d | 12 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 36 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 40 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 49 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 49 | Destinations of proxy attempts within the last month. |
| destinations-3m | 90 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 38 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 50 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 80 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 135 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 143 | Payloads execution attempts within the last month. |
| payloads-3m | 395 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 9 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 56 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 107 | New hosts that connected within the last month. |
| new-hosts-3m | 532 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 3 | New usernames used to connect within the last 21 days. |
| new-users-1m | 4 | New usernames used to connect within the last month. |
| new-users-3m | 90 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 292 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1359 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2729 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 5465 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10581 | New passwords used to connect within the last month. |
| new-passwords-3m | 83750 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 1 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 1 | New payloads execution attempts within the last month. |
| new-payloads-3m | 33 | New payloads execution attempts within the last 3 months. |
