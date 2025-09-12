# Stockholm Apartment Landing Page

Hey! This is my apartment website - a place in Stockholm that I rent out and might sell to the right person.

## What's this about?

So I'm doing this Technigo JavaScript project (week 1 of 3), and instead of making another generic business site, I decided to build something real - a landing page for my actual apartment in Kungsholmen.

Started sketching ideas with paper and pen (old school, I know). First thought about doing a recipe app I'd been working on (droo.ly - did some AI prototyping a few months back), but then switched to this apartment idea since I actually need it. I rent the place out on Airbnb/Qasa when I'm not there, and hey, might sell it if the right offer comes along!

## The vibe I'm going for

Trying to capture that minimal Swedish aesthetic mixed with Apple's clean style. You know - lots of white space, clean fonts, everything breathing. Like those fancy magazines but for an apartment. Still figuring out the perfect layout but getting there!

## What I built with

- Plain HTML & CSS (keeping it simple for now)
- Lucide icons (great icon library btw)
- SF Pro font stack (that clean Apple system font look)
- CSS Grid & Flexbox for layouts
- Pixel-based sizing for precise control
- Some cool CSS animations (reviews auto-scroll, carousel moves)

## How it looks on different screens

**Small phones (iPhone SE etc)**: Everything stacks in one column, smaller titles so nothing breaks

**Tablets**: 2 columns where it makes sense, better use of that iPad screen

**Desktop**: Full magazine layout with 4 columns in places, everything spreads out nicely

**Big screens**: Even more breathing room

## What's in there

Started by gathering all the good stuff - photos of every corner, guest reviews (got some really nice ones!), local restaurant tips. The page has:

- Big hero section with availability
- Quick facts about the place (wifi speed, location, all that)
- Reviews from past guests (they rotate automatically, pretty neat)
- Full kitchen tour (I love that kitchen)
- Workspace setup (perfect for remote work)
- The patio area (summer BBQs!)
- Local recommendations (my favorite Stockholm spots)
- Bathroom (renovated 2017, still looks fresh)
- The neighborhood vibe
- Booking options (email, Airbnb, or buy it!)
- **NEW: Inquiry form** (Week 3 addition) - Contact form with validation

## Project requirements ✅

**Week 1-2 requirements:**
- Responsive from 320px to 1600px ✓
- Navigation that works on mobile & desktop ✓  
- CSS Grid used ✓
- Flexbox too ✓
- Different column layouts for different screens ✓

**Week 3 requirements (Forms & Clean Code):**
- Hero image/video header ✓
- Signup form with 3+ different input types ✓
  - Text fields (name, visit dates) ✓
  - Email field ✓  
  - Radio buttons (guest count) ✓
  - Checkboxes (interests) ✓
  - Textarea (message) ✓
  - Submit button ✓
- Form posts to `https://httpbin.org/anything` ✓
- Fully responsive form ✓
- Clean code practices applied ✓

## Week 3 Progress ✅

**Completed tasks for HTML Forms & Clean Code:**

- **Added Inquiry Form Section**: A complete contact form with 3+ input types (text, email, textarea, radio buttons, checkboxes)
- **Form Validation Ready**: Form posts to `https://httpbin.org/anything` for testing
- **Mobile Spacing Optimization**: Reduced excessive vertical gaps on mobile for better UX  
- **CSS Cleanup**: Applied DRY principles, consolidated similar styles, removed redundant code
- **Semantic HTML**: Added meaningful comments throughout for better code readability
- **Responsive Form**: Fully responsive form that looks great 320px-1600px+
- **Clean Code Practices**: Following best practices from research on modern form validation

## What's next

Still thinking about:
- A proper booking form (maybe connect to a calendar?)
- Form that actually sends emails  
- Make it even smoother with transitions
- Compress those images (they're huge right now)
- Fix some icons that don't exist in Lucide (like refrigerator)
- Maybe add a gallery viewer?

## If you want to run it

Super simple:

1. Clone/download the files
2. Open index.html in your browser
3. That's it - no build tools or npm or anything

## Notes to self

The Apple style update really made a difference - those subtle grays (#86868b for muted text) and the cleaner font weights. Also that blue (#000000) for the main button pops nicely.

Had some fun with the CSS - that review slider took forever to get right (4 seconds per review, 6 reviews total). The carousel is infinite scroll which is pretty satisfying.

## Changes Made (Week 3)

**HTML Improvements:**
- Added semantic inquiry form section after final CTA
- Used proper form elements: `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<textarea>`
- Added `autocomplete` attributes for better UX
- Used `novalidate` to handle custom validation
- Added semantic HTML comments throughout

**CSS Optimization:**  
- Applied DRY principles - consolidated similar section styles
- Reduced mobile vertical spacing
- Created unified form styling system
- Added focus states with blue accent color
- Improved mobile responsiveness (form scales to 100% width)
- Organized CSS with clear section headers

**Form Features:**
- Name and email validation (required fields)
- Guest count selection (radio buttons)  
- Interest checkboxes (short stay, extended stay, purchase)
- Message textarea with placeholder guidance
- Responsive submit button with hover effects
- Posts structured data to HTTPbin for testing

**Clean Code Practices:**
- Meaningful CSS class names (`.inquiry-form`, `.form-group`)
- Consistent naming conventions (kebab-case)  
- Removed redundant styles
- Clear section organization
- Semantic HTML structure

---

Built in Lund with lots of coffee ☕  
Updated September 2025 with Week 3 progress
