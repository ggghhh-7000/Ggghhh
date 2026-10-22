# 🐷 Pig365 – Dual-Root Domain (IDN/ASCII) Architecture
# webdev
# domain
# cloudflare-users
Hello all X seniors and partners:

I want to share with everyone the recent independent design, development and deployment works of Chinese children: **Pig365**.

To help children understand the real-world Internet infrastructure and DNS operation principles in practice, we used Cloudflare experiments and established the **"Double Root Domain DNS (IDN & ASCII) System"**:

🌐 **Network architecture configuration:**

1. `pig365.xyz / or pig365.pro / pig365.vip` — main ASCII application and component service domain

2. `豬豬集團.xyz / or 豬豬集團.pro / 豬豬集團.vip` (`xn--ndsx45ja417h.xyz`) — Chinese IDN publishing and content display domain (such as Publishing.豬豬集團.xyz)

🛠️ **Project modules and technical highlights:**

* **Modular Component Ecosystem**: The project includes frontend components such as `SS` (lightweight static service) (e.g., pig ss meet: https://3000-idfj1lbwdo4g4r1icxx1s-02b9cc79.sandbox.novita.ai/ww), `WW` (web display module), and `Ue` (user experience and interaction module).

* **DNS level IDN & Punycode translation**: Allows Chinese domain names to function in native internet resolution.

* **Canonical 301 Redirect and Brand Alignment**: Establish a standard URL and redirect the traffic from the publishing domain to the main service.

* **Cloudflare Edge Routing & SSL**: Multi-domain edge routing and edge certificate issuance with no backend maintenance burden.

The project is completely open source and hosted on GitHub:

🔗 **GitHub Project Library**: https://github.com/ggghhh-7000

We are very welcome for the architects and senior engineers in the community to give children some architectural suggestions, exchange ideas, or give a ⭐ Star encouragement! Thank you all for supporting the programmers who explore programming independently for the next generation!

my cloudflare-account “ggghhh157@outlook.com”
