# Sec+ 

### Secure Protocols
#### SRTP - Secure Real-Time Transport Protocol  
* Voice and video
#### SNTP - Secure Network Time Protocol  
* Time syncronization  
#### S/MIME - Secure/ Multipurpose Internet Mail Extentions
#### Secure Pop
#### Secure IMAP
#### IPSec - Internet Protocol Security 
* Auth and Encryotion for every packet
* Anti- Replay
#### FTPS - File transfer Protocol Secure  
* Uses SSL
#### SFTP - SSH File Transfer Protocol  
* Uses SSH to transfer
#### LDAP - Lightweight Directory Access Protocol  
* Protocol for reading and writing directories over an IP network

SY0-601, Objective 4.5 - Forensics Data Acquisition  
SY0-601, Objective 2.6 - Embedded Systems  
SY0-601, Objective 5.2 - Security Frameworks  
##### SY0-601, Objective 3.4 - Wireless Authentication Protocols   
* EAP - Extensible Authentication Protocol
  * Integrates with 802.1x
* IEEE 802.1X
  * Port-based NAC
  * Don't get access to the network until you authenticate
  * Used in conjunction with an access database
    * RADUIS, LDAP, TACAS+
* EAP-FAST - EAP Flexible Auth via Secure Tunneling
  * Authentication server (AS) and supplicant share a protected acces credential (PAC) (shared secret)
  * AUTH occurs over the TLS tunnel
  * Need a RADIUS server
    * Provides the authentication databade and EAP-FAST services
* PEAP - Proctected Extensible Authentication Protocol
  * Protceted EAP
  * Created by CISCO, MS, and RSA Security
  * Encapsultaes EAP in a TLS Tunnel
  * AS uses a digital cerificate
  * User authenticates with MSCHAPv2
* EAP TLS - EAP Transport Layer Security
  * Strong security, wide adoption
  * Support from most of the industry
  * Need PKI
  * Must deploy and manage certs
* EAP TTLS - EAP Tunneled Transport Layer Security
  * Support __other__ authentication protocols on a TLS tunnel
  * Only requires a digital cert on the Authenticatino Server (AS)
  * Use RADIUS with federation 
  * Use 802.1X as the authentication method
    
##### SY0-601, Objective 3.6 - Cloud Security Solutions  
* CASB - Cloud Access Security Broker
  * Visibility, Compliance, Threat prevention, Data security
* SWG - Next-Gen Secure Web Gateway
  * Protect users and devices
  * Examine the application API
  * Examping JSON string and API   

##### SY0-601, Objective 1.3 - Race Conditions  
* TOCTOU - Time of change time of use attack

##### SY0-601, Objective 3.2 - Application Hardening  
* SED - Self Encrypting Drive  

##### SY0-601, Objective 3.5 - Mobile Device Management  
* MDM - Mobile Device Management
  
##### SY0-601, Objective 3.8 - Access Control  
* TOTP - Time based One Time Passwords
* DAC (Discretionary Access Control) is used in many operating systems, and this model allows the owner of the resource to control who has access.
* MAC (Mandatory Access Control) allows access based on the security level assigned to an object. Only users with the object’s assigned security level or higher may access the resource.
* ABAC (Attribute-based Access Control) combines many different parameters to determine if a user has access to a resource.
* RBAC (Role-based Access Control) assigns rights and permissions based on the role of a user. These roles are usually assigned by group.
  
SY0-601, Objective 2.1 - Honeypots and Deception  
SY0-601, Objective 4.3 - Log Files  
##### SY0-601, Objective 3.2 - Boot Integrity  
* Trusted Boot - The Trusted Boot portion of the startup process verifies the operating system kernel signature and starts the ELAM (Early Launch Anti-Malware) process.
* Measured Boot - Measured Boot occurs after the Trusted Boot process and verifies that nothing on the computer has been changed by malicious software or other processes.
* Secure Boot - Secure Boot is a UEFI BIOS boot feature that checks the digital signature of the bootloader. The Trusted Boot process occurs after Secure Boot has completed.
* POST - POST (Power-On Self-Test) is a hardware check performed prior to booting an operating system.


SY0-601, Objective 3.5 - Mobile Deployment Models  
SY0-601, Objective 5.1 - Security Controls  
SY0-601, Objective 2.3 - Secure Deployments  
SY0-601, Objective 5.3 - Personnel Security  
SY0-601, Objective 4.1 - Reconnaissance Tools Part 1  
SY0-601, Objective 3.9 - Certificate Concepts    

##### SY0-601, Objective 5.5 - Data Roles and Responsibilities  
* Data custodian - The data custodian manages access rights and sets security controls to the data.  
* Data processor - The data processor manages the operational use of the data, but not the rights and permissions to the information.  
* Data owner - The data owner is usually a higher-level  executive who makes business decisions regarding the data.  
* Privacy officer - A privacy officer sets privacy policies and implements privacy processes and procedures.   

##### SY0-601, Objective 3.3 - Other Network Appliances  
* HSM (Hardware Security Module)
  * High-end cryptographic hardware appliance that can securely store keys and certificates for all devices.
##### SY0-601, Objective 5.4 - Risk Analysis
* Likelihood - Annualized rate of Occurrence (ARO)
* SLE (Single Loss Expectancy)
* ALE (Annualized Loss Expectancy)
  * ARO x SLE
* RTO (Recovery Time Objective)
  * How long it can be down 
* RPO (Recovery Point Objective)
  * Acceptible data loss
* MTTR (Mean time to Repair)
  * Time required to fix the issue
* MTBF (Mean time Between Failures)
  * Predict the time between outages
   

SY0-601, Objective 3.1 - Secure Protocols  
SY0-601, Objective 1.8 - Penetration Testing  
