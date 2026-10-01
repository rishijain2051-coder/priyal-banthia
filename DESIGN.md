---
name: Priyal Banthia, Social Media Manager
description: A rose-warm paper page where eleven brand accounts each keep their own colour world inside one left edge.
colors:
  paper: "#F6F1F2"
  paper-card: "#FFFBFC"
  paper-sunk: "#EDE5E7"
  ink: "#221B1D"
  ink-soft: "#6B5D60"
  rule: "#DED2D6"
  rule-soft: "#E8DEE0"
  accent: "#9E3B54"
  accent-sunk: "#7E2C42"
  field-default: "#241F1E"
  field-fg: "#FFFBFC"
  field-fg-light: "#2A1B1E"
  field-sotrue: "#111111"
  field-srivari: "#0E3D27"
  field-mcl: "#313B41"
  field-alibaug: "#123E63"
  field-grandmercure: "#CBD8CE"
  field-slaystay: "#2A1C6B"
  field-numaani: "#7C2E13"
  field-diamour: "#4A1B3D"
  field-walkthetalk: "#EFD6CE"
  field-crystalicious: "#DED3EE"
  field-indianchai: "#E4A64B"
typography:
  display:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.3rem, 6.4vw, 3.5rem)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.038em"
  headline:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.65rem, 4.4vw, 2.35rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.028em"
  headline-closing:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.85rem, 5.2vw, 2.6rem)"
    fontWeight: 600
    lineHeight: 1.06
    letterSpacing: "-0.028em"
  title:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.15rem, 2.5vw, 1.4rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.034em"
  list-title:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 2.3vw, 1.4rem)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.034em"
  subtitle:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  subtitle-wide:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.0625rem, 2.2vw, 1.3rem)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  year:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 600
    letterSpacing: "-0.02em"
    fontFeature: "tabular-nums"
  year-sticky:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.35rem, 2.5vw, 1.95rem)"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "-0.02em"
    fontFeature: "tabular-nums"
  boot-wordmark:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.45rem, 5.6vw, 2.4rem)"
    fontWeight: 700
    letterSpacing: "-0.045em"
  figure:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "-0.03em"
    fontFeature: "tabular-nums lining-nums"
  body:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    fontFeature: "ss01, cv05"
  body-small:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.06em"
  day-label:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 500
    letterSpacing: "0.08em"
  meta:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    fontFeature: "tabular-nums"
  micro:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.4
  footnote:
    fontFamily: "Instrument Sans, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 400
rounded:
  focus: "2px"
  micro: "5px"
  cell: "6px"
  base: "10px"
  marker: "50%"
  scroll-thumb: "99px"
spacing:
  gutter: "clamp(1.25rem, 5vw, 2.5rem)"
  section: "clamp(3rem, 7vw, 4.75rem)"
  stack: "1.5rem"
  row: "1.1rem"
  tile-gap: "0.7rem"
  inline-gap: "0.75rem"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper-card}"
    typography: "{typography.body-small}"
    rounded: "{rounded.base}"
    padding: "0.72rem 1.15rem"
  button-primary-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.paper-card}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.body-small}"
    rounded: "{rounded.base}"
    padding: "0.72rem 1.15rem"
  button-ghost-hover:
    backgroundColor: "{colors.paper-card}"
    textColor: "{colors.ink}"
  account-tile:
    backgroundColor: "{colors.field-default}"
    textColor: "{colors.field-fg}"
    rounded: "{rounded.base}"
    padding: "1.1rem"
    height: "10.5rem"
  account-tile-light:
    backgroundColor: "{colors.field-walkthetalk}"
    textColor: "{colors.field-fg-light}"
    rounded: "{rounded.base}"
    padding: "1.1rem"
    height: "10.5rem"
  status-chip:
    backgroundColor: "color-mix(in oklab, #9E3B54 12%, #F6F1F2)"
    textColor: "{colors.accent-sunk}"
    typography: "{typography.label}"
    rounded: "{rounded.micro}"
    padding: "0.22rem 0.42rem"
  timeline-marker:
    backgroundColor: "{colors.rule}"
    size: "7px"
  timeline-marker-current:
    backgroundColor: "{colors.accent}"
    size: "7px"
  masthead:
    backgroundColor: "color-mix(in oklab, #F6F1F2 86%, transparent)"
    textColor: "{colors.ink-soft}"
    height: "4rem"
    padding: "0 clamp(1.25rem, 5vw, 2.5rem)"
  hero-cell:
    backgroundColor: "{colors.field-sotrue}"
    rounded: "{rounded.cell}"
    size: "1fr"
  calendar-entry:
    backgroundColor: "{colors.paper-card}"
    textColor: "{colors.ink}"
    typography: "{typography.list-title}"
    rounded: "{rounded.base}"
    padding: "1rem 1.05rem 1.1rem"
---

# Design System: Priyal Banthia, Social Media Manager

