# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 843 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1706 | Hosts that connected within the last 3 days. |
| hosts-1w | 3166 | Hosts that connected within the last 7 days. |
| hosts-3w | 7479 | Hosts that connected within the last 21 days. |
| hosts-1m | 10873 | Hosts that connected within the last month. |
| hosts-3m | 25366 | Hosts that connected within the last 3 months. |
| users-1d | 449 | Usernames used to connect within the last 24 hours. |
| users-3d | 945 | Usernames used to connect within the last 3 days. |
| users-1w | 1504 | Usernames used to connect within the last 7 days. |
| users-3w | 5595 | Usernames used to connect within the last 21 days. |
| users-1m | 7588 | Usernames used to connect within the last month. |
| users-3m | 16210 | Usernames used to connect within the last 3 months. |
| passwords-1d | 12953 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 27194 | Passwords used to connect within the last 3 days. |
| passwords-1w | 34063 | Passwords used to connect within the last 7 days. |
| passwords-3w | 78971 | Passwords used to connect within the last 21 days. |
| passwords-1m | 84415 | Passwords used to connect within the last month. |
| passwords-3m | 125483 | Passwords used to connect within the last 3 months. |
| destinations-1d | 4 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 33 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 85 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 97 | Destinations of proxy attempts within the last month. |
| destinations-3m | 230 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 29 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 82 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 123 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 296 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 395 | Payloads execution attempts within the last month. |
| payloads-3m | 900 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 1 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 4 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 15 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 48 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 54 | New hosts that connected within the last month. |
| new-hosts-3m | 83 | New hosts that connected within the last 3 months. |
| new-users-1d | 1 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 4 | New usernames used to connect within the last 3 days. |
| new-users-1w | 15 | New usernames used to connect within the last 7 days. |
| new-users-3w | 48 | New usernames used to connect within the last 21 days. |
| new-users-1m | 54 | New usernames used to connect within the last month. |
| new-users-3m | 83 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 829 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 1855 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 10845 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 26829 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 30733 | New passwords used to connect within the last month. |
| new-passwords-3m | 60655 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 1 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 1 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 5 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 5 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 1 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 2 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 10 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 33 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 34 | New payloads execution attempts within the last month. |
| new-payloads-3m | 52 | New payloads execution attempts within the last 3 months. |
