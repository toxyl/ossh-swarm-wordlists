# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 1052 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2309 | Hosts that connected within the last 3 days. |
| hosts-1w | 4190 | Hosts that connected within the last 7 days. |
| hosts-3w | 8911 | Hosts that connected within the last 21 days. |
| hosts-1m | 10799 | Hosts that connected within the last month. |
| hosts-3m | 23173 | Hosts that connected within the last 3 months. |
| users-1d | 1032 | Usernames used to connect within the last 24 hours. |
| users-3d | 1709 | Usernames used to connect within the last 3 days. |
| users-1w | 2359 | Usernames used to connect within the last 7 days. |
| users-3w | 3736 | Usernames used to connect within the last 21 days. |
| users-1m | 4775 | Usernames used to connect within the last month. |
| users-3m | 10379 | Usernames used to connect within the last 3 months. |
| passwords-1d | 6789 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 21785 | Passwords used to connect within the last 3 days. |
| passwords-1w | 39987 | Passwords used to connect within the last 7 days. |
| passwords-3w | 62068 | Passwords used to connect within the last 21 days. |
| passwords-1m | 65255 | Passwords used to connect within the last month. |
| passwords-3m | 120812 | Passwords used to connect within the last 3 months. |
| destinations-1d | 15 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 43 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 44 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 51 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 62 | Destinations of proxy attempts within the last month. |
| destinations-3m | 143 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 59 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 110 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 134 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 398 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 493 | Payloads execution attempts within the last month. |
| payloads-3m | 879 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 2 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 2 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 9 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 11 | New hosts that connected within the last month. |
| new-hosts-3m | 74 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 2 | New usernames used to connect within the last 3 days. |
| new-users-1w | 2 | New usernames used to connect within the last 7 days. |
| new-users-3w | 9 | New usernames used to connect within the last 21 days. |
| new-users-1m | 11 | New usernames used to connect within the last month. |
| new-users-3m | 74 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 901 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 3131 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4047 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 7696 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 8891 | New passwords used to connect within the last month. |
| new-passwords-3m | 50572 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 1 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 6 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 8 | New payloads execution attempts within the last month. |
| new-payloads-3m | 62 | New payloads execution attempts within the last 3 months. |
