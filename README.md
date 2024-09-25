# LimaCharlie Lookups

Lookups are dictionaries/maps/key-value-pairs where the key is a string. The lookup can then be queried by various parts of LimaCharlie (like D&R rules). The value component of a lookup must be a dictionary and represents metadata associated with the given key, which will be returned to the rule using the lookup. 

More information on using lookups in LimaCharlie can be found [here](https://docs.limacharlie.io/docs/platform-management-config-hive-lookups). Information on how to use the LimaCharlie lookup manager can be found [here](https://docs.limacharlie.io/docs/extensions-lc-extensions-lookup-manager).

LimaCharlie provides several pre-baked lookups from various 3rd parties. Below are the public URLs for each lookup. This allows you to see the contents of the lookups before adding or enabling them in your LimaCharlie organization.

* AlienVault - IP Reputation threat intelligence feed
    * https://storage.googleapis.com/lc-lookups-bucket/alienvault-ip-reputation.json
* Tor node list
    * https://storage.googleapis.com/lc-lookups-bucket/tor-ips.json
* Talos IP Blacklist
    * https://storage.googleapis.com/lc-lookups-bucket/talos-ip-blacklist.json
* CoinBlocker - Cryptojacking and cryptominers related domains and IPs
    * https://storage.googleapis.com/lc-lookups-bucket/coinblocker.json
* Feodo - Botnet C2 Indicators Of Compromise (IOCs)
    * https://storage.googleapis.com/lc-lookups-bucket/feodo-ips.json