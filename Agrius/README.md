**NAME:**  
Agrius

**Alias**  
AMERICIUM, Spectral Kitten, Pink Sandstorm, Agonizing Serpens, SharpBoys, BlackShadow, blackshadow
  
**Description**:   
The Agrius is an APT group discovered and named by foreign network security company SentinelOne. This group is suspected to have Iranian background. It attacks by using malware to maliciously erase victim system data, and disguises its attack behavior as a ransom attack. This group It has been consistently active since 2020, and the group’s focus seems to have shifted from the Middle East to individuals or groups such as Israeli national people and corporate institutions. The motivation for the group's attacks seems to be mainly financial, but in fact the group often uses web shells for espionage and secret theft operations.
The Agrius group usually exploits known WEB application vulnerabilities to conduct attacks, or uses SQL injection attacks to gain control of the target network. After gaining access to the target network, the attacker will upload a web shell. In most cases, this web shell is a variant of ASPXSpy. Attackers will use this web shell to achieve lateral movement under the target network. In addition, the Agrius group uses a custom backdoor written in .Net called "IPsec Helper." It is worth noting that most of the group’s attacks exploit the IP of VPN services, the most common of which is ProtonVPN. In addition, the group will also maliciously erase computer system files in the environment where the attack target is located, disguised as a ransomware attack.
Since around November 2020, the group has launched attacks against the Israeli country, deploying malicious data erasure software DEADWOOD, destroying computer MBR partitions and erasing files, and then requiring victims to pay a ransom in order to confirm the true identity of the victims and the analysis team. Purpose of attention. By launching such attacks, the group is suspected to be aiming to weaken the operational capabilities of the attacked party.

**References**:  
https://www.cyclonis.com/zh-hans/newly-spotted-agrius-apt-targets-entities-in-israel-and-uae/
https://www.cyclonis.com/newly-spotted-agrius-apt-targets-entities-in-israel-uae/
https://therecord.media/new-iranian-threat-actor-targets-israel-with-wipers-disguised-as-ransomware/
https://unit42.paloaltonetworks.com/agonizing-serpens-targets-israeli-tech-higher-ed-sectors/
https://assets.sentinelone.com/sentinellabs/evol-agrius
https://www.welivesecurity.com/2022/12/07/fantasy-new-agrius-wiper-supply-chain-attack/
https://beta.darkreading.com/threat-intelligence/new-iranian-threat-actor-using-ransomware-wipers-in-destructive-attacks
https://threatpost.com/agrius-wiper-attacks-israeli-targets/166474/


