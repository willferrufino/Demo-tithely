# Tithely Website Redesign + CRO Prototype


A three-page website redesign and front-end prototype exploring how Tithely's key marketing experiences could be made easier to understand, more interactive, and more conversion-focused.

Rather than simply restyling the existing pages, I approached the project from the perspective of a **Senior Website Designer working across UX, CRO, front-end development, and experimentation**.

The goal was to improve three important stages of the customer journey:

**Understand the product → Choose the right plan → Feel confident choosing Tithely**

Each concept was designed and developed directly in the browser using **HTML, CSS, and JavaScript**, with additional consideration for responsive design, accessibility, SEO, performance, analytics, and future A/B testing.

---

# 01. Online Giving

### [View Live Demo →](https://willferrufino.github.io/Demo-tithely/tithely-online-giving.html)

**File:** [`tithely-online-giving.html`](./tithely-online-giving.html)

## The Opportunity

Tithely Online Giving has a strong value proposition: churches can begin accepting digital donations without a monthly platform fee.

The redesign focuses on making that benefit immediately understandable while showing visitors what the actual giving experience feels like.

Instead of relying primarily on feature descriptions, I wanted visitors to be able to **experience the simplicity of the product directly on the page**.

## What I Improved

- Simplified the hero around the strongest value proposition.
- Created a clearer hierarchy between primary and secondary CTAs.
- Reduced visual complexity and improved content scanning.
- Reorganized features around donor and church-admin benefits.
- Strengthened recurring-giving messaging.
- Made pricing and transaction information easier to understand.
- Added stronger trust, security, and social-proof elements.
- Improved typography, spacing, responsive behavior, and visual hierarchy.
- Introduced a restrained Tithely-inspired mint, coral, and orange visual system.

## Interactive Product Experience

One of the biggest changes is an interactive giving walkthrough built directly into the page.

Visitors can move through a simulated church donation experience, select a giving amount, see the form update, and reach a successful donation state.

This turns a product feature into something the visitor can actually understand through interaction.

Additional front-end features include:

- Interactive donation amount selector.
- Multi-step giving walkthrough.
- Donation success state.
- Recurring-giving estimator.
- FAQ accordion.
- Sticky conversion navigation.
- Scroll-triggered content reveals.
- Responsive mobile giving interface.
- JavaScript interaction tracking.
- Reduced-motion accessibility support.

## CRO Approach

The original product information was reorganized into a more deliberate conversion journey:

**Value → Experience → Benefits → Trust → Pricing → Conversion**

Rather than asking visitors to imagine what Tithely Giving is like, the prototype demonstrates it.

---

# 02. Pricing

### [View Live Demo →](https://willferrufino.github.io/Demo-tithely/tithely-pricing-redesign.html)

**File:** [`tithely-pricing-redesign.html`](./tithely-pricing-redesign.html)

## The Opportunity

Pricing pages can quickly become overwhelming when customers are presented with multiple plans, transaction rates, standalone products, feature matrices, and add-ons simultaneously.

The goal of this redesign was to reduce that decision fatigue.

The primary question became:

> **Which Tithely plan is right for my church?**

## What I Improved

The information architecture was reorganized around three clear primary paths:

**Free Giving**  
A simple starting point for churches primarily looking for digital giving.

**Church Management**  
For churches that need giving plus people, volunteer, communication, and administrative tools.

**All Access**  
The recommended all-in-one option for churches looking to consolidate more of their technology stack.

Enterprise and standalone products remain available but are intentionally positioned as secondary decisions.

Other improvements include:

- Simplified plan cards.
- Stronger differentiation between plans.
- More prominent All Access recommendation.
- Reduced repetitive pricing information.
- Improved feature hierarchy.
- Cleaner transaction-rate presentation.
- Better visual separation between primary plans and standalone products.
- More scannable reviews and social proof.
- Clearer conversion CTAs throughout the page.

## Interactive Plan Finder

