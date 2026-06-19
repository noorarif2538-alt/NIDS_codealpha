# NIDS using Snort - CodeAlpha Task 4

## Overview
Network Intrusion Detection System implemented using Snort. Created custom rules and generated test alerts to verify detection.

## Files
- `Local.rules` - Custom Snort rules 
- `Screenshots/` - Screenshots of rule config + alert logs
- `Report.pdf` - Task report
- `alert.log` - Snort alert output

## How to Run
1. Install Snort
2. Copy `Local.rules` to Snort rules directory  
3. Run: `snort -c /etc/snort/snort.conf -r traffic.pcap`
4. Check alerts in `/var/log/snort/alert`

## Submission
CodeAlpha Internship Task 4
