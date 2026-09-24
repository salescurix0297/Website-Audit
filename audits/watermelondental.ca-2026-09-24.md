# SEO Audit Report: watermelondental.ca
**Date:** 2026-09-24
**Audited by:** Claude SEO Audit
**Business:** Watermelon Dental, a family and kids-focused general dental practice in Bolton (Caledon), Ontario, run by Dr. Sanjukta "Sanj" Mohanta. It opened around June 2026.
**Business goal (inferred):** Local SEO. Get new-patient bookings from Bolton, Caledon and Caledon East.

---

> ### ⚠️ Scope and limitations. Please read first
> This audit was done **from outside the site**. The audit environment's network policy **blocked direct access to `watermelondental.ca`**, so the raw HTML, `robots.txt`, `sitemap.xml`, response headers and page speed **could not be inspected directly**. Semrush data (traffic, keywords, backlinks) was also unavailable because the account has no API units left.
>
> All findings below come from what search engines have indexed and from public web signals. Each finding is labelled:
> - **✅ Confirmed**: seen directly in search results
> - **🔎 Inferred**: a strong likelihood based on indirect evidence. Check it before acting.
> - **❓ Unverified**: could not be checked. It is listed so it gets checked.
>
> The score is therefore an **estimate with a wide margin (about ±10 points)**. A crawl of the site (Screaming Frog, Search Console, PageSpeed Insights) should be the first follow-up.

---

## 🏆 Overall SEO Health Score: ~45/100 (estimated)

| Category | Score | Grade |
|----------|-------|-------|
| Technical SEO | 15/30 | D |
| On-Page SEO | 10/25 | D |
| Content Quality | 10/20 | C |
| Off-Page / Authority | 4/15 | F |
| User Experience | 6/10 | C |

**Summary:** Watermelon Dental has a strong, clearly different offer: kid-friendly care, sedation, AR glasses, Netflix and video games in the chair, and acceptance of CDCP, NIHB and IFHP. It also has a highly credentialed dentist. But the website is **almost invisible in search**. Google appears to index only 2 URLs: the homepage and a leftover `/home-2/` draft page. The homepage title is just the brand name, with no "dentist" or "Bolton". The site does not appear for "dentist Bolton Ontario", "kids dentist Bolton" or "CDCP dentist Bolton". Competitors own all of those searches with dedicated service and city pages. The practice is new, so this is expected, but it is very fixable.

---

## 🚨 Critical Issues (Fix Immediately)

### 1. Only ~2 pages indexed, and no service pages in Google ✅ Confirmed
A `site:watermelondental.ca` search returns only:
- `https://watermelondental.ca/`: title "Watermelon Dental"
- `https://watermelondental.ca/home-2/`: title "Home-2 – Watermelon Dental"

No pages were found for the individual services (cleanings, emergency, pediatric, sedation, crowns, root canals, whitening, dentures), for the team or doctor, for contact or booking, or for CDCP.
**Why it matters:** Google ranks *pages*, not websites. With one real page, the site can compete for at most one or two searches, and today it isn't competing for any of the valuable ones.
**Fix:**
1. Check in Google Search Console (**Indexing → Pages**) whether service pages exist but aren't indexed, or simply don't exist.
2. If they exist, check them for `noindex`. This is common when a WordPress site launches with **Settings → Reading → "Discourage search engines"** still ticked. Also check that `robots.txt` doesn't block them, then submit `sitemap.xml`.
3. If they don't exist, build them. See High Priority #1.

### 2. The duplicate "Home-2" draft page is indexed ✅ Confirmed
`/home-2/` ("Home-2 – Watermelon Dental") is a leftover WordPress page. The "Page Title – Site Name" format points to WordPress, 🔎 inferred. It is almost certainly a copy or draft of the homepage.
**Why it matters:** It competes with the real homepage for the same brand searches, splits its signals and looks unprofessional in results.
**Fix:** Delete or unpublish it and **301-redirect `/home-2/` → `/`**. A 301 redirect permanently sends users and Google to the right page. Then use Search Console → **Removals** to speed up dropping it from Google. Check for other leftovers such as `/sample-page/`, `/hello-world/`, `/home/` or `/?page_id=`.

### 3. The homepage title tag has no keywords or location ✅ Confirmed
The current title is **"Watermelon Dental"** (17 characters). The title tag is the blue clickable headline in Google and the strongest on-page ranking signal. Right now it tells Google nothing about *what* or *where*.
**Fix:** Use this (58 characters):
> **Dentist in Bolton, ON | Family & Kids Dentistry | Watermelon Dental**

A shorter option is "Bolton Dentist for Kids & Families | Watermelon Dental".

