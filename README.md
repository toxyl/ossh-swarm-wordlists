# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 412 | Hosts that connected within the last 24 hours. |
| hosts-3d | 810 | Hosts that connected within the last 3 days. |
| hosts-1w | 1613 | Hosts that connected within the last 7 days. |
| hosts-3w | 3956 | Hosts that connected within the last 21 days. |
| hosts-1m | 6857 | Hosts that connected within the last month. |
| hosts-3m | 19018 | Hosts that connected within the last 3 months. |
| users-1d | 644 | Usernames used to connect within the last 24 hours. |
| users-3d | 1174 | Usernames used to connect within the last 3 days. |
| users-1w | 1772 | Usernames used to connect within the last 7 days. |
| users-3w | 3869 | Usernames used to connect within the last 21 days. |
| users-1m | 5486 | Usernames used to connect within the last month. |
| users-3m | 8461 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2682 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 7722 | Passwords used to connect within the last 3 days. |
| passwords-1w | 10711 | Passwords used to connect within the last 7 days. |
| passwords-3w | 21069 | Passwords used to connect within the last 21 days. |
| passwords-1m | 46026 | Passwords used to connect within the last month. |
| passwords-3m | 101850 | Passwords used to connect within the last 3 months. |
| destinations-1d | 5 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 6 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 6 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 23 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 65 | Destinations of proxy attempts within the last month. |
| destinations-3m | 95 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 24 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 30 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 147 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 178 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 269 | Payloads execution attempts within the last month. |
| payloads-3m | 725 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 2 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 5 | New hosts that connected within the last month. |
| new-hosts-3m | 31 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 2 | New usernames used to connect within the last 21 days. |
| new-users-1m | 5 | New usernames used to connect within the last month. |
| new-users-3m | 31 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 163 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 464 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1407 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4000 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 9153 | New passwords used to connect within the last month. |
| new-passwords-3m | 29579 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 3 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 2 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 4 | New payloads execution attempts within the last month. |
| new-payloads-3m | 27 | New payloads execution attempts within the last 3 months. |
