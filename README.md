# Front-End & WordPress │ Developer Portfolio

Hi! My name is Pavlo, and I am a Front-End and WordPress Developer from Kyiv, Ukraine. I build custom WordPress themes from Figma that clients edit themselves, without a developer, and I maintain live sites: bug fixes, updates and hosting migrations with minimal downtime.

This portfolio includes selected commercial projects delivered for clients in the US, Canada, the UK, Germany and Hungary.

---

## 🏅 Track Record
- **Upwork:** 100% Job Success, $3,000+ earned
- **Fiverr:** Fiverr Pro, Level 2, 5.0 rating from 42 reviews, 60+ completed orders
- **Direct clients:** 16 projects in one year for one agency partner, about 70 static sites for another

---

## 🧑‍💻 About Me
- 10+ years of commercial development experience (HTML/CSS/JS frontend since 2015, WordPress since 2022)
- WordPress Developer (custom themes, ACF, Gutenberg, custom Gutenberg blocks)
- Front-End Developer (HTML5, SCSS with BEM, vanilla JavaScript, animations)
- Figma, PSD and Adobe Illustrator designs → pixel-perfect, responsive code; mobile layout adapted in code when there is no mobile mockup
- Website maintenance: bugs traced to the root cause in the code, fixes in the theme or child theme rather than in plugin files
- Hosting migration, DNS and email setup
- Multilingual websites on Polylang, including Arabic RTL
- Accessible websites built to ADA and WCAG 2.1/2.2
- Technical SEO: Yoast, canonical URLs, sitemaps, 301 redirects

---

## 🏆 Featured Projects

