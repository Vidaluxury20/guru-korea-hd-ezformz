# GuRu Korea — Column B catalog for EZFormz

452 catalog entries mapped to Column B prices in USD. Product IDs remain stable across the CSV and photo filenames.

| Photo status | Entries |
| --- | ---: |
| HD replacement | 169 |
| Retained source photo | 210 |
| Photo pending | 73 |
| Total | 452 |

## Files

- `ezformz_products.csv`: product names, pack sizes, Column B unit prices, image URLs, source pages, photo sources and review flags.
- `images/`: 379 product photos named by item ID, such as `GKR-001.jpg`.
- `GuRu_Korea_Column_B_Price_List.pdf`: the refreshed Column B catalog.
- `catalog-summary.json`: counts by photo status.
- `README.txt`: import notes.

## Form field mapping

| CSV column | Form field |
| --- | --- |
| `item_id` | Product reference / SKU |
| `product_name` | Product name |
| `pack_size` | Pack size / option description |
| `price_column_b_usd` | Unit price in USD |
| `image_url` | Product image URL |

The image paths and IDs were validated against all 379 uploaded photo files. All 452 prices were checked against the supplied catalog data. Prices are from Column B; image suppliers' retail prices are not used.

## Before building the form

This repository is **private**. The prepared raw GitHub image URLs will not load anonymously in EZFormz until public visibility is approved and enabled, or the photos are placed on another accessible host.

73 entries have blank image URLs and need photos. The retained source images are not new HD replacements. Review the `review_flag` column for repeated listings and grouped variants; source entries were preserved rather than silently merged.

The CSV provides the field mapping for building the new form. Compatibility with the actual EZFormz importer has not been tested; map the fields in its importer if supported, or use the CSV for product entry.
