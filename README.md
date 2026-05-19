


---

<div align="center">

## ⬡ Core Domains

</div>

<table align="center">
<tr>
<td><b>API Security</b></td>
<td>CVE research · OWASP · Burp extensions</td>
</tr>

<tr>
<td><b>Cryptography</b></td>
<td>Circuit audits · SMT validation . E2E encryption</td>
</tr>

<tr>
<td><b>Red team tools</b></td>
<td>Async scanners · SARIF · CVE tooling</td>
</tr>

<tr>
<td><b>Privacy Tools</b></td>
<td>ZK proofs · XChaCha20 · Deniability</td>
</tr>
</table>

---

<div align="center">

## ⚡ Tech Stack

<img src="https://skillicons.dev/icons?i=rust,python,ts,java,solidity,bash&theme=dark&perline=6"/>
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,cloudflare,docker,linux,github&theme=dark&perline=6"/>

</div>

---

<div align="center">

## 📊 GitHub Stats

<br/>

<img src="https://streak-stats.demolab.com/?user=Teycir&theme=transparent&ring=c8960c&fire=c8960c&currStreakLabel=c8960c&sideLabels=a0a0b0&currStreakNum=ffffff&dates=a0a0b0&stroke=2a2a3e&background=0d0d0d&border=2a2a3e"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Teycir&theme=darkhub&no-bg=true&no-frame=true&column=7&margin-w=8&title=Commits,Repositories,Stars,Followers,PullRequest,Issues,Reviews"/>

</div>

---

<div align="center">

## 🏆 Active CVE Disclosures

</div>

| ID | Target | Severity | Vector | Status |
|:---|:-------|:--------:|:-------|:------:|
| GHSA-wr6f-c7g2-gmfj | `circomlib` — Underconstrained Decoder | ![](https://img.shields.io/badge/CVSS%207.1-HIGH-c8960c?style=flat-square&labelColor=0d0d0d) | ZK circuit logic | Published |
| GHSA-22mg-j6pf-g6v4 | `zkevm-prover` — Unauthenticated gRPC | ![](https://img.shields.io/badge/CVSS%207.5-HIGH-c8960c?style=flat-square&labelColor=0d0d0d) | Network exposure | Published |
| Pending | `zk-email-verify` — Signature replay | ![](https://img.shields.io/badge/CVSS%207.5-HIGH-c8960c?style=flat-square&labelColor=0d0d0d) | Cross-instance replay | Coordinated |
| Pending | `eigen-zkvm` — FFT missing canonical bound | ![](https://img.shields.io/badge/MEDIUM-c8960c?style=flat-square&labelColor=0d0d0d) | Circuit arithmetic | Coordinated |

> All findings formally validated with Z3/CVC5 SMT solvers before disclosure. No technical details released without a GHSA in place.

---

## 🌐 Privacy web applications

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**Timeseal** ](https://github.com/Teycir/Timeseal) | Time-locked encryption vault · Dead Man's Switch · AES-256 split-key | `TypeScript` |
| [**Sanctum** ](https://github.com/Teycir/Sanctum) | Zero-trust vault · XChaCha20-Poly1305 · Argon2id · Plausible deniability | `TypeScript` |
| [**Ghostreceipt**](https://github.com/Teycir/Ghostreceipt) | ZK payment proofs · PII redaction · Multi-chain consensus oracle | `TypeScript` |
| [**GhostChat**](https://github.com/Teycir/GhostChat) | True P2P encrypted chat · WebRTC · serverless · self-destructing | `TypeScript` |
| [**xmrproof**](https://github.com/Teycir/xmrproof) | Monero payment verification · 100% client-side | `TypeScript` |
| [**TrustCircle**](https://github.com/Teycir/TrustCircle) | File timestamping vault on IPFS | `TypeScript` |

---

## 🔌 Privacy Chrome Extensions

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**Sanitizit**](https://github.com/Teycir/Sanitizit) | Auto-redact PII before sharing with AI assistants | `TypeScript` |
| [**ScrambleText**](https://github.com/Teycir/ScrambleText) | Homoglyph transforms to evade AI/moderation systems | `TypeScript` |
| [**LibreWolfTorRouting**](https://github.com/Teycir/LibreWolfTorRouting) | One-click Tor routing for LibreWolf | `TypeScript` |

---

## 🛠️ Burp Suite Extensions

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**BurpAPISecuritySuite**](https://github.com/Teycir/BurpAPISecuritySuite) | 15 attack types · 108+ payloads · BOLA/IDOR detection · AI integration · OWASP API Top 10 | `Python` |
| [**BurpWpsScan**](https://github.com/Teycir/BurpWpsScan) | WordPress deep scanning extension | `Python` |
| [**BurpCopyIssues**](https://github.com/Teycir/BurpCopyIssues) | Easy issue copy extension | `Python` |
| [**BurpComplianceScanner**](https://github.com/Teycir/BurpComplianceScanner) | Compliance and regulatory scan automation | `Python` |


---

## 🔍 Security Scanners & OSINT

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**DiffCatcher**](https://github.com/Teycir/DiffCatcher) | Git repo discovery · diff capture · code element extraction | `Rust` |
| [**ZkPatternMatcher**](https://github.com/Teycir/ZkPatternMatcher) | YAML-pattern vuln detection for ZK circuits | `Rust` |
| [**SeekYou**](https://github.com/Teycir/SeekYou) | OSINT on IP / domain / ASN | `TypeScript` `Next.js` `CF Workers` |
| [**IotScanner**](https://github.com/Teycir/IotScanner) | IoT device vulnerability scanner | `Python` |
| [**honeypotscan**](https://github.com/Teycir/honeypotscan) | Honeypot token scanner · 13 scam patterns · ETH/Polygon/Arbitrum | `TypeScript` `Next.js` `CF Workers` |

---

## 🔐 ZK POC

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**zklibreports**](https://github.com/Teycir/zklibreports) | Public ZK audit reports and security analyses | `Shell` |
| [**circomlib-exploit**](https://github.com/Teycir/circomlib-exploit) | PoC for underconstrained Decoder vulnerability | `Shell` |
| [**zk-email-verify-exploit**](https://github.com/Teycir/zk-email-verify-exploit) | PoC for cross-instance signature replay | `Shell` |
| [**zkevm-prover-exploit**](https://github.com/Teycir/zkevm-prover-exploit) | PoC for unauthenticated gRPC exposure | `Shell` |
| [**fft-exploit-poc**](https://github.com/Teycir/fft-exploit-poc) | FFT circuit missing canonical bound PoC | `Shell` |

---

