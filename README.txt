# GuRu Korea - Column B catalog for EZFormz

452 stable catalog entries with Column B prices in USD.

Photo counts: {"HD replacement": 219, "Photo pending": 2, "Retained original": 191, "New source photo (below HD)": 40}. 450 entries have mapped photo files. This update fills 71 of the original 73 blank entries.

`ezformz_products.csv` maps item_id to product reference, product_name to name, pack_size to option description, price_column_b_usd to unit price, and image_url to product photo. `photo-audit.csv` records resolutions and review flags. `needs-hd-photo.csv` lists entries needing a new HD source. `photo-pending.csv` lists missing exact matches.

HD means the published file measures at least 1000 pixels on both sides. Supplier files can themselves be enlarged or compressed. No missing product photos were invented or AI-upscaled. Smaller real source photos are labeled below HD. Retained originals remain identified.

Source product names, pack text, IDs and Column B prices are preserved. Review grouped variants, packaging changes, watermarks and source/catalog unit differences in review_flag. Medytox 100iu is ambiguous between Medytox brands; Trengamin 500mg lacks a verified exact pack photo. Supply exact supplier assets for these two entries.

The repository remains private. Raw GitHub image URLs require authenticated access and cannot serve anonymous EZFormz visitors. Export the ZIP photos to your form's accessible image host before using the form. The actual EZFormz importer has not been tested.
