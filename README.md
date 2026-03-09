# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 622 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1310 | Hosts that connected within the last 3 days. |
| hosts-1w | 3033 | Hosts that connected within the last 7 days. |
| hosts-3w | 7921 | Hosts that connected within the last 21 days. |
| hosts-1m | 10719 | Hosts that connected within the last month. |
| hosts-3m | 21532 | Hosts that connected within the last 3 months. |
| users-1d | 2859 | Usernames used to connect within the last 24 hours. |
| users-3d | 3125 | Usernames used to connect within the last 3 days. |
| users-1w | 3694 | Usernames used to connect within the last 7 days. |
| users-3w | 5235 | Usernames used to connect within the last 21 days. |
| users-1m | 7582 | Usernames used to connect within the last month. |
| users-3m | 14131 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3863 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 6838 | Passwords used to connect within the last 3 days. |
| passwords-1w | 10378 | Passwords used to connect within the last 7 days. |
| passwords-3w | 31886 | Passwords used to connect within the last 21 days. |
| passwords-1m | 39796 | Passwords used to connect within the last month. |
| passwords-3m | 118497 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 14 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 17 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 27 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 28 | Destinations of proxy attempts within the last month. |
| destinations-3m | 195 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 61 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 71 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 76 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 184 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 214 | Payloads execution attempts within the last month. |
| payloads-3m | 755 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 2 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 7 | New hosts that connected within the last month. |
| new-hosts-3m | 145 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 2 | New usernames used to connect within the last 21 days. |
| new-users-1m | 7 | New usernames used to connect within the last month. |
| new-users-3m | 145 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 396 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 851 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1421 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 6285 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 12041 | New passwords used to connect within the last month. |
| new-passwords-3m | 63687 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 0 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 0 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 12 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 1 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 2 | New payloads execution attempts within the last month. |
| new-payloads-3m | 90 | New payloads execution attempts within the last 3 months. |
