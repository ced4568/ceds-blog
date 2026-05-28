# Ced's Home Lab Blog

Technical blog covering homelab infrastructure, Kubernetes, observability, DevOps, and real production builds. Written by a DevOps and Cloud Infrastructure Engineer running an 18 node production environment out of Oxford, MS.

[![Live Blog](https://img.shields.io/badge/Blog-cedshomelab.com-1D9E75?style=flat-square)](https://cedshomelab.com)
[![Posts](https://img.shields.io/badge/Posts-Live-0F6E56?style=flat-square)](https://cedshomelab.com/posts)
[![Ebooks](https://img.shields.io/badge/Ebooks-Gumroad-268BFF?style=flat-square)](https://chasedumphord.gumroad.com)
[![NOC](https://img.shields.io/badge/Live%20NOC-noc.chasedumphord.com-085041?style=flat-square)](https://noc.chasedumphord.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-chasedumphord.com-0F6E56?style=flat-square)](https://chasedumphord.com)

---

## What This Is

Real infrastructure engineering documented as it happens. Every post covers a real build, a real incident, or a real config pulled directly from a production homelab running 24/7. Not a tutorial environment. Not a demo. Actual hardware, actual failures, actual fixes.

The lab behind the blog: 6 node Proxmox VE cluster, 12 node K3s Kubernetes cluster on Raspberry Pi, full observability stack running Prometheus, Grafana, and Alertmanager, VLAN segmented UniFi network, TrueNAS storage, and a live NOC dashboard visible at all times.

---

## Stack

| Layer | Technology |
|-------|------------|
| Static site generator | Hugo Extended v0.159.2 |
| Theme | PaperMod |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |
| Domain | cedshomelab.com via Cloudflare DNS |
| Email capture | Beehiiv |
| Ebook sales | Gumroad |

---

## Live Posts

| Status | Post |
|--------|------|
| Published | I Found a Dell Tower in the Trash. Five Years Later It's a 6-Node Proxmox HA Cluster |
| Published | How I Built a Live NOC Dashboard for My Homelab Using Grafana + Prometheus |
| Published | Zero Open Ports: How I Expose 28 Homelab Services Without Touching My Router |

---

## Post Backlog

| Status | Post |
|--------|------|
| In progress | K3s on Raspberry Pi: 12 Nodes, 117 Days |
| In progress | APRS iGate: Bridging RF and IP with a Raspberry Pi |
| In progress | Why I Run 4 VLANs and How I Set Them Up |
| In progress | Unpoller + Prometheus: Monitoring UniFi and the 429 Rate Limiting Problem |
| In progress | MTConnect: The Industrial Protocol Nobody Talks About |
| In progress | Disk Full → Prometheus Dark: A Real Homelab Incident Report |
| In progress | Building in Public: What KubeCraft Taught Me in 30 Days |
| In progress | Deploying an AI Operations Assistant on a Hetzner VPS |
| In progress | The Hugo Blog Build |
| In progress | Becoming a Kubestronaut |
| In progress | Starting Synthos Systems |
| In progress | Obsidian and How It Helped Me Get Organized |
| In progress | About Working at GE Aerospace |

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

Technical ebooks covering homelab infrastructure, Kubernetes, observability, and DevOps. Written from real production experience, not documentation rewrites, not beginner recaps. If it's in the ebook, it was built and tested in the lab first.

[Browse on Gumroad](https://chasedumphord.gumroad.com)

---

## The Lab Behind Everything

This blog is the public documentation layer of the same infrastructure that powers [Synthos Systems](https://synthossystems.com), an AI systems agency built on real operational infrastructure, not cloud-only tooling. Every solution Synthos deploys for clients gets tested in this lab first. Proxmox, K3s, Grafana, Prometheus, TrueNAS, all of it running live before it ever touches a client environment.

That's the differentiator. Not just AI tools. Real systems.

---

## Related

| Link | What it is |
|------|------------|
| [cedshomelab.com](https://cedshomelab.com) | Live blog |
| [chasedumphord.com](https://chasedumphord.com) | Portfolio and NOC |
| [noc.chasedumphord.com](https://noc.chasedumphord.com) | Live infrastructure dashboard |
| [synthossystems.com](https://synthossystems.com) | Synthos Systems: AI agency built on this infrastructure |
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
[![Synthos](https://img.shields.io/badge/Agency-synthossystems.com-3B82F6?style=flat-square)](https://synthossystems.com)
