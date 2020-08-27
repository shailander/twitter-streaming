Twitter Streaming Web Application
===============
​
Introduction
----
This is the python project with spark and flask compatibility. The project fetch trending tweets for a given location 
from Twitter API and start fetching it with spark streaming and then send it to the front-end with flask compatibility 
and shows the real time graph of top 10 trending tweets with its count. 
​
​
### Project Doc
​
Project documentation link : [Documentation file](https://docs.google.com/document/d/1kv1IETPaYimrdfN2FLFbAS1Uc86zhEIh-NERsjWVPMU/edit)
​
​
Setup for Running the Project
---
```   
1. Open the project TwitterStreaming
2. Go to the TwitterHttpClient folder
3. Run python file 'twitter_app.py'
    -> python twitter_app.py
4. Run pythonn file 'spark_app.py'
    -> python spark_app.py
5. Move to the HashTagsDashboard folder
6. Run python file 'app.py'
    -> python app.py
7. Open the below url in your browser to see the real-time graph
    -> http://localhost:5005
​
```
​
​
Key Entities in Code
----
```   
+-- Project
|   +--static
|       +--images
|       +--styles
|       +--Chart.js
|   +--templates
|       +--chart.html
|       +--index.html
|       +--search.html
|   +--index.py
|   +--README.md
|   +--spark_app.py
|   +--tweet.py
|   +--twitter_app.py
```
​
​
Dependencies
----
1. **flask**: It  is a micro web framework written in Python. It is classified as a microframework because it does not 
require particular tools or libraries.
​
2. **pyspark**: It is the Python API to support Apache Spark. Apache Spark is a distributed framework that can handle 
Big Data analysis. Spark is basically a computational engine, that works with huge sets of data by processing them in 
parallel and batch systems.
 
3. **requests_oauthlib**: It is used to directly fetch new access tokens without going through the normal OAuth workflow