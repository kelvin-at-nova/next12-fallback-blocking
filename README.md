To see it in action, run `npm run build` and then `npm run start`, visit localhost:3000/sydney` in your browser.

Quote from the doc, "Next.js allows you to create or update static pages after you’ve built your site". It does NOT run under `npm run dev`.

Now, try to access `localhost:3000/paris`, which is not in the static path list. You will notice that it loads up as usual, too. That is because SSR has kicked in and rendered the page for you.

From here on `/paris` will be served as a static page.

Refefrence:
https://nextjs.org/docs/api-reference/data-fetching/get-static-paths#fallback-blocking
