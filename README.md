Bitlbee
=======


What is does this role do?
--------------------------

This role installs and enables the bitlbee chat service gateway which
allows an IRC client to talk to almost all known chat systems.  This role also provides firewall rules.

Meta
----

Files Managed:
  * /etc/iptables.d/bitlbee.rules
  * /var/service/bitlbee

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)
