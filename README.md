# SaleLedger

**Auction trust-account reconciliation.** Windows software for auction houses and estate-sale companies reconciling consignor trust accounts.

Compare auction settlement exports, QuickBooks payout exports and bank statements. Review differences between the adjusted bank balance, trust control balance and consignor subledger, then produce a reconciliation report and check register.

## Try SaleLedger

[Visit the official website and start a 30-day free trial](https://getsaleledger.com/?utm_source=github&utm_medium=referral&utm_campaign=product_readme).

No charge during the trial. The subscription is **$129/month after the trial**. Review the current offer and terms on the official website.

## Guides and tools

- [Free three-way trust-account check](https://getsaleledger.com/trust-account-check.html)
- [Monthly reconciliation guide](https://getsaleledger.com/auction-trust-account-reconciliation.html)
- [Prepare the three source files](https://getsaleledger.com/auction-flex-quickbooks-bank-exports.html)

## Support

Questions about fit or setup: [support@getsaleledger.com](mailto:support@getsaleledger.com). Built by [Profitpin LLC](https://profitpingroup.com/).

---

## Website maintenance

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
