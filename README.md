This repository holds the base files for the Intechnica Hack Manchester Challenge.

The challenge relies on the imdb data - this data can be downloaded here

ftp://ftp.sunet.se/pub/tv+movies/imdb/

The repository includes a HTML file that includes a simple javascript function. The JavaScript expects you to have entered a valid url in the text box provided and then it connects to that url and appends ?q=[the contents to the other text box]. It then parses the JSON returned and displays the results.

The expected Json format is shown in the visible HTML.

