# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 894 | Hosts that connected within the last 24 hours. |
| hosts-3d | 2267 | Hosts that connected within the last 3 days. |
| hosts-1w | 3863 | Hosts that connected within the last 7 days. |
| hosts-3w | 9563 | Hosts that connected within the last 21 days. |
| hosts-1m | 12920 | Hosts that connected within the last month. |
| hosts-3m | 23920 | Hosts that connected within the last 3 months. |
| users-1d | 3449 | Usernames used to connect within the last 24 hours. |
| users-3d | 7130 | Usernames used to connect within the last 3 days. |
| users-1w | 9833 | Usernames used to connect within the last 7 days. |
| users-3w | 12454 | Usernames used to connect within the last 21 days. |
| users-1m | 24744 | Usernames used to connect within the last month. |
| users-3m | 27752 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4246 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 18049 | Passwords used to connect within the last 3 days. |
| passwords-1w | 29456 | Passwords used to connect within the last 7 days. |
| passwords-3w | 66100 | Passwords used to connect within the last 21 days. |
| passwords-1m | 95594 | Passwords used to connect within the last month. |
| passwords-3m | 148996 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 2 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 2 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 17 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 52 | Destinations of proxy attempts within the last month. |
| destinations-3m | 71 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 27 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 31 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 38 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 111 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 223 | Payloads execution attempts within the last month. |
| payloads-3m | 379 | Payloads execution attempts within the last 3 months. |
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
| new-passwords-1d | 290 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1940 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4660 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10733 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 33902 | New passwords used to connect within the last month. |
| new-passwords-3m | 80171 | New passwords used to connect within the last 3 months. |
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
