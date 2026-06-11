# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 387 | Hosts that connected within the last 24 hours. |
| hosts-3d | 875 | Hosts that connected within the last 3 days. |
| hosts-1w | 1393 | Hosts that connected within the last 7 days. |
| hosts-3w | 6885 | Hosts that connected within the last 21 days. |
| hosts-1m | 10214 | Hosts that connected within the last month. |
| hosts-3m | 21695 | Hosts that connected within the last 3 months. |
| users-1d | 677 | Usernames used to connect within the last 24 hours. |
| users-3d | 1019 | Usernames used to connect within the last 3 days. |
| users-1w | 1423 | Usernames used to connect within the last 7 days. |
| users-3w | 4372 | Usernames used to connect within the last 21 days. |
| users-1m | 5123 | Usernames used to connect within the last month. |
| users-3m | 9810 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4519 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6758 | Passwords used to connect within the last 3 days. |
| passwords-1w | 8512 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57827 | Passwords used to connect within the last 21 days. |
| passwords-1m | 65805 | Passwords used to connect within the last month. |
| passwords-3m | 119729 | Passwords used to connect within the last 3 months. |
| destinations-1d | 2 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 10 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 11 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 57 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 64 | Destinations of proxy attempts within the last month. |
| destinations-3m | 140 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 16 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 29 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 30 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 167 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 422 | Payloads execution attempts within the last month. |
| payloads-3m | 850 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 3 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 10 | New hosts that connected within the last month. |
| new-hosts-3m | 69 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 3 | New usernames used to connect within the last 21 days. |
| new-users-1m | 10 | New usernames used to connect within the last month. |
| new-users-3m | 69 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 256 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 649 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 875 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 6620 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10091 | New passwords used to connect within the last month. |
| new-passwords-3m | 49501 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 62 | New payloads execution attempts within the last 3 months. |
