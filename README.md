

# DEVEL HTB 

**Deficulty**:easy 

***************************
## Scanning & Enumeration

**nmap scaning **

Starting Nmap 7.92 ( https://nmap.org ) at 2022-06-10 12:15 EDT
NSE: Loaded 155 scripts for scanning.
NSE: Script Pre-scanning.
NSE: Starting runlevel 1 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
NSE: Starting runlevel 2 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
NSE: Starting runlevel 3 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
Initiating Connect Scan at 12:15
Scanning 10.129.71.101 [1000 ports]
Discovered open port 21/tcp on 10.129.71.101
Discovered open port 80/tcp on 10.129.71.101
Completed Connect Scan at 12:15, 14.31s elapsed (1000 total ports)
Initiating Service scan at 12:15
Scanning 2 services on 10.129.71.101
Completed Service scan at 12:15, 6.63s elapsed (2 services on 1 host)
NSE: Script scanning 10.129.71.101.
NSE: Starting runlevel 1 (of 3) scan.
Initiating NSE at 12:15
NSE: [ftp-bounce 10.129.71.101:21] PORT response: 501 Server cannot accept argument.
Completed NSE at 12:15, 3.79s elapsed
NSE: Starting runlevel 2 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 1.43s elapsed
NSE: Starting runlevel 3 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
Nmap scan report for 10.129.71.101
Host is up, received user-set (0.20s latency).
Scanned at 2022-06-10 12:15:20 EDT for 26s
Not shown: 998 filtered tcp ports (no-response)
PORT   STATE SERVICE REASON  VERSION
21/tcp open  ftp     syn-ack Microsoft ftpd
| ftp-syst: 
|_  SYST: Windows_NT
| ftp-anon: Anonymous FTP login allowed (FTP code 230)
| 03-18-17  02:06AM       <DIR>          aspnet_client
| 03-17-17  05:37PM                  689 iisstart.htm
|_03-17-17  05:37PM               184946 welcome.png
80/tcp open  http    syn-ack Microsoft IIS httpd 7.5
|_http-title: IIS7
| http-methods: 
|   Supported Methods: OPTIONS TRACE GET HEAD POST
|_  Potentially risky methods: TRACE
|_http-server-header: Microsoft-IIS/7.5
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

NSE: Script Post-scanning.
NSE: Starting runlevel 1 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
NSE: Starting runlevel 2 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
NSE: Starting runlevel 3 (of 3) scan.
Initiating NSE at 12:15
Completed NSE at 12:15, 0.00s elapsed
Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 27.98 seconds
***********************
**Two services Running**

**Port**:80 **IIS/7.5**
**Port**:21 **ftpd**

# HTB-DEVEL
