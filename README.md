# UK Cheap Eats Index

Open data on what a meal from an independent kitchen actually costs in the UK.

**151 dishes** — one per independent place — in London, Manchester, Brighton and Leeds. **138** have a confirmed price. Every row carries the source the price was read from.

| City | Dishes | Median | £10 or less |
|---|---|---|---|
| Brighton | 30 | £9.95 | 58% |
| Leeds | 21 | £6.50 | 95% |
| London | 62 | £6.25 | 88% |
| Manchester | 38 | £6.00 | 100% |
| **All four** | **151** | **£6.93** | **86%** |

A supermarket meal deal costs £3.74–£4.25.

## The files

The data is published on our own site, so these links are always the current version:

- CSV — https://ukfoodspot.co.uk/data/cheap-eats-index.csv
- JSON — https://ukfoodspot.co.uk/data/cheap-eats-index.json
- Method, column notes and the limits — https://ukfoodspot.co.uk/data.html

## Columns

`id`, `city`, `area`, `place`, `dish`, `cuisine`, `category`, `price_gbp`, `price_text`, `halal`, `vegan_option`, `gluten_free_option`, `address`, `source_name`, `source_url`, `page_url`

## How the prices are collected

Each price is read from a named source: the place's own menu or site, a delivery listing, or a published guide. The `source_url` column is there so any row can be checked without asking us.

Where a dish is sold as a range, we publish the **lowest** price in that range — never an average, never the top of it. The same rule applies to every figure we have ever published. Dishes without a confirmed price stay in the file with `price_gbp` empty, rather than guessed.

## What this is not

Not a census of UK restaurants. It is one dish at each independent place *we have listed*, in four cities, chosen by us. It leans towards places that publish their prices. Prices are as last reported and change without notice — treat a figure as "what it was when we read it".

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Free to use, including commercially. The only condition is credit:

> UK Food Spot Cheap Eats Index — https://ukfoodspot.co.uk/data.html — CC BY 4.0

## Who we are

[UK Food Spot](https://ukfoodspot.co.uk/) is a free guide to cheap independent eats in the UK. No ads, no sign-up, no commission, and restaurants cannot pay to be listed or to rank higher. Why, and how you can check it: https://ukfoodspot.co.uk/why-free.html
