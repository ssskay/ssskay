# Hi, I'm Sara 👋

`she/her` · Site Reliability Engineer @ IBM (HashiCorp) · tool gremlin 🐹

I build systems that keep running when nobody's watching — that's the day job
(observability platform, IBM/HashiCorp) and, it turns out, it's also what I do
for fun. Scrapers that survive a flaky upstream. Pipelines that ship the same
number today they shipped yesterday. Retry logic that treats a busy server as
weather, not failure.

I'd rather spend a weekend building the thing than an afternoon hunting for one
that almost fits — usually with a coding agent riding shotgun on the frontend so
I can focus on the data underneath.

🔗 [LinkedIn](https://www.linkedin.com/in/ssskay/) · [Substack](https://newsletter.datagremlingobrr.com) · [sarakay.me](https://sarakay.me)

---

# ⭐ Stuff I've built

## 🗓️ Open-data pipelines

I forked a scraping engine that already works and pointed it at information that
didn't have one yet.

#### 📚 [MangaRelease](https://mangarelease.github.io)

An automated, open-data release calendar for licensed English manga, manhwa,
manhua & webtoons.

*Under the hood:* a scraper fleet against 15+ publisher sites, running unattended
on a daily GitHub Actions schedule, normalizing wildly inconsistent upstream
formats into a single stable dataset. The full corpus ships as CSV — a public
data contract, so anyone's agents can build on it. An extensive fork of
[LNRelease's light-novel calendar](https://github.com/LNRelease/lnrelease.github.io) (MIT).

Repo: [github.com/mangarelease/mangarelease.github.io](https://github.com/mangarelease/mangarelease.github.io)

---

## 🤖 Agentic tools

Claude Code skills adapted from real problems I've encountered, nicely packaged
for anyone to use.

#### 🏛️ [internet-historian](https://github.com/ssskay/internet-historian)

A patient Wayback Machine archiver for macOS. It treats a busy Internet Archive
as weather rather than failure, and retries until your pages are actually
preserved. You can tell it to archive the websites related to the things you love
most, and walk away.

*Under the hood:* the whole design problem is telling a transient failure from a
permanent one. Backoff, resumable state, and idempotent retries against an
upstream that rate-limits you for existing. `pipx install internet-historian` for
the non-agent version.

#### 📖 [wiki-gap-finder](https://github.com/ssskay/wiki-gap-finder)

Finds people from underrepresented groups who are missing from English Wikipedia,
then fact-checks every claim into a research dossier. The AI does the detective
work; a human writes every sentence of the article. No API keys needed.

#### 📦 [inbox-catalog](https://github.com/ssskay/inbox-catalog)

Turns your order emails into structured purchase data your agents can use: sort
purchases by project, track spending in categories that match how you actually
think, stop re-buying things you already own.

*Under the hood:* deliberately **local-first and read-only**. Your mail never
leaves your machine and the tool cannot write to your inbox — the boundary is
the feature.

---

## 🎁 Free stuff engines

#### 🎁 [freestuff-template](https://github.com/ssskay/freestuff-template)

A school-agnostic engine for an agent-maintained catalog of free student and alum
perks. Searchable list, campus map, weekly automated link checker so the catalog
doesn't quietly rot. Fork it for your school!

#### 🌲 [Free Stuff @ Dartmouth](https://github.com/ssskay/freestuff-dartmouth-v2)

The Dartmouth reference build. I started making this site freshman year and
thanks to agents, now future freshmen can actually find everything the school
already pays for.

---

## 🖥️→🍎 Desktop pet rescue

I adopt cute Windows-only desktop apps and give them a second life on macOS. The
original developers did the hard, lovely work — I do the porting, the Mac-specific
bug hunts, and the extra bonus features. Every fix goes back upstream.

#### 🐰 [Yaha-Pet for macOS](https://github.com/ssskay/Yaha-Pet)

Port of [gitChara-dot's Yaha-Pet](https://github.com/gitChara-dot/Yaha-Pet) (MIT).
Usagi, Hachiware & Chiikawa roam your desktop, squeak when grabbed, and live in
your Dock. Fixed a crash and an animation bug along the way —
[offered upstream](https://github.com/gitChara-dot/Yaha-Pet/pull/2).

#### 🍙 [Desktop Chiikawa for macOS](https://github.com/ssskay/desktop-chiikawa-macos)

Port of [CookieElmo's Desktop Chiikawa](https://cookieelmo.itch.io/desktop-chiikawa),
the wellness-reminder pet from itch.io — rebuilt on the native Godot runtime with
wandering, petting, snacks, and kaomoji speech added. It tells you to drink water.
It remembers where you left it.

---

## 🔧 Currently into

SRE / observability · agentic AI side projects · Chiikawa · wooden pins & anime ·
charity making with [Gremlin Goods](«link or drop»)

> Code is a medium of self-expression. I just express mine in gremlin.
