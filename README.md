# SciNova India — Full-Stack Website

This package upgrades the SciNova India site with:

- Modern 3D/maximalist frontend
- Menu button + responsive mobile navigation
- Campus Ambassador Jotform integration
- WhatsApp community join link
- Instagram + LinkedIn links
- Inbuilt article/Dispatch publishing
- SQLite database
- Express backend + REST API
- Inquiry and newsletter storage
- Admin panel at `/admin`
- Optional AI assistant through an OpenAI-compatible API
- Safe demo mode when no AI key is configured

## Run locally

Requirements: Node.js 20+

```bash
npm install
cp .env.example .env
# edit .env and set a strong ADMIN_TOKEN
npm start
```

Open:
- http://localhost:3000
- http://localhost:3000/admin

## AI

Set `AI_API_KEY` in `.env`. The backend keeps the key server-side; it is never put into the frontend.

`AI_API_URL` and `AI_MODEL` can be changed for an OpenAI-compatible provider.

## Important

The backend is deployment-ready but is not automatically hosted by this generated package. For a live website, deploy the Node app and persistent database to a hosting provider, then point the domain to it.

The Jotform and WhatsApp links are external services supplied by SciNova India.
