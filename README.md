# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 778 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1435 | Hosts that connected within the last 3 days. |
| hosts-1w | 2552 | Hosts that connected within the last 7 days. |
| hosts-3w | 8086 | Hosts that connected within the last 21 days. |
| hosts-1m | 10731 | Hosts that connected within the last month. |
| hosts-3m | 24227 | Hosts that connected within the last 3 months. |
| users-1d | 822 | Usernames used to connect within the last 24 hours. |
| users-3d | 4136 | Usernames used to connect within the last 3 days. |
| users-1w | 4698 | Usernames used to connect within the last 7 days. |
| users-3w | 7000 | Usernames used to connect within the last 21 days. |
| users-1m | 7458 | Usernames used to connect within the last month. |
| users-3m | 16030 | Usernames used to connect within the last 3 months. |
| passwords-1d | 4738 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 27060 | Passwords used to connect within the last 3 days. |
| passwords-1w | 52618 | Passwords used to connect within the last 7 days. |
| passwords-3w | 64868 | Passwords used to connect within the last 21 days. |
| passwords-1m | 67589 | Passwords used to connect within the last month. |
| passwords-3m | 110970 | Passwords used to connect within the last 3 months. |
| destinations-1d | 17 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 30 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 49 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 89 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 91 | Destinations of proxy attempts within the last month. |
| destinations-3m | 225 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 40 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 60 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 155 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 347 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 357 | Payloads execution attempts within the last month. |
| payloads-3m | 859 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 25 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 33 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 40 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 40 | New hosts that connected within the last month. |
| new-hosts-3m | 69 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 25 | New usernames used to connect within the last 3 days. |
| new-users-1w | 33 | New usernames used to connect within the last 7 days. |
| new-users-3w | 40 | New usernames used to connect within the last 21 days. |
| new-users-1m | 40 | New usernames used to connect within the last month. |
| new-users-3m | 69 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 409 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 10185 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 11955 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 19727 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 20899 | New passwords used to connect within the last month. |
| new-passwords-3m | 50219 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 2 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 4 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 4 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 4 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 6 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 14 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 22 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 23 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 23 | New payloads execution attempts within the last month. |
| new-payloads-3m | 41 | New payloads execution attempts within the last 3 months. |
