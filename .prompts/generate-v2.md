This is a plain HTML/CSS/JS project. Build a landing page based on the
requirements below.

Requirements:
EventSpace Pro is an event booth rental and production service offering exhibition booths, food booths, and activity booths for exhibitions, concerts, and festivals. The brand features a modern, professional design that conveys trustworthiness and reliability. The visual approach emphasizes quality service delivery, expertise in event production, and the versatility of their booth rental solutions for various event types.

Output to a single file named `v2.html` with all CSS and JS
inline (no external files, no frameworks).

This is variant 2 of 2. Make it distinctly
different from the other variants in layout, palette, typography, and
visual direction.

No emojis anywhere. Use Lucide Icons instead:
`<script src="https://unpkg.com/lucide@latest"></script>` in head,
`<i data-lucide="icon-name"></i>` in body, `lucide.createIcons()` at end.

For images, search for relevant photos using the tool:
`bash /home/runner/work/web-builder-control/web-builder-control/core/tools/search-images.sh "keyword" [count]`
Search with different keywords per section (e.g. hero, features, about).
Use the returned URLs directly in `<img src="...">`. Add `?w=WIDTH&h=HEIGHT&fit=crop`
to resize as needed.

If the search tool is unavailable, fall back to
`https://picsum.photos/seed/{descriptive-keyword}/{width}/{height}`.

Constraints: no X-Frame-Options or frame-blocking headers (this page
will be loaded inside an iframe for client review).
