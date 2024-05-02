
# **Bridging the Data Gap: An Experimental Investigation into Demographic Representation in Healthcare AI**
An overview of the thesis project.



## Project Submission
***
### GitHub Repository Structure
Details about the directory structure can be found in the following link:
- **[Directory Structure](directory_structure.txt)**

***

### Installation and Setup
#### Dependencies Installation
To install the necessary Python packages, use the `requirements.txt` file. Below is the content of `requirements.txt` which lists all the packages used in the project:

```markdown
# requirements.txt with the packages you used
pandas==1.5.3
numpy==1.26.4
et-xmlfile==1.1.0
grobid-client-python==0.0.8
lxml==5.2.1
openpyxl==3.1.2
plotly==5.20.0
PyPDF2==3.0.1
PyMuPDF==1.24.2
PyMuPDFb==1.24.1
regex==2023.12.25
seaborn==0.13.2
squarify==0.4.3
zipp==3.17.0
```


To install these packages, run:
```bash
pip install -r requirements.txt
```

### Additional Setup for GROBID
To use GROBID, follow these steps:
[GROBID GitHub Repository](https://github.com/kermitt2/grobid_client_python)

1. **Download GROBID:**
   ```bash
   wget https://github.com/kermitt2/grobid/archive/0.8.0.zip
   ```

2. **Unzip the downloaded file:**
   ```bash
   unzip 0.8.0.zip
   ```

3. **Change to the GROBID directory:**
   ```bash
   cd grobid-0.8.0
   ```

4. **Run GROBID:**
   ```bash
   ./gradlew run
   ```

### Python Import Statements
Below are the import statements used in the notebooks:
```python
import fitz  # PyMuPDF for PDF rendering and manipulation
import PyPDF2  # PyPDF2 for PDF file reading and manipulation
import zipfile
import requests
from bs4 import BeautifulSoup
import io
from io import BytesIO
import urllib.request
from urllib.request import urlopen
import os
import re
import regex as re
import numpy as np
import pandas as pd
from xml.etree import ElementTree as et
from lxml import etree
from collections import Counter
from grobid_client.grobid_client import GrobidClient
import matplotlib.pyplot as plt
import matplotlib as mpl
from matplotlib import colormaps
import matplotlib.patches as mpatches
import matplotlib.ticker as ticker
import squarify
import seaborn as sns
import plotly.graph_objects as go
```

### Optional Installations
Uncomment the necessary installation commands if required:
```bash
# pip install PyPDF2
# pip install xhtml2pdf requests lxml 
# pip install xhtml2pdf requests
# pip install lxml
# pip install beautifulsoup4
# pip install pandas
# pip install numpy
# pip install regex
# pip install zipfile
# pip install lxml
# pip install pandas openpyxl
# pip install beautifulsoup4 requests lxml regex
# pip install pandas openpyxl
```

### Notebooks Overview
***
This section outlines the objectives and key functionalities of each notebook included in this repository, specifically designed for processing data from the MICCAI 2023 conference.

#### Notebook: 01MICCAI
**Objective:** Automate the extraction and processing of data from HTML documents.
- **Features:** 
  - Extract titles, authors, DOIs, and page numbers from HTML content.
  - Organizes information into structured formats for further analysis.
- **Links:**
  - [MICCAI 2023 Webpage](https://conferences.miccai.org/2023/papers/)
  - [Springer Link - MICCAI 2023 Volumes](https://link.springer.com/book/10.1007/978-3-031-43907-0)

#### Notebook: 02MICCAI
**Objective:** Divide multi-article PDF volumes into individual PDFs for each article.
- **Features:** 
  - Manually remove non-article pages before automated splitting based on specified page numbers.
- **Link:** [Springer Link - MICCAI 2023 Volumes](https://link.springer.com/book/10.1007/978-3-031-43907-0)

#### Notebook: 03MICCAI
**Objective:** Preprocess and analyze XML documents from the conference.
- **Features:** 
  - Extract structured information from raw XML data.
  - Identify and extract key content such as headers and titles.
  - Focus on cancer-related research.
  - Aggregate data into structured dataframes for advanced analysis.

#### Notebook: 04MICCAI
**Objective:** Extract relevant sentences from MICCAI 2023 research papers based on specific keywords.
- **Features:** Categorize sentences by paper titles, focusing on crucial information like demographics.

#### Notebook: 05MICCAI
**Objective:** Conduct detailed analyses and annotations of medical imaging articles.
- **Features:** 
  - Extract and categorize data about organs, image types, and datasets.
  - Analyze distribution across various demographic parameters.
  - Evaluate geographical locations and disclosure status of datasets.

### Additional Resources
***
#### Annotation Data
Details and data formats used for annotation in this project:
- **[Annotation Data](project_submission/00_project/annotation_data)**

#### Annotation Guide and Scheme
Guidelines and schemes applied for data annotation within the project:
- **[Annotation Guide and Scheme](<project_submission/00_project/annotation_guide_and _scheme>)**







