# Decisions

## 2026-02-22

- Chose a single-page landing page format to keep scope tight for a beginner
  workshop and make the project shippable quickly.
- Kept strict semantic section order (Hero, Problem, Solution, Features,
  Testimonials, Pricing, CTA, Footer) to align with assignment requirements and
  improve readability.
- Stayed with static HTML + CSS only (no JavaScript, no frameworks) to match
  constraints and reduce implementation complexity.
- Reused existing class names and CSS architecture instead of redesigning
  structure, so responsive behavior remained stable.
- Centered messaging on one core promise ("Focus deeper. Finish faster.") to
  keep copy clear, consistent, and conversion-oriented.
- Used concise, benefit-driven copy in each section to support beginner-level
  clarity and fast scanning.
- Defined two pricing tiers (Starter and Pro) to present an easy upgrade path
  without overcomplicating options.
- Made CTA language action-oriented ("Start Your Free Plan", "Create Your Free
  Account") to increase likelihood of user action.
- Completed a CSS-only visual polish pass in `styles.css` to improve hierarchy
  and readability without changing copy, section order, or HTML structure.
- Kept implementation static HTML + CSS only (no JavaScript), preserving the
  existing concept and messaging exactly as written.
- Standardized typography scale, section spacing rhythm, card treatment, and
  button system so the design reads as one coherent UI language.
- Added clearer hover/focus states and maintained strong contrast to improve
  accessibility and keyboard usability.
- Preserved mobile behavior by keeping current breakpoints/stacking model while
  tightening spacing and navigation wrapping for smaller screens.
- Tested three visual variants for imagery direction: illustrated, all-stock,
  and hybrid.
- Selected all-stock imagery as the primary direction for the main landing page
  due to stronger perceived trust and preferred overall look during comparison.
- Promoted stock variant to primary by making `index.html` use stock imagery and
  stock styling (`styles-stock.css`) as default presentation.
- Preserved alternates for reference and comparison in `index-stock.html`,
  `index-hybrid.html`, and `index-no-stock.html`.
- Resolved a structural issue where a full non-stock HTML page had been appended
  to the bottom of `index.html` by removing the duplicate document and keeping
  root page content single-source.
- Built a dedicated Pro trial onboarding experience as a separate page
  (`onboarding.html`) rather than extending the existing single-page anchor flow.
- Routed the primary Pro pricing CTA (`Start Pro Trial`) in `index.html` to the
  dedicated onboarding page for a clearer conversion path.
- Chose a detailed intake structure for onboarding (account basics, distraction
  profile, work cadence, and 30-day goals) to better fit Pro trial qualification.
- Kept onboarding fully static HTML + CSS (no JavaScript, no backend) to stay
  aligned with current project constraints.
- Implemented onboarding submit confirmation as an in-page success section using
  hash-target behavior (`#success`) and CSS `:target`.
- Added scoped onboarding styles in `styles.css` instead of creating a separate
  stylesheet to keep styling centralized and consistent.
- Documented a sell-ready roadmap in `tasks.md` covering four phases:
  monetization core, product access/backend, conversion/trust, and operations.
