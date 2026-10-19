# One Of A Kind Pro Painting & Small Repairs LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/oneOfAKindProPainting/ · **Repo:** https://github.com/10elizabethbell/oneOfAKindProPainting · **Built:** 2026-10-19 from Muse brief (run 2026-10-19, flyer post 2026-10-18 in "New Jersey Small Business Network")

## What's built
- **One page, phone first.** It runs top to bottom like this:
  - Header: a crown-and-house mark with the name on the left, and the tap-to-call number top right.
  - Hero: "A fresh start looks good here." (the flyer's own line), the promise line, a gold **Get my free estimate** button and an outlined **Text us a photo** button.
  - Services: "Paint. Repair. Improve. Repeat." with three rows, Interior painting, Exterior painting and Small repairs. Each row jumps to the form with that service already ticked.
  - Care band: "Details make the difference." plus a prominent Facebook link.
  - The free estimate: three steps, then the form.
  - Footer close: "One of a kind. Inside and out." with the name, phone, email and Facebook.
- **The world:** royal navy paint and gold trim from the flyer, with ceiling-white reading sections and heavy uppercase system type.
- **Signature element:** the hero is a tired old wall with yellowing, scuffs, a crack, nail holes, unsanded spackle, the faded spot where a frame hung, an outlet and a baseboard.
  - A roller with a gold handle paints it in the brand navy by itself, in vertical painter's strokes.
  - The roller runs dry and reloads, and the odd drip runs.
  - A finger (in any direction, without scrolling the page) or a mouse takes over the roller.
  - When the wall is about 90% painted, it cross-fades to a fresh old wall.
- **Carried through the page:** section edges are ragged roller ends, and the drips under the care band run when they scroll into view.
- **Contact wiring:**
  - `tel:+13374586145` in the header, the form note and the footer.
  - The form composes a pre-filled text (`sms:+13374586145?&body=...`) with a copy-message fallback.
  - The email appears in the footer only.
- **Tuning knobs** sit at the top of the first `<script>` IIFE: roller size, speed, coat strength, drip chance, idle time, and the reset threshold.

## Assumptions I made
- **Email is `oneofakindpropaintingllc@gmail.com`.** I read it off the flyer image. Muse's OCR said `...lc@gmail.co`, which was wrong.
- **Facebook URL is `facebook.com/OneOfAKindProPainting`.** The flyer prints "DM FB @ OneOfAKindProPainting", but the URL could not be confirmed without a login. Check it before sending, since it's the only "see our work" link.
- **Services are the flyer's four icons condensed to three rows.** The icons are Painting, Small repairs, Interior & exterior and Fix it right. I made the rows Interior painting, Exterior painting and Small repairs, plus the flyer's line "Homes, Businesses, Rentals & More".
- **Voice is "we".** "LLC" and the flyer don't say how many people work there. Switch to "I" if it's a one-person business.
- **Care copy is my wording**, built from the flyer's "Details make the difference": "We treat your home, shop or rental like it's our own. We fix what needs fixing, cut clean lines, and don't call it done until the details are right."
- **The step copy "It costs you nothing"** comes from the flyer's "complimentary online estimate".
- **Colors** are sampled by eye from the flyer: navy #162c6e and gold #e3b445.
- **Logo:** there is no logo file. The mark is redrawn from the flyer's crown on a roofline, and the wordmark is set in system italic, not their script. The favicon and the iPhone home-screen icon use the same mark.

## Placeholders and gaps
- **Service area: not on the page.** 337 is a Louisiana area code. A third-party places listing says 103 Green St, Crowley LA, but the ad ran in a New Jersey group. The form asks "Where is the job?" instead.
- **No photos of their work.** The flyer is an AI-styled illustration, not a photo of a job. There's no proof section. The Facebook button ("Click to see more of our work") sits in the care band until real photos exist.
- **Missing:** reviews, prices, hours, years in business, licensing and insurance. The page says nothing about any of them.
- **Owner name not used.** The ad was posted from Dee Trill's personal profile, but their role isn't stated.
- **Texting not confirmed.** Texts are unknown, so every text action is paired with the call number.

## Questions for the owner
1. Is the number textable? Is facebook.com/OneOfAKindProPainting the right page?
2. Which towns or area do you serve?
3. Can we have 4–8 photos of real jobs, ideally before/after pairs? These would unlock a proof section with before/after sliders.
4. Are you one person ("I") or a crew ("we")? Do you want your name on the site?
5. Hours, years in business, and licensed/insured (only if true)?
6. Do you have a logo file? The script "One Of A Kind" on the flyer could replace the system-italic wordmark.
7. Any reviews from customers we can quote word for word?

## Ideas not built (yours to pick)
- **Runner-up world:** painter's tape peeling off to reveal a crisp cut line in navy and gold. You'd drag the tape off.
- **Paint ideas from the finish review:**
  - a wet sheen that dries to matte behind the roller;
  - darker lap marks where strokes overlap;
  - a crisp cut-in line along the baseboard.
- **Paint colors:** let the visitor pick the paint color from a swatch fan (navy, gold, white), echoing the flyer's color fan.
- **Small repairs on the wall:** a hole or crack that patches itself when the roller passes over it.
- **A tiny reward:** a gold dab when a service chip is ticked.
- **Before/after sliders** under each service once real pairs exist.
- **A `book.html` estimate page** if the owner wants a fuller intake: room count, wall vs. trim, photos.

## Not verified
- Real-device touch on iPhone and Android, inside Facebook's in-app browser. Tested: Playwright WebKit plus Chromium touch emulation.
- The real hand-off to Messages on iOS and Android (`sms:` with a pre-filled body). Only URL encoding and decoding were verified.
- Frame rate on old Android phones. The canvas is capped at 1.25x sharpness on phones to help.
- Landscape phones (844×390): the first screen shows only the header and headline; the wall sits below.
- The Facebook page URL (login wall).
