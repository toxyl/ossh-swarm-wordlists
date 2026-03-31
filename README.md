# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 600 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1426 | Hosts that connected within the last 3 days. |
| hosts-1w | 2785 | Hosts that connected within the last 7 days. |
| hosts-3w | 7872 | Hosts that connected within the last 21 days. |
| hosts-1m | 9755 | Hosts that connected within the last month. |
| hosts-3m | 24911 | Hosts that connected within the last 3 months. |
| users-1d | 274 | Usernames used to connect within the last 24 hours. |
| users-3d | 821 | Usernames used to connect within the last 3 days. |
| users-1w | 4218 | Usernames used to connect within the last 7 days. |
| users-3w | 5592 | Usernames used to connect within the last 21 days. |
| users-1m | 7386 | Usernames used to connect within the last month. |
| users-3m | 16072 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8989 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 27656 | Passwords used to connect within the last 3 days. |
| passwords-1w | 47280 | Passwords used to connect within the last 7 days. |
| passwords-3w | 77899 | Passwords used to connect within the last 21 days. |
| passwords-1m | 81594 | Passwords used to connect within the last month. |
| passwords-3m | 123415 | Passwords used to connect within the last 3 months. |
| destinations-1d | 6 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 20 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 40 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 91 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 95 | Destinations of proxy attempts within the last month. |
| destinations-3m | 230 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 69 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 94 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 130 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 355 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 386 | Payloads execution attempts within the last month. |
| payloads-3m | 896 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 9 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 36 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 45 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 51 | New hosts that connected within the last month. |
| new-hosts-3m | 80 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 9 | New usernames used to connect within the last 3 days. |
| new-users-1w | 36 | New usernames used to connect within the last 7 days. |
| new-users-3w | 45 | New usernames used to connect within the last 21 days. |
| new-users-1m | 51 | New usernames used to connect within the last month. |
| new-users-3m | 80 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 496 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 8539 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 19261 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 27051 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 29241 | New passwords used to connect within the last month. |
| new-passwords-3m | 59295 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 2 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 4 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 4 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 6 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 22 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 30 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 31 | New payloads execution attempts within the last month. |
| new-payloads-3m | 49 | New payloads execution attempts within the last 3 months. |
