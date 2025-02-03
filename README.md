```markdown
# 911 Emergency Calls Analysis

## Overview
This project analyzes 911 emergency call data from Montgomery County, PA, covering the period from December 2015 to July 2020. The analysis focuses on temporal patterns, geographic distribution, and emergency type classification using Python's data science libraries.

## Dataset Description
- **Time Range**: December 10, 2015 to July 29, 2020
- **Geographic Area**: Montgomery County, PA (15 townships)
- **Emergency Categories**: EMS, Traffic, Fire

### Key Features
- `lat`/`lng`: Geographic coordinates
- `desc`: Full call description
- `zip`: ZIP code
- `title`: Emergency type and subtype
- `timeStamp`: Date and time of call
- `twp`: Township
- `reason`: Categorized emergency type (EMS/Fire/Traffic)
- `Hour`: Hour of the day (0-23)
- `Month`: Month of the year (1-12)
- `dayofweek`: Day of the week (Mon-Sun)

## Analysis Highlights

### 1. Temporal Patterns
- Hourly, daily, and monthly call trends
- Peak call times by emergency type
- Weekend vs. weekday comparisons

### 2. Geographic Distribution
- Emergency hotspots across townships
- Spatial clustering of incident types

### 3. Emergency Type Breakdown
- EMS: ~66% (e.g., diabetic emergencies, cardiac incidents)
- Traffic: ~25% (primarily vehicle accidents)
- Fire: ~9% (including gas leaks, building fires)

## Key Findings
- **Busiest Hours**: 
  - Overall: 5-6 PM (Hour 17)
  - EMS: 3-5 PM
  - Traffic: 5-7 PM
  - Fire: 2-4 PM
- **Busiest Day**: Friday for most emergency types
- **Geographic Hotspots**:
  - Norristown: High incidence of fire-related calls
  - Lower Merion: Frequent traffic incidents

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/911-calls-analysis.git
   ```
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```
   jupyter notebook Exploratory-Data-Analysis-Of-911-Calls-Data-Using-Python.ipynb
   ```

## File Structure
```
911-calls-analysis/
│
├── data/
│   └── 911.csv
│
├── notebooks/
│   └── Exploratory-Data-Analysis-Of-911-Calls-Data-Using-Python.ipynb
│
├── README.md
└── requirements.txt
```

## Future Work
- Predictive modeling for emergency resource allocation
- Integration with real-time data streams
- Comparative analysis with other counties or time periods

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Montgomery County, PA for providing the dataset
- Contributors and maintainers of pandas, matplotlib, and seaborn libraries

```

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/30638571/bec33506-6714-4644-88e9-3c3931c353fd/Exploratory-Data-Analysis-Of-911-Calls-Data-Using-Python.ipynb
