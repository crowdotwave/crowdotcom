# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Owners and managers of small businesses anywhere in Canada: clinics, gyms and
trainers, salons, makers, local shops. Busy, not technical, and many have
already paid for software that did not fit them. Most arrive on a phone, from a
search, an online post or ad, or a referral, and decide within about ten
seconds whether this person is serious.

The job they are doing: working out whether someone can build the system that
keeps their clients coming back (and takes repetitive work off the front
desk), without being sold to.

## Product Purpose

The public website for Chris's one-person business. It exists to turn a curious
small business owner into a written enquiry. Success is a filled-in contact
form from an owner with a real problem.

Chris does not do cold outreach or in-person selling. The site has to do the
introducing on its own, so it carries the proof (live demos, recordings, real
projects) that a sales conversation would otherwise carry.

## Positioning

Websites and apps that bring clients back: custom built for one business, with
a loyalty program (points, rewards, and the reports that show who has quietly
stopped coming) and client records stored securely in the cloud, run by the
person who built it. Not rented from a platform with thousands of customers.

What a vendor cannot truthfully copy:
- One person builds it and keeps running it. Changes in days, not quarters.
- It works alongside what the business already uses (booking, practice
  software, payment terminal) instead of replacing it.
- The points history is append-only: every point a client holds can be
  explained, and a correction is a new line, never an edit.
- Straight about limits: if something cannot be done, says so, and why.

Also offered, in support of the loyalty work: client apps with a matching
front desk screen, websites fixed or rebuilt and then kept running, and small
tools that automate repetitive weekly work.

## Operating Context

- Contact is **written only**: a short form (name, email, business, message)
  that sends to Chris's email through Formspree. Never promise a call.
- Chris works across Canada, and locally in Edmonton and St. Albert, Alberta.
- Visitors can try the real apps themselves, with no sign-up, through demo
  links that open the live app on invented sample data.

## Capabilities and Constraints

- Static pages (`index.html` and `projects.html`) sharing `assets/site.css`, no
  build step, no framework, hosted on GitHub Pages. Must open straight from disk.
  Supporting files live under `assets/`.
- Fonts and media are self-hosted; the only outside request may be the form
  submission.
- Contact form posts to `https://formspree.io/f/YOUR_FORM_ID` until Chris
  supplies the real id; until then the send button is off. Chris's email address never appears in the page.
- The business name is undecided. `crowdotcom` is a placeholder, set in one
  place (the `BRAND` constant) so it can be swapped.
- Undecided, so never stated: prices (say only "Every project is quoted for
  the business"), what a client owns if the work ends. There is no About
  section; the page speaks in the first person throughout.
- Placeholders are obvious and findable by searching for `[DECIDE]`.

## Brand Commitments

- Working role title: Loyalty Operations & Digital Product Specialist.
- First person ("I build"), never a pretend agency ("we").
- Plain, specific, calm. Say what a thing does, not how innovative it is.
- **No em dashes** anywhere. Commas, colons, periods, or parentheses.
- Never: AI-powered, cutting-edge, seamless, leverage, solutions, empower,
  unlock, supercharge, game-changer, "in today's digital landscape".
- No invented numbers, testimonials, logos or client counts.

## Evidence on Hand

- **Nith Valley Animal Hospital, New Hamburg, Ontario.** Client app and front
  desk console: refill requests tracked to pickup, run-out warnings, one-tap
  points at the counter, append-only ledger, never calculates a vaccine due
  date. Status: built and working, not yet a signed client. Say "built for",
  never "used by". Recording: `assets/work/nith-demo.mp4` (+ `.webm`,
  `-poster.jpg`). Live demo: `https://crowdotwave.github.io/nith-valley-app/?demo=client`
  and `?demo=staff`.
- **A personal trainer (ptC).** Two-sided workout app, in use. Works with no
  signal and syncs later; each client sees only their own data, enforced by the
  database. Recording: `assets/work/ptc-demo.mp4` (+ `.webm`, `-poster.jpg`).
- **A memorial resin artist.** Website with gallery, memorial wall and grief
  resources, written so the owner can update it without a developer.
- Absent, and not to be fabricated: testimonials, measured results, client
  logos, a client count, pricing.

## Product Principles

1. Proof over promises: let visitors try or watch the real thing.
2. The websites and apps are what is sold; loyalty is what they are for. Everything
   serves keeping clients coming back.
3. Honest status: never imply a client, result or feature that is not real.
4. Written, low-pressure contact that a busy owner can send at 11pm.
5. The page must work on a phone before anything else.

## Accessibility & Inclusion

Phone-first: no sideways scrolling at 360px. Real headings, alt text and
captions for recordings, visible focus, sufficient contrast. Respects reduced
motion: recordings show a still frame, and no content depends on an animation
to become visible.
