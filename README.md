# Halleluyah Salako

**Full-stack developer — WordPress & PHP, TypeScript, React Native.** Abuja, Nigeria (UTC+1).

I build production systems and the internal tools that run them: custom plugins instead of plugin sprawl, payment and API integrations, and admin dashboards non-technical teams can actually operate without calling a developer.

Nine years of client work. Currently contracting for a global health nonprofit, building both their web estate and an internal records platform.

---

## Selected work

### Veterinary Career Guide — [vetcareerguide.com](https://vetcareerguide.com)
A subscription commerce and publishing platform carried entirely by one custom WordPress plugin I wrote from scratch, plus a theme built specifically for it.

- **Custom subscription billing** written directly against the Paystack, Flutterwave and Stripe APIs — not their built-in subscription products — with WP Cron tracking each member's billing date and charging on schedule
- **Geo-routed payments** — the gateway is selected automatically by visitor country
- **Multi-currency** — prices held in Naira, converted from detected location, with manual override
- **Fulfilment** — per-buyer ebook watermarking; hardcopy purchases redeemed via codes printed in the physical book
- **Member dashboard** — progress tracker with calendar, to-do list, habit tracker and goal tracking
- Coupons (standard, group, email-targeted), early-bird pricing, stock management — each with admin screens for non-technical staff

### AFIWEL — [afiwel.com](https://afiwel.com)
Full site plus a Resources plugin serving 59 publications across an 11-country programme. One plugin replaced four: its own custom post type and fields in place of ACF, exposed as a custom Elementor widget, owning its query, filtering and pagination. Auto-generates download actions and share links for eight platforms on publish.

### One Health & Development Initiative — [onehealthdev.org](https://onehealthdev.org)
Full site plus a filter plugin replacing three or four stacked plugins — Year, Category and keyword filtering with its own query, results and pagination, available as both a shortcode and an Elementor widget.

### Also built and maintained
[agrowsafe.com](https://agrowsafe.com) · [onehealthv.com](https://onehealthv.com)

---

## Open source

**[Hal-Cartel](https://github.com/Halleluyahsalako/Hal-Cartel)** — a lightweight, security-conscious eCommerce plugin for WordPress; a free alternative to WooCommerce plus its paid extensions. One-page checkout, a pluggable payment-gateway architecture, Stripe PaymentIntents with signed idempotent webhooks, an abandoned-order cron that restocks stale orders, signed expiring download tokens, multi-currency, per-zone shipping, WooCommerce-compatible CSV import/export. *In active development.*

**[ctrl-freak](https://github.com/Halleluyahsalako/ctrl-freak)** — Kotlin Android app for syncing clipboard, notes and files between phone and computer.

---

## Stack

**WordPress** plugin architecture · custom themes · custom post types and meta · custom Elementor widgets · WP Cron · REST endpoints · webhooks · WooCommerce · Dokan · Formidable · ACF migration · PHP 8 upgrades · multisite
**Payments** Stripe (PaymentIntents, webhooks) · Paystack · Flutterwave
**Languages** PHP · TypeScript · JavaScript · SQL · Kotlin · Python
**Backend** NestJS · Node.js · Prisma · PostgreSQL · MySQL · MongoDB · BullMQ/Redis · JWT
**Frontend** Next.js · React · Vue · Tailwind
**Mobile** Expo / React Native · offline-first SQLite
**Security** hardening · malware detection and remediation · staging-to-production workflows · debugging live sites

---

## How I work

I work on staging before production, document what I changed, and send short written progress updates by default. I take ownership of a codebase end to end — schema, API, interface and deployment — and I'll tell a client when an off-the-shelf tool would genuinely be cheaper than hiring me to build one.

---

## Community

Django Girls mentor since the first Ogbomoso workshop in 2016; Abuja chapter through 2022.

---

**Get in touch** — halleluyaholuwapelumi42@gmail.com
