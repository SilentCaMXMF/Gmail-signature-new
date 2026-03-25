# Spec: gmail-signature-spec

Scope: feature

## Gmail Signature Improvement Spec

### Syntax Fix
- Fix malformed `href` on line 21 of index.html (missing closing quote)

### Unification
- Choose canonical version between index.html and script.jsx
- Sync both files to same content and styling

### Weaknesses
- Add proper fallback fonts: `font-family: Helvetica, Arial, sans-serif`
- Add dark mode support via `@media (prefers-color-scheme: dark)` with light background fallback

### Opportunities
- Add website link in text format: `silentcamxmf.github.io`
- Add pronouns: `(he/him)`
- Add CTA banner: "Open to collaborations 🎵" with link to Calendly or contact

### Threats
- Add `.gitignore` with credentials patterns
- Verify no secrets committed

### Testing
- Test in Gmail web, Outlook, Apple Mail