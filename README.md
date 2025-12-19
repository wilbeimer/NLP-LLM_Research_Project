# NLP-LLM_Research_Project

## Setup

1. Prerequisites

    - Python installed (recommend 3.13+, not sure if any others work I didn't test)
    - pip (Python package manager)
    - Optionally, install Anaconda

2. Clone the repository

    ```
    git clone https://github.com/wilbeimer/NLP-LLM_Research_Project

   
    cd NLP-LLM_Research_Project
    ```

4. Create a virtual environment (optional but recommended)

    ```
    python -m venv venv      # create a virtual environment called 'venv'

   
    source venv/bin/activate # Linux/Mac

   
    venv\Scripts\activate    # Windows
    ```

5. Install required packages

    ```
    pip install -r requirements.txt

   
    python -m spacy download en_core_web_lg
    ```

6. Run Jupyter Notebook

    ```
    jupyter notebook
    ```


7. Change Kernel

    If you are using a venv rather than the root python, jupyter requires you to select that kernel for the packages to work correctly

    1. Click on "kernel" from the menu bar
    2. From the drop down select "Python (name-of-your-venv)"


8. Optional: Run in Google Colab

    1. Go to Google Colab
    2. File → Open notebook → GitHub → paste your repo URL
    3. Open and run it in the cloud (no local setup needed)


## Sources

### Books
- [Emma][1]
- [Pride And Prejudice][2]
- [Sense And Sensibility][3]

### Text Rank
- [Text Summarization with NLP][4]
- [TextRank Algorithm][5]

### Basic Summarization in Python
- [Text Summarization in Python][6]

### Transformers
- [Hugging Face Transformers][7]

### LLMs
- [ChatGPT Developer Start][8]
- [Gemini API Reference][9]

### Evaluation
- [Understanding BLEU and ROUGE][10]
- [BERTScore][11]
    
[1]: https://www.gutenberg.org/ebooks/158 "Emma"
[2]: https://www.gutenberg.org/ebooks/26301 "Pride and Prejudice"
[3]: https://www.gutenberg.org/ebooks/161 "Sense And Sensibility"
[4]: https://www.geeksforgeeks.org/nlp/text-summarization-in-nlp/ "Text Summarization"
[5]: https://medium.com/@yassineerraji/understanding-textrank-a-deep-dive-into-graph-based-text-summarization-and-keyword-extraction-905d1fb5d266 "TextRank"
[6]: https://stackabuse.com/text-summarization-with-nltk-in-python
[7]: https://thepythoncode.com/article/text-summarization-using-huggingface-transformers-python
[8]: https://platform.openai.com/docs/quickstart
[9]: https://ai.google.dev/gemini-api/docs/text-generation
[10]: https://www.geeksforgeeks.org/nlp/understanding-bleu-and-rouge-score-for-nlp-evaluation/#introduction-to-bleu-and-rouge-scores
[11]: https://machinetranslate.org/bertscore
