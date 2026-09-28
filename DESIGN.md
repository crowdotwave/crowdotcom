---
name: crowdotcom
description: Loyalty that brings your clients back, drawn as light at a cloud's edge on a prairie night.
colors:
  night: "#070b16"
  night-2: "#0b1222"
  dusk: "#13203a"
  silver: "#e8ecf2"
  mist: "#a8b2c3"
  faint: "#7f8a9e"
  mint: "#8eeecf"
  ice: "#86c6ff"
  rose: "#f3a8c8"
  violet: "#b8a4ff"
  violet-deep: "#2a1f55"
  screen: "#000000"
typography:
  display:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2.7rem, 1.35rem + 5.2vw, 5.9rem)"
    fontWeight: 200
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2rem, 1.2rem + 3vw, 3.6rem)"
    fontWeight: 200
    lineHeight: 1.04
    letterSpacing: "-0.03em"
  headline-lead-offer:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2rem, 1.2rem + 3vw, 3.5rem)"
    fontWeight: 250
    lineHeight: 1.08
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.7rem, 1.2rem + 1.8vw, 2.6rem)"
    fontWeight: 250
    lineHeight: 1.08
    letterSpacing: "-0.025em"
  title-contact:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.7rem, 1.2rem + 1.8vw, 2.5rem)"
    fontWeight: 250
    lineHeight: 1.1
    letterSpacing: "-0.025em"
  subtitle:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.4rem, 1.1rem + 1.1vw, 2rem)"
    fontWeight: 250
    lineHeight: 1.12
    letterSpacing: "-0.02em"
  lede:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.08rem, 1rem + .35vw, 1.3rem)"
    fontWeight: 300
    lineHeight: 1.55
    letterSpacing: "normal"
  figure:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: "normal"
  figure-small:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.35rem"
    fontWeight: 300
    lineHeight: 1.1
    letterSpacing: "normal"
  step-title:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.3rem"
    fontWeight: 300
    lineHeight: 1.2
    letterSpacing: "normal"
  price:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 300
    lineHeight: 1.5
    letterSpacing: "normal"
  body-large:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.1rem"
    fontWeight: 300
    lineHeight: 1.6
    letterSpacing: "normal"
  body:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  body-project:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 300
    lineHeight: 1.6
    letterSpacing: "normal"
  nav:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".95rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  control:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".92rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "normal"
  small:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  meta:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".88rem"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "normal"
  note:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".85rem"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "normal"
  figcaption:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".82rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "normal"
  caption:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".78rem"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: ".02em"
  micro:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".75rem"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: ".06em"
  tag:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".72rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: ".06em"
  tag-phone:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: ".66rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "normal"
rounded:
  control: "999px"
  focus: "3px"
  phone: "2.1rem"
  phone-screen: "1.7rem"
  scrollbar: "10px"
spacing:
  gutter: "clamp(1rem, 4.5vw, 3rem)"
  row: "1.4rem"
  section: "clamp(6rem, 12vw, 10rem)"
components:
  button-primary:
    backgroundColor: "rgba(184, 164, 255, .08)"
    textColor: "{colors.silver}"
    rounded: "{rounded.control}"
    padding: ".7rem 1.35rem"
    height: "3rem"
  button-primary-hover:
    backgroundColor: "rgba(184, 164, 255, .18)"
  button-quiet:
    backgroundColor: "transparent"
    textColor: "{colors.silver}"
    rounded: "{rounded.control}"
    padding: ".7rem 1.35rem"
    height: "3rem"
  input-line:
    backgroundColor: "transparent"
    textColor: "{colors.silver}"
    rounded: "0"
    padding: ".6rem 0 .7rem"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.mist}"
    typography: "{typography.control}"
    rounded: "{rounded.control}"
    padding: ".45rem 1rem"
    height: "2.5rem"
  chip-selected:
    backgroundColor: "rgba(232, 236, 242, .08)"
    textColor: "{colors.silver}"
---

# Design System: crowdotcom

## Overview

**Creative North Star: "Noctilucent prairie night"**

The page is a clear Alberta night with one iridescent cloud in it. Loyalty is drawn as light at that cloud's edge: a regular client is a vivid fringe, a new one is still forming, a client who has quietly stopped coming is a fringe breaking apart. Everything else stays out of the way so that edge of light is the only spectacle.

Those edges are also honest charts. Each client's line is their last six months: how high it rides is how closely they keep their own rhythm, each bump is a visit, and where it thins and breaks is where they stopped coming. The idea underneath the whole page is consistency, and the lines are where a visitor sees it.

The ground is night blue, the text is silver, and colour appears only where light would: at an edge. There are no cards, no kickers, no glows. Rows are separated by hairlines, the type is one humanist sans at hairline weight for display, and violet is kept for the single action a visitor is asked to take.

