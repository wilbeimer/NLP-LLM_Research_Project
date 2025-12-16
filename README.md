# NLP-LLM_Research_Project

## Setup

1. Prerequisites

Python installed (recommend 3.13+, not sure if any others work I didn't test)

pip (Python package manager)

Optionally, install Anaconda

2. Clone the repository
``
git clone https://github.com/wilbeimer/NLP-LLM_Research_Project
cd NLP-LLM_Research_Project
``

3. Create a virtual environment (optional but recommended)
``
python -m venv venv      # create a virtual environment called 'venv'
source venv/bin/activate # Linux/Mac
venv\Scripts\activate    # Windows
``


Keeps dependencies isolated.

4. Install required packages

```
pip install -r requirements.txt
python -m spacy download en_core_web_lg
```

5. Run Jupyter Notebook
jupyter notebook


6. Optional: Run in Google Colab

You can tell people:

Go to Google Colab

File → Open notebook → GitHub → paste your repo URL

Open and run it in the cloud (no local setup needed)


## Sources

### Books
[Emma][1]

[Pride And Prejudice][2]

[Sense And Sensibility][3]

### Text Rank
[Text Summarization with NLP][4]

[TextRank Algorithm][5]
    
[1]: https://www.gutenberg.org/ebooks/158 "Emma"
[2]: https://www.gutenberg.org/ebooks/26301 "Pride and Prejudice"
[3]: https://www.gutenberg.org/ebooks/161 "Sense And Sensibility"
[4]: https://www.geeksforgeeks.org/nlp/text-summarization-in-nlp/ "Text Summarization"
[5]: https://medium.com/@yassineerraji/understanding-textrank-a-deep-dive-into-graph-based-text-summarization-and-keyword-extraction-905d1fb5d266 "TextRank"

