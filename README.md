# HyFi Landing Site

Static assets in this directory are published via GitHub Pages to satisfy Plaid's application and security review requirements.

## Local preview

```bash
cd docs/hyfi-site
python3 -m http.server 9000
```

Browse to <http://localhost:9000> to inspect the landing page.

## Deployment

Merges to `main` automatically trigger the **Publish HyFi Site** workflow, which uploads the contents of this directory to the `gh-pages` branch used by GitHub Pages. You can also run the workflow manually from the Actions tab to redeploy without a new commit.
