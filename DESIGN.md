---
name: Priyal Banthia, Social Media Manager
description: A wholesale linesheet printed on bright white stock, where eleven live accounts are the styles and rules do all the structural work.
colors:
  paper: "#FFFFFF"
  ink: "#0A0A0A"
  ink-2: "#56565B"
  rule: "#0A0A0A"
  hair: "#D6D6D6"
  stamp: "#C8102E"
  rev-2: "#B9B9BE"
  rev-rule: "#4A4A4F"
  cw-srivari: "#0E3D27"
  cw-diamour: "#4A1B3D"
  cw-crystalicious: "#DED3EE"
  cw-sotrue: "#111111"
  cw-slaystay: "#2A1C6B"
  cw-numaani: "#7C2E13"
  cw-walkthetalk: "#EFD6CE"
  cw-alibaug: "#123E63"
  cw-grandmercure: "#CBD8CE"
  cw-indianchai: "#E4A64B"
  cw-mcl: "#313B41"
typography:
  display:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(3.2rem, 17.4vw, 9.5rem)"
    fontWeight: 800
    lineHeight: 0.82
    letterSpacing: "-0.015em"
    fontVariation: "'wdth' 64"
  headline:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.75rem, 8.2vw, 2.6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 70"
  figure:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.55rem, 5.2vw, 2.1rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontVariation: "'wdth' 76"
  title:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.1875rem"
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: "0.01em"
    fontVariation: "'wdth' 82"
  subtitle:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: "0.02em"
    fontVariation: "'wdth' 84"
  body:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
    fontFeature: "tabular-nums"
  body-2:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "normal"
  small:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
    lineHeight: 1.5
    letterSpacing: "0.12em"
    fontVariation: "'wdth' 88"
  code:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    letterSpacing: "0.06em"
    fontVariation: "'wdth' 88"
  label:
    fontFamily: "Archivo, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 600
    letterSpacing: "0.14em"
    fontVariation: "'wdth' 92"
rounded:
  none: "0"
spacing:
  gut-phone: "20px"
  gut-wide: "32px"
  gut-desk: "48px"
  hair: "1px"
  heavy: "3px"
  measure: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.small}"
    rounded: "{rounded.none}"
    padding: "0 1rem"
    height: "52px"
  button-primary-hover:
    backgroundColor: "{colors.stamp}"
    textColor: "{colors.paper}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "0 1rem"
    height: "52px"
  button-ghost-hover:
    backgroundColor: "{colors.stamp}"
    textColor: "{colors.paper}"
  tick-box:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    size: "30px"
  tick-box-checked:
    backgroundColor: "{colors.stamp}"
    textColor: "{colors.paper}"
  colourway-chip:
    rounded: "{rounded.none}"
    size: "1rem"
  tag-current:
    backgroundColor: "{colors.stamp}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.1rem 0.4rem"
  order-slip:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "0.65rem 20px"
---

# Design System: Priyal Banthia, Social Media Manager

## Overview

**Creative North Star: "The Linesheet"**

