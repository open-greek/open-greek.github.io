# opengreek.org

GitHub Pages site for [opengreek.org](https://opengreek.org). It serves an instant
redirect to the [Open Greek organization](https://github.com/open-greek).

- `index.html` redirects the root to `https://github.com/open-greek`.
- `404.html` redirects any other path to the matching path under the org, so
  `opengreek.org/<repo>` lands on `github.com/open-greek/<repo>`.
- `CNAME` binds the custom domain so GitHub Pages provisions the TLS certificate.
