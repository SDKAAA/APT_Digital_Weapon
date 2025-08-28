**NAME:**  
MUT-9332
  
**Description**:   
MUT-9332 is a high-risk threat group targeting Solidity developers on the Windows platform. They uploaded malicious extensions disguised as "syntax checkers" or "vulnerability scanners" to the VS Code Marketplace. After users installed the extensions, they downloaded and executed hidden payloads such as myau.exe through PowerShell, disabling Windows Defender, tampering with the firewall, and ultimately stealing cryptocurrency wallet credentials and sensitive data from applications such as Chrome, Brave, and Discord. The extensions also have persistence and anti-analysis capabilities, causing data leakage and financial loss risks in the blockchain development community.
  
**References**:  
https://rewterz.com/threat-advisory/malware-alert-mut-9332-infects-solidity-devs-through-vs-code-active-iocs
