# UlarioSoft homepage

## Purpose

The homepage is the company entry point for UlarioSoft's five products. It gives the featured, purchasable product a short path to the Mac App Store and gives visitors direct routes to the other products and support.

## Planning review, 2026-11-23

| Round | Strategy | Design | Independent review | Decision |
| --- | --- | --- | --- | --- |
| 1 · Explore | Compared featured-product and equal-weight portfolio layouts | Proposed a light editorial studio and a dark developer catalog | Checked product states, destinations, and accessibility risks | Feature UlarMark. Keep the portfolio and support discoverable in navigation. |
| 2 · Challenge | Prevent the headline from implying exported PNGs remain editable. Keep a fast route to every product. | Compared a new cool light canvas with dark indigo product art to the initial concepts | Flagged the large Mark image, Card's generic store links, and legacy public URLs | Use a compressed genuine Mark capture and label the separate interactive example. Keep released and unreleased destinations distinct. |
| 3 · Finalize | Confirmed the featured product, purchase link, and portfolio hierarchy | Approved the layout with 320–1440px, keyboard, and contrast checks | Confirmed that the compatibility pages are UlarBox-specific and separated local QA from production checks | Approved the following implementation brief before development. |
| 4 · Prepare release | Connected the hero and navigation example into one task | Compared the existing house-photo capture with a work-oriented sample | Rechecked the Pages source, HTTPS, legal URLs, and rollback commit | Put an original workspace example annotated with UlarMark at the top. Show the authentic app capture in the workflow section. |

## Implementation brief

1. Replace the homepage with an original English-language, static company homepage. The visual system uses a cool light canvas, indigo feature artwork, real UlarMark and UlarBox captures, and a distinct open-source section.
2. Put the company identity and section navigation above the fold. Lead with UlarMark for Mac and a direct App Store purchase link. Explain the difference between a saved editable UlarMark document and the exported PNG.
3. Show the original and revised documentation screenshot in the hero. The workspace settings are fictional, and the marks are exported by UlarMark's compositor. Identify both states as a sample walkthrough. Both states must remain accessible without JavaScript. Keep all actual product and store links as HTML anchors.
4. Route UlarBox to its product site. Describe UlarCard as in development with no store action. Route ular-s7s and ular-git to their GitHub repositories and show clearly labeled example terminal views. Keep support contact and labeled UlarBox legal routes available.
5. Keep the GitHub Pages custom domain and use `https://www.ular.io/` as the canonical and social-sharing URL. New homepage assets are same-origin. The homepage makes no analytics or other third-party requests on load.

## Verification

Check 320px, 390px, 768px, 960px, and 1440px, plus a zoomed desktop viewport. Validate semantic landmarks, one heading hierarchy, visible keyboard focus, demo states with and without JavaScript, no horizontal page overflow, reachable support, product and App Store links, and optimized images. Check public product descriptions against their actual destinations before release.

The GitHub Pages production source is `main` at the repository root. Verify the apex-to-www redirect, canonical URL, shares, and compatibility URLs on the deployed site when release is authorized.
