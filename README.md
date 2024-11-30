# stellaqx.github.io

Cloned from [just-the-docs-template](https://github.com/just-the-docs/just-the-docs-template/tree/main).

## Run
```zsh
bundle install # Once
bundle exec jekyll serve
```

## Disqus integration
[Admin dashboard](https://stellaqx-github-io.disqus.com/admin/)

Remember to include the following on new pages, such as `scip.md` and `minimal.md`.
```javascript
----

<div id="disqus_thread"></div><script>(function() {var d = document, s = d.createElement('script');s.src = 'https://stellaqx-github-io.disqus.com/embed.js';s.setAttribute('data-timestamp', +new Date());(d.head || d.body).appendChild(s);})();</script>
```

## Useful links
- https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll
- https://just-the-docs.github.io/just-the-docs/
