# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 939 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2022 | Hosts that connected within the last 3 days. |
| hosts-1w | 3968 | Hosts that connected within the last 7 days. |
| hosts-3w | 10944 | Hosts that connected within the last 21 days. |
| hosts-1m | 13192 | Hosts that connected within the last month. |
| hosts-3m | 20700 | Hosts that connected within the last 3 months. |
| users-1d | 1031 | Usernames used to connect within the last 24 hours. |
| users-3d | 1693 | Usernames used to connect within the last 3 days. |
| users-1w | 3390 | Usernames used to connect within the last 7 days. |
| users-3w | 19026 | Usernames used to connect within the last 21 days. |
| users-1m | 19374 | Usernames used to connect within the last month. |
| users-3m | 23155 | Usernames used to connect within the last 3 months. |
| passwords-1d | 11139 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 40020 | Passwords used to connect within the last 3 days. |
| passwords-1w | 48221 | Passwords used to connect within the last 7 days. |
| passwords-3w | 103260 | Passwords used to connect within the last 21 days. |
| passwords-1m | 109112 | Passwords used to connect within the last month. |
| passwords-3m | 140535 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 1 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 9 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 56 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 62 | Destinations of proxy attempts within the last month. |
| destinations-3m | 72 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 58 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 67 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 75 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 283 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 303 | Payloads execution attempts within the last month. |
| payloads-3m | 477 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 19 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 24 | New hosts that connected within the last month. |
| new-hosts-3m | 33 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 19 | New usernames used to connect within the last 21 days. |
| new-users-1m | 24 | New usernames used to connect within the last month. |
| new-users-3m | 33 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 543 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 762 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2055 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 41074 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 46032 | New passwords used to connect within the last month. |
| new-passwords-3m | 74230 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 3 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 2 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 19 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 23 | New payloads execution attempts within the last month. |
| new-payloads-3m | 32 | New payloads execution attempts within the last 3 months. |
