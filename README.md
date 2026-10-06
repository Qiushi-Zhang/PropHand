# PropHand project website

A self-contained static website for PropHand, IROS 2026. All six videos, extracted paper figures, and the PDF are included. No build tools or third-party runtime dependencies are required.

## Preview
Open index.html in a browser, or run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

## Publish with GitHub Pages
1. Create a public repository named `prophand` in the Qiushi-Zhang account.
2. Upload the contents of this folder (index.html must be at the repository root).
3. Open Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. After the Pages deployment succeeds, the expected address is https://qiushi-zhang.github.io/prophand/.

For the address https://prophand.github.io/, you must control a GitHub user or organization named `prophand`, then publish from its repository named `prophand.github.io`. Name availability has not been verified.

## Edit in the future
- Edit index.html for titles, authors, abstract, video captions, results, and citation.
- Edit style.css for typography, colors, spacing, and responsive layout.
- Replace or add files in assets/videos, assets/images, and assets/papers. Update matching relative paths in index.html.
- Push changes to the configured publishing branch; GitHub Pages republishes automatically.
- You can request changes in the same ChatGPT conversation and provide the repository URL.

## Source and editorial notes
- Layout follows the academic-project structure of Berkeley Humanoid Lite: title, conference, authors, paper/video links, abstract, demonstrations, results, citation.
- Authors are inferred from the supplied PDF filename: Qiushi Zhang, Xilin Zhang, Jeff Ichnowski. The PDF itself says Anonymous Authors. Affiliations are omitted pending confirmation.
- The abstract is transcribed from the PDF, with line-break hyphenation removed. The project goal is a separate addition.
- Abstract estimation error is 6.3%; Table II and experimental text report 6.81%. Both are preserved in their source contexts, with a note in expanded results.
- The supplied screwing clip corresponds to the paper's nut-turning demonstration. Its caption describes a nut spinning along a screw.
- The keyboard heading uses the requested superhuman-speed wording; the caption uses the paper's quantitative claim of up to 12 Hz. No human comparison experiment is asserted.
- The numeric input filename is served as assets/videos/force_sensing_test.mp4.
- Figure images are direct high-resolution crops from the supplied PDF, not reconstructed plots.
- The original PDF is included unchanged and remains anonymized. Replace it with the author version when ready.
