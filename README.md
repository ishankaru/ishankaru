# Ishan Karunaratne

**Software systems architect · Chief Technology Officer**

I have been building and running production systems since the late 1990s, through the eras when
the hard problem moved from networks to servers to databases to architecture to teams, and lately
to AI. The job keeps changing shape. The underlying question never does: what happens when this
breaks, and who finds out first.

I served in the US Army as a Fire Direction Specialist, including a deployment to Iraq for
Operation Iraqi Freedom, several years into an IT career rather than before it. Computing firing
solutions teaches you quickly that checklists and verification are not bureaucracy.

I still write code most weeks. A technology leader who has not touched the stack in years is
guessing, and the team can always tell.

---

## What I build

### [DNS Checker](https://dnschkr.com)

A DNS and network intelligence platform that processes **more than 240 million domains a day**
across **1,900+ TLDs**, with 48 million held in the live index and **47 tools** spanning DNS,
email authentication, HTTP, hashing and domain research.

Most DNS tools resolve one record against one resolver and leave you to interpret it. DNS Checker
runs a full inspection, propagation across global resolvers, DNSSEC validation, SPF, DKIM and
DMARC analysis, blacklist status, HTTP security headers, then scores the result so a problem is
visible at a glance. A novice sees plain language and a verdict; an engineer sees the raw records
underneath. Free, no signup.

The interesting part is not the checks, it is the substrate. A quarter of a billion domains a
day is a continuous ingestion problem rather than a query problem: zone files for 1,900+ TLDs
arrive on different schedules in different formats and sizes, resolvers disagree with each other,
a negative answer has to be told apart from a timeout, and the index has to stay queryable while
it is being rewritten underneath live traffic. It runs on Elasticsearch behind a hand-built API,
and I designed, wrote and operate every layer of it, including the servers it sits on. No one
else has ever had a commit in it.

### [TechEarl](https://techearl.com)

A technical reference library of **793 articles**, of which **94 are interactive**.

The cheat sheets are the reason it exists. Instead of static command examples you copy and then
edit by hand, the parameters are live inputs: set your device, path, hostname or thread count
once and every command on the page rewrites itself, persisting per reader. Alongside those are
purpose-built calculators, including a chmod permission calculator, a crontab expression builder,
a hashcat attack builder and a yt-dlp command builder. That interaction model is the part you do
not get on other reference sites.

Everything is written from production work rather than rewritten from documentation, which is why
the caveats are in there: the BSD and GNU divergences, the version where a default changed, the
flag that silently does nothing.

### [Lipwalk](https://lipwalk.com)

Embeddable comments that are funded by subscriptions instead of by selling readers. One script
tag adds threaded discussion, reactions and star ratings, with AI moderation handling spam and
toxicity before you see it. Ships with a REST API, webhooks and TypeScript SDKs, and emits
AggregateRating markup so review stars can surface in search results.

### [American Lawyers Directory](https://americanlawyersdirectory.com)

An attorney directory across 51 states and DC built on state bar records rather than paid
placement. The constraint is structural: no firm owns it, and no listing position can be bought.

### Also running

[WPPaste](https://wppaste.com), a paste bin that recognises WordPress functions and hooks in a
snippet and links each one to its documentation. [Lyrics LK](https://lyrics-lk.com) and
[Chords LK](https://chordslk.com), because Sri Lankan music is badly served online and the
archive I wanted did not exist.

---

## How I work

**Architecture.** The shape of a system before anyone writes code: the data model, the failure
modes, where load lands, what happens at 3am when a dependency disappears.

**Security.** I came up reverse engineering and debugging at the instruction level. Every system
I have designed since treats security as part of the architecture rather than a hardening pass
the week before launch.

**Leadership.** Technical strategy, hiring and delivery, including M&A integrations and cloud
migrations. Currently CTO at Rehab Media Group, where the platforms connect millions of people
across the United States with addiction treatment and recovery resources.

**AI.** LLM applications, retrieval-augmented generation, agents, and the evaluation harnesses
that catch regressions before users do. The interesting question is rarely whether a model can do
something, it is whether the output is reliable enough to put in front of a customer.

---

## Activity

| | |
|---|---|
| Commits authored | **4,400** |
| In private repositories | **4,332** (98%) |
| Merged pull requests | **382** |
| Repositories | 100 (32 public, 68 private) |

Most of the work is not visible here. The public repositories are labs, references and tooling
that accompany the writing; the platforms above and the client and employer work behind them live
in private repositories.

**Primary languages by repository:** TypeScript, JavaScript, PHP, Python, Shell, Go.

---

## Stack

`TypeScript` `Node.js` `PHP` `Python` `Bash` `SQL` · `MySQL` `PostgreSQL` `Elasticsearch` `Redis` `ClickHouse`
`AWS` `GCP` `Cloudflare` `Docker` `Kubernetes` `Terraform` · `Linux` `Nginx` `DNSSEC` `SPF/DKIM/DMARC`
`React` `Next.js` `WordPress`

## Credentials

| | |
|---|---|
| 2010 | Charles Sturt University, Bachelor's degree, online systems |
| 2009 | CompTIA A+, Network+, Security+ |
| 2006 | Prosoft Certified Internet Webmaster (CIW) Professional |
| 2005 | Cisco CCNA coursework |
| 2002 | Principal Certified Lotus Professional, IBM Domino R5 Application Development |
| 1999 | Diploma in Advanced Programming Techniques, Unix and C, shell scripting |

ORCID [0009-0002-3088-0769](https://orcid.org/0009-0002-3088-0769)

---

**[ishankarunaratne.com](https://ishankarunaratne.com)** · [LinkedIn](https://www.linkedin.com/in/ishankarunaratne/) · [ORCID](https://orcid.org/0009-0002-3088-0769) · [X](https://x.com/ishankaru)

Open to hands-on development work, which is still the part I enjoy most, alongside advisory,
technical due diligence, architecture review and fractional CTO engagements.
