**About Nutoscan**


<img width="960" alt="Nutoscan" src="https://user-images.githubusercontent.com/67961316/183405168-a215b8f5-cad4-492d-bcf7-79c1e5a38827.png">


Nutoscan is an automated Network Vulnerability Scanner and Reconnaissance tool. It performs a wide range of scans like live Host Scanning, Port Scanning, Nmap Script Scans, Vulnerability Scanning, CVE Scanning OS Detection, UDP Scan and Recon on the target system.


**Key Features**

Auto Recon

Automated Vulnerability Scanning

Common Ports Scanning

All Ports Scanning

CVE Scanning

Fuzzing Directories

Automated Output

And much more


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

Help: ``` ./Nutoscan.sh -h ``` or ``` ./Nutoscan.sh --help ```

Basic Scan: ``` ./Nutoscan.sh -H/--host <TARGET-IP> -t/--type <TYPE> ```



<img width="960" alt="Nutoscan4" src="https://user-images.githubusercontent.com/67961316/183406025-c9654503-4552-483e-a8e1-10a024b4113f.png">


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
 
Network Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t Network ```

Basic Port Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t Port ```

Script Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t Script ```

Full Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t Full ```

UDP Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t UDP ```

Vulns Scan: ``` ./Nutoscan.sh -H <TARGET-IP> -t Vulns ```

Recon: ``` ./Nutoscan.sh -H <TARGET-IP> -t Recon ```

All: ``` ./Nutoscan.sh -H <TARGET-IP> -t All ```


**Note**
In Recon Scan It will prompt you to select options, you can select accordingly or else it will automatically scan all the available recon tools which has been already installed with your system!


<img width="960" alt="Nutoscan2" src="https://user-images.githubusercontent.com/67961316/183405098-08d25693-13dd-4790-a342-974048cce3a2.png">


<img width="960" alt="Nutoscan3" src="https://user-images.githubusercontent.com/67961316/183406135-31523856-6290-491a-8550-b08a94b54e32.png">



**Legal Disclaimer**:

You might be super excited to use this tool, me too. But here is the problem! whitehatsoumya or Github won't be responsible for any actions made by you. This tool is made for security research and education purposes only. It is the end user's responsibility to obey all applicable 
local, state and federal laws. 


If you love and supoort my work then you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/whitehatsoumya)
