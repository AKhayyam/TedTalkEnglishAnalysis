# TED Talks YouTube Analysis

## Project Overview

This project analyzes the top 5 most viewed TED Talks on YouTube to extract and identify the unique words used in English. The goal is to gain insights into the vocabulary used in these influential talks and explore patterns in their language.

## Data Source

The dataset consists of transcripts from the top 5 most viewed TED Talks on YouTube. The transcripts were processed using Python to extract and analyze unique words.

Technologies Used

Python: Used for data processing and analysis

Libraries: Pandas, NumPy, NLTK (Natural Language Toolkit), Matplotlib (for visualization)

Excel: Stores and presents the extracted unique words

Project Structure

├── data/                     # Contains transcripts and extracted words
├── analysis/                 # Python scripts for processing and analyzing data
│   ├── ted_talks_analysis.py # Main analysis script
├── results/                  # Final extracted unique words in Excel format
├── README.md                 # Project documentation

Methodology

Data Collection: Extracted transcripts from the top 5 most viewed TED Talks on YouTube.

Preprocessing: Cleaned text data by removing punctuation, stopwords, and special characters.

Tokenization: Split text into individual words.

Unique Word Extraction: Identified unique words for each TED Talk.

Data Storage: Saved results in an Excel file for further analysis and sharing.

Navigate to the project directory:

cd tedtalks-analysis

Install dependencies:

pip install -r requirements.txt

Run the analysis script:

python analysis/ted_talks_analysis.py

Check the results in the results/ folder.

Contributing

Feel free to contribute by improving the analysis, adding visualizations, or expanding the dataset.

License

This project is open-source and available under the MIT License.
