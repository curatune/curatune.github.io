# curatune.github.io

The hosted web demo of [Curatune](https://github.com/gabriel-dg/curatune), served at https://curatune.github.io/.

This repo holds no app code. The [Deploy](.github/workflows/deploy.yml) workflow builds the web app from the source repo and publishes it with GitHub Pages. It runs only when started by hand (Actions > Deploy > Run workflow).

The site runs entirely in your browser: you sign in with your own Spotify account and bring your own model and API key. Nothing is sent to a Curatune server, because there isn't one.
