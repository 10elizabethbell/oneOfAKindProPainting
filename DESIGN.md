---
name: One Of A Kind Pro Painting & Small Repairs LLC
description: A tired wall rolled over in royal navy while you watch, trimmed in gold, read on ceiling white.
colors:
  royal-navy: "#162c6e"
  navy-deep: "#10225a"
  crown-gold: "#e3b445"
  gold-hover: "#efc560"
  ceiling-white: "#f5f6fa"
  paper: "#ffffff"
  ink: "#14214d"
  ink-soft: "#45507a"
  on-navy: "#e9edf8"
  on-navy-soft: "#b9c3e2"
  focus-blue: "#2f5fe0"
  old-wall: "#d5cab1"
  rule: "rgba(22,44,110,.14)"
  line: "rgba(22,44,110,.22)"
  tint: "rgba(22,44,110,.08)"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2.6rem, 11.6vw, 5.6rem)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2rem, 9vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(1.25rem, 6vw, 1.9rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.005em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1.4
rounded:
  pill: "999px"
  panel: "14px"
  field: "12px"
  focus: "6px"
spacing:
  gutter-phone: "16px"
  gutter-desktop: "40px"
  gap-sm: "10px"
  gap-md: "22px"
  column-gap: "64px"
  section-phone: "72px"
  section-desktop: "120px"
components:
  button-primary:
    backgroundColor: "{colors.crown-gold}"
    textColor: "{colors.navy-deep}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-hover}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-submit:
    backgroundColor: "{colors.royal-navy}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    height: "56px"
    width: "100%"
  button-submit-hover:
    backgroundColor: "{colors.navy-deep}"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    height: "76px"
  service-row-arrow:
    backgroundColor: "{colors.tint}"
    textColor: "{colors.royal-navy}"
    rounded: "{rounded.pill}"
    size: "46px"
  service-row-arrow-hover:
    backgroundColor: "{colors.crown-gold}"
    textColor: "{colors.navy-deep}"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.royal-navy}"
    textColor: "{colors.paper}"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "54px"
  step-number:
    backgroundColor: "{colors.royal-navy}"
    textColor: "{colors.crown-gold}"
    rounded: "{rounded.pill}"
    size: "52px"
---

# Design System: One Of A Kind Pro Painting & Small Repairs LLC

## Overview

**Creative North Star: "The Fresh Coat"**

The whole site is a room being repainted. The first screen is an old wall (yellowed plaster, scuffs, a crack, nail holes, the clean ghost of a frame that hung for years, a white baseboard) with a roller laying royal navy over it in real time; the visitor's finger or mouse can take the roller. Below the hero the world holds together through three materials only: wet royal navy paint (the ground of the hero, the care band and the footer), gold trim (the roller handle, the crown in the mark, the primary button, the emphasis words in headlines), and ceiling white for the sections where people read and fill in the form. Where navy meets white, the boundary is a ragged roller end with spatter, and on the way out of a navy band a few drips run down once.

Density is low and the voice is loud: heavy uppercase headlines, few words, wide ruled rows instead of cards. Nothing floats; there are no cards, no shadows on the page, no photography. The paint is the decoration, and every effect has to read as the real material (stipple, tram lines from the roller ends, drips with a bead at the tip).

The world comes from the business's own flyer (royal navy, gold, white; the crown on the roofline). It refuses the painter template: stock living-room photo, icon-card service grid, testimonial carousel.

**Key Characteristics:**
- Royal navy and ceiling white alternate as full-bleed bands; gold is trim, never a ground.
- Section boundaries are painted edges (ragged roller end plus spatter), never straight lines or curves.
- Heavy (900) uppercase display type on a system stack; body at 17px.
- Pill-shaped controls, ruled list rows, no cards, no page shadows.
- One signature live element (the roller wall); everything else is still except brief state transitions and the one-time drips.

## Colors

Two-ground palette with a single trim color and a separate functional blue for form feedback.

