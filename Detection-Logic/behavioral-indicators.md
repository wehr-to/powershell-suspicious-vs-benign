These characteristics can be modeled into detection logic:

Rule Logic > Detection Pattern

Base64 payload detection = Command contains -enc and > 100 characters
LOLBin execution = powershell.exe launched by mshta.exe, regsvr32.exe, rundll32.exe
Internet-based execution = Use of IEX, DownloadString, Invoke-WebRequest to external domains
Registry persistence = Writes to HKCU:\Software\Microsoft\Windows\CurrentVersion\Run or RunOnce
Obfuscation score = Presence of [char], .join, multiple nested Invoke-Expression calls
Suspicious file location = .ps1 script run from Downloads, Temp, or %APPDATA%

