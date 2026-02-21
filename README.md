# Vowel Consonant Stacker

A simple web tool that displays text with consonants and vowels vertically aligned, inspired by [abjad writing systems](https://en.wikipedia.org/wiki/Abjad) such as Hebrew and Arabic

## Description

This tool takes any text input and creates a two-row display where:

- Consonants appear in the top row
- Their corresponding vowels appear directly beneath them
- Numbers appear in the top row only
- Words maintain their integrity and won't break across lines

## Example

Input: "hello world"

```
h ll w rld
e o  o
```

## Usage

1. Open the HTML file in any modern web browser
2. Enter your text in the input field
3. Click "Run" to see the stacked display

## Technical Details

- Built with vanilla JavaScript
- Uses monospace fonts and ```<pre>``` tags for precise character alignment
- Handles English alphabet characters and numbers
- Responsive design with configurable line width

## Inspiration

The display format is inspired by the Hebrew writing system, where vowel marks (niqqud) appear below or above the consonant letters.
