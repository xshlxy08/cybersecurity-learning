🌐DNS in Detail
🔗[TryHackMe — DNS in Detail](https://tryhackme.com/room/dnsindetail)
🧠Notes
🔹DNS
DNS=Domain Name System
Domain name→IP address
🏛️Domain Hierarchy
TLD=Top-Level Domain
Domain hierarchy→TLD→Domain→Subdomain
📡DNS Records
A→IPv4
AAAA→IPv6
CNAME→Alias
MX→Email
TXT→Text
NS→Name Server
🔄DNS Request Flow
Client→Recursive DNS→Root→TLD→Authoritative DNS
🖥️DNS Servers
Recursive DNS→Queries DNS information
Root DNS→Directs queries to TLD
TLD DNS→Directs queries to authoritative server
Authoritative DNS→Provides domain records
⏳TTL
TTL→Controls DNS caching duration
Caching→Reduces repeated DNS queries

❓Questions & Answers
📌Task 1
Q1:What does DNS stand for?
A:Domain Name System
🏗️Task 2
Q1:What is the maximum length of a subdomain?
A:63
Q2:Which of the following characters cannot be used in a subdomain (3 b _ -)?
A:_
Q3:What is the maximum length of a domain name?
A:253
Q4:What type of TLD is .co.uk?
A:ccTLD
📋Task 3
Q1:What type of record would be used to advise where to send email?
A:MX
Q2:What type of record handles IPv6 addresses?
A:AAAA
🔍Task 4
Q1:What field specifies how long a DNS record should be cached for?
A:TTL
Q2:What type of DNS Server is usually provided by your ISP?
A:Recursive
Q3:What type of server holds all the records for a domain?
A:Authoritative
🧪Task 5
Q1:What is the CNAME of shop.website.thm?
A:shops.myshopify.com
Q2:What is the value of the TXT record of website.thm?
A:THM{7012BBA60997F35A9516C2E16D2944FF}
Q3:What is the numerical priority value for the MX record?
A:30
Q4:What is the IP address for the A record of www.website.thm?
A:10.10.10.10
🛡️Security Insight
DNS→Helps understand domain infrastructure and services
💡Remember
A→IPv4 | AAAA→IPv6 | CNAME→Alias | MX→Mail | TXT→Text