### Primary
- **Royal Navy** (`royal-navy`): the fresh paint. Hero ground and roller paint, the care band, the footer, section edges and drips, selected chips, step numbers, the form's submit button, navy headlines on white.
- **Navy Deep** (`navy-deep`): text on gold, the submit button's hover, selection text.

### Secondary
- **Crown Gold** (`crown-gold`): trim. Primary button fill, emphasis words inside headlines on navy, the phone icon, the wordmark's subline, the roller handle, the service-row arrow on hover, global focus ring, the selected chip's dot, text selection. **Gold Hover** (`gold-hover`) is its lit state on the primary button only.

### Tertiary
- **Focus Blue** (`focus-blue`): functional only. Hover and focus outline on every form control (fields, chips, submit, copy button) and the keyboard ring around a service-row arrow. Chosen because gold is already the button fill and navy is the submit fill; the outline has to stand apart from both.

### Neutral
- **Ceiling White** (`ceiling-white`): the reading ground (body background, services, estimate).
- **Paper** (`paper`): field and chip fill, button text on navy, headlines on navy.
- **Ink** (`ink`) / **Ink Soft** (`ink-soft`): text on white; soft for supporting lines, optional markers and step descriptions.
- **On Navy** (`on-navy`) / **On Navy Soft** (`on-navy-soft`): body text on navy and the outline button border; soft for fine print.
- **Rule** (`rule`): 2px dividers between service rows. **Line** (`line`): 2px borders on fields and chips. **Tint** (`tint`): the resting fill of arrow circles. All three are royal navy at low alpha, so dividers stay in the paint family.
- **Old Wall** (`old-wall`): the unpainted plaster in the hero canvas only. It is the "before"; it never appears as a UI surface.
- **Error Red** (`error-red`): field error text and the invalid field border.

### Named Rules
**The Trim Rule.** Gold is trim: buttons, emphasis words, icons, handles, rings. It never fills a section or a card.

**The Two Hover Colors Rule.** Gold answers hover on navy grounds and on the service-row arrow; Focus Blue answers hover and focus inside the form. Never cross them (no gold outlines on form fields, no blue fills).

## Typography

