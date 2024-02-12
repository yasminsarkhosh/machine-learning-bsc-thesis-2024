The material in the weekly-meetings-yasmin.md is derived from "Whitaker Lab Project Management" by Dr. Kirstie Whitaker and the Whitaker Lab team, used under CC BY 4.0. weekly-meetings-yasmin.md is licensed under CC BY 4.0 by [Yasmin Sarkhosh].

# Yasmin's Weekly Meeting Notes

* [06 feb 2024](#date06-feb-2024)

### Date: 06 feb 2024
### Who helped you this week?
N/A
### What did you achieve?
* Settled on a research direction 
* Finished preliminary problem statement 
* Experiments: 
  * examining datasets in papers in MICCA 2023 for demographic information
* Looking into potential research questions 
* Looking for relevant literature 
* Setting up a Git repo with weekly meetings
* https://github.com/yasminsarkhosh/machine-learning-bsc-thesis-2024.git

### What did you struggle with?
N/A

### What would you like to work on next week?
* Finalizing research questions 
* Finalizing the methodology for the project
* Experiments - looking into MICCA 2023 
  * Experiment 1 - on webpage**
      - ‘command F’ - ‘cancer’
      - randomly selecting papers


### Where do you need help from Veronika?
* Finalizing research questions 
* Finalizing the methodology for the project!
* Setting research boundaries (finalizing a scope for the project) 

### Any other topics
N/A

### What are the agreements after this meeting? (to fill in after the meeting) 

#### Looking into MICCA 2023 ONLY
#### Write instructions
- How did I find the papers?
    - ‘command F’ - ‘cancer’
- Annotation scheme
    - Categories: why these?
    - How do I examine/annotate papers? 
- Find number of all papers
    - Define the number of rows from the total number of papers
    - Add all papers
    - Filter by ‘cancer’
        - What organ is in focus?
        - What image type?
    - Find the dataset(s)
        - Number of dataset(s)?
        - What are the demographic information?
        - What are other subgroups in mentioned in the paper?
- Think of a 'analysis code' for my method that makes it applicable for future analysis
- Remember: insert all experiments into ‘weekly meetings’


[13 feb 2024](#date-13-feb-2024)

### Date: 13 feb 2024
### Who helped you this week?

### What did you achieve?
Extracting all papers from MICCA 2023 webpage into an Excel sheet 
  * Experiment 2 - Excel Power Query**
    - save page as text file in ARC browser
    - open the file with Excel
        - data - get data - from text file - clean and remove html tags
        - result: a whole list of papers in excel
        - 730 papers in total extracted from micca 2023 webpage
        - 23 papers with 'cancer' in their titles
        - in progress: check for 'cancer' in the content of the papers
  * Manually found 10 volumes in PDF format with all 730 papers
  * Experiment 3 - search for cancer-related papers (not just by title)
    - Downloaded 10 PDF volumes with containting all papers from this url: https://link.springer.com/book/10.1007/978-3-031-43999-5  
    - opened the PDFs and searched for 'cancer' by command + F 
      - papers, with 'cancer' in their titel was marked with orange
      - papers, with 'cancer' beyond their titel was marked with purple
    - No. of papers with 'cancer' in their title:
    - No. of papers with 'cancer' beyond their title (in the content):
    - No. of papers in total: 730

  * Annotation scheme
    - Planning how to analyse each paper for demographics   
### What did you struggle with?
Writing code that will:
* Extract ALL 730 PDFs from the MICCA 2023 webpage by webscrapping 
  - Currently managed to extract all hmtl from the page, however still struggling with downloading each pdf from hmtl into a folder
    - Managed to extract all direct pdf urls into a list, however still not able to extract text from/download each pdf
* Extract PDFS with 'cancer' in their title from webpage

### What would you like to work on next week?


### Where do you need help from Veronika?
* Web scraping
* Keep me on the right track  

### Any other topics
* I need to reschedule meetings if possible due to work (not all tuesdays, but some)

### What are the agreements after this meeting? (to fill in after the meeting) 

