# Rules for Claude

Claude reads this file at the start of every session on this repo and follows these rules.
Edit it any time to add, change, or remove rules.

## My rules

<!-- Add your own rules here, one per line. Examples:
- Always explain changes in plain, non-technical language.
- Ask me before deleting any page.
-->

- Explain what you changed in plain, simple language. I'm not a developer.
- Ask me before deleting files or making big changes to the site's look.
- Don't create a pull request unless I ask for one.

## About this repo

This is my GitHub Pages site (tarynmaloney5-ui.github.io). It's plain HTML with no build step.
Changes go live after they're merged into the main branch.

- `index.html`: home page listing my apps (ExamMe, Drawing Wall, and a footer link to CanvassFlow).
- `examme/` and `drawingwall/`: old page addresses that now forward to exammenow.com and drawingwall.com.
  Keep them as forwarding pages so old links (such as Play Store privacy policy links) keep working.

## Style for pages

- Keep pages as single, self-contained HTML files with styles inside a `<style>` tag.
- Support light and dark mode using the color variables on `:root`.
- Make sure pages look right on phones.
