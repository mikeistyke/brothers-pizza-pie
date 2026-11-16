# Brothers Pizza

Plain HTML and CSS for https://brotherspizzapie.com. No React, Vite, npm dependencies, Tailwind CDN, or compilation.

## Edit and preview

All published files are in public/. Edit public/index.html for content and public/styles.css for styling. Open public/index.html directly or serve public/ with any static web server. Images are in public/assets/.

Gallery filters use CSS radio controls. Navigation and expandable details use native HTML. The site works without JavaScript. The dish illustrations are retained from the original design, not actual menu photographs. Confirm restaurant hours and replace illustrations with approved photos as needed.

## Cloudflare Pages

- Repository: mikeistyke/brothers-pizza-pie
- Production branch: main
- Framework preset: None
- Build command: exit 0
- Build output directory: public
- Root directory: blank (repository root)

No environment variables or API keys are required. Push to main to trigger the existing Cloudflare Pages Git integration. The custom domain is brotherspizzapie.com.

The previous AI Studio export remains recoverable in Git history. It required React/Vite, had conflicting package versions, and kept source and assets inside a ZIP instead of deployable files.
