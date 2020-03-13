## Yian's Portfolio

---

### Data Storytelling

#### [Space-Time Prediction of Scooter Activity in Louisville, KY](https://xinyimsumyee.github.io/html/scooters.html)

We use the data set from Louisville open data and focus on scooter trips from March to August. OLS regression models are built here to predict the pickup and return activity respectively.
<br>
We project the trips count on census tract and fishnet. **Census tract** level prediction provide a general understanding of the demand across the city. **Fishnet** level provides more details to assist staff target the excess demand or supply areas and re-balance efficiently. 
<br>
To determine whether there is an excess supply or demand, we **subtract the predicted demand and supply**.
<br><br>
<img src="/images/scooter.JPG?raw=true"/>
<br><br>
Then we design an app use case for re-balancing staff based on the prediciton result. For more about our app **Sco-Porter**, here is a [video](https://www.youtube.com/watch?v=xheEpq_Ij4E)!
<br><br>
<img src="/images/app.JPG?raw=true"/>

---
#### [Sale Price Prediction in San Francisco](/code_files/House Price Prediction.html)

In this project, we build an OLS model to predict 700 home sale prices in San Francisco from 2012-2015 based on 9433 known data entries. It successfuly takes spatial autocorrelation into accounts. 
<br>
The final outcome is pretty impressive with a **MAE of 230000** and an **MAPE of 23%**. In general, it is a pretty good model that describes both local demographics and physical characteristics of the housing.
<br><br>
<img src="/images/houseprice.JPG?raw=true"/>

---

### Data Visualization

#### [Data Analysis on Electric Vehicle Usage & Environmental Impacts](http://example.com/)
<br>
This project detect environmental changes by green land and air quality in U.S. states where has the most rapid and advanced growth in electric vehicle usage.
<br>
<img src="/images/larp743.JPG?raw=true"/>

#### [Visualize crime incidents in Philadelphia](http://example.com/)
In this project, web scraping by BeautifulSoup are used to get data, and Datashader and Imageio make the animated map to visualize crime incidents in Philadelphia for each hour.
<br>
<img src="/images/crimes_name.gif?raw=true"/>

---

### Data Manipulation

#### [Big Data Analytics - Assignment 1](/code_files/HW_spark_sql_bfs.ipynb)
This assignment focuses on hierarchical data stored in dataframes, graph data and traversing relationships among data.

#### [Big Data Analytics - Assignment 2](http://example.com/)
This assignment uses an EMR cluster to use Spark to manipulate the linkedin dataset as well as the stocks data.

---

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
