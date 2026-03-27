# Claude Code Prompt — Jessilyn Stewart Peaslee Author Website
## Final Version — Ready to Paste Into Claude Code

---

## YOUR MISSION

Build a complete, production-ready static author website for **Jessilyn Stewart Peaslee**.
Output a single `index.html` with all CSS and JS inline. No build tools. No frameworks.
Deployable to Netlify by pushing to Git.

This site must be genuinely beautiful — something a fairy tale author would cry happy tears over.
Her audience is teen girls and adult women who love clean, heartfelt romance.
She is a busy mom of 5 boys with zero time to maintain anything.
Build it zero-maintenance, set-it-and-forget-it.

---

## ASSETS IN THIS REPO (use relative paths)

- `brighthaven.png` — Bright Haven Books publisher logo. Use in footer.
- `website cover (4).png` — Hero/banner image for the site. Use as hero section background or decorative element.
- The author headshot is NOT yet in this repo. Add an `<!-- AUTHOR PHOTO placeholder -->` comment in the About section for a file called `author-photo.jpg` that will be added later.


---

## SEO & META (include in `<head>`)

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jessilyn Stewart Peaslee — Fairy Tale Retellings</title>
<meta name="description" content="Award-winning fairy tale retellings by Jessilyn Stewart Peaslee. Clean YA romance inspired by Cinderella, Beauty and the Beast, and more. Silver & Gold Quill Award winner.">
<meta property="og:title" content="Jessilyn Stewart Peaslee — Fairy Tales Brought to Life">
<meta property="og:description" content="Once upon a time — somewhere between laundry piles and bedtime stories — Jessilyn fell in love with fairy tales.">
<meta property="og:image" content="website cover (4).png">
<meta property="og:type" content="website">
<link rel="icon" type="image/png" href="brighthaven.png">
```

---

## AUTHOR PROFILE

**Name:** Jessilyn Stewart Peaslee
**Publisher:** Bright Haven Books (brighthavenbooks.com) — this is her PUBLISHER, not a book title
**Location:** Utah (raised in Southern California)
**Education:** BYU, BA in English, 2004
**Family:** Science-teaching husband, five hilarious boys
**Influences:** Shakespeare, Jane Austen, the Brontë sisters

**Core brand voice:** Warm, witty, self-deprecating, wholesome. She ends her bio with:
*"As you read this, she is probably folding laundry… or should be."*
She describes herself as *"a boy mom who writes delightfully girly books."*

**Awards:**
- 🥈 Silver Quill Award — League of Utah Writers, YA Fiction — *Ella*
- 🥇 Gold Quill Award — League of Utah Writers, YA Fiction — *Finding Beauty in the Beast*

**CLEAN READ:** All books are explicitly clean/PG — no swearing, no inappropriate content.
This is a KEY differentiator. Display a "Clean Read ✓" badge prominently on book cards.


---

## THE BOOKS

### Reading Universe
**Ella Universe** (read in this order): Ella → Ella's Will → Finding Beauty in the Beast → Always Ella
**Standalone:** Awake at Widmore Manor

---

### ELLA — 🥈 Silver Quill Award
**Fairy tale:** Cinderella | **Card color:** #1B3A6B (deep sapphire) | **Motif:** glass slipper silhouette
Reserved yet resilient, Ella Blakeley lives with her cruel stepmother and stepsisters, without hope
of escape — until Prince Kenton announces a ball that changes everything. Even without mice, magic,
or fairy godmothers, Ella might discover a life better than she ever dreamed.
- Amazon Print: https://www.amazon.com/Ella-Jessilyn-Stewart-Peaslee/dp/1462117457
- Amazon Kindle: https://www.amazon.com/Ella-Jessilyn-Stewart-Peaslee-ebook/dp/B0172NFJ2Q
- Bright Haven: https://brighthavenbooks.com/collections/all?sort_by=relevance&q=Jessilyn

### ELLA'S WILL
**Fairy tale:** Cinderella — Will's POV | **Card color:** #1A4D2E (forest green) | **Motif:** horseshoe / stable
Will Hawkins is just a stable boy. How can he hope to woo Ella — his once-wealthy childhood friend —
when his competition is the prince? Witty, romantic, and impossible to put down. Told from Will's
perspective, this companion novel is the other half of the same love story.
- Amazon Print: https://www.amazon.com/Ellas-Will-Jessilyn-Stewart-Peaslee/dp/1462119085
- Amazon Kindle: https://www.amazon.com/Ellas-Will-Jessilyn-Stewart-Peaslee-ebook/dp/B01KPDTKES

### FINDING BEAUTY IN THE BEAST — 🥇 Gold Quill Award
**Fairy tale:** Beauty & the Beast, but the PRINCESS is the Beast | **Card color:** #6B1A2E (burgundy) | **Motif:** rose
Princess Rose's fiery temper has kept every suitor away — until she forces every eligible man to
present a gift under pain of death. When Corbin offers a simple rose, hoping to be passed over,
love works in mysterious ways. A clever, subversive twist on a beloved classic.
- Amazon Print: https://www.amazon.com/Finding-Beauty-Beast-Jessilyn-Peaslee/dp/1462129404
- Amazon Kindle: https://www.amazon.com/Finding-Beauty-Jessilyn-Stewart-Peaslee-ebook/dp/B078BGJW67


### AWAKE AT WIDMORE MANOR
**Fairy tale:** Princess and the Pea — Regency style | **Card color:** #3D4F6B (slate blue) | **Motif:** rainstorm / manor window
A violent storm. A sleepless night. A test. Emma Widmore has longed to return to her childhood home
since her father's death. Granted refuge on a stormy night by her childhood friend James Atwood —
heir of Widmore Manor — she finds only suspicion. After hearing rumors of a test other women have
failed, Emma must reconcile her past and discover what being home truly means.
Part of the "Once Upon a Regency" series.
- Amazon Kindle: https://www.amazon.com/Awake-Widmore-Manor-Once-Regency-ebook/dp/B07SGC3KZ8
- Amazon Print: https://www.amazon.com/Awake-Widmore-Manor-Once-Regency/dp/1074540832

### ALWAYS ELLA: THE STEPMOTHER'S STORY
**Fairy tale:** Cinderella — the wicked stepmother's origin | **Card color:** #7A4E2D (warm chestnut) | **Motif:** mirror / crown
Nobody is born wicked. The beautiful, headstrong Victoria Noble has lofty dreams — but none involve
becoming a villain. This poignant prequel traces her journey through love, loss, and choices that
haunt her. Told from the perspective of the "wicked stepmother," it's a powerful reminder that
redemption is never walked alone.
- Amazon: https://www.amazon.com/Always-Ella-Jessilyn-Stewart-Peaslee/dp/B0C91DKW43

---

## SITE SECTIONS (in order)

### 1. ANNOUNCEMENT BAR (top of page, thin)
Gold background, small text: "✨ All books now available at Bright Haven Books →"
Link: https://brighthavenbooks.com/collections/all?sort_by=relevance&q=Jessilyn
Dismissible with an × button (localStorage to remember dismissal).

### 2. NAVIGATION (sticky)
- Left: "Jessilyn Stewart Peaslee" — Playfair Display, elegant
- Right links: Books | About | Quiz | Newsletter | Speaking | Contact
- Transparent on hero, transitions to frosted glass / solid cream on scroll
- Mobile: hamburger → full-screen overlay menu with centered links


### 3. HERO SECTION
Full-width. Use `website cover (4).png` as the hero background image (cover with a semi-transparent
deep forest green overlay so text is readable).

- Small eyebrow text (Cormorant Garant, gold): "Award-Winning Fairy Tale Retellings"
- Main headline (Playfair Display, 72px desktop / 42px mobile, cream white):
  **"Fairy Tales Brought to Life"**
- Subheadline (Lora italic, 20px, cream/80% opacity):
  *"Once upon a time — somewhere between laundry piles and bedtime stories —
  Jessilyn fell in love with fairy tales and the belief that they still matter."*
- Two CTAs side by side:
  [Discover Her Books] — gold filled button, scrolls to #books
  [Meet Jessilyn] — outlined/ghost button, scrolls to #about
- 6 floating CSS sparkle particles (✦ or ★ shaped, varying sizes, slow drift animation)
- Decorative botanical SVG (climbing vine with small roses) along one edge

### 4. BOOKS SECTION — id="books" ("Once Upon a Shelf")

Section header: "Once Upon a Shelf" (Playfair Display)
Subhead: "Clean romance for the fairy tale lover in all of us. ✓ Always PG. Always heartfelt."

**Book grid:** 3 columns desktop, 2 tablet, 1 mobile. Each card:

CARD STRUCTURE:
- Top half: Styled CSS "book cover" tile with:
  - Jewel-tone background (color listed per book above)
  - Subtle SVG pattern overlay matching the book's fairy tale motif (listed above)
    e.g., for Ella: faint glass slipper silhouettes; for Finding Beauty: faint rose outlines
  - Book title in Playfair Display (white, large)
  - Fairy tale source in small italic Cormorant (e.g., "A Cinderella Retelling")
  - Award badge (if applicable) — gold ribbon icon, top-right corner
  - "Clean Read ✓" badge — small pill, sage green, bottom-left corner
- Bottom half (cream background):
  - 2-sentence description
  - Two buttons: [Shop at Bright Haven] (primary gold) + [Amazon ↗] (small text link)
  - Hover effect: card lifts (translateY -8px) + gold glow shadow

Reading order note (below grid, centered, italic):
"New to Jessilyn's world? Begin with *Ella*, then follow Will's story in *Ella's Will*.
Or jump in anywhere — each book stands beautifully on its own."

[Browse All Books at Bright Haven →] — text link button below grid

### 5. READER LOVE SECTION ("What Readers Are Saying")

Section header: "What Readers Are Saying" (Playfair Display)
Display 4 real reader quotes in elegant quote cards (parchment background, gold left border, Lora italic):

Quote 1 (about Ella):
"I have always favored Cinderella tales and retellings and Jessilyn Stewart Peaslee has written a
splendid and delightful twist on this beautiful story." — Amazon Verified Review ⭐⭐⭐⭐⭐

Quote 2 (about Ella's Will):
"This is how the story should have always been. There are insights into human nature explained from
different points of view, in enlightening ways." — Amazon Verified Review ⭐⭐⭐⭐⭐

Quote 3 (about Finding Beauty in the Beast):
"Such a fresh take. Having 'Beauty' as the 'Beast' added so many layers and delivered such a
meaningful and poignant message. Jessilyn truly has a way with words." — Amazon Verified Review ⭐⭐⭐⭐⭐

Quote 4 (about Awake at Widmore Manor):
"Jessilyn Stewart Peaslee has proven four times that she can do a perfect fairy tale retelling with
new depth — making each story superior to the original." — Amazon Verified Review ⭐⭐⭐⭐⭐


### 6. "WHICH FAIRY TALE IS FOR YOU?" QUIZ — id="quiz"

This is a FUN, interactive section — her audience will love it.
Build a simple 3-question quiz in pure JS that recommends one of her books.

Section header: "Which Fairy Tale is For You?" (Playfair Display)
Subhead: "Answer three questions and we'll find your perfect Jessilyn story."

QUESTION 1: "What kind of hero speaks to your soul?"
  A) The quietly resilient one who endures with grace → points to Ella
  B) The loyal best friend who refuses to give up → points to Ella's Will
  C) The fiery one who has to learn to let love in → points to Finding Beauty
  D) The one who longs to return to where she belongs → points to Awake at Widmore Manor

QUESTION 2: "Your ideal fairy tale setting?"
  A) A kingdom ball where everything changes in one night → Ella
  B) A royal stable yard, working-class charm → Ella's Will
  C) A forbidding castle where a grumpy princess rules → Finding Beauty
  D) A candlelit Regency manor on a stormy night → Awake at Widmore Manor

QUESTION 3: "What fairy tale theme moves you most?"
  A) Finding your worth despite how others treat you → Ella
  B) Proving love through loyalty, not grand gestures → Ella's Will
  C) Discovering the beauty beneath a difficult exterior → Finding Beauty
  D) Finding your way back to where you truly belong → Awake at Widmore Manor

RESULT DISPLAY: After Q3, show an animated reveal card with:
- The recommended book title (large, Playfair Display)
- The book's jewel-tone color as background
- A 2-sentence description
- "Read It Now" → Amazon link
- Small text: "Or browse all of Jessilyn's books ↓"
- "Retake Quiz" link

Style: Clean card steps, gold radio-button-style selectors, smooth CSS slide transitions between questions.
Progress bar at top showing question 1/3, 2/3, 3/3.

### 7. ABOUT SECTION — id="about" ("The Author Behind the Magic")

Two-column layout (desktop): photo left, bio right. Stack on mobile.

PHOTO (left column):
```html
<!-- AUTHOR PHOTO: Add file author-photo.jpg to this repo, then replace this placeholder -->
<div class="author-photo-placeholder">
  <span>Photo Coming Soon</span>
