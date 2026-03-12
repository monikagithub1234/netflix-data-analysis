# Netflix Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset to understand patterns in movies and TV shows available on the platform.

The goal of this project is to clean the dataset, analyze the features, and visualize insights such as content distribution, release trends, and genre popularity.

Dataset contains information like:
- Show ID
- Type (Movie / TV Show)
- Title
- Director
- Cast
- Country
- Release Year
- Rating
- Duration
- Genre
- Description
3️⃣ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
4️⃣ Project Workflow
1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handling Missing Values
5. Exploratory Data Analysis
6. Data Visualization
7. Insights Extraction
5️⃣ Data Cleaning

Explain what you did:

- Checked dataset shape and column information
- Identified missing values
- Handled null values in columns like director, cast, and country
- Converted date_added column to datetime format
6️⃣ Exploratory Data Analysis

Examples of analysis:

- Movies vs TV Shows distribution
- Content release trend by year
- Country-wise content production
- Most common genres
- Rating distribution
7️⃣ Visualizations

You can mention graphs like:
<img width="597" height="823" alt="{DF2F93AC-9018-4EFC-BB70-E4CAF39DA149}" src="https://github.com/user-attachments/assets/dd1d2a30-ae8a-4d13-98c0-90f642151049" />
<img width="570" height="853" alt="{2C574B02-DF74-4451-A2DA-91E88C032A90}" src="https://github.com/user-attachments/assets/981c0324-a7d4-4f51-8f03-444a9c565537" />
<img width="759" height="421" alt="{6225AA5C-0ABF-4639-BEBD-39068D0BCBFB}" src="https://github.com/user-attachments/assets/6d9bbc05-3557-453e-af98-dc76d17cf853" />
Bar charts
Count plots
Heatmaps
Distribution plots

Libraries used:

Matplotlib

Seaborn

8️⃣ Key Insights

Example:

- Netflix contains more Movies compared to TV Shows
- Content production increased rapidly after 2015
- USA produces the highest number of Netflix titles
- Drama and International Movies are among the most common genres
9️⃣ Project Structure
Netflix-Data-Analysis
│
├── netflix_data_analysis.ipynb
├── netflix_titles.csv
└── README.md
🔟 Future Improvements
- Build a recommendation system
- Apply machine learning models
- Create an interactive dashboard using Streamlit
