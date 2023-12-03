# markdown2html

A Javascript function to convert markdown to HTML. Support only an essential subset of tags: `h1`, `h2`, `h3`, `h4`, `strong`, `em`, `ul`, `ol`, `a`, `img`, and `hr`. The function's inside is modular, so you can add your own tags by defining a regex and corresponding tag replacing module in `paragraphedArray` loop.

For this code to work properly, each markdown part should be separated by a blank line. Also, preceding tags such as `#` or `-` should be followed by one space before the text.

To use, copy the code to your JS file, and call `markdown2html("markdown-text")` to get HTML.

This software is provided as is. I wrote it for my own use. Please customize for your use case.

Copyright 2023 by Chitpong Kittinaradorn under MIT License.