</div>
```
Style the placeholder as an elegant oval frame with gold border and cream background.
When the real photo is added: style `author-photo.jpg` as an oval portrait with decorative gold border frame.

BIO TEXT (right column, Lora body font):
"Once upon a time — somewhere between laundry piles and bedtime stories — Jessilyn Stewart Peaslee
fell in love with fairy tales and the belief that they still matter. She reimagines classic stories
through the lens of real life, where courage and love are the truest magic of all.

Her debut novel, *Ella*, received the Silver Quill Award from the League of Utah Writers, and her
third novel, *Finding Beauty in the Beast*, earned the Gold Quill Award, both in YA Fiction.

A passionate advocate for young writers, Jessilyn loves encouraging youth to pursue their creative
dreams and has visited schools throughout Utah and surrounding states.

A graduate of Brigham Young University with a BA in English, she grew up in Southern California in
a family of music lovers, movie quoters, and sports fans — and now lives in Utah with her
science-teaching husband and their five hilarious, incredible boys.

As you read this, she is probably folding laundry… or should be."

FUN FACTS SIDEBAR (small card below or beside bio, parchment background, whimsical):
✦ Raised in sunny Southern California
✦ BYU English grad, class of 2004
✦ Loves Shakespeare, Jane Austen & the Brontës
✦ Utah resident, Rocky Mountain backdrop
✦ Mom of FIVE boys (yes, five)
✦ Writes delightfully girly books anyway
✦ Published by Bright Haven Books

SOCIAL ROW (icons + labels):
- Facebook: https://www.facebook.com/authorjesspeaslee
- Instagram: https://www.instagram.com/authorjesspeaslee/
- Amazon Author: https://www.amazon.com/stores/Jessilyn-Stewart-Peaslee/author/B01DAN87LM
- Goodreads: https://www.goodreads.com/author/show/14214145.Jessilyn_Stewart_Peaslee
- Blog: http://www.jotsbyjess.com/


### 8. NEWSLETTER SECTION — id="newsletter" ("Stay in the Story")

Warm parchment-toned full-width section.

Headline: "Stay in the Story" (Playfair Display, large)
Subhead: "Book news, a little inspiration, and the occasional dash of humor — delivered to your inbox.
No spam. Just stories. Unsubscribe anytime."

INCENTIVE HOOK (small card above form, gold border):
"✨ Join the list and be the first to know about new releases, giveaways, and exclusive reader content."

MAILCHIMP EMBEDDED FORM:
Form method POST, action (opens in new tab, Mailchimp handles success page):
https://jessilynstewartpeaslee.us12.list-manage.com/subscribe/post?u=f097221b9cf193c455b234370&id=b4a131a922

Fields (all styled to match the site aesthetic):
- Email Address * (required, type="email", name="EMAIL", placeholder="your@email.com")
- First Name (name="FNAME", placeholder="First name")
- Last Name (name="LNAME", placeholder="Last name")
- Birthday — two small selects side by side (optional, charming):
  name="MMERGE4[month]" (1–12 with month names) and name="MMERGE4[day]" (1–31)
- Hidden: <input type="hidden" name="u" value="f097221b9cf193c455b234370">
- Hidden: <input type="hidden" name="id" value="b4a131a922">
- Anti-bot honeypot (required by Mailchimp, must be visually hidden):
  <div style="position:absolute;left:-5000px" aria-hidden="true">
    <input type="text" name="b_f097221b9cf193c455b234370_b4a131a922" tabindex="-1" value="">
  </div>
- Submit button: "Subscribe ✨" — gold filled, full-width on mobile

### 9. SPEAKING SECTION ("Bringing Stories to Life")

Section header: "Bringing Stories to Life"

Body copy:
"Jessilyn is passionate about encouraging young writers to find their voice and pursue their creative
dreams. She has visited schools throughout Utah and surrounding states — bringing fairy tales to life
and inspiring students to believe in the magic of their own stories."

4 offering tiles (icon + title + 1-line description):
📖 Author Talks — The story behind the stories, and why fairy tales still matter
✍️ Writing Workshops — Hands-on encouragement for young and aspiring writers
📚 Book Signings — Meet Jessilyn and get a personally signed copy
🎤 Library & Event Appearances — Bringing the magic of reading to your community

CTA: [Book a Visit →] — scrolls to #contact

### 10. CONTACT SECTION — id="contact" ("Send a Note")

Section header: "Send a Note"
Subhead: "Jessilyn loves hearing from readers! She'll do her best to respond —
though with five boys running around, give her a moment."

NETLIFY FORM (works automatically when deployed to Netlify):
<form name="contact" method="POST" data-netlify="true" data-netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="contact">
  <input type="hidden" name="bot-field"> (hidden honeypot)

Fields:
- Name (text, required)
- Email (email, required)
- Subject (select, required): "I loved your books! 💕" | "School Visit Request" | "Media / Interview" | "Other"
- Message (textarea, 5 rows, required)
- Submit: "Send Message →" — gold button

Below form (small italic text):
"For school visit inquiries, please include your school name, location, and preferred dates."

### 11. FOOTER

Left: Author name + tagline: "Reimagining fairy tales, one story at a time."
Center: Nav links (Books | About | Quiz | Newsletter | Speaking | Contact)
Right: Publisher credit:
  <a href="https://brighthavenbooks.com"><img src="brighthaven.png" alt="Bright Haven Books" style="height:32px;width:auto;filter:brightness(0.8)"></a>
  <small>Published by Bright Haven Books</small>

Bottom strip: Social icons row (Facebook, Instagram, Amazon, Goodreads, Blog)
Copyright: "© 2025 Jessilyn Stewart Peaslee · All rights reserved"
Small: "Site crafted with ✨ and a fairy godmother's blessing"


---

## DESIGN SYSTEM

### Aesthetic
Enchanted Storybook — refined, warm, literary. Think: the inside of a beautifully bound antique book
with pressed botanical illustrations. Jane Austen meets fairy tale. NOT childish. NOT pink glitter.
Sophisticated enough for adult women, magical enough to delight a teen girl.

### CSS Variables
```css
:root {
  --cream: #FAF6F0;           /* page background */
  --parchment: #F0E8D8;       /* cards, alternating sections */
  --parchment-dark: #E2D5BE;  /* borders, dividers */
  --forest: #2D5016;          /* primary dark green */
  --forest-mid: #3D6B20;      /* hover states */
  --sage: #7A9E5C;            /* secondary green, badges */
  --gold: #B8860B;            /* primary accent */
  --gold-light: #D4AF37;      /* hover gold */
  --gold-pale: #F5E8B0;       /* subtle gold tint */
  --ink: #1C1C1C;             /* body text */
  --charcoal: #3D3D3D;        /* secondary text */
  --warm-grey: #8B8070;       /* captions, metadata */
  --white: #FFFFFF;
  --shadow-soft: 0 4px 24px rgba(44,40,30,0.10);
  --shadow-hover: 0 12px 40px rgba(184,134,11,0.22);
}
```

### Google Fonts
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400;1,600&family=Lora:ital,wght@0,400;0,500;1,400;1,500&family=Cormorant+Garant:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap" rel="stylesheet">
```
- **Headings:** Playfair Display — literary, elegant serif
- **Body:** Lora — warm, highly readable serif
- **Accents/nav/eyebrows:** Cormorant Garant — refined, airy

