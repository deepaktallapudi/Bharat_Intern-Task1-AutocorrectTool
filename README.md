# Bharat_Intern-Task1-AutocorrectTool


### Spell Correction Using NLTK

This repository contains a Python script that demonstrates automatic spell correction using the Natural Language Toolkit (NLTK). The script utilizes edit distance and Jaccard similarity to suggest possible corrections for misspelled words in a given sentence.

### Prerequisites

Before running the script, make sure you have the NLTK library installed. You can install it using the following command:

```bash
pip install nltk
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

2. Run the script:

```bash
python spell_corrector.py
```

### How It Works

The `spell_corrector.py` script provides two main functions:

1. `find_nearest_word(word, word_list)`: This function takes a word and a list of words, calculates the edit distance and Jaccard similarity between the input word and each word in the list, and returns the nearest word based on a combined score.

2. `auto_correct_sentence(sentence)`: This function tokenizes a given sentence into words, checks if each word is in the NLTK English word list, and if not, suggests a corrected word using the `find_nearest_word` function.

### Example

```python
from spell_corrector import auto_correct_sentence

input_sentence = "speling errurs in somethink Whutever possibel  Misteaks hapen "
corrected_sentence = auto_correct_sentence(input_sentence)

print(f"Original Sentence: {input_sentence}")
print(f"Corrected Sentence: {corrected_sentence}")
```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore and modify the script to suit your needs. If you encounter any issues or have suggestions for improvements, please feel free to create an issue or pull request.

OUTPUT VIDEO:


https://github.com/deepaktallapudi/Bharat_Intern-Task1-AutocorrectTool/assets/103422044/4c4d300f-9223-423d-b5f0-1f1ebea0994f





**Note**: This README assumes that you have a `spell_corrector.py` file containing the provided code in your repository. Make sure to adjust the filenames and paths according to your project structure.


