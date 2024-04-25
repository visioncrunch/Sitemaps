# Coursera Grade Scraper using Web Scraper Extension

## Introduction
This guide provides step-by-step instructions on how to scrape your grades from Coursera using the Web Scraper extension for your browser. The provided sitemap JSON file allows you to extract grade-related information from your course page.

## Prerequisites
- Google Chrome browser
- Web Scraper extension installed (Available for free on the [Chrome Web Store](https://chromewebstore.google.com/detail/web-scraper-free-web-scra/jnhgnonknehpejjnehehllkliplmbmhn))

## Instruction (Steps you need to do only once - intial setup)
1. Open a new tab in your Google Chrome browser.
2. Press `Ctrl + Shift + C` to open the inspection tools. (Shortcut might differ for other OS and browsers)
3. In the inspection tools window, navigate to the "Web Scraper" tab and click on it.
4. The Web Scraper interface will appear. Click on "Create Sitemap".
5. Select "Import sitemap" and copy-paste the contents of [sitemap.xml](https://github.com/visioncrunch/Sitemaps/blob/main/sitemap.xml) into the designated area.
6. Choose a name for your sitemap and click "Import Sitemap".
## Final Scraping steps
8. Once the sitemap is created, go to the "Sitemaps" tab and click on your newly created sitemap.
9. Click on the dropdown menu and select "Scrape".
10. Click "Start Scraping" to begin the scraping process.
11. The extension will open a new tab, and you'll see links changing in a sequence, indicating the scraping process is ongoing.
12. After completion, the tab will stop, and you might see a message indicating "Scraping Completed".
13. Go back to the dropdown menu of your sitemap and select "Export Data".
14. Choose the desired format, such as `.xlsx` for an Excel file, and export your scraped data.

## repeat step 8 to 14 whenever you need to scrape your grades

## Conclusion
By following these steps, you can scrape your grades from Coursera using the provided sitemap and the Web Scraper extension. This allows you to conveniently collect and analyze your course performance data.
