# labexperiments.github.io
- Expectations: Lab tests are here


  This site is the website of [The Lab Media Archive](https://labexperiments.xyz)!
## What is a DNS CNAME record?

A CNAME record, canonical name, or alias record is a DNS record type used in place of an A (for IPv4) or AAAA (for IPv6) record when the domain or subdomain is an alias of another domain.

All CNAME records must point to a domain name, not an IP address. Suppose, for example, the subdomain www, which is an alias of the root domain abc.com. The users accessing www.abc.com are referred to the root domain (or DNS zone apex). That means a DNS query that hits the DNS server for the DNS info of www.abc.com triggers another DNS lookup query for abc.com to get an IP address via its A or AAAA record.
