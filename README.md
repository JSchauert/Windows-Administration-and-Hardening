# Windows-Administration-and-Hardening

Deliverable for Task 1: Take a screenshot of all the GPOs created for this homework assignment. To find these, launch the Group Policy Management tool, select Group Policy Objects, and take a screenshot of the GPOs you've created.


 
 

Deliverable for Task 2: Submit a screenshot of the different Account Lockout policies in Group Policy Management Editor. It should show the three values you set under the Policy and Policy Setting columns.
  

  

Deliverable for Task 3: Submit a screenshot of the different Windows PowerShell policies within the Group Policy Management Editor. Four of these should be enabled.
  




Deliverable for Task 4: Submit a copy of your enum_acls.ps1 script.
  
 
 
  

Deliverable for Bonus Task 5: Submit a screenshot of the contents of one of your transcribed PowerShell logs or a copy of one of the logs.

CONTENTS OF POWERSHELL LOG BELOW
**********************
Windows PowerShell transcript start
Start time: 20220512165241
Username: DESKTOP-SITPOTH\sysadmin
RunAs User: DESKTOP-SITPOTH\sysadmin
Configuration Name:
Machine: DESKTOP-SITPOTH (Microsoft Windows NT 10.0.19041.0)
Host Application: C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
Process ID: 8
PSVersion: 5.1.19041.1
PSEdition: Desktop
PSCompatibleVersions: 1.0, 2.0, 3.0, 4.0, 5.0, 5.1.19041.1
BuildVersion: 10.0.19041.1
CLRVersion: 4.0.30319.42000
WSManStackVersion: 3.0
PSRemotingProtocolVersion: 2.3
SerializationVersion: 1.1.0.1
**********************
**********************
Command start time: 20220512165258
**********************
PS C:\Users\sysadmin> enum_acls.ps1
**********************
Windows PowerShell transcript start
Start time: 20220512165258
Username: DESKTOP-SITPOTH\sysadmin
RunAs User: DESKTOP-SITPOTH\sysadmin
Configuration Name:
Machine: DESKTOP-SITPOTH (Microsoft Windows NT 10.0.19041.0)
Host Application: C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe
Process ID: 8
PSVersion: 5.1.19041.1
PSEdition: Desktop
PSCompatibleVersions: 1.0, 2.0, 3.0, 4.0, 5.0, 5.1.19041.1
BuildVersion: 10.0.19041.1
CLRVersion: 4.0.30319.42000
WSManStackVersion: 3.0
PSRemotingProtocolVersion: 2.3
SerializationVersion: 1.1.0.1
**********************
**********************
Command start time: 20220512165258
**********************
PS>CommandInvocation(Out-String): "Out-String"
>> ParameterBinding(Out-String): name="InputObject"; value="The term 'enum_acls.ps1' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again."
enum_acls.ps1 : The term 'enum_acls.ps1' is not recognized as the name of a cmdlet, function, script file, or operable
program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ enum_acls.ps1
+ ~~~~~~~~~~~~~
	+ CategoryInfo      	: ObjectNotFound: (enum_acls.ps1:String) [], CommandNotFoundException
	+ FullyQualifiedErrorId : CommandNotFoundException
enum_acls.ps1 : The term 'enum_acls.ps1' is not recognized as the name of a cmdlet, function, script file, or operable
program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ enum_acls.ps1
+ ~~~~~~~~~~~~~
	+ CategoryInfo      	: ObjectNotFound: (enum_acls.ps1:String) [], CommandNotFoundException
	+ FullyQualifiedErrorId : CommandNotFoundException
enum_acls.ps1 : The term 'enum_acls.ps1' is not recognized as the name of a cmdlet, function, script file, or operable
program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ enum_acls.ps1
+ ~~~~~~~~~~~~~
	+ CategoryInfo      	: ObjectNotFound: (enum_acls.ps1:String) [], CommandNotFoundException
	+ FullyQualifiedErrorId : CommandNotFoundException

**********************
Command start time: 20220512165344
**********************
PS C:\Users\sysadmin> cd Documents
**********************
Command start time: 20220512165351
**********************
PS C:\Users\sysadmin\Documents> .\enum_acls.ps1


	Directory: C:\Users\sysadmin\Documents


Path      	Owner              	Access
----      	-----              	------
20220506  	BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  FullControl...
20220512  	BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  FullControl...
enum_acls.ps1 BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  FullControl...


	Directory: C:\Users\sysadmin\Documents\20220506


Path                                                          	Owner              	Access
----                                                          	-----              	------
PowerShell_transcript.DESKTOP-SITPOTH.EckBEtjg.20220506181545.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH.EckBEtjg.20220506181545.zip BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH.fUHbfDGU.20220506183600.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH.L+TD6LsB.20220506182309.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH.nilUCKBu.20220506182257.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...


	Directory: C:\Users\sysadmin\Documents\20220512


Path                                                          	Owner              	Access
----                                                          	-----              	------
PowerShell_transcript.DESKTOP-SITPOTH.CPqQbCKQ.20220512164751.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH.WwOHGe4V.20220512164129.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...
PowerShell_transcript.DESKTOP-SITPOTH._pvwqwu5.20220512165240.txt BUILTIN\Administrators NT AUTHORITY\SYSTEM Allow  ...


**********************
Command start time: 20220512165508
**********************
PS C:\Users\sysadmin\Documents> ls


	Directory: C:\Users\sysadmin\Documents


Mode             	LastWriteTime     	Length Name
----             	-------------     	------ ----
d-----      	5/6/2022   6:51 PM            	20220506
d-----     	5/12/2022   4:52 PM            	20220512
-a----     	5/12/2022   4:49 PM        	128 enum_acls.ps1


**********************
Command start time: 20220512165521
**********************
PS C:\Users\sysadmin\Documents> cd 20220512
**********************
Command start time: 20220512165523
**********************
PS C:\Users\sysadmin\Documents\20220512> ls


	Directory: C:\Users\sysadmin\Documents\20220512


Mode             	LastWriteTime     	Length Name
----             	-------------     	------ ----
-a----     	5/12/2022   4:49 PM     	152280 PowerShell_transcript.DESKTOP-SITPOTH.CPqQbCKQ.20220512164751.txt
-a----     	5/12/2022   4:45 PM     	157582 PowerShell_transcript.DESKTOP-SITPOTH.WwOHGe4V.20220512164129.txt
-a----     	5/12/2022   4:53 PM       	4588 PowerShell_transcript.DESKTOP-SITPOTH._pvwqwu5.20220512165240.txt




