> בס״ד
<div align="center">

<h2 align="center"><a href="https://github.com/Anlominus">⚜️ Aภl๏miuภuຮ ⚜️</a></h2>

<img align="center" width="100" src="https://user-images.githubusercontent.com/51442719/172729066-1293d382-4a31-4f03-8c23-ab0ea5f611a0.png">

⫷ [**`HacKingPro`**](https://github.com/Anlominus/HacKingPro) ⫸
<br>
⫷ [**`TryHackMe`**](https://github.com/Anlominus/TryHackMe) | [**`KoTH`**](https://github.com/Anlominus/TryHackMe/tree/main/King%20of%20the%20Hill/KoTH) ⫸ 
<br>
⫷ [**`Privilege-Escalation`**](https://github.com/Anlominus/Privilege-Escalation)⫸ 
<br>
⫷ [**`ScanPro`**](https://github.com/Anlominus/ScanPro) | [**`Linfo`**](https://github.com/Anlominus/Linfo) | [**`Diablo`**](https://github.com/Anlominus/Diablo) ⫸ 
<br>
⫷ [**`Offensive-Security`**](https://github.com/Anlominus/Offensive-Security) | [**`PenTest`**](https://github.com/Anlominus/PenTest) ⫸
<br>
⫷ [**`Goals`**](https://github.com/Anlominus/Goals) | [**`Studies`**](https://github.com/Anlominus/Studies) | [**`HacKing`**](https://github.com/Anlominus/HacKing) | [**`AnyTeam`**](https://github.com/Anlominus/AnyTeam) ⫸
<br>

</div>
  
---
 
  
<div align="center">

# [`Privilege-Escalation`](https://github.com/Anlominus/Privilege-Escalation) ~> [`Windows-PrivEsc`](https://github.com/Anlominus/Windows-PrivEsc)
[**`Tools`**](https://github.com/Anlominus/Windows-PrivEsc/tree/main/GiTools#linux-privesc--gitools) | [**`Cheat Sheets`**](https://github.com/Anlominus/Windows-PrivEsc/tree/main/Cheat%20Sheets#linux-privesc--cheat-sheets) | [`Notes`](./Notes)  | [`Checklists`](./Checklists)
  
</div>

---

# Cheat Sheets

## [Cheat-Sheet---Active-Directory](https://github.com/drak3hft7/Cheat-Sheet---Active-Directory)
- This cheat sheet contains common enumeration and attack methods for Windows Active Directory with the use of powershell.


## [Active Directory Exploitation Cheat Sheet](https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet)
- This cheat sheet contains common enumeration and attack methods for Windows Active Directory.

## [Active Directory Cheat Sheet](https://github.com/Integration-IT/Active-Directory-Exploitation-Cheat-Sheet)
- This repository contains a general methodology in the Active Directory environment. 
- It is offered with a selection of quick commands from the most efficient tools based on Powershell, C, .Net 3.5 and .Net 4.5.

## [Exchange-AD-Privesc](https://github.com/gdedrouas/Exchange-AD-Privesc)
- This repository provides a few techniques and scripts regarding the impact of Microsoft Exchange deployment on Active Directory security. 
- This is a side project of AD-Control-Paths, an AD permissions auditing project to which I recently added some Exchange-related modules.

---

# Tools

## [ActiveDirectoryAttackTool](https://github.com/The-Viper-One/ActiveDirectoryAttackTool) 
- ADAT is a small tool used to assist CTF players and Penetration testers with easy commands to run against an Active Directory Domain Controller. 
- This tool is is best utilized using a set of known credentials against the host.

## [Phant0m](https://github.com/hlldz/Phant0m) | Windows Event Log Killer
> ![image](https://user-images.githubusercontent.com/51442719/179116846-1f44d88c-8724-4726-81b6-6786c6f73c51.png)
- Svchost is essential in the implementation of so-called shared service processes, where a number of services can share a process in order to reduce resource consumption. 
- Grouping multiple services into a single process conserves computing resources, and this consideration was of particular concern to NT designers because creating Windows processes takes more time and consumes more memory than in other operating systems, e.g. in the Unix family.
<br>

- This means briefly that; On Windows operating systems, svchost.exe manages the services and services are actually running under svchost.exe’s as threads.
- Phant0m targets the Event Log service and finding the process responsible for the Event Log service, it detects and kills the threads responsible for the Event Log service. 
- Thus, while the Event Log service appears to be running in the system (because Phant0m didn't kill process), it does not actually run (because Phant0m killed threads) and the system does not collect logs.

## [SpookFlare](https://github.com/hlldz/SpookFlare) 
> ![image](https://user-images.githubusercontent.com/51442719/179117084-82a15257-492d-4c0a-9d7a-4f86efcc6ce2.png)
> - ### Loader, dropper generator with multiple features for bypassing client-side and network-side countermeasures.
> - SpookFlare has a different perspective to bypass security measures and it gives you the opportunity to bypass the endpoint countermeasures at the client-side detection and network-side detection. <br> SpookFlare is a loader/dropper generator for Meterpreter, Empire, Koadic etc. <br> SpookFlare has obfuscation, encoding, run-time code compilation and character substitution features. <br> So you can bypass the countermeasures of the target systems like a boss until they "learn" the technique and behavior of SpookFlare payloads. <br> <br>
> - Obfuscation
> - Encoding
> - Run-time Code Compiling
> - Character Substitution
> - Patched Meterpreter Stage Support
> - Blocked powershell.exe Bypass

## [Winpayloads](https://github.com/nccgroup) Undetectable Windows Payload Generation with extras Running on Python2.7
> ![image](https://user-images.githubusercontent.com/51442719/179118345-b5ce3947-f432-4f8f-a155-75757cdb2c0b.png)

## [RedSnarf](https://github.com/nccgroup/redsnarf) is a pen-testing / red-teaming tool for Windows environments
> - ### RedSnarf is a pen-testing / red-teaming tool by Ed Williams for retrieving hashes and credentials from Windows workstations, servers and domain controllers using OpSec Safe Techniques.

## [BloodyAD](https://github.com/CravateRouge/bloodyAD) Framework
> - ### BloodyAD is an Active Directory Privilege Escalation Framework, it can be used manually using bloodyAD.py or automatically by combining pathgen.py and autobloody.py.

## [CheeseTools](https://github.com/klezVirus/CheeseTools)
> - ### Self-developed tools for Lateral Movement/Code Execution
> - ![image](https://user-images.githubusercontent.com/51442719/179422488-f4760779-49b2-4ab5-bc92-efd1457668fd.png)

---

- [How to Upgrade Command Shell to Meterpreter](https://www.hackingarticles.in/command-shell-to-meterpreter/)
- [Win Brute Logon (Proof Of Concept)](https://github.com/DarkCoderSc/win-brute-logon)
*   [PayloadsAllTheThings - Windows Privilege Escalation](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md)
*   [Priv2Admin - Abusing Windows Privileges](https://github.com/gtworek/Priv2Admin)
*   [RogueWinRM Exploit](https://github.com/antonioCoco/RogueWinRM)
*   [Potatoes](https://jlajara.gitlab.io/others/2020/11/22/Potatoes_Windows_Privesc.html)
*   [Decoder's Blog](https://decoder.cloud/)
*   [Token Kidnapping](https://dl.packetstormsecurity.net/papers/presentations/TokenKidnapping.pdf)
*   [Hacktricks - Windows Local Privilege Escalation](https://book.hacktricks.xyz/windows-hardening/windows-local-privilege-escalation)

---

## [Microsoft-Activation-Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts) Microsoft Activation Scripts (MAS):
#### A collection of scripts for activating Microsoft products using HWID / KMS38 / Online KMS activation methods with a focus on open-source code, fewer antivirus detection and user-friendliness.

---

## [Ghostpack-CompiledBinaries](https://github.com/r3motecontrol/Ghostpack-CompiledBinaries) Compiled Binaries for Ghostpack (.NET v4.0)

## [SharpCollection](https://github.com/Flangvik/SharpCollection) Nightly builds of common C# offensive tools, fresh from their respective master branches built and released in a CDI fashion using Azure DevOps release pipelines.


