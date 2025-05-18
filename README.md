# Mapping The Entire IPv4 Internet Address Space

# 'Probably the biggest and most comprehensive open source Internet IPv4 address audit project ever... mapping the entire IPv4 Internet'

### ** As of 18 May 2025, this repository has over 2.624 billion public Internet IPv4 addresses mapped.**

These files present a large range of public Internet IPv4 provider/country to address lookup.
It's a bit like a '*reverse WHOIS*', where you have the *country* or *organisation* / *provider* name and can reference these files to find the associated IPv4 addresses.

These files are in the .p2p file format which is compatible with Peerblock and Peerguardian.
The file format consists of the following markdown (in most cases);

*_STARTADDRESS - END ADDRESS - DETAILS* (all free text) *STARTADDRESS-ENDADDRESS_*

In some cases, the free text may be in CIDR format. Most entries include the details along with the date that it was recorded.

The files are all plain text format and readable using Notepad, Notepad++, Vim, etc.
They have been lovingly hand created and maintained since 2006 by the author using both manual and semi-automated methods.

Use cases include;
* Deny IPv4 from specific countries (GEOIP), network providers or Government / Military
* Allow IPv4 from specific countries (GEOIP), network providers or Government / Military
* You have a firewall which is DENY ALL, and wish to 'punch a few holes in it' for specific providers or organisations (ORGIP) - you may find your network provider listed here.
* You wish to block network access from a specific provider / organisation (ORGIP).
* OSINT - Discovery of an IPv4 address from an organisation name.
* You want to launch a port scan and ensure certain organisations or countries are excluded to reduce the risk of complaints from less tolerant targets.
* Hardening your infrastructure by applying filtering to reduce the possibility of a cyber-attack.
* To limit outbound Internet traffic to only specific providers or countries (helps to lock down hosts which are compromised and are attempting to 'phone home' to their Command and Control (C&C / C2) server).
* WAF bypass. Configure your WAF/IPS/IDS to respond in a different manner depending on the source inbound IP address.
* Anti-spam filtering. Configure your packet-based firewall to block specific IP address ranges for SMTP or configure your SMTP receiver to allow or deny specific IP ranges. You could also make use of a host-based firewall.
* Whitelist IP address ranges for SMTP greylisting or DNSBL bypass.
* Search for large ranges of potentially unused IP addresses - Some large providers are now making offers for the transfer of some of these previously unused IPv4 address blocks.
* Azure Conditional Access Policies which make use of IPv4 addresses. Azure offers GEOIP but not ORGIP.
* Target audience - You already know who your target audience is (for your servers), so these lists could help you restrict access accordingly.
* Fraud prevention - As part of a 'defense-in-depth' strategy, if you provide services to clients, using these lists could help to work out the risk profile of an IP address.
* Filtering of source IP addresses to your authoritative name servers. If DNS records can't be resolved, it makes it harder for an attacker to find your hosts. This can help to reduce spam.

The lists can be adapted to suit your needs and the information within applied to commercial enterprise-grade and open source firewalls.

**NOTE1: Some country lists may not be fully populated due to recording the IPv4 addresses instead against a provider / organisation. Use both the country and the org lists for your maximum enjoyment.**

**NOTE2: The IPv4 address space allows for a maximum of _4,294,967,296_ IP addresses. Once the reserved IPv4 addresses have been deducted from this value, this will give the actual amount of useable public Internet routable IPv4 addresses that can be used. According to the authors bad math ;-), the calculated number of actual usable routable public Internet IPv4 addresses are _3,684,258,432_.**

**NOTE3: The file _UNASSIGNED.p2p_ refers to IP addresses that are not assigned to any organisation. You would not normally expect any traffic from these ranges.**

**NOTE4: The file RESERVED.p2p refers to IP addresses that are reserved and there would not normally be a reason for you to manually assign ANY of these IP address ranges.**

**NOTE5: If you find your IP address(es) listed here, be assured that all information was discovered using OSINT methodologies including WHOIS, Google or a bit of reverse DNS...**
<br><br><br>
Disclaimer; No warranty is given for any inaccuracies, loss of service or otherwise. The term IP and IPv4 are used interchangeably.  Some WHOIS records can contradict others and some WHOIS records state the IP address in the the 'EU', and the lists here try to match with an actual country, as opposed to a region. Also sometimes, WHOIS records state a specific country, and a traceroute proves otherwise, but of course this may be due to dynamic routing.... Everything listed here was recorded from a United Kingdom IP address... My hovercraft is full of eels.
<br><br>

Also - see _https://en.wikipedia.org/wiki/PeerGuardian_