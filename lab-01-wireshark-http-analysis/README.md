# Lab 01 – HTTP Traffic Analysis (Wireshark)

## Objective
Analyze HTTP traffic and identify login credentials transmitted in cleartext.

## Tools Used
- Wireshark
- Kali Linux / Windows PCAP file

## Scenario
Captured network traffic was provided. The goal was to inspect packets and identify potential sensitive information exposure.

## Steps Performed
1. Applied HTTP filter
2. Followed TCP stream
3. Identified POST request
4. Extracted credentials from packet payload

## Findings
- Login credentials transmitted over HTTP
- No encryption used (security risk)

## Lessons Learned
- HTTP transmits data in cleartext
- Importance of HTTPS
- How to use Wireshark filters effectively