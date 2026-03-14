# Hi there 👋

Here's some stuffs about me

## Hobby

- Software Development
- Development and Operations (DevOps)
- System Administration (SysAdmin)

## Notable Projects

**Personal Projects**

- [pwr-bot](https://github.com/FAZuH/pwr-bot): Discord bot for tracking anime & manga updates, and voice call stats
- [fazuh.com](https://fazuh.com): My notes, hosted on a VPS. Written using [![Obsidian](https://img.shields.io/badge/Obsidian-483699?style=flat-square&logo=obsidian&logoColor=white)](https://obsidian.md/), built using [![Quartz](https://img.shields.io/badge/Quartz-000000?style=flat-square&logo=obsidian&logoColor=white)](https://quartz.jzhao.xyz/)
- mail.fazuh.com: Mail server for @fazuh.com emails using [![Mailcow](https://img.shields.io/badge/Mailcow-EA4335?style=flat-square&logo=gmail&logoColor=white)](https://mailcow.email/)
- [warlock](https://github.com/FAZuH/warlock): Bot for course registration, course schedule update tracking for SIAKNG - UI
- [contribution-grid](https://crates.io/crates/contribution-grid): A Rust crate for generating customizable, GitHub-style contribution heatmap graphs as images
- [faz-bot-app-discord](https://github.com/FAZuH/faz-bot-app-discord) & [faz-bot-app-collect](https://github.com/FAZuH/faz-bot-app-collect): Discord bot for Wynncraft stat tracking n stuff

**College Projects**

- https://github.com/FAZuH/Perbankan: Banking app
- https://github.com/FAZuH/MonitorMBG: A monitoring system for Indonesia's Makan Bergizi Gratis (MBG) program

## Skills

Tools & platform I've learned and used for my projects

<u>Sorted by frequency/total use time</u>

Last updated: 2026-03-14

### DevOps/SysAdmin

List of tools and platforms I've used to manage my servers

- [![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/): To spin up services declaratively and consistently. I have 33 `docker-compose.yaml` and 107 active containers. For other services I just create bash scripts
    <details>
    <summary>Images</summary>
        
    ![See image](https://media.discordapp.net/attachments/1301884019457261729/1482412493916733711/image.png?ex=69b6dbb8&is=69b58a38&hm=c8e9e560253892c287737d6c5e16e6d06b36bcfb8d21ca15afcd30ec80c0c368&=&format=webp&quality=lossless&width=1270&height=201)
    </details>
- [![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/), [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/) and other Linux tools: For simple scripting & automation
- Tailscale: To connect to private services (such as Nextcloud, admin panels, Bitwarden, etc.)
- [![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)](https://www.nginx.com/): Reverse proxy
- [![Consul](https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white)](https://www.consul.io/) **Template**: Dynamically generate NGINX configurations with Consul for automated reverse proxy
- [![Restic](https://img.shields.io/badge/Restic-00ADEE?style=flat-square)](https://restic.net/), [![Autorestic](https://img.shields.io/badge/Autorestic-000000?style=flat-square)](https://autorestic.vercel.app/): Automatic backups
- [![SOPS](https://img.shields.io/badge/SOPS-5E6772?style=flat-square)](https://github.com/getsops/sops) & [![age](https://img.shields.io/badge/age-000000?style=flat-square)](https://github.com/FiloSottile/age): Secrets encryption
- [![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)](https://grafana.com/), [![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)](https://prometheus.io/), [![Uptime Kuma](https://img.shields.io/badge/Uptime_Kuma-607D8B?style=flat-square&logo=uptime-kuma&logoColor=white)](https://uptime.kuma.pet/): Server monitoring
- [![OVH](https://img.shields.io/badge/OVH-0050D7?style=flat-square&logo=ovh&logoColor=white)](https://www.ovhcloud.com/): Current cloud provider. As of writing, I manage 3 VPS & 1 dedicated (+3 VM)
- [![iptables](https://img.shields.io/badge/iptables-444444?style=flat-square)](https://www.netfilter.org/projects/iptables/), [![Consul](https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white)](https://www.consul.io/): Created script to NAT active Docker containers dynamically (which isn't possible by default) in VMs, and route to a port in the host, all sharing 1 IP with health checking
- [![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)](https://www.proxmox.com/): For virtualization in my dedicated server to manage VMs and resource allocation. Though I just copied a setup script and modified it

### Software Development

List of programming languages and frameworks used for my projects

- [![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
    - [![Poise](https://img.shields.io/badge/Poise-000000?style=flat-square)](https://github.com/serenity-rs/poise): Discord bot
    - [![sqlx](https://img.shields.io/badge/sqlx-2B3E50?style=flat-square)](https://github.com/launchbadge/sqlx): SQLite
    - [![Axum](https://img.shields.io/badge/Axum-333333?style=flat-square)](https://github.com/tokio-rs/axum): Web backend
- [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
    - [![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)](https://playwright.dev/): Web automation
    - [![Nextcord](https://img.shields.io/badge/Nextcord-5865F2?style=flat-square)](https://nextcord.dev/): Discord bot
    - [![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)](https://www.sqlalchemy.org/): Database ORM
    - [![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/), [![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/), [![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white)](https://matplotlib.org/): Data analysis
    - [![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io/): Rapid web prototyping
- [![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)

<hr>

<div align="center">

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=FAZuH&layout=compact&bg_color=00000000&border_color=00000000&text_color=fff)](https://github.com/anuraghazra/github-readme-stats)
</div>
