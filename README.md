# Multilingual-Audio-Video-Summarizer
## Overview

This project demonstrates a comprehensive text processing pipeline, including translation, summarization, and evaluation using various Python libraries and tools. The project leverages deep learning models to translate, summarize, and evaluate text from different sources.

## Features

- **Translation**: Translates input text from Spanish to English.
- **Summarization**: Summarizes the translated text to provide a concise version.
- **Evaluation**: Evaluates the summarization using metrics such as ROUGE.

## Requirements

- Python 3.11.7
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Vinil-0603/Multilingual-Audio-Video-Summarizer
    cd <repository_directory>
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Solution.ipynb
    ```

2. Follow the steps in the notebook to process your text files:
    - Provide input text in Spanish.
    - The notebook will translate the text to English.
    - Summarize the translated text.
    - Evaluate the summarization with ROUGE scores.

## Example

### Input Text
```plaintext
Un pájaro volando alto en el cielo, pensaba en su pájaro. Ella esperaba que él estuviera disfrutando de los cielos de esa manera.
```

### Translated Text
```plaintext
A bird flying high in the sky, thinking about his bird. She hoped he was enjoying the skies that way.
```

### Summary
```plaintext
A bird flying high, thinking about another bird, hoping he was enjoying the skies.
```

### Evaluation
```plaintext
ROUGE Scores:
- rouge1: 0.66
- rouge2: 0.66
- rougeL: 0.66
```

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss improvements or new features.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
