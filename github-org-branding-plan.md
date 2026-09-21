# GitHub org branding — SchemaFirst

Build sheet for [github.com/SchemaFirst](https://github.com/SchemaFirst). Visuals match [www.schemafirst.org](https://www.schemafirst.org): schema-bracket mark, Geist wordmark, teal `#1FBAB0`.

**Decided:** org login `SchemaFirst` (GitHub is case-insensitive; `schemafirst` resolves here). Canonical site `https://www.schemafirst.org`.

## 0. Name drift (do not skip)

The org is SchemaFirst. These still say LKSY / lksy.org / `lksy-org`:

| Surface | Current |
| --- | --- |
| Site GitHub buttons / footer | `github.com/lksy-org/community-standards` |
| Site X/Twitter | `twitter.com/lksyorg` |
| `lksy.org` | error / not the SchemaFirst site |
| This backend repo (`LKSY`) | `api.lksy.org`, `mcp.lksy.org`, GCP `lksy-org` |
| Standards repo | `lksy-org/community-standards` |
| List metadata `title` suffixes | `\| lksy.org` |

Until those move, the org README points at both. Confirm before transferring `community-standards` or retargeting the site.

## 1. Tokens

| Token | Value |
| --- | --- |
| Brand teal | `#1FBAB0` (`oklch(0.70 0.12 180)`) |
| Dark bg | `#020303` |
| Foreground | `#E8E8E8` |
| Muted (`.org`) | `#888888` |
| Light bg | `#F4F6F6` |
| Type | Geist / Geist Mono |
| Wordmark | **SchemaFirst** + muted `.org` |
| Mark | Dark rounded square, teal brackets, three bars (teal / white / muted) |

## 2. Org profile (Settings → General / Profile)

| Field | Value |
| --- | --- |
| Name | `SchemaFirst.org` |
| Description | Universal, openly governed standards for publishing authoritative organizational context so any compatible AI starts from the same source of truth. |
| URL | `https://www.schemafirst.org` |
| Avatar | https://schemafirst.org/brand/org-avatar-512.png |
| Twitter | leave empty until a SchemaFirst handle exists (`@lksyorg` is the old one) |
| Verified domain | add `schemafirst.org` (DNS TXT from GitHub) |

API cannot upload the avatar; use the Profile picture control.

## 3. Org profile README

Special public repo named `.github` with `profile/README.md`. Source in this repo.

## 4. Per-repo social preview

GitHub: Settings → General → Social preview → https://schemafirst.org/brand/social-preview-1280x640.png (1280×640). Wordmark: https://schemafirst.org/brand/logo-horizontal-dark-bg.svg

## 5. Community health (this `.github` repo)

Defaults for every repo in the org: `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`.

## 6. Presentation

- Pin standards (and later website) repos once they live here
- Topics: `schemafirst`, `brand-schema`, `gtm`, `ai-context`, `open-standards`
- Badges: shield color `%231FBAB0`, `labelColor=020303`

## 7. Assets (canonical)

Hosted on the site. Copies also live in [SchemaFirst/.github/brand](https://github.com/SchemaFirst/.github/tree/main/brand).

| URL | Use |
| --- | --- |
| https://schemafirst.org/brand/org-avatar-512.png | Org avatar |
| https://schemafirst.org/brand/social-preview-1280x640.png | Repo OG |
| https://schemafirst.org/brand/logo-horizontal-dark-bg.svg | Wordmark on dark |

## Checklist

- [x] Org display name, description, website URL
- [ ] Upload org avatar (`org-avatar-1000.png`)
- [x] Public `.github` repo with `profile/README.md`
- [x] Org-wide CoC, contributing, security, support
- [ ] Verify domain `schemafirst.org`
- [ ] Social preview on each public repo
- [ ] Pin repos after transfer
- [ ] Retarget site GitHub/Twitter links from `lksy-org` / `@lksyorg`
- [ ] Twitter/X handle for SchemaFirst