This is the wholesale document a D2C fashion label sends a buyer: Priyal is the label, her eleven live accounts are the styles, and the page is one sheet of stock. It is printed on bright white (#FFFFFF), not cream, because a real linesheet is an unglamorous trade document and that plainness is what makes it persuasive. The cream-ground, high-contrast-serif reading of "fashion document" is the confirmed anti-reference; so is the freelancer portfolio arrangement of hero band, service card grid, and "selected work".

Structure is carried entirely by rules. A hairline (#D6D6D6) separates rows inside a block; a full-ink rule (#0A0A0A) separates records; a three-pixel heavy rule closes a section. Nothing on the page is enclosed: no card, no container, no tint panel, no radius anywhere, and no shadow at rest. Density is a trade document's, close-set and ruled rather than airy, and every field is named before its value, including the blank ones ("Audience / Not published").

The phone is the real layout, not the small one. Roughly 95% of visitors arrive on a phone, so 390px is where the sheet is composed and wider viewports simply gain columns, the way a linesheet gains them on a larger press sheet. Functional text never drops below 11px (0.6875rem), a floor set by measured legibility failure at 9 and 10px on this audience's devices.

**Key Characteristics:**
- Bright white stock, one black ink, one trade red
- One typeface, Archivo variable, worked across width and weight
- Rules do the structural work; nothing is ever enclosed
- Zero radius, zero resting shadow, zero tint panel
- Phone-primary at 390px; wide layouts add columns, not ideas
- Every field named, blanks shown as blanks
- Tabular figures everywhere

## Colors

A monochrome trade sheet with exactly one accent, plus eleven sample chips that are never page colour.

### Primary
- **Stamp Red** (#C8102E): The single accent, 5.9:1 on paper. It appears in four places only: the checked tick box, the order slip's top rule, the Current tag on the provenance block, and interactive feedback (button hover/active, link hover, focus-visible outline). Nowhere else.

### Neutral
- **Linesheet White** (#FFFFFF): The page ground. The only background in the system apart from the one reversed surface.
- **Press Black** (#0A0A0A): Body ink at 20.0:1, and the same value serves as the structural rule colour. Ink and rule are deliberately one value, not two.
- **Second Ink** (#56565B): Supporting text at 7.2:1 — labels, codes, section prose, spec values, notes. The entire secondary voice is this one grey.
- **Hairline** (#D6D6D6): Non-text only. Divides rows inside a block and the masthead bar at rest. It never carries meaning on its own.
- **Reversed Second Ink** (#B9B9BE): Supporting text on the ink-filled order slip, 10.1:1 on ink.
- **Reversed Rule** (#4A4A4F): The border on controls sitting inside the ink-filled order slip.

### Tertiary
- **The Eleven Colourways** (#0E3D27 Emerald, #4A1B3D Plum, #DED3EE Lilac, #111111 Carbon, #2A1C6B Indigo, #7C2E13 Rust, #EFD6CE Blush, #123E63 Deep Sea, #CBD8CE Sage, #E4A64B Amber, #313B41 Slate): Each is a real account's own palette, printed as a 1rem swatch chip in the spec block and as a full-width chip in the masthead colourway strip. They are sample material on a shade card, never page colour.

### Named Rules
**The One Ink Rule.** The page has one ink and one accent. The accent is reserved for ticks, the slip's top rule, the Current tag, and interaction feedback. Any new need answered with a second colour is a failure of the world.

**The Sample Material Rule.** A colourway belongs to its account, not to the page. It may fill a chip and nothing else: never a background, never a text colour, never a section tint.

**The Rule Is The Structure Rule.** A rule at full ink means structure. A hairline is decoration-weight and never carries meaning alone. There is no third stroke colour.

## Typography

**Display Font:** Archivo variable (with ui-sans-serif, system-ui, sans-serif)
**Body Font:** Archivo variable — the same family
**Label/Mono Font:** Archivo variable with `font-variant-numeric: tabular-nums` set on `body`

**Character:** One family, worked hard. The axes are wdth 62..125 and wght 100..900, and the whole hierarchy is built from width and weight rather than from a second face: display sits at 64% width / 800, body at 100% / 400, labels at 92% / 600. A trade document's hierarchy, not a magazine's.

### Hierarchy

Ten sizes, and that is the whole ramp. Every one carries a rank; no size exists that another rank could have used.

- **Display** (800, clamp(3.2rem, 17.4vw, 9.5rem), 0.82, wdth 64%, uppercase): The name in the masthead, two lines, flush left.
- **Headline** (800, clamp(1.75rem, 8.2vw, 2.6rem), 0.95, wdth 70%, uppercase): Every section heading, including the closing order heading. A closing heading is not a higher rank than the ones before it, so it does not get a larger size.
- **Figure** (800, clamp(1.55rem, 5.2vw, 2.1rem), 1.0, wdth 76%, tabular): The three trade-header numbers a buyer checks first. One fluid value across all viewports, not a size plus a desktop override.
- **Record Title** (700, 1.1875rem, wdth 82–84%, uppercase): The title of any record on the sheet — a service, an employer, a style. All three are the same rank, so all three are the same size, and a record title does not change size at a breakpoint.
- **Subtitle** (700, 1.0625rem, wdth 84–86%, uppercase): The next rank down — a contents entry, the order slip's running total, the showroom contact name.
- **Body** (400, 16px, 1.5): Running prose, one value at every width. Measures cap at 46ch for section intros, 48ch for provenance notes, 52ch for service copy, 56ch for the sheet note.
- **Secondary Body** (400, 0.875rem / 14px, second ink): Supporting text inside a record, a 2px step under body — the spec value, the provenance role and note, the masthead meta value, the footer link.
- **Small / UI** (600–700, 0.8125rem, 0.04–0.12em, wdth 80–90%): Control and strip type — the button label, the masthead bar name, the group head, the style link, the sheet note, the showroom line, the footer line.
- **Code** (600, 0.75rem, 0.06em, wdth 88%, tabular): Style numbers, years, counts, section numbers, the slip's style list and send control.
- **Label** (600, 0.6875rem, 0.14em, wdth 92%, uppercase, second ink): Every named field — spec keys, figure captions, plate captions, the tick's "Add", slip headings, the Current tag. This is also the floor.

### Named Rules
**The One Family Rule.** Archivo variable is the entire typographic system. A second face is never the answer to a hierarchy problem; narrow the width axis or raise the weight instead.

**The 11px Floor Rule.** No functional text below 0.6875rem (11px). This audience is mobile-only and 9px and 10px labels were a measured legibility failure here.

**The One Size Per Rank Rule.** Ten sizes is the ramp. A new size is only justified by a rank that does not yet exist, never by a context: same rank, same size, whatever the block and whatever the viewport. A rank that needs to grow gets a clamp, not a breakpoint override — and where the growth would span a pixel or two, it gets the larger value at every width instead, which is how body arrived at a single 16px. The phone reads the same size the desktop does.

**The Running Head Rule.** `SECTION 01`..`04` are wayfinding, set above the section rule with the heading well below, and referenced by the contents index. They are not kickers hugging an h2; an earlier build had kickers and they were removed.

## Layout

A single ruled column. Sheet margin is a `--gut` custom property stepping 20px (phone) → 32px (≥34rem) → 48px (≥64rem), and at the widest step the sheet, masthead bar and footer share `padding-inline: max(48px, calc((100vw - 1180px) / 2))`, capping the measure at 1180px.

Two breakpoints only. At **34rem** the action buttons go horizontal with a 16rem minimum, and the spec block doubles to two key/value pairs per row. At **64rem** the masthead meta moves up beside the name, the services list and provenance read as ruled columns, and the style rows become a five-track ruled table (`8rem | minmax(0,19rem) | 14rem | 1fr | 3rem`) where the style count, name, spec, slack and tick each own a track so nothing can wrap against the tick. The order section splits `1fr 20rem` with the showroom contact at the side.

Vertical rhythm is set by section padding (2.4rem on phone, 4rem at 64rem) and by row padding of roughly 1rem top / 1.1rem bottom against the rules. The masthead sits under a sticky bar (56px-ish, z-index 40) whose bottom border upgrades from hairline to full rule once the sheet has scrolled. When the order slip is up it is fixed at the foot (z-index 50) and pushes `--slip-h` of padding onto the body so the last rows never sit under it.

### Named Rules
**The Phone Is The Sheet Rule.** 390px is the composed layout. Wider viewports add columns to the same rules; they never get a different arrangement, a different component, or content the phone does not have.

## Elevation & Depth

There are no shadows. Not one `box-shadow` exists in the build, at rest or on any state. Depth is entirely a matter of stroke weight and reversal: a hairline recedes, a full-ink rule sits forward, a three-pixel heavy rule closes a block, and the single reversed surface (the ink-filled order slip, with its red top rule) reads as a slip laid over the sheet without needing a shadow to say so. Layering is managed by z-index alone — bar at 40, slip at 50.

### Named Rules
**The Nothing Is Enclosed Rule.** No card, no container, no panel, no tint, no radius, no shadow. If a new element seems to need a box to be legible, it needs a rule and a label instead.

## Shapes

Zero radius, everywhere, on everything: buttons, the tick box, colourway chips, image plates, the order slip, the Current tag. Corners are square because the sheet is printed, not rendered.

The only form vocabulary is the stroke. Three weights exist: the hairline (1px #D6D6D6), the rule (1px #0A0A0A), and the heavy rule (3px #0A0A0A, which closes a section and tops the order slip in stamp red). Images are bordered plates — a 1px ink frame with a ruled caption bar beneath, capped at 20rem wide. Icons are inline SVG from a `<symbol>` sprite, stroked at 1.6–2.6 with square caps so they share the rules' drawn quality; there are no glyph or font icons.

## Components

### Buttons
- **Shape:** Square (0 radius), 52px minimum height, 1px border matching the fill
- **Primary:** Ink fill (#0A0A0A) with paper text, set in Small/UI at 0.8125rem / 700 / wdth 88% / 0.12em, padding `0 1rem`, icon pushed to the far edge by `justify-content: space-between`
- **Hover / Focus / Active:** Fill and border both go stamp red over 0.16s linear; hover only under `(hover:hover)`, `:active` always. Focus-visible is a 2px stamp outline at 3px offset.
- **Ghost:** Transparent fill, ink text, same ink border and the same red takeover on interaction
- **Wide:** 16rem minimum width from 34rem up, laid out in a row

### Chips
- **Style:** A 1rem square of the account's own colourway, filled from a `--c` custom property set inline, with a `rgba(10,10,10,.28)` hairline so pale colourways still read against white
- **Masthead variant:** The same chip stretched to a flex track, 2.1rem tall, eleven across with a 4px gap — the shade card on the cover

### Cards / Containers
None. The system has no card. Records are rows separated by rules, closed by a heavy rule. See the Nothing Is Enclosed Rule.

### Inputs / Fields
- **The tick:** A real `<input type="checkbox">`, visually hidden, with a 30px square box inside a 44px label target. Checked state fills stamp red and inks a check that scales from 0.6 to 1 over 0.14s. Focus-visible draws the 2px stamp outline on the box.
- **Critical:** the checked selector is the **general** sibling combinator (`.tick input:checked ~ .box`), because an inline "Add" label sits between the input and the box. An adjacent combinator silently breaks the checked state while scripted measurement still reports success.

### Navigation
- **Masthead bar:** Sticky, paper ground, name at 0.8125rem / 700 / wdth 80% / 0.1em uppercase on the left, `Linesheet / 2026` in code type on the right. Bottom border is a hairline at rest and upgrades to full rule once scrolled (`[data-stuck]`, driven by an IntersectionObserver probe).
- **Contents index:** The catalogue's own index, shipped as sheet content rather than a hidden drawer because on a phone it is the most useful block on the page. Four rows, each a hairline-topped flex line of section number / name / count, closed by a 3px rule. Hover reds the name.

### The Order Slip (signature)
The sheet is orderable. Ticking styles builds a running slip fixed at the foot: ink ground, stamp-red 3px top rule, a label, a count in subtitle type (1.0625rem), a truncated list of style codes in code type (first three, then `+n`), a paper-filled Send button and a 34px clear control bordered in reversed rule. It rises on `translateY(101%) → 0` over 0.26s `cubic-bezier(.2,.8,.2,1)` and sets `--slip-h` so the body gives back the height it covers. Bottom padding respects `env(safe-area-inset-bottom)`.
- **No-JS guarantee:** the script only ever adds. Without it the slip does not exist, no control is left dead, every style row still links out, and the mailto still works. The script-stripped page renders pixel-identical at 390.

### Motion
The only authored motion in the build: the two masthead rules draw themselves once on load (`scaleX(0) → 1`, 0.5s, staggered 0.1s, transform-origin left), the tick inks, and the order slip rises. Nothing fades in, nothing floats, nothing is hidden to achieve an entrance. `prefers-reduced-motion: reduce` flattens all animation and transition to 0.01ms and turns off smooth scrolling.

## Do's and Don'ts

### Do:
- **Do** build structure from rules: hairline (1px #D6D6D6) inside a block, full rule (1px #0A0A0A) between records, heavy rule (3px) to close a section.
- **Do** keep every new surface at 0 radius and 0 shadow.
- **Do** derive hierarchy from Archivo's width and weight axes (wdth 62..125, wght 100..900) rather than reaching for a second family.
- **Do** reuse the ramp's existing size for anything of an existing rank, and reach for a clamp rather than a breakpoint override when a rank needs to grow.
- **Do** name every field before its value, and print a blank as a stated blank ("Not published") rather than hiding the row.
- **Do** compose at 390px first; let wider viewports add columns to the same rules.
- **Do** hold functional text at or above 0.6875rem (11px).
- **Do** use `.tick input:checked ~ .box` — the general sibling combinator — whenever a label sits between an input and its visual box.
- **Do** write a two-class override (`.order .addr`) when a single class would lose specificity to an element-scoped rule like `.order p { max-width:46ch }`; the miss only shows at a wide viewport.
- **Do** keep stamp red to ticks, the slip's top rule, the Current tag, and interaction feedback.
- **Do** ship interactive enhancement as additive only: the script-stripped page must stay whole and pixel-identical.

### Don't:
- **Don't** enclose anything in a card, container, panel, or tinted block.
- **Don't** introduce a radius, a resting shadow, or a second accent colour.
- **Don't** use a colourway as page colour, a background, or a text colour; it fills a chip and nothing else.
- **Don't** add a second typeface, including for labels, code, or numerals.
- **Don't** add a size to the ramp for a context rather than a rank, and don't re-size an existing rank at a breakpoint.
- **Don't** set a kicker or eyebrow above a heading. Section numbers are running heads above the section rule, referenced by the contents index.
- **Don't** let a hairline carry structural meaning on its own.
- **Don't** add motion beyond a rule drawing, a tick inking, or the slip rising. No fades, no floats, no parallax.
- **Don't** invent a metric or print a compensation figure anywhere on the sheet.
