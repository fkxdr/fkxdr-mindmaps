# fkxdr-mindmaps for exploiting and bypassing EDR

![image](https://github.com/user-attachments/assets/a2abcdbb-f9fa-42d6-a61c-6de985be283f)

Hello friend, how are you?

This is a small place about hosting my personal techniques needed for real-life scenarios, focused on EDR and XDR.

#### Initial Defender Enumeration
[ ] Check if Microsoft Defender Antivirus is running with fkmde  
  
#### Smart Screen
[ ] Smart Screen Test: https://commandcontrol.smartscreentestratings.com/  
[ ] Smart Screen Test: https://smartscreentestratings2.net  
[ ] Smart Screen Phishing: https://demo.smartscreen.msft.net/phishingdemo.html  
[ ] Smart Screen Malware: https://demo.smartscreen.msft.net/other/malware.html  
[ ] Smart Screen Untrusted: https://demo.smartscreen.msft.net/download/malwaredemo/freevideo.exe  
[ ] Smart Screen Exploit: https://demo.smartscreen.msft.net/other/exploit.html  

```mermaid
flowchart TD
    MDE[ Microsoft Defender for Endpoint ]
    --> MDEFK[ fkmde.ps1 ]
    -->| Vulnerable Exclusions | MDEEX[ Exploit MDE Exclusions with PoC ]
    MDEFK -->| Vulnerable ASR | MDEC[ Exploit ASR with PoC ]
    MDE --> MDESC[ Smart Screen testing URL ]

    APP[ Microsoft AppLocker ]
```
