# GitHub org branding — SchemaFirst

Build sheet for [github.com/SchemaFirst](https://github.com/SchemaFirst). Visuals match [www.schemafirst.org](https://www.schemafirst.org): mark from `/icon.svg`, type Geist, teal `#1FBAB0`.

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
| Mark | Teal rounded square, white S from site `icon.svg` |

## 2. Org profile (Settings → General / Profile)

| Field | Value |
| --- | --- |
| Name | `SchemaFirst.org` |
| Description | Universal, openly governed standards for publishing authoritative organizational context so any compatible AI starts from the same source of truth. |
| URL | `https://www.schemafirst.org` |
| Avatar | `brand/org-avatar-1000.png` (or 512) |
| Twitter | leave empty until a SchemaFirst handle exists (`@lksyorg` is the old one) |
| Verified domain | add `schemafirst.org` (DNS TXT from GitHub) |

API cannot upload the avatar; use the Profile picture control.

## 3. Org profile README

Special public repo named `.github` with `profile/README.md`. Source in this repo.

## 4. Per-repo social preview

GitHub: Settings → General → Social preview → `brand/social-preview-1280x640.png` (1280×640). Editable source: `brand/social-preview.svg`.

## 5. Community health (this `.github` repo)

Defaults for every repo in the org: `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`.

## 6. Presentation

- Pin standards (and later website) repos once they live here
- Topics: `schemafirst`, `brand-schema`, `gtm`, `ai-context`, `open-standards`
- Badges: shield color `%231FBAB0`, `labelColor=020303`

## 7. Assets (`brand/`)

| File | Use |
| --- | --- |
| `org-avatar-512.png` / `org-avatar-1000.png` | Org avatar |
| `org-avatar.svg` | Vector avatar (full-bleed teal) |
| `social-preview-1280x640.png` / `social-preview.svg` | Repo OG |
| `logo-horizontal-dark-bg.{svg,png}` | Wordmark on dark |
| `logo-horizontal-light-bg.{svg,png}` | Wordmark on light |

PNGs were rasterized on the live site so Geist is the real webfont, not a substitute. Mark path is copied from `https://www.schemafirst.org/icon.svg`.

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