## Overview

**Creative North Star: "Eleven Worlds, One Left Edge"**

The page makes a single argument: one manager has run brands that share no visual language at all, from a black skincare feed to a highway contractor. So the system is built as a quiet stage carrying loud evidence. The stage is rose-warm paper, hairlines, one accent, and a left edge that never moves from the masthead wordmark to the footer line. The evidence is a mosaic of eleven coloured tiles, each wearing its own brand's colour, and a header built from the same eleven: a 3×3 grid of account fields with her cut out of her own photograph standing in front of it. Her medium is the grid, so the page opens on one. The restraint of the stage is what lets the range of the tiles read as range rather than noise.

Density is editorial rather than promotional: facts sit in a run of 1px rules instead of big-number cards, roles hang off a marker spine under a sticky year, and the services are laid out as a working week. Surfaces are flat at rest: there is no at-rest atmospheric shadow anywhere in the build, and depth is carried by hairlines, by the tonal step between paper and card-paper, and by colour. Everything that lifts earns it by being touched. The page is light-locked — there is no dark theme, no `prefers-color-scheme` branch and no toggle — and the light stage is load-bearing, because the dark account fields only read as objects sitting on a page if the page under them is paper.

The palette leans rose on purpose: the warm neutral is pulled toward red-violet rather than yellow, and the accent is a muted wine. The beige / brass / espresso portfolio family was rejected. The hue test is mechanical and the trap is real — an earlier shipped ramp read as peach because its green channel sat above its blue.

The world was chosen by interview, not by roll. Three materially different directions were put to the user with their trade-offs stated inside each option; the user chose "The Feed" and a light warm neutral over a recommended dark stage, then redirected the section order and asked for the entrance overlay mid-build. There is no seed key because no script roll ran. The light lock is the user's own decision against the recommendation, not a default.

**Key Characteristics:**
- Rose-warm paper stage, never yellow-beige, never dark
- One accent (`#9E3B54`) whose visible home is the primary action: it fills the primary button at rest, and also carries focus, caret, selection and the current-role marker
- One left edge for every section, one reading measure inside it
- A single 10px radius for anything interactive or tiled, 6px for the header grid cells; no pills
- Eleven per-account colour fields treated as content, not theme
- Hairlines, markers and a calendar grid instead of cards; flat until touched, with no at-rest shadow
- Browser chrome (selection, caret, scrollbar, focus ring) themed from the palette
- Icons authored inline at one stroke weight; no icon library, no emoji

## Colors

A warm neutral that leans rose rather than yellow, one wine accent, and eleven per-account content fields that are explicitly not part of the theme.

### Primary
- **Wine Accent** (`{colors.accent}`): The page's single voice, and its one visible home is the primary action. It fills the primary button at rest with a `{colors.paper-card}` label (measured 6.38:1), and it also carries the `:focus-visible` ring, the text caret, the `::selection` background, the favicon tile, the current-role marker on the timeline spine, and the status chip's tinted background. It is never a section background and never a body text colour. Measured 5.9:1 on paper.
- **Wine Deep** (`{colors.accent-sunk}`): The accent's pressed-deeper step. It is the primary button's hover fill and border, and the "Current" chip's label colour, where accent-coloured text at 11px needs the extra depth to clear AA.

### Neutral
- **Rose Paper** (`{colors.paper}`): The page background, the scrollbar track, and the halo punched around each timeline marker so the spine appears to pass behind it.
- **Card Paper** (`{colors.paper-card}`): Slightly lifted off-white. The primary button's label, the `::selection` foreground, and the ghost button's hover fill.
- **Sunk Paper** (`{colors.paper-sunk}`): The portrait frame's backing while the image loads.
- **Ink** (`{colors.ink}`): Body and heading text, and the primary button's rest fill and border. Measured 15.1:1 on paper.
- **Soft Ink** (`{colors.ink-soft}`): Every piece of secondary text on the paper stage — ledes, service descriptions, years, job titles, timeline detail, roster note, footer, nav links at rest. Measured 5.53:1 on paper.
- **Rule** (`{colors.rule}`): The structural hairline. The scale band's top and bottom edges, the masthead's rule once scrolled, the scrollbar thumb, the default timeline marker.
- **Soft Rule** (`{colors.rule-soft}`): The quieter hairline. Section separators, list separators, band cell dividers, footer top edge, and the timeline spine itself.

### Account Fields
Eleven named fields (`{colors.field-sotrue}` through `{colors.field-indianchai}`) declared once on `:root` as `--f-*` and read from there by all three surfaces that use them — the mosaic tiles, the header grid and the loader — plus the `{colors.field-default}` fallback declared on the tile itself. They are defined in one place because duplicating them let a consumer go stale. Each belongs to one real brand. Four of the eleven sit lighter than the page and carry `{colors.field-fg-light}` foreground; the other seven carry `{colors.field-fg}`. Grand Mercure is a pale sage (`{colors.field-grandmercure}`) rather than the deep teal it once was, because that teal was a near-twin of Srivari's green and the brand is a hotel, not a jewellery label — two fields that read as one colour cost the set an account's worth of range.

