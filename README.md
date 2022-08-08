**About Nutoscan**


Nutoscan is an automated Network Vulnerability Scanner and Reconnaissance tool. It performs a wide range of scans like live Host Scanning, Port Scanning, Nmap Script Scans, Vulnerability Scanning OS detection, UDP Scan and Recon on the target system.

**Key Features**


It will automatically check all the available recon tools in your system and it will suggest some available options to select. If you don't select any option, then it'll automatically select the default scan which includes all the available methods.
It will automatically automatically create a folder and save the default scan results. As well as you can also give your custom output path to save your scanning results.

**Installation**
```
git clone https://github.com/whitehatsoumya/Nutoscan.git
```

```
cd Nutoscan 
```

```
chmod +x Nutoscan.sh
```

**Usage**

Help: ``` Nutoscan.sh -h ``` or ``` Nutoscan.sh --help ```

Basic Scan: ``` Nutoscan.sh -H/--host <TARGET-IP> -t/--type <TYPE> ```

Scan Types:                                                                                                                            
        Network : Shows all live hosts in the host's network (Approx 15 seconds)                                                       
        Port    : Shows all open ports (Approx 15 seconds)                                                                             
        Script  : Runs a script scan on found ports (Approx 5 minutes)                                                                 
        Full    : Runs a full range port scan, then runs a script scan on new ports (Approx 5-10 minutes)                              
        UDP     : Runs a UDP scan "requires sudo" (Approx 5 minutes)                                                                   
        Vulns   : Runs CVE scan and nmap Vulnerabilities scan on all found ports (Approx 5-15 minutes)                                 
        Recon   : Suggests a vareity of recon commands on your choice else automatically runs default(Depends)                         
        All     : Runs all the scanning methods at same time (Approx 20-30 minutes)
        
 **Examples** 
 
Network Scan: ``` Nutoscan.sh -H <TARGET-IP> -t Network ```

Basic Port Scan: ``` Nutoscan.sh -H <TARGET-IP> -t Port ```

Script Scan: ``` Nutoscan.sh -H <TARGET-IP> -t Script ```

Full Scan: ``` Nutoscan.sh -H <TARGET-IP> -t Full ```

UDP Scan: ``` Nutoscan.sh -H <TARGET-IP> -t UDP ```

Vulns Scan: ``` Nutoscan.sh -H <TARGET-IP> -t Vulns ```

Recon: ``` Nutoscan.sh -H <TARGET-IP> -t Recon ```

All: ``` Nutoscan.sh -H <TARGET-IP> -t All ```


**Note**
In Recon Scan It will prompt you to select options, you can select accordingly or else it will automatically scan all the available recon tools which has been already installed with your system!


**Legal Disclaimer**:

You might be super excited to use this tool, me too. But here is the problem! whitehatsoumya, Soumyaranjan Pradhan and Github won't be responsible for any actions made by you. This tool is made for security research and education purposes only. It is the end user's responsibility to obey all applicable 
local, state and federal laws. 


If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/whitehatsoumya)
