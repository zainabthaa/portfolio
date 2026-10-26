<div align="center">

# Zainab Taha · Cybersecurity Portfolio

**GRC · Network & Cloud Security · Security Operations**

Cybersecurity student at Effat University (GPA 3.86) building labs that attack systems, detect the attacks, and turn the detections into compliance evidence.

🌐 **Live site:** https://zainabthaa.github.io/portfolio/

[![Live site](https://img.shields.io/badge/Live_site-zainabthaa.github.io%2Fportfolio-22d3ee?style=for-the-badge)](https://zainabthaa.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-zainab--taha--cs-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zainab-taha-cs)
[![CV](https://img.shields.io/badge/CV-PDF-a78bfa?style=for-the-badge)](assets/cv/Zainab_Taha_CV.pdf)

</div>

---

## About

I'm a senior Computer Science student on the cybersecurity track at **Effat University** in Jeddah, Saudi Arabia, graduating in June 2027. My work combines the offensive side (testing and detection) with the governance side (risk and compliance). I map my results to **MITRE ATT&CK, NIST CSF, ISO 27001, NCA ECC and Saudi PDPL**.

I'm a **published co-author** on AI-based intrusion detection for energy-sector OT networks, and I co-founded Effat University's **Cyber Security Club** and **SPE Student Chapter**.

🎯 **I'm looking for a cybersecurity internship starting January 2027.**

## Featured projects

| Project | Focus | Highlights | Repo |
|---|---|---|---|
| **Purple-Team Lateral Movement Detection Platform** | SecOps · GRC · Network | A simulated company network with 13 containers on 3 subnets. It emulates 20 ATT&CK techniques and maps the detections to NIST CSF, ISO 27001 and NCA ECC | [lateral-movement-showcase](https://github.com/zainabthaa/lateral-movement-showcase) |
| **Compliance-as-Code Policy Enforcement Pipeline** | Cloud · GRC | Blocks insecure AWS infrastructure at the pull-request stage, using 10 controls and 6 Rego policy modules | [compliance-as-code-pipeline](https://github.com/zainabthaa/compliance-as-code-pipeline) |
| **NoorPay GRC Consulting Engagement** | GRC | A NIST SP 800-30 risk assessment, a GDPR/PDPL gap analysis and an incident response plan for a fintech after a breach | [noorpay-grc-assessment](https://github.com/zainabthaa/noorpay-grc-assessment) |
| **Web Application Penetration Test: SQLi & XSS** | Offensive · AppSec | SQL injection auth bypass and UNION extraction (confirmed with sqlmap), plus reflected and stored XSS with filter bypass. Written up as a 37-page report | [web-app-pentest](https://github.com/zainabthaa/web-app-pentest) |
| **Glovia: Secure Code Review & Hardening** | AppSec | A full-stack PHP/MySQL site that I later reviewed and hardened, taking Semgrep findings from 4 to 0, with 18 automated attack tests | [glovia](https://github.com/zainabthaa/glovia) |
| **Secure Banking System** | Secure software | A Java 17 / Swing banking app with PBKDF2 hashing (600k iterations) and 62 JUnit 5 tests | [banking-system](https://github.com/zainabthaa/banking-system) |

## Research

**AI-Powered Intrusion Detection for Programmable Logic Controllers in Smart Grid and Industrial Energy Networks: A Reproducible Docker-Based Simulation Platform**
Zainab Taha et al. · *Intelligent Computing for Energy and Environment (ICEE)*, Vol. 1, No. 1, 2026 · [PDF](assets/docs/ICEE_PLC_IDS_Paper.pdf)

An open, containerised IT/OT testbed that generates its own labelled traffic and detects a two-stage attack live, using rule-based detection and a Random Forest model.

## Certifications

- **CompTIA Security+**: in progress, expected January 2027
- **Cisco**: Security Operations Center (SOC) Fundamentals (2026)
- **IBM**: Containers with Docker, Kubernetes & OpenShift (2026)
- **IBM**: Introduction to DevOps (2025)

## Tech stack

`Kali Linux` `Wireshark` `sqlmap` `Docker` `Terraform` `AWS` `GitHub Actions` `Python` `Bash` `Java` `PHP` `MySQL` `Flask` `Streamlit` `scikit-learn`

---

## About this site

The site is plain HTML, CSS and JavaScript with no frameworks and no build step. It's hosted on **GitHub Pages** from the root of the `main` branch.

```
portfolio/
├── index.html        # all page content and scripts
├── styles.css        # styles (light and dark themes)
└── assets/
    ├── img/          # screenshots (WebP, max 1600px wide)
    ├── icons/        # tech-stack SVG icons
    ├── docs/         # project reports and the research paper (PDF)
    └── cv/           # CV (PDF and DOCX)
```

### Running it locally

```bash
git clone https://github.com/zainabthaa/portfolio.git
cd portfolio
python3 -m http.server 8000   # then open http://localhost:8000
```

### Updating

- Edit the content in `index.html`. Each project is an `<article class="slide">` in the Featured Projects section.
- Add images to `assets/img/` as WebP files, no more than 1600px wide.
- **Capstone screenshots:** add `assets/img/lml-soc.webp` and `assets/img/lml-grc.webp`, then uncomment the block marked `CAPSTONE SCREENSHOTS` in `index.html`.

## Contact

🌐 [zainabthaa.github.io/portfolio](https://zainabthaa.github.io/portfolio/) · 📧 [zaataha25@gmail.com](mailto:zaataha25@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/zainab-taha-cs) · 🐙 [GitHub](https://github.com/zainabthaa)
