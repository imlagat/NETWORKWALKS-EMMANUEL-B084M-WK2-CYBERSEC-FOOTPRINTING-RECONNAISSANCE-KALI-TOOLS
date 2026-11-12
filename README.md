# NETWORKWALKS B084 – WEEK 2: WEB RECONNAISSANCE

# Cybersecurity & Penetration Testing Internship

This repository documents my Week 2 practical activities during the Networkwalks Cybersecurity Internship.

The focus was Web Reconnaissance using Kali Linux, exploring techniques used to gather publicly available information about a website and understand its digital footprint.

For the practical exercises, I used one domain as the reference target across the different reconnaissance activities. This helped me understand how different tools reveal different aspects of the same website.

# Learning Objectives

Understand the role of reconnaissance in penetration testing.

Explore DNS records and domain infrastructure.

Inspect HTTP response headers.

Understand Web Application Firewall detection.

Retrieve domain registration information.

Identify website technologies using WhatWeb.

Understand domain-to-IP address resolution.

Practical Exercises

# 1. DNS Enumeration

Objective: Gather information about the target domain's DNS infrastructure.

# Activities:

Examined available DNS records.

Explored A, MX, NS and TXT records.

Investigated associated subdomains.

Studied how DNS information reveals aspects of domain infrastructure.

Key Learning: DNS enumeration helps identify publicly available information about a domain and its associated services.

# 2. HTTP Header Inspection

Objective: Examine HTTP response headers to understand how the target web server communicates with clients.

# Activities:

Retrieved and inspected HTTP response headers.

Examined server response information.

Explored security-related headers such as Content-Security-Policy and Strict-Transport-Security.

Reviewed HTTP status codes.

Key Learning: HTTP headers can reveal useful information about server configurations and security policies.

# 3. Web Application Firewall (WAF) Detection

Objective: Explore techniques used to identify Web Application Firewalls protecting web applications.

# Activities:

Investigated indicators of WAF protection.

Examined HTTP responses for possible WAF-related information.

Studied how WAFs filter and monitor incoming web traffic.

Key Learning: WAF detection helps identify additional security layers protecting web applications.

# 4. WHOIS Lookup

Objective: Retrieve publicly available registration information associated with the target domain.

# Activities:

Examined domain registration records.

Investigated registrar and registration details.

Explored name server information.

Reviewed the role of WHOIS in domain footprinting.

Key Learning: WHOIS provides useful background information about domain registration and management.

# 5. Technology Fingerprinting with WhatWeb

Objective: Identify technologies and frameworks exposed by the target website.

# Activities:

Used WhatWeb to investigate website technologies.

Examined detected web technologies and server information.

Explored how technology fingerprinting supports security assessments.

Key Learning: Technology fingerprinting helps establish an understanding of the technologies behind a web application.

# 6. DNS Resolution

Objective: Understand how the target domain resolves to its corresponding IP address.

# Activities:

Performed domain-to-IP resolution checks.

Examined DNS lookup results.

Explored the relationship between domain names and IP addresses.

Key Learning: DNS resolution helps establish how domain names map to network addresses.

# Practical Evidence

Screenshots and command outputs from the exercises are organized in the following directories:

Exercise

# Screenshot Directory

DNS Enumeration

screenshots/dns

HTTP Header Inspection

screenshots/http-headers/

WAF Detection

screenshots/waf

WHOIS Lookup

screenshots/whois

WhatWeb Fingerprinting

screenshots/whatweb/

DNS Resolution

screenshots/dns-resolution/

# Challenges Encountered and Lessons Learned

During the practical exercises, I encountered several learning challenges:

Interpreting DNS records: Understanding the differences between DNS record types and the information each one provides required additional attention.

Understanding HTTP responses: Distinguishing ordinary server information from security-related headers was an important learning process.

WAF identification: WAF detection was not always straightforward because different security configurations can produce different response patterns.

WHOIS information limitations: Some domain registration details may be hidden through privacy protection services.

Technology fingerprinting: WhatWeb results required careful interpretation because not every technology used by a website is necessarily exposed.

Correlating findings: Connecting information from different tools to build a broader picture of one domain required understanding how DNS, web servers and application technologies relate.

# How I Addressed These Challenges

I focused on understanding the purpose of each tool, reviewing its output and comparing findings across the different exercises. This helped me appreciate that reconnaissance requires technical interpretation rather than simply executing commands.

# Key Takeaways

Reconnaissance is a fundamental phase of penetration testing.

DNS information can reveal important details about domain infrastructure.

HTTP headers provide insights into web server communication and security configurations.

WAFs provide an additional layer of web application protection.

WHOIS contributes to domain footprinting.

Technology fingerprinting helps identify exposed web technologies.

Findings from different reconnaissance techniques complement one another.

Reconnaissance results should be verified before drawing security conclusions.

# Tools and Technologies

Kali Linux

DNS Lookup Utilities

WHOIS

WhatWeb

HTTP Header Inspection Tools
