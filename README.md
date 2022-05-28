# Assignment 0: Markdown
---
## You hove to write markdown
---
### Some Math Equation
<center>

First equation: $ Y=X \beta+\epsilon_y, \forall x $<br>
Second equation: $ X=Z\gamma + \epsilon_x $

$f_1(w)=\frac{\sigma^{2}}{2\pi},\omega\in[-\pi,\pi]$
</center>

1. First item a. first sub-item A) first sub-sub-item b. second sub-item
2. Second item
3. Third item a. second sub item
4. Fourth Item


* First Item
* Second Item
   * first sub-item
      * first sub-sub-item
    * second sub-item

![picture alt](pic/cat.png "Cat Pic")

library(tidyverse)<br>
library(mdsr)<br>
SAT_2010 %>% gglot(aes(write,...density...)) + geom_histogram() + geom_density() + theme_minimal + labs(title = "SAT Writing Scores")

# Table with alignment 
---
You can align text in the columns to the left, right, or center by adding a colon(:) to the left, right, or on both side of the hypens within the header row.

| Syntax        | Description   |Test Text |
|:-------------:|:-------------:|:--------:|
| Header        | Title         |Here' this|
| Paragraph     | Text          |And more  |
