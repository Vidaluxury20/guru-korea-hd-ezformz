# GuRu Korea - Column B catalog for EZFormz

452 stable catalog entries with Column B prices in USD. All prices and IDs were checked against the supplied catalog. This update fills 71 of the original 73 blank entries and upgrades 19 retained photos.

| Photo status | Entries |
| --- | ---: |
| HD replacement | 219 |
| New source photo below HD | 40 |
| Retained original | 191 |
| Exact photo pending | 2 |
| Total | 452 |

450 entries have mapped image files.

## Form field mapping

| CSV column | Form field |
| --- | --- |
| item_id | Product reference / SKU |
| product_name | Product name |
| pack_size | Pack size / option description |
| price_column_b_usd | Unit price in USD |
| image_url | Product photo URL |

`ezformz_products.csv` contains the mapping. `photo-audit.csv` records native file dimensions, source pages and review flags. `needs-hd-photo.csv` lists 233 entries needing a new HD source. `photo-pending.csv` lists the two missing exact matches.

HD means the published file measures at least 1000 pixels on both sides. Supplier files can themselves be enlarged or compressed. Smaller real source photos are labeled below HD. No missing product photos were invented or AI-upscaled.

## Remaining exact matches

- GKR-008: Medytox 100iu. Confirm which Medytox brand this catalog entry represents and supply its exact photo.
- GKR-349: Trengamin Injection 500mg. Supply the exact 500mg pack photo and confirm catalog pack text.

Source product names, pack text, IDs and Column B prices are preserved. Review grouped variants, packaging changes, watermarks and source/catalog unit differences in `review_flag`.

## Image access for the form

The repository is public. The raw GitHub image URLs in `ezformz_products.csv` can load without signing in and can be used as product image URLs in the form. Compatibility with the actual EZFormz importer has not been tested.
