# DNS in detail

## Task1: What is DNS

- DNS stand for : **Domain Name System**

## Task2: Domain Hierarchy

- The maximum length of a subdomain is : **63**

- The character cannot be used in a subdomain is : **_**

- The maximum length of a subdomain is: **256**

- The domain .co.uk is a **ccTLD** (Country Code Top Level Domain)

## Task3: Record Types

- The type of record used to advise where to send email is : **MX** Ex: tryhackme.com -> MX record show: alt1.aspmx.l.google.com

- The record who handle IPv6 address is : **AAAA** conversely, A record handle IPv4 address.

## Task4: Making a Request:

- The field who specify how long a DNS record should be cached for is : **TTL** (Time to live value)

- Our ISP usually provide **Recursive** DNS Server but you can choose your own Server if you want to.

- The server who holds all the record for a domain is: **Authoritative** server.

## Task5: Practical

- To have the CNAME, change on the top of the page the value "DNS Type" by "CNAME" and write "shop" as subdomain
the result is: **shops.myshopify.com**

- Do the same, but put TXT value, and no subdomain, the flag is : **THM{7012BBA60997F35A9516C2E16D2944FF}**

- The priority value of the MX record is 30

- The IP address of the A record of www.website.thm is : 10.10.10.10