---

## 🟠 High Priority Issues

### 1. Build service + city landing pages 🔎 Inferred gap, competitors confirmed
Every competitor that ranks has pages built around a service plus a city:
- Humber Valley Dental: `/family-kid-dentistry/`, `/cdcp-dentist-near-me-bolton/`, `/dentist-in-caledon-east/`
- Smiles on Queen: `/childrens-dentist-bolton-caledon/`, `/sleep-sedation-dentistry/`
- Bolton Kids Dental: `/oral-moderate-sedation/`

**Create one page, of at least 600 words, for each of these**, with a unique title, H1 and FAQs:

| Page | Suggested URL | Suggested title |
|---|---|---|
| Kids / pediatric dentistry | `/kids-dentist-bolton/` | Kids Dentist in Bolton, ON \| Watermelon Dental |
| Sedation dentistry | `/sedation-dentistry-bolton/` | Sedation Dentistry in Bolton & Caledon \| Watermelon Dental |
| CDCP / NIHB / IFHP | `/cdcp-dentist-bolton/` | CDCP Dentist in Bolton, ON – Now Accepting \| Watermelon Dental |
| Emergency dentist | `/emergency-dentist-bolton/` | Emergency Dentist in Bolton, ON \| Watermelon Dental |
| Cleanings & checkups | `/dental-cleaning-bolton/` | Gentle Dental Cleanings in Bolton \| Watermelon Dental |
| Root canals, crowns, extractions, dentures, whitening | one page each | "[Service] in Bolton, ON \| Watermelon Dental" |
| Anxious patients / comfort (AR glasses, Netflix, blankets) | `/anxious-patients/` | Dentist for Anxious Patients in Bolton \| Watermelon Dental |
| Caledon / Caledon East / Nobleton / King City | `/dentist-caledon/` etc. | Dentist Near Caledon, ON \| Watermelon Dental |

The **CDCP page is especially high-value**. It is a fast-growing, high-intent search in 2025–26, and Watermelon also accepts **NIHB and IFHP**, which almost no competitor mentions.