This family, and every secondary text colour derived from it, is deliberately exempt from palette enumeration. Twenty-two derived values exist only at paint time (eleven fields × two roles), for example `rgb(203,200,200)` on Sotrue's category label, `rgb(202,209,205)` on Srivari's, `rgb(81,64,65)` on the light Walk The Talk field and `rgb(79,55,39)` on the light Indian Chai field. A colour audit will report them as drift; they are not drift, and they must not be pinned to literals or flattened to a grey. The loader's four platform marks carry their own brand hexes (`#E4405F`, `#0866FF`, `#0A66C2`, `#0467DF`) and are exempt on the same grounds: they are third-party marks, not palette. The same eleven values, in mosaic order, are the only colour in the entrance overlay. Worst measured contrast across the set is 4.98:1, on the lightest tile.

### Named Rules
**The Blue Over Green Rule.** Rose-warm means the blue channel sits at or above the green channel in every neutral. The shipped paper measures `rgb(246,241,242)`. A warm neutral whose green exceeds its blue is yellow-beige or peach wearing the rose label, and it passes a visual glance while failing the brief. Check the channels, not the impression.

**The One Accent Rule.** There is exactly one accent, it is used across the whole page rather than per section, and it must actually reach the eye on the primary action rather than surviving only in a badge. A new surface that wants a second accent needs a different argument, not a different colour.

**The Own Base Colour Rule.** Any surface that cycles through the fields takes its own first field as its static base, never a shared one. The header grid's nine cells each sit on their own `--c1`: based on a single shared field the whole grid rendered as one colour with animation off, so every reduced-motion visitor lost the range the grid exists to show. An animated set must still read as a set when the animation never runs.

**The Field Is Content Rule.** The eleven `--field` values are content tokens, not theme tokens. They exist because the brands they stand for exist. Never recolour UI from a field, never add a twelfth field without a twelfth account, and never choose a field for compositional balance alone.

**The Lightness Range Rule.** The field set ranges across lightness as well as hue, and some fields must sit lighter than the page. Eleven dark fields of similar value collapse into one dark mass and the page loses its argument. A light field flips both the foreground and the direction of its gradient lift.

**The Derived Secondary Rule.** Secondary text on a coloured field is derived from that field itself with `color-mix(in oklab, var(--fg) N%, var(--field))`, preceded by an equivalent `rgba()` fallback declaration. It is a computed value, not a palette entry, and it is never grey, never a blanket opacity, and never a hand-picked second colour per tile. Grey on a coloured surface is the failure this rule exists to prevent, so a derived secondary is never "fixed" by being replaced with a neutral.

**The Light-Locked Rule.** No dark theme, no `prefers-color-scheme` branch, no toggle. The light stage is a decision, not a default.

**The Chrome Is Ours Rule.** Selection, caret, scrollbar track and thumb, focus ring and underline offset are all drawn from the palette. The parts nobody designs still carry the design.

## Typography

**Display Font:** Bricolage Grotesque (variable, 400–800, falling back to `ui-sans-serif` / `system-ui`)
**Body Font:** Instrument Sans (variable, 400–600 plus italic, same fallback)

**Character:** Bricolage's slightly irregular grotesque carries every heading with tight negative tracking, which keeps a one-page portfolio from reading corporate; Instrument Sans underneath is plain and high-legibility and stays out of the way. Body text runs with the `ss01` and `cv05` stylistic sets on. No serif anywhere, and no system display face.

