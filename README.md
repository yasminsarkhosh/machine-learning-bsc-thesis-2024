
# Project Submission: project_submission
## Project: 00_project

### Annotation Data
***

### Annotation Guide and Scheme
***


### Notebooks
***
#### **Objective of the Notebook: 01MICCAI**
This notebook is designed to automate the extraction and processing of data from HTML documents containing information about MICCAI 2023 conference papers. It streamlines the gathering of details such as titles, authors, DOIs, and page numbers from web-scraped HTML content, organizing this information into structured data formats for usability in further analysis or as a reference.

**MICCAI 2023 webpage:** [Conference Papers List](https://conferences.miccai.org/2023/papers/)
The 730 research articles are divided across 10 PDF volumes: [Springer Link - MICCAI 2023 Volumes](https://link.springer.com/book/10.1007/978-3-031-43907-0)


#### **Objective of the Notebook: 02MICCAI**
The notebook's primary goal is to divide multi-article PDF volumes (https://link.springer.com/book/10.1007/978-3-031-43907-0)  from the MICCAI 2023 conference (https://conferences.miccai.org/2023/papers/) into individual PDFs for each article. This involves manually removing non-article pages before automated splitting based on specified page numbers for each article.

#### **Objective of the Notebook: 03MICCAI**
This notebook preprocesses and analyzes XML documents from the MICCAI 2023 conference with the aim to:
- **Extract Structured Information:** Transform raw XML data into a clean, organized format for detailed analysis.
- **Identify Key Content:** Extract headers, titles, and related text from XML documents.
- **Focus on Specific Research:** Identify and extract papers related to cancer topics.
- **Data Aggregation:** Aggregate data into structured dataframes to facilitate further analysis and insights extraction.

#### **Objective of the Notebook: 04MICCAI**
The notebook's primary goal is to extract sentences from preprocessed MICCAI 2023 research papers based on specific keywords. These sentences are categorized by paper titles and focus on gathering text that potentially contains crucial information regarding demographics and other significant areas.

#### **Objective of the Notebook: 05MICCAI**
The notebook is designed to conduct detailed analyses and annotations of medical imaging articles from the MICCAI 2023 conference. It primarily focuses on extracting and categorizing data about organs, image types, and datasets from these articles, and then analyzing how these categories distribute across various demographic parameters. Additionally, the notebook evaluates the geographical locations associated with the studies and assesses the disclosure status of datasets used within the articles.

## GitHub Repository Structure
***
[Directory Structure](directory_structure.txt)

