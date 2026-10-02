---
name: Priyal Banthia
description: A near-black frame that holds eleven borrowed brand identities and re-skins itself for each; the only constant is her name.
colors:
  void: "#07070A"
  bone: "#F2F0EC"
  smoke: "#8D8F97"
  smoke-contrast: "#C9CBD1"
  hair-contrast: "rgba(242,240,236,.55)"
  hair: "rgba(242,240,236,.16)"
  srivari-field: "#0E3D27"
  srivari-2: "#A8C2B4"
  diamour-field: "#4A1B3D"
  diamour-2: "#C7A3BC"
  crystalicious-field: "#DED3EE"
  crystalicious-ink: "#120A1C"
  crystalicious-2: "#4A3C5E"
  sotrue-field: "#111111"
  sotrue-2: "#9B9B9B"
  slaystay-field: "#2A1C6B"
  slaystay-2: "#A9A0D8"
  numaani-field: "#7C2E13"
  numaani-2: "#EBC3AE"
  walkthetalk-field: "#EFD6CE"
  walkthetalk-ink: "#1C100A"
  walkthetalk-2: "#5C443A"
  alibaug-field: "#123E63"
  alibaug-2: "#9DBAD2"
  grandmercure-field: "#CBD8CE"
  grandmercure-ink: "#101611"
  grandmercure-2: "#47544B"
  indianchai-field: "#E4A64B"
  indianchai-ink: "#1B1206"
  indianchai-2: "#44300D"
  mcl-field: "#313B41"
  mcl-2: "#AEB7BD"
typography:
  label:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: ".6875rem"
    fontWeight: 600
    letterSpacing: ".2em"
  code:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: ".75rem"
    fontWeight: 500
    letterSpacing: ".03em"
  small:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: ".8125rem"
    fontWeight: 500
    letterSpacing: ".02em"
  body:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: ".9375rem"
    fontWeight: 400
    lineHeight: 1.6
  base:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.55
  sub:
    fontFamily: "Schibsted Grotesk, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    letterSpacing: "-.01em"
  title:
    fontFamily: "Big Shoulders Display, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.6rem, 7.4vw, 2.6rem)"
    fontWeight: 700
    lineHeight: .96
    letterSpacing: "-.005em"
  head:
    fontFamily: "Bodoni Moda, ui-serif, Georgia, serif"
    fontSize: "clamp(1.9rem, 9vw, 4.4rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-.02em"
  id:
    fontFamily: "Bodoni Moda, ui-serif, Georgia, serif"
    fontSize: "clamp(2.4rem, 13vw, 6.4rem)"
    fontWeight: 500
    lineHeight: .92
    letterSpacing: "-.02em"
  id-loud:
    fontFamily: "Big Shoulders Display, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.8rem, 16.2vw, 11rem)"
    fontWeight: 800
    lineHeight: .82
    letterSpacing: "-.01em"
  hook-a:
    fontFamily: "Bodoni Moda, ui-serif, Georgia, serif"
    fontSize: "clamp(2.6rem, 13.2vw, 7.6rem)"
    fontWeight: 900
    lineHeight: .9
    letterSpacing: "-.025em"
  hook-b:
    fontFamily: "Big Shoulders Display, ui-sans-serif, sans-serif"
    fontSize: "clamp(2.05rem, 10.6vw, 6.2rem)"
    fontWeight: 700
    lineHeight: .9
    letterSpacing: "-.005em"
rounded:
  disc: "50%"
spacing:
  s-1: "2.4px"
  s-2: "4.8px"
  s-3: "8px"
  s-4: "11.2px"
  s-5: "14.4px"
  s-6: "18.4px"
  s-7: "24px"
  s-8: "32px"
  s-9: "38.4px"
  s-10: "51.2px"
  s-11: "64px"
  s-12: "80px"
  s-13: "112px"
  gutter: "22px"
  gutter-wide: "48px"
