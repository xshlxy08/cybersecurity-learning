🌐 **DNS in Detail**

🔗 [TryHackMe — DNS in Detail](https://tryhackme.com/room/dnsindetail)

🧠 **Notes**

🔹 **DNS**

DNS = Domain Name System

A system that translates human-readable domain names into network addresses.


🏛️ **Domain Hierarchy**

Domains are organised into different levels.

TLD → Domain → Subdomain


📡 **DNS Records**

DNS records store different types of information about a domain.

Each record type is used for a specific purpose.


🔄 **DNS Request Flow**

A DNS lookup passes through multiple levels of DNS infrastructure.

Client → DNS Resolver → Root → TLD → Authoritative


🖥️ **DNS Servers**

Different DNS servers perform different roles during DNS resolution.

They handle queries, delegation and the final domain information.


⏳ **TTL & Caching**

DNS responses can be stored temporarily in a cache.

Caching helps reduce repeated DNS queries and improve response time.


❓ **Questions & Answers**

📌 **Task 1**

**Q1:** What does DNS stand for?

**A:** Domain Name System


🏗️ **Task 2**

**Q1:** What is the maximum length of a subdomain?

**A:** 63

**Q2:** Which of the following characters cannot be used in a subdomain (3 b _ -)?

**A:** _

**Q3:** What is the maximum length of a domain name?

**A:** 253

**Q4:** What type of TLD is .co.uk?

**A:** ccTLD


📋 **Task 3**

**Q1:** What type of record would be used to advise where to send email?

**A:** MX

**Q2:** What type of record handles IPv6 addresses?

**A:** AAAA


🔍 **Task 4**

**Q1:** What field specifies how long a DNS record should be cached for?

**A:** TTL

**Q2:** What type of DNS Server is usually provided by your ISP?

**A:** Recursive

**Q3:** What type of server holds all the records for a domain?

**A:** Authoritative


🧪 **Task 5**

**Q1:** What is the CNAME of shop.website.thm?

**A:** shops.myshopify.com

**Q2:** What is the value of the TXT record of website.thm?

**A:** THM{7012BBA60997F35A9516C2E16D2944FF}

**Q3:** What is the numerical priority value for the MX record?

**A:** 30

**Q4:** What is the IP address for the A record of www.website.thm?

**A:** 10.10.10.10


🛡️ **Security Insight**

DNS is useful for understanding domain infrastructure, services and how systems communicate through domain names.


💡 **Remember**

DNS resolution involves domain hierarchy, DNS records, DNS servers and caching.
