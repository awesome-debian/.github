<h1 align="center">awesome-debian</h1>
<p align="center"><em>From "just installed Debian" to "actually contributing upstream" — one station at a time.</em></p>

---

This org is a **pipeline**, not a link dump: each repo is a station that takes you one step further on the way from a Windows user to a Debian contributor. Every station states what you need to arrive with (**Input**) and what you leave able to do (**Output**), like a real assembly line — and every guide holds itself to a "sourced, not guessed" bar, not vibes.

## The line

```
Station 1              Station 2              Station 3            Station 4                 Station 5                    Station 6
windows-to-debian  →  debian-daily-driver  →  debian-power-user  →  build-your-own-image  →  debian-first-contribution  →  debian-specialize
(switch & install)     (config, apps,          (systemd, apt         (fork a template,         (file a bug, build           (pick a Pure Blend
                        dotfiles, backups)       pinning, fix-your-    build a custom image)      your first package)          or team to keep
                                                 own-system skills)                                                            contributing to)
```

| Station | Repo | Input → Output |
|---|---|---|
| 1 | [windows-to-debian](https://github.com/awesome-debian/windows-to-debian) | A Windows user who wants to switch → a working Debian daily-driver install |
| 1.5 (companion) | [debian-hardware-and-gaming](https://github.com/awesome-debian/debian-hardware-and-gaming) | Unknown hardware compatibility → working GPU/Wi-Fi/gaming, honestly assessed |
| 2 | [debian-daily-driver](https://github.com/awesome-debian/debian-daily-driver) | A fresh install → a system you understand, configure, and back up yourself |
| 3 | [debian-power-user](https://github.com/awesome-debian/debian-power-user) | A stable system → comfortable enough to break and fix your own box |
| 4 | [debos-custom-os](https://github.com/awesome-debian/debos-custom-os) · [debos-build-action](https://github.com/awesome-debian/debos-build-action) · [live-build-iso-action](https://github.com/awesome-debian/live-build-iso-action) | Power-user skills → your own custom Debian image or bootable ISO, built via GitHub Actions |
| 5 | [debian-first-contribution](https://github.com/awesome-debian/debian-first-contribution) | Someone who can administer Debian → your first filed bug or first tiny package |
| 6 | [debian-specialize](https://github.com/awesome-debian/debian-specialize) | A first contribution → an ongoing Pure Blend or packaging team to keep contributing to (no "next" — this is the graduation point) |
| (hub) | [awesome-debian](https://github.com/awesome-debian/awesome-debian) | Curated tooling reference and community recipe directory for Station 4 |

## What every station has

- An explicit **Input/Output** contract — arrive knowing X, leave able to do Y.
- **Sourced, not guessed** content — specific claims link to where they were verified; known rough edges are stated as plainly as things that work.
- **Previous/Next** links so you always know where you are on the line.
- GitHub Actions where they earn their place — link-checking across the content-heavy guides, a real container-based test workflow in `debian-power-user`, and a `lintian`-based CI template in `debian-first-contribution` modeled on Debian's own Salsa CI pipeline. Not decoration — every workflow in this org does something a reader would actually notice if it broke.
- CC0-licensed, PRs welcome — see each repo's `CONTRIBUTING.md`.

## Have something to add?

If a station is missing a step, a link has rotted, or a compatibility claim is stale, open an issue or PR on the specific repo it belongs to — each one's `CONTRIBUTING.md` says what "on-thesis" means for that station.
