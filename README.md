# Footprinting-Recon-Scanning
Performed footprinting, reconnaissance, DNS enumeration, and network scanning using WHOIS, theHarvester, recon-ng, and Nmap.

# * WHOIS Lookup
Objective:-
  - WHOIS is used to gather registration information about a domain such as owner details, registrar, DNS servers, and creation/expiry dates.
Command:-
  - whois google.com
Explanation:-
  - whois → Queries WHOIS databases
  - example.com → Target domain
Sample Output:-
  Domain Name: example.com
  Registrar: Example Registrar Inc.
  Creation Date: 2020-01-01
  Expiry Date: 2030-01-01
  Name Server: ns1.example.com
Analysis:-
  The WHOIS results reveal:
    Domain registrar information
    Registration timeline
    DNS server details
    Administrative and technical contacts (if public)
