# Reshape and Sort Word Lists (sed / echo / sort / cat)

A small Unix shell utility that reshapes a horizontal, comma-separated word list into a vertical one-word-per-line column and sorts it alphabetically. It is a compact demonstration of chaining core text-processing tools (sed, echo, sort, cat) applied to a list of Unix command names.

## What the script does

1. Replace the comma-and-space after each word with a newline, turning a single-row list into a column (sed)
2. Stage a vertical word list in the console (echo -e with embedded newlines)
3. Sort the words alphabetically (sort)
4. Display the result (cat)

Input: my_utilites0.txt. Intermediate: my_utilites1.txt, my_utilites2.txt. Output: my_utilites3.txt.

## Files

- sed_echo_sort_cat_Reshape_word_lists.sh: the reshaping / sorting script
- my_utilites0.txt ... my_utilites3.txt: input, intermediate and sorted output word lists

## Requirements

- A POSIX shell (sh/bash) with sed, sort, echo and cat (standard on Unix-like systems)

## Usage

    bash sed_echo_sort_cat_Reshape_word_lists.sh

Edit my_utilites0.txt (or the inline echo list) to reshape and sort your own word list.

## Author

Polina Lemenkova
ORCID: https://orcid.org/0000-0002-5759-1089

## License

See the LICENSE file in this repository.
