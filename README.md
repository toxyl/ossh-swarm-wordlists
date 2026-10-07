# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 848 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1925 | Hosts that connected within the last 3 days. |
| hosts-1w | 3615 | Hosts that connected within the last 7 days. |
| hosts-3w | 9443 | Hosts that connected within the last 21 days. |
| hosts-1m | 12920 | Hosts that connected within the last month. |
| hosts-3m | 23670 | Hosts that connected within the last 3 months. |
| users-1d | 4361 | Usernames used to connect within the last 24 hours. |
| users-3d | 7753 | Usernames used to connect within the last 3 days. |
| users-1w | 9583 | Usernames used to connect within the last 7 days. |
| users-3w | 12199 | Usernames used to connect within the last 21 days. |
| users-1m | 24533 | Usernames used to connect within the last month. |
| users-3m | 27555 | Usernames used to connect within the last 3 months. |
| passwords-1d | 7032 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 21160 | Passwords used to connect within the last 3 days. |
| passwords-1w | 30817 | Passwords used to connect within the last 7 days. |
| passwords-3w | 65857 | Passwords used to connect within the last 21 days. |
| passwords-1m | 95952 | Passwords used to connect within the last month. |
| passwords-3m | 148975 | Passwords used to connect within the last 3 months. |
| destinations-1d | 1 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 2 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 5 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 20 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 52 | Destinations of proxy attempts within the last month. |
| destinations-3m | 71 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 17 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 36 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 57 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 114 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 289 | Payloads execution attempts within the last month. |
| payloads-3m | 381 | Payloads execution attempts within the last 3 months. |
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
| new-passwords-1d | 624 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 2643 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 4486 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 10604 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 34121 | New passwords used to connect within the last month. |
| new-passwords-3m | 80104 | New passwords used to connect within the last 3 months. |
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
