# Security Policy — Dank Troll Hunt ($DTH)

We take security seriously. This document explains how to report vulnerabilities responsibly, what’s in scope, and how we handle disclosures.

---

## 📣 How to Report a Vulnerability

**Preferred method (private):**
- Open a **GitHub Security Advisory** (Security → Advisories → “Report a vulnerability”), or  
- Send a private message to the core team via **Telegram**: https://t.me/DankTrollHunt (tag: `#security`)  
- Optional email (add later): security@[your-domain]

Please **do not** open public GitHub issues for sensitive reports.

Include (as applicable):
- A clear description of the issue and potential impact
- Steps to reproduce (PoC, test account, screenshots, logs)
- Environment details (browser, OS, network, build commit/branch)
- Mitigation ideas, if any

We will acknowledge within **72 hours** and keep you updated.

---

## 🧭 Scope

In scope (current repo and official DTH infrastructure):
- Website/app code in this repository
- Staking UI integrations and front-end logic
- Public endpoints/services we publish and control
- Smart-contract repositories under the DTH organization (when published)

Out of scope:
- Third-party services and contracts we don’t control (e.g., Pump.fun, PumpSwap, Smithii, wallets)
- Social media platforms (X, Telegram, Discord) unless the issue is caused by our custom bots/integrations
- Non-security bugs (use normal GitHub issues)

---

## ✅ Responsible Disclosure & Timeline

- We work with you to validate the issue and plan a fix.
- Please allow us **up to 90 days** (or earlier if critical) before public disclosure.
- For critical, actively exploited issues, we’ll expedite fixes and share mitigations ASAP.

If you believe a vulnerability is being exploited in the wild, flag **URGENT** in your report.

---

## 🔐 Do & Don’t

**Do**
- Test only on accounts/assets you own or have permission to use
- Minimize data access; stop testing once you confirm impact
- Share PoC privately; use non-destructive methods

**Don’t**
- Exfiltrate data beyond proof-of-impact
- DoS/traffic flooding, spam, or social engineering
- Access private keys, seed phrases, or attempt funds movement

---

## 🧾 Secrets & Keys

- Never submit secrets (private keys, mnemonics, API keys) in reports.
- If you discover exposed secrets, **redact** them and notify us privately.
- We rotate/disable exposed credentials on confirmation.

---

## 📦 Dependencies & Updates

- We track and update dependencies regularly.
- Security-relevant updates are prioritized.
- If you spot a vulnerable dependency, please include:
  - Affected package + version
  - Advisory/CVE reference
  - Suggested safe version

---

## 🚨 Incident Response

For confirmed high/critical issues:
1. Contain and mitigate (temporary measures where needed)
2. Patch and validate the fix
3. Rotate credentials (if applicable)
4. Post-mortem summary (impact, fix, prevention) shared with the community when appropriate

---

## 🛡️ Safe Harbor

We won’t pursue legal action against good-faith research aligned with this policy:
- No privacy violations, data destruction, or service disruption
- No access beyond what’s required to demonstrate the issue
- Follow the responsible disclosure timeline above

If unsure whether your testing is allowed, **ask us first** via the private contact methods above.

---

## 🤝 Recognition

We appreciate responsible reports. As the project grows, we may offer recognition or bounties for impactful findings. For now, we’ll credit researchers (with consent) in release notes or a Hall of Fame.

---

**Thank you for helping keep Dank Troll Hunt and its community safe.**
