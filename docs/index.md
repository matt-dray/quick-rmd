Automate, reproduce, win!
========================================================
author: Matt Dray
date: 14 May 2018
autosize: true




The problem is the process
========================================================

It's looooong and error-prone.

1. Receive non-machine-readable data in Excel format
2. Use a pre-prepared Excel template to reformat the data
3. Generate figures, tables and plots
4. Copy and paste to ~100-page Word document
5. Find error/need to alter something
6. Spend ages re-copying and re-pasting all instances
7. Get confused about the current working version
7. Repeat steps 5 to 7 until 4am
8. Eventually document is as ready as it can be

Minimise the risk
========================================================

We can reduce human error and go faster.

1. Receive machine-readable data in Excel format
2. Run a pre-prepared *R Markdown* file
3. Make minor tweaks if needed and re-render stress-free
4. Use the saved time to prepare more informative commentary and have a cup of tea

What's R Markdown?
========================================================

- Write plain text
- Format it with symbols (`*`, `[]`, `^`, etc)
- Embed R code
- Click a button to render into HTML, Word or PDF



Formatting
========================================================

You type | You get
--- | ---
`*italic*` | *italic*
`**bold**` | **bold**
`super^script` | super^script
`* bullet` | <ul><li>bullet</li></ul>
`[Link]()` | [Link](www.gov.uk)
`![](img/cat.png)` | ![](img/cat.png)

More examples are availabe in [this cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf).

Code in R Markdown (1/2)
========================================================

You can write some R code in the middle of a sentence!

For example: write <code>&grave;r 1 + 1&grave;</code> in a sentence and it will render as '2'.

Or even: the best Pokemon is 

(Don't worry about the actual code; just know that this is possible.)


Code in R Markdown (2/2)
========================================================



Basic process
========================================================

1. Open a file with the .Rmd (<u>R</u> <u>M</u>ark<u>d</u>own) extension
2. Write your report using R Markdown
3. Embed code that calculates values or produces plots and tables, for example
4. Use the `knitr` package to *knit* the document, rendering your R Markdown into a 'proper' document for sharing

1. File > New File > R Markdown

1. You write a plain text file and format it with symbols
2. You intersperse it with your R code
3. You render the file and it spits out your fully-formed document
