This script was developed by Sneakysecdoggo. The original script can be found https://github.com/Sneakysecdoggo/Wynis 
before executing the script run the following command in powershell with administrator privilege 


Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine


Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process


after this run the following command and wait for the report to be executed 
For Auditing windows 10 run following command inside Windows10 folder 
C:> .\Windows10.ps1
For Auditing AD server run following command inside windows AD folder 
C:>.\WindowsAD.ps1
For Auditing Normal windows server run following command inside windowsserver folder
C:>.\windows_server.ps1
