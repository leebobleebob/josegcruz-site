# Jose Cruz Static Site

This is a static rebuild of the Wix site for `josegcruz.org`.

## Local preview

```sh
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## GitHub Pages

Publish this folder from a GitHub repository using GitHub Pages. The included `CNAME` file maps the site to:

```txt
josegcruz.org
```

DNS records needed at the domain provider:

- `A` records for `josegcruz.org` pointing to GitHub Pages:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` record for `www` pointing to your GitHub Pages hostname, usually `YOUR-GITHUB-USERNAME.github.io`.

After GitHub detects the domain, enable **Enforce HTTPS** in the Pages settings.
