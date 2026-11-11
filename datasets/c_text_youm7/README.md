# Youm7 News Text Dataset

## Overview

`youm7_real_data.csv` contains **12,090 Arabic news records** scraped from
[Youm7](https://www.youm7.com/). The records were collected from the site's
section listing pages and are intended for Arabic text classification,
information retrieval, and exploratory natural-language processing.

## File format

- **File:** `youm7_real_data.csv`
- **Encoding:** UTF-8
- **Delimiter:** comma
- **Header:** included
- **Rows:** 12,090 data rows
- **Text language:** primarily Arabic

## Columns

| Column | Description |
| --- | --- |
| `news_id` | Unique Youm7 article identifier. |
| `source_site` | Website from which the record was collected. |
| `section_url` | URL of the section listing page used during scraping. |
| `page_number` | Listing-page number within the section. |
| `article_url` | URL of the article on Youm7. |
| `image_url` | URL of the associated article image. |
| `publish_date_raw` | Publication date and time as displayed by the site, in Arabic. |
| `title_html` | Article title, including HTML markup. |
| `title_text` | Article title with the visible text extracted. |
| `summary_html` | Article summary, including HTML markup. |
| `summary_text` | Article summary with the visible text extracted. |
| `full_raw_html` | Raw HTML for the scraped news listing/card. |
| `word_count_raw` | Word-count value supplied by the source record. |
| `category_label` | Arabic category label used as the class label. |

## Categories

There are seven category labels:

| Label | Records | Meaning |
| --- | ---: | --- |
| `علوم_وتكنولوجيا` | 1,879 | Science and technology |
| `سياسة_وأخبار_مصر` | 1,783 | Politics and Egypt news |
| `محافظات_ومجتمع` | 1,770 | Governorates and society |
| `فن_وثقافة` | 1,746 | Arts and culture |
| `اقتصاد_وبورصة` | 1,741 | Economy and stock market |
| `رياضة_مصرية` | 1,683 | Egyptian sports |
| `حوادث_وقضايا` | 1,488 | Accidents and cases |

