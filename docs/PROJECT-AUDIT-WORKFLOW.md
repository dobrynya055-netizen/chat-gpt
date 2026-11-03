# Project audit workflow

## 1. Intake
Record project URL, repository, intended audience, target devices, hosting, and any locked/approved components. Obtain the actual source or rendered screenshots before making visual claims.

## 2. Baseline
Capture desktop (1440px), tablet (768px), and mobile (390px) screenshots. Note console errors, failed assets, layout shifts, broken links, and keyboard navigation. Do not alter the site during baseline capture.

## 3. Review
Use skills/frontend-design, ui-ux-audit, anti-slop, asset-quality, motion-design and website-qa. Classify issues P0 (broken), P1 (high impact), P2 (polish). Every finding requires location, evidence, suggested fix, and acceptance criterion.

## 4. Implementation
Create a separate branch, preserve locked sections, make targeted changes, and review screenshots side by side. Never claim that source edits are deployed until deployment is verified.

## 5. Acceptance
Check 390/768/1440 widths, image cropping, navigation, keyboard, reduced motion, performance and key business flows. Publish an audit report with tested/unverified/blocked statuses.

## Pilot: pastry chef site
Target URL: https://mellifluous-valkyrie-7905c9.netlify.app/
Known constraint: the approved homepage hero is locked; do not edit it. Other page elements need evidence-based review. Source code location is not yet confirmed. Site inspection is currently blocked in the available environment, so no visual findings have been asserted.
