# Wikipedia Sample Dataset (Scraper Demo)

This repository contains a minimal sample dataset of content extracted from Wikipedia using our custom web scraping pipeline. The dataset is intended to demonstrate the structure, formatting, and quality of data collected.

## Dataset Description
The dataset includes articles with their associated content, filtered to provide a representative sample.  

Key features:  
- Text content is cleaned of HTML tags and common HTML entities for easier usage.  
- The dataset is formatted as a JSON array, where each element contains:  
  - `rule` — the rule it followed to be scraped (Text for this dataset)
  - `text` — the content that was extracted  
- Total entries: small sample for demonstration purposes (~230+ articles).  

## Considerations
This sample dataset is intentionally small, as it was created during the early development stage of our scraping and data processing pipeline. It’s meant to demonstrate format, structure, and quality rather than maximum capacity.

The underlying tools—including the crawler, cleaner, and pipeline—are undergoing major upgrades to reduce hardcoding, improve efficiency, and eliminate resource leakage. The system is fully capable of handling much larger datasets and is designed to scale to meet diverse client needs without compromising quality or performance.

## Attribution
All content in this sample comes from a single Wikipedia URL collected at a single timestamp. For more professional or larger-scale projects, more detailed metadata (such as multiple URLs, collection timestamps, and source details) will be included to ensure transparency and traceability.  

## Usage
This dataset is ideal for:  
- Testing and prototyping NLP models on Wikipedia text  
- Research projects involving encyclopedic content  
- Educational purposes related to data extraction and text analysis  

## File List
- `wiki_datasample.json` — The raw JSON sample dataset
- `wiki_metadata.json` — The URL, timestamp and success status of the scrape  
- `README.md` — This file with dataset description, considerations, and attribution  

## License
This sample dataset and the accompanying code are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) license. You are free to share and adapt the dataset as long as proper attribution is given and derivative works are distributed under the same license.

## Contact
If you use this dataset or have questions, feel free to open an issue or contact me.  

cleanai.datasets@gmail.com

Custom dataset creation, data cleaning, and specialized scraping services are available for businesses and researchers.
