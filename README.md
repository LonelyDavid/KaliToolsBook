# Kali Linux 工具使用详解
本书收录了Kali Linux VMWare系统中预安装的所有工具的基本使用方法和案例， 主要是为了帮助初学者能够对这些工具有个基本的概念并大致了解如何使用。所有的内容仅作学习之用。 
本书的目录结构按照Kali Linux VMWare系统中预安装的工具类别和顺序排列。 

### 01-信息收集工具（Information Gathering）
- **DNS分析 （DNS Analysis）**
  - [x] [dnsenum](Http://google.com)
  - [x] [dnsrecon]()
  - [x] [fierce]()
- **IDS/IPS 识别（IDS/IPS Identification）**
  - [x] lbd
  - [x] wafw00f
- **主机识别（Live Host Identification）**
  - [x] arping
  - [x] fping
  - [x] hping3
  - [x] masscan
  - [x] thcping6
- **网络端口扫描（Network & Port Scanners）**
  - [x] nmap
- **OSINT 分析（OSINT Analysis）**
  - [x] maltego
  - [x] theharvester
- **路由扫描（Route Analysis）**
  - [x] netdiscover
  - [x] netmask
- **SMB 分析（SMB Analysis）**
  - [x] enum4linux
  - [x] nbtscan
  - [x] smbmap
- **SMTP 分析（SMTP Analysis）**
  - [x] swaks
- **SNMP 分析（SNMP Analysis）**
  - [x] onesixtyone
  - [x] snmp-check
- **SSL 分析（SSL Analysis）**
  - [x] ssldump
  - [x] sslh
  - [x] sslscan
  - [x] sslyze
- **其他工具**
  - [x] dmitry
  - [x] ike-scan
  - [x] recon-ng
  - [x] sparta
&nbsp;
### 02-脆弱性分析（Vulnerability Analysis）**
- **模糊测试工具（Fuzzing Tools）**
  - [x] spike-generic_chunked
  - [x] spike-generic_listen_tcp
  - [x] spike-generic_send_tcp
  - [x] spike-generic_send_udp
- **VoIP工具 （VoIP Tools）**
  - [x] voiphopper
- **其他工具**
  - [x] nikto
  - [x] nmap
  - [x] sparta
  - [x] unix-privesc-check
&nbsp;
### 03-网页应用分析（Web Application Analysis）**
- **CMS及框架识别（CMS & Framework Identification）**
  - [x] clusterd
  - [x] wpscan
- **网页应用代理（Web Application Proxies）**
  - [x] burpsuite
- **网络爬虫及目录检索（Web Crawlers & Directory Browsing）**
  - [x] cutycapt
  - [x] dirb
  - [x] dirbuster
  - [x] wfuzz
- **网页脆弱性扫描（Web Vulnerability Scanners）**
  - [x] cadaver
  - [x] davtest
  - [x] nikto
  - [x] skipfish
  - [x] wapiti
  - [x] whatweb
- **其他工具**
  - [x] commix
  - [x] sqlmap 
&nbsp;
### 04-数据库评估（Database Assessment） 
  - [x] SQLite database Browser
  - [x] sqlmap 
&nbsp;
### 05-密码破解 （Password Attacks）
- **离线破解（Offiline Attacks）**
  - [x] chntpw
  - [x] hashcat
  - [x] hashid
  - [x] hash-identifier
  - [x] ophcrack-cli
  - [x] samdump2
- **在线破解（Online Attacks）**
  - [x] hydra
  - [x] hydra-gtk
  - [x] onesixtyone
  - [x] patator
  - [x] thc-pptp-bruter
- **哈希传递攻击工具（Passing the Hash Tools）**
  - [x] mimikatz
  - [x] pth-curl
  - [x] pth-net
  - [x] pth-rpcclient
  - [x] pth-smbclient
  - [x] pth-smbget
  - [x] pth-sqsh
  - [x] pth-winexe
  - [x] pth-wmic
  - [x] pth-wmis
  - [x] pth-xfreerdp
  - [x] smbmap
- **密码字典（Password Profiling & Wordlists）**
  - [x] cewl
  - [x] crunch
  - [x] rsmangler
  - [x] wordlists
- **其他工具**
  - [x] john
  - [x] medusa
  - [x] ncrack
  - [x] ophcrack
&nbsp;
### 06-无线网络攻击 （Wireless Attacks）
- **802.11无线工具（802.11 Wireless Tools）**
  - [x] bully
  - [x] fern wifi cracker
- **蓝牙工具（Bluetooth Tools）**
  - [x] spooftooph
- **其他工具**
  - [x] aircrack-ng
  - [x] kisnet
  - [x] pixiewps
  - [x] reaver
  - [x] wifite
&nbsp;
### 07-逆向工程 （Reverse Engineering）
  - [x] clang
  - [x] clang++
  - [x] NASM shell
  - [x] radare2
&nbsp;
### 08-漏洞利用工具 （Exploitation Tools）
  - [x] metasploit framework
  - [x] msf payload creator
  - [x] searchsploit
  - [x] social enginerring toolkit
  - [x] sqlmap
&nbsp;
### 09-嗅探及网络欺骗工具（Sniffing & Spoofing）
- **网络嗅探（Network Sniffers）**
  - [x] dnschef
  - [x] netsniff-ng
- **网络欺骗工具及MITM（Spoofing and MITM）**
  - [x] rebind
  - [x] sslsplit
  - [x] tcpreplay
- **其他工具**
  - [x] ettercap-graphical
  - [x] macchanger
  - [x] mitmproxy
  - [x] responder
  - [x] wireshark
&nbsp;
### 10-渗透工具 (Post Exploitation)
- **OS 后门工具（OS Backdoors）**
  - [x] dbd
  - [x] powersploit
  - [x] sbd
- **隧道及数据渗漏（Tunneling & Exfiltration）**
  - [x] dns2tcpc
  - [x] dns2tcpd
  - [x] exe2hex
  - [x] iodine
  - [x] miredo
  - [x] proxychains
  - [x] proxytunnel 
  - [x] ptunnel
  - [x] pwnat
  - [x] sslh
  - [x] stunnel4
  - [x] udptunnel
- **网络后门工具（Web Backdoors）**
  - [x] laudanum
  - [x] weevely
- **其他工具**
  - [x] mimikatz
&nbsp;
### 11-取证工具 （Forensics）
- **文件雕刻取证工具（Forensic Carving Tools）**
  - [x] magicrescue
  - [x] scalpel
  - [x] scrounge-ntfs
- **取证图像工具（Forensic Imaging Tools）**
  - [x] guymager
- **PDF取证工具（PDF Forensics Tools）**
  - [x] pdfid
  - [x] pdf-parser
  - [x] peepdf
- **追踪套件（Sleuth Kit Suite）**
  - [x] autopsy
  - [x] blkcalc
  - [x] blkcat
  - [x] blkls
  - [x] blkstat
  - [x] ffind
  - [x] fls
  - [x] fsstat
  - [x] hfind
  - [x] icat-sleuthkit
  - [x] ifind
  - [x] ils-sleuthkit
  - [x] img_cat
  - [x] img_stat
  - [x] istat
  - [x] jcat
  - [x] jls
  - [x] mactime-sleuthkit
  - [x] mmcat
  - [x] mmls
  - [x] mmstat
  - [x] sigfind
  - [x] sorter
  - [x] srch_strings
  - [x] tsk_comparedir
  - [x] tsk_gettimes
  - [x] tsk_loaddb
  - [x] tsk_recover
- **其他工具**
  - [x] binwalk
  - [x] bulk-extractor
  - [x] hashdeep
&nbsp;
### 12-报告工具 （Reporting Tools）
- [x] cutycapt
- [x] faraday IDE
- [x] maltego
- [x] pipal
- [x] recordmydesktop
&nbsp;
### 13-社交网络工具 （Social Engineering Tools）
- [x] maltego
- [x] msf payload creator
- [x] social engineering toolkit

