# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 426 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1587 | Hosts that connected within the last 3 days. |
| hosts-1w | 3463 | Hosts that connected within the last 7 days. |
| hosts-3w | 8738 | Hosts that connected within the last 21 days. |
| hosts-1m | 12707 | Hosts that connected within the last month. |
| hosts-3m | 32118 | Hosts that connected within the last 3 months. |
| users-1d | 1378 | Usernames used to connect within the last 24 hours. |
| users-3d | 2037 | Usernames used to connect within the last 3 days. |
| users-1w | 2570 | Usernames used to connect within the last 7 days. |
| users-3w | 4057 | Usernames used to connect within the last 21 days. |
| users-1m | 5427 | Usernames used to connect within the last month. |
| users-3m | 30443 | Usernames used to connect within the last 3 months. |
| passwords-1d | 19507 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 24245 | Passwords used to connect within the last 3 days. |
| passwords-1w | 25846 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57201 | Passwords used to connect within the last 21 days. |
| passwords-1m | 63746 | Passwords used to connect within the last month. |
| passwords-3m | 149770 | Passwords used to connect within the last 3 months. |
| destinations-1d | 31 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 32 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 36 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 69 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 86 | Destinations of proxy attempts within the last month. |
| destinations-3m | 130 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 30 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 73 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 84 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 174 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 209 | Payloads execution attempts within the last month. |
| payloads-3m | 480 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 3 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 3 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 143 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 170 | New hosts that connected within the last month. |
| new-hosts-3m | 580 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 3 | New usernames used to connect within the last 3 days. |
| new-users-1w | 3 | New usernames used to connect within the last 7 days. |
| new-users-3w | 105 | New usernames used to connect within the last 21 days. |
| new-users-1m | 114 | New usernames used to connect within the last month. |
| new-users-3m | 181 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 700 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 2471 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 3094 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10494 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 14312 | New passwords used to connect within the last month. |
| new-passwords-3m | 71880 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 20 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 20 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 24 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 3 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 3 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 84 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 89 | New payloads execution attempts within the last month. |
| new-payloads-3m | 111 | New payloads execution attempts within the last 3 months. |
