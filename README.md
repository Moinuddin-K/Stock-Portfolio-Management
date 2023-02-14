# final-project-jams

final-project-jams created by GitHub Classroom



## Team members:    

1. Moinuddin Raziuddin Khaja (NUID - 0027620250, Email - khaja.m@northeastern.edu)          
2. Anay Rajesh Pampatwar (NUID - 002766273, Email - pampatwar.a@northeastern.edu)
3. Jay Milan Doshi (NUID - 002762973, Email - doshi.jaym@northeastern.edu)
4. Swapnil Shankarrao Biradar (NUID - 002775707, Email - biradar.sw@northeastern.edu)


## Overview:

A Stocks Portfolio management web application which enables the user to view stock listings, IPO listings, add stocks to watchlist, buy/sell stocks, display the portfolio, stock transaction history and showcase the stock news.


## Architecture & Technologies

* <b>JavaScript</b>, the project's front and backend programing language.
* <b>React</b>, a JavaScript library used to assist with efficient management of rapidly changing data and maintaining a single-page web application structure.
* <b>Node.js</b>, a runtime environment used to execute JavaScript for server-side scripting.
* <b>Express.js</b>, a web application framework, used with Node.js, to provide server-side structure for querying and retrieval of API data.
* <b>Mongoose</b>, a javascript library that creates a connection between MongoDB and Node.js.
* <b>MongoDB</b>, a document-oriented (NoSQL) database system used for storage and management of information.
* <b>Material-UI/MUI</b>, a comprehensive styling library that features implementation of Google's Material Design system.
* <b>Sass, CSS3 and HTML5</b>, used to manage the presentation and styling of the project.
* <b>finnhub.io</b>, a third party finance API that provides real time stock market price, stock news and IPO listings.
* <b>TradingView</b>, a REST API that provides real time stock market charts.



## Functionality:

* Landing Page: 
Landing Page will show the features that we offer. 
When you click on any feature, it will prompt to Register/Login first.   

* Register Page:
Register Page will have a form to be filled by user to Create a new account.
All form fields has validations.

* Login:
Login Page for the existing users to login.
Once the users successfully Logs in/Registers he will be taken to the Home page.

* Home Page:
Home page will have stock listings with real time stock value fetched using finnhub.io API. Stocks can be added to watchlist. User can navigate to other section using sidebar and navbar.

* Watchlist: 
Contains user added stocks with real time values such as stock price, volume, day high, day low, etc. User can perform actions such as buy, sell, more stock information and remove stock from watchlist.

* Buy/Sell Stocks:
User can buy/sell stocks. Validations such as balance check and quantity check has been implemented.

* Portfolio: 
Showcases user with current investment, quantity and profit/loss for each stock holdings and total profit/loss.

* Stock Information:
Contains realtime stock chart and technical analysis of that stock. Used TradingView API to fetch data.


## Instructions to run the project:
* Open the project in visual studio code
* Open Mongodb Compass and connect to "mongodb+srv://JAMS:NEUWebDesignJAMS@stock.7r94bfe.mongodb.net/?* retryWrites=true&w=majority".
* Run "npm start" in the backend folder to start the backend API service.
* Run "npm start" in the frontend folder.
* You will be redirected to landing page of the project.

