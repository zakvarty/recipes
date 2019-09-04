
# About this book

## Summary
This is a collection of my most used recies and a first attempt at making a book using R Markdown and **bookdown** (https://github.com/rstudio/bookdown). 

The recipe book is still a work in progress and needs cleaning, expanding and ordering by type.

## How is it made?
This book is written in **Markdown** using the `bookdown` package in `R`. 
Each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>.

The **bookdown** package can be installed from CRAN or Github:

```{r eval=FALSE}
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```
## Key markdown syntax
The content of this book is predominantly written in plain text. Additional formatting may be added to make text __bold__, _italic_ or `verbatim`.

| formatting     | syntax                      |
|----------------|-----------------------------|
| __bold__       | `__bold__` or `**bold**`    |
| _italic_       | `_italic_` or `*italic*`    |
| `verbatim`     | ``verbatim``                |

## Adding a recipe 
Recipes are added to the desired chapter.Rmd and should be written according to the following template. Recipies may be added by submission of a pull request.
````
## Recipe title
_recipe source_ 

__Prep:__ mins    __Cook:__ mins     __Serves:__  

__Ingredients:__
 *
 *
 *
__Method:__ 
1.
2.
3.
````
