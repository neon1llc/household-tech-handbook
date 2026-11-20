# Household tech handbook

**A handbook for the person who looks after a family's devices and accounts.** Passwords, backups, the router, kids' first phones, helping aging parents, and what to do when something breaks.

From [neon1](https://neon1.tech).

**Status:** stable. Accuracy and source updates only, no new modules for now.

---

You're the person everyone calls when the Wi-Fi drops, a parent's phone is full, or a strange text arrives. You don't need to be an expert. This handbook helps you set things up once so you stop fixing the same problems.

## What's inside

| Folder | What it holds |
|---|---|
| [`handbook/`](handbook/index.md) | Twelve chapters, from mapping your household's tech to planning for emergencies. |
| [`templates/`](templates/index.md) | A household tech sheet, a device inventory, an emergency card, and an account recovery sheet. |
| [`checkups/`](checkups/index.md) | A yearly checkup, a new device checklist, and a checklist for visiting parents. |

## Start here

1. Read [chapter 1](handbook/01-household-map.md) and fill in the [household tech sheet](templates/household-tech-sheet.md). It takes an evening.
2. Do [accounts](handbook/02-accounts-and-passwords.md) and [backups](handbook/03-backups.md) next. They prevent the two worst days: losing an email account and losing the photos.
3. Put the [yearly checkup](checkups/yearly-checkup.md) on the calendar.

## Related

- [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go): step-by-step practice cards and playbooks. The handbook links to them.
- [Phishing Awareness Kit](https://github.com/neon1llc/phishing-awareness-kit): a session kit on scams for a family, senior center, or classroom.
- [SOC 2 Readiness](https://github.com/neon1llc/soc-2-readiness): training for when the household becomes a business.

## Checking a change

```
node tools/check.mjs    # front matter on every page, and no broken links
```

## Licenses

| What | License | What it means |
|---|---|---|
| Written material (everything except `tools/` and `.github/`) | [CC BY-SA 4.0](LICENSE) | Share, teach from, and adapt it, even commercially. Credit it as *"Based on Household Tech Handbook by neon1 (neon1.tech), CC BY-SA 4.0"* and share changes under the same license. |
| Code (`tools/`, `.github/`) | [MIT](LICENSE-CODE) | Use it for anything, keeping the copyright notice. |
| The Household Tech Handbook and neon1 names and the neon1 logo | Reserved | Not covered by either license. See [TRADEMARK.md](TRADEMARK.md). |

Household Tech Handbook is © 2026 neon1 LLC. Keep the [NOTICE](NOTICE) file in copies and adaptations.

Found something wrong or outdated? See [SECURITY.md](SECURITY.md). Want to help? See [CONTRIBUTING.md](CONTRIBUTING.md).
