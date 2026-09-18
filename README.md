# Amazon Prime Movies EDA

This project performs an Exploratory Data Analysis (EDA) on a dataset of Amazon Prime movies. It walks through data wrangling, cleaning, and visualizations to extract insights regarding top-rated content and the historical timeline of the platform.

## Project Workflow
* **Data Extraction:** Connects to Google Drive to import `amazon prime movies.csv`.
* **Data Cleaning & Wrangling:**
    * Fills missing `IMDb Rating` and `Year of Release` data using the column mode.
    * Standardizes missing `Plot` fields by filling them with 'No Data'.
    * Identifies and drops duplicate rows, yielding a final dataset of 8,124 rows and 7 columns.
* **Insights & Visualizations:**
    * Custom matplotlib timeline mapping Amazon's journey from a 1994 bookstore to 230 million subscriptions in 2024.
    * Horizontal bar chart highlighting the Top 10 movies on Prime based on average IMDb ratings.
    * Analysis of regional Indian cinema, concluding that regional language films frequently score higher ratings than mainstream Hindi movies due to authentic storytelling and deep cultural resonance.

---

## Dataset Overview

The dataset contains information on 8,124 original movie entries across various languages and genres. 

| Column Name | Description |
| :--- | :--- |
| **Movie Name** | The title of the film. |
| **Language** | The primary audio language (e.g., Tamil, English, Telugu, Malayalam, Hindi). |
| **IMDb Rating** | The user rating from IMDb (out of 10). |
| **Running Time** | Duration of the movie (e.g., "1 h 35 min"). |
| **Year of Release** | The year the movie was released. |
| **Maturity Rating** | Recommended viewing age (e.g., 18+, 13+, All). |
| **Plot** | A brief synopsis of the movie's storyline. |

---

## Conclusion

* **Platform Evolution:** Amazon Prime has strategically transformed from a localized online bookstore into a global streaming powerhouse.
* **Viewer Preferences:** Analysis of the catalog and viewer ratings indicates a clear audience preference for authentic, regional storytelling over mainstream releases, particularly within Indian cinema.
* **Strategic Impact:** Delivering culturally resonant content is essential for sustaining high viewer satisfaction and driving ongoing platform engagement.
## Requirements

Ensure you have the necessary dependencies to run the notebook by installing the packages in `requirements.txt`:

```bash
pip install -r requirements.txt

