# G.Lab. Book

Rendered Book URL: https://giovannellilab.github.io/

## How to contribute
- Suggested way: using `Pull Requests`
- Suggested tool: `RStudio` as it can show a preview of the rendered book.
However, any code editor can work.

```
git clone git@github.com:giovannellilab/giovannellilab.github.io.git
```

Open R in the terminal and install `bookdown` package:
```
install.packages("bookdown")
```

For a complete reference go to: [bookdown repository](https://github.com/rstudio/bookdowne)

### RStudio Setup 
Open Rstudio and create a new project
`RStudio > File > New Project > Existing Directory > giovannellilab.github.io` then click `Create Project`.

In the panel `Build`, open the dropdown menu and choose: `bookdown::gitbook`.

#### Render Book
From now on, you can modify each markdown file and render all the changes by clicking on `Build Book` in the Build panel. After this, `Rstudio will open a preview of the book`.

This will update the `docs` folder, then commit changes and push when you have finished.

### Alternative Code Editor
After modifying the markdown, you can render all the changes by executing the following command in R:
```
bookdown::render_book()
```
To see the changes, you have to manually open the `docs/index.html` with your browser.

## Push changes
1. Commit the changes and push them to GitHub.

1. The GitHub page will load the new version in a few minutes