### Hierarchy
- **Display** (`{typography.display}`): The hero headline only. Its measure is the grid column, with no character cap.
- **Headline** (`{typography.headline}`): Section titles.
- **Headline Closing** (`{typography.headline-closing}`): The contact section's title only, one step larger because it is the page's final ask.
- **Title** (`{typography.title}`): The employer name on each timeline row — the largest display text inside a section, because that is the word both audiences scan for.
- **List Title** (`{typography.list-title}`): Calendar entry titles in the services section. They previously sat at body size, which made the section read as grey paragraphs; the scale step is the fix, so it is part of the ramp rather than a local override.
- **Subtitle** (`{typography.subtitle}`): Account names in the mosaic. Display face at body size, distinguished by family and weight rather than scale.
- **Subtitle Wide** (`{typography.subtitle-wide}`): The account name in a double-width mosaic cell only; single-width cells stay at subtitle.
- **Year** (`{typography.year}`): The timeline's scan column below 52rem, display face and tabular.
- **Year Sticky** (`{typography.year-sticky}`): The same year from 52rem up, where it becomes the row's sticky label in a `9.5rem` column. Sized deliberately — at a larger scale the widest label, the `2025-26` range, overran its column and collided with the employer names.
- **Day Label** (`{typography.day-label}`): The Mon–Sun header over the services calendar. Uppercase at `.08em`, a touch wider than the tile label, because seven three-letter words need the extra separation to read as a header row.
- **Micro** (`{typography.micro}`): Scale band captions and small secondary text.
- **Footnote** (`{typography.footnote}`): The footer line.
- **Boot Wordmark** (`{typography.boot-wordmark}`): The loader's name, the only type on that surface. It animates its own tracking from `.04em` to `-.045em` as it emerges.
- **Figure** (`{typography.figure}`): Follower counts inside account tiles.
- **Body** (`{typography.body}`): All running prose. Paragraphs cap at 64ch globally, with tighter local caps where the column is narrower: 46ch in the hero, 50ch on timeline detail, 34ch on calendar entry descriptions.
- **Body Small** (`{typography.body-small}`): Job titles, service descriptions, timeline detail, nav links, button labels.
- **Label** (`{typography.label}`): The uppercase category label inside an account tile, and the "Current" status chip. The only uppercase type in the system, and it never appears above a section heading.
- **Meta** (`{typography.meta}`): The account handle line with its outbound arrow.

### Named Rules
**The Tabular Figure Rule.** Every number that can be compared or scanned carries `font-variant-numeric: tabular-nums` — band figures, timeline years, follower counts, handle metadata. Figures never reflow their own column.

**The Measure Rule.** Prose is capped in characters, not container width. A paragraph carries its own `ch` cap, so a list can run wider than the reading column without its text running long.

**The No Ch-Cap On Display Rule.** Display type whose line count matters carries no `ch`-based max-width. The hero's `max-width: 22ch` measured 775px against a 776px column, so it bound by one pixel with the webfont loaded and by far more with the fallback, flipping the headline to three lines until the font swapped in. A `ch` cap moves when the font moves; let the grid column be the measure.

**The Scale-By-Family Rule.** Subtitle-level text is the same size as body text and is separated from it by family, weight and tracking. Do not add a type step to signal a hierarchy that family already signals.

**The Scan Column Rule.** Inside a scannable list, the line the reader is actually hunting for gets the display face and the size step — on the timeline that is the employer, not the job title.

## Layout

One column, one left edge. Every section is `max-width: 78rem`, centred in the viewport with `clamp(1.25rem, 5vw, 2.5rem)` gutters, and its children are capped at `44rem` and left-aligned. The masthead, the scale band and the footer share that same 78rem box and the same gutter, so the wordmark, every heading, every list and the footer line all begin on one vertical edge.

Two documented exceptions, each earned by the block capping its own inner text instead: the account mosaic and the roster head run full width (`max-width: none`); and the two text lists, services and roles, share one secondary column width of `60rem` (calendar entry descriptions cap at 34ch, timeline detail at 50ch). The 60rem is a single deliberate value — an earlier 62rem/58rem pair read as accidental.

Sections are separated by a single `{colors.rule-soft}` hairline with `clamp(3rem, 7vw, 4.75rem)` of vertical padding; the first section has no top rule. Blocks inside a section stack at `1.5rem`.

Responsive behaviour is a handful of real breakpoints rather than a scale: the hero becomes two columns (`minmax(0,1fr) 21rem`) at `52rem`, where the header grid moves from above-left at `min(13rem, 62vw)` to right-aligned at full column width; the mosaic goes from 2 columns to 4 at `40rem`; the scale band from 2 to 4 at `46rem`; the services calendar collapses from its seven day columns to a single stack below `46rem`, dropping the day header with it, since a one-column week is not a week; the timeline takes its sticky year, `9.5rem` column and `10.3rem` spine from `52rem` up, and below `32rem` drops the spine and markers and falls back to hairline separators in one column; the two interior nav links hide below `32rem`. Anchored sections carry `scroll-margin-top: 5.25rem` to clear the sticky masthead.

### Named Rules
**The One Left Edge Rule.** Content is capped by a max-width on the children of a full-width section, never by centring a narrower column inside a wider one. A centred 44rem column inside a 78rem page produces two competing left edges and reads as misalignment rather than composition.

**The Own-Cap Exception Rule.** A block may exceed the 44rem reading measure only if every text run inside it carries its own `ch` cap, and when it does it goes to the one secondary width, `60rem`. One exception width, not a width per block.

**The Hairline Rule.** Runs of facts are separated by 1px rules or by a spine and markers, not wrapped in cards. Only a clickable object gets a filled, rounded container.

## Elevation & Depth

The page is flat at rest, and now literally so: no element carries an at-rest atmospheric shadow. Depth comes from hairlines, from the tonal step between paper, card-paper and sunk-paper, and from the account fields' own colour. Shadows appear in three places only — under an interactive object while it is hovered, under the one small proof thumbnail that floats over a tile, and as a structural knockout ring around each timeline marker so the spine reads as passing behind it.

