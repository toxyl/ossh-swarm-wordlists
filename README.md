# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 868 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2318 | Hosts that connected within the last 3 days. |
| hosts-1w | 3846 | Hosts that connected within the last 7 days. |
| hosts-3w | 6988 | Hosts that connected within the last 21 days. |
| hosts-1m | 8742 | Hosts that connected within the last month. |
| hosts-3m | 22791 | Hosts that connected within the last 3 months. |
| users-1d | 990 | Usernames used to connect within the last 24 hours. |
| users-3d | 1210 | Usernames used to connect within the last 3 days. |
| users-1w | 1701 | Usernames used to connect within the last 7 days. |
| users-3w | 3196 | Usernames used to connect within the last 21 days. |
| users-1m | 3719 | Usernames used to connect within the last month. |
| users-3m | 10310 | Usernames used to connect within the last 3 months. |
| passwords-1d | 8303 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 23531 | Passwords used to connect within the last 3 days. |
| passwords-1w | 52230 | Passwords used to connect within the last 7 days. |
| passwords-3w | 57563 | Passwords used to connect within the last 21 days. |
| passwords-1m | 62364 | Passwords used to connect within the last month. |
| passwords-3m | 119348 | Passwords used to connect within the last 3 months. |
| destinations-1d | 8 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 10 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 13 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 26 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 26 | Destinations of proxy attempts within the last month. |
| destinations-3m | 126 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 33 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 56 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 290 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 398 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 417 | Payloads execution attempts within the last month. |
| payloads-3m | 859 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 7 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 14 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 15 | New hosts that connected within the last month. |
| new-hosts-3m | 73 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 7 | New usernames used to connect within the last 7 days. |
| new-users-3w | 14 | New usernames used to connect within the last 21 days. |
| new-users-1m | 15 | New usernames used to connect within the last month. |
| new-users-3m | 73 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 419 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 835 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 2117 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4068 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 6842 | New passwords used to connect within the last month. |
| new-passwords-3m | 49447 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 2 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 2 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 5 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 10 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 11 | New payloads execution attempts within the last month. |
| new-payloads-3m | 56 | New payloads execution attempts within the last 3 months. |
