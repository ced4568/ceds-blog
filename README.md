# Ced's Home Lab Blog

> Technical blog covering homelab infrastructure, Kubernetes, observability, DevOps, and real production builds written by a DevOps and Cloud Infrastructure Engineer running an 18 node production environment out of Oxford, MS.

[![Live Blog](https://img.shields.io/badge/Blog-cedshomelab.com-1D9E75?style=flat-square)](https://cedshomelab.com)
[![Posts](https://img.shields.io/badge/Posts-Live-0F6E56?style=flat-square)](https://cedshomelab.com/posts)
[![Ebooks](https://img.shields.io/badge/Ebooks-Gumroad-268BFF?style=flat-square)](https://chasedumphord.gumroad.com)
[![NOC](https://img.shields.io/badge/Live%20NOC-noc.chasedumphord.com-085041?style=flat-square)](https://noc.chasedumphord.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-chasedumphord.com-0F6E56?style=flat-square)](https://chasedumphord.com)

---

## What This Is

Real infrastructure engineering documented as it happens. Every post covers a real build, a real incident, or a real config from a production homelab running 24/7 not a tutorial environment, not a demo, actual hardware.

The lab behind the blog: 6 node Proxmox VE cluster, 12 node K3s Kubernetes cluster on Raspberry Pi, full observability stack (Prometheus, Grafana, Alertmanager), VLAN segmented UniFi network, TrueNAS storage, and a live NOC dashboard.

---

## Stack

| Layer | Technology |
|-------|------------|
| Static site generator | Hugo Extended v0.159.2 |
| Theme | PaperMod |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |
| Domain | cedshomelab.com (Cloudflare DNS) |
| Email capture | Beehiiv |
| Ebook sales | Gumroad |

---

## Live Posts

- [x] I Found a Dell Tower in the Trash. Five Years Later It's a 6-Node Proxmox HA Cluster
- [x] How I Built a Live NOC Dashboard for My Homelab Using Grafana + Prometheus
- [x] Zero Open Ports: How I Expose 28 Homelab Services Without Touching My Router

---

## Post Backlog 

- [ ] K3s on Raspberry Pi — 12 Nodes, 117 Days
- [ ] APRS iGate — Bridging RF and IP with a Raspberry Pi
- [ ] Why I Run 4 VLANs and How I Set Them Up
- [ ] Unpoller + Prometheus: Monitoring UniFi (and the 429 Rate Limiting Problem)
- [ ] MTConnect — The Industrial Protocol Nobody Talks About
- [ ] Disk Full → Prometheus Dark: A Real Homelab Incident Report
- [ ] Building in Public: What KubeCraft Taught Me in 30 Days
- [ ] Deploying an AI Operations Assistant on a Hetzner VPS
- [ ] The Hugo Blog Build
- [ ] Becoming a Kubestronaut
- [ ] Starting Synthos Systems
- [ ] Obsidian and How It Helped Me Get Organized
- [ ] About Working at GE Aerospace

---

## Publishing Workflow

All posts are Markdown files in `content/posts/`. Push to `main` and GitHub Actions builds and deploys automatically in about 60 seconds.

```bash
git add .
git commit -m "add post: your post title"
git push
```

---

## Ebooks

Technical ebooks available on Gumroad covering homelab infrastructure, Kubernetes, observability, and DevOps. All written from real production experience.

[Follow on Gumroad →](https://chasedumphord.gumroad.com)

---

## Related

| Link | Description |
|------|-------------|
| [cedshomelab.com](https://cedshomelab.com) | Live blog |
| [chasedumphord.com](https://chasedumphord.com) | Portfolio and NOC |
| [noc.chasedumphord.com](https://noc.chasedumphord.com) | Live infrastructure dashboard |
| [ceds-homelab](https://github.com/ced4568/ceds-homelab) | Homelab infrastructure repo |
| [ced-k3s-homelab](https://github.com/ced4568/ced-k3s-homelab) | K3s cluster repo |

---

## Author

**Chase Dumphord (Ced)**
DevOps and Cloud Infrastructure Engineer · GE Aerospace · Oxford, MS

[![Portfolio](https://img.shields.io/badge/Portfolio-chasedumphord.com-0F6E56?style=flat-square)](https://chasedumphord.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-chase--dumphord-0A66C2?style=flat-square)](https://www.linkedin.com/in/chase-dumphord/)
[![GitHub](https://img.shields.io/badge/GitHub-ced4568-181717?style=flat-square)](https://github.com/ced4568)
[![Blog](https://img.shields.io/badge/Blog-cedshomelab.com-1D9E75?style=flat-square)](https://cedshomelab.com)