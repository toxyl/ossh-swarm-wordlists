# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 1088 | Hosts that connected within the last 24 hours. |
| hosts-3d | 3157 | Hosts that connected within the last 3 days. |
| hosts-1w | 4767 | Hosts that connected within the last 7 days. |
| hosts-3w | 7985 | Hosts that connected within the last 21 days. |
| hosts-1m | 9991 | Hosts that connected within the last month. |
| hosts-3m | 16883 | Hosts that connected within the last 3 months. |
| users-1d | 1008 | Usernames used to connect within the last 24 hours. |
| users-3d | 2599 | Usernames used to connect within the last 3 days. |
| users-1w | 4188 | Usernames used to connect within the last 7 days. |
| users-3w | 5099 | Usernames used to connect within the last 21 days. |
| users-1m | 5876 | Usernames used to connect within the last month. |
| users-3m | 10901 | Usernames used to connect within the last 3 months. |
| passwords-1d | 10464 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 21882 | Passwords used to connect within the last 3 days. |
| passwords-1w | 40115 | Passwords used to connect within the last 7 days. |
| passwords-3w | 68148 | Passwords used to connect within the last 21 days. |
| passwords-1m | 74972 | Passwords used to connect within the last month. |
| passwords-3m | 101262 | Passwords used to connect within the last 3 months. |
| destinations-1d | 5 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 25 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 25 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 31 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 40 | Destinations of proxy attempts within the last month. |
| destinations-3m | 61 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 32 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 57 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 77 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 89 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 97 | Payloads execution attempts within the last month. |
| payloads-3m | 300 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 6 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 15 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 17 | New hosts that connected within the last month. |
| new-hosts-3m | 19 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 6 | New usernames used to connect within the last 7 days. |
| new-users-3w | 15 | New usernames used to connect within the last 21 days. |
| new-users-1m | 17 | New usernames used to connect within the last month. |
| new-users-3m | 19 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 870 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 5866 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 16351 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 36113 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 42061 | New passwords used to connect within the last month. |
| new-passwords-3m | 51906 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 3 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 6 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 6 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 5 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 14 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 16 | New payloads execution attempts within the last month. |
| new-payloads-3m | 18 | New payloads execution attempts within the last 3 months. |