### 🔹 **Stargo Facility Services – Bug Fixes on a Live Site**
**Repo:** [stargo-wordpress-project](https://github.com/Pavlo-Honcharenko/stargo-wordpress-project)
**Live site:** https://stargo-fs.de/
A German cleaning company had four defects on a live WordPress site with a custom theme and real traffic. I cloned it from a full backup and traced each issue in the source. The carousel bug was real: a mousemove handler placed the prev and next buttons at the same coordinates, so Next permanently covered Prev. Also a logo with no retina source, a hero missing its trust block, and an image losing half its height to a fixed container. All four fixed and verified on desktop and mobile in one session; rated 5 stars, and a larger project followed.

---

### 🔹 **Hive Builders – Custom WordPress Theme from Figma for a Construction Company**
**Repo:** [hivebuilders-wordpress-project](https://github.com/Pavlo-Honcharenko/hivebuilders-wordpress-project)
**Live site:** https://hivebuilders.com/
A commercial general contractor in San Jose, California, wanted their site on WordPress rather than locked into a no-code platform. Custom theme from scratch, no template and no jQuery: semantic HTML, BEM SCSS, a video hero, smooth-scroll navigation, a hexagon grid for 8 construction sectors and 6 service cards. Every text block is a labeled custom field. Mobile was built from its own Figma frame, not a stacked desktop. Yoast configured, deployed with domain and SSL.

---

### 🔹 **NEAGENT – Real Estate Classifieds Platform + Hosting Migration**
**Repo:** [neagent-wordpress-project](https://github.com/Pavlo-Honcharenko/neagent-wordpress-project)
**Live site:** https://neagent.org.ua/
Real estate classifieds platform built on WordPress and ListingHive, featuring automated agency feed imports, custom Gutenberg blocks, 5,000+ SEO articles, and full-cycle development, administration, and optimization.
**Migration:** moved the live site (6 GB, thousands of listing photos) to a new host before the old contract expired. The copy was built on the new host while the public site kept running; the final sync took about 1.5 hours of maintenance mode. DNS switched at record level only, SPF, DKIM and DMARC pass on real headers, no data lost.

---

### 🔹 **Rate Shop Live – Custom WordPress Theme with Lead Tracking and Conversions API**
**Repo:** [rateshoplive-wordpress-project](https://github.com/Pavlo-Honcharenko/rateshoplive-wordpress-project)
**Live site:** https://rateshoplive.com/
A life insurance rate comparison service that pays for its traffic, so every lead has to be attributable. Custom theme from Figma with a multi-step quote form, a personalized video review flow and Calendly in an on-site popup. Three dataLayer events (form_start, generate_lead, booking_confirmed) feed Google Ads, while Meta Pixel and server-side Conversions API share one event_id. 23 carrier logos import through a WP-CLI command and an admin button, since the host has no SSH. Content is managed through 8 ACF options pages.

---

### 🔹 **Autos On The Go – Custom WordPress Theme + SEO Recovery After Redesign**
**Repo:** [autosonthego-wordpress-project](https://github.com/Pavlo-Honcharenko/autosonthego-wordpress-project)
**Live site:** https://www.autosonthego.com/
Custom WordPress multi-page website with a blog for a US and Canada car shipper, built from Figma. Includes dynamic content via Custom Fields, custom Gutenberg elements and page templates, Gravity Forms integration, Yoast SEO setup, and accessibility improvements.
**SEO recovery:** months after a redesign, new service pages were still not indexed. The sitemap listed 21 pages while the site had 31: old canonical URLs stayed in the database after service URLs moved, so Yoast dropped those pages. I removed them, set correct canonicals and 301 redirects, and all 31 pages returned to the sitemap.

---

### 🔹 **ConnectABA – ADA & WCAG Accessible WordPress Website**
**Repo:** [connectaba-wordpress-project](https://github.com/Pavlo-Honcharenko/connectaba-wordpress-project)
**Live site:** https://connectaba.org/
An accessibility-focused WordPress website where ADA and WCAG 2.1/2.2 compliance was a mandatory client requirement. Figma → HTML/SCSS/JS → custom theme with ACF and Contact Form 7, plus advice on choosing the hosting provider.

---

## 🧰 More Client Work

### Custom WordPress Builds

#### 🔹 **Stargo – Figma to WordPress Landing Page for Google Ads (10 Sections)**
**Repo:** [stargo-wordpress-project](https://github.com/Pavlo-Honcharenko/stargo-wordpress-project)
**Live site:** https://stargo-fs.de/bueroreinigung-stuttgart/
A landing page for a Google Ads campaign, built inside the client's existing custom theme rather than beside it. 10 sections from Figma: hero with company stats and trust logos, project cases, team, a contractor-switching process, fixed-price explainer, property types, service categories, ticket system and FAQ. The page reuses the site's exact visual language; mobile is its own layout, and every interaction works without hover.

#### 🔹 **LDVILL – Custom WordPress Theme in 5 Languages (Figma → HTML → WP)**
**Repo:** [ldvill-wordpress-project](https://github.com/Pavlo-Honcharenko/ldvill-wordpress-project)
**Live site:** https://ldvill.com/
A custom WordPress theme for an electrical services company in Budapest, developed from a full Figma design. Includes ACF integration, custom PHP templates, animations, a fully responsive layout, and 5 languages on Polylang (Hungarian, English, German, Russian, Ukrainian), plus Contact Form 7.

#### 🔹 **KYTSIAWEB – Custom WordPress Theme (Figma → HTML → WP)**
**Repo:** [kytsiaweb-wordpress-project](https://github.com/Pavlo-Honcharenko/kytsiaweb-wordpress-project)
Custom WordPress website for a web design agency, built from Figma with pixel-perfect front-end development, a category filter, animations, and ACF-powered dynamic content.

#### 🔹 **HasibPay – Multilingual Landing Page (EN + AR)**
**Repo:** [hasibpay-wordpress-project](https://github.com/Pavlo-Honcharenko/hasibpay-wordpress-project)
A multilingual landing page built from Figma on the Astra theme and Gutenberg blocks. Includes RTL layout for Arabic, Polylang setup and Contact Form 7. Before work started, I advised against GoDaddy hosting because of email delivery issues, and the client picked IONOS from my shortlist. After review on my staging server, I connected the GoDaddy domain to IONOS and launched the same evening, then set up new mailboxes and confirmed form emails arrive.

#### 🔹 **Nine Champagne 9 – Redesign of a Live WooCommerce Store**
**Live site:** https://9champagne.pro/
A UK PR agency wanted their live store rebuilt around a new look without pausing sales. The only reference was six screenshots from an AI builder: no design file and no mobile version. I rebuilt the homepage as 6 sections, with the services grid pulling from real WooCommerce products instead of hardcoded prices, redesigned About and Contact, added shop category badges and two legal pages. Work ran on a local clone and was pushed back live, so the store never closed.

### Front-End (HTML / CSS / JavaScript)

#### 🔹 **Junebug Weddings – HTML5 Vendor Portfolio Template for a Wedding Media Brand**
**Live site:** https://junebugweddings.com/ (vendor pages)
A new vendor portfolio page for a wedding media brand: first a standalone template, then integrated into the live site. Hand-coded HTML5, CSS and JavaScript from an Adobe Illustrator design, plain media queries, LightGallery for the gallery. I proposed replacing Flickity with Swiper because it is MIT licensed, removing a commercial licensing obligation. Delivered as a Gulp and Webpack environment with SCSS sources; still live two years later.

#### 🔹 **EventForm – Front-End for an Event Platform (Six Projects)**
*Product not public.*
A US founder needed components he could drop into an event platform codebase that was already running: an organizer console plus the public event page. I kept most of the work in CSS so the existing editor and date inputs kept their behaviour. Where markup changed, it changed for a reason: the registrations table moved to divs for a fixed header on scroll, and the native time input was replaced with a picker supporting 15-minute steps. Six engagements over eleven months, every review five stars.

#### 🔹 **Internal Production Management System – Reusable UI Component Set**
*Client name, screenshots and code not shown (NDA).*
An in-house team needed front-end their developers could build on: not pages, but a reusable component set with global elements their own team could change themselves. I delivered the UI across 12 screens with style documentation, working inside the framework they had already chosen. It grew into several follow-up engagements: print-ready document templates, modal dialogs and a data table with row states and tabs.

#### 🔹 **Orpheus Show – Custom Audio Player on a Static Site**
**Live site:** https://www.orpheusfantasy.com/music.html
A multi-page static site for a composer's rock opera, built in 2022 and running unchanged since. The audio player has a fully custom UI on top of the native audio element, with no player library. The bundle is BEM-structured CSS and vanilla JavaScript: no jQuery, React, Vue or Bootstrap, which anyone can verify in the source.

#### 🔹 **Static Business Websites for a US Agency Partner**
**Repo:** [nationalbridgedemolition-static-project](https://github.com/Pavlo-Honcharenko/nationalbridgedemolition-static-project)
**Example:** https://nationalbridgedemolition.com/
About 70 static sites for home services and construction businesses (demolition, refinishing, home additions, tree services and more), built with HTML, SCSS and JavaScript on Gulp, Vite and Webpack. The example above scored 90 for performance and 100 for SEO and best practices in Lighthouse desktop (September 2026).

---

## 💬 What Clients Say

> "Pavlo has successfully completed over a dozen projects for us, ranging from pixel-perfect HTML templates to fully customized WordPress websites built from Figma designs. […] Communication has always been smooth, and the quality of his work is consistently excellent."
> — Vlad K., Graphic, UI/UX & Branding Expert (Upwork)

> "Pavlo did an incredible job on our project. He was exceptionally diligent, proactive and communicative. The finished product is excellent."
> — Matt Howitt, Junebug Weddings (Fiverr)

> "He took my complex Figma designs and delivered an exact implementation in HTML/CSS/JS that I was able to plug and play. His code was clean and easy to follow."
> — Founder, EventForm (Fiverr)

---

## 🔧 How I Work
1. Full backup before any change.
2. Work on a staging or local copy, while the live site keeps running.
3. Fix the root cause in the code, in the theme or child theme.
4. Check desktop and mobile in Chrome, Firefox, Safari and Edge.
5. Deploy and hand over the source via GitHub; fixes on delivered code for as long as the client asks.

---

## 🛠️ Tech Stack

### **WordPress Development**
- Custom Themes
- Gutenberg blocks
- ACF Pro (Flexible Content, Options)
- Custom PHP templates
- Polylang (multilingual, RTL)
- Contact Form 7, Gravity Forms
- Yoast SEO
- WooCommerce (store redesign, templates, small fixes)
- Backups: UpdraftPlus, backup before every change

### **Front-End**
- HTML5
- CSS3 / SASS / BEM
- JavaScript
- Animations
- Responsive design
- Gulp, Vite, Webpack

### **Additional Expertise**
- Figma → WordPress conversion
- Website migration & domain transfer, DNS and email setup
- Performance optimization
- Technical SEO (canonical URLs, sitemaps, 301 redirects)
- Conversion tracking (GTM dataLayer, Meta Pixel, Conversions API)
- Cross-browser/device testing
- Accessibility (ADA, WCAG 2.1/2.2)

---

## 📫 Contact
If you want to collaborate or have questions about my work:

- **Email:** pavlo.dev.pro@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/pavlo-honcharenko/
- **GitHub:** https://github.com/Pavlo-Honcharenko/

---

## 📌 Notes
This portfolio includes selected commercial projects.
Additional work samples are available upon request.
