# Alien Workshop for macOS

**Official macOS client** — a clean, minimal control surface for **Artificial Intelligence & Operations**.

This app is designed to feel *native, lightweight, and dependable*: a fast way to sign in, manage your account, jump into your workspace, and keep Alien Workshop “present” on your Mac.

---

## What this app is

A **thin macOS client** focused on high-signal workflows:

- **Sign in / sign out**
- **Account status** (plan, usage, sessions, device state)
- **Quick access** to your workspace (open, resume, deep links)
- **System integration** (notifications, menu bar / quick actions, deep-link handling)
- **Polished distribution** (App-Store-friendly posture, minimal permissions)

The goal is not “do everything.” The goal is **do the essentials extremely well**.

---

## Design principles

- **Thin by default**  
  This app should stay small: fewer screens, fewer permissions, fewer moving parts.

- **Mac-first UX**  
  Crisp typography, sharp spacing, predictable navigation, system-consistent behavior.

- **Fast paths, not feature sprawl**  
  The best client gets you to the outcome quickly: open, capture, notify, act.

- **Stable and boring (in a good way)**  
  Reliability beats cleverness. Clear error states. No surprises.

---

## Capabilities (current + near-term)

### Core
- Authentication + session handling
- Account overview (status, settings entry points)
- Open workspace / resume last context
- Deep links (open specific pages/objects from URLs)
- Notifications for important events

### Near-term additions
- Menu bar quick actions (open, capture, recent items)
- Lightweight “capture” (note/prompt/idea → send to workspace)
- Offline-friendly UI states (no network, expired session, partial availability)
- Better onboarding + first-run experience

---

## Repository location

This README lives at:

- `apps/macos/README.md`

The repository root README is here:

- `../../README.md`

---

## Project layout (inside `apps/macos`)

This folder is intentionally simple. As the code lands, expect a structure similar to:

- `App/` — application entry + core app shell
- `UI/` — views, screens, components
- `Services/` — auth, networking, notifications, deep link routing
- `Resources/` — assets, localized strings
- `Docs/` — development notes, App Store / distribution notes

If you’re adding new modules, keep them small and clearly named.

---

## Getting started (development)

This macOS client is intended to be a **native macOS app**.

Typical dev setup:
- A recent macOS version
- Xcode installed (latest stable recommended)
- An Apple developer account only if you’re testing signing / App Store workflows (not required for most changes)

Until the first implementation lands, the best way to contribute is:
- Improve this README + app docs
- Propose UX flows (screens, states, empty/error behavior)
- Open issues for feature requests and edge cases

Once code is present, this section will include exact build/run steps.

---

## What to work on (high-leverage contributions)

If you want to help and you’re not sure where to begin, these are strong starting points:

- **First-run experience**: onboarding, sign-in states, “what happens next”
- **Deep link routing**: predictable behavior + good error states
- **Notifications**: preference controls, timing, relevance
- **Menu bar quick actions**: small, useful, and fast
- **Polish**: spacing, copy, loading states, accessibility, keyboard navigation

Open an Issue titled:

**“macOS: I want to help — highest leverage task?”**

…and we’ll carve out a clear first PR.

---

## UX + quality bar

We want the macOS app to feel premium:

- Crisp spacing and typography
- No jittery transitions
- Respect reduced motion and accessibility settings
- Clear loading, empty, and error states
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
