# CYBER AMIT — JSON API Dashboard

A mobile-friendly, neon-blue hacker-style static dashboard. No build command is required.

## Run locally
Open `index.html` in a browser, or serve the folder with any simple static server.

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` and `vercel.json`.
2. In Vercel, import that repository.
3. Choose the framework preset **Other**.
4. Leave Build Command empty and Output Directory as `.` (or default static output).
5. Deploy.

## How to use
- Initial demo password: `DIMPUU`
- Open **ADMIN PANEL** after entering.
- Rename buttons, set an HTTPS API URL, method, optional key header, extra headers, and a POST JSON body template.
- Use `{{query}}` in a URL or POST body to insert the search text.
- Save settings, select a tool, enter a query, and press Search. The API response is displayed as formatted JSON.

## Important limitations
- This is a static starter/demo project. Password and settings are stored in the browser's localStorage, so they are not secure and are not shared between devices/browsers.
- API keys entered here are stored in the browser and may be exposed to anyone who can inspect the browser. Do not use production secrets. For real private API keys, use a backend/serverless function and real server-side admin authentication.
- Some APIs block browser requests (CORS). Those require a secure backend proxy.
- This is a generic JSON API client and does not collect social-media passwords or imitate official login pages. Only use APIs and data you are authorized to access.
- 
