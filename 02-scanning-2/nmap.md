# Nmap

{% file src="../.gitbook/assets/nmapcheatsheetv1.0.pdf" caption="SANS Nmap Cheat Sheet \(PDF\)" %}

**General Enumeration**  
  
`nmap -vv -Pn -A -sC -sS -T 4 -p- 10.0.0.1`   
Verbose, syn, all ports, all scripts, no ping   
  
`nmap -v -sS -A -T4 x.x.x.x`   
Verbose, SYN Stealth, Version info, and scripts against services.   
  
`nmap –script smb-check-vulns.nse –script-args=unsafe=1 -p445 [host]`    
Nmap Script to scan for vulnerable SMB servers – WARNING: unsafe=1 may cause knockover

