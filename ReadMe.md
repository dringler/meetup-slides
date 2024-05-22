PyData Berlin Local Meetup Slides
----------------------------------

Hi there! Thanks for your interest in our [PyData Berlin Meetup Group](https://www.meetup.com/PyData-Berlin/]). Here you can find slides from our latest events.

Interested in giving or hosting a talk? Reach out [<info@pydata.berlin>](mailto:info@pydata.berlin).


## Setup environment with pyenv and poetry
`pyenv local use 3.12.2`

`poetry env use 3.12.2`

`poetry install`

## Creating the slides

`poetry run jupyter nbconvert --to slides MEETUP_FOLDER/intro.ipynb`

This command creates a file named `intro.slides.html` that you can open in your browser.

### Creating a PDF for the slides

Open the intro.slides.html file in your browser, add `?print-pdf` to the url, e.g. `".../intro.slides.html?print-pdf"`.

Now, print and save the slides as PDF.
