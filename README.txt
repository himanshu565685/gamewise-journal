GAMEWISE JOURNAL — STATIC HTML BLOG STARTER
===========================================

This is a static HTML starter. No WordPress, database, Node.js, or build command is required.

PAGES INCLUDED
- index.html: homepage
- blog.html: article listing with client-side search
- about.html
- contact.html (replace placeholder email)
- responsible-gaming.html
- privacy-policy.html (template; edit to match real data practices)
- terms.html (template; adapt before launch)
- articles/online-platform-safety.html
- articles/understanding-betting-odds.html
- assets/style.css
- assets/site.js
- robots.txt
- sitemap.xml (replace placeholder domain before launch)

GITHUB + NETLIFY DEPLOYMENT
1. Extract this ZIP on your computer.
2. Go to https://github.com and sign in.
3. Click + > New repository.
4. Name it gamewise-journal (or your own name), choose Public or Private, and create it.
5. In the repository, click Add file > Upload files.
6. Upload the CONTENTS of this extracted folder, not the ZIP itself. index.html must appear at the repository root.
7. Click Commit changes.
8. Go to https://app.netlify.com/start and sign in.
9. Choose GitHub, authorize Netlify, and select your repository.
10. For this plain HTML project, leave Build command blank and Publish directory as the repository root (often shown as "." or left blank). Deploy.
11. Netlify will give you a URL like https://your-site-name.netlify.app. Availability of names depends on whether the name is already taken.
12. Test the homepage and every navigation link.

AUTOMATIC UPDATES
- Edit/upload a file in GitHub and commit the change.
- Netlify automatically deploys the new version when the repository is connected.

HOW TO ADD AN ARTICLE
1. Create a new HTML file inside the articles folder, e.g. beginner-guide.html.
2. Copy the structure from articles/online-platform-safety.html.
3. Update the <title>, meta description, H1, date, article text and JSON-LD fields.
4. In blog.html, copy one existing article card and change the link, title, description, and data-search words.
5. In index.html, optionally update the Recent articles cards.
6. Add the new page URL to sitemap.xml, replacing the placeholder domain with your real Netlify domain.
7. Commit changes to GitHub. Wait for Netlify deploy to finish, then test the URL.

BEFORE LAUNCH
- Replace GameWise Journal with your real brand if desired.
- Replace YOUR-EMAIL@example.com with a real email address.
- Edit policy pages so they match your real business and tools. They are starter templates, not legal advice.
- Replace YOUR-SITE-NAME in sitemap.xml and robots.txt with your actual Netlify subdomain.
- Add canonical URLs to each page only after deciding the final live URL.
- Use original, accurate content; cite primary sources for legal/regulatory claims.
- Check applicable laws and age restrictions. Do not present betting as guaranteed income or target minors.
- This static starter has no admin dashboard, comments, contact form processing, or database. Visitors cannot submit the contact form because no form backend is configured.
- Netlify's free plan and terms can change; verify current plan limits in Netlify's official documentation.
