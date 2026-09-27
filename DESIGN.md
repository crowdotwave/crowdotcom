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
  title:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.7rem, 1.2rem + 1.8vw, 2.6rem)"
    fontWeight: 250
    lineHeight: 1.08
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  small:
    fontFamily: "Commissioner, Segoe UI, system-ui, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
rounded:
  control: "999px"
  focus: "3px"
  phone: "2.1rem"
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
---

# Design System: crowdotcom

## Overview

**Creative North Star: "Noctilucent prairie night"**

The page is a clear Alberta night with one iridescent cloud in it. Loyalty is drawn as light at that cloud's edge: a regular client is a vivid fringe, a new one is still forming, a client who has quietly stopped coming is a fringe breaking apart. Everything else stays out of the way so that edge of light is the only spectacle.

The ground is night blue, the text is silver, and colour appears only where light would: at an edge. There are no cards, no kickers, no glows. Rows are separated by hairlines, the type is one humanist sans at hairline weight for display, and violet is kept for the single action a visitor is asked to take.

**Key Characteristics:**
- One WebGL cloud in the hero, a dark silhouette that hides the stars, lit only at its edge, capped at 30fps, paused offscreen, a still frame under reduced motion.
- The spectrum (mint, ice, violet, rose) appears only as a fringe: the cloud edge, the client edges, the logo mark, the phone frame's hairline.
- Hairline-ruled rows instead of containers.
- Hairline display type (weight 200) against a comfortable 400 body.

## Colors

### Primary
- **Violet** `#b8a4ff`: the one action. Primary button edge, focus ring, caret, "With me" labels. Nowhere decorative.

### Secondary
- **Spectrum fringe** mint `#8eeecf`, ice `#86c6ff`, violet, rose `#f3a8c8`, always together as a gradient edge, never as a fill.
- **Rose** alone marks a client who is drifting or gone, and a form error.

### Neutral
- **Night** `#070b16` page ground, **Night 2** `#0b1222`, **Dusk** `#13203a` for the bottom of the hero sky.
- **Silver** `#e8ecf2` text, **Mist** `#a8b2c3` secondary text, **Faint** `#7f8a9e` metadata and placeholders (5.4:1 on night).
- Rules are silver at 12% and 24% alpha.

**The Edge Rule.** Colour lives on edges and on the numbers that matter, never on surfaces. Points held are ice, points earned are mint, points waiting or spent are rose. If a colour fills an area larger than a hairline, it is wrong.

**The One Violet Rule.** Violet marks the thing to do next. Two violet things on one screen means one of them is lying.

## Typography

Commissioner, self-hosted as a variable woff2 (100 to 900), is the only face.

### Hierarchy
- **Display** (h1): 200 weight, up to 5.9rem, line-height .98, tracking -0.035em. The emphasised phrase steps up to 300, never italic, never gradient.
- **Headline** (section h2): 200 weight, up to 3.6rem.
- **Title** (project h3): 250 weight, up to 2.6rem.
- **Body**: 400 at 1.0625rem, line-height 1.65, measure held near 36rem.
- **Small**: .9rem for status lines, labels and sample notes.

**The Hairline Rule.** Size carries hierarchy, weight stays light. Headings never go bold.

## Layout

Single column of sections inside a 78rem wrap with a fluid gutter. The hero is a two-column grid (copy, observation panel) that stacks below 60rem, with the cloud given a clear strip above the headline on phones. Client rows are three-column grids (name, edge, state) that reflow to name and state over a full-width edge below 44rem. Projects alternate text and phone recording, stacking below 54rem. No horizontal scroll at 360px.

## Elevation & Depth

The page is flat. The only shadow is under the phone recordings, a neutral black drop with offset and blur, so the device sits on the night rather than glowing in it.

**The No Glow Rule.** No coloured shadows, no zero-offset halos. Light in this world comes from the cloud, not from UI.

## Shapes

Controls are full pills. Phone frames are rounded rectangles with a 1px spectrum hairline. Everything else is square, separated by hairlines.

## Components

### Buttons
- **Primary**: pill, 1px violet border, 8% violet wash, silver text, 18% wash on hover. One per view.
- **Quiet**: pill, 24% silver border, transparent; the border turns silver on hover.
- **Disabled**: 45% opacity, not-allowed cursor.

### Inputs / Fields
Underline only, 24% silver rule, turning violet on focus. Labels above in mist. Placeholders in faint.

### Navigation
Fixed header, transparent over the sky, gaining a night background and hairline after scroll. Section links in mist, the contact action as a quiet pill. Links hide below 48rem, leaving the logo and the action.

### Who is drifting (signature)
Four invented sample clients, each an SVG edge: a 10px silver body under a 2px spectrum fringe. States are `vivid`, `forming` (animated dash), `dispersing` and `absent` (sparse dashes, faded body). "Send a note" moves a client to forming and updates a live status line.

### The thread
One client edge drawn the length of the page, built from the page's own layout. It leaves the hero from under the lit cloud, runs down a gutter beside each section, and crosses each gap in a single S to the opposite gutter, landing just above the next heading. Scrolling draws it: its head stays two thirds of the way down the screen, with a short forming stretch (the animated dash) ahead of it. It sits under the content and only ever occupies gutters and gaps. The fringe's spectrum repeats down the page, so its colour turns as it is followed. Under reduced motion the whole line is drawn and still.

### Observation panel
A sample client's points history that prints one new line every few seconds on top of already visible content. Labelled as sample data.

## Do's and Don'ts

### Do:
- Do put colour only on edges: the cloud, client fringes, the logo, hairlines.
- Do keep one violet action per view.
- Do label every piece of example data as a sample.
- Do give recordings a poster and pause them offscreen.

### Don't:
- Don't use cards, kickers, eyebrows or section numbers.
- Don't use coloured or glowing shadows.
- Don't use gradient text or bold headings.
- Don't use em dashes anywhere.
- Don't invent numbers, testimonials, prices or clients.
