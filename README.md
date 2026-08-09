# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 372 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1013 | Hosts that connected within the last 3 days. |
| hosts-1w | 1647 | Hosts that connected within the last 7 days. |
| hosts-3w | 3482 | Hosts that connected within the last 21 days. |
| hosts-1m | 4802 | Hosts that connected within the last month. |
| hosts-3m | 16280 | Hosts that connected within the last 3 months. |
| users-1d | 576 | Usernames used to connect within the last 24 hours. |
| users-3d | 1279 | Usernames used to connect within the last 3 days. |
| users-1w | 1971 | Usernames used to connect within the last 7 days. |
| users-3w | 4683 | Usernames used to connect within the last 21 days. |
| users-1m | 5401 | Usernames used to connect within the last month. |
| users-3m | 10064 | Usernames used to connect within the last 3 months. |
| passwords-1d | 1306 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6495 | Passwords used to connect within the last 3 days. |
| passwords-1w | 11322 | Passwords used to connect within the last 7 days. |
| passwords-3w | 19498 | Passwords used to connect within the last 21 days. |
| passwords-1m | 25072 | Passwords used to connect within the last month. |
| passwords-3m | 80161 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 1 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 2 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 6 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 7 | Destinations of proxy attempts within the last month. |
| destinations-3m | 79 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 19 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 27 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 28 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 52 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 107 | Payloads execution attempts within the last month. |
| payloads-3m | 626 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 0 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 0 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 0 | New hosts that connected within the last month. |
| new-hosts-3m | 12 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 0 | New usernames used to connect within the last 7 days. |
| new-users-3w | 0 | New usernames used to connect within the last 21 days. |
| new-users-1m | 0 | New usernames used to connect within the last month. |
| new-users-3m | 12 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 142 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 693 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 947 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 2617 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 3841 | New passwords used to connect within the last month. |
| new-passwords-3m | 19576 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 1 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 0 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 0 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 0 | New payloads execution attempts within the last month. |
| new-payloads-3m | 11 | New payloads execution attempts within the last 3 months. |
