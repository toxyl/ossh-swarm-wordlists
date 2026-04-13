# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 566 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1083 | Hosts that connected within the last 3 days. |
| hosts-1w | 2306 | Hosts that connected within the last 7 days. |
| hosts-3w | 6496 | Hosts that connected within the last 21 days. |
| hosts-1m | 9434 | Hosts that connected within the last month. |
| hosts-3m | 25995 | Hosts that connected within the last 3 months. |
| users-1d | 692 | Usernames used to connect within the last 24 hours. |
| users-3d | 877 | Usernames used to connect within the last 3 days. |
| users-1w | 1230 | Usernames used to connect within the last 7 days. |
| users-3w | 5131 | Usernames used to connect within the last 21 days. |
| users-1m | 5872 | Usernames used to connect within the last month. |
| users-3m | 15642 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3419 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 4991 | Passwords used to connect within the last 3 days. |
| passwords-1w | 13233 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57707 | Passwords used to connect within the last 21 days. |
| passwords-1m | 84290 | Passwords used to connect within the last month. |
| passwords-3m | 128166 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 8 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 58 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 88 | Destinations of proxy attempts within the last month. |
| destinations-3m | 226 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 51 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 56 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 199 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 320 | Payloads execution attempts within the last month. |
| payloads-3m | 833 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 41 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 50 | New hosts that connected within the last month. |
| new-hosts-3m | 83 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 41 | New usernames used to connect within the last 21 days. |
| new-users-1m | 50 | New usernames used to connect within the last month. |
| new-users-3m | 83 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 1099 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1297 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2362 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 25263 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 30572 | New passwords used to connect within the last month. |
| new-passwords-3m | 62291 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 3 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 27 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 35 | New payloads execution attempts within the last month. |
| new-payloads-3m | 52 | New payloads execution attempts within the last 3 months. |
