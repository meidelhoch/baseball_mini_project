
# Mini Project 2: Web scraping

## Due date

This mini project is due on GitHub by Sunday, May 14, at midnight.

# Project Description

In this project, you will collaborate with a partner to create a short
blog post that narrates an engaging story based on data scraped from one
or more webpages listed below. Your task is to define your own research
question(s) based on your interests, and utilize data wrangling, web
scraping, and data visualization skills acquired in this course.

The most successful projects will:

-   Explore an interesting topic
-   Offer a well-planned, informative analysis
-   Present insights or analytics using visualizations, including at
    least one created with `plotly`
-   Be well-written
-   Comprise 500-700 words

Your objective is to use web-scraping techniques from this course to
tell a captivating story about any aspect of your chosen topic,
utilizing multiple data tables obtained through web scraping from either
the same or different webpages. Craft your analysis as a blog post using
R Markdown, and incorporate web scraping, data visualization, and data
wrangling tools you’ve learned in this course. **Please remember to
create your own CSV file by scraping data from the web and tidying it,
rather than using an existing CSV file available online or downloading
one via web scraping.**

For web scraping, use the `polite` and `rvest` packages, and employ
suitable CSS selector helpers from the `SelectorGadget` tool. Include at
least one well-designed, thoughtfully-prepared data graphic that
supports your story with relevant information, with one of them
utilizing `plotly` for an interactive visualization. Upload both your R
Markdown (.Rmd) file and the knitted PDF/html to GitHub. Make sure to
give your post an engaging title!

In your knitted PDF, hide your code, but remember that your .Rmd file
will be reviewed for grading, so keep it organized and use comments
effectively.

**Note**: While working on your project, consider webpages with multiple
pages and HTML elements, as this will provide opportunities for more
complex web scraping and data extraction tasks.

## Data

You could use any of the following webpages for data scraping:

