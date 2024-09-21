# Malicious-IPs-Feed

This repository contains a curated, continuously updated list of malicious IP addresses from multiple trusted threat intelligence sources. It serves as a feed for cybersecurity professionals, researchers, and network administrators, enabling them to block or monitor known malicious IPs to protect their systems from attacks.

## Overview

The **Malicious-IPs-Feed** repository compiles IP addresses from various reputable sources. These sources include, but are not limited to:

- **AFTA (Iran Government IT Security)**

Each feed is regularly processed, cleaned, and merged into a single list of malicious IPs. This list is designed to assist in identifying and mitigating threats such as:

- **Malware**: IPs associated with malware distribution.
- **Phishing**: IPs used for phishing attempts.
- **Botnets**: IPs involved in botnet communications.
- **DDoS Attacks**: IPs used to launch distributed denial-of-service (DDoS) attacks.

## Files and Structure

The repository contains the following files:

- **[Source-Name]-Feed.txt**: Individual feeds from various sources, including AFTA and others.
- **README.md**: Documentation for the repository.

## How It Works

The IP addresses from each source are cleaned, deduplicated, and verified to reduce false positives.

The feed can be integrated into your firewall rules, intrusion detection systems (IDS), or other security tools.

## How to Use

### Download the Feed:

- For more detailed information on individual feeds, see the respective **[Source-Name]-Feed.txt** files.

### Integrate the Feed:

- Integrate the malicious IP feed into your security systems such as firewalls, SIEM, or IDS to automatically block or monitor traffic from these IPs.

### Stay Updated:

- Regularly pull updates from the repository to ensure you have the latest data on malicious IPs.

## Contributions

Contributions are welcome. If you have additional feeds or IPs to contribute, please submit a pull request with the new data. Ensure that all submitted IPs are verified and confirmed to be involved in malicious activities.

## Disclaimer

This repository is provided for educational and research purposes only. Use of the malicious IPs is at your own risk, and the maintainers of this repository are not liable for any misuse or damage caused by the integration of these IP addresses into your security systems.
