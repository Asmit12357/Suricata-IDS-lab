# Setup Guide

## Environment
- IDS: Suricata
- Platform: Kali Linux (VM)

## Steps
1. Installed Suricata
2. Configured suricata.yaml
3. Added custom.rules
4. Ran Suricata in live and PCAP mode

## Commands

### Live Capture
sudo suricata -c configs/suricata.yaml -i eth0

### PCAP Analysis
sudo suricata -c configs/suricata.yaml -r test.pcap