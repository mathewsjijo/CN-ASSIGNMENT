# Assignment
Assignment 1
## Title
TCP/IP Protocol Stack & Communication Analysis for Spotify.com
## Objective
To analyze how Spotify utilizes the 4-layer TCP/IP stack, DNS, HTTPS, TCP, and CDNs to securely and efficiently deliver music streaming to millions of users
## Solution
Spotify leverages the 4-layer TCP/IP protocol stack—supported by DNS for IP resolution, HTTPS for encryption, and TCP with BBR congestion control for reliable delivery—to handle user authentication, metadata queries, and streaming sessions
## Output
When a user plays a track, the client resolves the domain via DNS, establishes a secure TCP/TLS connection, requests track metadata, and streams audio data chunks from the nearest CDN to local buffers.
## Conclusion
By integrating DNS resolution, TCP reliability, TLS security, and CDN caching across the TCP/IP stack, Spotify delivers fast, secure, and uninterrupted audio streaming globally.  
