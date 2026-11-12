```console
zi@homelab:~$ whoami
IT support / Linux enthusiast
```

```console
zi@homelab:~$ cat /etc/motd
> One old laptop, Arch Linux, Docker, and the parts of IT that break quietly.
> Windows and Linux, nginx, DNS, TLS, permissions, backups, monitoring.
> I read the logs before I change anything, and I keep the failures in the
> repo next to the fixes.
```

### `ls ~/homelab`

```text
homelab/
├── nginx/        one TLS entry point, per-host routing, self-signed CA
├── jellyfin/     media server, library mounted read-only over SMB
├── monitoring/   prometheus, grafana, alertmanager, five alert rules
├── searxng/      private search, LAN only, no limiter
├── samba/        AD DC, file shares, legacy functional level
├── hardening/    ssh keys, nftables, fail2ban
├── backup/       restic units and a restore drill that really runs
└── docs/         screenshots, build log, troubleshooting, decisions
```

### `cat status`

| | |
|---|---|
| `looking_for` | IT support · helpdesk · junior Linux admin |
| `location`   | Czech Republic |
| `stack`      | Arch · NixOS · Windows · Docker · nginx · Samba AD · Prometheus · Grafana · restic |
| `learning`   | Active Directory · NixOS · network troubleshooting |

### `ls ~/homelab/docs`

- **[restore drill](https://github.com/ZiZiHigh/homelab/blob/main/docs/restore-drill.md)** — a backup is a hypothesis until you restore it, with hashes and timings
- **[media over the LAN](https://github.com/ZiZiHigh/homelab/blob/main/docs/media-share.md)** — SMB export, CIFS mount, and the mount-propagation gotcha
- **[screenshots](https://github.com/ZiZiHigh/homelab/tree/main/docs/screenshots)** — Grafana, Prometheus, Alertmanager, Jellyfin
- **[troubleshooting](https://github.com/ZiZiHigh/homelab/blob/main/docs/troubleshooting.md)** — symptom, checks, cause, fix

Also: [homelab-ticketing](https://github.com/ZiZiHigh/homelab-ticketing), an osTicket stack behind the same proxy. Not everything here is IT — this profile is a portfolio, not only a server log.

<div align="center">

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)
![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white)
![Gentoo](https://img.shields.io/badge/Gentoo-54487A?style=flat-square&logo=gentoo&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Samba](https://img.shields.io/badge/Samba_AD-EE0000?style=flat-square&logo=samba&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**[Portfolio → zizihigh.vercel.app](https://zizihigh.vercel.app/)**
</div>
