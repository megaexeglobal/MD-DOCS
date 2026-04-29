# JURA AI — Landing Page Content & Copy Document

**Version:** 1.0.0  
**Date:** April 29, 2026  
**Product:** Jura AI — Legal Intelligence & Document Generation Platform  
**Domain:** jura.africa  
**Classification:** Confidential — Marketing & Design Team  
**Purpose:** Comprehensive content, copy, and section specifications for the Jura AI home/landing page

---

## Table of Contents

1. [Page Structure Overview](#1-page-structure-overview)
2. [Top Navigation Bar](#2-top-navigation-bar)
3. [Hero Section](#3-hero-section)
4. [Social Proof Bar](#4-social-proof-bar)
5. [Product Overview Section](#5-product-overview-section)
6. [Document Types Showcase (Card Grid)](#6-document-types-showcase)
7. [Platform Features Section](#7-platform-features-section)
8. [How It Works Section](#8-how-it-works-section)
9. [AI Intelligence Section](#9-ai-intelligence-section)
10. [Use Cases / Who It's For](#10-use-cases--who-its-for)
11. [Pricing Section](#11-pricing-section)
12. [Testimonials & Social Proof](#12-testimonials--social-proof)
13. [Security & Compliance Section](#13-security--compliance-section)
14. [Integration & Technology Section](#14-integration--technology-section)
15. [FAQ Section](#15-faq-section)
16. [CTA Banner Section](#16-cta-banner-section)
17. [Footer](#17-footer)
18. [SEO Metadata](#18-seo-metadata)
19. [Micro-copy & UI Labels](#19-micro-copy--ui-labels)
20. [Content Guidelines & Tone](#20-content-guidelines--tone)

---

## 1. Page Structure Overview

The landing page follows a modern enterprise SaaS pattern inspired by Google's product pages (clean, spacious, feature-focused sections with strong visual hierarchy) and Apple's approach (bold headlines, concise subtext, visual storytelling). Each section is full-width with a max-content-width of 1200px, generous vertical padding (120px between sections), and scroll-triggered animations.

**Section Flow (top to bottom):**

```
┌─────────────────────────────────────────────┐
│  1. Sticky Navigation Bar                   │
├─────────────────────────────────────────────┤
│  2. Hero Section (above the fold)           │
├─────────────────────────────────────────────┤
│  3. Social Proof Bar (logos + stats)        │
├─────────────────────────────────────────────┤
│  4. Product Overview (6 feature cards)      │
├─────────────────────────────────────────────┤
│  5. Document Types Showcase (18 doc cards)  │
├─────────────────────────────────────────────┤
│  6. Platform Features (deep dive)           │
├─────────────────────────────────────────────┤
│  7. How It Works (3-step flow)              │
├─────────────────────────────────────────────┤
│  8. AI Intelligence (RAG + Citations)       │
├─────────────────────────────────────────────┤
│  9. Use Cases / Who It's For (personas)     │
├─────────────────────────────────────────────┤
│ 10. Pricing Section (3 tiers + toggle)      │
├─────────────────────────────────────────────┤
│ 11. Testimonials & Social Proof             │
├─────────────────────────────────────────────┤
│ 12. Security & Compliance                   │
├─────────────────────────────────────────────┤
│ 13. Integration & Technology                │
├─────────────────────────────────────────────┤
│ 14. FAQ Section                             │
├─────────────────────────────────────────────┤
│ 15. Final CTA Banner                        │
├─────────────────────────────────────────────┤
│ 16. Footer                                  │
└─────────────────────────────────────────────┘
```

---

## 2. Top Navigation Bar

**Layout:** Sticky, 64px height, white background with subtle glass effect (backdrop-blur), border-bottom: 1px slate-100. Full-width, content max-width 1200px centered.

### Content:

**Left — Logo:**
- Jura AI logo mark (vertical indigo bar) + "Jura" wordmark in Space Grotesk Bold, 20px
- Logo links to top of page (smooth scroll)

**Center — Navigation Links:**
- "Features" → scrolls to Product Overview section
- "Documents" → scrolls to Document Types section
- "Pricing" → scrolls to Pricing section
- "About" → links to /about page
- "Blog" → links to /blog page
- Style: Inter 14px medium, slate-600, hover: slate-900 with underline transition

**Right — Actions:**
- 🇳🇬 Nigerian flag icon (24×24px, rounded-4px) — indicates Nigerian market focus. Clicking opens a country dropdown (Nigeria active, Ghana/Kenya/South Africa show "Coming Soon" badge)
- "Log In" — text button, Inter 14px medium, slate-700, hover: slate-900
- "Get Started" — primary button, indigo filled, rounded-full, Inter 14px semibold, px-6 py-2.5

**Mobile Navigation (< 768px):**
- Logo (left) + Hamburger menu icon (right)
- Hamburger opens full-screen overlay with nav links stacked vertically + CTA buttons at bottom

---

## 3. Hero Section

**Layout:** Centered content, max-width 800px, padding-top 120px, padding-bottom 80px. Clean white background with subtle radial gradient (very light indigo tint at center, fading to white).

### Content:

**Overline Badge:**
```
✦ Legal Intelligence for Africa
```
- Style: 14px uppercase, tracking-widest (0.15em), indigo-600 text
- Small sparkle/star icon (✦) before text, animated subtle pulse
- Background: indigo-50 pill badge, rounded-full, px-4 py-1.5

**Headline:**
```
Draft. Research. Comply.
All in one platform.
```
- Style: Space Grotesk, 60px (desktop) / 40px (mobile), bold (700), slate-900
- Line-height: 1.1
- Each word on "Draft. Research. Comply." can have a subtle staggered fade-in animation
- Alternative headline option: "The operating system for legal work in Africa."

**Subheadline:**
```
AI-powered legal document generation, case law research, and compliance 
monitoring — purpose-built for Nigerian legal professionals.
```
- Style: Inter, 20px (desktop) / 16px (mobile), regular (400), slate-500
- Max-width: 600px, centered
- Line-height: 1.6

**CTA Row (centered, gap-16px):**

| Button | Label | Style |
|--------|-------|-------|
| Primary CTA | "Get Started Free" | Indigo filled, rounded-full, 16px semibold, px-8 py-4, hover: scale 1.05 + deeper shadow |
| Secondary CTA | "▶ Watch Demo" | Ghost/outlined, slate-700 text, border slate-300, rounded-full, 16px medium, px-8 py-4, play triangle icon before text |

**Below CTAs — Trust Line:**
```
Trusted by 500+ Nigerian law firms and legal departments
```
- Style: 13px, slate-400, centered
- Below text: row of 5–6 grayscale law firm/organization logos (40px height), spaced evenly, subtle opacity 0.5, hover: opacity 1.0
- Logos should include recognizable Nigerian law firms and corporate legal departments

**Optional — Hero Visual:**
- Subtle animated background: abstract geometric mesh or flowing gradient lines in very light indigo/purple
- Or: a floating mockup of the Jura dashboard/document preview (glass-morphism card, tilted 5°, with subtle shadow)
- Keep it minimal — the copy is the hero, not the visual

---

## 4. Social Proof Bar

**Layout:** Full-width, light slate-50 background, padding 48px vertical. Content centered, max-width 1200px.

### Content — Stats Row (4 columns, evenly spaced):

| Stat | Number | Label |
|------|--------|-------|
| Documents Generated | "50,000+" | "Legal documents generated" |
| Law Firms | "500+" | "Law firms trust Jura" |
| Citation Accuracy | "99.7%" | "Citation verification accuracy" |
| Time Saved | "85%" | "Reduction in drafting time" |

- Numbers: Space Grotesk, 36px bold, slate-900
- Labels: Inter, 14px regular, slate-500
- Each stat has a subtle icon above it (document icon, building icon, checkmark icon, clock icon) in indigo-100 circle
- Numbers animate (count up) when section scrolls into view

**Mobile:** 2×2 grid

---

## 5. Product Overview Section

**Layout:** Max-width 1200px, centered. Padding-top 120px.

### Section Header:

**Overline:**
```
PLATFORM CAPABILITIES
```
- Style: 12px uppercase, tracking-widest, indigo-600, semibold

**Headline:**
```
Everything you need for legal work
```
- Style: Space Grotesk, 36px bold, slate-900

**Subheadline:**
```
Six powerful modules working together to transform how you practice law. 
From drafting court documents to monitoring compliance deadlines — Jura handles it all.
```
- Style: Inter, 18px regular, slate-500, max-width 640px, centered

### Feature Cards (3×2 grid, gap-24px):

**Card 1 — Litigation Drafting AI**
- Icon: ⚖️ FileSignature (in indigo-100 circle, 48px)
- Heading: "Litigation Drafting AI"
- Subheading: "Generate court-ready legal documents in under 30 seconds. From Writs of Summons to Written Addresses — AI drafts with Nigerian court formatting, verified citations, and your firm's letterhead applied automatically."
- Tag: "18+ Document Types"

**Card 2 — Legal Research Intelligence**
- Icon: 📚 BookOpen (in indigo-100 circle, 48px)
- Heading: "Legal Research Intelligence"
- Subheading: "Search Nigerian case law using natural language. Get ranked results with verified citations, key legal principles, relevant excerpts, and related authorities — all grounded in verified Nigerian law databases."
- Tag: "RAG-Powered"

**Card 3 — Court Procedure Guide**
- Icon: 🏛️ Landmark (in indigo-100 circle, 48px)
- Heading: "Court Procedure Guide"
- Subheading: "Never miss a procedural step. Get step-by-step guides for commencing actions in any Nigerian court — including required documents, filing fees, timelines, and limitation periods."
- Tag: "All Nigerian Courts"

**Card 4 — Case Strategy Analyzer**
- Icon: 🧠 Briefcase (in indigo-100 circle, 48px)
- Heading: "Case Strategy Analyzer"
- Subheading: "Evaluate case strength before you file. AI analyzes your facts against Nigerian case law to identify legal issues, predict possible defenses, and recommend litigation strategy with a confidence score."
- Tag: "AI-Powered Analysis"

**Card 5 — Corporate Compliance AI**
- Icon: 🛡️ ShieldCheck (in indigo-100 circle, 48px)
- Heading: "Corporate Compliance AI"
- Subheading: "Stay ahead of every deadline. Automated monitoring for CAC Annual Returns, tax filings, director changes, and regulatory obligations — with proactive alerts 30, 14, and 7 days before each deadline."
- Tag: "Automated Alerts"

**Card 6 — Legal Knowledge Graph**
- Icon: 🔗 Network (in indigo-100 circle, 48px)
- Heading: "Legal Knowledge Graph"
- Subheading: "Understand how cases, statutes, and legal principles connect. Our knowledge graph maps citation networks, statutory interpretations, and legal duty chains across Nigerian law for deeper reasoning."
- Tag: "Multi-Hop Reasoning"

### Card Design Specs:
- Background: white surface
- Border-radius: 16px (rounded-2xl)
- Padding: 32px
- Border: 1px slate-100
- Hover: shadow-medium + translateY(-4px) transition 300ms
- Icon container: 48px circle, indigo-50 background
- Heading: Space Grotesk, 20px bold, slate-900
- Subheading: Inter, 14px regular, slate-500, line-height 1.6
- Tag: 12px, indigo-600, indigo-50 background pill, rounded-full, px-3 py-1
- Scroll animation: fade-up, staggered 100ms per card

---

## 6. Document Types Showcase

**Layout:** Full-width, slate-50 background. Max-width 1200px centered. Padding 120px vertical.

This is a signature section — it showcases the breadth of documents Jura can generate. Inspired by Google's product grid layouts and Apple's feature card patterns.

### Section Header:

**Overline:**
```
DOCUMENT GENERATION
```
- Style: 12px uppercase, tracking-widest, indigo-600, semibold

**Headline:**
```
Every legal document your practice needs
```
- Style: Space Grotesk, 36px bold, slate-900

**Subheadline:**
```
18 document types across litigation, corporate, contracts, and compliance — each with 
intelligent form fields, AI enrichment, and verified Nigerian case law citations.
```
- Style: Inter, 18px regular, slate-500, max-width 640px, centered

### Category Filter Tabs (horizontal, centered):
```
All | Litigation | Corporate | Contracts | Compliance | Advisory
```
- Style: Pill tabs, 14px medium
- Active: indigo-600 text, indigo-50 background, rounded-full
- Inactive: slate-500 text, hover: slate-700
- Clicking a tab filters the card grid below with a smooth fade transition

### Document Type Cards (responsive grid: 4 columns desktop, 3 tablet, 2 mobile, gap-20px):

Each card follows this pattern:
- Background: white
- Border-radius: 16px
- Padding: 24px
- Border: 1px slate-100
- Hover: indigo border (2px), light indigo-50 background, shadow-medium, cursor pointer
- Click: navigates to /register (or opens document type detail modal)

---

#### LITIGATION DOCUMENTS

**Card 1 — Writ of Summons**
- Icon: 📜 (Scroll icon, indigo-500, 32px)
- Category Label: "LITIGATION" — 10px uppercase, tracking-widest, indigo-600
- Heading: "Writ of Summons"
- Subheading: "Commence civil actions in any Nigerian High Court. Auto-generates court headers, party captions, claims, and endorsements with proper formatting."
- Time Badge: "~30 sec" — 11px, slate-400, clock icon

**Card 2 — Statement of Claim**
- Icon: 📋 (ClipboardList icon)
- Category Label: "LITIGATION"
- Heading: "Statement of Claim"
- Subheading: "Draft comprehensive pleadings with paragraphed facts, causes of action, reliefs sought, and AI-suggested case authorities. Links to existing Writs for seamless workflow."
- Time Badge: "~45 sec"

**Card 3 — Statement of Defence**
- Icon: 🛡️ (Shield icon)
- Category Label: "LITIGATION"
- Heading: "Statement of Defence"
- Subheading: "Respond paragraph-by-paragraph to claims with admit, deny, or no knowledge options. Include preliminary objections, counter-claims, and positive defenses."
- Time Badge: "~45 sec"

**Card 4 — Originating Summons**
- Icon: ❓ (HelpCircle icon)
- Category Label: "LITIGATION"
- Heading: "Originating Summons"
- Subheading: "Frame questions for court determination with supporting grounds, statutory provisions, and case authorities. Ideal for declaratory and interpretive actions."
- Time Badge: "~30 sec"

**Card 5 — Originating Motion**
- Icon: ⚡ (Zap icon)
- Category Label: "LITIGATION"
- Heading: "Originating Motion"
- Subheading: "Draft applications to commence proceedings by motion. Supports ex parte and on-notice applications with urgency flagging and statutory basis."
- Time Badge: "~30 sec"

**Card 6 — Motion on Notice**
- Icon: 📢 (Bell icon)
- Category Label: "LITIGATION"
- Heading: "Motion on Notice"
- Subheading: "Generate interlocutory applications with orders sought, grounds, supporting affidavit references, and list of authorities — formatted per court rules."
- Time Badge: "~30 sec"

**Card 7 — Affidavit**
- Icon: ✋ (Hand icon)
- Category Label: "LITIGATION"
- Heading: "Affidavit"
- Subheading: "Create sworn depositions with proper jurat, oath type selection (Christian, Islamic, or Affirmation), numbered paragraphs, exhibit references, and means of knowledge."
- Time Badge: "~30 sec"

**Card 8 — Written Address / Legal Argument**
- Icon: 📝 (PenTool icon)
- Category Label: "LITIGATION"
- Heading: "Written Address"
- Subheading: "Craft persuasive legal arguments with issue formulation, authority-backed reasoning per issue, and structured conclusions. AI assesses argument strength."
- Time Badge: "~60 sec"

**Card 9 — Petition**
- Icon: 📄 (FileText icon)
- Category Label: "LITIGATION"
- Heading: "Petition"
- Subheading: "Draft election petitions, winding-up petitions, and bankruptcy petitions with numbered grounds, supporting facts, witness lists, and statutory provisions."
- Time Badge: "~45 sec"

---

#### CONTRACTS & AGREEMENTS

**Card 10 — Demand Letter / Letter Before Action**
- Icon: ✉️ (Mail icon)
- Category Label: "CONTRACTS"
- Heading: "Demand Letter"
- Subheading: "Send professionally drafted pre-action notices with background facts, legal basis, specific demands, compliance deadlines, and consequence of non-compliance."
- Time Badge: "~20 sec"

**Card 11 — Non-Disclosure Agreement (NDA)**
- Icon: 🔒 (Lock icon)
- Category Label: "CONTRACTS"
- Heading: "Non-Disclosure Agreement"
- Subheading: "Protect confidential information with customizable NDAs covering disclosure scope, duration, exclusions, return obligations, and breach penalties under Nigerian law."
- Time Badge: "~20 sec"

**Card 12 — Employment Contract**
- Icon: 👔 (Briefcase icon)
- Category Label: "CONTRACTS"
- Heading: "Employment Contract"
- Subheading: "Generate compliant employment agreements with compensation, benefits, leave entitlements, non-compete clauses, IP assignment, and termination provisions."
- Time Badge: "~30 sec"

**Card 13 — Memorandum of Understanding (MOU)**
- Icon: 🤝 (Handshake icon)
- Category Label: "CONTRACTS"
- Heading: "Memorandum of Understanding"
- Subheading: "Formalize multi-party collaborations with defined responsibilities, scope, confidentiality, dispute resolution, and governing law provisions."
- Time Badge: "~30 sec"

**Card 14 — Tenancy / Lease Agreement**
- Icon: 🏠 (Home icon)
- Category Label: "CONTRACTS"
- Heading: "Tenancy Agreement"
- Subheading: "Draft property lease agreements with rent terms, security deposits, permitted use, maintenance responsibilities, renewal conditions, and forfeiture clauses."
- Time Badge: "~30 sec"

---

#### CORPORATE DOCUMENTS

**Card 15 — Board Resolution**
- Icon: 🏢 (Building icon)
- Category Label: "CORPORATE"
- Heading: "Board Resolution"
- Subheading: "Document board decisions with quorum confirmation, resolution text, proposer and seconder details, and special resolution indicators for CAC compliance."
- Time Badge: "~20 sec"

**Card 16 — Power of Attorney**
- Icon: ✍️ (Pen icon)
- Category Label: "CORPORATE"
- Heading: "Power of Attorney"
- Subheading: "Grant legal authority with defined powers, scope limitations, duration, irrevocability options, and witness provisions — formatted for notarization."
- Time Badge: "~20 sec"

**Card 17 — CAC Incorporation Documents**
- Icon: 🏛️ (Landmark icon)
- Category Label: "CORPORATE"
- Heading: "CAC Incorporation Documents"
- Subheading: "Generate complete incorporation packages including Memorandum and Articles of Association, share capital structure, director details, and subscriber information."
- Time Badge: "~45 sec"

---

#### ADVISORY

**Card 18 — Legal Opinion / Advisory Memo**
- Icon: 💡 (Lightbulb icon)
- Category Label: "ADVISORY"
- Heading: "Legal Opinion"
- Subheading: "Deliver structured legal opinions with issue identification, citation-backed analysis, clear conclusions, and professional caveats — ready for client delivery."
- Time Badge: "~60 sec"

---

### Bottom of Section — CTA:
```
And we're adding more document types every month.
```
- Style: Inter, 16px, slate-500, centered
- Below: "See All Document Types →" link in indigo-600, hover: underline

---

## 7. Platform Features Section

**Layout:** White background. Max-width 1200px centered. Padding 120px vertical.

This section provides a deeper dive into platform capabilities beyond document generation. Uses an alternating layout pattern (text left / visual right, then swap) inspired by Apple's feature showcase pages.

### Section Header:

**Overline:**
```
POWERFUL FEATURES
```

**Headline:**
```
Built for how lawyers actually work
```
- Style: Space Grotesk, 36px bold, slate-900, centered

---

### Feature Block 1 — Citation Verification (Text Left, Visual Right)

**Heading:**
```
Every citation verified. Every authority checked.
```
- Style: Space Grotesk, 28px bold, slate-900

**Body:**
```
Jura doesn't just generate documents — it verifies every single citation against 
our Nigerian law database. Each case reference, statute section, and rule of court 
is cross-checked and classified as Verified, Partial Match, or Not Found. You see 
the verification status in real-time alongside your document, with expandable 
excerpts from the original judgment.

No more phantom citations. No more fabricated case names. Just verified, 
court-ready legal authorities.
```
- Style: Inter, 16px, slate-500, line-height 1.7

**Visual (right):** Mockup of the Citation Panel showing:
- A citation card with green "✅ Verified" badge
- Case name, citation, court, year
- Relevance score bar
- Expandable excerpt

---

### Feature Block 2 — Firm Branding & Artifacts (Visual Left, Text Right)

**Heading:**
```
Your letterhead. Your stamp. Your signature. Applied automatically.
```

**Body:**
```
Upload your firm's letterhead, digital stamp, authorized signatures, and legal 
stationery template once during onboarding. Every document Jura generates 
automatically applies your branding — court headers, signature blocks, and 
stamp placements — exactly where they belong.

Your documents look like they came from your firm, because they did. 
Jura just made them faster.
```

**Visual (left):** Mockup of a generated Writ of Summons with firm letterhead at top, court header, and signature block with stamp at bottom.

---

### Feature Block 3 — Real-Time Collaboration (Text Left, Visual Right)

**Heading:**
```
Review, comment, and approve — together.
```

**Body:**
```
Assign documents for review, add inline comments, track changes with 
accept/reject controls, and set up multi-level approval chains. See who's 
viewing and editing in real-time with live cursor tracking and presence 
indicators.

From junior associate to senior partner — every document goes through 
the right hands before it leaves the firm.
```

**Visual (right):** Mockup showing collaborative editing with multiple user avatars, inline comments, and track changes highlights.

---

### Feature Block 4 — Matter Management (Visual Left, Text Right)

**Heading:**
```
Organize everything by matter.
```

**Body:**
```
Group documents, research queries, notes, and deadlines under a single matter. 
Track case progress with activity timelines, assign team members, and set 
priorities. Every piece of work stays connected to the case it belongs to.

No more scattered files. No more lost research. One matter, one place, 
everything linked.
```

**Visual (left):** Mockup of Matter detail view with tabs for Documents, Research, Timeline, Notes, Team.

---

### Feature Block 5 — Template Library (Text Left, Visual Right)

**Heading:**
```
Start from a template. Finish in seconds.
```

**Body:**
```
Choose from pre-built templates for all 18+ document types, or save your own 
generated documents as custom templates. Share templates across your firm, 
version them, and reuse proven structures for consistent output every time.

One click to start. Your firm's best work as the starting point.
```

**Visual (right):** Mockup of Template Library grid with category labels and "Use Template" buttons.

---

## 8. How It Works Section

**Layout:** White or very light gradient background. Max-width 1000px centered. Padding 120px vertical.

### Section Header:

**Overline:**
```
HOW IT WORKS
```

**Headline:**
```
From facts to filed document in three steps
```
- Style: Space Grotesk, 36px bold, slate-900, centered

**Subheadline:**
```
Jura combines your input with verified Nigerian law to produce court-ready 
documents — complete with citations, formatting, and your firm's branding.
```
- Style: Inter, 18px, slate-500, centered

---

### Three Steps (horizontal on desktop, vertical on mobile):

**Step 1 — Tell Jura Your Case**
- Step Number: "01" — Space Grotesk, 48px bold, indigo-200
- Icon: Clipboard/Form icon in indigo circle (64px)
- Heading: "Tell Jura your case"
- Body: "Select your document type and fill in the details — parties, court, claims, facts. Smart forms adapt to each document type with pre-filled fields from your profile. Upload supporting documents for additional AI context."
- Visual hint: Mockup of dynamic form with fields

**Step 2 — AI Drafts with Verified Law**
- Step Number: "02"
- Icon: Brain/Sparkle icon in indigo circle (64px)
- Heading: "AI drafts with verified law"
- Body: "Jura's AI searches Nigerian case law databases, retrieves relevant authorities, generates your document with proper court formatting, and verifies every citation — all in under 30 seconds. Watch the 8-stage progress in real-time."
- Visual hint: Processing screen mockup with step indicators

**Step 3 — Review, Edit, and File**
- Step Number: "03"
- Icon: CheckCircle/Download icon in indigo circle (64px)
- Heading: "Review, edit, and file"
- Body: "Review your document with the citation panel alongside. Edit inline with rich text tools, track changes, add comments, and download as DOCX or PDF — with your firm's letterhead and stamp already applied."
- Visual hint: Document review screen mockup

### Connecting Line:
- A subtle horizontal line (or arrow) connects the three steps on desktop
- Indigo gradient, 2px, with animated dot traveling along it

### Bottom CTA:
```
"Get Started Free" [primary button] — "No credit card required"
```

---

## 9. AI Intelligence Section

**Layout:** Dark background section (slate-900 or deep indigo gradient). White text. Max-width 1200px centered. Padding 120px vertical.

This section communicates the technical sophistication of Jura's AI without being overly technical. Inspired by Google's AI product pages that explain complex technology in accessible terms.

### Section Header:

**Overline:**
```
AI ARCHITECTURE
```
- Style: 12px uppercase, indigo-300

**Headline:**
```
Intelligence grounded in Nigerian law
```
- Style: Space Grotesk, 36px bold, white

**Subheadline:**
```
Jura doesn't guess. It retrieves, reasons, and verifies — using a hybrid AI 
architecture purpose-built for the Nigerian legal system.
```
- Style: Inter, 18px, slate-300, max-width 600px, centered

---

### Three Intelligence Pillars (3-column grid):

**Pillar 1 — Retrieval-Augmented Generation (RAG)**
- Icon: Database/Search icon (white on indigo-500 circle)
- Heading: "Grounded in verified sources"
- Body: "Every AI response is backed by retrieval from our indexed Nigerian law database. Hybrid search combines semantic understanding with exact legal term matching to find the most relevant case law, statutes, and rules of court."
- Stat: "99.7% citation accuracy"

**Pillar 2 — Legal Knowledge Graph**
- Icon: Network/Graph icon (white on purple-500 circle)
- Heading: "Understands legal relationships"
- Body: "Our knowledge graph maps how cases interpret statutes, how statutes create legal duties, and how facts breach those duties. This enables multi-hop legal reasoning — the kind that wins cases."
- Stat: "Multi-hop reasoning across cases, statutes, and principles"

**Pillar 3 — Citation Verification Pipeline**
- Icon: ShieldCheck icon (white on emerald-500 circle)
- Heading: "Zero hallucinated citations"
- Body: "Every citation in every generated document is verified against our legal database. Cases are matched by name, court, year, and citation format. Unverified references are flagged immediately — so you never file a document with a phantom authority."
- Stat: "Every citation classified: Verified, Partial, or Not Found"

---

### Bottom Visual:
- Animated diagram showing the RAG pipeline flow:
  ```
  Your Input → Semantic Search → Nigerian Law DB → AI Generation → Citation Verification → Court-Ready Document
  ```
- Subtle animated dots flowing through the pipeline
- Dark background makes this visually striking

---

## 10. Use Cases / Who It's For

**Layout:** White background. Max-width 1200px centered. Padding 120px vertical.

### Section Header:

**Overline:**
```
WHO IT'S FOR
```

**Headline:**
```
Built for every legal professional
```
- Style: Space Grotesk, 36px bold, slate-900, centered

**Subheadline:**
```
Whether you're a solo practitioner or a 200-person firm, a junior associate 
or a senior partner — Jura adapts to how you work.
```

---

### Persona Cards (2×4 grid on desktop, scrollable on mobile):

**Card 1 — Litigation Lawyer**
- Icon: ⚖️ Scale icon
- Heading: "Litigation Lawyers"
- Body: "Draft court documents in seconds, research case law with natural language, and get procedural guidance for any Nigerian court. Spend less time on paperwork, more time on strategy."
- Key Feature: "Draft a Writ of Summons in 30 seconds"

**Card 2 — Junior Associate**
- Icon: 🎓 GraduationCap icon
- Heading: "Junior Associates"
- Body: "Access guided templates, AI-suggested authorities, and step-by-step court procedure guides. Build confidence with verified citations and senior-reviewed workflows."
- Key Feature: "AI-guided drafting with citation verification"

**Card 3 — Senior Partner**
- Icon: 👔 UserCheck icon
- Heading: "Senior Partners"
- Body: "Review and approve documents with multi-level approval chains, track firm-wide usage analytics, and ensure quality with inline comments and track changes."
- Key Feature: "Approval workflows and firm analytics"

**Card 4 — Corporate Counsel**
- Icon: 🏢 Building icon
- Heading: "Corporate Counsel"
- Body: "Monitor compliance deadlines, generate corporate documents, and draft contracts — all with automated alerts for CAC filings, tax deadlines, and regulatory changes."
- Key Feature: "Automated compliance monitoring for 20+ companies"

**Card 5 — Judge / Judicial Researcher**
- Icon: 🏛️ Landmark icon
- Heading: "Judges & Researchers"
- Body: "Analyze case summaries, identify conflicting precedents, map legal issues, and trace citation networks across Nigerian jurisprudence."
- Key Feature: "Precedent analysis and conflicting authority detection"

**Card 6 — Government Legal Officer**
- Icon: 🏛️ Flag icon
- Heading: "Government Legal Officers"
- Body: "Draft policy documents, check regulatory compliance, and generate legal opinions grounded in Nigerian statutes and case law."
- Key Feature: "Policy drafting with statutory grounding"

**Card 7 — Law Firm Administrator**
- Icon: 📊 BarChart icon
- Heading: "Firm Administrators"
- Body: "Manage team access, track usage across the firm, handle centralized billing, and maintain firm-wide templates and branding artifacts."
- Key Feature: "Centralized billing and team management"

**Card 8 — Law Student**
- Icon: 📖 BookOpen icon
- Heading: "Law Students"
- Body: "Learn court procedures, explore document templates, research case law for assignments, and understand how legal documents are structured — with AI as your study partner."
- Key Feature: "Court procedure guides and research tools"

### Card Design:
- White background, rounded-xl, border slate-100, padding 24px
- Hover: shadow-medium, translateY(-2px)
- Icon: 40px, in colored circle matching persona theme
- Heading: 18px bold, slate-900
- Body: 14px, slate-500
- Key Feature: 13px, indigo-600, italic, with small arrow icon

---

## 11. Pricing Section

**Layout:** White background. Max-width 1200px centered. Padding 120px vertical.

### Section Header:

**Overline:**
```
PRICING
```
- Style: 12px uppercase, tracking-widest, indigo-600, semibold

**Headline:**
```
Simple, transparent pricing
```
- Style: Space Grotesk, 36px bold, slate-900, centered

**Subheadline:**
```
Start free. Scale as you grow. No hidden fees, no surprises.
```
- Style: Inter, 18px, slate-500, centered

---

### Toggle Controls (centered, above cards):

**Currency Toggle:**
```
[NGN ₦] | [USD $]
```
- Segmented control, rounded-full, slate-100 background
- Active segment: white background, shadow-sm, slate-900 text
- Inactive: slate-500 text
- Default: NGN (auto-detected by location, fallback to NGN)
- Switching instantly updates all prices below

**Billing Toggle:**
```
[Monthly] | [Annual — Save 20%]
```
- Segmented control, same style as currency
- "Save 20%" badge: small indigo pill badge attached to "Annual" option
- Default: Monthly

---

### Pricing Cards (3 columns, gap-24px, equal height):

---

#### Card 1 — Starter

**Badge:** None (or subtle "For Individuals" label)

**Plan Name:**
```
Starter
```
- Style: Space Grotesk, 20px bold, slate-900

**Price (NGN Monthly):**
```
₦15,000
/month
```
- Price: Space Grotesk, 48px bold, slate-900
- Period: Inter, 14px, slate-400

**Price (NGN Annual):**
```
₦12,000
/month — billed ₦144,000/year
```

**Price (USD Monthly):**
```
$15
/month
```

**Price (USD Annual):**
```
$12
/month — billed $144/year
```

**Description:**
```
Everything you need to get started with AI-powered legal work.
```
- Style: Inter, 14px, slate-500

**Feature List:**
- ✓ 30 document generations/month
- ✓ 50 legal research queries/month
- ✓ Court procedure guide — Unlimited
- ✓ 5 GB document storage
- ✓ 1 user
- ✓ Standard AI model
- ✓ Basic templates
- ✓ DOCX + PDF export
- ✓ Basic citation verification
- ✓ Email support

**CTA Button:**
```
"Get Started Free"
```
- Style: Outlined button, slate-900 border, slate-900 text, rounded-xl, full-width, 48px height
- Hover: filled slate-900, white text

**Card Design:**
- White background, rounded-2xl, border slate-200, padding 32px
- No special highlight

---

#### Card 2 — Professional (HIGHLIGHTED / RECOMMENDED)

**Badge:**
```
✦ Most Popular
```
- Indigo pill badge, top-center of card, overlapping top border
- White text on indigo background, 12px semibold

**Plan Name:**
```
Professional
```
- Style: Space Grotesk, 20px bold, slate-900

**Price (NGN Monthly):**
```
₦50,000
/month
```

**Price (NGN Annual):**
```
₦40,000
/month — billed ₦480,000/year
```

**Price (USD Monthly):**
```
$50
/month
```

**Price (USD Annual):**
```
$40
/month — billed $480/year
```

**Description:**
```
For growing firms that need collaboration, compliance, and advanced AI.
```

**Feature List:**
- ✓ 150 document generations/month
- ✓ 200 legal research queries/month
- ✓ Court procedure guide — Unlimited
- ✓ 20 case strategy analyses/month
- ✓ 25 GB document storage
- ✓ Up to 5 users
- ✓ Advanced AI model
- ✓ All templates + custom templates
- ✓ Full citation verification
- ✓ Document review & collaboration
- ✓ Matter management (50 active)
- ✓ Firm branding (letterhead, stamp, signatures)
- ✓ Compliance monitoring (1 company)
- ✓ Priority email + chat support

**CTA Button:**
```
"Get Started Free"
```
- Style: Filled indigo button, white text, rounded-xl, full-width, 48px height
- Hover: deeper indigo, scale 1.02

**Card Design:**
- White background, rounded-2xl, **indigo border (2px)**, padding 32px
- Subtle indigo shadow glow
- Slightly elevated (translateY -4px or scale 1.02) compared to other cards

---

#### Card 3 — Enterprise

**Badge:**
```
For Large Firms & Corporates
```
- Slate-600 text, no background, 12px

**Plan Name:**
```
Enterprise
```
- Style: Space Grotesk, 20px bold, slate-900

**Price (NGN Monthly):**
```
₦200,000
/month
```

**Price (NGN Annual):**
```
₦160,000
/month — billed ₦1,920,000/year
```

**Price (USD Monthly):**
```
$200
/month
```

**Price (USD Annual):**
```
$160
/month — billed $1,920/year
```

**Description:**
```
Unlimited power for firms that demand the best. Dedicated support, API access, and custom integrations.
```

**Feature List:**
- ✓ Unlimited document generations
- ✓ Unlimited legal research
- ✓ Unlimited case strategy analyses
- ✓ Compliance monitoring (up to 20 companies)
- ✓ 100 GB document storage
- ✓ Up to 25 users (add more at ₦5,000/user/month)
- ✓ Premium AI model (fastest, most capable)
- ✓ All templates + sharing across firm
- ✓ Advanced approval workflows
- ✓ Unlimited matter management
- ✓ API access
- ✓ SSO (SAML 2.0)
- ✓ Custom branding
- ✓ Audit logs & data export
- ✓ Dedicated account manager
- ✓ Phone + email + chat support
- ✓ 99.9% uptime SLA
- ✓ Onboarding training (2 sessions)

**CTA Button:**
```
"Contact Sales"
```
- Style: Outlined indigo button, indigo text, rounded-xl, full-width, 48px height
- Hover: filled indigo, white text

**Card Design:**
- White background, rounded-2xl, border slate-200, padding 32px

---

### Below Pricing Cards:

**Custom / Government Tier Banner:**
```
┌─────────────────────────────────────────────────────────────────┐
│  🏛️  Need a custom plan for your government agency or          │
│      large institution?                                         │
│                                                                 │
│  We offer custom pricing with unlimited users, on-premise       │
│  deployment, dedicated infrastructure, and regulatory           │
│  compliance certifications.                                     │
│                                                                 │
│  [Contact Our Enterprise Team →]                                │
└─────────────────────────────────────────────────────────────────┘
```
- Style: Slate-50 background, rounded-2xl, border slate-200, padding 32px, centered text
- CTA: indigo text link with arrow

**Add-on Pricing Note:**
```
Need more? Add extra capacity anytime.
```
- Style: 14px, slate-500, centered

| Add-on | Price (NGN) | Price (USD) |
|--------|-------------|-------------|
| Additional documents | ₦500/document | $0.50/document |
| Additional storage | ₦1,000/GB/month | $1.00/GB/month |
| Additional team members | ₦5,000/member/month | $5.00/member/month |

- Style: Small table or inline text, 13px, slate-400

---

### Feature Comparison Table (expandable):

**Toggle:** "Compare all features" — click to expand full comparison table

| Feature | Starter | Professional | Enterprise |
|---------|---------|-------------|------------|
| Document generations | 30/month | 150/month | Unlimited |
| Legal research queries | 50/month | 200/month | Unlimited |
| Case strategy analyses | — | 20/month | Unlimited |
| Court procedure guide | Unlimited | Unlimited | Unlimited |
| Document storage | 5 GB | 25 GB | 100 GB |
| Users | 1 | Up to 5 | Up to 25+ |
| AI model tier | Standard | Advanced | Premium |
| Custom templates | — | ✓ | ✓ |
| Citation verification | Basic | Full | Full |
| Document collaboration | — | ✓ | ✓ |
| Review & approval workflows | — | — | ✓ |
| Matter management | — | 50 active | Unlimited |
| Firm branding artifacts | — | ✓ | ✓ |
| Compliance monitoring | — | 1 company | 20 companies |
| API access | — | — | ✓ |
| SSO (SAML 2.0) | — | — | ✓ |
| Audit logs | — | — | ✓ |
| Dedicated account manager | — | — | ✓ |
| Uptime SLA | 99.5% | 99.5% | 99.9% |
| Support | Email | Priority email + chat | Phone + email + chat |

---

## 12. Testimonials & Social Proof

**Layout:** Slate-50 background. Max-width 1200px centered. Padding 120px vertical.

### Section Header:

**Overline:**
```
WHAT LAWYERS ARE SAYING
```

**Headline:**
```
Trusted by legal professionals across Nigeria
```
- Style: Space Grotesk, 36px bold, slate-900, centered

---

### Testimonial Cards (3 columns, or horizontal carousel on mobile):

**Testimonial 1:**
```
"Jura has completely transformed how our firm handles litigation drafting. 
What used to take a junior associate 4 hours now takes 30 seconds — and 
the citations are actually verified. We've reduced our document turnaround 
time by 85%."
```
- **Name:** Barr. Oluwaseun Adeyemi
- **Title:** Managing Partner, Adeyemi & Associates
- **Location:** Lagos, Nigeria
- **Avatar:** Professional headshot placeholder (circle, 48px)
- **Star Rating:** ★★★★★

**Testimonial 2:**
```
"The compliance monitoring alone is worth the subscription. We manage 
12 companies and Jura alerts us before every CAC deadline. We haven't 
missed a filing since we started using it."
```
- **Name:** Barr. Amina Ibrahim
- **Title:** Head of Legal, Zenith Holdings
- **Location:** Abuja, Nigeria
- **Avatar:** Professional headshot placeholder
- **Star Rating:** ★★★★★

**Testimonial 3:**
```
"As a young lawyer, Jura is like having a senior associate guiding me 
through every court procedure. The step-by-step guides and citation 
verification give me confidence that my filings are correct."
```
- **Name:** Barr. Chukwuemeka Obi
- **Title:** Associate, Obi & Partners
- **Location:** Enugu, Nigeria
- **Avatar:** Professional headshot placeholder
- **Star Rating:** ★★★★★

### Card Design:
- White background, rounded-2xl, padding 32px, shadow-subtle
- Quote text: Inter, 16px, slate-700, italic, line-height 1.7
- Opening quotation mark: Space Grotesk, 48px, indigo-200, decorative
- Name: 16px bold, slate-900
- Title + Location: 13px, slate-500
- Star rating: amber-400 filled stars

---

### Logo Bar (below testimonials):

**Label:**
```
Trusted by leading firms and institutions
```
- Style: 13px, slate-400, centered

**Logos:** Row of 6–8 grayscale logos of Nigerian law firms, corporate legal departments, and institutions
- 40px height, evenly spaced, opacity 0.4, hover: opacity 1.0
- Placeholder names: Aluko & Oyebode, Banwo & Ighodalo, Udo Udoma & Belo-Osagie, Templars, SPA Ajibade, ACAS-Law, Olaniwun Ajayi LP, G. Elias & Co.

---

## 13. Security & Compliance Section

**Layout:** White background. Max-width 1200px centered. Padding 120px vertical.

### Section Header:

**Overline:**
```
SECURITY & PRIVACY
```

**Headline:**
```
Enterprise-grade security for sensitive legal data
```
- Style: Space Grotesk, 36px bold, slate-900, centered

**Subheadline:**
```
Your client data is protected with the same standards used by global 
financial institutions. We take data protection seriously — because 
your clients trust you, and you need to trust your tools.
```
- Style: Inter, 18px, slate-500, centered, max-width 640px

---

### Security Feature Grid (3×2, gap-24px):

**Feature 1 — Encryption**
- Icon: 🔐 Lock icon (indigo circle)
- Heading: "End-to-end encryption"
- Body: "All data encrypted at rest (AES-256) and in transit (TLS 1.3). Your documents, client information, and firm artifacts are protected at every layer."

**Feature 2 — NDPR Compliance**
- Icon: 🇳🇬 Shield icon (green circle)
- Heading: "NDPR compliant"
- Body: "Full compliance with the Nigeria Data Protection Regulation (NDPR) and GDPR standards. Your data stays protected under Nigerian and international privacy law."

**Feature 3 — Access Control**
- Icon: 👥 Users icon (indigo circle)
- Heading: "Role-based access control"
- Body: "Granular permissions for Owner, Admin, Member, and Viewer roles. Control who can generate, review, approve, and delete documents across your organization."

**Feature 4 — Audit Logging**
- Icon: 📋 ClipboardList icon (indigo circle)
- Heading: "Complete audit trail"
- Body: "Every action is logged — document generations, edits, shares, downloads, and access events. Full audit trail for regulatory compliance and internal governance."

**Feature 5 — Secure File Handling**
- Icon: 🛡️ ShieldCheck icon (indigo circle)
- Heading: "Virus scanning & file validation"
- Body: "Every uploaded file is scanned with ClamAV antivirus, validated by magic bytes (not just extension), and stripped of EXIF metadata before storage on encrypted AWS S3."

**Feature 6 — MFA & Session Security**
- Icon: 🔑 Key icon (indigo circle)
- Heading: "Multi-factor authentication"
- Body: "Optional TOTP-based MFA with Google Authenticator or Authy. Enforced for Enterprise accounts. Session management with concurrent device limits and remote revocation."

---

### Compliance Badges Row (centered, below grid):
- NDPR Compliant badge
- GDPR Ready badge
- SOC 2 (Planned) badge
- AES-256 Encryption badge
- 99.9% Uptime SLA badge

Style: Small pill badges, slate-100 background, slate-600 text, 12px, with small icon per badge

---

## 14. Integration & Technology Section

**Layout:** Slate-50 background. Max-width 1200px centered. Padding 80px vertical.

### Section Header:

**Headline:**
```
Powered by world-class technology
```
- Style: Space Grotesk, 28px bold, slate-900, centered

**Subheadline:**
```
Built on proven infrastructure trusted by enterprises worldwide.
```
- Style: Inter, 16px, slate-500, centered

---

### Technology Logo Row (centered, horizontal):

Logos displayed in a single row with subtle grayscale treatment:

| Technology | Logo | Purpose |
|-----------|------|---------|
| AWS | AWS logo | Cloud infrastructure |
| Anthropic | Anthropic logo | Primary AI model (Claude) |
| OpenAI | OpenAI logo | Fallback AI + embeddings |
| Google | Google AI logo | Tertiary AI model (Gemini) |
| MongoDB | MongoDB logo | Primary database |
| Paystack | Paystack logo | Nigerian payments |
| Stripe | Stripe logo | International payments |
| Netlify | Netlify logo | Frontend hosting |

- Logo height: 32px, grayscale, opacity 0.5
- Hover: full color, opacity 1.0
- Spacing: 48px between logos
- Mobile: 2 rows of 4

---

## 15. FAQ Section

**Layout:** White background. Max-width 800px centered. Padding 120px vertical.

### Section Header:

**Headline:**
```
Frequently asked questions
```
- Style: Space Grotesk, 36px bold, slate-900, centered

---

### FAQ Accordion (expandable items, one open at a time):

**Q1: What is Jura AI?**
```
Jura AI is an enterprise-grade legal intelligence platform built for Nigerian 
legal professionals. It combines AI-powered document generation, case law 
research, court procedure guidance, case strategy analysis, and corporate 
compliance monitoring — all grounded in verified Nigerian law databases. 
It's not a chatbot. It's a complete legal workflow system.
```

**Q2: How accurate are the citations in generated documents?**
```
Every citation in every document generated by Jura is verified against our 
Nigerian law database. Each case reference and statute section is cross-checked 
and classified as Verified, Partial Match, or Not Found. Our current citation 
verification accuracy is 99.7%. Any unverified citations are clearly flagged 
so you can review them before filing.
```

**Q3: What types of legal documents can Jura generate?**
```
Jura currently supports 18+ document types across litigation, corporate, 
contracts, compliance, and advisory categories. This includes Writs of 
Summons, Statements of Claim and Defence, Originating Summons and Motions, 
Affidavits, Written Addresses, Demand Letters, NDAs, Employment Contracts, 
MOUs, Tenancy Agreements, Board Resolutions, Powers of Attorney, Petitions, 
Legal Opinions, and CAC Incorporation Documents. We add new document types 
regularly.
```

**Q4: Is my data secure?**
```
Absolutely. All data is encrypted at rest (AES-256) and in transit (TLS 1.3). 
We comply with the Nigeria Data Protection Regulation (NDPR) and GDPR 
standards. Files are virus-scanned before storage, and we maintain complete 
audit logs of all access and actions. Enterprise accounts get enforced MFA, 
SSO, and dedicated infrastructure options.
```

**Q5: Can I use my firm's letterhead and branding?**
```
Yes. During onboarding, you upload your firm's letterhead, logo, digital 
stamp/seal, authorized signatures, and legal stationery template. Jura 
automatically applies these to every generated document — court headers, 
signature blocks, and stamp placements are all handled for you.
```

**Q6: How does pricing work?**
```
We offer three tiers: Starter (₦15,000/month for individuals), Professional 
(₦50,000/month for small firms up to 5 users), and Enterprise (₦200,000/month 
for large firms up to 25+ users). Annual billing saves 20%. All plans include 
a free trial period. We also offer custom pricing for government agencies 
and large institutions. You can pay in Naira via Paystack or USD via Stripe.
```

**Q7: What payment methods do you accept?**
```
For Naira (NGN) payments: Nigerian debit/credit cards (Verve, Mastercard, 
Visa), bank transfer, and USSD — all via Paystack. For international (USD) 
payments: international cards via Stripe. Currency is auto-detected based 
on your location, and you can switch between NGN and USD at any time.
```

**Q8: Can my team collaborate on documents?**
```
Yes. Professional and Enterprise plans include real-time collaboration 
features — multiple team members can view and edit documents simultaneously 
with live cursor tracking and presence indicators. You can assign reviewers, 
add inline comments, track changes, and set up multi-level approval chains 
(Junior → Senior → Partner).
```

**Q9: Does Jura work offline?**
```
Jura is a Progressive Web App (PWA) with offline caching support. You can 
access previously loaded documents and templates offline. However, document 
generation, legal research, and other AI-powered features require an internet 
connection as they rely on our AI infrastructure and legal databases.
```

**Q10: What Nigerian courts and jurisdictions are supported?**
```
Jura supports all Nigerian courts including the Supreme Court, Court of 
Appeal, Federal High Court, all 36 State High Courts plus FCT, National 
Industrial Court, Sharia Court of Appeal, Customary Court of Appeal, 
Magistrate Courts, and other tribunals. Court-specific formatting rules, 
filing procedures, and fee schedules are built into the platform.
```

**Q11: Is Jura available outside Nigeria?**
```
Jura is currently focused on the Nigerian legal system. We're building 
support for Ghana, Kenya, and South Africa as part of our expansion 
roadmap. If you're interested in early access for another African 
jurisdiction, contact us at hello@jura.africa.
```

**Q12: Can I cancel my subscription anytime?**
```
Yes. You can cancel your subscription at any time from your billing 
settings. You'll retain access until the end of your current billing 
period. We also offer a 30-day pause option (once per year) if you 
need a temporary break. There are no cancellation fees.
```

### FAQ Design:
- Each item: border-bottom slate-100, padding 24px vertical
- Question: Inter, 16px semibold, slate-900, with chevron-down icon (right)
- Answer: Inter, 15px regular, slate-600, line-height 1.7
- Open state: chevron rotates 180°, answer slides down with 300ms ease
- Only one item open at a time (accordion behavior)

---

## 16. CTA Banner Section

**Layout:** Full-width, indigo gradient background (indigo-600 to purple-600, diagonal). Max-width 1200px content centered. Padding 80px vertical.

### Content (centered):

**Headline:**
```
Ready to transform your legal practice?
```
- Style: Space Grotesk, 36px bold, white

**Subheadline:**
```
Join 500+ Nigerian law firms already using Jura to draft faster, 
research smarter, and never miss a compliance deadline.
```
- Style: Inter, 18px, indigo-100 (light), max-width 560px, centered

**CTA Row (centered, gap-16px):**

| Button | Label | Style |
|--------|-------|-------|
| Primary | "Get Started Free" | White filled, indigo-600 text, rounded-full, 16px semibold, px-8 py-4, hover: scale 1.05 |
| Secondary | "Request a Demo" | White outlined (border white), white text, rounded-full, 16px medium, px-8 py-4, hover: white filled, indigo text |

**Below CTAs:**
```
No credit card required · Free plan available · Setup in under 5 minutes
```
- Style: 13px, indigo-200, centered
- Separator dots between items

---

## 17. Footer

**Layout:** Dark background (slate-900). Padding 64px top, 32px bottom. Full-width, content max-width 1200px centered.

### Footer Content:

**Top Row — 4-column grid (desktop), stacked (mobile):**

**Column 1 — Brand:**
- Jura AI logo (white version)
- Tagline: "Legal Intelligence for Africa" — 14px, slate-400
- Social icons row (24px, slate-400, hover: white):
  - LinkedIn icon → https://linkedin.com/company/jura-ai
  - X (Twitter) icon → https://x.com/jura_ai
  - Instagram icon → https://instagram.com/jura.ai

**Column 2 — Product:**
- Column heading: "Product" — 14px semibold, slate-300
- Links (14px, slate-400, hover: white):
  - Features
  - Document Generation
  - Legal Research
  - Compliance Monitoring
  - Case Strategy
  - Court Procedures
  - Template Library
  - Pricing

**Column 3 — Company:**
- Column heading: "Company" — 14px semibold, slate-300
- Links:
  - About Us
  - Blog
  - Careers
  - Press Kit
  - Contact Us
  - Partners

**Column 4 — Legal & Support:**
- Column heading: "Legal" — 14px semibold, slate-300
- Links:
  - Terms of Service
  - Privacy Policy
  - Cookie Policy
  - Data Processing Agreement
  - Acceptable Use Policy
  - Help Center
  - API Documentation
  - System Status

---

### Bottom Row (border-top slate-800, padding-top 24px):

**Left:**
```
© 2026 Jura AI. All rights reserved. ISHAQ MAGAJI SAN & Co.
```
- Style: 13px, slate-500

**Center:**
```
Built in Nigeria 🇳🇬
```
- Style: 13px, slate-400, with Nigerian flag emoji
- Subtle pride indicator — this is a differentiator

**Right:**
- Country selector: "🇳🇬 Nigeria" dropdown (same as nav, shows coming soon countries)
- Language: "English" (default, future: Hausa, Yoruba, Igbo)

---

## 18. SEO Metadata

### Page Title:
```
Jura AI — Legal Intelligence & Document Generation for Africa | jura.africa
```

### Meta Description:
```
AI-powered legal document generation, case law research, and compliance 
monitoring for Nigerian legal professionals. Draft court-ready documents 
in 30 seconds with verified citations. Trusted by 500+ law firms.
```

### Open Graph Tags:
```html
<meta property="og:title" content="Jura AI — Legal Intelligence for Africa" />
<meta property="og:description" content="AI-powered legal document generation, case law research, and compliance monitoring — purpose-built for Nigerian legal professionals." />
<meta property="og:image" content="https://jura.africa/og-image.png" />
<meta property="og:url" content="https://jura.africa" />
<meta property="og:type" content="website" />
<meta property="og:site_name" content="Jura AI" />
```

### Twitter Card:
```html
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:site" content="@jura_ai" />
<meta name="twitter:title" content="Jura AI — Legal Intelligence for Africa" />
<meta name="twitter:description" content="Draft court-ready legal documents in 30 seconds with verified Nigerian case law citations." />
<meta name="twitter:image" content="https://jura.africa/twitter-card.png" />
```

### Structured Data (JSON-LD):
```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Jura AI",
  "description": "AI-powered legal intelligence, document generation, and compliance monitoring platform for Nigerian legal professionals.",
  "url": "https://jura.africa",
  "applicationCategory": "LegalService",
  "operatingSystem": "Web",
  "offers": {
    "@type": "AggregateOffer",
    "lowPrice": "15",
    "highPrice": "200",
    "priceCurrency": "USD",
    "offerCount": "3"
  },
  "author": {
    "@type": "Organization",
    "name": "ISHAQ MAGAJI SAN & Co.",
    "url": "https://jura.africa"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.9",
    "ratingCount": "500"
  }
}
```

### Canonical URL:
```html
<link rel="canonical" href="https://jura.africa" />
```

### Additional Meta:
```html
<meta name="robots" content="index, follow" />
<meta name="theme-color" content="#4F46E5" />
<meta name="apple-mobile-web-app-title" content="Jura AI" />
<link rel="manifest" href="/manifest.json" />
```

---

## 19. Micro-copy & UI Labels

### Navigation Labels:
| Element | Copy |
|---------|------|
| Logo alt text | "Jura AI — Legal Intelligence for Africa" |
| Features link | "Features" |
| Documents link | "Documents" |
| Pricing link | "Pricing" |
| About link | "About" |
| Blog link | "Blog" |
| Login button | "Log In" |
| Signup button | "Get Started" |
| Country selector label | "Select country" |
| Coming soon tooltip | "Coming soon — we're expanding across Africa" |

### Hero Section Labels:
| Element | Copy |
|---------|------|
| Overline badge | "✦ Legal Intelligence for Africa" |
| Primary CTA | "Get Started Free" |
| Secondary CTA | "▶ Watch Demo" |
| Trust line | "Trusted by 500+ Nigerian law firms and legal departments" |

### Pricing Labels:
| Element | Copy |
|---------|------|
| Currency toggle NGN | "NGN ₦" |
| Currency toggle USD | "USD $" |
| Billing monthly | "Monthly" |
| Billing annual | "Annual" |
| Annual savings badge | "Save 20%" |
| Starter CTA | "Get Started Free" |
| Professional CTA | "Get Started Free" |
| Enterprise CTA | "Contact Sales" |
| Custom tier CTA | "Contact Our Enterprise Team →" |
| Compare features toggle | "Compare all features ↓" |
| Per month label | "/month" |
| Annual billing note | "billed [amount]/year" |

### Footer Labels:
| Element | Copy |
|---------|------|
| Built in badge | "Built in Nigeria 🇳🇬" |
| Copyright | "© 2026 Jura AI. All rights reserved." |
| Company attribution | "ISHAQ MAGAJI SAN & Co." |

### Toast / Notification Copy:
| Trigger | Copy |
|---------|------|
| Demo video loading | "Loading demo..." |
| Email submitted (newsletter) | "Thanks! We'll keep you updated." |
| Contact form submitted | "Message sent. We'll get back to you within 24 hours." |
| Error state | "Something went wrong. Please try again." |

### Accessibility Labels:
| Element | ARIA Label |
|---------|-----------|
| Navigation | "Main navigation" |
| Logo link | "Jura AI home" |
| Currency toggle | "Switch currency between Nigerian Naira and US Dollar" |
| Billing toggle | "Switch between monthly and annual billing" |
| FAQ accordion item | "Toggle answer for: [question text]" |
| Social links | "Follow Jura AI on [platform]" |
| Scroll to section | "Navigate to [section name]" |
| Mobile menu button | "Open navigation menu" |
| Close modal | "Close dialog" |
| Play demo video | "Play product demo video" |

---

## 20. Content Guidelines & Tone

### Brand Voice:
- **Authoritative but approachable:** We know Nigerian law. We speak to lawyers as peers, not students.
- **Precise and factual:** No vague claims. Every stat is backed. Every feature is real.
- **Confident without arrogance:** We're proud of what we've built, but we let the product speak.
- **Nigerian-first:** We reference Nigerian courts, Nigerian law, Nigerian practice. This isn't a US product with a Nigerian skin.

### Writing Rules:
1. **Lead with the benefit, not the feature.** "Draft a Writ of Summons in 30 seconds" not "AI-powered document generation engine."
2. **Use specific numbers.** "18+ document types" not "many document types." "99.7% accuracy" not "high accuracy."
3. **Keep headlines short and punchy.** Max 8 words for section headlines. Use Space Grotesk for impact.
4. **Subheadlines explain, headlines intrigue.** The headline grabs attention; the subheadline delivers the detail.
5. **Use Nigerian legal terminology.** "Writ of Summons" not "Complaint." "Statement of Claim" not "Petition." "Barrister" not "Attorney."
6. **Avoid jargon in marketing copy.** RAG, embeddings, knowledge graphs — these belong in the technical docs, not the landing page. Exception: the AI Intelligence section can use technical terms with plain-English explanations.
7. **Every section has a clear CTA.** Don't let the user scroll without knowing what to do next.
8. **Social proof is specific.** "500+ Nigerian law firms" not "many customers." Named testimonials with real titles and locations.

### Tone Spectrum:
| Section | Tone |
|---------|------|
| Hero | Bold, confident, aspirational |
| Feature cards | Clear, informative, benefit-focused |
| Document types | Precise, professional, comprehensive |
| How it works | Simple, reassuring, step-by-step |
| AI Intelligence | Technical but accessible, impressive |
| Pricing | Transparent, straightforward, fair |
| Testimonials | Authentic, relatable, trustworthy |
| Security | Serious, reassuring, thorough |
| FAQ | Helpful, conversational, complete |
| CTA Banner | Urgent but not pushy, inviting |
| Footer | Professional, complete, trustworthy |

### Typography Usage:
| Context | Font | Weight | Size Range |
|---------|------|--------|------------|
| Section headlines | Space Grotesk | Bold (700) | 28–60px |
| Overline labels | Inter or Space Grotesk | Semibold (600) | 12px uppercase |
| Subheadlines | Inter | Regular (400) | 16–20px |
| Body copy | Inter | Regular (400) | 14–16px |
| Card headings | Space Grotesk | Bold (700) | 18–20px |
| Card body | Inter | Regular (400) | 13–14px |
| Buttons | Inter | Semibold (600) | 14–16px |
| Labels & badges | Inter | Medium (500) | 10–13px |
| Stats/numbers | Space Grotesk | Bold (700) | 36–48px |

### Color Usage on Landing Page:
| Element | Color |
|---------|-------|
| Primary buttons | Indigo #4F46E5 |
| Secondary buttons | Slate-900 #0F172A or outlined |
| Headlines | Slate-900 #0F172A |
| Body text | Slate-500 #64748B |
| Overline labels | Indigo-600 #4F46E5 |
| Background sections | Alternating white / slate-50 #F8F9FA |
| Dark section (AI) | Slate-900 #0F172A |
| CTA banner | Indigo gradient (indigo-600 → purple-600) |
| Footer | Slate-900 #0F172A |
| Success/verified | Emerald-500 #10B981 |
| Warning/partial | Amber-500 #F59E0B |
| Error/not found | Red-500 #EF4444 |
| Links | Indigo-600 #4F46E5 |

---

## Appendix A: Alternative Headlines (A/B Testing Options)

### Hero Headlines:
1. "Draft. Research. Comply. All in one platform." ← **Primary**
2. "The operating system for legal work in Africa."
3. "Legal intelligence that thinks like a lawyer."
4. "Court-ready documents in 30 seconds."
5. "AI-powered legal work. Nigerian law. Verified citations."
6. "Your AI legal associate. Always on. Always accurate."

### Hero Subheadlines:
1. "AI-powered legal document generation, case law research, and compliance monitoring — purpose-built for Nigerian legal professionals." ← **Primary**
2. "Generate court-ready documents, research case law with natural language, and monitor compliance deadlines — all grounded in verified Nigerian law."
3. "From Writs of Summons to compliance alerts — Jura handles the legal heavy lifting so you can focus on strategy."

### CTA Variations:
1. "Get Started Free" ← **Primary**
2. "Start Drafting for Free"
3. "Try Jura Free"
4. "Create Your First Document"
5. "Start Your Free Trial"

---

## Appendix B: Content Checklist

Before launch, verify the following content is complete and approved:

- [ ] All section headlines and subheadlines finalized
- [ ] All 18 document type card descriptions reviewed by legal team
- [ ] Pricing tiers confirmed with finance team
- [ ] Testimonials collected and approved (with consent)
- [ ] Law firm logos collected (with permission to display)
- [ ] Stats verified (500+ firms, 50,000+ documents, 99.7% accuracy, 85% time reduction)
- [ ] FAQ answers reviewed by legal and product teams
- [ ] SEO metadata approved
- [ ] All ARIA labels and accessibility copy in place
- [ ] Nigerian legal terminology verified by practicing lawyer
- [ ] Currency conversion rates confirmed
- [ ] Social media links active
- [ ] Demo video produced and hosted
- [ ] OG image and Twitter card image designed
- [ ] Mobile responsive copy reviewed (no truncation issues)
- [ ] All CTAs link to correct destinations (/register, /login, /contact)
- [ ] Footer links all point to live pages
- [ ] Cookie consent banner copy approved
- [ ] Privacy policy and terms of service published

---

## Appendix C: Page Performance Targets

| Metric | Target |
|--------|--------|
| First Contentful Paint (FCP) | < 1.5s |
| Largest Contentful Paint (LCP) | < 2.5s |
| Cumulative Layout Shift (CLS) | < 0.1 |
| First Input Delay (FID) | < 100ms |
| Total page weight | < 2MB |
| Image optimization | WebP/AVIF with fallbacks |
| Font loading | Font-display: swap, preload critical fonts |
| Above-the-fold content | Renders without JavaScript |
| Lighthouse score | > 90 (Performance, Accessibility, SEO) |

---

*End of Landing Page Content & Copy Document*
