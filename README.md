# NeuroWeb Studio — Frontend Quality Lab

A browser-based academic frontend project focused on identifying common markup issues, exercising UI interactions, and running lightweight browser-side assertions.

## Run locally
1. Open this folder in VS Code.
2. Use Live Server, or open `index.html` directly in a modern browser.
3. Choose **Quality checker** and paste a small HTML fragment to run the heuristic diagnostics.

## Scope and limitations
- HTML diagnostics parse pasted markup in an inert document and do not execute scripts or upload content.
- The checks are heuristics, not a full WCAG audit or replacement for assistive-technology testing.
- The Test Lab contains lightweight browser-side assertions; it is not a substitute for a professional end-to-end testing framework.
- Test history is stored locally in the browser.

## Technologies
HTML5, CSS3, JavaScript, responsive layouts, DOMParser, browser APIs, and optional Google Fonts with local font fallbacks.