components:
  button-primary:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.void}"
    typography: "{typography.small}"
    padding: "0 18.4px"
    height: "58px"
  button-ghost:
    backgroundColor: "{colors.void}"
    textColor: "{colors.bone}"
    typography: "{typography.small}"
    padding: "0 18.4px"
    height: "58px"
  button-ghost-hover:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.void}"
  identity-action:
    textColor: "{colors.bone}"
    typography: "{typography.small}"
    padding: "0 8px 0 14.4px"
    height: "52px"
  action-disc:
    rounded: "{rounded.disc}"
    size: "30px"
  record-now:
    textColor: "{colors.bone}"
    typography: "{typography.label}"
    padding: "2.4px 8px"
---

# Design System: Priyal Banthia

## Overview

**Creative North Star: "The Switch"**

Her craft is disappearing into other people's brands, so the page performs it. A monochrome near-black frame holds eleven full-bleed account identities, and each one re-skins the screen completely: typeface, colour, scale, alignment and arrival motion. The only constant is her name, fixed in the corner, taking its colour from whichever identity is live. The frame never carries colour; every colour on the page belongs to an account.

Phone is the composed layout (about 95% of visitors); wide screens gain columns and gutter, not new ideas. Nothing is enclosed. Structure comes from full-bleed fields and 1px hairlines. The build diverges from the contract in three recorded ways: grain sits over the eleven fields only (not over everything), the clinical voice is Schibsted Grotesk (the contract said Geist), and the section order leads with proof (hook, turn, eleven, craft, record, close).

**Key Characteristics:**
- Monochrome frame, eleven borrowed palettes, three borrowed voices.
- Cuts, not dissolves: identities change with no opacity transition.
- No card, no radius (except discs), no shadow.
- Entrance motion differs per voice; weight, never bounce.
- Nothing is hidden without JavaScript; the script only arms the stage.

## Colors

A frame of void, bone and one smoke grey, plus eleven account palettes that are content, not theme.

### Primary
- **Void** (frontmatter `void`): page ground, loader settle, and the text colour on bone buttons.
- **Bone** (`bone`, 18.3:1 on void): all frame text, the primary button fill, selection.

### Neutral
- **Smoke** (`smoke`, 6.3:1 on void): secondary frame text, the scroll cue, record metadata.
- **Hairline** (`hair`): the only divider; 1px rules and ghost-button borders.

### Account palettes
Each account contributes a field, a foreground that clears AA on it (bone on the dark fields; a near-black ink on the four light fields: Crystalicious, Walk The Talk, Grand Mercure, The Indian Chai), and a derived secondary (`*-2`) used for spec lines and notes. Declared once as `.f-*` classes, each exposing `--field`, `--fg`, `--fg-2`. Field names in the build: emerald, plum, lilac, carbon, indigo, rust, blush, deep sea, sage, amber, slate.

### Named Rules
**The Borrowed Colour Rule.** The frame is monochrome. A colour appears only as an account's own field, foreground or secondary, and only while that account is live. A new accent for the page itself is forbidden.

**The Name Observer Rule.** The fixed name takes `--chrome` from the live identity's `--fg`, and its scroll-edge wash takes `--chrome-bg` from the live `--field`, handed over by observer. Never `mix-blend-mode: difference`; over a mid-tone it cannot be guaranteed to reach AA.

**The Contrast Rule.** Every new account palette needs a foreground that clears AA on its field before it ships.

## Typography

**Display Font:** Bodoni Moda (with ui-serif, Georgia, serif), the jewelled and formal.
**Loud Font:** Big Shoulders Display (with ui-sans-serif, system-ui), the loud.
**UI/Body Font:** Schibsted Grotesk (with ui-sans-serif, system-ui), the clinical and all UI.

**Character:** Three temperaments, not three sizes. The face is chosen to match the account; the frame's own UI is always Schibsted Grotesk.

### Hierarchy
Twelve named steps; every `font-size` references one. A new size needs a rank that has none.
- **hook-a / hook-b** (Bodoni 900 / Big Shoulders 700, 0.9 line-height, uppercase): the two-voice thesis, "I don't have a style." over "I have twenty-five."; hook-b is smaller so the longer line fits on one line.
- **id / id-loud** (Bodoni 500; Big Shoulders 800 uppercase, 0.82): account names. id-loud is sized to the longest unbreakable word, Crystalicious.
- **head** (Bodoni 400, 1.05): the turn and the craft heading; Schibsted Grotesk 400 at tight tracking for clinical identities.
- **title** (Big Shoulders 700 uppercase): craft items, the quiet identity name, the identity index numeral.
- **sub, base, body, small** (Schibsted Grotesk): 17, 16, 15, 13px for record titles, body, notes, buttons.
- **code, label** (Schibsted Grotesk, 12px and 11px): label is the floor at 11px, tracked .2em uppercase for the fixed name, spec lines and the record heading. Nothing functional goes below it.

