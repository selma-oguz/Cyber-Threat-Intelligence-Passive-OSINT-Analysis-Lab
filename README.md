# Cyber Threat Intelligence & Passive OSINT Analysis Lab

**Report ID:** CTI-OSINT-001

**Date:** 29 September 2026

**Analyst:** Selma Oguz

**TLP (Traffic Light Protocol):** GREEN (Cleared for public portfolio/educational sharing)

Disclaimer & Source:
The organizations, entities, and events described in this report are entirely fictional and were analyzed strictly for educational purposes. This analysis is based on a simulated training scenario.
Source: Centri - Introduction to Dark Web Operations

## 1. Executive Summary

This report details a passive reconnaissance and Open-Source Intelligence (OSINT) exercise conducted within the Tor network. The primary objective was to observe the operational security (OPSEC) practices, communication vectors, and logistical footprints of high-volume threat actors operating in dark web marketplaces. The analysis profiles a specific vendor purportedly based in the United Kingdom, focusing on their supply chain methodologies and digital footprint.

## 2. Operational Environment & OPSEC Setup

To ensure complete isolation and prevent operational blowback or accidental exposure, the investigation was strictly contained within a secure laboratory environment:

* **Virtualization:** Hardened Linux distribution deployed on a Type-2 Hypervisor with no host-integration (drag-and-drop and shared folders disabled).

* **Network Anonymity:** Traffic routed exclusively through the Tor network. No personal VPNs or clear-net credentials were intermingled with the session to prevent traffic correlation.

* **Engagement Rules:** Strictly passive observation (Passive OSINT). No active engagement, purchases, or account creations that would leave a digital footprint on the threat actor's infrastructure.

## 3. Threat Actor Profiling

Passive monitoring of a known illicit marketplace identified a high-tier vendor exhibiting characteristics of a large-scale operator.

* **Claimed Operating Region:** United Kingdom

* **Primary Commodity:** Illicit Narcotics

* **Market Footprint:** High trust-rating vendor indicating established logistics and a high volume of successful illicit transactions.

## 4. Observed Tactics, Techniques, and Procedures (TTPs)

An analysis of the vendor’s public manifesto, shipping rules, and buyer requirements revealed several mature operational patterns:

* **Secure Communications:** Strict enforcement of PGP (Pretty Good Privacy) encryption for all buyer correspondence. The vendor explicitly ignores clear-text shipping addresses, indicating high OPSEC awareness.

* **Financial Obfuscation:** Transactions are exclusively settled via privacy-focused cryptocurrencies (e.g., Monero/XMR) to bypass the traceability of transparent ledgers like Bitcoin.

* **Logistics & "Stealth" Shipping:** Utilization of domestic postal services employing advanced stealth packaging techniques (e.g., vacuum sealing, Mylar bags, and decoy commercial packaging) to bypass traditional customs and postal scanning.

## 5. Analyst Assessment

The profiled vendor demonstrates a high degree of operational maturity, characteristic of advanced threat actors operating within illicit physical supply chains. Their strict reliance on asymmetric encryption (PGP) and privacy coins (XMR) indicates a clear understanding of modern law enforcement tracking capabilities. This exercise successfully demonstrated the ability to safely navigate isolated networks, conduct passive threat profiling, and document illicit TTPs without compromising analyst OPSEC.
