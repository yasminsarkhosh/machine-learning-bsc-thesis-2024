
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
Bachelor Thesis: Directory Structure of Machine-Learning-BSC-Thesis-2024
==============================
machine-learning-bsc-thesis-2024/
│
├── grobid_client_python/                                   # GROBID client for extracting XML data from PDF files
│
├── project_submission/                                     # Project submission files
│   ├── 00_project/                                         # Project files
│   │   ├── annotation_data/
│   │   │   └── annotation_data_raw.xlsx                    # Raw annotation data 
│   │   | 
│   │   ├── annotation_guide_and_scheme/                    # Annotation guide and scheme files
│   │   │   ├── annotation_guide_details.docx
│   │   │   ├── annotation_guide_details.pdf
│   │   │   └── annotation_scheme_and_guide.xlsx 
│   │   |
│   │   └── notebooks/  # Project notebooks
|   |       |
│   │       ├── 00MICCAI_total_outputs/                                     # Total outputs of the project 
|   |       |    ├── 01MICCAI_all_outputs/                                  # All outputs of the project notebook 01
|   |       |    |    └── 01MICCAI_2023_notebook_database_miccai2023.csv
|   |       |    |
|   |       |    ├── 03MICCAI_all_outputs/                                  # All outputs of the project notebook 03
|   |       |    |    ├── 03MICCAI_notebook_cleaned_dataframes/             # Cleaned dataframes    
|   |       |    |    ├── 03MICCAI_2023_notebook_GROBID_dataframes/         # GROBID dataframes
|   |       |    |    └── 03MICCAI_2023_notebook_GROBID_processed_volumes/  # GROBID processed volumes
|   |       |    |    |    
|   |       |    |    ├── 03MICCAI_2023_notebook_100_randomly_selected_papers.csv    
|   |       |    |    ├── 03MICCAI_2023_notebook_df_paper_extractions_all_cleaned.csv
|   |       |    |    ├── 03MICCAI_2023_notebook_df_paper_extractions_cancer_csv
|   |       |    |    └── 03MICCAI_2023_notebook_df_paper_extractions_patients_and_cancer.csv
|   |       |    |
|   |       |    ├── 04MICCAI_all_outputs/                                  # All outputs of the project notebook 04
|   |       |    |    ├── 04MICCAI_notebook_extracted_keywords/
|   |       |    |    └── 04MICCAI_notebook_extracted_sentences/
|   |       |    |    
|   |       |    └── 05MICCAI_all_outputs/                                  # All outputs of the project notebook 05
|   |       |        ├── 05MICCAI_notebook_data_visualization/
|   |       |        |
|   |       |        ├── 05MICCAI_notebook_dataset_counts.csv
|   |       |        ├── 05MICCAI_notebook_normalized_datasets.csv
|   |       |        ├── 05MICCAI_notebook_preprocessed_annotation_data.csv
|   |       |        ├── 05MICCAI_notebook_unique_image_types.csv
|   |       |        └── 05MICCAI_notebook_unique_organs.csv
|   |       |    
│   │       ├── 01MICCAI_2023_HTML_Data_Extraction.ipynb                            # HTML data extraction notebook
│   │       ├── 02MICCAI_2023_PDF_Segmentation.ipynb                                # PDF segmentation notebook
│   │       ├── 03MICCAI_2023_XML_Data_Extraction_and_Paper_Selection.ipynb         # XML data extraction and paper selection notebook
│   │       ├── 04MICCAI_2023_Keyword_Sentence_Extraction.ipynb                     # Keyword and sentence extraction notebook
│   │       └── 05MICCAI_2023_Annotation_Analysis.ipynb                             # Annotation analysis notebook
│   │                 
│   ├── 01_experiment                   # Experiment files
│   ├── 02_old_notebooks                # Old notebooks
│   └── 03_archive                      # Archive files
│
├── requirements/                       # Python packages requirements per notebook       
│   ├── 01MICCAI_requirements.txt
│   ├── 02MICCAI_requirements.txt
│   ├── 03MICCAI_requirements.txt
│   ├── 04MICCAI_requirements.txt
│   └── 05MICCAI_requirements.txt
│
├── venv/                               # Virtual environment
│
├── meeting_w_theo.md                   # Meeting notes with Theo
├── README.md                           # Instructions and descriptions
├── requirements.txt                    # Python packages requirements overview
└── weekly-meetings-yasmin.md           # Weekly meetings notes

