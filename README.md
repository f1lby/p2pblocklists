IPv4 lookup lists.

These files present a large range of public Internet IPv4 provider/country to address lookup.
It's a bit like a 'reverse WHOIS', where you have the country or provider name and can reference these files to find the associated IPv4 addresses.

These files are in the .p2p file format which is compatible with Peerblock and Peerguardian.
The file format consists of the following markdown (in most cases);

STARTADDRESS - END ADDRESS - DETAILS (all free text)  STARTADDRESS-ENDADDRESS

In some cases, the free text may be in CIDR format. Most entries include the details along with the date that it was recorded.

The files are all plain text format and readable using Notepad, Notepad++, Vim, etc.
They have been lovingly hand created and maintained since 2006 by the author.

Use cases include;
* Deny IPv4 from specific countries (GEOIP), network providers or Government / Military
* Allow IPv4 from specific countries (GEOIP), network providers or Government / Military
* You have a firewall which is DENY ALL, and wish to 'punch a few holes in it' for specific providers or organisations - you may find your network provider listed here.
* You wish to block network access from a specific provider / organisation.

The lists can be adapted to suit your needs and the information within applied to commercial enterprise-grade and open source firewalls.

As of 04th June 2024 the list officially reached over 2 billion IPv4 addresses. We had a little party....

Disclaimer; No warranty is given for any inaccuracies, loss of service or otherwise.
These lists are pretty good and very comprehensive, but not 100% world coverage. There's always something to be added....