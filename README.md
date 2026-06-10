================================================================================
  FLOWRA — SaaS Productivity Landing Page
================================================================================

OVERVIEW
--------
Flowra is a fictional SaaS (Software as a Service) productivity platform
designed to help teams manage tasks, stay focused, and ship work faster.
This project is a fully designed, production-ready marketing landing page
for the Flowra brand.

The page is built to convert visitors into signups — showcasing the product's
value proposition, features, pricing, and social proof in a single, scrollable
experience.

--------------------------------------------------------------------------------

WHAT IS A SaaS LANDING PAGE?
------------------------------
A SaaS landing page is the public-facing marketing website for a software
product sold on a subscription basis (monthly or annually). Its primary goals
are to:

  1. Explain what the product does and who it's for
  2. Build trust through testimonials and social proof
  3. Present pricing plans clearly
  4. Drive visitors to sign up or book a demo (conversion)

This landing page follows industry best practices for SaaS marketing sites
used by companies like Notion, Linear, Figma, and Superhuman.

--------------------------------------------------------------------------------

PAGE SECTIONS
--------------
  1. NAVIGATION BAR
     Sticky glassmorphism nav with logo, links, Sign In, and "Try free" CTA.
     Collapses to a hamburger menu on mobile.

  2. HERO SECTION
     Main headline, subheadline, dual CTA buttons, social proof (avatar stack +
     star rating), and a decorative dashboard UI mockup built in pure HTML/CSS.

  3. BRAND LOGOS BAR
     "Trusted by teams at..." section displaying fictional company names to
     reinforce credibility.

  4. FEATURES SECTION (6 cards)
     - Smart Priority Engine
     - Deep Focus Mode
     - Team Flow Boards
     - Clarity Analytics
     - One-Click Integrations
     - Enterprise Security

  5. STATS BANNER
     Animated count-up numbers: 12,000+ teams, 94% report more focus,
     4.8M+ tasks completed, 99% uptime SLA.

  6. PRICING TABLE (3 plans)
     - Starter: Free forever
     - Pro: $18/seat/mo (Most Popular)
     - Business: $42/seat/mo
     Includes a monthly/annual billing toggle that updates prices live (-30%).

  7. TESTIMONIALS (6 cards)
     Five-star reviews from fictional users across different roles and companies.

  8. CALL TO ACTION (CTA)
     Full-width conversion section: "Your best work is one click away."
     Includes primary CTA and "Book a demo" secondary option.

  9. FOOTER
     4-column layout with Product, Company, and Resources links, social icons,
     copyright, and legal links.

--------------------------------------------------------------------------------

TECHNICAL DETAILS
------------------
  - Stack:        Pure HTML5, CSS3, Vanilla JavaScript
  - Dependencies: ZERO — no external libraries, CDNs, or frameworks
  - Design style: Glassmorphism (backdrop-filter blur, translucent cards,
                  soft pastel gradients, floating orb decorations)
  - Responsive:   Fully mobile-friendly down to 375px viewport
  - Animations:   CSS keyframes + IntersectionObserver scroll-reveal +
                  requestAnimationFrame count-up
  - File count:   1 (single self-contained index.html)
  - Deploy:       Drop index.html into Hostinger public_html — done

--------------------------------------------------------------------------------

HOW TO DEPLOY ON HOSTINGER
----------------------------
  1. Log in to Hostinger hPanel
  2. Go to File Manager > public_html
  3. Upload index.html
  4. Visit your domain — the page is live

  Optional: rename index.html if deploying to a subfolder path.

--------------------------------------------------------------------------------

CUSTOMIZATION GUIDE
--------------------
  Brand name/colors   →  Search "Flowra" and CSS :root variables at the top
  Pricing numbers     →  Update .monthly-price / .annual-price span values
  Feature cards       →  Edit .feature-card blocks in the features section
  Testimonials        →  Edit .testimonial-card blocks
  CTA links           →  Replace href="#" with real signup/demo URLs
  Stats numbers       →  Update data-target attributes on [data-target] elements

--------------------------------------------------------------------------------

LICENSE
-------
This file is provided as a template/starter. The Flowra brand name, copy,
and visuals are fictional and created for demonstration purposes only.
Free to use, modify, and redistribute for personal or commercial projects.

================================================================================
