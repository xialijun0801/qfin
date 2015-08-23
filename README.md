# qfin
Books for Quant Finance Interviews. (*comments on the usefulness* are based on the score of 0-5).

## Brain Teasers

*comments on the usefullness*: 5 for fresh graduate, `max(2, 5 - #years of experience)` for experienced hires.

### Basic
[A Practical Guide To Quantitative Finance Interviews](http://www.amazon.com/Practical-Guide-Quantitative-Finance-Interviews/dp/1438236662)

All Martin Gardner's books, 
  [book1](http://www.amazon.com/Mathematical-Logic-Puzzles-Dover-Recreational/dp/0486281523) * |
  [book2](http://www.amazon.com/Entertaining-Mathematical-Puzzles-Martin-Gardner/dp/0486252116) *
  
### Advanced

[Mathematical Olympaid Challenges](http://www.amazon.com/Mathematical-Olympiad-Challenges-Titu-Andreescu/dp/0817645284) *

[The USSR Olympiad Problem Book](http://www.amazon.com/The-USSR-Olympiad-Problem-Book/dp/0486277097) *

## Algorithms / Whiteboard Programming

*comments on the usefullness*: 5 for high frequency or algo trader/researcher, pricing quants (model validation  roles), start arb strategists.

[Algorithm for interviews](http://www.amazon.com/Algorithms-Interviews-Adnan-Aziz/dp/1453792996) *

[Leetcode](https://leetcode.com/)

Cracking the Coding Interviews by [Careercup.com](http://www.careercup.com/) *

## Quant Equity / Portfolio Theory

*comments on the usefullness*: 5 for quant equity strategists, 4 for quant macro strategists.

[Quantitative Equity Portfolio Management: Modern Techniques and Applications](http://www.amazon.com/Quantitative-Equity-Portfolio-Management-Applications/dp/1584885580) *

[Active Equity Management](http://www.amazon.com/Active-Equity-Management-Xinfeng-Zhou/dp/0692297774) *

[Financial Modeling of the Equity Market: From CAPM to Cointegration](http://www.amazon.com/Financial-Modeling-Equity-Market-Cointegration/dp/0471699004) *

## Statistics

*comments on the usefullness*: 5 for all roles.

Linear regression is the most heavily tested topic in statistics. Unfortunately, there are not many good books on this topic (either too elementary or too advanced). Greene's [Econometric Analysis](http://www.amazon.com/Econometric-Analysis-7th-William-Greene/dp/0131395386) * might be an overshoot due to its length. Honestly, if you are able to manually calculate all outputs from R regression functions, you should be fine. (see my comments on R)

[Analysis of Financial Time Series](http://www.amazon.com/Analysis-Financial-Time-Series-Ruey/dp/0470414359) * I personally like other books more, but this book exposes one to the most number of time series models.

[Time Series Analysis](http://press.princeton.edu/titles/5386.html) A much better book, also more expensive.

## C/C++

*comments on the usefullness*: 5 for high frequency or algo trader/researcher, pricing quants (model validation  roles), start arb strategists.

If you rarely program in C/C++, start with [C++ Design Patterns and Derivatives Pricing](http://www.amazon.com/Patterns-Derivatives-Pricing-Mathematics-Finance/dp/0521721628). This is by no means a complete introduction, but it gives you an overview of the language. 

Try using a **build system**, do not use an IDE.  I prefer the naive [makefile](http://www.amazon.com/Managing-Projects-Make-Nutshell-Handbooks/dp/0596006101) and the advanced [CMake](http://www.cmake.org/). (My personal view is Autotools is unpretty and out-dated.) IDEs are nice to work with, but helpless for interview prep.

Try writing C++ using only objects. Templates are nice to have as well. Use [Design Patterns](https://sourcemaking.com/) whenever you can.  

Here is a short but interesting article on [Expression Template](https://github.com/dmlc/mshadow/tree/master/guide/exp-template) that examplifies some basic usage of C++ templates.

You **must** finish Scott Meyers'

- [Effective C++](http://www.amazon.com/Effective-Specific-Improve-Programs-Designs/dp/0321334876) *
- [Effective STL](http://www.amazon.com/Effective-STL-Specific-Standard-Template/dp/0201749629)

before your first C++ interview.  There are other books, [More Effective C++](http://www.amazon.com/More-Effective-Improve-Programs-Designs/dp/020163371X) and [Effecive Mordern C++](http://www.amazon.com/Effective-Modern-Specific-Ways-Improve/dp/1491903996), but I haven't read them yet.

## R

*comments on the usefullness*: not heavily tested during interviews, but very helpful.

There's no real good book for R. Hadley's [Advanced R](http://adv-r.had.co.nz/) is an excellent book, but it is only for advanced users.

I would suggest starting from [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.html) and familarize yourself with the following packages:

- data.table
- dplyr
- foreach
- ggplot2
- reshape2

and these packages as well:

- stringr
- lubridate
- Matrix
- gridExtra

Once you are fluent with R, take a look at these advanced packages:

- Rcpp
- devtools 
- testthat 
- roxygen2

Make sure you understand the usage and output of these functions: `lm`, `glm`, `anova`, `summary.lm`, `plot.lm`, `acf`, `pacf`.

## Python
-Python for data analysis by Wes McKinney
*comments on the usefullness*: 5 for all roles
