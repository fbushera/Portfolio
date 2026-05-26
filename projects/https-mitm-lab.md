# HTTPS Man-in-the-Middle Lab

## Overview
A cybersecurity lab demonstrating how HTTPS can be compromised when a trusted Certificate Authority is abused in a controlled environment.

## Problem
HTTPS is designed to protect confidentiality and integrity, but that protection depends heavily on browser trust in Certificate Authorities. This lab explored what happens when a malicious or compromised trusted CA is introduced.

## My Role
I configured and tested the MITM portion of the lab, including domain mapping, browser trust configuration, and proxy-based traffic observation.

## Technologies
- Docker
- Linux
- Firefox certificate settings
- TLS / HTTPS
- Custom Certificate Authority
- MITM proxy

## Key Work Completed
- Configured Docker-based client, server, and proxy environment
- Generated and trusted a lab Certificate Authority
- Used `/etc/hosts` to map a domain to the MITM proxy
- Observed decrypted HTTPS requests in the proxy
- Explained why CA trust is central to HTTPS security

## Skills Demonstrated
- TLS/HTTPS fundamentals
- Certificate trust chain concepts
- Linux networking and host mapping
- Security lab documentation
- Controlled attack simulation and analysis

## Status
Case study documented. Screenshots or lab report excerpts can be added later if appropriate.