### 2. Google Business Profile not confirmed ❓ Unverified
For a local dentist, the Google Business Profile (the listing in the Google Maps "3-pack") drives more new patients than the website does. No GBP listing appeared in the searches, though reviews on the site are visible in search.
**Fix:** Claim and verify it. Set **Primary category** to "Dentist" and add the secondary categories "Pediatric dentist" and "Emergency dental service". Add all services, hours, booking URL, 20+ photos (the kids' play area and craft room are great visuals) and the CDCP, NIHB and IFHP attributes. Ask every happy patient for a Google review. The goal is 50+ reviews in the first 6 months.

### 3. Address ambiguity: shared building, with the unit number missing ✅ Confirmed
Search engines list Watermelon Dental at **18 King Street East (Courtyards), Bolton**. That same address is also used by **Smiles on Queen Family Dentistry (Unit L-3)** and **Davis Orthodontics – Bolton**.
**Why it matters:** Google merges or confuses businesses at the same address. Without a unit number, Watermelon's listing may be filtered out of Maps or mixed up with a competitor two doors away.
**Fix:** Always publish the **full address with unit number and postal code (L7E …)**. Use it in exactly the same format on the website footer, the contact page, schema, GBP and every directory.

### 4. LocalBusiness / Dentist schema markup ❓ Unverified
Schema is structured data that tells Google your business details in a machine-readable way. It could not be checked. Most new WordPress dental sites don't have it.
**Fix:** Add JSON-LD `Dentist` schema to the homepage and contact page:
```json
{
  "@context": "https://schema.org",
  "@type": "Dentist",
  "name": "Watermelon Dental",
  "url": "https://watermelondental.ca/",
  "telephone": "+1-XXX-XXX-XXXX",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "18 King Street East, Unit ___",
    "addressLocality": "Bolton",
    "addressRegion": "ON",
    "postalCode": "L7E ___",
    "addressCountry": "CA"
  },
  "geo": { "@type": "GeoCoordinates", "latitude": 0, "longitude": 0 },
  "openingHoursSpecification": [],
  "founder": { "@type": "Person", "name": "Dr. Sanjukta Mohanta", "alumniOf": "University of Toronto Faculty of Dentistry" },
  "paymentAccepted": "Canadian Dental Care Plan (CDCP), NIHB, IFHP, Private insurance",
  "sameAs": ["https://www.instagram.com/watermelondental/"]
}
```
Add `FAQPage` schema on service pages. Check the result with Google's Rich Results Test.

### 5. Brand name collision: "Watermelon Dental" in Tijuana ✅ Confirmed
A search for `"watermelondental.ca"` returns a **Facebook page "Watermelon Dental | Tijuana"** above the actual site. This is a different business.
**Fix:** Create an official Facebook page, e.g. "Watermelon Dental – Bolton, ON". Link all social profiles from the site and from `sameAs` in the schema. Always use "Watermelon Dental Bolton" in listings so Google can tell the two apart.

---

## 🟡 Medium Priority Issues

1. **Meta description** ❓ Unverified. Write a unique 150–160-character description for every page. Homepage suggestion (157 characters):
   > *Fun, gentle family & kids dentistry in Bolton, ON. Sedation, Netflix & AR glasses in the chair. Now accepting CDCP, NIHB & IFHP. Book your visit today!*
2. **H1 on the homepage** ❓ Unverified. It should be one H1 with the main keyword, e.g. *"Fun, Gentle Family & Kids Dentist in Bolton, Ontario"*.
3. **Doctor bio page (E-E-A-T)** 🔎 Inferred gap. E-E-A-T means Experience, Expertise, Authoritativeness and Trust, the qualities Google looks for on health sites. Dr. Sanj's credentials are exceptional and should have their own `/dr-sanj-mohanta/` page. They include U of T Dentistry 1999, 25+ years in practice, the ODA Service Award, the U of T Alumni of Influence Award, the Ontario Volunteer Award, the New Dentist Study Club podcast host role and outreach work (Filling the Gap, 1000 Smiles, Northern Ontario Indigenous communities). Google weighs these trust signals heavily for health ("YMYL") content. Add `Person` schema and link to her LinkedIn, Garrison Dental profile and podcast.
4. **Local citations / directories** ✅ Confirmed gap. Watermelon Dental doesn't appear on Yelp, YellowPages.ca, Canpages, RateMDs, Opencare, Medimap or hellodent. All of those rank for "dentist Bolton" and list the competitors. Create consistent listings on each, starting with Opencare, Medimap and RateMDs, which send patients directly.
5. **Backlinks** 🔎 Inferred very low. The site is new, and no referring sites were found. Easy wins:
   - The ODA member directory
   - U of T Dentistry alumni pages
   - Filling the Gap and 1000 Smiles volunteer pages
   - The Caledon Chamber of Commerce
   - Bolton community and news sites (Caledon Citizen, Caledon Enterprise)
   - Local schools, sports sponsorships
   - The "Caledon – Yours to Explore" podcast (it already mentions the domain)
6. **Sitemap and robots.txt** ❓ Unverified. Confirm that `/sitemap.xml` (or `/wp-sitemap.xml` / Yoast's `/sitemap_index.xml`) exists, lists only real pages and is submitted in Search Console. Confirm that `robots.txt` doesn't `Disallow: /`.
7. **www vs non-www and HTTPS consistency** ❓ Unverified. Make sure `http://`, `http://www.` and `https://www.` all 301-redirect to `https://watermelondental.ca/` in a single hop.

---

## 🟢 Quick Wins & Low Priority

- **Image alt text** ❓: describe the images, e.g. `alt="Kids play area at Watermelon Dental in Bolton"`, not `IMG_2034`.
- **Open Graph tags** ❓: set a branded share image and title, so links look good when shared on Instagram, Facebook or WhatsApp.
- **Blog / FAQ content**: start with 1–2 posts per month answering local questions. Examples: "Does CDCP cover kids' dental in Ontario?", "What age should my child first see a dentist?", "Is nitrous oxide safe for kids?", "What to do in a dental emergency in Caledon".
- **Online booking CTA**: put a "Book Now" button and a click-to-call phone link in the header on every page.
- **Opening announcement**: publish a "We're Open in Bolton!" news post and send it to local media for easy backlinks.

---

## 📊 Detailed Findings

### Technical SEO
| Check | Status | Finding |
|---|---|---|
| HTTPS / SSL | ❓ | Search results use `https://`, so HTTPS is likely in place. Mixed content could not be checked. |
| Crawlability (robots.txt) | ❓ | Blocked from fetching. Verify that it doesn't block the whole site. |
| Sitemap | ❓ | Blocked from fetching. Verify it exists and is submitted to GSC. |
| Indexation | 🔴 ✅ | Only about 2 URLs indexed (`/`, `/home-2/`). |
| Canonicalization | 🔴 ✅ | `/home-2/` is a duplicate of the homepage. www vs non-www is unverified. |
| Mobile-friendliness | ❓ | Most modern WordPress themes are responsive. Verify with PageSpeed Insights. |
| Page speed / CWV | ❓ | No data. Check with PageSpeed Insights. Aim for LCP < 2.5 s, INP < 200 ms, CLS < 0.1. |
| Structured data | ❓ | Unknown. Very likely missing Dentist/LocalBusiness schema. |
| Hreflang | N/A | English-only site. Not needed. |
| Redirects / 404s | ❓ | Unknown. Run Screaming Frog. |

### On-Page SEO
| Check | Status | Finding |
|---|---|---|
| Title tag | 🔴 ✅ | "Watermelon Dental": brand only, no keyword or location. |
| Title tag (`/home-2/`) | 🔴 ✅ | "Home-2 – Watermelon Dental": a leftover draft. |
| Meta description | ❓ | Not verifiable. Write a unique one per page. |
| H1 / heading structure | ❓ | Not verifiable. |
| Keyword usage | 🔎 | Indexed snippets list services in one sentence, with no depth per service. |
| Internal linking | 🔎 | Few or no inner pages indexed, so there is little internal linking. |
| URL structure | 🟡 ✅ | `/home-2/` is a meaningless URL. Use descriptive slugs. |
| Content length | 🔎 | The homepage seems to carry all the content, and each service gets only one line. |

### Content Quality
- **Strengths ✅:** a unique, memorable positioning ("fun, fresh and healthy like a watermelon"). It has clear kid-focused differentiators (play area, craft room, whole family in the operatory, Netflix and games, AR glasses, blankets, nitrous and oral sedation) and inclusive coverage (CDCP, NIHB, IFHP). Search snippets also show positive reviews on the site.
- **Weaknesses:** there is no depth per service. There is no visible doctor bio page, even though Google says little about Dr. Sanj on the site itself (her bio signals come from LinkedIn and Instagram). There is no blog or FAQ content and no freshness signals.
- **Intent match:** people search for "kids dentist Bolton", "sedation dentist near me" and "CDCP dentist Bolton". Each needs its own page to match.

### Off-Page & Authority
- **Backlinks:** Semrush data was unavailable (no API units). Only 1 external page referencing the domain was found (the Caledon podcast listing on iHeart). The profile is effectively new.
- **Brand mentions:** Instagram `@watermelondental` (Bolton, ON) ✅, Dr. Sanj's personal Instagram, LinkedIn and Garrison Dental profile ✅.
- **Brand confusion:** the Watermelon Dental Tijuana Facebook page outranks the site for the domain name ✅.
- **Local citations:** absent from all major Canadian dental directories that were checked ✅.

### User Experience
- ❓ Navigation, CTAs, pop-ups, mobile layout and Core Web Vitals could not be checked because direct access was blocked.
- 🔎 The comfort-first offering strongly supports conversion, provided it is prominent above the fold together with a "Book Now" button and a phone number.
- Accessibility: check colour contrast. Watermelon pink or green on white often fails WCAG AA for body text.

### Local SEO
| Check | Status | Finding |
|---|---|---|
| Google Business Profile | ❓ | Not seen in results. Claim and optimize it. |
| NAP consistency | 🟠 ✅ | The address is shared with 2 other dental offices, and the unit number is not shown publicly. |
| Local schema | ❓ | Likely missing. |
| Location pages | 🔴 🔎 | None indexed. Competitors have Bolton, Caledon and Caledon East pages. |
| Local keywords in titles | 🔴 ✅ | "Bolton" is absent from the homepage title. |
| Map-pack visibility | 🔴 ✅ | The site does not appear for "dentist Bolton Ontario". The results are Humber Valley Dental, Dentistry in Bolton, Bolton Family Dental Centre, Bolton Park Dentistry, South Bolton Dental and The Tooth Place. |

**Main local competitors to benchmark:** Humber Valley Dental, Smiles on Queen (same building), Bolton Kids Dental (direct kids/sedation competitor), Dentistry in Bolton, Bolton Family Dental Centre, Bolton Park Dentistry, South Bolton Dental and The Tooth Place.

---

## 🗺️ Action Plan

### Week 1 (Critical + High Priority)
- [ ] Set up and verify **Google Search Console** and GA4. Check Indexing → Pages for `noindex` or excluded pages.
- [ ] In WordPress, untick **"Discourage search engines"** if it is set.
- [ ] Delete `/home-2/` and add a 301 redirect to `/`. Request removal in GSC.
- [ ] Change the homepage title to **"Dentist in Bolton, ON | Family & Kids Dentistry | Watermelon Dental"** and add the meta description.
- [ ] Publish the full address with **unit number + postal code** in the footer and on the contact page.
- [ ] Claim and optimize the **Google Business Profile**. Start asking for reviews.
- [ ] Install an SEO plugin (Yoast or Rank Math) and submit the sitemap.

### Month 1 (Medium Priority)
- [ ] Publish service pages: **Kids Dentist, Sedation, CDCP/NIHB/IFHP, Emergency, Cleanings**, then the remaining services.
- [ ] Publish the **Dr. Sanj Mohanta** bio page and the Team page.
- [ ] Add `Dentist` + `FAQPage` + `Person` schema.
- [ ] Create a Facebook page and listings on Opencare, Medimap, RateMDs, YellowPages.ca, Yelp and Canpages, all with identical NAP.
- [ ] Get the first backlinks: ODA directory, U of T alumni, volunteer organizations, the Caledon Chamber, a local press release.
- [ ] Run PageSpeed Insights and fix any Core Web Vitals failures (compress images, use WebP, cache).

### Ongoing
- [ ] 1–2 blog/FAQ posts per month on local and patient questions.
- [ ] Get 4–8 new Google reviews per month and reply to all of them.
- [ ] Post to GBP weekly (photos, offers, events).
- [ ] Check GSC monthly for new queries and turn frequent impressions into pages.
- [ ] Add Caledon, Caledon East, Nobleton and King City location pages once the core pages rank.

---

## 📈 Expected Impact

The site is new and currently has almost no organic visibility, so the upside is large:
- **Weeks 1–4:** fixing the title, removing `/home-2/` and claiming GBP should get the practice ranking for its **brand** and appearing in **Google Maps** for "dentist near me" searches close to the office.
- **Months 2–4:** with 8–12 service and location pages, schema and citations, it is realistic to reach **page 1 for long-tail searches** such as "kids dentist Bolton", "sedation dentist Caledon" and "CDCP dentist Bolton". Competition on these is moderate. The NIHB and IFHP angle is almost uncontested.
- **Months 4–9:** with steady reviews and backlinks, the practice can compete for the **Map Pack on "dentist Bolton"**. That is typically the biggest single source of new patients for a local dental office.

---

## 🔍 Tools Recommended for Ongoing Monitoring
- **Google Search Console** (free): indexing, queries, errors
- **Google Business Profile Insights** (free): calls, direction requests, map views
- **Google PageSpeed Insights** (free): Core Web Vitals
- **Screaming Frog SEO Spider** (free up to 500 URLs): a full crawl to fill in every ❓ above
- **Semrush** (backlink, keyword and local rank tracking). Needs API units for MCP access: https://www.semrush.com/mcp-access
- **Schema Markup Validator** / **Rich Results Test**
- **BrightLocal** or **Whitespark**: citation building and local rank grids

---

## Sources
- [Watermelon Dental – homepage](https://watermelondental.ca/)
- [Watermelon Dental – /home-2/ (indexed duplicate)](https://watermelondental.ca/home-2/)
- [Watermelon Dental – Instagram](https://www.instagram.com/watermelondental/)
- [Dr. Sanjukta Mohanta – LinkedIn](https://www.linkedin.com/in/sanjukta-mohanta-146232212/)
- [Sanjukta Mohanta – Garrison Dental](https://www.garrisondental.com/leaders/sanjukta-mohanta)
- [Watermelon Dental | Tijuana – Facebook (brand collision)](https://www.facebook.com/WatermelonDental/)
- [Caledon – Yours to Explore podcast (iHeart)](https://www.iheart.com/podcast/1333-caledon-yours-to-explore-340036751)
- [Smiles on Queen – 18 King St E address](https://smiledentistry.ca/llm-info/)
- [Davis Orthodontics – Bolton](https://www.davisortho.ca/orthodontist/bolton-orthodontist/)
- [Humber Valley Dental – CDCP Bolton page](https://www.humbervalleydental.ca/cdcp-dentist-near-me-bolton/)
- [Humber Valley Dental – Caledon East page](https://www.humbervalleydental.ca/dentist-in-caledon-east/)
- [Smiles on Queen – Children's Dentist Bolton/Caledon](https://smiledentistry.ca/childrens-dentist-bolton-caledon/)
- [Smiles on Queen – Sedation Dentistry](https://smiledentistry.ca/sleep-sedation-dentistry/)
- [Bolton Kids Dental](https://boltonkidsdental.com/)
- [Dentistry in Bolton](https://www.dentistryinbolton.com/site/home)
- [Bolton Park Dentistry](https://boltonparkdentistry.com/)
- [South Bolton Dental](https://southboltondental.com/)
- [The Tooth Place](https://thetoothplace.ca/)
- [Medimap – Bolton dentists](https://medimap.ca/clinics/dentists/on/bolton)
- [RateMDs – Bolton dentists](https://www.ratemds.com/best-doctors/on/bolton/dentist/)
