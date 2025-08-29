### **Sentence Tokenization Comparison**

This repository provides a Python-based analysis comparing the performance of different sentence tokenization techniques. The goal is to evaluate the accuracy and efficiency of popular tokenizers on diverse text types, including those with abbreviations, unconventional punctuation, and complex sentence structures.

### **Project Goals**

The main objectives of this project are to:

*   Compare the performance of three widely-used sentence tokenizers from NLTK:
    
    *   **RegexpTokenizer** – A rule-based tokenizer using regular expressions.
        
    *   **sent\_tokenize** – A pre-trained tokenizer from NLTK designed for general-purpose sentence splitting.
        
    *   **PunktSentenceTokenizer** – A machine-learning-based tokenizer trained on a large corpus for context-aware sentence splitting.
        
*   Analyze how each tokenizer handles:
    
    *   Abbreviations (e.g., "Dr.", "U.S.A.").
        
    *   Unconventional punctuation.
        
    *   Complex or multi-clause sentences.
        
*   Measure tokenization accuracy and efficiency across different types of text.
    

### **Dataset**

The project uses a sample text dataset stored in the 'Data/' directory. This dataset includes various sentence types to test tokenizer robustness.

### **Usage**

Open the provided Jupyter Notebook (Sentence\_Tokenization\_Comparison.ipynb) to:

*   Explore the dataset.
    
*   Run different tokenizers.
    
*   Compare their output and performance.
    

The notebook is organized into sections for data loading, tokenization, and comparison analysis.

### **Results**

The analysis highlights:

*   The strengths and weaknesses of each tokenizer.
    
*   Situations where rule-based tokenizers outperform machine learning ones.
    
*   Cases where pre-trained tokenizers are more reliable.
