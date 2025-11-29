<p align="center">
  
<img width="100" height="100" alt="logo 100x100" src="https://github.com/user-attachments/assets/7fc4d22d-8a6b-44bf-81da-7ba8f1bfe11f" />

<h1 align="center">Cypherfucker</h1>

## TL;DR

Cypherfucker exists so that the people who care about privacy don’t have to build everything from scratch, and the people who never thought about privacy can still benefit from strong encryption by default. We write free, open, auditable software that runs on your devices, not on our servers. We dedicate it to the public domain so that it outlives us. And we treat every encrypted file as a tiny act of resistance against a world that keeps insisting that nothing should be secret anymore. 
If that resonates with you, you’re in the right place. Welcome to the collective.

# **About Us**

Cypherfucker is a small collective of geeks, privacy maximalists and cryptography nerds tired of being told that surveillance is the “price of being online”. We exist to make that trade-off obsolete — by building radically simple, radically transparent tools that let anyone encrypt, erase, and route around control without asking anyone for permission.

We’re a loose band of curious internet people who believe that the most powerful way to fight surveillance is to make strong encryption boringly easy. Our work lives in public, under [public-domain license](https://github.com/cypherfucker/about/blob/main/LICENSE), so that no company, state or platform can ever lock it away again. 

## What we build

Cypherfucker is not “one app” – it’s a growing constellation of small, sharp tools for people who care about encryption, privacy and free software more than branding and buzzwords.

At the core of what we build are three pillars:

1. **Free & Open Source** – Everything we ship is free and open source, with code living in [public repositories](https://github.com/cypherfucker?tab=repositories), open to inspection, criticism, forking and reuse. If someone can’t audit it, they shouldn’t be asked to trust it. [Licenses](https://github.com/cypherfucker/about/blob/main/LICENSE) are chosen to maximise freedom, not lock-in: we lean on highly permissive terms and **public-domain** style dedications so that our work can be mirrored, repackaged, embedded and remixed without friction or permission-seeking. 

2. **Encryption as a basic right, not a luxury** – Our projects revolve around making strong cryptography usable without a PhD, a command line, or a subscription. That includes browser-based file encryption (like our [SecureLock](https://github.com/cypherfucker/SecureLock) project, which lets you encrypt any file locally with no server ever seeing your plaintext), but also future tools for text, backups, messaging workflows and “everyday” digital hygiene. The goal is always the same: authenticated, modern crypto primitives under the hood; clear, anxiety-free interfaces on the surface. 

3. **Privacy as architecture, not a settings page** – We start from the assumption that if a system can see your data, someone will eventually try to take it: through subpoenas, breaches or corporate policy changes. So we design our tools to avoid holding that data in the first place. Local-first execution, zero-knowledge designs, no telemetry, and minimal reliance on third-party services are not “nice to have” – they are the baseline.

### A constellation of tools, not a single product

Check our **[pinned projects](https://github.com/cypherfucker/)** for our last ships

* **Encryption utilities for real life, not lab demos**
  Small, focused tools that handle specific pain points: encrypting folders before they hit cloud storage, scrubbing metadata from files, sharing secrets in ways that don’t require trusting a random proprietary app, and more. Each tool is built to stand alone, but also to fit into a broader pattern: give users control over their plaintext, not just their passwords.

* **Privacy-preserving workflows**
  We’re interested not only in “one-shot” tools, but in workflows: how journalists exchange drafts with sources, how activists move photos and videos, how ordinary people back up their personal archives. Our projects aim to make these flows safer without asking people to completely change their habits or learn an entire new ecosystem.

* **Reference implementations for the wider FOSS world**
  Because our repos are open and permissively licensed, we consciously build them as templates others can steal. A simple, well-documented browser encryption frontend can be forked into a CLI tool, a desktop app or integrated in bigger systems. When we solve a problem, we try to solve it in a way that’s easy to copy.

### Principles encoded in code

Across all our projects, a few technical and ethical rules keep repeating:

* **Strong, modern primitives** – We favour widely-reviewed algorithms and libraries rather than home-rolled crypto. Think [AES-GCM](https://grokipedia.com/page/Galois%252fCounter_Mode) modern KDFs, curve-based public-key crypto, implemented via mature libraries instead of custom “genius” code. Our job is to wire them correctly and safely into UX, not to invent a new cipher suite in someone’s bedroom.

* **Local-first, zero-knowledge** – Wherever feasible, encryption, decryption and key derivation happen entirely on the client side. Servers (when used at all) should handle only opaque blobs, never plaintext or raw keys. For browser apps, that means doing the work in your tab; for future native tools, that means keeping secrets on your device, not in someone else’s data centre.

* **No analytics, no dark patterns** – We don’t hide trackers under “performance cookies”, we don’t do fingerprinting, we don't even have basic telemetry and we’re not interested in growth-hacking your threat model away. If we ever need metrics, they will be designed in a way that respects anonymity and can be understood from the outside.

* **Design for non-experts, respect for experts** – Interfaces are meant to be readable by someone who doesn’t live on Hacker News, while still exposing enough detail that security people can meaningfully critique what we’re doing. Clear explanations, sensible defaults, and honest warnings beat “trust us, it’s military-grade” every time.

### Tools as acts of resistance

Every [projects](https://github.com/cypherfucker?tab=repositories) is built with a very simple idea in mind: **if using encryption is easier than staying exposed, more people will choose to be safe**. That’s why we obsess about friction, onboarding and emotional load as much as we care about key sizes and IVs. You shouldn’t have to become a full-time paranoiac to protect a handful of files, a chat log, or a personal archive.

So whether you’re dragging a file into a browser tab to encrypt it, scrubbing metadata from a photo before sharing it, or using one of our future tools to keep your backups out of reach of landlords, bosses or regimes, you’re participating in the same thing: quietly shrinking the surface area of surveillance, a few megabytes at a time.

That’s what we build. Not just apps, but habits – small, reproducible ways of saying: *my data is mine, and math is on my side*.

## Why we exist

The modern web is a panopticon disguised as a convenience service. Every click is logged, every message is scanned, every photo becomes training data for a system you never consented to. Even tools that claim to be “secure” often hide behind proprietary binaries, opaque legal terms, and vague promises that boil down to “trust us, we’re nice”.

We don’t believe in “trust us”. We believe in **don’t take our word for it — read the code, run it locally, fork it if you want**. Our default posture is that any system which can see your plaintext will eventually leak it, be compelled to share it, or be compromised. The only winning move is to ensure that other people never see your plaintext in the first place.

Cypherfucker is our answer to that reality. Instead of adding another central service that promises to keep your secrets “safe”, we write tools where we never see those secrets at all. Instead of chasing user data, we deliberately architect our projects so that we couldn’t harvest it even if we turned evil tomorrow. Instead of building a brand moat, we deliberately license our work into the public domain, so that the tools survive even if the collective doesn’t. 

## Our philosophy: weaponise math, not people

The name is confrontational on purpose. Encryption has been framed for decades as something suspicious: the domain of spies, criminals and “people with something to hide”. We reject that framing completely. Cryptography is just math, and math does not care whether you are a journalist under threat, a queer kid hiding a journal from hostile parents, a dissident in an authoritarian state, or simply someone who does not want their landlord, boss or cloud provider reading their files.

When we say we “sabotage surveillance”, what we mean is this: we make it cheaper, easier and more pleasant to use strong encryption than to stay in the default, unprotected state. We take tools that used to require a PhD or a command-line obsession and turn them into clean, quiet web apps you can explain to a friend in five minutes. We treat privacy not as a luxury, but as a baseline.

We also refuse the false binary between “hardcore security” and “good UX”. Our work tries to prove that you can have both: interfaces that are minimal, accessible and aesthetically pleasing, with cryptographic underpinnings that would pass a professional security review. The user only sees a drag-and-drop zone and a progress bar; under the surface, authenticated encryption, salts, IVs and KDFs are doing their silent work. 

## How we work

Cypherfucker is intentionally small, distributed, and porous. There is no office, no HR, no corporate ladder. Repositories live on GitHub, issues are public by default. If you want to know how something works, you read the source. If you want to change it, you open a pull request. 

Our development process is built around a few non-negotiables:

* **Open by default.** All code, designs, and documentation live in public repositories under permissive or [CC0 license](https://github.com/cypherfucker/about/blob/main/LICENSE). If we can’t show it, we probably shouldn’t be running it.
* **Local-first architecture.** We’d rather ship a slightly “less convenient” tool that never sees your plaintext than a slick cloud dashboard built on data hoarding. If your data have to reach a server, it's encrypted first so no one - not even us - can see it.
* **No telemetry, no dark patterns.** We don’t embed trackers, A/B testing spy scripts or telemetry. If we need metrics, we design them in ways that don’t deanonymise individual users and can be measured from the outside.
* **Cryptography from experts, not ego.** We rely on established libraries and community-vetted implementations instead of rolling our own crypto. Our job is to wire those primitives into good UX, not to invent new block ciphers in the shower. 

This way of working is slower than “move fast and break things”, but it’s also less likely to break the people who rely on us.

## Who this is for

Cypherfucker is for anyone who has ever looked at their devices and thought: “I wish I could keep this to myself.” That includes but is not limited to:

* Journalists and sources who need to move sensitive files without leaving a trail of unencrypted copies on random servers.
* Activists, organisers, and journalists operating in environments where surveillance is the default, not the exception.
* Vulnerable people who have learned the hard way that “family computer” often means “no real privacy”.
* Peoples stuck in hostile places who still want a way to keep personal backups, notes or correspondence out of reach.
* Everyday geeks who just like the idea that their data belongs to them and no one else.

You don’t need to identify as an “activist” or a “threat-model nerd” to belong here. If all you want is a simple, honest way to encrypt a folder before it touches a cloud drive, you are exactly the kind of person we build for.

## Our promise

Because we are a collective and not a company, our promises are intentionally simple:

* We will never build features whose primary purpose is to collect data about you.
* We will never put critical security functionality behind a paywall.
* We will never ship proprietary clients that you cannot audit, decompile, or replace.
* We will continue to license our work in ways that let you fork it, mirror it, and run it without us. 

We can’t promise that we will never ship bugs, or that our tools will magically solve every security problem in your life. What we can promise is that our incentives are aligned with yours: we want you to have working, trustworthy encryption that does not depend on our continued existence, funding, or goodwill.

## How to get involved

If you’re reading this, you’re already part of the story. The easiest way to get involved is to **use the tools**, file issues, and tell us when something feels confusing, broken, or unsafe. Good feedback makes better tools.

If you have technical skills, you can:

* Contribute code, tests, and refactors to harden the implementation.
* Help review cryptographic choices or validate the way we wire libraries together.
* Port our ideas into other environments — command-line tools, mobile apps, desktop clients — while preserving the same local-first, zero-knowledge guarantees.
* Translate the interfaces and documentation so that people outside the English-speaking internet can use them without friction.

If you don’t write code, you are still welcome and needed. You can write documentation, threat-model real-world use cases, design clearer interfaces, record how-to videos, or help people in your community adopt better digital hygiene using the tools we publish.

Fork the repos. Mirror the web apps. Embed the components into your own projects. Ignore the name if it scares your boss and call it something else in your context. We don’t mind — in fact, that’s the point.

---
