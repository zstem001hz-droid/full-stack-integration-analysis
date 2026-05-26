# Full-Stack Integration Analysis

A written reflection on the key challenges and solutions involved in connecting a decoupled React frontend to a Node.js/Express backend, with a focus on CORS, environment variable management, and data-fetching strategies.

## Resources

### Reading

- [Avoiding Cross-Origin Issues While Hosting Full Projects — Dev.to](https://dev.to/...)
- [The Ultimate Guide to Setting Up Your Dev Environment for CORS — Wisp Blog](https://wisp.blog/...)

### Video

- [React Proxy | Easiest Fix to CORS Error — YouTube](https://youtu.be/N4yUiQiTvwU?feature=shared)

## Reflection Questions

1. **CORS Explained** — In your own words, explain what a CORS error is and why it occurs in a typical MERN stack application with separate client and server repositories. Describe two different strategies a developer could use to resolve CORS issues during local development.

2. **Environment Management** — Why is it considered a bad practice to hardcode API URLs directly into client-side React code? Explain how environment variables (`.env` files) help solve this on both the client (`REACT_APP_` / `VITE_`) and server (`dotenv` package).

3. **Data Fetching Trade-offs** — The lessons covered both the native `fetch` API and the `axios` library for making API requests. Based on the resources and your own understanding, describe one key advantage of using `axios` over `fetch` for a complex application.

## Submission

- [reflections.md](./reflections.md)
