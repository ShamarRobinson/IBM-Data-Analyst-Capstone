# Web Scraping – IBM Data Analyst Capstone

This section demonstrates how to extract structured data from a web page using Python and the `BeautifulSoup` library. The goal is to collect information on programming languages and salaries for later analysis and visualization.

## Scope and Approach

- Retrieved the target web page at `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/datasets/Programming_Languages.html` using the `requests` library.
- Parsed the HTML content with `BeautifulSoup` to locate the table of programming languages and average annual salaries.
- Extracted the **Language** and **Average Salary** fields from each table row and stored them in a `pandas` DataFrame.
- Exported the scraped data to a CSV file named `popular-languages.csv` for reuse in downstream analysis.

## Output and Data Structure

- **Output file**: `popular-languages.csv`
- **Columns**:
  - `Language` – Name of the programming language (e.g., Python, Java, R, JavaScript).
  - `Average Salary` – Annual average salary for that language (formatted as text with a leading `$`).

This dataset provides a clean, tabular view of programming‑language salary information that can be used for comparisons, rankings, and simple visualizations in later stages of the project.

## Skills Demonstrated

- ✅ Web scraping using Python, `requests`, and `BeautifulSoup`  
- ✅ HTML parsing and structured data extraction from HTML tables  
- ✅ Data storage in CSV format using `pandas`  
- ✅ Creation of reproducible, self‑contained data‑collection scripts
