# Code map

| Surface | Entry point | Verification |
| --- | --- | --- |
| Homepage and outbound links | `index.html` | Load root on a static server. Check all five products, Mac App Store, GitHub, and UlarBox policy links. |
| Responsive layout and sample interaction | `styles.css`, draft/revised radio group in `index.html` | Test keyboard and pointer in a browser at 320px through 1440px. Both states work without JavaScript. |
| Product media and sharing | `assets/studio/`, image and Open Graph tags in `index.html` | Match walkthrough images to the General and Sharing captions. They were created by applying UlarMark 26.11.1's exporter to fictional settings screens. Compare separate editor captures to the UlarMark and UlarBox product repos. |
| Custom domain and compatibility routes | `CNAME`, `privacy.html`, `terms.html`, `open-source-licenses.html` | Verify root, apex redirect, and legal routes after an authorized deployment to GitHub Pages from `main`. |

For product priorities, requirements and the three planning reviews, see [SPEC.md](../SPEC.md).
