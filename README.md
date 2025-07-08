# Spell Checker in Python

A simple Python spell checker that uses a text corpus (big.txt) to build a vocabulary and word probability model. It suggests corrections for misspelled words using edits (insert, delete, swap, replace) up to two levels.

## Features
- Builds vocabulary from corpus
- Computes word probabilities
- Suggests top corrections using edit distance
- Supports 1-edit and 2-edit prediction

## Requirements
- Python 3
- pandas
- tqdm

## Usage
1. Place `big.txt` in the project folder.
2. Install requirements: `pip install pandas tqdm`
3. Run the script or import functions.
4. Example:
   - `spell_check_edit_1('famili')` ➜ `['family']`
   - `spell_check_edit_2('fameli')` ➜ `['family', 'namely', 'fame', 'amelie', 'camel']`
   
