# DHCP (Dynamic Host Configuration Protocol)
Allows devices to automatically obtain a IP address. *Ethan's Definition* 
A network management protocol that automatically assigns IP addresses and essential connection settings to devices on a network. *Official Definition* 

## Example:
When a device shows up and says "I'm new here - where do I go?", DHCP responds with:
- an IP address
- subnet mask
- default gateway
- DNS servers
- lease duration
Without DHCP, every device would require manual configuration.

## Why DHCP matters
1. Stability and uptime
	Misconfigured IP settings cause outages, Incorrect gateways = note internet. Wrong DNS = apps break. DHCP ensures consistency and reduces human error.
2. Scalability
	Managing 10 devices manually is doable. Managing 1,000 is a nightmare. DHCP enables plug-and-play onboarding of devices across your environment.
3. Centralized control
	You can update network settings globally in one place. For example. change DNS servers once on your DHCP server instead of touching every workstation

### What to know about DHCP
- How to design and size DHCP scopes properly
- How DHCP leasing works (discover, offer, request, acknowledge)
- Reserved IP vs dynamic lease
- Scope options vs server options
- How DHCP works across VLANs (relay/Helper Address on routers)
- How to detect and eliminate rogue DHCP servers
- How to troubleshoot common DHCP failures


