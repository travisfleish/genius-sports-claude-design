# Genius Sports → Claude Design Reference Bundle

## Before you onboard this into Claude Design — 2 things need a decision

1. **Secondary typeface conflict.** The brand deck names **Inter** as the secondary typeface. The live SharePoint asset library's "Secondary typeface" folder instead contains **Red Hat Text** — files are now included below and verified (SIL-OFL, no usage caps). The only thing left to resolve is *which one is actually current* — that's a call for the brand owner, not an asset-readiness gap anymore.

2. **Klarheit Kurrent licensing is capped, not open.** Per invoice ES210330-377 (Extraset Typefoundry, 30.03.2021): the license covers **Regular and Bold only**, for **1–3 computers** and **web use up to 10,000 views/month**. A Book-weight file was supplied but isn't on the invoice — its license status is unverified. Check with whoever manages font licensing before using this broadly in Claude Design, since team-wide or high-traffic use may exceed what was purchased.

3. **Iconography conflict — two problems, not one.** The brand deck specifies Google Material Symbols. The actual "Branded Icons" folder contains a custom two-tone set instead (33 of an estimated ~60 icons received here). Beyond the system mismatch: **the icon set's own two colorways disagree with each other** — the dark colorway's accent color is `#FF4F5E` (matches nothing in the documented palette), while the white colorway's accent is `#F76B6A` (exactly the documented "Light Red"). Needs a brand-owner decision on both which icon system is current AND which accent color is correct.

## What's in here

```
brand-guidelines.md          — brand platform, tone of voice, visual identity rules
design-tokens.json           — colors, type scale, logo rules (all 3 flags above inline)
logo/                        — 16 official vector SVGs (Primary/Secondary/Symbol/Wordmark × blue/white × standard/small)
logo-png/                    — same 16 marks as PNG
icons-branded/               — 33 of ~60 branded icons (partial set, color conflict flagged)
graphic-devices/             — Linear Graphic reference crops (32-step, 16-step)
fonts/klarheit-kurrent-primary/  — Regular + Bold (all formats), plus an unverified Book file
fonts/red-hat-text-secondary/    — Regular/Medium/Bold + italics, SIL-OFL licensed, ready to use
```
