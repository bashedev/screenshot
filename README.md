## A quick script to render all the lines in a file urls.txt into corresponding pngs using Phantom.js
# (Largely taken from example render\_multi\_url.js)

## Usage:
- Put the urls to be rendered in urls.txt in same dir as screenshot.js, one per line, e.g. http://www.example.com/
- Run phantomjs screenshot.js
- Profit!

## Notes:
- Each url will be rendered as a png with the filename equal to the hostname
- Default rendering screensize is 800x600 (change in sourecode)

