# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 596 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1479 | Hosts that connected within the last 3 days. |
| hosts-1w | 2809 | Hosts that connected within the last 7 days. |
| hosts-3w | 7666 | Hosts that connected within the last 21 days. |
| hosts-1m | 9735 | Hosts that connected within the last month. |
| hosts-3m | 25077 | Hosts that connected within the last 3 months. |
| users-1d | 793 | Usernames used to connect within the last 24 hours. |
| users-3d | 939 | Usernames used to connect within the last 3 days. |
| users-1w | 2462 | Usernames used to connect within the last 7 days. |
| users-3w | 5618 | Usernames used to connect within the last 21 days. |
| users-1m | 7367 | Usernames used to connect within the last month. |
| users-3m | 16184 | Usernames used to connect within the last 3 months. |
| passwords-1d | 10287 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 22268 | Passwords used to connect within the last 3 days. |
| passwords-1w | 36493 | Passwords used to connect within the last 7 days. |
| passwords-3w | 78197 | Passwords used to connect within the last 21 days. |
| passwords-1m | 82401 | Passwords used to connect within the last month. |
| passwords-3m | 124270 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 19 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 32 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 91 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 95 | Destinations of proxy attempts within the last month. |
| destinations-3m | 230 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 65 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 102 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 122 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 343 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 394 | Payloads execution attempts within the last month. |
| payloads-3m | 899 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 2 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 7 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 22 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 47 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 53 | New hosts that connected within the last month. |
| new-hosts-3m | 82 | New hosts that connected within the last 3 months. |
| new-users-1d | 2 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 7 | New usernames used to connect within the last 3 days. |
| new-users-1w | 22 | New usernames used to connect within the last 7 days. |
| new-users-3w | 47 | New usernames used to connect within the last 21 days. |
| new-users-1m | 53 | New usernames used to connect within the last month. |
| new-users-3m | 82 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 530 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 3412 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 12413 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 26672 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 29623 | New passwords used to connect within the last month. |
| new-passwords-3m | 59826 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 1 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 2 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 5 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 4 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 16 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 31 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 32 | New payloads execution attempts within the last month. |
| new-payloads-3m | 50 | New payloads execution attempts within the last 3 months. |
