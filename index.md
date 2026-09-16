---
title: Vero
---

# Vero

A browser extension that notices persuasion techniques on shopping pages — countdown timers,
limited-stock messages, crossed-out reference prices — and, at add-to-cart or checkout, asks a
question about what was actually on screen.

It reports what a page displayed and asks a question. It never asserts intent, deception, or
illegality.

- [Privacy policy](./privacy.html)
- [Source code](https://github.com/viditChhajed/vero)

**By default it makes no network requests.** Everything it notices stays on your device and is
deleted after 30 days. There is one optional setting, off unless you switch it on, that shares
which shops use which techniques — it names the shop's domain, never the page, and never you.

**It asks for access to all https sites when you install it, and Chrome will say so.** That
permission is broad on purpose: persuasion techniques are not confined to a list of big
retailers, and a fixed list is always wrong in the direction that leaves people unprotected.
It never runs on banking, health, government or webmail sites, and it sends nothing anywhere
unless you turn sharing on. The [privacy policy](./privacy.html) explains how both of those are enforced rather
than merely promised.
