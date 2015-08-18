# qfin
Books for Quant Finance Interviews

## Brain Teasers

### Basic
[A Practical Guide To Quantitative Finance Interviews](http://www.amazon.com/Practical-Guide-Quantitative-Finance-Interviews/dp/1438236662)

All Martin Gardner's books, 
  [book1](http://www.amazon.com/Mathematical-Logic-Puzzles-Dover-Recreational/dp/0486281523) * |
  [book2](http://www.amazon.com/Entertaining-Mathematical-Puzzles-Martin-Gardner/dp/0486252116) *
  
### Advanced

[Mathematical Olympaid Challenges](http://www.amazon.com/Mathematical-Olympiad-Challenges-Titu-Andreescu/dp/0817645284) *

[The USSR Olympiad Problem Book](http://www.amazon.com/The-USSR-Olympiad-Problem-Book/dp/0486277097) *

## Algorithms / Whiteboard Programming

[Algorithm for interviews](http://www.amazon.com/Algorithms-Interviews-Adnan-Aziz/dp/1453792996) *

[Leetcode](https://leetcode.com/)

Cracking the Coding Interviews by [Careercup.com](http://www.careercup.com/) *

## Quant Equity / Portfolio Theory

[Quantitative Equity Portfolio Management: Modern Techniques and Applications](http://www.amazon.com/Quantitative-Equity-Portfolio-Management-Applications/dp/1584885580) *

[Active Equity Management](http://www.amazon.com/Active-Equity-Management-Xinfeng-Zhou/dp/0692297774) *

[Financial Modeling of the Equity Market: From CAPM to Cointegration](http://www.amazon.com/Financial-Modeling-Equity-Market-Cointegration/dp/0471699004) *

## Statistics

Linear regression is the most heavily tested topic in statistics. Unfortunately, there is not single book that summarises all need-to-know knowledge. Greene's [Econometric Analysis](http://www.amazon.com/Econometric-Analysis-7th-William-Greene/dp/0131395386) * might be an overshoot due to its length. Honestly, if you are able to manually calculate all outputs from R regression functions (see my comment about R), you should be fine.

[Analysis of Financial Time Series](http://www.amazon.com/Analysis-Financial-Time-Series-Ruey/dp/0470414359) * I personally like other books more, but this book exposes one to the most number of time series models.

[Time Series Analysis](http://press.princeton.edu/titles/5386.html) A much better book, also more expensive.

## C/C++

If you rarely program in C/C++, start with [C++ Design Patterns and Derivatives Pricing](http://www.amazon.com/Patterns-Derivatives-Pricing-Mathematics-Finance/dp/0521721628). This is by no means a complete introduction, but it gives you a taste of C++. 

Try use a **build system**, do not use an IDE.  I prefer the naive `makefile` and [CMake](http://www.cmake.org/).

You **must** finish Scott Meyers'

- [Effective C++](http://www.amazon.com/Effective-Specific-Improve-Programs-Designs/dp/0321334876) *

- [Effective STL](http://www.amazon.com/Effective-STL-Specific-Standard-Template/dp/0201749629)

before your first C++ interview.  There's another book, [More Effective C++](http://www.amazon.com/More-Effective-Improve-Programs-Designs/dp/020163371X), but I haven't read it yet.

## R

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

Be sure to understand the usage and output of these functions: `lm`, `glm`, `anova`, `summary.lm`, `plot.lm`.

## Python

