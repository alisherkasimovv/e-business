Key aspects of technical SEO include:
- **Crawlability:** Ensuring search engines can easily crawl and access all important pages on your site through proper site structure, internal linking, redirects, etc.
- **Performance:** Optimising site speed, reducing code bloat, implementing responsive design, and using technologies like AMP to improve user experience
- **Indexation:** Preventing duplicate content issues, using sitemaps, internal linking, and checking log files to ensure complete and accurate indexation
Here are the key steps to create an optimised XML sitemap:
1. **Use tools and plugins to automatically generate your sitemap.** For WordPress sites, plugins like Yoast SEO and Rank Math can create XML sitemaps easily. Manually creating a sitemap is only needed if you want to add hreflang attributes.
2. **Submit your sitemap to Google Search Console and Bing Webmaster Tools.** This helps search engines discover and crawl your pages more efficiently, although it doesn't guarantee indexation. The main benefit is that Google will find and fix any crawling errors.
3. **Optimise your sitemap content:** Include only important, high-quality pages that you want indexed
4. **Keep your sitemap size manageable.** Sitemaps should be under 50MB and 50,000 URLs. If your site is larger, split it into multiple sitemaps.
5. Add your sitemap location to robots.txt to make it easier for search engines to find.
6. Follow the sitemaps.org protocol - use `<urlset>`, specify the namespace, include `<url>` and `<loc>` tags, etc.