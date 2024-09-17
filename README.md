# fkxdr-mindmaps for exploiting and bypassing EDR/XDR

![image](https://github.com/user-attachments/assets/a2abcdbb-f9fa-42d6-a61c-6de985be283f)

This is a small place about hosting my personal techniques needed for real-life scenarios, focused on EDR and XDR.
  
```mermaid
flowchart TD
    MDE[ Microsoft Defender for Endpoint ]
    MDE --> MDEENUM[ Enumerate Microsoft Defender ]
    MDEENUM --> | fkmde.ps1 | MDEVULN[ Vulnerable Configurations, ASR Rules or Exclusions ]
    MDE --> | ps1-obfuscator.ps1 | MDEBPASS[ Defender Bypass ]
    
    MDEVULN --> MDEEXPL[ Defender Exploitable PoCs]
    MDEBPASS --> MDEEXPL[ Defender Exploitable PoCs]

    MDE --> | Smart Screen testing URL | MDESSCR[ Find disabled Smart Screen Settings ]

    APP[ Microsoft AppLocker ]
```

## Table of Contents
Enumeration of MDE
* [Smart Screen](#Smart-Screen)  

## Enumeration of MDE
### Smart Screen

A collection of smart screen test links.

* Smart Screen Test: https://commandcontrol.smartscreentestratings.com/  
* Smart Screen Test: https://smartscreentestratings2.net  
* Smart Screen Phishing: https://demo.smartscreen.msft.net/phishingdemo.html  
* Smart Screen Malware: https://demo.smartscreen.msft.net/other/malware.html  
* Smart Screen Untrusted: https://demo.smartscreen.msft.net/download/malwaredemo/freevideo.exe  
* Smart Screen Exploit: https://demo.smartscreen.msft.net/other/exploit.html  