Instead of expecting visitors to study every feature, I created an interactive JavaScript **Plan Finder**.

Visitors answer a few questions about their ministry needs and receive a recommended Tithely plan.

The recommendation dynamically updates:

- Recommended plan.
- Monthly price.
- Reasons the plan fits.
- Relevant conversion CTA.

This changes pricing from a passive comparison into a guided decision experience.

## Interactive Feature Comparison

The large feature comparison was redesigned using progressive disclosure.

Visitors can filter the table by:

- Essentials.
- Giving.
- Church administration.
- Engagement.
- Website + app.

The result is a comparison experience that provides detailed information without displaying everything simultaneously.

## Transaction Fee Calculator

I also redesigned the **Competitive Transaction Rates** experience into an interactive calculator.

Visitors can:

- Enter a donation amount.
- Select a payment method.
- See the estimated transaction fee.
- See how much the church receives.
- Toggle donor-covered fees.

This makes abstract percentages easier to understand in a real-world giving scenario.

## CRO Approach

The pricing experience changes the conversation from:

> Here are all of our plans and features.

to:

> Tell us what your church needs and we'll help you choose.

The intended journey becomes:

**Understand → Narrow → Compare → Calculate → Choose**

---

# 03. Compare Tithely

### [View Live Demo →](https://willferrufino.github.io/Demo-tithely/tithely-compare-redesign.html)

**File:** [`tithely-compare-redesign.html`](./tithely-compare-redesign.html)

## The Opportunity

Visitors reaching a competitor comparison page are typically much further into the buying process.

They already understand the category.

Now they are asking:

> **Why should our church choose Tithely?**

The redesign therefore focuses less on introducing features and more on building confidence through comparison, demonstration, social proof, and real customer experiences.

## What I Improved

- Created a stronger comparison-focused hero.
- Made Tithely's 24-second product video a prominent part of the experience.
- Simplified competitor information.
- Improved the visual hierarchy of the comparison matrix.
- Made Tithely's column easier to identify.
- Added interactive comparison filtering.
- Increased the prominence of church/customer proof.
- Added a scrolling ministry-logo marquee.
- Created a dedicated customer video-story experience.
- Improved reviews and testimonial presentation.
- Strengthened final conversion messaging.
- Added SEO pathways for visitors researching individual competitors.

## Interactive Competitor Comparison

Instead of presenting one large static comparison table, visitors can filter the information based on what matters to them:

- Pricing.
- Giving.
- Church tools.
- Administration + reporting.
- Everything.

The JavaScript filtering keeps the detailed information available while making the initial experience significantly easier to scan.

## Video-First Social Proof

Video is one of the strongest elements of Tithely's existing content, so I intentionally made it more prominent.

The redesign includes Tithely's **24-second product video** near the top of the experience and again as a major proof point later in the journey.

I also created a custom JavaScript customer-story slider using real Tithely church videos.

The slider includes:

- Real church-story thumbnails.
- Horizontal scroll-snap navigation.
- Previous / next controls.
- Slider progress indicator.
- Interactive play states.
- YouTube modal playback.
- Keyboard controls.
- Escape and backdrop modal closing.
- Responsive card sizing.
- Analytics event hooks.

The component was built without relying on an external carousel library.

## Ministry Social Proof

A continuously scrolling logo marquee highlights recognizable churches and ministries using Tithely.

The animation is intentionally subtle and includes:

- Seamless looping.
- Responsive logo sizing.
- Pause-on-hover behavior.
- Reduced-motion accessibility support.

This adds credibility immediately before the larger customer-proof portion of the page.

## SEO Strategy

The page was also structured around high-intent competitor research.

Comparison pathways include topics such as:

- Tithely vs Pushpay.
- Tithely vs Subsplash.
- Tithely vs Planning Center.
- Tithely vs PayPal.
- Tithely vs Zeffy.
- Church giving platform alternatives.

The prototype also includes:

