# Progress Log

## June 11, 2026
- Purchased TryHackMe premium
- Completed Pre-Security: Intro to LAN
- Learned ARP, subnetting, MAC addresses
- Applied to IT Specialist role at Liberty Latin America
- Updated resume with cybersecurity skills and GitHub portfolio

## June 12, 2026
- Booted Kali Linux live from USB for first time
- Disabled Secure Boot on MSI BIOS
- Ran full network ping sweep on Kali natively
- Scanned router - identified filtered SSH, Telnet, FTP ports
- Confirmed ADB vulnerability on Smart TV via Kali
- Identified PS4 on network via MAC vendor lookup
- 
## June 13, 2026
- Purchased TryHackMe premium
- Completed Pre-Security: Intro to LAN
- Learned ARP, subnetting, MAC addresses, default gateways
- Applied to IT Specialist role at Liberty Latin America
- Updated resume with cybersecurity skills and GitHub portfolio
- Updated LinkedIn profile — photo, headline, about section, skills

## June 14, 2026
- Completed TryHackMe: Packets & Frames room (3 day streak)
- Learned TCP 3-way handshake (SYN, SYN/ACK, ACK)
- Learned packet sequencing, checksums, and port fundamentals
- Completed OSI Model room — all 7 layers covered
- Applied to BairesDev via INDI, completed video intro
- LinkedIn post shared on TryHackMe progress

## June 15, 2026
- Earned TryHackMe Networking Nerd badge
- Completed Extending Your Network room
- Started DNS in Detail (13% complete)
- Flashed Kali Linux with 16GB persistence onto 32GB USB
- Bought TP-Link Archer T2U scheduled for June 26th paycheck

## June 16, 2026
- Completed DNS in Detail room
- Completed How Websites Work room (HTML injection lab)
- Started How the Web Works module 4
- Learned about Load Balancers, CDNs, Databases, WAF
- Applied job hunting strategy mapped out

## June 17, 2026
- Completed How Websites Work module
- Learned Load Balancers, CDN, WAF, Databases
- Started How the Internet Works - Client Server basics

## June 18, 2026
- Completed Client-Server Basics
- Completed Virtualization Basics (VMs, Containers, Docker)
- Started Operating Systems Basics
- Learned cloud scalability concepts

## June 19, 2026
- Completed Operating Systems Basics room (Linux fundamentals)
- Started Windows Basics room
- Deep dive into WiFi pentesting theory PMKID attacks, dictionary vs brute force, Evil Twin attacks, hash cracking math
- Researched RTX 4050 cracking performance for future TP-Link practice
- Confirmed WiFi pentesting permission with neighbor for future authorized testing

## June 20, 2026
- Continued Operating Systems Basics room
- Researched WiFi pentesting attack types (again) PMKID, Evil Twin, KARMA, WPA3 downgrade

## June 21, 2026
- Completed Operating Systems Basics room
- First real privilege escalation chain: SSH access, password guessing, found root credentials exposed in command history, escalated to root
- Started Windows Basics room

## June 22, 2026
- Completed Module 5: Operating Systems Basics
- Completed Module 6: Software Basics (JavaScript fundamentals, SQL query structure)
- Created new repo: tryhackme-writeups
- One module remaining in Pre-Security path

## June 23, 2026
- COMPLETED Pre-Security Learning Path on TryHackMe (19h10m total)
- Earned official Pre-Security completion certificate
- Started Cyber Security 101 
- Next: Jr Penetration Tester path

## June 24 - July 2, 2026
- Personal commitments took priority; limited technical activity during this period

## July 3, 2026
- Full WiFi penetration test: monitor mode, handshake capture via deauth, cracked with Aircrack-ng
- Created new repo: wifi-pentest-lab
- Installed and configured BeEF framework
- Hooked browsers on desktop AND phone (cross-device via local network)
- Tested 8 BeEF modules: geolocation, internal IP, battery status, fake notifications, fake Flash update, Google phishing, Pretty Theft
- Created new repo: beef-browser-exploitation-lab

## July 4, 2026 — Completed TryHackMe Windows Fundamentals 1 (Jr Penetration Tester path). 
Covered Windows editions, system directory structure, Task Manager, and user account basics. 
Starting Windows Fundamentals 2 next session.

## July 5 - 6 2026 — No hands-on lab work today (personal circumstances). 
Reinforced concepts via video study: unrestricted file upload → RCE via 
malicious PHP payload, recon-to-brute-force chain (host discovery → gobuster 
directory enumeration → Hydra password cracking on admin panel), and SQL 
injection auth bypass (' OR 1=1-- comment-based logic to skip credential 
check). No new tools used, but strengthened understanding of concepts 
already touched in prior labs (gobuster/hydra chain mirrors home-network-scan 
work).

## July 7, 2026 — BeEF Browser Exploitation Lab, Part 2

Built a fully functional fake e-commerce site (Kinetic Gear) with real HTML/CSS/JS 
(product grid, working cart interaction, newsletter form) to replace the bare test 
page used in the original BeEF lab — better simulates hooking a realistic target vs. 
an empty shell page. Site built with separated HTML/CSS/JS files (not single-file) 
for a more realistic, maintainable structure.

Hosted via python3 -m http.server, hooked via BeEF on local network (wlan0, 
192.168.100.197). Recovered lost BeEF admin credentials via /etc/beef-xss/config.yaml 
after losing the original login.

Modules tested:
- Get Geolocation — retrieved device location
- Get Page HTML — pulled full rendered page source
- Keylogger — captured keystrokes on hooked session in real time
- Infinite Alert/Request loop — DoS-style browser disruption module
- Fake Notification Bar (Social Engineering) — rendered a convincing fake 
  update/permission prompt with a custom link target

Reinforced understanding of the social engineering side of client-side attacks — 
technical hooking is only half the exploitation chain; modules like the fake 
notification bar depend entirely on exploiting user trust/habit rather than any 
software vulnerability.
