# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 554 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1478 | Hosts that connected within the last 3 days. |
| hosts-1w | 3581 | Hosts that connected within the last 7 days. |
| hosts-3w | 9215 | Hosts that connected within the last 21 days. |
| hosts-1m | 13402 | Hosts that connected within the last month. |
| hosts-3m | 23217 | Hosts that connected within the last 3 months. |
| users-1d | 4681 | Usernames used to connect within the last 24 hours. |
| users-3d | 6417 | Usernames used to connect within the last 3 days. |
| users-1w | 7892 | Usernames used to connect within the last 7 days. |
| users-3w | 11928 | Usernames used to connect within the last 21 days. |
| users-1m | 24043 | Usernames used to connect within the last month. |
| users-3m | 26723 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8449 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 15426 | Passwords used to connect within the last 3 days. |
| passwords-1w | 23619 | Passwords used to connect within the last 7 days. |
| passwords-3w | 64546 | Passwords used to connect within the last 21 days. |
| passwords-1m | 99246 | Passwords used to connect within the last month. |
| passwords-3m | 147161 | Passwords used to connect within the last 3 months. |
| destinations-1d | 0 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 1 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 7 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 42 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 64 | Destinations of proxy attempts within the last month. |
| destinations-3m | 71 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 17 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 27 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 60 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 122 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 308 | Payloads execution attempts within the last month. |
| payloads-3m | 386 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 4 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 16 | New hosts that connected within the last month. |
| new-hosts-3m | 33 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 4 | New usernames used to connect within the last 21 days. |
| new-users-1m | 16 | New usernames used to connect within the last month. |
| new-users-3m | 33 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 993 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 2176 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 3391 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10200 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 35647 | New passwords used to connect within the last month. |
| new-passwords-3m | 78800 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 4 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 16 | New payloads execution attempts within the last month. |
| new-payloads-3m | 32 | New payloads execution attempts within the last 3 months. |