### Named Rules
**The Floor Rule.** Nothing functional is set below 11px (`label`).

**The Name Never Reflows Rule.** In the loader the name is two lines with `white-space: nowrap` so it cannot reflow between voices.

**The Display Leading Rule.** Leading tightens as type grows. Body sits at 1.5-1.6; `head` and above run 1.04-1.05, and `id-loud` runs 0.82. The turn's paragraph is `head` Bodoni at 18ch, so it is display type and takes display leading. A generic "line-height >= 1.3" check will flag it; that floor is a body-text rule and does not apply above `title`.

## Layout

Phone-first single column. Gutter 22px, 48px from 48rem; from 72rem sections centre in a 1140px measure (min 48px inset). Spacing is thirteen steps `s-1` to `s-13`, derived from the clusters actually in the file; every padding, margin and gap references one. Each identity owns a full viewport (100svh) and is laid out differently: `bottom`, `right`, `huge`, `quiet` (15rem measure), `left`, `centre`, `top`. Alignment is part of the identity. Wide screens: craft becomes two columns, record's year column widens to 7rem, actions sit in two 19rem columns, the hero portrait narrows and dims to .46, and two identities gain a plate image.

Scroll mechanics: armed, a sticky stage pins one identity at a time while invisible triggers supply scroll range; a one-pixel band at the viewport middle selects the live one. Unarmed, the eleven are full-screen panels in normal flow. Layers: `z-base` 1, `z-mark` 55, `z-vig` 60, `z-boot` 80.

## Elevation & Depth

Flat. Zero `box-shadow` in the file. Depth is atmosphere only: a fixed radial vignette over the page whose opacity is handed over with the chrome (`--vig-o`, 0 on the four light fields), film grain (overlay, .1 opacity) on the eleven coloured fields only, and a mask-faded wash of the live field behind the fixed name so text can pass under it. The wash is a scroll edge, never a divider.

### Named Rules
**The Grain Placement Rule.** Grain lives on `.id::after` only. Over the near-black frame, at the opacity it needed, it never reached the screen.

**The Vignette Belongs to the Frame Rule.** The vignette is the black frame's atmosphere. Over a light account field it is a grey-brown smudge belonging to no account, which breaks Borrowed Colour, so `live()` sets `--vig-o: 0` for those palettes and the exit sentinel restores it.

**The No-Shadow Rule.** No shadow, glow or elevation. Hairlines and full-bleed fields do the structural work.

## Shapes

Square. No card, no radius. The single exception is the 50% action disc holding the diagonal arrow. Borders are 1px (hairline or currentColor); 2px under `prefers-contrast: more`. Plates (screenshots) are clipped rectangles at .92 opacity in their own colour: they are the only evidence on the page and dimming them into the field dimmed the proof. Each is sized to its source aspect so `object-fit` never crops readable text. The portrait is greyscale and bleeds off all four edges, fading from the band where the small type sits.

## Components

### Buttons
- **Primary** (`btn-1`): bone fill, void text, 58px tall, 18.4px side padding, 13px tracked uppercase, with a disc at the right.
- **Ghost** (`btn`): hairline border, bone text; inverts to bone fill and void text on hover (hover-capable devices only); active scales .985.
- **Disc:** 30px circle, 1px currentColor border, arrow nudges 3px up-right on hover.

### Identity action
The account handle is the action, so it is built as one: 52px tall, 1px currentColor border in the account's `--fg`, 34px disc; hover inverts to `--fg` on `--field`. Self-aligns to the identity's layout (start, end, centre). Set in the identity's own face, not the UI face. Four of the eleven (`data-act="rule"`) drop the border entirely and sit on a 1.5px rule instead, because the same enclosure eleven times reads as the card this world forbids.

### Fixed name
Top, 11px tracked caps, pointer-inert except its two links. Colour from the observer; wash behind it fades by mask.

