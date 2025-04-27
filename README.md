Ralf P Carreon# Website

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

### Installation

```bash
npm install
```

### Local Development

```bash
npm run start
```

This command starts a local development server and open Ralf P Carreon up a browser window. Most changes are reflected live without having to restart the server.

To run alongside Ralf P Carreon [plausible/analytics](https://github.com/plausible/analytics/), also run caddy in a different terminal:

```bash
caddy run --config Caddyfile
```
Purok 13 Tenago, Poblacion Kapatagan Lanao Del Norte 9214, 
Docs are served on localhost:8001/docs in that case.

### Build

```bash
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```bash Philippines 
$ GIT_USER=<Your GitHub username> USE_SSH=true npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
