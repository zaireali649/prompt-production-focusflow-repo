# Tasks

## Version 1

- [Defined audience: students, professionals, and creators who struggle with distraction]
- [Defined core problem: notifications and context switching break focus and reduce output]
- [Customized hero messaging with core promise: "Focus deeper. Finish faster."]
- [Updated features and visual style to a modern, clean, credible SaaS look]
- [Created stock-image comparison variant in `index-stock.html` with consistent image loading and cropping standards]
- [Created hybrid comparison variant in `index-hybrid.html` to test mixed stock + illustrated visuals]
- [Set stock-image version as primary in `index.html`]
- [Created non-stock standalone page in `index-no-stock.html`]
- [Removed accidentally duplicated non-stock HTML document from the bottom of `index.html`]
- [Created dedicated Pro trial onboarding page in `onboarding.html`]
- [Updated primary Pro pricing CTA in `index.html` to route to `onboarding.html`]
- [Added detailed static onboarding intake flow (account, focus profile, work pattern, 30-day goals)]
- [Implemented static success confirmation section in onboarding using `#success` + CSS `:target`]
- [Extended `styles.css` with scoped onboarding form and responsive styles]

## Future Improvements

- [Add a 3-step "How it works" strip under Hero]
- [Add a "Most Popular" badge on the Pro pricing tier]
- [Add a short FAQ block near Pricing/CTA]
- [Add a subtle hero accent background treatment (gradient or soft glow) to
  strengthen first-screen visual impact]
- [Add a lightweight icon treatment for feature cards to improve scanability
  for beginner audiences]
- [Add soft section dividers or transition accents between major sections to
  improve visual flow]

## Sell-Ready Roadmap

### Phase 1 - Monetization Core

- [Set up Stripe products and prices for Starter and Pro plans]
- [Implement trial start and trial-end logic]
- [Handle Stripe webhooks for subscription lifecycle events]
- [Add billing portal for self-serve subscription management]
- [Connect subscription status to user account state]

### Phase 2 - Product Access and Onboarding Backend

- [Implement account auth flow (signup, login, verification, reset)]
- [Persist onboarding intake responses to a database]
- [Link onboarding data to each authenticated user account]
- [Redirect post-purchase users to in-app setup dashboard]
- [Create first-session quick win flow (create first focus plan)]

### Phase 3 - Conversion and Trust

- [Replace static confirmation with real trial activation flow]
- [Add FAQ section and objection-handling copy near pricing]
- [Add trial, refund, and billing policy clarity]
- [Add trust signals (proof metrics, testimonials, or logos)]
- [Set up transactional emails (welcome, trial reminders, trial ending)]

### Phase 4 - Operations and Reliability

- [Set up analytics funnel from landing page to paid activation]
- [Add error tracking and uptime monitoring]
- [Create admin visibility for users, subscriptions, and onboarding status]
- [Set up support inbox and response workflow]

### Sell-Ready Gate Checklist

- [Users can pay securely through live checkout]
- [Users get immediate access to real product value]
- [Trial and billing states are reliable and test-covered]
- [Terms, Privacy, and Cookie pages are published]
- [Support and debugging workflow is operational]