**Display Font:** system UI stack (-apple-system, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** One family at two extremes: weight 900 uppercase with tight tracking for anything that names something, regular 17px for reading. The contrast is weight and case, not typeface. The system stack is a house commitment: Ellie's rule for every pitch site is the system font stack (fast on cellular, nothing to load). Keep it unless she asks otherwise.

### Hierarchy
- **Display** (900, clamp(2.6rem, 11.6vw, 5.6rem), 0.94, uppercase): the hero headline only. The emphasis phrase goes gold.
- **Headline** (900, clamp(2rem, 9vw, 3.6rem), 1, uppercase): section headings; the footer close runs larger (clamp(2.2rem, 10vw, 4.4rem)). On navy, the second phrase goes gold.
- **Title** (900, clamp(1.25rem, 6vw, 1.9rem), 1, uppercase): service row labels. Step headings use the same voice at 1.15rem.
- **Body** (400, 17px, 1.55): all reading text. Lead paragraphs on navy run 1.18rem, max 58ch; the hero promise is 600 weight, max 30ch, balanced.
- **Label** (800, 1rem): form labels and legends; "(optional)" markers drop to 500 in Ink Soft. Buttons are 800 at 1.02rem with +0.02em tracking.

### Named Rules
**The Weight-Not-Face Rule.** Hierarchy comes from 900 uppercase against 400 sentence case. Don't add a second family or mid weights for headings.

**The Gold Phrase Rule.** A headline may turn its final phrase gold (on navy) as the one emphasis. One gold phrase per heading.

## Layout

Phone first; the real viewing context is Facebook's in-app browser. A single column with a 16px gutter (`gutter-phone`) that widens to 40px (`gutter-desktop`) at 900px, inside a 1180px max-width container (the header row runs to 1440px).

- **Hero:** full-height navy band (min(100svh, 900px) on phones, clamp(660px, 100svh, 920px) on desktop). On phones the copy sits on top and the old wall fills the space below it down to the baseboard; on desktop the copy holds the left ~46% and the wall takes the right. Header: mark and name left, the tap-to-call number top right.
- **Sections:** vertical rhythm of 72-96px on phones and 120-150px on desktop. At 900px the services and estimate sections split 5fr / 7fr (heading left, rows or form right) and the care band 6fr / 5fr, all with a 64px column gap.
- **Inner rhythm:** 22px between form fields and steps, 10-12px between chips and buttons. The form caps at 640px.
- **Breakpoints:** 380px (tighten the header so the number fits), 600px (hero buttons go side by side), 900px (desktop gutter and two-column sections).

## Elevation & Depth

Flat. The page has no box shadows, cards or layered surfaces; depth comes from paint. The navy bands sit "on top" of the white ones because their ragged edges overlap the white by a few pixels and their drips run down over it. The only cast shadows live inside the hero canvas: the roller's soft shadow (which grows as it lifts off the wall), a faint line where the baseboard meets the wall, and the outlet plate.

### Named Rules
**The Paint-Is-The-Depth Rule.** Don't add shadows or raised cards to the page. If a surface needs to read as in front, paint it navy and give it a roller edge.

## Shapes

Two families. Controls are fully round: pill buttons and chips (`pill`), circular arrows and step numbers. Containers that hold typing are gently curved: fields at 12px (`field`), the message fallback panel at 14px (`panel`). Borders are 2px everywhere they exist (fields, chips, outline buttons, row rules).

The signature silhouette is the **roller edge**: a 26px-tall band where navy ends in a slightly wavy line that steps a few pixels at every roller width (92px on phones, 150px on desktop), with a scatter of small spatter dots. Edges sit at the top of a navy band (`up`) and at its bottom (`down`). A bottom edge can carry drips: rounded-tip runs 4-7px wide and 16-62px long, with a bead at the end.

## Components

### Buttons
Tactile and plain: big pills, heavy labels, no icons except where they name the destination.
- **Shape:** full pill (`pill`), 56px tall, 26px side padding, 2px border.
- **Primary (gold):** Crown Gold fill, Navy Deep text. The main action on navy grounds ("Get my free estimate").
- **Outline:** transparent with an On Navy border and Paper text; on hover a 10% white wash. Secondary actions on navy (the hero's text-a-photo button, the Facebook link in the care band).
- **Submit:** Royal Navy fill, Paper text, full width; hover deepens to Navy Deep and adds the Focus Blue outline (3px, 3px offset).
- **Copy (small):** 44px outlined navy pill inside the fallback panel; Focus Blue outline on hover and focus.
- **Press:** every button nudges down 1px on `:active`. Transitions run 0.15-0.2s on color and border only.

### Service rows
The signature list pattern: big uppercase labels between 2px rules, each ending in a circular arrow.
- **Rest:** Ink label at title size, row 76px tall (92px desktop); arrow is a 46px circle in Tint with a navy arrow.
- **Hover / Focus:** only the arrow changes. It fills Crown Gold with a Navy Deep arrow. The row itself never gets an outline, background or shadow. Keyboard focus puts the Focus Blue ring around the arrow circle.
- **Behavior:** a row links to the estimate form and ticks the matching service chip.

### Chips
- **Style:** 48px pill, Paper fill, 2px Line border, 700 weight, with a 16px open circle before the label.
- **Selected:** Royal Navy fill and border, Paper text, the circle fills gold.
- **Hover / Focus:** 3px Focus Blue outline, 1px offset.
- Chips exist only as checkbox inputs inside the form.

### Inputs / Fields
- **Style:** Paper fill, 2px Line border, 12px radius, 54px min height (textarea 120px), 17px text so phones don't zoom.
- **Hover / Focus:** border turns Focus Blue and a 3px Focus Blue outline appears at 1px offset.
- **Error:** border turns Error Red and a one-line message appears below in Error Red, 600 weight.

### Numbered steps
Three static steps beside the estimate heading: a 52px Royal Navy circle with a gold 900-weight numeral, a step title in title voice, and an Ink Soft line under it.

### Navigation
There is no menu. The header holds the crown-house mark with the italic 900 wordmark ("One Of A Kind") and its gold uppercase subline, and on the right the phone number as a tap-to-call link with a gold phone icon (hover turns the number gold). A skip link (gold pill) jumps to the estimate.

### The Roller Wall (signature)
A full-bleed canvas in the hero. It draws a procedurally aged wall (stained plaster, the clean ghost of a frame and its nail, nail holes, spackle patches, scuffs low down, a crack, a water ring on wide screens, plaster grain), the strip already painted behind the headline, a white baseboard and (on wide walls) an outlet. A roller with a gold handle lays navy with a streaky nap and heavier tram lines at its ends. It carries a paint load: the cover fades toward dry as it travels, strokes lighten, and a loaded roller moving down can start a drip.
- **Autopilot** rolls a painter's pattern (straight up-and-down strokes, lifting to step over by most of a roller width), pausing to reload when dry. At 90% coverage it holds, then cross-fades to a fresh old wall.
- **Control:** a mouse paints on hover; a finger paints while down, in every direction (vertical drags never scroll the page inside the wall zone). The roller rides a little above a fingertip so it stays visible. A visitor's roller never runs fully dry. Autopilot resumes 2.6s after the last touch. A small uppercase hint ("Drag to roll on a fresh coat") sits on the baseboard and fades after the first touch.
- **Text stays clear:** the wall zone sits below the copy on phones and right of it on desktop; nothing in the canvas runs through text.
- **Tunables** live at the top of the first script block (roller length per breakpoint, speed, stamp size and alpha, dry-out rate, drip chance, idle delay, reset coverage and timing, paint and dry colors).

### Motion
- **One loop:** a single requestAnimationFrame loop drives the hero. It stops when the hero leaves the viewport or the tab is hidden, and restarts on return.
- **Drips run once:** section-edge drips grow over about 2.8s (randomized 0.7-1.3x, up to 0.8s delay, ease-out) the first time an edge scrolls into view, then stay put.
- **Reduced motion:** the hero renders one still frame of a half-rolled wall with no autopilot; touch still paints while the finger is down. Drips appear at full length with no transition, and smooth scrolling is off.

## Do's and Don'ts

### Do:
- **Do** alternate Royal Navy and Ceiling White bands, and join them with a roller edge (drips only on a band's bottom edge).
- **Do** keep gold as trim: the primary button, one gold phrase per heading on navy, icons, focus rings.
- **Do** outline every form control in Focus Blue (3px) on hover and focus; keep gold for the service-row arrow and navy grounds.
- **Do** keep controls at 44px minimum (buttons 56px, chips 48px, fields 54px) and form text at 17px.
- **Do** put the phone number in the header's top-right corner as a `tel:` link, and nowhere else on the first screen. It may repeat beside the form and in the footer.
- **Do** keep the business email in the footer only.
- **Do** keep the hero to the headline, the promise line and at most two buttons: gold for the estimate, outlined for the secondary action. No Call button under the headline.
- **Do** make every effect read as the real material, and keep text in a clear zone free of canvas detail.
- **Do** pause all motion off-screen and give reduced-motion visitors a still frame.

### Don't:
- **Don't** add a sticky bar fixed to the bottom of the phone screen.
- **Don't** give a service row an outline, background tint or shadow on hover or focus; only its arrow changes.
- **Don't** use pill or chip shapes for anything that isn't interactive (service areas, tags, labels). Pills are buttons and form choices only.
- **Don't** add cards, box shadows or straight-line section dividers; depth is paint.
- **Don't** fill a section with gold or use Old Wall as a UI surface.
- **Don't** publish facts the business hasn't given (service area, hours, years, licensing, insurance, prices, reviews, owner name), and add no demo or sample wording.
- **Don't** add email buttons, email links outside the footer, or a send-by-email option on the form.
- **Don't** run a second animation loop or add looping ambient motion outside the hero.
