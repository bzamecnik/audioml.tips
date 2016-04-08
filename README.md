# AudioML.tips

http://audioml.tips

Tips on Audio Processing &amp; Machine Learning.

A blog written by [@bzamecnik](http://twitter.com/bzamecnik).

[License](LICENSE.txt).

## Usage

This site is built using Nikola, a static site generator.

I have nikola in an anaconda environment.

```shell
source activate nikola
```
Builds and serves a site; automatically detects site changes, rebuilds, and optionally refreshes a browser. It starts the server in foreground.

```shell
nikola auto
```

Open the site in browser:

```shell
open http://localhost:8000
```

Create new post:

```shell
nikola new_post
```

After committing, the site can be built and deployed. It is deployed to GitHub Pages.

```shell
nikola deploy
```
