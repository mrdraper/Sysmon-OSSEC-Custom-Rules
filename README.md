# Sysmon & OSSEC Custom Rules

Extra rules to detect the latest trend in malicious use of Powershell commands.
These rules detect most of the commands often used in attacks.

### Usage

For more information, see a blog post in which i detail the creation of these rules: https://thesecuritystoic.com/2017/06/customizing-endpoint-intrusion-detection-with-ossec-and-sysmon/

Paste the rules in the local_rules.xml file in your OSSEC folder and restart:
./var/ossec/bin/ossec-control restart

### Extra 

Creator: The Security Stoic
Sources: Experience & Symantec Whitepaper: Increased use of Powershell in attacks

Feel free to use and tweak.