### Record row
Year column and two-line entry on a hairline top rule. The "Current" tag is a hairline-bordered 11px tracked chip.

### Craft list
Unnumbered list of Big Shoulders titles over smoke body, hairline between items.

### Loader
CSS end to end. Eleven identity flashes at .12s each, then a black settle and a lift (translateY -101%, .42s, `--ease`). Clears itself with scripts removed; script node removal is a backstop. Removed entirely under reduced motion.

### Motion
One easing: `cubic-bezier(.22,1,.36,1)`, for weight and never bounce. The identity cut has no opacity transition, and the brand name and handle morph across it under The Carry-Over Rule. Arrival varies by voice: bodoni drifts (translateY 26px, blur 13px, .86s); loud snaps (scale 1.035, no blur, .3s); grot resolves (9px, blur 4px, .5s). The portrait is introduced: `fig-in` resolves it out of near-black over 2.6s after the loader lifts, then `fig-drift` alternates over 34s.

### Named Rules
**The Cut Rule.** A change of identity is a cut. A crossfade between two full-bleed fields reads as a dissolve and was removed.

**The Voice Owns the Identity Rule.** A voice is not a font on one heading. The index numeral and the handle are set in the identity's own face too. Setting the shared parts in one clinical face on all eleven is what makes eleven worlds read as one recoloured template. No two identities may share the same face, layout and action treatment; all eleven combinations are distinct.

**The Reach Rule.** The cut is a visual state, never an existence one. Non-live identities are `opacity: 0; pointer-events: none` and stay in the tab order and the accessibility tree; `visibility: hidden` took ten of the eleven account links out of both. Focus entering an identity makes it live.

**The Carry-Over Rule.** The field cuts; the name and the handle do not. They are the same two objects across the whole stage, carrying `view-transition-name` only while their identity is live, so the browser always has exactly one old and one new to morph between and never a duplicate. The group owns the long curve (.52s on `--ease`); the content swap is deliberately short, the old leaving on a blur in .19s and the new arriving over .28s after a .13s hold, because cross-fading bone type against near-black type is a double exposure rather than a morph. The root snapshot is not animated at all, so the field still arrives whole. One morph at a time: a cut arriving mid-morph abandons it and lands whole, which keeps a fast flick at frame rate. A browser without the View Transitions API gets the cut on its own, unchanged. What carries over does not also re-enter, so only the spec line and the note still arrive in the identity's voice.

**The One Source of Truth Rule.** Scroll position decides which identity is live. Focus therefore moves the page — it scrolls the focused identity's own trigger to the centre line — instead of setting `is-live` itself. Setting both is how the two disagreed: focusing a handle scrolled it into view, the observer then fired for whichever trigger was on the centre line, and overwrote the focus.

**The Varied Entrance Rule.** Each voice has its own entrance. One entrance repeated eleven times is scattered motion.

**The Unhidden Rule.** Nothing is hidden without JavaScript. Pre-animation states exist only under `.switch.armed`.

**The Preference Rule.** Honour `prefers-reduced-motion` (loader gone, drift stopped, transitions collapsed), `prefers-contrast: more` (hairline .55, smoke lifted to #C9CBD1, secondaries to full foreground, borders doubled) and `prefers-reduced-transparency` (grain and vignette dropped).

## Do's and Don'ts

### Do:
- **Do** keep the frame monochrome; let an account's own palette supply all colour.
- **Do** change face, scale, alignment and entrance together when adding an identity.
- **Do** reference a named type step and a spacing step for every size and gap.
- **Do** make the handle the action, and put the category in the spec line below the heading.
- **Do** keep metrics honest: only the two real follower figures (Sotrue 22.5K, SlayStay 12.3K) appear.

### Don't:
- **Don't** put a kicker or eyebrow above a heading. Eleven shipped as category labels above each brand name and were removed.
- **Don't** add cards, radii (beyond the 50% disc) or shadows.
- **Don't** crossfade identities, or use `mix-blend-mode: difference` for the name.
- **Don't** set functional text below 11px.
- **Don't** put grain over the frame; it belongs on the fields.
- **Don't** size a loud name by guess; size to the longest unbreakable word.
