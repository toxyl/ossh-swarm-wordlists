# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 731 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1580 | Hosts that connected within the last 3 days. |
| hosts-1w | 2588 | Hosts that connected within the last 7 days. |
| hosts-3w | 6679 | Hosts that connected within the last 21 days. |
| hosts-1m | 9455 | Hosts that connected within the last month. |
| hosts-3m | 26028 | Hosts that connected within the last 3 months. |
| users-1d | 742 | Usernames used to connect within the last 24 hours. |
| users-3d | 1187 | Usernames used to connect within the last 3 days. |
| users-1w | 1369 | Usernames used to connect within the last 7 days. |
| users-3w | 3433 | Usernames used to connect within the last 21 days. |
| users-1m | 5858 | Usernames used to connect within the last month. |
| users-3m | 15680 | Usernames used to connect within the last 3 months. |
| passwords-1d | 3912 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 8652 | Passwords used to connect within the last 3 days. |
| passwords-1w | 12117 | Passwords used to connect within the last 7 days. |
| passwords-3w | 48672 | Passwords used to connect within the last 21 days. |
| passwords-1m | 86105 | Passwords used to connect within the last month. |
| passwords-3m | 129710 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 4 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 8 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 40 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 68 | Destinations of proxy attempts within the last month. |
| destinations-3m | 218 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 30 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 90 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 107 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 172 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 327 | Payloads execution attempts within the last month. |
| payloads-3m | 771 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 1 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 26 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 51 | New hosts that connected within the last month. |
| new-hosts-3m | 82 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 1 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 26 | New usernames used to connect within the last 21 days. |
| new-users-1m | 51 | New usernames used to connect within the last month. |
| new-users-3m | 82 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 993 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 3359 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 3867 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 19608 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 31823 | New passwords used to connect within the last month. |
| new-passwords-3m | 63189 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 2 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 1 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 20 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 36 | New payloads execution attempts within the last month. |
| new-payloads-3m | 51 | New payloads execution attempts within the last 3 months. |
