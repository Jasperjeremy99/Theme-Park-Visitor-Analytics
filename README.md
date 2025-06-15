# Theme-Park-Visitor-Analytics

This repository contains a data analysis project focused on understanding visitor behavior and sentiment within theme parks. By applying sentiment analysis and topic modeling techniques to visitor feedback, the project aims to identify key areas for improvement and enhance overall visitor experience.

## Project Goal

The primary goal is to extract actionable insights from theme park visitor data to address specific business questions, such as identifying key visitor segments, optimizing operational times, and understanding visitor perceptions of services and attractions to drive strategic improvements.

## Files Overview

* **`theme_park_visitor_analytics.ipynb`**: This Jupyter notebook provides a detailed walkthrough of the visitor analytics pipeline:
    * **Data Exploration**: Initial steps to clean, understand, and prepare the theme park visitor data for analysis.
    * **Sentiment Analysis**: Utilizes VADER to perform sentiment analysis on visitor comments, categorizing them as positive, negative, or neutral and providing insights into overall visitor satisfaction.
    * **Topic Modeling (LDA)**: Implements Latent Dirichlet Allocation to uncover prevalent themes and discussion points within the unstructured text data of visitor reviews, helping to pinpoint specific areas of feedback.
    * **Practical Implications & Recommendations**: Translates analytical findings into concrete business recommendations aimed at improving visitor experience, such as optimizing queue times, enhancing staff interactions, and refining amenities.

## Dataset

This project relies on the `ThemePark.csv` dataset, which contains visitor information and feedback. **Please note: This data file is not included in this repository.** The Jupyter notebook is configured to load this dataset from a Google Drive path (`/content/drive/MyDrive/ThemePark.csv`). To run the notebook, you will need to obtain this dataset and ensure it is accessible at the specified path or modify the notebook to load your own theme park visitor data.

## Technologies Used

* Python
* Pandas (for data manipulation)
* NumPy (for numerical operations)
* Matplotlib & Seaborn (for data visualization)
* NLTK (for VADER Sentiment Analysis)
* Scikit-learn & Gensim (for Topic Modeling - LDA)

## Getting Started

To explore or run the analysis:

1.  Clone this repository.
2.  Ensure you have Python installed along with the necessary libraries (you can install them via `pip install pandas numpy matplotlib seaborn nltk scikit-learn gensim`).
3.  **Provide the `ThemePark.csv` dataset**: You will need to obtain this dataset and ensure it is accessible to the notebook (e.g., by uploading it to your Google Drive at the path `/content/drive/MyDrive/ThemePark.csv` if using Google Colab, or placing it in an appropriate local directory and updating the notebook's file path).
4.  Open `theme_park_visitor_analytics.ipynb` in a Jupyter environment (e.g., Jupyter Lab, VS Code with Jupyter extension, or Google Colab).
5.  Run the cells sequentially to execute the data loading, analysis, and visualization steps.

## Contact

For any questions or further information, please contact [Jeremiyah/jeremypeter016@gmail.com].
