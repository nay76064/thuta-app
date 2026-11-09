# Haven web app

The responsive Haven website lets people find homes in Myanmar and manage property listings. Its supported behavior is described in [SPEC.md](SPEC.md).

## Run locally

Requires Node.js 20 or later. Install dependencies and start the Vite development server:

```sh
npm install
npm run dev
```

The app runs on port 5173 and proxies `/api` to `http://127.0.0.1:4001`. Start the [Haven API](https://github.com/nay76064/thuta-api) separately, or set `API_PROXY_TARGET` to another API address.

Run `npm run build` to create a production build.
