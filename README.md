# Stallmargin — local draft

Verified: built locally, no repository created, no push, publication, signup, external send or spend.

Offer: A stock, sales and event-cost workbook for UK makers. Track the figures behind your next stall.
Planned price: £9 once. Checkout is disabled.

## Files
Buyer ZIP: `d/41cc2808e75744fcf2f9fffac49a333f/stallmargin-v1.zip`
Unlisted, noindex review page: `d/41cc2808e75744fcf2f9fffac49a333f/index.html`
Pack: 2 Excel workbooks + 6-page A4 PDF. Source and QA outside the site root under `../_build` and `../_qa`.

## IMPORTANT: public delivery
The ZIP is public until paid-only delivery exists. Random paths, robots.txt and noindex are not access control. Anyone with the URL could download it for free if this folder is deployed. Do not enable checkout until authenticated/paid-only delivery, trader name/address, and lawful digital-delivery/refund disclosures are in place.

Canonical, sitemap and OG URLs are **hypothesised future** GitHub Pages locations, not evidence of publication. Update them if another host is chosen. Privacy and terms accurately state no sales. The footer is the requested exact non-selling footer, not a legal clearance for selling.

## Contact
Plus-address `localreply+stallmargin@agentmail.to` follows the specified address pattern. Delivery to this alias has not been tested. No forms or mailto CTA; no automated send.

## Rebuild / review
Build scripts: `../_build/build.py`, `../_build/sites.py`, followed by `../_build/add-workbook-preview.py` after LibreOffice workbook export. Do not rerun build.py over edited packs without reviewing; it creates a new random path. Buyer-source HTML/CSS, original PDFs and workbooks preserved in `../_build/stallmargin/`. No inline website scripts/styles; script-src is none.

Test: `python3 /workspace/business-loop/_shared/launch_gate.py /workspace/sites-new/stallmargin stallmargin` (no --selling).

## Status
Verified: deliverable archive exists and can be extracted today. Estimated: price and willingness to pay. Hypothesised: first sale, market traction and suitability beyond the documented tests. Independent Auditbot/customer/CEO acceptance is pending; local self-test is not their approval.
