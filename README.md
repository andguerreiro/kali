# Kali Linux Labs

## lab01

**Objective:** Set up an isolated virtual environment where Kali Linux is used as the attack machine and Windows 7 is the target. The lab enables controlled penetration-testing exercises between the two VMs while keeping them isolated from the Internet and the physical network. The final objective is to identify vulnerabilities in Windows 7 and exploit them to gain control of the target system.

## lab02

**Objective:** Conduct the first penetration-testing session from an offline Kali Linux attack machine against an isolated Windows 7 target with all firewall rules off. The lab confirms that the target exposes vulnerable SMBv1 (MS17-010) and resolves a missing mysmb.py dependency via the Debian host, though initial exploitation failed due to an inaccessible named pipe.

## Host
Debian 13, Xfce 

## Hardware
5700X, RX 7600, 16GB DDR4, 512GB KC3000, CF-WU785AC
