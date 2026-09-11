# Body Grace Fitness & Yoga — Homepage Redesign Demo

A warm, community-first homepage redesign concept for **Body Grace Fitness & Yoga** in Vienna, VA.

- Single static `index.html` — no build step
- Real Body Grace photography (in `/images`)
- Story-led layout: Welcome → What We Do → Beginner-friendly → Paula's story → All Are Welcome → Longevity → Prenatal → Instructors → New Studio → Community → Pricing → Schedule → Visit
- Responsive, accessible, LocalBusiness structured data, Open Graph tags

> Demo redesign concept — not the official Body Grace website. Schedule and pricing rows shown are illustrative samples; link out to the live calendar and fee pages for current details.

## Booking (Acuity)
Body Grace already books through **Acuity Scheduling**. The `#book` section is pre-wired for the embed — see the comment block above `<section class="book">` in `index.html`. To go live: drop the studio's Acuity `owner` ID into the iframe and remove the placeholder. Every "Book a Class" CTA already points to `#book`.

## Brand
- Dusty slate-blue (from the real logo) + warm cream neutrals + soft terracotta accent
- Script wordmark (Kaushan Script) echoes the hand-brushed "Body Grace" logo
- Photo carousel ("Life at Body Grace") mirrors her existing slideshow

## Deploy on Vercel
This is a static site. Import the repo in Vercel and deploy with default settings (Framework Preset: **Other**, no build command, output = repo root).

Business: 133 Maple Avenue E, Suite 300, Vienna, VA 22180 · 703-298-3903
