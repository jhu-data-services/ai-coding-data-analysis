# AI for Coding and Data Analysis

Materials for a workshop that provides an introduction to using AI assistance in coding and data analysis.

Workshop materials · October 14, 2026 · Inna Kouper, Digital Scholarship and Data Services, Sheridan Libraries, Johns Hopkins University

## Getting started

You need a Google account (a personal Gmail works) and a web browser. Nothing to install, nothing to upload.

### Before the workshop (5 minutes)

1. Click [Open in Colab](https://colab.research.google.com/github/jhu-data-services/ai-coding-data-analysis/blob/main/notebooks/starter_notebook.ipynb) and sign in to Google if asked.
2. Check that you see a notebook titled *AI for Coding and Data Analysis: starter notebook*.
3. Check that the **Gemini** button (✦) appears in Colab. If it doesn't, try a personal Google account; some school or organization accounts have Colab's AI features turned off.

### During the workshop

1. Open the [starter notebook in Colab](https://colab.research.google.com/github/jhu-data-services/ai-coding-data-analysis/blob/main/notebooks/starter_notebook.ipynb).
2. Choose **File → Save a copy in Drive**. A new tab opens with *Copy of starter_notebook.ipynb*. Work in that tab and close the original.
3. Click the title at the top left and add your name.
4. Run the first code cell with ▶. When Colab warns *"This notebook was not authored by Google,"* click **Run anyway**. The cell downloads the survey files; you'll see them in the 📁 Files panel on the left.

Your copy is saved in Google Drive, in the **Colab Notebooks** folder.

### If something doesn't work

- **"Changes will not be saved" banner:** you're in the original. Choose **File → Save a copy in Drive**.
- **Wrong Google account:** check the account icon at the top right of Colab.
- **Runtime disconnected after a pause:** click **Reconnect** and run the first cell again (the downloaded files are cleared when the runtime resets).
- **The link doesn't open:** in Colab, choose **File → Open notebook → GitHub**, enter `jhu-data-services/ai-coding-data-analysis`, and select `notebooks/starter_notebook.ipynb`.
- **Last resort:** download `notebooks/starter_notebook.ipynb` from this repository and use **File → Upload notebook** in Colab.

## Contents

- `notebooks/starter_notebook.ipynb`: the workshop notebook. Its first cell downloads the data below.
- `data/data_practices_survey_2026-09-30.xlsx`: first export of a fictional Research Data Practices survey (Qualtrics layout).
- `data/data_practices_survey_2026-10-09.xlsx`: a later, cumulative export of the same survey.
- `data/data_practices_survey_codebook.xlsx`: questions, response options, and skip logic.

## About the data

The survey data are **synthetic**: generated for teaching, with the kinds of problems real survey exports have
(extra header rows, test and incomplete responses, a duplicate submission, multi-select answers, free-text fields).
No real people responded. IP addresses use reserved documentation ranges.

## License

MIT License; see `LICENSE`.
