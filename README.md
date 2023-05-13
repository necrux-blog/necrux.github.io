# necrux.com

This is Wes Henderson's blog, recently migrated to Jekyll using a GitHub Pages template for academic websites; formally a WordPress site.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

## Local Testing
For local development I am using a container [image](https://hub.docker.com/r/bretfisher/jekyll-serve) created by [Bret Fisher](https://github.com/BretFisher). From the root of the repo simply run:

```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

The local site can be viewed at [http://localhost:4000/](http://localhost:4000/).

**Note:** Changes to `_config.yml` require a reload of the server.
