<div align="center">

<br/>

<img src="public/logo/bn-logo.png" alt="BnRamadan" width="110" />

<br/>
<br/>

# بن رمضان
### BnRamadan

**A portfolio that runs itself.**

*One engineer's work, presented by a platform built with the same care as the work it presents.*

<br/>

**Live:** [bnramadan.com](https://bnramadan.com)

`Live in production` · `18 languages` · `1.1s to content` · `All rights reserved`

<br/>

English · العربية · Français · Deutsch · Español · Italiano · Nederlands · Português · Русский · 日本語 · 한국어 · 中文 · Türkçe · Polski · हिन्दी · اردو · فارسی · Latina

<br/>

</div>

---

## The Problem

Most developer portfolios are brochures. A static list of projects, written once, in one
language, going quietly stale from the day they ship. Updating one means editing code and
redeploying, so nobody does. They are invisible to the AI assistants people now ask instead
of searching, unreadable outside English, and indistinguishable from the template they were
cloned from.

This one is a product. Everything a visitor sees is live content, not code. It speaks
eighteen languages properly, it is built to be found and quoted by both search engines and
answer engines, and it is maintained from a private control room, so it stays current
without a single line of code changing.

The site itself is the first project in the portfolio. That is the point.

---

## What It Does

**Runs entirely from a private control room.**
Projects, skills, filters, statistics, page copy, the CV and the blog: everything visible
on the site is editable data. Publishing a change takes seconds and no deployment. Nothing
a visitor reads is hardcoded anywhere.

**Speaks eighteen languages like it means it.**
Visitors are met in their own language, chosen from where they are, not from a dropdown
they have to find. Right-to-left scripts were designed from the first screen rather than
mirrored at the end. New content is translated automatically the moment it is saved, and
names that should never be translated, products, brands and technologies, are recognised
and left alone, because a machine-translated brand name reads like a broken product.

**Publishes a real blog.**
Long-form writing with the structure both readers and machines need: key takeaways, a
navigable outline, questions answered directly, related work linked in context. Written to
answer what a reader actually asked, and structured so search engines and AI answer engines
can quote it accurately instead of paraphrasing it badly.

**Is readable by machines on purpose.**
A growing share of discovery no longer happens on a results page. It happens inside an
assistant that reads, summarises and recommends on someone's behalf. The platform publishes
structured, machine-readable descriptions of itself and its work so those systems can cite
it accurately. This was built early and deliberately, before it was obvious it would matter.

**Looks right when shared.**
Every page carries a branded preview card in the right language, generated from the same
live data as the page itself. A link to this site dropped into a chat looks intentional.

**Feels instant everywhere.**
Over a thousand pages are rendered ahead of time and served from a global edge network, so
a visitor is reading before a server anywhere has done any work on their behalf. The
interface is heavily animated and interactive, an explorable 3D skills sphere, a world map
of delivered work, video previews on hover, yet it is tuned for a mid-range phone on a weak
connection first and a desktop second, and it installs to a home screen and behaves like an
app.

**Shows the work live.**
There is no static project list here to go stale. The portfolio's projects are managed in
the platform itself and presented current, each with a live demo, a video preview and a
description in the visitor's language: [browse them live](https://bnramadan.com/en/projects/allprojects).

---

## The Position On AI

AI in this product works for the owner, never on the visitor.

There is deliberately no public AI surface. No chatbot floats over the pages, no assistant
answers strangers on the site's behalf. One was built, worked well, and was removed anyway:
a public model endpoint is a running cost and an attack surface, and a portfolio earns
nothing from carrying either. That trade was measured, not guessed at.

Inside the private workspace, AI does the tedious work. It drafts project descriptions and
articles in the site's own voice from rough notes, structures a pasted CV into clean data,
translates new content into every supported language, and flags the names that must never
be translated. Every AI-written word is a draft until a person approves it. Nothing
generated reaches the public site untouched.

The tooling is held to rules that live outside the prompt: it uses only the facts it is
given, text pasted from anywhere is treated as untrusted including instructions hidden
inside it, and generation runs across multiple independent providers with automatic
failover, so no single vendor outage or rate limit stalls the owner's work.

---

## How It Is Built

The honest summary is that most of the effort in this project is not the features. It is
the discipline around them.

**Speed is a budget, not a hope.**
Every public page is prepared ahead of time; rebuilding one is the rare exception, never
the default. An automated guard runs before every deployment and fails the build if any
page could quietly become expensive to serve. Performance regressions do not reach
production by accident, because the build refuses to carry them there.

**Fresh without being wasteful.**
An edit in the control room appears on the live site within seconds, yet pages are still
served from cache worldwide. Most platforms pick one of those two properties. The design
here refuses to.

**Self-contained by rule.**
Nothing user-facing loads from a third party at runtime. A visitor running an ad blocker,
or sitting behind an unreliable network, sees the same site as everyone else. This rule
exists because its absence was once a real bug that testing on a clean machine could never
have caught.

**Destructive actions ask first.**
Nothing in the control room deletes anything on a single click, and input is validated
where it arrives rather than cleaned up after it has spread.

**The languages are the design, not a feature.**
Domain wording is defined once and reused, the typography is chosen per script, and layout,
navigation and animation all hold up in both text directions. Eighteen languages that each
look native is a different job from one language translated seventeen times.

---

## How It Is Verified

> **"A website that loads faster than you can blink."**

**Benchmarks anyone can re-run.**
The performance numbers are measurements of the live site, taken with public tools, and the
links below let a stranger take them again without trusting this document.

[![Lighthouse](https://img.shields.io/badge/Lighthouse-100%25_SEO-4285F4?logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/analysis/https-bnramadan-com/)
[![GTmetrix](https://img.shields.io/badge/GTmetrix-Grade_A-00D084?logo=gtmetrix&logoColor=white)](https://gtmetrix.com/)
[![Best Practices](https://img.shields.io/badge/Best_Practices-100%2F100-success?logo=google&logoColor=white)](https://pagespeed.web.dev/)

| Platform | Performance | SEO | Accessibility |
| :-- | :--: | :--: | :--: |
| **Google Lighthouse (Desktop)** | ![93](https://img.shields.io/badge/93-success) | ![100](https://img.shields.io/badge/100-success) | ![94](https://img.shields.io/badge/94-brightgreen) |
| **Google Lighthouse (Mobile)** | ![82](https://img.shields.io/badge/82-success) | ![100](https://img.shields.io/badge/100-success) | ![94](https://img.shields.io/badge/94-brightgreen) |
| **GTmetrix** | ![85](https://img.shields.io/badge/85-success) | ![100](https://img.shields.io/badge/100-success) | ![94](https://img.shields.io/badge/94-brightgreen) |

Real measurements from production, held against Google's own bar:

| Metric | Value | Google Standard | Status |
| :-- | :--: | :--: | :--: |
| **LCP** (Largest Contentful Paint) | `1.1s` | < 2.5s | 🟢 Excellent |
| **FCP** (First Contentful Paint) | `1.0s` | < 1.8s | 🟢 Excellent |
| **TBT** (Total Blocking Time) | `260ms` | < 300ms | 🟢 Excellent |
| **CLS** (Cumulative Layout Shift) | `0.00` | < 0.1 | 🟢 Perfect |
| **TTFB** (Time to First Byte) | `~400ms` | < 800ms | 🟢 Fast |
| **Speed Index** | `1.8s` | < 3.4s | 🟢 Fast |

```
TTFB  ━━━━                                      0.4s
FCP   ━━━━━━━━━                                 1.0s
LCP   ━━━━━━━━━━                                1.1s
TTI   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  4.4s
```

A visitor sees the main content in about one second, the page never shifts under their
finger, and the whole thing is interactive well before they have finished reading the
first line. Take the measurements yourself:
[PageSpeed Insights](https://pagespeed.web.dev/analysis/https-bnramadan-com/) · [GTmetrix](https://gtmetrix.com/)

**A build that refuses to ship known mistakes.**
The deployment pipeline runs automated guards that encode lessons already paid for once.
Configurations that would silently lose caching, or make a page expensive to serve, fail
the build with an explanation instead of reaching production. The guards are adversarial by
design: each was written after watching the mistake it now prevents actually happen.

**Checked against production, not assumptions.**
Claims about caching and speed were verified by measuring the live site's behaviour from
the outside, the way a stranger would, not by reading the code and hoping.

**Whole-repository type checking**, on every change, with no excluded corners.

**Accessibility as a floor, not a badge.**
Keyboard navigation, screen reader support, visible focus, contrast held to WCAG 2.1 AA.

---

## Security Posture

The public site is read-only by design. The private control room sits behind
authentication, privileged actions are authorised on the server rather than trusted from
the client, public write operations are rate limited, and secrets exist only in the
deployment environment, never in this repository.

**On this document specifically.**

This README deliberately contains no architecture, no directory layout, no route or
endpoint inventory, no data model, no dependency names or versions, no configuration
variable names, and no description of how any individual protection is implemented. That is
not an accident and it is not modesty.

Published implementation detail is reconnaissance. A version number is a free search
against a vulnerability database. An endpoint list is a target list. A described mechanism
is a mechanism with a known shape to work around. None of it is needed to understand what
this platform is or how seriously it was built, so none of it is here.

Security concerns are handled privately through the contact below. Please do not open a
public issue for anything security related.

---

## Status

Live in production and actively evolving. The platform is complete enough that day-to-day
work is content rather than code: new projects, new writing, the same words in eighteen
languages. When code does change, it passes through the same gates described above before
anyone sees it.

---

## License

© Mohamed Bn Ramadan. **All rights reserved.**

This repository is shared for showcase and reference only. No part of it, its design or its
content may be copied, reused, redistributed or deployed as your own. Access to this
repository grants no licence to its contents.

---

## Author

**Mohamed Bn Ramadan**
Creative full-stack engineer. Builds fast, animated, multilingual web products end to end.

[Portfolio](https://bnramadan.com) · [GitHub](https://github.com/BnRamadan) · [LinkedIn](https://www.linkedin.com/in/bnramadan/) · [Email](mailto:contact@bnramadan.com) · [WhatsApp](https://wa.me/+201025980987)

<div align="center">

<br/>

**بن رمضان**

*"Built with passion, animated with precision, deployed in seconds."*

*The site is the résumé.*

</div>