### Shadow Vocabulary
- **Tile hover** (`box-shadow: 0 3px 6px rgba(34,27,29,.08), 0 20px 40px -18px rgba(34,27,29,.45)`): Account tiles while hovered, paired with a 3px lift. Light tiles use the same shape at `.35` alpha so the cast does not over-darken a pale field.
- **Accent hover glow** (`box-shadow: 0 6px 18px -6px rgba(158,59,84,.45)`): Under the primary button on hover only, tinted with the accent rather than ink.
- **Proof thumb** (`box-shadow: 0 2px 10px rgba(0,0,0,.4)`): The one small inset image floating over a tile. The only shadow using pure black, because it sits on a saturated field rather than on paper.
- **Marker halo** (`box-shadow: 0 0 0 4px var(--paper)`): Not depth — a knockout. It punches the page colour around each timeline dot so the 1px spine appears to run behind it.
- **Field lift, dark state** (`linear-gradient(155deg, rgba(255,255,255,.14), rgba(255,255,255,0) 58%)` on a `z-index: -1` pseudo-element): How a dark account field reads as a material rather than a flat swatch.
- **Field lift, light state** (`linear-gradient(155deg, rgba(0,0,0,.055), rgba(0,0,0,0) 58%)`): The same treatment inverted for the four light fields, at the same 155deg. Two states of one surface treatment, not two effects: a white gloss on a near-paper field is invisible, so the lift has to darken instead.

### Named Rules
**The Flat-Until-Touched Rule.** Shadows are a response to state, not decoration. If an element cannot be hovered or pressed it carries no atmospheric shadow, and the system now has no exception: a surface that needs to separate from the page uses a hairline and a tonal step, as the calendar entries do.

**The Ink-Tinted Shadow Rule.** Shadows are tinted with `rgba(34,27,29,…)` (ink) or with the accent, never neutral black — except where the shadow falls on a saturated field rather than on paper.

## Shapes

One radius does nearly all the work: **10px** on every interactive or tiled shape, meaning both buttons, all eleven account tiles and the six calendar entries. **6px** is the header grid's cell, a step tighter because nine small cells at 10px read as lozenges rather than a grid. Below that there are two micro radii in service roles: **5px** for the "Current" chip and the small proof thumbnail, and **2px** for the global focus ring. One `50%` circle exists — the 7px timeline marker. The scrollbar thumb is the only fully rounded shape in the build (`99px`), and it is browser chrome rather than page content. The 14px portrait frame is gone with the component that used it.

Borders are 1px and come in three kinds: a solid accent border on the primary button (the same colour as its fill, so hover can swap both at once), a `{colors.rule}` border on the ghost button darkening to ink on hover, and a `{colors.rule-soft}` border around each calendar entry, which is how those surfaces separate from the page without a shadow. Everything else that looks like a divider is a `border-top` hairline or a 1px absolutely-positioned spine, not a box.

The mosaic's geometry is deliberate: eleven tiles whose spans total 16 cells against a 4-column grid, so it tessellates exactly with no orphan row, under `grid-auto-flow: row dense`. Wide tiles use `grid-column: span 2`; the double-width set is Sotrue, Srivari, Montecarlo, The Indian Chai and SlayStay, which deliberately places one light field in a big cell (measured big-cell luminances 0.006, 0.036, 0.042, 0.443, 0.024) so the lightness range lands where the section carries its weight. Tiles are at least 9.5rem tall on phones and 10.5rem above 40rem, with their content bottom-aligned so a row of mixed tiles shares one baseline band.

### Named Rules
**The Single Radius Rule.** 10px is the radius. A new interactive surface or tile uses 10px and does not introduce a new value. 6px belongs to the header grid cells, 5px to chip-scale objects, 2px to focus shapes, `50%` to the timeline marker.

**The No Pills Rule.** Nothing in the page content is fully rounded. Buttons, tiles and chips are squared-off rectangles with a soft corner.

**The Tessellation Rule.** The mosaic's spans always sum to a multiple of its column count, and `grid-auto-flow: row dense` is the guard so a future change to the tile count backfills rather than opening a hole. A tile is not added without rebalancing the spans.

## Components

### Buttons
- **Shape:** Soft-cornered rectangle (10px), inline-flex with a `.5rem` gap for its icon, `.72rem 1.15rem` padding, never wrapping.
- **Primary:** Accent fill, `{colors.paper-card}` label (measured 6.38:1), 1px accent border. This is the accent's one visible home on the page; the primary button is not ink.
- **Hover:** Fill and border both deepen to `{colors.accent-sunk}`, plus an accent-tinted glow. `.18s` transitions on transform, background and shadow.
- **Active:** `translateY(1px)`. Pressed, not scaled.
- **Ghost:** Transparent fill, ink label, `{colors.rule}` border. On hover it fills with card-paper and its border darkens to ink; it takes no shadow. Always the second action in a pair.
- **Icons:** 16×16 inline SVG from the sprite, `flex: none`.

