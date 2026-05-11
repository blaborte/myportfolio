# Baltazar Laborte — IT & Cybersecurity Portfolio

A personal portfolio website built with pure HTML, CSS, and JavaScript — no frameworks, no build tools. Designed with a dark/light glassmorphic aesthetic, animated network canvas background, and a consistent BL brand identity across all pages.

Live site: **[blaborte.github.io](https://blaborte.github.io)**

---

## 📁 File Structure

```
/
├── index.html              # Home / landing page
├── about.html              # About me
├── education.html          # Education, certifications & work experience
├── skills.html             # Technical skills & tools
├── projects.html           # Homelab project cards
├── active-directory.html   # Active Directory lab detail page
├── osticket.html           # osTicket lab detail page
├── contact.html            # Contact information
├── favicon.svg             # BL monogram favicon
└── README.md               # This file
```

---

## 📄 Pages

### `index.html` — Home
The main landing page. Features an animated particle network canvas, ambient orb backgrounds, hero section with avatar, social links (LinkedIn, GitHub, Email, Phone, Credly), and navigation to all other pages. Supports dark/light mode toggle with localStorage persistence.

### `about.html` — About Me
Personal bio, homelab setup link, location, target roles, current study goals, and a direct link to the Credly profile for verified digital badges.

### `education.html` — Education & Experience
Tabbed layout with four panels:
- **Education** — Degrees, training programs (Npower, Per Scholas), and certifications timeline
- **Certifications** — All earned and pursuing certs (Security+, ISC2 CC, Google Cybersecurity, CompTIA A+, Google IT, CFOT, Network+)
- **Experience** — Work history from DOE Field Technician / The Cyber Ledger through Accenture and earlier roles
- **Timeline** — Unified chronological view

### `skills.html` — Skills & Certifications
Visual breakdown of technical skills organized by category: Cybersecurity, Networking, Systems/IT, Cloud & Virtualization, and Tools. Includes animated skill bars and a certifications grid.

### `projects.html` — Lab Work & Projects
Filterable project card grid with categories: IT Support, Networking, Cybersecurity, and Cloud/Virtualization. Each card shows status (In Progress / Upcoming), tech tags, and links to detail pages where available.

**Project statuses:**
| Project | Status |
|---|---|
| Active Directory Home Lab | 🟡 In Progress |
| Ticketing System (osTicket) | 🟣 Upcoming |
| pfSense Firewall & VLAN Segmentation | 🟣 Upcoming |
| WireGuard VPN Server | 🟣 Upcoming |
| SIEM Deployment with Splunk | 🟣 Upcoming |
| Vulnerability Scanning with Nessus | 🟣 Upcoming |
| Malware Analysis Sandbox | 🟣 Upcoming |
| Proxmox Virtualization Cluster | 🟣 Upcoming |
| Docker Self-Hosted Stack | 🟣 Upcoming |

### `active-directory.html` — Active Directory Home Lab
Dedicated detail page for the Enterprise Windows Server 2025 AD & SIEM lab. Includes lab topology, objectives, what was built, key learnings, outcomes, snapshot gallery, and sidebar with environment specs, monitored event IDs, GPO list, and skills demonstrated.

**Lab Stack:** VirtualBox · Windows Server 2025 · Windows 11 · Splunk Enterprise · Sysmon · Ubuntu Server 24.04

### `osticket.html` — Ticketing System (osTicket)
Dedicated detail page for the self-hosted osTicket helpdesk lab. Covers LAMP stack deployment on Ubuntu, department routing, SLA configuration, email piping, agent roles, and the full ticket lifecycle walkthrough.

**Lab Stack:** VirtualBox · Ubuntu Server 22.04 · Apache · MySQL · PHP · osTicket v1.18

### `contact.html` — Contact
Contact card with email, phone, LinkedIn, GitHub, and Credly links. Includes a fixed dark/light mode toggle.

---

## 🎨 Design System

| Element | Value |
|---|---|
| Primary font | Sora |
| Display font | Playfair Display |
| Mono font | JetBrains Mono |
| Accent font | Raleway (headings/logo) |
| Dark bg | `#050c1a` |
| Light bg | `#f0f4ff` |
| Cyan accent | `#22d3ee` |
| Blue accent | `#2563eb` |
| Green (IT) | `#34d399` |
| Violet | `#a78bfa` |
| Amber | `#fbbf24` |

**Features across all pages:**
- Dark / light mode toggle (persists via `localStorage`)
- Animated particle network canvas background
- Ambient orb blur effects
- Scroll progress bar
- Back to top button
- Mobile hamburger menu
- Scroll reveal animations
- BL monogram favicon (`favicon.svg`)

---

## 🚀 Deployment

This site is deployed via **GitHub Pages** from the root of the repository. No build step required — push HTML files directly and they go live.

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, glassmorphism, grid/flexbox, animations
- **Vanilla JavaScript** — theme toggle, canvas animation, scroll effects, hamburger menu
- **No frameworks** — zero dependencies, no npm, no build tools

---

## 📜 License

Personal portfolio — all content, design, and code by **Baltazar Laborte**.  
Feel free to use as inspiration; please do not copy directly.

---

*Built and maintained by Baltazar Laborte · [baltazarlaborte@gmail.com](mailto:baltazarlaborte@gmail.com) · [linkedin.com/in/baltazarlaborte](https://www.linkedin.com/in/baltazarlaborte/)*
