# Alien Workshop for iOS

**Official iOS client** — a fast, lightweight companion for **Artificial Intelligence & Operations**.

This app is built for the moments that matter on mobile: capture ideas, stay connected, receive notifications, and take quick actions that keep work moving.

---

## What this app is

A **thin iOS client** focused on speed, clarity, and reliability:

- **Sign in / sign out**
- **Account status** (plan, usage, sessions, device state)
- **Quick access** to your workspace (open, resume, deep links)
- **Capture** (notes, prompts, ideas → send to your workspace)
- **Notifications** (high-signal events and workflow nudges)
- **Lightweight actions** (approve, save, pin, share, open)

The goal is not to replicate a full desktop environment. The goal is to create a **mobile front door** that’s always ready.

---

## Design principles

- **Fast moments over long sessions**  
  Most mobile interactions should take seconds, not minutes.

- **Thin by default**  
  Keep scope small, flows obvious, and screens minimal.

- **High-signal notifications**  
  Notifications should feel valuable, not noisy.

- **Privacy + restraint**  
  Minimal permissions, clear data handling, predictable behavior.

---

## Capabilities (current + near-term)

### Core
- Authentication + session handling
- Account overview (status, settings entry points)
- Open workspace / resume last context
- Deep links (open specific pages/objects from URLs)
- Capture (quick note / quick prompt)

### Near-term additions
- Share sheet integration (send text/links into your workspace)
- Widgets (quick capture / recent items / status)
- Offline-friendly UI states (no network, expired session, partial availability)
- Better onboarding + first-run experience
- Push notification preferences + tuning

---

## Repository location

This README lives at:

- `apps/ios/README.md`

The repository root README is here:

- `../../README.md`

---

## Project layout (inside `apps/ios`)

This folder is intentionally simple. As the code lands, expect a structure similar to:

- `App/` — entry point, app shell, navigation
- `UI/` — screens, components, styling
- `Services/` — auth, networking, notification handling, deep link routing
- `Extensions/` — share sheet, widgets (when present)
- `Resources/` — assets, localized strings
- `Docs/` — product notes and development guidance

If you’re adding new modules, keep them small and clearly named.

---

## Getting started (development)

This iOS client is intended to be a **native iOS app**.

Typical dev setup:
- macOS + Xcode installed (latest stable recommended)
- iOS Simulator (or a test device)
- An Apple developer account only if you’re testing signing / TestFlight (not required for most changes)

Until the first implementation lands, the best way to contribute is:
- Improve this README + app docs
- Propose UX flows (screens, states, empty/error behavior)
- Open issues for feature requests and edge cases

Once code is present, this section will include exact build/run steps.

---

## What to work on (high-leverage contributions)

If you want to help and you’re not sure where to begin:

- **Capture UX**: quick note/prompt flows that feel effortless
- **Share sheet**: send text/links into the workspace cleanly
- **Deep link routing**: predictable behavior + great fallbacks
- **Notification tuning**: relevance, grouping, preference controls
- **Widgets**: minimal, high-signal, fast access

Open an Issue titled:

**“iOS: I want to help — highest leverage task?”**

…and we’ll carve out a clear first PR.

---

## UX + quality bar

We want this to feel premium and intentional:

- Fast launch, low latency
- Crisp spacing and copy
- Great loading/empty/error states
- Respect accessibility and reduced motion
- Minimal permissions (only ask when needed, explain why)

If you’re submitting UI work, screenshots are appreciated.

---

## Links

- Website: https://alienworkshop.ai  
- Repo root: https://github.com/alienworkshop-labs/alienworkshop-app  

For press or partnership inquiries: **press@alienworkshop.ai**

---

## Trademark

**Alien Workshop™** is a trademark of Alien Workshop LLC.

---

## License

See the `LICENSE` file in the repository root.