### Account Tile (signature component)
The argument of the page, rendered eleven times: a coloured link whose field colour belongs to the brand it represents.
- **Shape:** 10px, `overflow: hidden`, `isolation: isolate` so the gradient pseudo-element can sit behind the content at `z-index: -1`.
- **Colour:** Local `--field` and `--fg` custom properties set by an `.f-*` class. The `.light` modifier flips `--fg` to `{colors.field-fg-light}` and inverts the gradient lift to a dark one.
- **Content order:** Category label (uppercase), optional follower figure, brand name, handle with outbound arrow. Bottom-aligned.
- **Secondary text:** Derived per tile at `color-mix(in oklab, var(--fg) 78%, var(--field))` for the label and `74%` for the meta line (`80%` / `76%` on light tiles), each preceded by an `rgba()` fallback.
- **Hover:** 3px lift, layered tile shadow, and the outbound arrow nudges `translate(1px,-1px)`.
- **Active:** Lift returns to zero.
- **Proof thumbnail (one tile only):** A 4.1rem image pinned to the tile's top inline-end corner at 5px radius, widening to 5.4rem on hover. Deliberately small — proof, not a section.

### Timeline
A vertical spine with a marker per role, a sticky year per row, and an employer-leading layout: both audiences scan that column for company names, not job titles. From `52rem` up each row's year is `position: sticky` at `top: 6.25rem` inside its own row box in a `9.5rem` column with a `1.6rem` gutter and the spine moved out to `10.3rem`, so a year holds while its role passes and the next row's year pushes it out. A 1px `{colors.rule-soft}` line sits at `left: 5.05rem`, inset from the first and last row so it starts and ends at the markers rather than at the list edges. Each row is a two-column grid (`4.6rem` year column at `{typography.year}`, then content) carrying a 7px circular marker on the spine, haloed with a 4px paper ring; the current role's marker is accent-filled. The employer is the display-scale element at `{typography.title}`, the job title sits beneath it in soft ink at `.9375rem`, and the optional detail caps at 50ch. There are no row rules above 32rem — the spine and markers already do the separating. Below 32rem the spine and markers are hidden and rows revert to hairline-separated single-column blocks.

### Scale Band
Four facts in a `dl` bounded top and bottom by a `{colors.rule}` hairline, with `{colors.rule-soft}` dividers between cells. 4 columns above 46rem, 2 below, where the dividers re-wire so the first cell of each row loses its left border and flushes to the left edge. Figures use the display face with tabular numerals; captions are soft ink at `.875rem`.

### Status Chip
The "Current" marker beside the newest employer. Accent-tinted background (`color-mix(in oklab, var(--accent) 12%, var(--paper))`), deep-wine label, label typography with letter-spacing reset to `0`, 5px radius, `.22rem .42rem` padding, nudged `.22em` vertically to sit on the employer's baseline. It is a status marker inside a line of text, never a standalone badge.

### Masthead
Sticky, 4rem tall, 86% paper with a 10px backdrop blur and a `@supports` fallback to solid paper. Its bottom border starts transparent and transitions to `{colors.rule}` only once a 1px sentinel at the top of the document scrolls out of view, so the rule is earned rather than permanent. Wordmark in the display face at 700; nav links in soft ink at `.9375rem` darkening to ink on hover, with "Connect" in ink at weight 500. The two interior links hide below 32rem.

### Header Grid (signature component)
The page opens on the thing she actually makes. A square `3×3` grid of account fields at `4px` gaps and 6px cells, with her cut out of her own photograph standing in front of it, breaking the frame rather than sitting inside it (`width: 118%`, `left: -9%`, `bottom: -5%`). Each of the nine cells cycles three of the eleven fields over `30s` linear infinite, staggered `-3.1s` per cell by index, so the grid is always mid-change and never in step. Each cell's base colour is its own first field, which is what keeps the grid reading as a range when the animation never runs; `prefers-reduced-motion` sets `animation: none` and leaves nine different colours standing. The grid is `aria-hidden`, the cutout is `pointer-events: none`, and `.portrait` is now only the positioning context — there is no frame, no backing, no shadow and no aspect-ratio image rule.

### Services Calendar
The daily calendar is the deliverable, so the section is laid out as one. A `Mon–Sun` header row in day-label type over a hairline, then the six services placed across seven columns as scheduled entries by start column and span: `(1,4) (5,3) (2,3) (5,3) (1,3) (4,4)`. That leaves one empty cell at row 2 column 1, which is what a real week looks like. Entries are card-paper surfaces with a `{colors.rule-soft}` hairline and the 10px radius, `1rem 1.05rem 1.1rem` padding, title at `{typography.list-title}` and description capped at 34ch. Below `46rem` the day header is hidden and every entry spans `1 / -1`.

