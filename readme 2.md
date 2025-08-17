# Tokenization Model Learning Project

This project explores different tokenization techniques and models, inspired by **Hugging Face courses**. It provides hands-on implementations of the key components that make up modern tokenizers.

## What You'll Learn

![Tokenizer Overview](public/tokenizer.png)

- **Normalization**: Text preprocessing and cleaning techniques
- **Pre-tokenization**: Breaking text into initial tokens
- **Tokenization Models**: Three main approaches:
  - **BPE** (Byte Pair Encoding)
  - **WordPiece** 
  - **Unigram**

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation

1. **Clone/Download** this repository
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter or use an environnement **:
   ```bash
   jupyter notebook 
   ```
   or
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

## Learning Path

Follow this **sequential order** for the best learning experience:

### Step 1: Normalization
```
1_normalization/normalize.ipynb
```
Learn how to clean and standardize text data before tokenization.

### Step 2: Pre-tokenization  
```
2_pre_tokenization/pre_tokenize.ipynb
```
Understand how to split text into preliminary tokens.

### Step 3: Tokenization Models
```
3_model/read_first.ipynb  ← Start here for overview
3_model/1_bpe.ipynb       ← Byte Pair Encoding
3_model/2_word_piece.ipynb ← WordPiece algorithm  
3_model/3_unigrams.ipynb   ← Unigram model
```

## Usage

1. **Start** with `1_normalization/normalize.ipynb`
2. **Progress** through each folder sequentially
3. **Read** the overview in `3_model/read_first.ipynb` before diving into specific models
4. **Experiment** with the code and try different parameters

## Key Concepts

- **Normalization**: Unicode handling, case folding, accent removal
- **Pre-tokenization**: Whitespace splitting, punctuation handling
- **BPE**: Iteratively merges frequent character pairs
- **WordPiece**: Google's subword tokenization approach
- **Unigram**: Probabilistic subword segmentation

## Dependencies

- `torch` - PyTorch framework
- `transformers` - Hugging Face transformers library
- `datasets` - Dataset utilities
- `pandas` - Data manipulation
- `numpy` - Numerical computing
- `ipywidgets` - Interactive widgets
- `dotenv` - Environment variables

---

*This project is inspired by the excellent [Hugging FaceCourse](https://huggingface.co) tokenization chapters.*
