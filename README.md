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
  2. <b>Navigation Card containing link to Social Media section</b> - Analysis and plots related to sentiments of customer review posts on social medias.
  3. <b>Navigation Card containing link to Top Products section</b> - Top 90 trendy electronics products on social media along with their details.
  4. <b>Navigation Card containing link to Big Billion Days section</b> - Analysis and plots related to products sold and customer feedbacks of the same during Big Billion Days

## Future Prospects

- Add a Login-Logout system in the application 
- Add a Meeting Section to update about the upcoming or incomplete meetings in the workplace

## UI Of The Web Application

### 1. Home Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181441355-4324ecab-e617-4439-a0f9-8a7ff01324f4.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441418-023a5926-a8e4-4534-9770-fd55ee3ce5c2.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441511-e645e907-d71e-4602-9c17-27cba1420fdf.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441970-832c9ace-9dbb-4308-bed6-d062247f4147.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442072-e3e87b33-f36d-413c-9649-27a4387e2744.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442147-caf6dfdd-f696-4ab3-a298-8d32313476a6.png" width="1000"> 
</pre>

### 2. Social Media Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181442605-3aa75389-bc37-47e3-9a61-fafc3a883033.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442623-377b9dc9-adc3-4091-a21a-9770278d3745.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181444492-36fa33ac-2ae3-43ad-a724-5b5776374212.png" width="1000">
</pre>

### 3. Top Products
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181443175-447222b4-88a2-460e-8dc5-6de1a4446e34.png" width="1000"> 
</pre>

### 4. Big Billion Days Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181445122-c06045a3-0a09-409e-ae3e-a998f62c3bbe.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181443713-9e929ad6-690f-4216-8ccc-e226f028c335.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181444896-495bea4b-5808-4a1a-8542-cf86ea449420.png" width="1000">
</pre>

## Run Locally

1.1 `git clone <repo link>`

1.2 `cd ManageIt`

1.3 `flask run`
