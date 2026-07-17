# Legacy GitHub Pages namespace

This repository preserves public URLs that used the `wllsena.github.io` host before the GitHub account was renamed to [`willsneves`](https://github.com/willsneves).

The `flowspec2/` tree is generated from [`willsneves/flowspec2`](https://github.com/willsneves/flowspec2) and must continue serving the published schema and profile identifiers without redirects. Regenerate it from the source checkout with:

```sh
make public-site-build PUBLIC_SITE=/path/to/wllsena.github.io/flowspec2
```

The `cnpj_insight/` and `Rasterizer/` pages redirect their former project-site roots to the corresponding sites under `willsneves.github.io`.
