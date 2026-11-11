TECK LEONG / COPPER.ASIA STATIC WEBSITE COPY

This folder contains a local static HTML mirror of copper.asia with the site's downloaded HTML pages, CSS, JavaScript, and images. Original page copy and image assets are retained wherever available. SEO additions are limited to page titles where generic, descriptions where missing or duplicated, canonical links, Open Graph metadata, image alt text, robots.txt, and sitemap.xml.

LOCAL PREVIEW
1. Extract the ZIP.
2. Serve this folder with Apache/LiteSpeed; direct file:// previews and generic static servers do not apply the clean-URL rewrites.
3. Keep the directory structure intact; page and image links are relative.
4. Enable mod_rewrite and allow .htaccess overrides so clean URLs resolve to their matching .html files.

IMPORTANT LIMITATIONS
- This is a static mirror, not an authorized deployment to copper.asia. Review rights and permissions before publishing.
- The original site uses ASP.NET/server-side functionality. Its enquiry form, verification code, file upload, and any server postbacks will not work as intended from static HTML alone; connect a secure form handler before launch.
- A small number of image references were missing or saved as HTML by the mirror. Those references use the site's local no-image placeholder.
- GA4 and Google Tag Manager tags are retained; review consent/privacy requirements before publishing.
- Verify every URL, title, description, canonical, sitemap entry, and image before replacing a live site.
