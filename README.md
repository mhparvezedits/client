# Video Client Prospector v2.0

A fast, fully private, in-browser CRM designed specifically for freelance video editors. This tool helps you define a target market, generate hyper-local search queries, score prospects, and automatically generate custom outreach scripts—all without needing a backend server or database.

## Features

* **Target Market Configuration:** Select high-ticket niches (e.g., Real Estate, Med Spas, Gyms) and target cities to tailor your research.
* **Advanced Research Links (Google Dorks):** Automatically generate targeted Google Search URLs to bypass standard websites and find specific Facebook Pages, YouTube Channels, and Instagram Profiles in your target city.
* **Automated Lead Scoring:** An algorithmic scoring system (0-100) that categorizes leads into Hot, Warm, or Cold based on their current video content gaps, content quality, and contactability.
* **Outreach Script Generator:** Generates customized Instagram DMs and Cold Emails based on the lead's specific content gaps and the selected service type (e.g., Reels, Shorts, Ad Creatives).
* **Pipeline Dashboard:** A clean visual dashboard to track total leads, average pipeline score, and contact status.
* **100% Private Data:** Built entirely on vanilla JavaScript and `localStorage`. No web scraping, no APIs, and no servers. Your data never leaves your browser.
* **CSV Export:** One-click export of your entire lead database for external backup or migration.

## Tech Stack

* **Frontend:** HTML5, CSS3 (Custom design system based on modern UI principles)
* **Logic:** Vanilla JavaScript (ES6)
* **Storage:** Browser `localStorage`
* **Architecture:** Single-file application (Zero dependencies)

## How to Use

1. **Setup:** Download the `index.html` file and open it directly in any modern web browser (Chrome, Edge, Firefox, Brave). No local server required.
2. **Define Target:** In Section 1, choose your service type, client category, and target city. Click "Save Market Target".
3. **Research:** In Section 2, click "Generate Research Links". Use the provided Google Dork links to find businesses and social profiles in your target area.
4. **Log Leads:** When you find a prospect, enter their details in Section 3. Be sure to select their current content quality and video presence to get an accurate score.
5. **Pitch:** Go to Section 5, find your lead, and click "View Scripts" to get auto-generated, copy-paste-ready messages tailored to that specific business.
6. **Export:** Periodically export your leads to CSV as a backup before clearing your browser cache.

## Contributing & Future Roadmap

Contributions are welcome! While v2.0 is designed as a standalone static tool, the architecture is primed for the following upgrades:
* **Webhook Integration:** Connect custom pitches directly to n8n to automate email sequencing.
* **BaaS Integration:** Replace `localStorage` with a Supabase PostgreSQL backend for cross-device syncing.
* **Chrome Extension:** Port the logic into an extension to enable active tab scraping of social media profiles.

Please feel free to submit a Pull Request or open an Issue to discuss potential improvements.

## License

**MIT License**

Copyright (c) 2026 Mh Parvez

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