**Key Characteristics:**
- One WebGL cloud in the hero: a cumulus of rounded billows placed in the clear sky above the headline, a dark silhouette against a pale patch of sky that hides the stars, lined in silver that turns iridescent along its top, its billows faintly shaded so it has volume. Stars keep a soft margin clear of every line of text, button and the points panel, so nothing sparkles between the words. Capped at 30fps, paused offscreen, a still frame under reduced motion.
- The spectrum (mint, ice, violet, rose) appears only as a fringe: the cloud edge, the client edges, the logo mark, the phone frame's hairline.
- Client edges are six month timelines of sample data, with big moments (a spend, a milestone, a referral) marked on the line and an owner-only ranking of the best clients underneath.
- One thread runs the length of the page and draws itself as the visitor scrolls.
- Hairline-ruled rows instead of containers.
- Hairline display type (weight 200) against a comfortable 400 body.

## Colors

### Primary
- **Violet** `#b8a4ff`: the one action. Primary button edge, focus ring, caret, "With me" labels. Nowhere decorative.

### Secondary
- **Spectrum fringe** mint `#8eeecf`, ice `#86c6ff`, violet, rose `#f3a8c8`, always together as a gradient edge, never as a fill. On a client timeline the gradient is pinned to time rather than to the line's own length: mint six months ago, rose now, the same on every row, so a line that is flat still carries its colour.
- **Rose** alone marks a client who is drifting or gone, the Drifting tag on the leaderboard, and a form error.

### Neutral
- **Night** `#070b16` page ground, **Night 2** `#0b1222`, **Dusk** `#13203a` for the bottom of the hero sky.
- **Screen** `#000000` only behind the phone recordings, where a real phone screen is black, and in the mask that draws the phone frame's spectrum edge.
- **Silver** `#e8ecf2` text, **Mist** `#a8b2c3` secondary text, **Faint** `#7f8a9e` metadata and placeholders (5.4:1 on night).
- Rules are silver at 12% and 24% alpha.

**The Edge Rule.** Colour lives on edges and on the numbers that matter, never on surfaces. Points held are ice, points earned are mint, points waiting or spent are rose. If a colour fills an area larger than a hairline, it is wrong.

**The One Violet Rule.** Violet marks the thing to do next. Two violet things on one screen means one of them is lying.

## Typography

Commissioner, self-hosted as a variable woff2 (100 to 900), is the only face.

### Hierarchy
The scale below is what the page uses. It was written down after the fact, so where this document and the page ever disagree, the page is right and this section gets updated.

- **Display** (h1): 200 weight, up to 5.9rem, line-height .98, tracking -0.035em. The emphasised phrase steps up to 300, never italic, never gradient.
- **Headline** (section h2): 200 weight, up to 3.6rem, and the lead offer at up to 3.5rem.
- **Title** (project h3): 250 weight, up to 2.6rem; the contact heading at up to 2.5rem.
- **Subtitle**: up to 2rem, for offer names, the fits list and the leaderboard heading.
- **Lede**: up to 1.3rem at weight 300, the hero's supporting line.
- **Figures**: 1.6rem for the points total, 1.35rem for leaderboard numbers, both weight 300 and tabular.
- **Body**: 400 at 1.0625rem, line-height 1.65, measure held near 36rem. Section intros and the lead offer run a step larger at 1.1rem, project text at 1.05rem, the price line at 1.15rem, and the two steps' titles at 1.3rem.
- **Small**: .95rem for nav links and the drift note, .92rem for small controls, chips and field labels, .9rem for status lines and footers, .88rem for the detail line under a client, .85rem and .82rem for panel notes and phone captions.
- **Captions and tags**: .78rem for sample notes and the timeline scale, .75rem for the small caps under a figure, .72rem for the marks on a timeline and the Drifting tag, and .66rem for those marks on a phone, where they have to stay out of the line's way.

**The Hairline Rule.** Size carries hierarchy, weight stays light. Headings never go bold.

## Layout

Two pages share one stylesheet. The home page is a single column of sections inside a 78rem wrap with a fluid gutter, in this order: hero, who is drifting (with the business chips, the client timelines and the best clients ranking), where it fits, the work (the two loyalty cases and a link to every project), what I build, how I work, contact. The Projects page holds every project, each with a recording or a screenshot in a phone frame. The hero is a two-column grid (copy, observation panel) that stacks below 60rem, with the cloud sized to the clear sky above the headline on every layout and never wider than the screen. Client rows are three-column grids (name, timeline, state) that reflow to name and state over a full-width timeline below 44rem, with a "6 months ago … Now" scale under the last row. Offer and fit rows are two columns, name then description. Projects alternate text and phone recording, stacking below 54rem; a project with no media runs full width. No horizontal scroll at 360px.

