# Price watch test pages

These static pages test Will's Price watch runners. All product names, prices and stock states are synthetic. Nothing is for sale. The pages have no tracking or outside assets.

Only `changing.html` may change during a test. The other pages are fixed controls: changing their values pauses the collector.

- `in-stock.html`: $123.45 AUD, in stock, with JSON-LD.
- `sold-out.html`: $67.89 AUD, sold out, with microdata.
- `two-prices.html`: one product with two prices; the reader must refuse it as ambiguous.
- `blocked.html`: a synthetic human-verification page with no product data.
- `changing.html`: starts at $50.00 AUD, sold out; used to test price and stock changes.
- `list.html`: 200 synthetic listings, $1.01 to $3.00 AUD, alternating in and out of stock.