- SEO title and meta description.
- Canonical URL.
- Open Graph metadata.
- Semantic heading structure.
- Structured data.
- Search-friendly comparison content.

## CRO Approach

Someone visiting a comparison page probably doesn't need another long product pitch.

They need evidence that switching is the right decision.

The experience therefore follows:

**Differentiate → Compare → Demonstrate → Prove → Convert**

---

# Design + Development Approach

These prototypes were treated as working web experiences rather than static design exercises.

## UX + Visual Design

- Conversion-focused information architecture.
- Responsive layouts.
- Modern typography.
- Consistent spacing systems.
- Clear visual hierarchy.
- Progressive disclosure.
- Reusable component patterns.
- Restrained animation and motion.
- Mobile-first considerations.
- Tithely-inspired visual language.

## Front-End Development

All three prototypes were built using front-end technologies including:

- HTML5.
- CSS3.
- JavaScript.
- CSS Grid.
- Flexbox.
- DOM manipulation.
- Intersection Observer.
- Dynamic UI states.
- Modals.
- Carousels.
- Calculators.
- Interactive forms.
- Responsive breakpoints.

The goal was to demonstrate the ability to move fluidly between **design thinking and working front-end implementation**.

---

# CRO + Experimentation

Another focus of the project was identifying areas that could eventually become measurable experiments rather than treating the redesign as purely visual.

Potential experiments include:

- Hero messaging.
- CTA language.
- Pricing hierarchy.
- Recommended-plan positioning.
- Interactive vs static product demonstrations.
- Social-proof placement.
- Video placement.
- Comparison-table presentation.
- Transaction-fee messaging.
- Sticky CTA behavior.

JavaScript `dataLayer` events were added around important interactions such as:

- CTA engagement.
- Donation walkthrough completion.
- Plan recommendations.
- Comparison filtering.
- Video engagement.
- Newsletter signup.

These events could be connected with tools such as **GA4, GTM, Optimizely, VWO, or similar experimentation platforms** to measure performance and support future A/B testing.

---

# Accessibility + Performance

Accessibility and front-end quality were considered throughout the prototypes.

This includes:

- Semantic HTML.
- Keyboard-accessible interactions.
- Responsive layouts.
- Accessible buttons and controls.
- `prefers-reduced-motion` support.
- Mobile-friendly touch targets.
- Lightweight vanilla JavaScript.
- No unnecessary JavaScript frameworks.
- SEO-friendly markup.
- Performance-conscious interaction patterns.

---

# Project Summary

This project was created as an exploration of how I would approach Tithely's website as a **Senior Website Designer working at the intersection of design, CRO, experimentation, and front-end development**.

The objective wasn't simply to make three pages look different.

It was to identify where visitors may experience friction, redesign those moments, and then build working prototypes that demonstrate the proposed solution.

### Online Giving
**Make the product easier to understand and experience.**

### Pricing
**Make the right plan easier to choose.**

### Compare
**Make the decision to choose Tithely easier to trust.**

Together, the three concepts demonstrate an approach centered around:

**Research → UX → Design → Prototype → Build → Measure → Iterate**

---

# View the Prototypes

| Prototype | Live Demo | Source |
|---|---|---|
| **Online Giving** | [View Live →](https://willferrufino.github.io/Demo-tithely/tithely-online-giving.html) | [`HTML`](./tithely-online-giving.html) |
| **Pricing** | [View Live →](https://willferrufino.github.io/Demo-tithely/tithely-pricing-redesign.html) | [`HTML`](./tithely-pricing-redesign.html) |
| **Compare Tithely** | [View Live →](https://willferrufino.github.io/Demo-tithely/tithely-compare-redesign.html) | [`HTML`](./tithely-compare-redesign.html) |

---

**Concept, UX, visual design, front-end development, and prototyping by William Ferrufino.**

*Independent design concept created as a portfolio demonstration. This project is not an official Tithely production website.*
