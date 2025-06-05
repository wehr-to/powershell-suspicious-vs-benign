# PowerShell Behavior Analysis: Tools Overview

This folder contains curated tooling to analyze, detect, and hunt suspicious PowerShell activity.

## Static & Script Analysis
- [PowerShell Script Analyzer (PSA)](https://github.com/PowerShell/PSScriptAnalyzer)
- Obfuscation detectors
- Base64 decoders

## Log-Based Detection
- Sysmon + custom config (Event IDs 1, 3, 13)
- Sigma detection rules for ELK, Splunk, or Sentinel
- PowerShell ScriptBlock Logging (Event ID 4104)

## Threat Intelligence
- VirusTotal, Hybrid Analysis
- Defender ATP query examples (KQL-based)

Each subfolder includes configurations, detection rule templates, or usage examples.


