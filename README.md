# ossh-swarm-wordlists

Daily exports from my swarm of SSH honeypots.  

## Available Data

All datasets are sorted by count in descending order, i.e. the first line of each file is the most commonly used value.  
Datasets starting with `new` represent values that have never been seen before the given period. For example `new-passwords-1d.txt` will contain the passwords used in the last 24 hours that have not been seen in the data before `now - 24 hours`. 

| Dataset | Records | Description |
| --- | --- | --- |
| hosts-1d | 513 | Hosts that connected within the last 24 hours. |
| hosts-3d | 1772 | Hosts that connected within the last 3 days. |
| hosts-1w | 3876 | Hosts that connected within the last 7 days. |
| hosts-3w | 7829 | Hosts that connected within the last 21 days. |
| hosts-1m | 9631 | Hosts that connected within the last month. |
| hosts-3m | 22835 | Hosts that connected within the last 3 months. |
| users-1d | 894 | Usernames used to connect within the last 24 hours. |
| users-3d | 1537 | Usernames used to connect within the last 3 days. |
| users-1w | 2330 | Usernames used to connect within the last 7 days. |
| users-3w | 3801 | Usernames used to connect within the last 21 days. |
| users-1m | 4293 | Usernames used to connect within the last month. |
| users-3m | 10093 | Usernames used to connect within the last 3 months. |
| passwords-1d | 17089 | Passwords used to connect within the last 24 hours. |
| passwords-3d | 32165 | Passwords used to connect within the last 3 days. |
| passwords-1w | 38243 | Passwords used to connect within the last 7 days. |
| passwords-3w | 58392 | Passwords used to connect within the last 21 days. |
| passwords-1m | 62740 | Passwords used to connect within the last month. |
| passwords-3m | 117106 | Passwords used to connect within the last 3 months. |
| destinations-1d | 3 | Destinations of proxy attempts within the last 24 hours. |
| destinations-3d | 7 | Destinations of proxy attempts within the last 3 days. |
| destinations-1w | 10 | Destinations of proxy attempts within the last 7 days. |
| destinations-3w | 25 | Destinations of proxy attempts within the last 21 days. |
| destinations-1m | 26 | Destinations of proxy attempts within the last month. |
| destinations-3m | 123 | Destinations of proxy attempts within the last 3 months. |
| payloads-1d | 43 | Payloads execution attempts within the last 24 hours. |
| payloads-3d | 54 | Payloads execution attempts within the last 3 days. |
| payloads-1w | 63 | Payloads execution attempts within the last 7 days. |
| payloads-3w | 399 | Payloads execution attempts within the last 21 days. |
| payloads-1m | 420 | Payloads execution attempts within the last month. |
| payloads-3m | 811 | Payloads execution attempts within the last 3 months. |
| new-hosts-1d | 0 | New hosts that connected within the last 24 hours. |
| new-hosts-3d | 0 | New hosts that connected within the last 3 days. |
| new-hosts-1w | 1 | New hosts that connected within the last 7 days. |
| new-hosts-3w | 9 | New hosts that connected within the last 21 days. |
| new-hosts-1m | 14 | New hosts that connected within the last month. |
| new-hosts-3m | 72 | New hosts that connected within the last 3 months. |
| new-users-1d | 0 | New usernames used to connect within the last 24 hours. |
| new-users-3d | 0 | New usernames used to connect within the last 3 days. |
| new-users-1w | 1 | New usernames used to connect within the last 7 days. |
| new-users-3w | 9 | New usernames used to connect within the last 21 days. |
| new-users-1m | 14 | New usernames used to connect within the last month. |
| new-users-3m | 72 | New usernames used to connect within the last 3 months. |
| new-passwords-1d | 48 | New passwords used to connect within the last 24 hours. |
| new-passwords-3d | 592 | New passwords used to connect within the last 3 days. |
| new-passwords-1w | 1977 | New passwords used to connect within the last 7 days. |
| new-passwords-3w | 4592 | New passwords used to connect within the last 21 days. |
| new-passwords-1m | 6737 | New passwords used to connect within the last month. |
| new-passwords-3m | 47827 | New passwords used to connect within the last 3 months. |
| new-destinations-1d | 0 | New destinations of proxy attempts within the last 24 hours. |
| new-destinations-3d | 0 | New destinations of proxy attempts within the last 3 days. |
| new-destinations-1w | 0 | New destinations of proxy attempts within the last 7 days. |
| new-destinations-3w | 1 | New destinations of proxy attempts within the last 21 days. |
| new-destinations-1m | 2 | New destinations of proxy attempts within the last month. |
| new-destinations-3m | 7 | New destinations of proxy attempts within the last 3 months. |
| new-payloads-1d | 0 | New payloads execution attempts within the last 24 hours. |
| new-payloads-3d | 0 | New payloads execution attempts within the last 3 days. |
| new-payloads-1w | 1 | New payloads execution attempts within the last 7 days. |
| new-payloads-3w | 7 | New payloads execution attempts within the last 21 days. |
| new-payloads-1m | 10 | New payloads execution attempts within the last month. |
| new-payloads-3m | 57 | New payloads execution attempts within the last 3 months. |
