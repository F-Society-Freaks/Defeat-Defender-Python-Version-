# Defeat-Defender
## Powerfull python script  To Disable Windows Defender,Firewall,Smartscreen And Execute the payload 
## Usage :
## 1. Edit Defeat-Defender.py on line number 42 and replace the direct url of your payload
## 2 Run the script "Defeat-Defender.py" . It will ask for Admin Permission.If permission Granted The script will work Silently without console windows...
## 3. After it got admin permission it will disable defender 
### 1. PUAProtection 
### 2. Automatic Sample Submission
### 3. Windows FireWall
### 4. Windows Smart Screen(Permanently)
### 5. Disable Quickscan
### 6. Add exe file  to exclusions in defender settings
### 7. Disable Ransomware Protection
## Virus Total Result::
<p align="left">
   <img src="https://raw.githubusercontent.com/swagkarna/Defeat-Defender-Python-Version-/main/Screenshot%20(47).png" width=750px height=500px>
   </p>
### Bypasssing Windows-Defender Techniques :
## Recently Windows Introduced new Feature called "Tamper Protection".Which Prevents the disable of real-time protection and modifying defender registry keys using powershell or cmd...If you need to disable real-time protection you need to do manually....But i have done some trick to run our payload without triggering defender even "real-time protection" turned on
## Behind The Scenes :
## When Batch file is executed it ask for admin permissions.After getting admin privileage it starts to disable windows defender real time protectin , firewall , smartscreen and starts downloading our backdoor from server and it will placed in startup folder.
## The backdoor will be executed after it has downloaded from server..And will be executed after 25 seconds

## Compile to Exe ::
### To compile python file to exe just run compiletoexe.bat...
# Discalimer :
## Use this only for educational Purpose...Love you Guys Bye.
