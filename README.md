# market-data

Market prices for the stress monitor on [lima-spielhofen.com](https://lima-spielhofen.com).
A scheduled job runs `fetch_data.py` (Yahoo Finance and FRED) and puts
`market.json` and `fred.json` on the `data` branch, where the site reads them.
