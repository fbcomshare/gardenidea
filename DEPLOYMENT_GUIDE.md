# GardenBloom — Complete Website File Index & Deployment Guide
# Version 2.0 — Final

## ✅ ALL FILES COMPLETE

### CORE PAGES (6 files)
- index.html              ← Homepage with all products + articles
- digital-guides.html     ← All 5 digital products (conversion page)
- about.html              ← About page
- contact.html            ← Contact form (uses Formspree — free)
- privacy-policy.html     ← Required for Ezoic/AdSense
- disclaimer.html         ← Affiliate + earnings disclosure

### ARTICLES (8 complete files)
- article-ribbon-roses.html      ← How to Make Ribbon Roses
- article-wedding-bouquet.html   ← DIY Wedding Bouquet
- article-seasonal-wreaths.html  ← Seasonal Wreath Ideas
- article-backyard-ideas.html    ← 50 Backyard Garden Ideas
- article-cottage-garden.html    ← Cottagecore Garden Aesthetic
- article-farmhouse-decor.html   ← Farmhouse Home Decor
- article-string-lights.html     ← Outdoor String Lights
- article-outdoor-living.html    ← Cozy Outdoor Living Space

### PENDING (add later when ready)
- article-spring-tablescape.html
- article-indoor-plants.html

---

## DIGITAL PRODUCTS — FINAL PRICING

| Product | Price | URL |
|---------|-------|-----|
| Ribbon Rose Masterclass | $37 | ezd.gumroad.com/l/vpsnr |
| Wedding Bouquet Guide | $27 | ezd.gumroad.com/l/wedding-bouquet-guide |
| Seasonal Wreath Guide | $27 | ezd.gumroad.com/l/wreath-guide |
| Cottage Garden Planner | $24 | ezd.gumroad.com/l/cottage-garden-planner |
| Farmhouse Decor Guide | $24 | ezd.gumroad.com/l/farmhouse-decor-guide |

---

## STEP 1: DEPLOY TO NETLIFY (10 minutes)

1. Go to https://netlify.com → Sign up free (use GitHub or email)
2. Click "Add new site" → "Deploy manually"
3. Drag the entire folder onto the upload area
4. Site goes live instantly at: something.netlify.app
5. Go to Site Settings → Domain → Add custom domain
   - Buy domain at Namecheap: gardenbloomblog.com (~$12/year)
   - Follow Netlify's DNS instructions to connect

---

## STEP 2: CONTACT FORM SETUP (5 minutes)

The contact form uses Formspree (free tier = 50 submissions/month):
1. Go to https://formspree.io → Sign up free
2. Create new form → copy your Form ID
3. In contact.html, replace "your-form-id" with your actual ID:
   action="https://formspree.io/f/YOUR-FORM-ID"
4. Redeploy to Netlify

---

## STEP 3: EZOIC SETUP (Day 2)

1. Go to https://ezoic.com → Sign up
2. "Add New Site" → enter your domain
3. Choose "Cloudflare Integration" (easiest)
   - Sign up for free Cloudflare account
   - Follow Ezoic's step-by-step guide
4. Submit for review (3-7 days approval)
5. Once approved, replace all ad comments with real Ezoic placeholders:

Replace: <!-- ezoic-pub-ad-placeholder-101 -->
With:    <div id="ezoic-pub-ad-placeholder-101"></div>

Ad Placement Map:
- 101 = Top leaderboard (all pages)
- 102 = In-content #1
- 103 = In-content #2
- 104 = In-content #3
- 105 = In-content #4
- 106 = Sidebar top (300x250)
- 107 = Between sections (homepage)
- 108 = Sidebar sticky (300x250)
- 109 = Bottom leaderboard

---

## STEP 4: UPDATE GUMROAD PRICES

Log into gumroad.com and update prices:
- vpsnr → $37
- wedding-bouquet-guide → $27 (create this product)
- wreath-guide → $27 (create this product)
- cottage-garden-planner → $24 (create this product)
- farmhouse-decor-guide → $24 (create this product)

---

## STEP 5: PINTEREST PINNING SCHEDULE

Post 5 pins per day minimum. Best times (EST):
- 8:00 PM, 9:00 PM, 10:00 PM, 11:00 PM

Pin each article at least 5 times with different:
- Image designs (different backgrounds/layouts)
- Title text variations
- Description variations

Priority order for pinning:
1. Ribbon Roses (→ Gumroad direct) ⭐ highest revenue
2. Wedding Bouquet (→ article + product CTA)
3. Seasonal Wreaths (→ article + product CTA)
4. Backyard Ideas (→ article, high traffic)
5. Cottagecore Garden (→ article + product CTA)
6. Farmhouse Decor (→ article + product CTA)
7. String Lights (→ article, evergreen)
8. Outdoor Living (→ article, evergreen)

---

## AI TRAFFIC FAQ STRATEGY

Each article contains FAQ questions formatted for AI search:
- "How do I..." questions → ChatGPT picks these up
- "What is the best..." questions → Gemini/Claude reference these
- "Step by step..." questions → AI tools cite these

Add these FAQ questions to Pinterest descriptions too —
they match how people type into AI tools.

---

## REVENUE PROJECTIONS

Monthly Pinterest Visitors → Estimated Revenue:

5,000/month:
  Ezoic display: ~$50-75
  Digital guides (1% conversion, avg $27): ~$135
  Total: ~$185-210/month

20,000/month:
  Ezoic display: ~$200-280
  Digital guides (1% conversion): ~$540
  Total: ~$740-820/month

50,000/month:
  Mediavine (migrate from Ezoic): ~$750-1,000
  Digital guides (1% conversion): ~$1,350
  Total: ~$2,100-2,350/month

Note: Lawn & Garden + Floral niche has PEAK RPM
in Spring (March-May) and Christmas (Nov-Dec).
Expect 2x normal RPM in these months.

---

## DOMAIN SUGGESTION

Best available options (check at Namecheap):
- gardenbloomblog.com ✓
- gardenbloomideas.com ✓
- bloomgarden.blog ✓

---

## QUICK CHECKLIST BEFORE GOING LIVE

- [ ] All HTML files uploaded to Netlify
- [ ] Contact form Formspree ID updated
- [ ] Privacy Policy email address updated (search "privacy@gardenbloomblog.com")
- [ ] Custom domain connected
- [ ] Ezoic application submitted
- [ ] Pinterest profile links to website in bio
- [ ] First 5 pins scheduled/posted
- [ ] Gumroad products created with correct prices
