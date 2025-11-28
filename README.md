<div align="center">

# 🦅 SilentKey
### The Open-Source Dead Man's Switch
**Protect your digital legacy. Secure your infrastructure.**

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](LICENSE)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsilentkey.dev)](https://silentkey.dev)

[Website](https://silentkey.dev) • [Documentation](https://docs.silentkey.dev) • [Enterprise](https://silentkey.cloud/enterprise)

</div>

---

## 🧐 What is SilentKey?

**SilentKey** is a self-hosted, secure dead man's switch. It monitors your activity and triggers pre-defined actions if you become unavailable (due to death, accident, or emergency).

It is designed to solve two critical problems:
1.  **Digital Legacy:** Passing crypto keys, passwords, and sentimental messages to family members.
2.  **The "Bus Factor":** Ensuring business continuity (server access, domains) if a key team member goes missing.

Unlike other solutions, **SilentKey is Zero-Knowledge**. All data is encrypted client-side. We (or your server admin) cannot read your secrets.

## ✨ Key Features

* **🔐 Zero-Knowledge Architecture:** Data is encrypted in your browser using OpenPGP/AES before it ever touches the server.
* **📦 Multi-Recipient Vaults:** Create separate vaults for different people.
    * *Wife* gets access to bank accounts and photos.
    * *Co-founder* gets AWS keys and GitHub repository admin rights.
* **🔗 Webhooks & Integrations:** Don't just send emails. Trigger a webhook to:
    * Shutdown/Wipe servers via API.
    * Post a "Final Tweet".
    * Send a message to a Slack/Discord channel.
* **🛡️ Shamir's Secret Sharing:** Securely split crypto seed phrases. The server only holds *one* shard of the key, making it mathematically impossible to hack your wallet from the server side.
* **❤️ Heartbeat Monitoring:** Check-in via email link, API ping, or active device monitoring.
