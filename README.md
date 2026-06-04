


---

<div align="center">

## ⬡ Core Domains

</div>

<table align="center">
<tr>
<td><b>MCP</b></td>
<td>AI agent orchestrator · MCP vuilnerability finder · MCP on security tools</td>
</tr>
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
| [**Timeseal** ](https://github.com/Teycir/Timeseal) | Time-locked encryption vault · Dead Man's Switch · AES-256 split-key | `TypeScript` `Next.js` `CF Workers` |
| [**Sanctum** ](https://github.com/Teycir/Sanctum) | Zero-trust vault · XChaCha20-Poly1305 · Argon2id · Plausible deniability | `TypeScript` `Next.js` `CF Workers` |
| [**Ghostreceipt**](https://github.com/Teycir/Ghostreceipt) | ZK payment proofs · PII redaction · Multi-chain consensus oracle | `TypeScript` `Next.js` `CF Workers` |
| [**GhostChat**](https://github.com/Teycir/GhostChat) | True P2P encrypted chat · WebRTC · serverless · self-destructing | `TypeScript` `Next.js` `CF Workers` |
| [**TrustCircle**](https://github.com/Teycir/TrustCircle) | File timestamping vault on IPFS | `TypeScript` `Next.js` `CF Workers` |

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
| [**APIHunter**](https://github.com/Teycir/ApiHunter) | Scrapes fast hundreds of APIs and finds vulnerabilities, bypasses WAF and uses YAML patterns that are extensible | `Rust` |
| [**DiffCatcher**](https://github.com/Teycir/DiffCatcher) | Git repo discovery · diff capture · code element extraction | `Rust` |
| [**ZkPatternMatcher**](https://github.com/Teycir/ZkPatternMatcher) | YAML-pattern vuln detection for ZK circuits | `Rust` |
| [**SeekYou**](https://github.com/Teycir/SeekYou) | OSINT on IP / domain / ASN | `TypeScript` `Next.js` `CF Workers` |
| [**IotScanner**](https://github.com/Teycir/IotScanner) | IoT device vulnerability scanner | `Python` |
| [**McPwn**](https://github.com/Teycir/Mcpwn) | MCP vulnerability scanner | `Python` |
| [**honeypotscan**](https://github.com/Teycir/honeypotscan) | Honeypot token scanner · 13 scam patterns · ETH/Polygon/Arbitrum | `TypeScript` `Next.js` `CF Workers` |
| [**Checkapis**](https://github.com/Teycir/checkapis) | Checks LLM API validity and status in batches then reports | `TypeScript` `Next.js` `CF Workers` |


---

## 🤖 MCP

| Project | Description | Tech |
|:--------|:------------|:-----|
| [**Butler**](https://github.com/Teycir/Butler) | Persistent Coordination and Memory Layer for AI Coding Agents. | `Typescript` |
| [**McPwn**](https://github.com/Teycir/Mcpwn) | Automated MCP server security scanner · RCE · path traversal · prompt injection · protocol fuzzing · semantic detection · SARIF output | `Python` |
| [**burp-mcp-server**](https://github.com/Teycir/burp-mcp-server) | MCP server for Burp Suite Professional · vulnerability scanning · issue retrieval · HTTP proxying via AI assistants | `JavaScript` |
| [**nmap-mcp**](https://github.com/Teycir/nmap-mcp) | MCP server for Nmap · stealth recon · vuln/NSE scanning · OS detection · firewall evasion · red team ops | `Python` |
| [**nuclei-mcp**](https://github.com/Teycir/nuclei-mcp) | MCP server for Nuclei · multi-target scanning · severity filtering · template browsing · rate control | `TypeScript` |
| [**frida-mcp**](https://github.com/Teycir/frida-mcp) | MCP server for Frida · dynamic instrumentation · SSL pinning bypass · Java/ObjC hooking · mobile red teaming | `Python` |
| [**adb-mcp**](https://github.com/Teycir/adb-mcp) | MCP server for Android Debug Bridge · USB/network device control via AI assistants | `Python` |
| [**ripgrep-mcp**](https://github.com/Teycir/ripgrep-mcp) | MCP server exposing ripgrep · fast regex code search for AI-driven code audits | `Python` |

> A suite of MCP servers turning best-in-class security tools into AI-callable primitives — scan, instrument, and audit from any MCP-compatible client.

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

