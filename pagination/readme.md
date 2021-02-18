# Pagination

## Intro

In a recent project, a user needed to review a series of collected documents.  Instead of presenting them all pasted together in one giant document (some were a collection of more than 500 documets), 
I wanted to give the user the ability to load each file one at a time.

## Process

### Basic
* Open `update_html_file.ipynb`
* Collect html text
* Read in a html shell `index_with_vars.html`
* Insert collected reports into the shell
* Write to `index_output.html` file

### Add Stats
* Use the html shell `index_vars_bokeh.html`
* #TODO Python workflow to input custom bokeh charts

## Resources

This code was adapted from [{THATSOFTWAREDUDE}](https://www.thatsoftwaredude.com/content/6125/how-to-paginate-through-a-collection-in-javascript)

