### Project Overview

This project automates the creation of the *Consumer prices of cultural goods and services* article from Eurostat’s *Statistics Explained* series. By using the Eurostat API and reproducible coding practices, it streamlines the production of an up-to-date and publication-ready version of this article.

### Key Components

#### Data Retrieval and Processing
We use the Eurostat API to automatically access and retrieve the latest data on consumer prices for cultural goods and services. The script queries and transforms this data, ensuring it's in the format needed for accurate analysis and presentation.

#### Article Layout Replication
Our R Markdown script re-creates the structure and layout of Eurostat's original article by:
   - **Generating Tables, Charts, and Text**: The code is designed to produce each element in alignment with Eurostat’s visual and layout guidelines.
   - **Highlighting Trends and Key Statistics**: Each section, from trend analysis to statistical highlights, is generated with the latest data for a consistent, accurate presentation.

#### Automated Workflow
The code is built to maintain a fully reproducible workflow by:
   - **Retrieving Updated Data Automatically**: Regular API calls ensure the data is always current.
   - **Updating Visualizations**: Plots and tables refresh automatically with each new data retrieval, keeping the visuals accurate.
   - **Following Best Practices for Replicability**: Version control, minimal manual steps, automation of functions.

