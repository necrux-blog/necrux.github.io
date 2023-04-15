# necrux.com

This is Wes Henderson's blog, recently migrated to Jekyll using a Github Pages template for academic websites; formally a WordPress site. This template was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

## Local Testing
For local development I am using a container [image](https://hub.docker.com/r/bretfisher/jekyll-serve) created by [Bret Fisher](https://github.com/BretFisher). From the root of the repo simply run:

```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

The local site can be viewed at [http://localhost:4000/](http://localhost:4000/).

**Note:** Changes to `_config.yml` require a reload of the server.
