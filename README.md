## Project for resume generation from markdown to html & PDF
Based on the engine [there4/markdown-resume](https://github.com/there4/markdown-resume) and the template swissen2 (enhanced version that I developped for my needs)
Github Actions pipeline does the rendering then it publishes to my Github Pages.

Run locally
```bash
# Using original docker img
docker run -v ${PWD}/assets/swissen2:/app/templates/swissen2 -v ${PWD}:/resume there4/markdown-resume:2.3.1 md2resume pdf --ansi --template swissen2 cv.md .
docker run -v ${PWD}/assets/swissen2:/app/templates/swissen2 -v ${PWD}:/resume there4/markdown-resume:2.3.1 md2resume html --ansi --template swissen2 cv.md .

# Using mine with fixed local access to resources from within image (wkhtmltopdf) ans theme already included
docker run -v ${PWD}:/resume xto34/markdown-resume:latest md2resume pdf --ansi --template swissen2 cv.md .
docker run -v ${PWD}:/resume xto34/markdown-resume:latest md2resume html --ansi --template swissen2 cv.md .
```
