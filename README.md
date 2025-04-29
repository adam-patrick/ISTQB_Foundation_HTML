# Project Name

ISTQB Question Bank and Practice Tests

## Features

- Asks all questions available, one-by-one, either in order or at random.
- Can perform practice tests of the uploaded, freely available sample tests from various sources.

## Installation

Place all files (index.html, set1.json, set2.json, set3.json) in the same folder.

Run a simple local server:

```
python -m http.server
```

Open http://localhost:8000/ in your browser.

Your quiz will now dynamically load question sets from their own JSON files.

## Adding Images

- Simple Image: After Options line, add:

```
"image": "images/sample-image.png",
```

- To Add next to an option:
```
"<b>a. <img src='images/sample-image.png alt='sampleImage' style='max-width:100px;'</b>",
```