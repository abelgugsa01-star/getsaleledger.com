# getsaleledger.com

Public marketing site for SaleLedger, served by GitHub Pages at
https://getsaleledger.com.

This repo contains **only** the static site (`index.html` + `CNAME`).
The SaleLedger product itself lives in a separate private repository;
nothing here is generated from it, and nothing from it should be added
here.

## Deploy

GitHub Pages is configured to serve from `main` / root. Pushing to `main`
publishes within a minute or two.

## Editing

The canonical copy of the page is `website/index.html` in the private
SaleLedger repo. Edit it there, then copy it here and commit:

    cp ../saleledger/website/index.html index.html
    git commit -am "Update site" && git push
