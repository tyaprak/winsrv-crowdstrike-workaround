# winsrv-crowdstrike-workaround
Latest update of Crowd Strike caused serious damage to Windows Servers. A quick solution proposal for the situation


1- Boot Windows in Safe Mode

2- Rename this sys file: "C:\Windows\system32\drivers\CrowdStrike\csagent.sys"

3- Navigate to the C:\Windows\System32\drivers\CrowdStrike directory

4- Locate the file matching “C-00000291*.sys”, and delete it.

5- Boot the host normally.


Please use this proposal at your own risk. Consider taking backup of your system or the files you edited.
