# littleboxes
RStudio Addin - creates boxed in titles in an Rscript

## Installation

```R
# install.packages("devtools")
devtools::install_github("ThinkRstat/littleboxes")
```
## Usage

![alt tag](https://raw.githubusercontent.com/ThinkRstat/littleboxes/master/demo.gif)



```R
# write a sentence, place your cursor on the line and go to Addins > Nice Title

# Part One

1+1
plot(iris)

# Part Two
lm(1~1)

will be turned into:

############################################################
#                                                          #
#                         Part One                         #
#                                                          #
############################################################

1+1
plot(iris)

############################################################
#                                                          #
#                         Part Two                         #
#                                                          #
############################################################

lm(1~1)

```