-   [Sports Reference](https://www.sports-reference.com/)
-   [MLB Batting
    Leaders](https://www.espn.com/mlb/history/leaders/_/breakdown/season/year/2022/)
-   [MLB Team Payrolls](http://www.stevetheump.com/Payrolls.htm)
-   [NBA Reference](https://www.basketball-reference.com/)
-   [NFL Player Stats](https://www.nfl.com/stats/player-stats/)
-   [Premier League
    Stats](https://fbref.com/en/comps/9/stats/Premier-League-Stats)
-   [USA Facts](https://usafacts.org/)
-   [Yahoo Finance](https://finance.yahoo.com/)
-   [Market
    Watch](https://www.marketwatch.com/tools/stockresearch/globalmarkets/intindices.asp)
-   [Wikipedia: Your favorite
    series](https://en.wikipedia.org/wiki/List_of_CSI:_Crime_Scene_Investigation_episodes)
-   [FRED Economic Data: Federal Reserve Bank of
    St. Louis](https://fred.stlouisfed.org/)
-   [International Monetary Fund: World Economic Outlook
    Database](https://www.imf.org/en/Publications/SPROLLs/world-economic-outlook-databases)
-   [FiveThirtyEight](https://data.fivethirtyeight.com/)
-   [Global economy](https://www.theglobaleconomy.com/)
-   [World Bank Open Data](https://data.worldbank.org/)
-   [Eurostat Statistics](https://ec.europa.eu/eurostat/web/main)
-   [The Global Economy](https://www.theglobaleconomy.com/)
-   [Statista](https://www.statista.com/)
-   [U.S. Census Bureau](https://www.census.gov/data.html)

This is not an exhaustive list of webpages that you could use to scrape
your data from. Please consult with me to get an approval, if you are
using any other webpages that are not on this list.

## Grading Rubric

**Technical aspects**

| Topic                                                                 | Excellent: 10                                                                                                                                                                                                                              | Good: 7.5                                                                                                                               | Satisfactory: 5                                                                                                                                                                    | Needs work: 2.5                                                                                                                          |
|-----------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| Coding style                                                          | Group has gone beyond what was expected and required, coding style is followed, code is well commented                                                                                                                                     | Group mostly follows coding style, code is readable and has some comments, but with some inconsistencies                                | Coding style lacks refinement and has some errors, but code is readable and has some comments                                                                                      | Many errors in coding style, little attention paid to making the code human readable                                                     |
| Coding strategy                                                       | Complicated problem broken down into sub-problems that are individually much simpler. Code is efficient, correct, and minimal. Code uses appropriate data structure (list, data frame, vector/matrix/array). Code checks for common errors | Code is mostly efficient, correct, and minimal, with occasional deviations. Uses appropriate data structures and checks for some errors | Code is correct, but could be edited down to leaner code. Some “hacking” instead of using suitable data structure. Some checks for errors.                                         | Code tackles complicated problem in one big chunk. Code is repetitive and could easily be functionalized. No anticipation of errors.     |
| Presentation: graphs                                                  | Graph(s) carefully tuned for desired purpose. Careful styling highlights important features, and attention is paid to labels, colors, and scales.                                                                                          | Graph(s) well chosen and styled, but with a few minor problems: inappropriate aspect ratios, poor labels, or sub optimal color choices. | Graph(s) well chosen, but with some issues: inappropriate aspect ratios, poor labels, or lack of attention to detail in styling.                                                   | Graph(s) poorly chosen to support questions, with little attention paid to styling, labels, or appropriate visualization type.           |
| Achievement, mastery, cleverness, creativity                          | Student has gone beyond what was expected and required, e.g., extraordinary effort, additional tools not addressed by this course, unusually sophisticated application of tools from course.                                               | Student displays a high level of mastery and creativity, but without extraordinary effort or additional tools                           | Tools and techniques from the course are applied very competently and, perhaps, somewhat creatively. Chosen task was acceptable, but fairly conservative in ambition.              | Student does not display the expected level of mastery of the tools and techniques in this course. Chosen task was too limited in scope. |
| Ease of access, compliance with course conventions for submitted work | Access as easy as possible, code runs, .Rmd knits without error or extra messages, everything is on time                                                                                                                                   | Code runs and .Rmd knits with minor issues, mostly complies with course conventions and is on time                                      | Code runs, but .Rmd may have some issues knitting or generate extra messages; some deviations from course conventions, but overall acceptable; submitted work may be slightly late | Not an earnest effort to reduce friction and comply with conventions and/or code does not run                                            |

**Data wrangling and web scraping**

| Topic                                                               | Excellent: 10                                                                                                                                                                              | Good: 7.5                                                                                                                                                             | Satisfactory: 5                                                                                                                        | Needs work: 2.5                                                                                                                                                                                                                                       |
|---------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| *Web Scraping:* <br> Achievement, mastery, cleverness, creativity   | Group has gone beyond what was expected and required, e.g., extraordinary effort, additional tools not addressed by this course, unusually sophisticated application of tools from course. | Tools and techniques from the course are applied very competently and, perhaps, somewhat creatively. Chosen task was acceptable, but fairly conservative in ambition. | Group does not display the expected level of mastery of the tools and techniques in this course. Chosen task was too limited in scope. | Group struggles significantly with web scraping techniques, displaying a lack of understanding or mastery of the tools and techniques covered in the course. Chosen task is overly simplistic or does not demonstrate the expected level of effort.   |
| *Data Wrangling:* <br> Achievement, mastery, cleverness, creativity | Group has gone beyond what was expected and required, e.g., extraordinary effort, additional tools not addressed by this course, unusually sophisticated application of tools from course. | Tools and techniques from the course are applied very competently and, perhaps, somewhat creatively. Chosen task was acceptable, but fairly conservative in ambition. | Group does not display the expected level of mastery of the tools and techniques in this course. Chosen task was too limited in scope. | Group struggles significantly with data wrangling techniques, displaying a lack of understanding or mastery of the tools and techniques covered in the course. Chosen task is overly simplistic or does not demonstrate the expected level of effort. |

**Communication**

| Topic             | Excellent: 10                                                                                                                                      | Good: 7.5                                                                                                                                  | Satisfactory: 5                                                                                                                   | Needs work: 2.5                                                                                           |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Data introduction | Clearly and concisely describes the data set, and why it is of interest. Establishes an engaging story (i.e., set of questions) that will be told. | Introduction and story are clear, but could be more engaging; provides context and motivation but lacks some detail.                       | Introduction and story outlined, but could be clearer or more engaging; context and motivation are present but may not be strong. | Context and motivation is lacking; story unclear or not well-defined.                                     |
| Results           | Results are clearly explained in an engaging way. The questions posed are clearly answered. Potential limitations are outlined and discussed.      | Results are clear and engaging, but some minor improvements could be made; most questions are answered and some limitations are addressed. | Results are explained, and the questions posed are answered; limitations may be mentioned but not discussed in detail.            | Results are not completely explained and/or questions are left unanswered; limitations are not addressed. |
| Code review       | Extensive evidence that group members are giving constructive feedback on each other’s code, leading to better code.                               | Evidence that group members are giving feedback on each other’s code, with some room for improvement.                                      | Some evidence that group members are giving constructive feedback on each other’s code, leading to better code.                   | Little evidence that group members are giving constructive feedback on each other’s code.                 |

## Ackowledgements

This prompt was adapted from a prompt written by Adam Loy and Katie
St. Clair.
