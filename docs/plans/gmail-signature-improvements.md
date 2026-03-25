---
plan name: gmail-signature-improvements
plan description: Fix syntax errors, address weaknesses, leverage opportunities, and mitigate threats
plan status: done
---

## Idea
Improve the Gmail signature project by fixing bugs and adding features

## Implementation
- Fix syntax error on index.html line 21 - malformed href attribute on phone number
- Unify index.html and script.jsx - choose best version as canonical
- Add proper fallback font stack to CSS
- Add dark mode support using meta color scheme or media queries
- Add website link in text format (not just in image)
- Add professional pronouns (he/him)
- Add 'Open to collaborations' banner or CTA
- Move image hosting to reliable CDN (optional - evaluate)
- Add .gitignore and verify no secrets committed
- Test signature across different email clients

## Required Specs
<!-- SPECS_START -->
- gmail-signature-spec
<!-- SPECS_END -->