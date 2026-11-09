<h1 align="center">0xS3J4D</h1>

<p align="center"><b>Cybersecurity student · threat intelligence · digital forensics · detection engineering</b><br>
I take real attacks apart and build tools for the people who defend against them.</p>

<p align="center">
<img alt="Focus" src="https://img.shields.io/badge/focus-CTI%20%C2%B7%20DFIR%20%C2%B7%20detection-2dd4bf">
<img alt="Region" src="https://img.shields.io/badge/region-Norway%20%F0%9F%87%B3%F0%9F%87%B4-0b1220">
<img alt="Open to" src="https://img.shields.io/badge/open%20to-internships%20%26%20graduate%20roles-f59e0b">
</p>

---

## About

I'm a cybersecurity student in Norway. Most of my work is on threats against Norwegian users, like smishing, BankID fraud and account takeover, and on the forensic side of finding out what happened afterwards.
I write up everything I analyse in both English and Norwegian. I redact sensitive data and map my findings to MITRE ATT&CK.

*🇳🇴 Cybersikkerhetsstudent med fokus på trusseletterretning, digital etterforskning og deteksjon, særlig trusler mot norske brukere.*

## Projects

### 🔎 [BankID Smishing Kit Analysis](https://github.com/0xS3J4D/phishing-analysis)
A smishing SMS reached me in my real BankID message thread. The link said `bankld` (with an L, not an i), so I took the kit apart instead of logging in. It collects the victim's national ID, one-time code and password in five steps and sends every field to a Telegram bot in real time.
`PHP/JS analysis` `CTI` `MITRE ATT&CK` `YARA` `IOC extraction` · Report in English and Norwegian

### 🧪 [Tracelume](https://github.com/0xS3J4D/tracelume)
An open source digital forensics workbench. It puts phones, disks, memory and logs into one offline case, with a single timeline, deleted-data recovery, SQL on phone databases, and PDF reports with a hash-chained chain of custody. Each tool runs in its own isolated container.
`Python` `FastAPI` `React` `Docker` `ALEAPP/iLEAPP` `Volatility 3` `The Sleuth Kit` · GPL-3.0

## Toolbox

| Area | Tools |
|---|---|
| Threat intel and detection | MITRE ATT&CK · YARA · IOC handling · TLP |
| Forensics | Volatility 3 · The Sleuth Kit · ALEAPP / iLEAPP · ExifTool · Plaso |
| Development | Python · FastAPI · React · Docker · PostgreSQL · Bash |
| Platforms | Linux · Windows |

## How I work

- **Ethics first.** I only analyse what I'm authorised to analyse, I never touch live criminal infrastructure, and I redact sensitive data before publishing.
- **Reproducible.** Every project has source files, a build script and a changelog.
- **Two languages.** Reports are written in English and Norwegian.

## Contact

Connect with me through LinkedIn (linked in the sidebar) or open an issue in any of my repositories.

<p align="center"><sub>All research is for defensive and educational use.</sub></p>
