# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 704 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1635 | Hosts that connected within the last 3 days. |
| hosts-1w | 2799 | Hosts that connected within the last 7 days. |
| hosts-3w | 6098 | Hosts that connected within the last 21 days. |
| hosts-1m | 8003 | Hosts that connected within the last month. |
| hosts-3m | 23546 | Hosts that connected within the last 3 months. |
| users-1d | 1195 | Usernames used to connect within the last 24 hours. |
| users-3d | 1753 | Usernames used to connect within the last 3 days. |
| users-1w | 2132 | Usernames used to connect within the last 7 days. |
| users-3w | 3165 | Usernames used to connect within the last 21 days. |
| users-1m | 3655 | Usernames used to connect within the last month. |
| users-3m | 12090 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2397 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 7408 | Passwords used to connect within the last 3 days. |
| passwords-1w | 14809 | Passwords used to connect within the last 7 days. |
| passwords-3w | 45104 | Passwords used to connect within the last 21 days. |
| passwords-1m | 52337 | Passwords used to connect within the last month. |
| passwords-3m | 117759 | Passwords used to connect within the last 3 months. |
| destinations-1d | 8 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 14 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 16 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 17 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 20 | Destinations of proxy attempts within the last month. |
| destinations-3m | 117 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 61 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 128 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 162 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 196 | Payloads execution attempts within the last month. |
| payloads-3m | 635 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 2 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 8 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 9 | New hosts that connected within the last month. |
| new-hosts-3m | 71 | New hosts that connected within the last 3 months. |
| new-users-1d | 2 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 8 | New usernames used to connect within the last 21 days. |
| new-users-1m | 9 | New usernames used to connect within the last month. |
| new-users-3m | 71 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 158 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 448 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 864 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4474 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 9151 | New passwords used to connect within the last month. |
| new-passwords-3m | 53165 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 2 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 6 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 7 | New payloads execution attempts within the last month. |
| new-payloads-3m | 49 | New payloads execution attempts within the last 3 months. |
