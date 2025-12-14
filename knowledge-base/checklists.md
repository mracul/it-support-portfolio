# Troubleshooting Checklists (Templates)

Use these checklists as copyable templates. Keep each checklist concise so it fits on one page.

## Basic network troubleshooting
- Physical checks: [cable, link LED, port label]
- IP configuration: `ipconfig /all` — record IP/Gateway/DNS
- DNS test: `nslookup <host>` and `ping <host>`
- If needed: capture network traffic (Wireshark) and document capture file path

## User login checklist
- Verify username and domain
- Check account status: locked/disabled, password expired
- Check AD replication status and connectivity to DC
- Verify DNS resolution and time sync

## Printer checklist
- Confirm driver and queue presence on print server
- Verify port and IP; ping the printer
- Test print from server and client; check spooler service