### Loader
Her four platforms, then her name, then the page. Four marks stack at the centre of a paper screen and spread — two up, two down — each scaling from `.62` and unrotating from a small angle, staggered `.07s` by index; her name then emerges from the gap they opened via a `clip-path` inset unfolding from the centre line while its tracking tightens; and at `1.72s` the screen splits along that same line, the two halves translating out over `.82s`.

It is built as two absolutely-positioned clipped halves, each holding an identical full-height stage, so the two read as one image until they part. The marks are centred with `inset: 0` plus `margin: auto` on a definite size, because `place-content` on the stage grid does not reach an absolutely positioned child and the marks pin to its top-left corner instead. Instagram, Facebook and Meta are Simple Icons paths (CC0); LinkedIn is the mark already in our own sprite, because Simple Icons dropped LinkedIn over trademark.

It is CSS-only end to end, so it clears itself with the script removed (the script's `2600ms` node removal is a backstop, never the mechanism), it is `aria-hidden`, and it is `display: none` entirely under reduced motion. Its roughly 2.5s hold is a cost this page carries by the user's request; it is not a pattern for new surfaces to repeat, and it must never be lengthened or made dependent on JS to clear.

### Icons
Inline SVG only, authored in a single `<defs>` sprite at the top of the body and referenced with `<use>`. Every sprite entry is a `<symbol>` carrying `viewBox="0 0 20 20"`, never a `<g>`: a `<g>` cannot establish a viewport, so art drawn in 20 user units is clipped to the consuming element's pixel box. That exact defect shipped once — all eleven outbound arrows rendered with the arrowhead cut off at 11px. Every consuming `<svg>` is `aria-hidden="true"`. One stroke weight throughout (`1.6`, round caps and joins). Three glyphs exist: outbound arrow, mail, LinkedIn mark. 16px in buttons, 11px in tile metadata.

### Imagery
Three rasters ship, all the client's own work, all out of the portfolio deck she supplied (`Priyal Banthia Portfolio (2).pdf`), extracted with pypdf and processed with PIL. The deploy set is `index.html` plus three assets, 375 KB.

- `assets/priyal-cutout.png` (330×274) is the header cutout. Its alpha matte came from rembg's `u2net_human_seg` on the same deck photograph, cropped to `y 124..398` because the matting could not separate the table and chair below that line; fringe was suppressed on the boundary ring only, since a whole-frame fringe pass caught her skin and fabric and erased her; and the bottom 70px is alpha-ramped so she dissolves into the paper rather than ending on a cut line.
- `assets/priyal-portrait.jpg` (389×519) is the unmodified extraction. It is retained and still referenced, but only as `og:image`: a transparent PNG makes a poor share card.
- `assets/srivari-thumb.jpg` is a crop of the deck's before/after page at box `(20,60,500,600)`, LANCZOS-downscaled to 420×473 at quality 86, her own published before/after of the Srivari feed.

`assets/_source/` holds unreferenced originals kept for future edits and must not be uploaded; one abandoned crop was deleted rather than shipped unreferenced.

### Motion
**The Literal Keyframe Rule.** Two animations that differ only by direction are written as two literal keyframe sets, not one set parameterised by a custom property. `transform: translateY(calc(var(--dir,-1) * 100%))` inside a keyframe computed to identity and the loader's halves never moved at all. Custom-property arithmetic inside a keyframe transform is not reliable; two plain animations cannot fail that way.

**The Can't-Desynchronise Rule.** A device that labels a row must not be able to drift from the row it names, which means CSS when CSS can do the job. The sticky year replaced a scripted pinned year that depended on an IntersectionObserver with no fallback and deduped by the year string, so the two 2025 roles made it name the wrong employer. `position: sticky` inside each row's own box cannot name anything but its own row.

The mosaic reveal is the page's one in-content animated moment: tiles settle in from `translateY(16px)` and `opacity: 0`, staggered at `46ms` each over `.66s` with `cubic-bezier(.16, 1, .3, 1)`, once, on first view. Everything else in the page body that moves is hover or active feedback at `.18s`–`.26s` on that same easing, with two standing exceptions: the header grid's slow 30s colour cycle, and the loader. Both are documented above rather than generalised into a rule, and both are a divergence from the original one-moment intent.

**The Never-Hidden Rule.** Tiles are visible in CSS by default and the script adds the pre-animation state, so with the script removed nothing is ever hidden — the no-JS page renders at the same height as the live one. The reveal class is dropped 1.5s after it fires so it can never replay, and a 2.5s failsafe timer releases it regardless of what the observer does, because the mosaic must never be able to sit at `opacity: 0`.

**The Full Collapse Rule.** `prefers-reduced-motion: reduce` collapses every transition and animation to `.01ms`, removes the loader outright, stops the header grid's cycle with `animation: none` so it rests on nine different fields, forces the mosaic to its settled state, disables the tile hover lift and turns smooth scrolling off. The reveal is never even armed when reduced motion is set.

## Do's and Don'ts

### Do:
- **Do** give every section the same 78rem box and `clamp(1.25rem, 5vw, 2.5rem)` gutter and cap its children at 44rem, so the page keeps one left edge.
- **Do** let a block exceed the reading measure only when every text run inside it carries its own `ch` cap, and send it to the one 60rem secondary width.
- **Do** check a candidate neutral channel by channel: blue at or above green, or it is not rose-warm. The shipped paper is `rgb(246,241,242)`.
- **Do** keep the accent visible on the primary action; a palette whose one accent survives only in a badge is failing the One Accent Rule, not honouring it.
- **Do** use 10px for any new interactive or tiled surface, and 6px for a small grid cell.
- **Do** derive secondary text on a coloured field with `color-mix(in oklab, var(--fg) N%, var(--field))`, with an `rgba()` fallback declared first, and expect a colour audit to flag the 22 computed results as drift. They are content, not palette.
- **Do** separate runs of facts with 1px hairlines, a spine and markers, or a calendar grid, instead of wrapping them in cards.
- **Do** give a surface that must separate from the page a hairline and a tonal step rather than an at-rest shadow.
- **Do** give any set that cycles colours its own first value as its static base, so it still reads as a set with animation off.
- **Do** prefer CSS for a device that labels or tracks a row; a scripted one can desynchronise from the row it names.
- **Do** write two literal keyframe sets for two directions rather than parameterising one with a custom property.
- **Do** tint shadows with ink (`rgba(34,27,29,…)`) or the accent, and keep atmospheric shadows tied to hover.
- **Do** give the scanned line in a list the display face and the size step, as the employer gets on the timeline and the service name gets in its list.
- **Do** send any block that earns the own-cap exception to the single `60rem` secondary width.
- **Do** set `font-variant-numeric: tabular-nums` on every figure, year and count.
- **Do** theme browser surfaces from the palette: `::selection`, `caret-color`, scrollbar track and thumb, a 2px accent `:focus-visible` ring at `3px` offset, and `.22em` underline offset on links.
- **Do** author icons as inline SVG in the single `<defs>` sprite at stroke-width 1.6, as a `<symbol>` with an explicit `viewBox`, and mark every consuming `<svg>` `aria-hidden="true"`.
- **Do** keep the page's own labels consistent with the counts it claims: the eleven tile categories resolve to the seven the scale band states.
- **Do** keep raster provenance recorded, never display a raster above its native size, and keep unreferenced source images out of the upload.
- **Do** keep every text colour at AA or better; the measured floor in this build is 4.98:1 on the lightest account tile.
- **Do** make any full-screen or reveal state clear itself without JavaScript, with a timer as a backstop only.

### Don't:
- **Don't** add a dark theme, a `prefers-color-scheme` branch, or a theme toggle. The page is light-locked by decision.
- **Don't** centre a narrower reading column inside a wider section; that is the misalignment the One Left Edge Rule exists to prevent.
- **Don't** drift the warm neutral toward yellow-beige, brass, peach or espresso, and don't let its green channel rise above its blue. The neutral leans rose.
- **Don't** introduce a second accent, and don't use the accent as a section background.
- **Don't** treat the eleven `--field` colours as theme colours, or add one without an account behind it.
- **Don't** fill the field set with eleven dark values of similar lightness; keep four light fields in the mix with the `.light` treatment, keep at least one of them in a double-width cell, and don't ship two fields that read as the same colour.
- **Don't** use grey, or a blanket opacity, for secondary text on a coloured field, and don't replace a derived secondary with a literal to silence an audit.
- **Don't** make anything in the page content fully rounded, and don't add a radius value beyond 2 / 5 / 6 / 10px and the one 7px circle.
- **Don't** put an at-rest atmospheric shadow on anything; the build has none.
- **Don't** put a `ch`-based cap on display type whose line count matters — the cap moves when the font does.
- **Don't** draw ruled columns behind a grid of cards. They were built here as a `repeating-linear-gradient` for the calendar and removed: they sat mostly hidden behind the entries, earned nothing, and read as decorative stripes. The day header and the spans carry the calendar on their own.
- **Don't** base a cycling set of colour cells on one shared field; with animation off the whole set collapses to a single colour.
- **Don't** do custom-property arithmetic inside a keyframe transform.
- **Don't** add another blocking entrance or hold-screen to a new surface, and don't let any reveal or overlay state persist where it could leave content at `opacity: 0`.
- **Don't** use an uppercase letterspaced label as a kicker above a heading; that type role belongs inside tiles and chips only.
- **Don't** use emoji, an icon font, or an icon library in place of the authored sprite, and don't author a sprite entry as a `<g>` — it cannot establish a viewport and the art will clip.
