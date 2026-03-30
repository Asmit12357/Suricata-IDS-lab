# Detection Analysis

## Rule Created
Custom ICMP detection rule was created to identify ping-based reconnaissance.

## Objective
Detect ICMP echo requests commonly used in network scanning.

## Attack Simulation
- Tool used: ping / reconnaissance scan
- Traffic generated from attacker machine to target

## Detection Evidence
- Alerts observed in eve.json
- Alerts confirmed in fast.log

## Key Fields Observed
- src_ip
- dest_ip
- alert.signature
- protocol: ICMP

## Outcome
Successfully detected ICMP-based reconnaissance traffic using custom Suricata rule.