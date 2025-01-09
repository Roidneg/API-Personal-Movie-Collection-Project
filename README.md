# Movie Collection Analysis

## Project Overview
This project explores patterns and trends within my personal movie collection, spanning a few hundred titles. The focus is on analyzing key attributes such as **Genre**, **Release Year**, **Release Decade**, and **Format** (e.g., TV, Movie, Anime). The dataset is derived from a curated Google Sheet of my collection.

Through data analysis and visualizations, the project aims to highlight:
- Genre distributions over decades.
- Format preferences within the collection.
- Trends in specific genres like **Horror** and **Comedy**.

## Key Features
- **Data Source:** A Google Sheet containing columns:
  - `Title`
  - `Genre`
  - `Release Year`
  - `Release Decade`
  - `Format`
- **Data Cleaning:**
  - Grouped minor genres into a "Miscellaneous" category for better visual clarity.
  - Ensured consistent formatting for columns.
- **Visualizations:**
  - Heatmap: Showcasing genre distribution by decade.
  - Pie Chart: Distribution of genres with smaller categories grouped.
  - Bar Chart: Titles by release decade and format.
  - Line Chart: Comparative analysis of **Horror** vs. **Comedy** trends over decades.

## Tools and Libraries
- **Python**: Core language for analysis and visualization.
- **Libraries**:
  - `pandas`: Data manipulation and cleaning.
  - `matplotlib` and `seaborn`: Data visualization.
  - `gspread`: Integration with Google Sheets.

## Highlights
### Heatmap: Genre Distribution by Decade
The heatmap reveals:
- Dominance of specific genres during particular decades.
- A personal preference for **Comedy** in the 1990s and 2000s, and **Horror** in the 1980s.

### Simplified Pie Chart: Genre Distribution
By grouping genres with less than 3% representation into "Miscellaneous," the pie chart highlights:
- Dominant genres like **Comedy** and **Action**.

### Line Chart: Horror vs Comedy Trends
The line chart compares **Horror** and **Comedy** titles over decades, showcasing:
- A peak in **Comedy** titles during the 2000s.
- A consistent presence of **Horror** in earlier decades like the 1980s.

## Future Enhancements
- Add data from additional sources (e.g., IMDb API) for enriched metadata like ratings and cast.
- Expand the analysis to other genres or collections (e.g., TV shows, documentaries).
- Automate updates by syncing live Google Sheet changes with the analysis pipeline.

## How to Use
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis and visualizations.

## Example Visualizations
### Genre Distribution Heatmap
![Heatmap Example](path/to/heatmap.png)

### Horror vs Comedy Trends
![Line Chart Example](path/to/line_chart.png)

---

## Acknowledgments
- Data sourced from my personal Google Sheet.
- Tools and libraries: Python, pandas, matplotlib, seaborn, gspread.

---

### Contact
For questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/username/repository/issues).
