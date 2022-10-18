# i18n for Cosmic Cat

## i18n Guide.
This guide will cover how to translate Cosmic Cat!

## Set up
1. Open a shell of your choice.
2. Change the current working directory to the location where you want the cloned directory.
3. Type `git clone`, followed by the repo's URL. [Git can be installed from here.](https://git-scm.com/downloads)</br>
`$ git clone https://github.com/ciulinuwu/Ciulinations`
4. Press **Enter** to create your local clone.
5. Change the current working directory to the cloned folder > i18n</br>
`$ cd Ciulinations/i18n`
6. Make a duplicate of `en.json` and rename it to the ISO 639-1 Language Code of your language. [ISO 639-1 Language Codes can be looked up here](https://www.loc.gov/standards/iso639-2/php/code_list.php)</br>
`$ cp en.json <ISO 639-1 code here>.json`

## Editing
1. Open `<ISO 639-1 code here>.json` in an IDE of your choice.
2. Navigate to `Line 2` and add your ISO 639-1 Code to the `language` field.
3. Navigate to `Line 3` and add your GitHub username to the `author` field.
4. From this point, you can translate the strings in each field inside `json`.</br>
**Do not translate the field name otherwise will render the contents of that field useless.**

## Submitting
(NEEDS RESEARCH)

## Rules
* Do **NOT** use machine translation.
* Must be fluent in English and the targeted language.
