# ansible_save_iptables

Saves IP Tables ip4 and ipv6 rules.
Its installed the package iptables-persistent
and enables its service netfilter-persistent.service

then it saved the iptables rules to
/etc/iptables/rules.v6
and
/etc/iptables/rules.v4


the tables you can save is:
filter
nat
mangle
raw
security