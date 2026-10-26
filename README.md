# Abid Hasan Rafi — Personal SEO Website

A responsive, animated personal profile website built with plain HTML, CSS, and JavaScript. It is suitable for GitHub Pages and other static hosting services.

## Included
- Responsive layout for desktop, laptop, tablet, and mobile
- Profile photo from the supplied GitHub asset URL
- Sections for About, SEO Expertise, Career & Education, Approach, and Contact
- Subtle CSS animations and scroll reveal
- SEO title, description, canonical URL placeholder, Open Graph and Twitter metadata
- `ProfilePage` / `Person` JSON-LD structured data
- `robots.txt`, `sitemap.xml`, and SVG favicon
- Accessible mobile navigation and reduced-motion support

## Before publishing — important SEO setup
1. Choose a domain or use your final GitHub Pages URL.
2. In `index.html`, replace **every** `https://YOUR-DOMAIN.example/` with your actual public website URL, including the canonical URL, `og:url`, and JSON-LD `url`.
3. In `robots.txt` and `sitemap.xml`, replace `https://YOUR-DOMAIN.example` with the actual domain and sitemap URL.
4. The LinkedIn URL you supplied was the same as your Facebook URL. Replace the LinkedIn button URL in `index.html` with your real LinkedIn profile URL when you have it.
5. Check that the supplied profile photo URL remains publicly accessible. If it ever stops loading, download your own copy and place it in `assets/`, then update the image URLs in `index.html`.
6. Review all copy and only add claims, achievements, client results, or certifications that are accurate.

## Preview locally
Simply open `index.html` in a browser. No build tools or package installation are required. For the most accurate local preview, use VS Code with the Live Server extension.

## Publish with GitHub Pages
1. Create a new GitHub repository, for example `abid-hasan-rafi-website`.
2. Extract this ZIP and upload the files and folders to the repository root. `index.html` must be at the root, not inside another nested project folder.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish and open the URL shown on the Pages screen.
6. Replace the placeholder domain URLs in the source with your actual published URL and commit the changes.
7. In Google Search Console, add/verify the site, submit `sitemap.xml`, and use URL Inspection to request indexing for the homepage.

## SEO expectations
This website includes useful technical foundations, but no website can guarantee first position or instant indexing for the keyword **Abid Hasan Rafi**. Google may take days or longer to crawl a new site. Improve discoverability by linking to the website from your authentic social profiles, keeping the personal details consistent across profiles, and publishing genuinely useful original content over time.

## Files
- `index.html` — page content, metadata, structured data
- `styles.css` — layout, colors, responsiveness, animations
- `script.js` — mobile menu, year, scroll reveal
- `robots.txt` — crawler rules and sitemap location
- `sitemap.xml` — homepage sitemap (update URL before publishing)
- `assets/favicon.svg` — browser icon
