<h1 align="center">
             🟡FlipAnalyse🔵
</h1>

![image](https://user-images.githubusercontent.com/78029145/181165548-0bdca110-6bfd-48b4-bfed-66cf2c3b8361.png)


## Overview of the App

<table>
<tr>
<td>
This application can be used by Flipkart to get a detailed overall sentiment analysis of customer reviews for Flipkart products scrapped from multiple social media platforms like - Twitter, LinkedIn, Reddit. It also contains a section which displays the top 90 Electronics Products extracted from various social media platforms along with the details of the products taken from Flipkart. Additionally the application also gives meaningful insights from the analysis shown of the products sold and customer feedbacks during Flipkart Big Billion Days.
</td>
</tr>
</table>

There are 3 main sections in the app as follows -

1. <b>Social Media</b> - This section contains a total of 6 plots to display the analysis of sentiment counts and percentages via Histograms and Pie Charts for tweets, posts, contents extacted from social media platforms like Twitter, Reddit, LinkedIn using web scrapping tools like ParseHub, Apify. The data scrapped from different social media platforms are passed through a Recurrent Neural Network Sentiment Anlaysis Model with 99.2% accuracy to predict the results.

2. <b>Top Products</b> - This section contains top 90 trendy electronics products on social media platforms like Facebook, Instagram using web scrapping tools like ParseHub, Apify and the details of the respective products taken from official site of Flipkart. The data scrapped from multiple social media platforms is used to match with products on flipkart and then details of those products are extracted.

3. <b>Big Billion Days Sale</b> - This section contains a total of 6 plots to showcase the insights of sale of products and products categories sold along with customer feedbacks and reviews for the same. The dataset is collected for Big Billion Days 2021 and analysis is drawn.


## Tech Stack Used -

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/>

## Libraries Used -

<img src="https://img.shields.io/badge/numpy%20-%2314354C.svg?&style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas%20-%2314354C.svg?&style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/plotly%20-%2314354C.svg?&style=for-the-badge&logo=plotly&logoColor=white"/> <img src="https://img.shields.io/badge/pickle%20-%2314354C.svg?&style=for-the-badge&logo=pickle&logoColor=white"/> <img src="https://img.shields.io/badge/nltk%20-%2314354C.svg?&style=for-the-badge&logo=nltk&logoColor=white"/> <img src="https://img.shields.io/badge/tensorflow%20-%2314354C.svg?&style=for-the-badge&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/flask%20-%2314354C.svg?&style=for-the-badge&logo=flask&logoColor=white"/> 

## Structure Of The Project

The home page of the application contains -
  1. <b>Landing Page</b> - Here users can get started with using our application
  2. <b>Link to Employee Section</b> - Add, Update, Delete employee details for any workplace
  3. <b>Link to Notes Section</b> - Add, Update, Delete notes for any workplace

## Future Prospects

- Add a Login-Logout system in the application 
- Add a Meeting Section to update about the upcoming or incomplete meetings in the workplace
  
## UI Of The Web Application

### 1. Home Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/179470475-9ee9759e-5e48-41a6-a9dd-26a7e16f3a8c.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179470566-f2b6059f-356e-42db-8a3b-ad3c236d57bf.png" width="1000"> 
</pre>

### 2. Employee Details Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/179470942-b350838a-519f-49b6-bc91-53d3de1ce7d6.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179471056-b111aadf-a6c3-43f0-863f-fedf1be9fbf1.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179471245-40e4660d-a3c8-4689-b4d4-97b3a530f133.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179471314-61853de8-5cf6-4a65-9f55-c4418269d3fa.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179471553-6b8937a3-5b23-4a2b-a14c-c21396bc2f8e.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179473003-c956ea22-3687-4f5d-842c-0db2c922b42c.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179472319-ce0ee974-80f0-49e9-84b6-961b62926720.png" width="1000">
</pre>

### 3. Notes Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/179474203-ce6339ae-6b63-4424-a973-2761a3b869fa.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179474259-bad9799b-dcc7-42d7-8b75-7c5731c47d7d.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179474361-475fe685-c693-4eb1-8a1c-284be84f37b8.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/179474409-6ae9f999-1f75-4775-83ba-a0fdb26a5708.png" width="1000">
</pre>


## Run Locally

1.1 `git clone <repo link>`

1.2 `cd ManageIt`

1.3 `flask run`
