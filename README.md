** Make sure to pip install ansible, apt has an older copy **

# Instructions
* Install Ansible `pip3 install ansible`
* Clone and enter the repo `git clone https://github.com/l4rRyxz/kali-build.git`
* Install requirements `ansible-galaxy install -r requirements.yml`
* Make sure we have a sudo token `sudo whoami`
* Run the playbook `ansible-playbook main.yml`

---

# What's within?
---

### APT Installations

- [x] Instll TMUX
- [x] Install go
- [x] Install rust
- [x] Install Packages: 
      - jq
      - pipx
      - python3
      - python3-dev
      - python3-pip
      - python3-venv
      - python3-requests-future
      - ntpdate
      - flameshot
      - exiftool
      - gnome-terminal
      - bloodhound
      - feroxbuster
      - gobuster
      - oscanner
      - redis-tools
      - tnscmd10g
      - wkhtmltopdf
      - proxychains
      - docker.io
      - docker-compose
      - awscli
      - azure-cli

### Python Installations (pipx)
- [x] Certipy
- [x] Crackmapexec
- [x] Impacket
- [x] Updog
- [x] AutoRecon
- [x] manspider
- [x] DonPAPI
- [ ] bloodhound-python

### Github Repo's

- [x] SharpCollection
- [x] Seclists
- [x] Scripts
- [x] PowerSharpPack
- [x] Tmux-Logging
- [x] Villain
- [x] pre-compiles
- [x] pretender
- [x] donut
- [x] X-Force SQLRecon
- [X] XenSpawn
- [ ] RustHound
- [ ] Havoc C2
- [ ] NucleiFuzzer
- [ ] Coercer https://github.com/p0dalirius/Coercer

### Public Packer/Loader
- [x] RustPacker
- [ ] Freeze (rs,go)
- [ ] https://github.com/wangfly-me/LoaderFly
- [ ] https://github.com/TunnelGRE/Augustus
- [ ] https://github.com/D3Ext/Hooka
- [ ] https://github.com/b1nhack/rust-shellcode

### Rust Malware Development
https://github.com/memN0ps
https://github.com/trickster0/OffensiveRust
https://github.com/Kudaes

### Sliver Custom Extensions

#### [Feeding Sliver - Extension Guide](https://medium.com/@l4rry/feeding-sliver-extension-guide-1c14fae42a2a)

- [x] Chisel
- [x] Mimikatz

### BOF Collection
- [ ] Truestedsec (SA/Remote)
- [ ] Outflank C2TC
- [ ] https://github.com/Mr-Un1k0d3r/Elevate-System-Trusted-BOF

### Github Compiled Releases
- [ ] Sliver C2 Framework
- [ ] PEASS-ng
- [ ] pspy
- [ ] Chisel
- [ ] Ligolo-ng

### Custom Installations/Configurations

- [x] VSCode
- [x] Kerbrute
- [x] customize Burp Suite
- [x] customize Firefox
- [x] custom queries bloodhound
- [x] customize .zshrc
- [ ] Bloodhound CE
- [ ] Auditd
