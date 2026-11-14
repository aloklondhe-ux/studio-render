# studio-render

Render runners for a private animation project. The project's code and content live in a private repository; this
repository only holds the generic render workflow and the static pages for the publishing app's sign-in screen.

- `.github/workflows/render.yml` renders a private project in parallel chunks. Everything it produces is encrypted.
- `docs/` holds the home page, privacy policy and terms of the "Channel Publisher" app.

No credentials are stored in this repository. Workflows run only when started by the owner.
