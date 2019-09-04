# Scraping Data Using the Genius Tidy Data Lyrics Extractor

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
Genius Tidy Data Lyrics Extractor tutorial by <a href="dlac.grinnell.edu" rel="cc:attributionURL">Katherine Walden, Digital Liberal Arts Specialist (Grinnell College)</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

### What is the Genius Tidy Data Lyrics Extractor?

From the [app website](https://dasil-jarren.shinyapps.io/genius-app/), “The Genius Lyrics Tidy Data Extractor web application extracts lyrics from [Genius](https://genius.com/) and allows for users to download this data in a [tidy format](https://vita.had.co.nz/papers/tidy-data.pdf). It was created by [Jarren Santos](https://github.com/jarrenls) (Data Scientist @ DASIL, Grinnell College), using the `shiny` R package that interacts with the Genius API using the `genius` R package by [Josiah Parry](https://github.com/JosiahParry/genius).

The Genius Tidy Data Lyrics Extract is a web-based application built using R and RStudio, hosted by Shiny. According to the [project website](https://www.r-project.org/), “R is a free software environment for statistical computing and graphics.” [RStudio](https://www.rstudio.com/) gives users a “popular open source and enterprise-ready professional software for the R statistical computing environment.” According to the [Shiny website](https://shiny.rstudio.com/ ), “Shiny is an R package that makes it easy to build interactive web apps straight from R.”

### What is Tidy Data?

As described by statistician Hadley Wickham in [an article he wrote](http://vita.had.co.nz/papers/tidy-data.html) for *The Journal of Statistical Software* in 2014 (volume 59):

<blockquote>“A huge amount of effort is spent cleaning data to get it ready for analysis, but there has been little research on how to make data cleaning as easy and effective as possible. This paper tackles a small, but important, component of data cleaning: data tidying. Tidy datasets are easy to manipulate, model and visualize, and have a specific structure: each variable is a column, each observation is a row, and each type of observational unit is a table. This framework makes it easy to tidy messy datasets because only a small set of tools are needed to deal with a wide range of un-tidy datasets. This structure also makes it easier to develop tidy tools for data analysis, tools that both input and output tidy datasets. The advantages of a consistent data structure and matching tools are demonstrated with a case study free from mundane data manipulation chores.”</blockquote>

See also:
- Hadley Wickham (2014) Tidy Data, *The Journal of Statistical Software 59* (2014). http://vita.had.co.nz/papers/tidy-data.html. 
- Karl W. Broman & Kara H. Woo (2018) Data Organization in Spreadsheets, *The American Statistician* 72:1, 2-10, DOI: [10.1080/00031305.2017.1375989](https://doi.org/10.1080/00031305.2017.1375989)  

## Getting Started with the Genius Lyrics App

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_1.png?raw=true" alt="Capture" /></p>

Navigate to https://dasil-jarren.shinyapps.io/genius-app/ in a web browser.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_2.png?raw=true" alt="Capture" /></p>

In a separate browser window, navigate to https://genius.com/. 

The App uses song URLs from Genius to extract and download the lyrics for that specific song.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_3.png?raw=true" alt="Capture" /></p>

Search for a specific Reggeaton artist.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_4.png?raw=true" alt="Capture" /></p>

Select an album from that artist.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_5.png?raw=true" alt="Capture" /></p>

Select a specific song from that album.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_6.png?raw=true" alt="Capture" /></p>

Copy the Genius URL.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_7.png?raw=true" alt="Capture" /></p>

Paste the Genius URL into the App.

Click the Submit button.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_8.png?raw=true" alt="Capture" /></p>

The lyrics will appear on the App web page in a structured tabular data format.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_9.png?raw=true" alt="Capture" /></p>

Click the Download button to save the song lyrics as a CSV file.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_10.png?raw=true" alt="Capture" /></p>

Open the CSV file in Microsoft Excel or another spreadsheet program to see the structured data.

You’ll notice Microsoft Excel does not correctly display the Spanish-language special characters or accent markings.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/GeniusApp-Tutorial/blob/master/screenshots/Capture_11.png?raw=true" alt="Capture" /></p>

Open the CSV file in a text editor (NotePad on PC or TextEdit on Mac) to see the text characters without Excel’s additional formatting errors.
