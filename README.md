# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 578 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1555 | Hosts that connected within the last 3 days. |
| hosts-1w | 3326 | Hosts that connected within the last 7 days. |
| hosts-3w | 9203 | Hosts that connected within the last 21 days. |
| hosts-1m | 12233 | Hosts that connected within the last month. |
| hosts-3m | 30663 | Hosts that connected within the last 3 months. |
| users-1d | 920 | Usernames used to connect within the last 24 hours. |
| users-3d | 1162 | Usernames used to connect within the last 3 days. |
| users-1w | 1415 | Usernames used to connect within the last 7 days. |
| users-3w | 4929 | Usernames used to connect within the last 21 days. |
| users-1m | 7404 | Usernames used to connect within the last month. |
| users-3m | 29327 | Usernames used to connect within the last 3 months. |
| passwords-1d | 2813 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 13306 | Passwords used to connect within the last 3 days. |
| passwords-1w | 31667 | Passwords used to connect within the last 7 days. |
| passwords-3w | 53888 | Passwords used to connect within the last 21 days. |
| passwords-1m | 68596 | Passwords used to connect within the last month. |
| passwords-3m | 163863 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 25 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 31 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 51 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 59 | Destinations of proxy attempts within the last month. |
| destinations-3m | 99 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 48 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 119 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 161 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 184 | Payloads execution attempts within the last month. |
| payloads-3m | 441 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 15 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 51 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 90 | New hosts that connected within the last month. |
| new-hosts-3m | 550 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 6 | New usernames used to connect within the last 7 days. |
| new-users-3w | 17 | New usernames used to connect within the last 21 days. |
| new-users-1m | 18 | New usernames used to connect within the last month. |
| new-users-3m | 102 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 222 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 554 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4543 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 9482 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 11775 | New passwords used to connect within the last month. |
| new-passwords-3m | 87829 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 8 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 6 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 11 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 12 | New payloads execution attempts within the last month. |
| new-payloads-3m | 42 | New payloads execution attempts within the last 3 months. |
