# jpn-dango

jpn-dango is a simple web application designed to help users practice Japanese vocabulary. It displays a list of Japanese words with their Hiragana, Kanji, and Korean translations.

## How to Use

1. Clone this repository or download the files.
2. Open the `index.html` file in your web browser.
3. You will see a table of Japanese vocabulary.
4. Use the "히라가나 표시" (Show Hiragana) checkbox at the top to toggle the visibility of the Hiragana column. This can be helpful for testing your memory of Hiragana readings.

## Contributing

The vocabulary data is stored in the `data.json` file. If you want to add more words, you can edit this file. The file contains a single JSON object with a key "data", which is an array of vocabulary items. Each item is an object with the following keys:

*   `"cate"`: An integer representing the category of the word (e.g., 1 for i-adjectives, 2 for na-adjectives).
*   `"hira"`: The Hiragana reading of the word (string).
*   `"kanji"`: The Kanji representation of the word (string). If no Kanji exists, this can be the same as Hiragana or Katakana.
*   `"kor"`: The Korean translation of the word (string).

**Example:**

```json
{
  "data": [
    {
      "cate": 1,
      "hira": "おおきい",
      "kanji": "大きい",
      "kor": "크다"
    },
    {
      "cate": 2,
      "hira": "しずか",
      "kanji": "静か",
      "kor": "조용한"
    }
  ]
}
```

To add a new word, simply add a new object with these keys to the "data" array. Make sure your JSON is valid before saving.
