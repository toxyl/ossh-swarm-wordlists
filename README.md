# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 434 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1117 | Hosts that connected within the last 3 days. |
| hosts-1w | 2204 | Hosts that connected within the last 7 days. |
| hosts-3w | 5934 | Hosts that connected within the last 21 days. |
| hosts-1m | 7726 | Hosts that connected within the last month. |
| hosts-3m | 23974 | Hosts that connected within the last 3 months. |
| users-1d | 676 | Usernames used to connect within the last 24 hours. |
| users-3d | 1139 | Usernames used to connect within the last 3 days. |
| users-1w | 1614 | Usernames used to connect within the last 7 days. |
| users-3w | 2754 | Usernames used to connect within the last 21 days. |
| users-1m | 3202 | Usernames used to connect within the last month. |
| users-3m | 12278 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4246 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 5957 | Passwords used to connect within the last 3 days. |
| passwords-1w | 28566 | Passwords used to connect within the last 7 days. |
| passwords-3w | 46198 | Passwords used to connect within the last 21 days. |
| passwords-1m | 53486 | Passwords used to connect within the last month. |
| passwords-3m | 118900 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 6 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 8 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 15 | Destinations of proxy attempts within the last month. |
| destinations-3m | 109 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 62 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 105 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 116 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 144 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 179 | Payloads execution attempts within the last month. |
| payloads-3m | 619 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 3 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 7 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 7 | New hosts that connected within the last month. |
| new-hosts-3m | 73 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 3 | New usernames used to connect within the last 7 days. |
| new-users-3w | 7 | New usernames used to connect within the last 21 days. |
| new-users-1m | 7 | New usernames used to connect within the last month. |
| new-users-3m | 73 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 67 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 323 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 975 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 5898 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 10227 | New passwords used to connect within the last month. |
| new-passwords-3m | 54991 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 5 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 5 | New payloads execution attempts within the last month. |
| new-payloads-3m | 48 | New payloads execution attempts within the last 3 months. |
