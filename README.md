# ossh-swarm-wordlists

Exports from my oSSH Swarm, updated daily. 

## Available Data
| Dataset | Description |
| --- | --- |
| usernames | Usernames used in login attempts |
| passwords | Passwords used in login attempts |
| hosts | IPs of connecting hosts. Note that IPs can get reassigned, use sources like AbuseIPDB to verify if IPs are still malicious. |
| destinations | Some bots attempt to proxy data through nodes, these are destinations used. Be aware that there are plenty of legitimate destinations that bots use to determine connection status e.g. |
| payloads | These are hex-encoded strings of the payloads bosts attempted to execute on the nodes. |

All datasets are availble for 1 day, 3 days, 1 week, 3 weeks, 1 month and 3 months. They are sorted by count in descending order, so that the first line of each file is the most commonly used value.
