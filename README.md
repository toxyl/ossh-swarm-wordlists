# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 909 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2207 | Hosts that connected within the last 3 days. |
| hosts-1w | 3717 | Hosts that connected within the last 7 days. |
| hosts-3w | 8539 | Hosts that connected within the last 21 days. |
| hosts-1m | 10184 | Hosts that connected within the last month. |
| hosts-3m | 22020 | Hosts that connected within the last 3 months. |
| users-1d | 910 | Usernames used to connect within the last 24 hours. |
| users-3d | 1482 | Usernames used to connect within the last 3 days. |
| users-1w | 2011 | Usernames used to connect within the last 7 days. |
| users-3w | 3450 | Usernames used to connect within the last 21 days. |
| users-1m | 4406 | Usernames used to connect within the last month. |
| users-3m | 10149 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8090 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 10738 | Passwords used to connect within the last 3 days. |
| passwords-1w | 43972 | Passwords used to connect within the last 7 days. |
| passwords-3w | 58385 | Passwords used to connect within the last 21 days. |
| passwords-1m | 61233 | Passwords used to connect within the last month. |
| passwords-3m | 117398 | Passwords used to connect within the last 3 months. |
| destinations-1d | 27 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 28 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 29 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 38 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 48 | Destinations of proxy attempts within the last month. |
| destinations-3m | 135 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 53 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 69 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 93 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 357 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 454 | Payloads execution attempts within the last month. |
| payloads-3m | 834 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 9 | New hosts that connected within the last month. |
| new-hosts-3m | 72 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 9 | New usernames used to connect within the last month. |
| new-users-3m | 72 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 412 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1074 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1544 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 5254 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 6252 | New passwords used to connect within the last month. |
| new-passwords-3m | 47721 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 5 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 59 | New payloads execution attempts within the last 3 months. |
