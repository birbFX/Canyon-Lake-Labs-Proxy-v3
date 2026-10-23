> [!IMPORTANT]
> **This is AI vibe coding.**
> This project is a **passion project by Canyon Lake Labs**, built for fun and made
> almost entirely with AI assistance. It is a hobby project, not a polished
> commercial product. If you don't like AI-made software, that's completely
> fine — **don't use it.**

<h1>Canyon Lake Lab's Proxy — Demo v3</h1>

A public web proxy demo by **Canyon Lake Labs**. Enter an address or a search and
browse through the proxy.

v3 is the mid-tier demo — about **50%** of the internal build's features.

## Features

- **Browser** — search bar + proxied iframe
- **Tabs** — closable tabs with an activity rail
- **Start** — quick-launch portal
- **Network** — request inspector (method, status, timing, headers)
- **Console** — run JavaScript inside the active proxied page
- **Settings** — home page, Wisp server, request limit, fast mode

## Run it

```sh
npm install
npm run dev
```

Then open <http://localhost:3030> (honors `$PORT`).

## Deploy

Set the start command to `npm start` (or `node server.js`).

## Notes

- Powered by the open-source [Scramjet](https://github.com/MercuryWorkshop/scramjet)
  proxy engine. All credit for the engine goes to Mercury Workshop.
- Licensed under the AGPL-3.0.
