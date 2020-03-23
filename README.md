# Jekyll gh-pages site (cross-maintained)

Branch for [seas.upenn.edu](seas.upenn.edu/~apallath) ENIAC website
- `_config.yml` for gh-pages requires an empty baseurl, whereas for eniac, this requires a url of `https://seas.upenn.edu/` and a baseurl of `/~apallath/`. Make these changes first.
- Serve locally to generate `_site`
- scp `_site` to server
- Reset values of baseurl and url
