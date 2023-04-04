To see it in action, access `localhost:3000/sydney` in your browser.

You will notice that this page is already in the static path list. It loads up as usual.

Now, try to access `localhost:3000/paris`, which is not in the static path list. You will notice that it loads up as usual, too. That is because SSR has kicked in and rendered the page for you.

From here on `/paris` will be served as a static page.

Refefrence:
https://nextjs.org/docs/api-reference/data-fetching/get-static-paths#fallback-blocking
