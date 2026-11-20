# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 572 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1722 | Hosts that connected within the last 3 days. |
| hosts-1w | 3586 | Hosts that connected within the last 7 days. |
| hosts-3w | 9147 | Hosts that connected within the last 21 days. |
| hosts-1m | 12482 | Hosts that connected within the last month. |
| hosts-3m | 31239 | Hosts that connected within the last 3 months. |
| users-1d | 1226 | Usernames used to connect within the last 24 hours. |
| users-3d | 1746 | Usernames used to connect within the last 3 days. |
| users-1w | 2088 | Usernames used to connect within the last 7 days. |
| users-3w | 3919 | Usernames used to connect within the last 21 days. |
| users-1m | 7610 | Usernames used to connect within the last month. |
| users-3m | 29676 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3384 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 18507 | Passwords used to connect within the last 3 days. |
| passwords-1w | 25661 | Passwords used to connect within the last 7 days. |
| passwords-3w | 55276 | Passwords used to connect within the last 21 days. |
| passwords-1m | 69693 | Passwords used to connect within the last month. |
| passwords-3m | 154060 | Passwords used to connect within the last 3 months. |
| destinations-1d | 9 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 12 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 31 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 52 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 58 | Destinations of proxy attempts within the last month. |
| destinations-3m | 103 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 35 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 45 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 70 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 162 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 188 | Payloads execution attempts within the last month. |
| payloads-3m | 458 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 9 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 61 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 73 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 132 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 181 | New hosts that connected within the last month. |
| new-hosts-3m | 569 | New hosts that connected within the last 3 months. |
| new-users-1d | 9 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 61 | New usernames used to connect within the last 3 days. |
| new-users-1w | 68 | New usernames used to connect within the last 7 days. |
| new-users-3w | 95 | New usernames used to connect within the last 21 days. |
| new-users-1m | 97 | New usernames used to connect within the last month. |
| new-users-3m | 172 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 225 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1892 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2750 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10326 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 13538 | New passwords used to connect within the last month. |
| new-passwords-3m | 76023 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 2 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 11 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 12 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 13 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 13 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 20 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 8 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 60 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 67 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 78 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 78 | New payloads execution attempts within the last month. |
| new-payloads-3m | 107 | New payloads execution attempts within the last 3 months. |
