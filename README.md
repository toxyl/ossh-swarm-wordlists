# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 605 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2198 | Hosts that connected within the last 3 days. |
| hosts-1w | 5160 | Hosts that connected within the last 7 days. |
| hosts-3w | 8446 | Hosts that connected within the last 21 days. |
| hosts-1m | 10394 | Hosts that connected within the last month. |
| hosts-3m | 17387 | Hosts that connected within the last 3 months. |
| users-1d | 1569 | Usernames used to connect within the last 24 hours. |
| users-3d | 2252 | Usernames used to connect within the last 3 days. |
| users-1w | 4676 | Usernames used to connect within the last 7 days. |
| users-3w | 5647 | Usernames used to connect within the last 21 days. |
| users-1m | 6443 | Usernames used to connect within the last month. |
| users-3m | 11338 | Usernames used to connect within the last 3 months. |
| passwords-1d | 9702 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 23220 | Passwords used to connect within the last 3 days. |
| passwords-1w | 46208 | Passwords used to connect within the last 7 days. |
| passwords-3w | 66551 | Passwords used to connect within the last 21 days. |
| passwords-1m | 83446 | Passwords used to connect within the last month. |
| passwords-3m | 107087 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 9 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 27 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 33 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 42 | Destinations of proxy attempts within the last month. |
| destinations-3m | 60 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 123 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 196 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 225 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 248 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 258 | Payloads execution attempts within the last month. |
| payloads-3m | 461 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 5 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 14 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 18 | New hosts that connected within the last month. |
| new-hosts-3m | 20 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 5 | New usernames used to connect within the last 7 days. |
| new-users-3w | 14 | New usernames used to connect within the last 21 days. |
| new-users-1m | 18 | New usernames used to connect within the last month. |
| new-users-3m | 20 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 2410 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 3794 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 16473 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 29054 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 44725 | New passwords used to connect within the last month. |
| new-passwords-3m | 54547 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 6 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 5 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 13 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 17 | New payloads execution attempts within the last month. |
| new-payloads-3m | 19 | New payloads execution attempts within the last 3 months. |
