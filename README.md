# CIS-Hardening-Windows-2022-Server By Credit:eneerge![hardening output](https://github.com/Yuta-Okkotsuu/CIS-Hardening-Windows-2022-Server/assets/152240150/9a16adb8-83e8-4594-acdb-f978028feb76)

Steps to run the script
1) Place the code in the Desktop

![image](https://github.com/Yuta-Okkotsuu/CIS-Hardening-Windows-2022-Server/assets/152240150/c42eadd3-94ad-48da-b5ef-fd6d779684bc)

2) Run the script in powershell

![image](https://github.com/Yuta-Okkotsuu/CIS-Hardening-Windows-2022-Server/assets/152240150/43032ea2-281d-4dc1-ab3f-95c4a3610c91)

3) After running the script the outputs will produce automatically

![image](https://github.com/Yuta-Okkotsuu/CIS-Hardening-Windows-2022-Server/assets/152240150/b3c3b888-5898-4d2c-b586-d613193bebc5)

Contents in the Output files:

PolicyChangesMade: Documents only the modifications implemented by the script, excluding unchanged CIS settings.

PolicyResult: Details the comprehensive outcomes of each CIS setting, including "Before" and "After" states, highlighting any altered settings with "Value changed" for easy tracking. These alterations are also noted in PolicyChangesMade.txt.

secedit_original: The file is a standard output from the 'secedit' command, a tool for setting and assessing Windows system security. It represents the settings before any security modifications are made by the CIS script. Typically used for security analysis and compliance, this file helps in adjusting the system's security settings, with its contents determining the strictness of the system's security measures.

secedit_final: The content of this file indicates the specific security configurations applied to a Windows system after the CIS script has made changes. These settings dictate how stringent or relaxed the system's security measures are post-script execution.

CommandReport: Logs the outputs from executing Windows commands to import the local security policy.

PoliciesApplied: Captures the policies outlined in the $ExecutionList.






