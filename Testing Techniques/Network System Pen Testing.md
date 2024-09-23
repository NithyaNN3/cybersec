# Pentesting
- manual or automated techniques that simulate an attack on an org's security arrangements
- black box testing 

**Black Box testing** - attacks without prior knowledge of internal workings. Checks the accuracy of your system without too much concern about the internal implementations
**White box testing** - deeply analyzes the system by checking all the internal coding

## Types
1) Application pen testing
2) Infrastructure pentesting
3) Device pentesting
4) Mobile pentesting
5) Wireless pentesting
and so on..

## Testing Prep
1. Define scope
2. determine testing applications
3. define purpose and limitation[
4. Prepare test environment, data
5. Select tester and timeframe

# Network Pentest Phases
- follow a methodology like OWASP, PTES, NIST
1) **Gather information:**
  - using OSINT (open source intelligence) framework
  - port scanning and service enumeration
  - foot printing, directory brute forcing
  - understand how target system works
2) **Threat modelling:**
  - identify target and draw data flow diagrams
  - find technologies in use
  - understand attack surface and create attacks
  - create possible malicious payloads
  - list possible attacks
3) **Identify vulnerabilities:**
  - execute threat modelling plan
  - inject arbitrary code and change execution flow
  - access control and user management
  - fuzz the application
  - identify cause and severity of vulnerability
  - Tools: automated testing(Nessus, Burpsuite pro), OSINT (SpiderFoot, ProjectDiscovery.io), NMAP port scanner, Metasploit (contains packages for identifying and exploiting vulnerabilities)
4) **Exploitation:**
  - exploit vulnerabilities identifies in previous step
  - escalate privileges
  - lateral movement (attack internal network)
  - dump credentials and data
5) **Reporting:**
  - executive summary of the test
  - includes remediation recommendation
6) **Quality assurance:**
  - for the technical members & non-technical members to review

## Common Network Vulnerabilities
- insufficient network segmentation
- firewall rules too permissive
- users have unnecessary or too many permissions
- active directory misconfigurations
- default passwords on network devices
- lack of patching
- legacy servers or devices
- poor password policy
- insufficient network access control
- lack of authentication

https://bugcrowd.com/rmit...

Upskilling pentesting - offensive security certified professional certification, HackTheBox
