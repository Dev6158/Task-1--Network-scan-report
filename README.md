# Task-1--Network-scan-report
Performing network scan using nmap and wireshark for open ports.
Scan Results:
I performed a port scan using Nmap on the target 192.168.1.5 with the command nmap -sS 192.168.1.5. The result showed all 1000 scanned ports as closed, and no open ports were detected.
I verified the host was up and attempted a full port range scan (nmap -p- 192.168.1.5), but still found no open ports. This suggests either no services are running or a firewall is blocking access.
