## Analysis of the Impact of War and Terrorism on "Islamophobia and Media Portrayals of Muslim Women" ([Final Paper PDF](https://github.com/seanhugh/Data-Islamophobia/blob/master/final_writeup.pdf))

I analyze the findings in the paper [Islamophobia and Media Portrayals of Muslim Women: A Computational Text Analysis of US News Coverage](http://rochelleterman.com/wp-content/uploads/2014/08/Manuscript.pdf) by University of Chicago Postdoctoral Fellow [Rochelle Terman](https://cisac.fsi.stanford.edu/people/rochelle-terman) using [data from the Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/W8AAYK&version=1.0).

Terman's paper finds that western media (specifically the New York Times and Washington Post) depicts Muslim countries as a *cultural* threat through an analysis of their coverage of Muslim women. By controlling for war and terrorism, I reduce the magnitude of these results by 33%.

-----

File Organization

**final_writeup.pdf** - PDF copy of the final report

**final_writeup.Rmd** - Rmd code used to generate final report

**data_manipulation.Rmd** - Rmd code used to create all figures, tables

**writeup_files** - folder where all figure and table data for final writeup are stored

**dataverse_files** - folder where all Terman replication data is stored

----

Select Results
![Key Result](https://raw.githubusercontent.com/seanhugh/Data-Islamaphobia/master/writeup_files/keyexerpt.png)

NAW ("Not at war") countries refers to a subset of countries that are not currently involved in active war with the United States. By removing countries at war with the United States from the experimental data set, I found the magnitude of the effects of Terman's results decreased by around 33%.
