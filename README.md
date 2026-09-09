# Murilo Prestes

**Linux. Networks. VoIP. Automation.**

I work with infrastructure and operations, mostly around Linux servers, network troubleshooting, VoIP and the small automations that make repeated work less manual.

Most things I put here start with a real problem: a server migration, a SIP route behaving badly, a backup that needs checking, a network path that makes no sense, or a task I have already done enough times to turn into a script.

I don't like knowing only the command that fixes something. I want to understand what broke, why it broke and how I can prove it.

## What I work with

- **Linux** — Debian, CentOS, services, storage, backups and troubleshooting
- **Networks** — routing, switching, VPNs, DNS, packet capture and path analysis
- **VoIP** — Asterisk, FreePBX, SIP, PJSIP and WebRTC
- **Troubleshooting** — tcpdump, sngrep, Wireshark and a lot of reading logs before changing things
- **Monitoring** — Zabbix, Grafana and operational checks
- **Automation** — Bash, Ansible and some Python
- **Infrastructure** — migrations, firewalls, services and day-to-day operations
- **Cloud** — AWS, Azure and DigitalOcean

## Projects

### [infra-scripts](https://github.com/n0nsi/infra-scripts)
Small infrastructure scripts for backups, network checks, monitoring and VoIP.

They are intentionally simple. The repository has checks and regression tests for the failure cases I want to avoid, but the scripts still look like tools I can open on a server and understand without following five layers of abstraction.

### [testdivoip](https://github.com/n0nsi/testdivoip)
A Bash tool for repeatable network-path checks around VoIP troubleshooting.

It collects ping, MTR, traceroute and ASN context, then keeps the evidence in local reports. The score is only a troubleshooting summary; it is not a carrier verdict or a substitute for reading the measurements.

### [infrawifi](https://github.com/n0nsi/infrawifi)
One of my own infrastructure and Wi-Fi projects.

It is a different kind of project from the shell tools above, but it is part of the same path: infrastructure work that started outside GitHub and that I want to document better instead of leaving the knowledge only in my head.

## What I'm studying

I use GitHub as part of my study process too, but I don't want to publish empty folders just to make the profile look busy.

The areas I'm actively developing are:

- CCNA / routing and switching
- Linux administration
- Windows Server and Active Directory
- server virtualization
- Ansible
- monitoring and observability
- cloud infrastructure

When a lab becomes something worth keeping, I want the repository to contain the topology, configuration, verification and what I actually learned — not just a screenshot saying it worked.

## How I like to work

I prefer small tools I can explain, evidence before guesses, and documentation that says what the code really does.

There is old work in my GitHub and there will probably always be things I would write differently after learning more. I don't see that as a problem. The useful part is being able to look back and understand what changed and why.

— **Murilo Prestes**
