---
layout: post
title: "Spring Blog 4 - DNS"
date: 2022-03-08 01:46:17 -700
categories: jekyll update
---

## What is DNS?
DNS is the abbreviation for Domain Name System, which is the phonebook of the Internet. The DNS has a list of domain names that are associated with the IP addresses. Every device connected to the internet has its own IP address. DNS servers make it easy for people to enter normal text into the browsers without having to keep a list of the IP address for every website they visit. DNS translates domain names to IP addresses so browsers can load Internet pages.

## Types of DNS Servers
First, DNS servers convert the domain names into IP addresses. There are three types of DNS servers:
- Authoritative Name Server: The authoritative name server is in the higher level servers in the DNS. It is authoritative because it holds the up-to-date information for the specific hostname.
- DNS Resolver: This server converts the hostname (human readable) into IP address (machine readable). It is responsible for tracking the IP addresses of the hostname. 
- DNS Root Server: Root servers are the DNS name servers that function in the root zone. The root zone is the stored record of queries. There are 13 root servers.

## Types of DNS Queries
DNS query is also the DNS request. It is a request from the user’s computer to ask for an IP address to a DNS server. There are three types of DNS queries: 
- Recursive query -  It is a request from a client for a website that must be responded to either the requested resource record or an error message if it cannot be found. 
- Iterative query - The DNS client will allow the DNS to return the best answer. If the server doesn’t have the IP address request, it forwards the request on to another DNS server. The user can request repeatedly to different DNS servers. 
- Non-recursive query - A query in which the DNS Resolver already knows the answer because it’s authoritative for the record or the record exists inside of its local cache.

![The process of DNS](/assets/images/dns-process.png)
