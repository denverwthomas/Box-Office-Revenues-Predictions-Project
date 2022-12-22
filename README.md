# Box-Office-Revenue-Prediction-Project
This project used data scraped from the TMDB website to predict if a movie would be a big box office.  
  
We classified all the movies into three classes:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Lucrative movies;   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Break-even movies;   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Money-losing movies.  
  
Detailed description of this project is in the file "Final Report.pdf".

## File Descriptions
* **Data_Scraping.ipynb**: Scraped movie features from the TMDB website. A sample of the features is shown below.
![avatar](/images/data.png)

* **Data_Analysis.ipynb**: Visualizations of scraped movie data.

* **Collection_Moview_Analysis.ipynb**: Visualization of collection movie data.

* **The_Impact_Of_Economy_Factors.ipynb**: Data processing of external economic data.

* **Prediction_Models.ipynb**: Predictive models

## Business Insights
* If an investor does not have much money to invest (less than 4M USD), and decided NOT to invest in horror movies, we are quite confident that this investor will lose money.
* If you have a moderate amount of money (60M USD-100M USD), we recommend that you do not release the movie in January. 
* if you have more than 100M to invest, in this case, which production company you work with matters. We recommend collaborating with one of the more prestigious companies.

## Prediction Results
This model was made in the December of 2019. At that time, we predicted a soon to be released movie Mulan (by Disney) would be lucrative, according to this model;.  
![avatar](/images/mulan.jpg)

## Limitations
Mulan turns out to be a failure for Disney. But this is caused by the pandemic.  This also proves that our model can not respond well to big emergencies, such as Covid-19. This is where we can make improvements.
