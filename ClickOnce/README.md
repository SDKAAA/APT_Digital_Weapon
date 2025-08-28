**NAME:**  
ClickOnce
  
**Alias**  
APT-Q-14, 旺刺, ClickOnce, APT-C-47
  
**Description**:   
The earliest attack activities of the APT-Q-14 (旺刺) group can be traced back to 2018. Originating from South Korea, the group primarily targets entities and individuals associated with the Korean Peninsula. In the first half of their attacks, they used multiple C# modules, and in the latter half, they employed Go language modules. They are also the only known group to use ClickOnce technology in their attack activities. The group carries out attacks by sending phishing emails to victims, which contain disguised security plugin upgrade links. When the victim clicks on the disguised upgrade link, they are directed to a fake plugin webpage where they click on the installation link to download and install the ClickOnce deployment file ( *.appref-ms ). This file contains the address of the malicious ClickOnce program, and after downloading and installation, it deceives the user into believing that the security module update is complete. At this point, the attacker successfully infiltrates and establishes persistence on the target host.
Since 2019, the proportion of open-source intelligence related to the Darkhotel group's activities has decreased year by year. At the same time, several attack clusters with backgrounds from the Korean Peninsula and different tactics and techniques have appeared in the terminals of government and enterprises. We classified these attack clusters based on their characteristics and target industries, naming them APT-Q-11 (虎木槿), APT-Q-12 (伪猎者), APT-Q-14 (旺刺), APT-Q-15, and UTG-Q-005. After five years of continuous tracking, we found that there is overlap between these groups, and we believe that these attack clusters are all subsets of the former Darkhotel.
APT-Q-14 delivered a 0day vulnerability targeting the Android platform in 2022-2023, with the trigger logic similar to that on the Win platform. It exploits an XSS vulnerability in the email structure parsed by the app to call internal interfaces, thereby executing the malicious code in the attachment. Finally, it reads the email data from the corresponding app on the phone, packages it with tar, and uploads it to the C2 domain via the nc command executed by toybox. The attackers aimed to gather intelligence related to China-North Korea trade.

  
**References**:  
https://www.wangan.com/articles/2306#8bf6bf
https://mp.weixin.qq.com/s/h_MUJfa3QGM9SqT_kzcdHQ
https://ti.qianxin.com/blog/articles/operation-deviltiger-0day-vulnerability-techniques-and-tactics-used-by-apt-q-12-disclosed-cn/