## Elevation & Depth

The page is flat. The only shadow is under the phone recordings, a neutral black drop with offset and blur, so the device sits on the night rather than glowing in it.

**The No Glow Rule.** No coloured shadows, no zero-offset halos. Light in this world comes from the cloud and the pale patch of sky that lines it, never from UI. A moment dot on a timeline is ringed in the night colour to lift it off the line; that ring is a cut, not a glow.

## Shapes

Controls are full pills. Phone frames are rounded rectangles (2.1rem, with the screen inside at 1.7rem) with a 1px spectrum hairline. The scrollbar thumb rounds at 10px. Everything else is square, separated by hairlines.

## Components

### Buttons
- **Primary**: pill, 1px violet border, 8% violet wash, silver text, 18% wash on hover. One per view.
- **Quiet**: pill, 24% silver border, transparent; the border turns silver on hover.
- **Disabled**: 45% opacity, not-allowed cursor.

### Inputs / Fields
Underline only, 24% silver rule, turning violet on focus. Labels above in mist. Placeholders in faint.

### Navigation
Fixed header, transparent over the sky, gaining a night background and hairline after scroll. Section links in mist, the contact action as a quiet pill. Links hide below 48rem, leaving the logo and the action.

### Chips
- **Style:** pill, 24% silver border, transparent, mist text at the control size. Used for the business picker above the client timelines and for the leaderboard's sort.
- **State:** selected is a silver border, silver text and an 8% silver wash. Never violet: choosing what to look at is not the action the page asks for.

### Who is drifting (signature)
Four invented sample clients in whichever business the chips show (vet clinic, gym or studio, groomer, salon, trainer), each a six month timeline drawn from a sample visit history that agrees with the words beside it.
- **Height** is how closely the client keeps their own rhythm, from the baseline (stopped) to the kept line, a little higher when they come more than usual. The same height means the same thing for a monthly pickup and three classes a week.
- **Bumps** are visits, or busier weeks.
- **Fringe** over a 9px silver body: whole and 2.4px where the rhythm is kept, a thin dash where it is slipping, a faint sparse dash once they have stopped. A new client's line starts where they joined, as the animated forming dash.
- **Moments** are white 8px dots on the line with a short label above (a spend, a milestone, a referral), placed as HTML over the stretched line so they never distort.
- **States** in words beside each line: Regular, New still forming, Drifting, Gone quiet. "Send a note" moves a client to forming and updates a live status line.

### Your best clients
The owner's ranking, under the drift list and labelled as a view clients never see. Hairline rows of rank, name with a detail line, and one figure in figure-small weight 300 with a small caps caption. Sorts by most loyal (rhythm kept, as a percentage) or top spend (this year). A drifting client in the ranking carries a rose Drifting tag, which is the link between who to thank and who to bring back.

### Offer rows
Hairline-ruled rows, name in subtitle weight on the left and a line or two of description on the right. The where-it-fits variant adds each business's rhythm under its name in faint.

### The thread
One client edge drawn the length of the page, built from the page's own layout. It leaves the hero from under the lit cloud, runs down a gutter beside each section, and crosses each gap in a single S to the opposite gutter, landing just above the next heading. Scrolling draws it: its head stays two thirds of the way down the screen, with a short forming stretch (the animated dash) ahead of it. It sits under the content and only ever occupies gutters and gaps. The fringe's spectrum repeats down the page, so its colour turns as it is followed. Under reduced motion the whole line is drawn and still.

### Observation panel
A sample client's points history that prints one new line every few seconds on top of already visible content. Labelled as sample data. A reward is only claimed once the balance covers it, so the total never goes below zero.

## Do's and Don'ts

### Do:
- Do put colour only on edges: the cloud, client fringes, the logo, hairlines.
- Do keep one violet action per view.
- Do label every piece of example data as a sample.
- Do give recordings a poster and pause them offscreen.
- Do make every shape on a client line mean something: height is rhythm kept, bumps are visits, dots are moments, the fringe is continuity. Nothing on a line is decoration.
- Do make sample figures agree with each other: the words beside a line, the line itself and the ranking below describe the same client.

### Don't:
- Don't use cards, kickers, eyebrows or section numbers.
- Don't use coloured or glowing shadows.
- Don't use gradient text or bold headings.
- Don't use em dashes anywhere.
- Don't invent numbers, testimonials, prices or clients.
- Don't let a line rise or fall for looks. A slope is a claim about a client, and an unexplained one reads as something having happened.
- Don't use violet for a selected chip.
