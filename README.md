# sveltekit-netlify-cms

A SvelteKit skeleton app with Netlify CMS living in `/admin`. Netlify CMS is configured to directly edit `/routes/*.md` files, which are preprocessed by [mdsvex](https://mdsvex.com).

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/buhrmi/sveltekit-netlify-cms&amp;stack=cms"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

[Demo](https://sveltekit-netlify-cms.netlify.app)

## Developing

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create the production version of your app, run:

```bash
npm run build
```

> You can preview the built app with `npm run preview`. However, this should _not_ be used to serve your app in production.
