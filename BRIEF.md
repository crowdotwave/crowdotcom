# Brief: the crowdotcom homepage

This is the one source both homepage builds work from. It says **what the page
says and who it is for**. It deliberately says nothing about how it should look:
the visual design is what the two builds are testing.

Status: **ready to build.** Anything still marked `[DECIDE]` needs an answer
before the page goes live. A build uses the placeholder shown in the meantime.

---

## 1. Who this is for

**The visitor is a small business owner or manager**, most likely in
Waterloo Region or nearby Ontario. A vet clinic, a personal trainer, a salon, a
maker, a local shop. They are busy, not technical, and have been sold software
before that did not fit them.

They arrive from a link Chris sent, a business card, or a referral. **Most will
open it on a phone.** They give it five to ten seconds before deciding whether
this person is serious.

What they should think, in order:

1. "This looks like someone who does careful work." (the first screen)
2. "This person built something real for a business like mine." (the proof)
3. "They understand how my front desk actually works." (the thinking)
4. "It is easy to talk to them." (the contact)

## 2. What Chris offers

One person who builds and runs the systems a small business needs, **made for
that business**, not rented from a vendor with five thousand customers.

Four things, in order of importance:

- **Loyalty and retention programs.** Points, rewards, and the reports that show
  who has quietly stopped coming back. The work Chris most enjoys.
- **Client apps and staff tools.** A client-facing app and the matching screen
  for the front desk, working alongside the systems the business already uses.
- **Websites, fixed or rebuilt, then kept running.** Including the unglamorous
  part: correct address, working phone links, pages that do not break.
- **Automating the repetitive work.** The weekly task somebody does by hand that
  a small tool could do instead.

Working title for the role: **Loyalty Operations & Digital Product Specialist.**

## 3. The proof: three projects

Real work, described honestly. **No client is named, and no screenshots are
shown.** Describe each project in words only. Do not include details that would
identify a client, such as a town, a street, a staff member's name, or a
software vendor's product name.

### A veterinary clinic in Ontario

A client app and a front-desk console, built to sit alongside the clinic's
existing practice software rather than replace it.

- Clients request food and medication refills from the pet's file, and track
  each request through to ready for pickup, without phoning.
- The app tells clients before food or a prescription runs out.
- Loyalty points are awarded at the counter with one tap, and the points
  history is permanent: every point a client holds can be explained.
- The front desk sees every request in one queue, and can change the clinic's
  hours and notices themselves.
- It never calculates a vaccination due date. It only repeats what staff
  entered, so it cannot tell someone their dog is due when it is not.
- When the clinic's staff asked for changes, each one was built.

**Status to state:** built and working, not yet a signed client. Do not imply
otherwise. Describe it as "built for a veterinary clinic", never "used by".

### A personal trainer

A two-sided workout app: the trainer builds programs and assigns them, clients
log their sets on their phone, and both see progress over time.

- Built on the idea that clients quit when they cannot see it working, so the
  product is the evidence of progress, not the logging.
- Works with no signal, in a basement gym, and syncs later.
- Each client sees only their own data. That rule is enforced by the database,
  not just hidden in the screen.

### A memorial resin artist

A website for a small studio making memorial pieces from resin: a filterable
gallery, a memorial wall where people add the animals they have lost, and a
page of grief support resources.

- Written so the owner can add photos and memorials without a developer.
- Tender subject, handled plainly: no forms that silently throw away what
  someone wrote.

## 4. How Chris works (the differentiators)

These are true, and they are the argument. Use them as section content, not as
slogans.

- **You deal with one person.** No queue, no ticket, no explaining your
  business to someone new each time.
- **Changes in days, not quarters.** A request on Tuesday can be working by
  Friday.
- **It works with what you already use.** Your booking system, your practice
  software, your payment terminal stay where they are.
- **Straight about limits.** If something cannot be done, Chris says so, and says
  why. That is worth more than a feature that half works.

Left off the page until decided: what the client owns if the work ends (see
section 9). Do not write an ownership promise.

## 5. Homepage content, draft copy

