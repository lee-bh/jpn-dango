# Japanese Vocabulary Practice

This is a simple web-based tool for practicing Japanese vocabulary. It displays a table of words and offers an interactive quiz to help you learn.

## Features

- **Vocabulary List**: View a comprehensive table of Japanese words, including their Hiragana, Kanji, and Korean translations.
- **Toggle Hiragana**: Easily show or hide the Hiragana column to challenge your Kanji reading skills.
- **Interactive Quiz**: Test your knowledge with a multiple-choice quiz.
  - A Korean word is presented as the question.
  - Four options are displayed in a `Kanji (Hiragana)` format.
  - The answers are arranged in a two-column layout for easy viewing.
  - Receive instant feedback on your selection.

## How to Use

1.  Open the `index.html` file in any modern web browser.
2.  The vocabulary data is loaded from `data.json`. You can customize your study list by editing this file.

## Data Format

The `data.json` file follows a simple structure:

```json
{
  "data": [
    {
      "hira": "にほんご",
      "kanji": "日本語",
      "kor": "일본어"
    },
    {
      "hira": "たんご",
      "kanji": "単語",
      "kor": "단어"
    }
  ]
}
```