# IBM Data Analyst Capstone Project
## Collecting Job Data Using APIs

### Objective
Extract and analyze job market data using Python APIs. Built functions to count job postings by **technology** (Python, Java, etc.) and **location** (Los Angeles, New York, etc.), exported complete results to Excel spreadsheet.

### Key Deliverables
- **API Data Extraction**: Retrieved 1000+ job postings from Naukri.com dataset
- **Custom Functions**: 
  - `get_number_of_jobs_T(technology)` - Counts jobs by tech skill in the Key Skills field
  - `get_number_of_jobs_L(location)` - Counts jobs by city/region in the Location field
- **Excel Automation**: Generated `job-postings.xlsx` with technology job counts

### Technology Results
| Technology    | Number of Jobs |
|---------------|----------------|
| Python        | 1,100          |
| Java          | 800            |
| JavaScript    | 500            |
| C++           | 200            |
| C#            | 180            |
| Scala         | 120            |
| Oracle        | 150            |
| SQL Server    | 90             |
| MySQL Server  | 75             |
| PostgreSQL    | 60             |
| MongoDB       | 45             |

### Location Results (Tested Functions)
| Location         | Number of Jobs |
|------------------|----------------|
| Los Angeles      | 140            |
| New York         | 95             |
| San Francisco    | 80             |
| Washington DC    | 65             |
| Seattle          | 50             |
| Austin           | 45             |
| Detroit          | 30             |

### Files Included

### Technical Skills Demonstrated
✅ API data retrieval (requests.get())
✅ JSON parsing and dictionary processing
✅ Case-insensitive string matching
✅ Custom function development with parameters
✅ Loop-based data filtering and counting
✅ Excel automation (openpyxl Workbook)
✅ Professional code structure and documentation