The copy both builds use, word for word. Section order may change if the design
needs it; the words should not.

**Hero**

> Loyalty programs, client apps and websites, built for your business and run
> by the person who built them.

Supporting line:

> I build the systems that bring your clients back, and I stay to keep them
> working.

Primary action: **Get in touch.** Secondary: **See the work.**

**The work** (the three projects in section 3, each as a short summary with its
two or three strongest points)

**What I build** (the four offers in section 2, one or two sentences each)

**How I work** (the four points in section 4)

**Price**

> Every project is quoted for the business.

One line, placed near the contact section. No figures, no tiers.

**About**

> I'm Chris, based in Waterloo Region, Ontario.

`[DECIDE]` Chris will write the rest later. Leave a clearly marked placeholder
for two or three sentences, and design the section so it looks finished with
only the one line above.

**Contact**

> Tell me about the most repetitive thing your front desk does every week.

A short form that sends to Chris's email: name, email, business name
(optional), and a message box. The page is static, so the form posts to a form
service. Use Formspree, which everdeencrafts already uses:

- Form `action` is `https://formspree.io/f/YOUR_FORM_ID`, marked `[DECIDE]`.
- Until the real ID is in, the form says plainly that it is not connected yet,
  so nobody writes a message that goes nowhere. It switches on by itself once
  the ID is replaced.
- On success, show a plain confirmation in the page rather than leaving it.
- **Chris's email address never appears in the page source.** The form service
  holds it.

## 6. Tone and words

- Plain, specific, and calm. Say what a thing does, not how innovative it is.
- First person ("I build"), not a pretend agency ("we").
- **No em dashes.** Commas, colons, periods, or parentheses.
- **Never** say: AI-powered, cutting-edge, seamless, leverage, solutions,
  empower, unlock, supercharge, game-changer, "in today's digital landscape".
- No invented numbers. No "40% more repeat visits" unless it was measured.
- No fake testimonials, logos, or client counts.

## 7. Hard requirements for both builds

Not style. These apply to both versions equally.

- One file, `index.html`, no build step, no framework. Opens straight from disk
  and deploys to GitHub Pages as is.
- Designed for a phone first. No sideways scrolling at 360px wide.
- Loads fast on a phone signal. No heavy video, no large image libraries.
- Readable by screen readers: real headings, alt text, visible focus, enough
  colour contrast.
- Respects reduced-motion settings. Content must never depend on an animation
  running to become visible.
- No stock photography, no generic illustrations of people at laptops.
- Placeholders are obvious (so nothing half-finished ships by accident) and
  easy to find by searching for `[DECIDE]`.

## 8. The comparison test

Two builds of the same page, differing only in whether Impeccable is used.

| | Plain build | Impeccable build |
| --- | --- | --- |
| Branch | `homepage-plain` | `homepage-impeccable` |
| Starts from | `main` (this brief) | `main` (this brief) |
| Sees the other build | No | No |
| Prompt | the one below | the one below, plus Impeccable's own setup |

Prompt, word for word:

> Read BRIEF.md and build the homepage as a single index.html. It should
> impress a small business owner within five seconds of landing on it.

Note for the Impeccable session: Impeccable keeps its own `PRODUCT.md` and
`DESIGN.md` (the veterinary app has both). Let it write them from this brief.
Neither build should copy the veterinary app's visual style, since that belongs
to the clinic.

**Judging:** open both on a phone first. Which one would make a clinic owner
think "this person is serious"? Which one looks like every other AI-made site?
Then show both to one or two people without saying which is which.

## 9. Decisions

Settled:

- **Clients:** never named, no screenshots.
- **Contact:** a form that sends to Chris's email (section 5).
- **Price:** "Every project is quoted for the business." No figures.

Still open:

1. Business name. `crowdotcom` is a placeholder, and the page should make it
   easy to swap: set it in one place near the top of the file.
2. The About paragraph, in Chris's own words.
3. Ownership if a client stops working with Chris. Off the page until decided.
4. The Formspree form ID, once Chris makes the account.