### Visual Details
- Botanical SVG vine dividers between every major section
  (simple inline SVG: a horizontal line with small leaves/roses along it)
- Gold horizontal rule lines as section accents
- Sections alternate: cream → parchment → cream
- Book card tiles: jewel-tone background + subtle repeating SVG motif overlay (10% opacity)
  Each motif matches its fairy tale (slipper, horseshoe, rose, raindrop/manor, mirror)
- Soft drop shadows only — no hard/brutal shadows
- 10px border radius on cards
- Generous whitespace — this is NOT a busy site

### Animation
- Page load: staggered fade-in + translateY(20px) on hero elements
- Scroll reveal: IntersectionObserver on all sections (fade-in + translateY, threshold 0.15)
  Stagger book cards by 100ms each
- Nav: background transition on scroll (transparent → frosted glass over 200ms)
- Book cards: hover translateY(-8px) + box-shadow var(--shadow-hover)
- CTA buttons: CSS ::after shimmer sweep on hover (gold gradient moving left-to-right)
- Hero sparkles: CSS keyframe animation, 6 particles floating slowly (different speeds/directions)
- Quiz: CSS slide transition between questions (translateX)
- Testimonial cards: subtle entrance animation on scroll

---

## TECHNICAL REQUIREMENTS

- **Single file:** `index.html` — ALL CSS and JS inline between style/script tags
- **No frameworks, no build tools, no npm** — pure HTML/CSS/JS only
- **Netlify Forms:** `data-netlify="true"` and `data-netlify-honeypot="bot-field"` on contact form
- **Mobile-first responsive:**
  - Hamburger nav on mobile with full-screen overlay
  - Book grid: 3col → 2col → 1col
  - About section: side-by-side → stacked
  - Quiz cards: full-width on mobile
- **Accessible:** semantic HTML5, proper heading hierarchy (h1→h2→h3), alt text on all images,
  aria-label on icon-only buttons, focus styles on interactive elements
- **Performance:** lazy-load images (`loading="lazy"`), minimal JS, no external JS dependencies
- **No broken links:** all URLs listed above are verified

---

## AFTER BUILDING

The `index.html` plus the two image files (`brighthaven.png`, `website cover (4).png`) should all
be in the repo root. Commit and push to GitHub — Netlify auto-deploys.

To add the author headshot later: drop `author-photo.jpg` into the repo root, then update the
placeholder in the About section.

**DNS (to connect jessilynstewartpeaslee.com via GoDaddy):**
- CNAME record: `www` → `[netlify-subdomain].netlify.app`
- A record: `@` → `75.2.60.5`
