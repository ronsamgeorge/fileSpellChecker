# SpellChecker

SpellChecker is a bash script that helps you quickly find and fix misspelled words in your text files. It takes in a directory as input and recursively checks all `.txt` and `.md` files for misspelled words using the `aspell` spell-checking tool.

## Features

- Fast and efficient spell-checking of multiple file types (`.txt` and `.md`).
- User-friendly interface with easy-to-read output.

## Getting Started

To use SpellChecker, simply download the `spellchecker.sh` script and run it with the path to the directory you wish to check. For example:

` ./spellchecker /path/to/directory`

SpellChecker will then scan all `.txt` and `.md` files in the specified directory (and any subdirectories) for misspelled words.

## Future Features

- Save the output to a specified output file
- provide other language support(present in the aspell library)

## Contributing

If you find any bugs or have suggestions for new features, feel free to create an issue or submit a pull request. Contributions are always welcome!

## License

SpellChecker is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
