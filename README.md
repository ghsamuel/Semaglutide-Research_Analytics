## Semaglutide-Research_Analytics
Analyze global Semaglutide research trends using PubMed and ClinicalTrials.gov data. Includes data cleaning, fuzzy matching, publication type classification, and visualizations with Plotly and Folium. Highlights top countries, centers, and publication patterns in an interactive notebook.
## Semaglutide Global Research Visualization

This project explores global trends in Semaglutide-related research using data from PubMed and ClinicalTrials.gov.

###  Files

- `Semaglutide_Global_Publications.ipynb`: Main analysis notebook
- `data/`: Source Excel files
- `images/`: (Optional) Exported charts and visuals

###  Key Features

- Cleans and classifies publication types (Trial, Guideline, Journal)
- Uses fuzzy matching to align country names
- Generates visual insights with Plotly (bar, line, pie)
- Builds an interactive map of research centers using Folium

###  Example Output

![Sample bar chart](images/sample_chart.png)

###  Requirements

Install Python libraries:

```bash
pip install pandas numpy plotly openpyxl folium fuzzy_pandas
