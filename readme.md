# IPDenyBlackList

Bash script for download and set ipset in firewall deamon.
Script downloads all zones from [https://www.ipdeny.com/]()

Usage: ipdenyblacklist `<command>`

Available commands:

`download` - Download blacklisted IPs.
`ipset-flush` - Remove all IPs from ipset
`ipset-update <FILE>` - Update ipset with given `<FILE>`

Remember to call ```firewall-cmd --reload``` to activate changes.