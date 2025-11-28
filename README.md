<div align="center">

# 🦅 SilentKey
### The Open-Source Dead Man's Switch
**Protect your digital legacy. Secure your infrastructure.**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](LICENSE)
[![Status: In Development](https://img.shields.io/badge/Status-In_Development-orange)](https://github.com/silentkey-dev/silentkey)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsilentkey.dev)](https://silentkey.dev)

[Website](https://silentkey.dev) • [Roadmap](#-roadmap) • [Enterprise](https://silentkey.cloud/enterprise)

</div>

---

## 🧐 What is SilentKey?

**SilentKey** is a modern, self-hosted **Dead Man's Switch**. It is currently under active development.

It monitors your activity (heartbeat) and triggers pre-defined actions if you become unavailable due to death, accident, or emergency. Unlike legacy solutions, SilentKey is designed for the modern web—supporting **Webhooks**, **Crypto wallets**, and **Zero-Knowledge encryption**.

### The Problem
* **Digital Legacy:** If you pass away today, will your family be able to access your photos, bank accounts, or crypto assets?
* **The "Bus Factor":** If your lead DevOps engineer goes offline, does your company lose access to its servers?
* **Trust:** Existing SaaS solutions require blind trust. Scripts are too fragile.

### The Solution
SilentKey provides a secure, automated system to distribute the right secrets to the right people, strictly when needed.

---

## ✨ Planned Features

SilentKey is built on a **Zero-Knowledge Architecture**. Data is encrypted client-side using OpenPGP/AES before it ever touches the database. We cannot read your secrets.

### 📦 Multi-Recipient Vaults (Digital Vaults)
Don't send everything to everyone. Create granular vaults:
* **Family Vault:** Unlocks Bank details & Photos for your partner.
* **Business Vault:** Unlocks AWS Root Keys & GitHub access for your co-founder.
* **Legal Vault:** Sends your Will to your lawyer.

### 🔗 Beyond Email: Webhooks & Automation
SilentKey isn't just an email sender. It's an automation trigger:
* **Webhook support:** Trigger workflows in n8n, Zapier, or Make.com.
* **API Actions:** Automatically shut down servers or wipe data remotely.
* **Social Media:** Post a final message to LinkedIn or Twitter.

### 🛡️ Crypto-First Security
* **Shamir's Secret Sharing:** Securely split your crypto Seed Phrase. The server holds only one shard, making it mathematically impossible for us (or hackers) to steal your wallet.
* **Panic Button:** Immediately trigger (or destroy) data in case of duress.

---

## 🗺️ Roadmap

We are building SilentKey in public. Here is our plan:

- [ ] **Phase 1: The Foundation (MVP)**
    - Core Heartbeat Logic (Check-ins).
    - Client-side Encryption (Zero Knowledge).
    - Basic Email Triggers.
    - Docker Container for Self-Hosting.

- [ ] **Phase 2: Connectivity**
    - Webhook Integrations (n8n, Zapier).
    - "Digital Vaults" (Multi-recipient support).
    - Shamir's Secret Sharing Tool.

- [ ] **Phase 3: Enterprise & Cloud**
    - SaaS Launch (Managed Hosting).
    - SSO (Single Sign-On).
    - Audit Logs & Compliance features.
    - 

## ⚖️ License & Business Model

SilentKey is an **Open Core** project, ensuring it remains sustainable and open.

### Community Edition (AGPLv3)
The core of SilentKey is free and open-source software licensed under the **GNU Affero General Public License v3 (AGPLv3)**.
* ✅ Free for personal and hobby use.
* ✅ Free for internal non-commercial use.
* ⚠️ If you modify the code and offer it as a service to others, you **must** open-source your modifications.

### Enterprise Edition (Commercial)
For companies requiring:
* 🚀 Single Sign-On (SSO).
* 📝 Compliance Audit Logs.
* 👮‍♂️ Approval Workflows.
* 💼 Exemption from AGPL obligations (Proprietary modifications).

*Contact info for licenses coming soon.*

---

<div align="center">
  <sub>Built with ❤️ by <b>Krpasoft</b>.</sub><br>
  <sub>Copyright © 2025 Krpasoft. All rights reserved.</sub>
</div>
