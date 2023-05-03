# base-web-app-template

Everything you need to build another SvelteKit-based project.

## Developing

Once you've installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

To close the dev server, hit Ctrl-C.

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

✔ Typescript

  Inside Svelte components, use <script lang="ts">

Production changes
- node build
+ node -r dotenv/config build
Pass in HOST=127.0.0.1 PORT=4000 when you need it 
Additionally, ORIGIN, PROTOCOL\_HEADER and HOST\_HEADER can be passed in

