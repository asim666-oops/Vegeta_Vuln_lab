# Vegeta_Vuln_lab
# Overview

This lab focuses on core penetration testing concepts, including:
* Network reconnaissance
* Web exploitation
* Hidden directory & content discovery
* OSINT-based decoding (CyberChef, Morse)
* SSH credential extraction
* Privilege escalation via misconfigured system files
* Full system takeover

# TOOLS USED
## Enumeration
   * arp-scan
   * nmap
   * gobuster
   * Nikto

## Exploitation
  * Web directory analysis
  * CyberChef decoding
  * Morse code decoder
  * SSH login

## Privilege Escalation
  * LinPEAS
  * Writable /etc/passwd exploit
  * Custom root user injection

## Post-Exploitation
  * SSH (user pivoting)
  * Reading system files
  * Gaining full root access

# Conclusion

This lab reinforces critical penetration testing abilities required in real-world assessments:
* Effective enumeration of services and hidden directories
* Decoding multi-layered OSINT clues
* Extracting valid credentials through unconventional formats (audio → Morse)
* Gaining SSH access using discovered credentials
* Privilege escalation using insecure file permissions
* Achieving complete system compromise through methodical steps
