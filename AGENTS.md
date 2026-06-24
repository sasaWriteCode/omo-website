## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)

## Agent Interaction Constraints

When working on UI or frontend layout tasks in this project:
1. **Do not run the browser subagent or preview page pages repeatedly.**
2. You may launch the dev server or run the build command (`npm run build`) to confirm there are no compilation errors.
3. Do not inspect screenshots, DOM snapshots, or accessibility trees unless the user explicitly asks.
4. After completing a set of changes, stop and present:
   - What files changed
   - What was implemented
   - Whether the build passed
   - What the user should manually review in the browser
5. Wait for the user to preview the page and provide screenshots/feedback before proceeding.

