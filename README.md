# Roxiler-System-assessment-1

<h2>GET Create API to initialize the database. fetch the JSON from the third party API and initialize the database with seed data. You are free to define your own efficient table / collection structure 
</h2> <br> 


<p>Instruction All the APIs below should take month ( expected value is any month between January to December) as an input and should be matched against the field dateOfSale regardless of the year.
</p>
<h2>GET Create an API to list the all transactions </h2> <br><br>
<p>
API should support search and pagination on product transactions</p>
Based on the value of search parameters, it should match search text on product title/description/price and based on matching result it should return the product transactions
If search parameter is empty then based on applied pagination it should return all the records of that page number
Default pagination values will be like page = 1, per page = 10
GET Create an API for statistics
<br> <br> br>
<p>
Total sale amount of selected month
Total number of sold items of selected month
Total number of not sold items of selected month
GET Create an API for bar chart ( the response should contain price range and the number of items in that range for the selected month regardless of the year )</p>

0 - 100 <br>

101 - 200 <br>
201-300 <br>
301-400 <br>
401-500 <br>
501 - 600 <br> 
601-700<br> 
701-800<br> 
801-900<br> 
901-above<br> 
<h3>GET Create an API for pie chart Find unique categories and number of items from that category for the selected month regardless of the year. For example : </h3>

X category : 20 (items)
Y category : 5 (items)
Z category : 3 (items)

<h3>GET Create an API which fetches the data from all the 3 APIs mentioned above, combines the response and sends a final response of the combined JSON </h3>

<h1>Frontend Task </h1>

By using above created apis, create the following table and charts on single page. Follow the given mockups and you can implement your own design to change the look and feel Transctions Table
<br>
<li>
<ul> Here use your transactions listing api to list transactions in the table </ul>
 <ul>Select month dropdown should display Jan to Dec months as an options </ul> 
 <ul> By default March month should be selected </ul> 
 <ul> Table should list the transactions of the selected month irrespective of the year using API </ul> 
 <ul> Search transaction box should take an input and if search text is matching with anyone of these title/description/price then those transactions of the selected month should come in the list using API </ul>
If user clear’s the search box then initial list of transactions should be displayed for the selected month using API
On click of Next it should load the next page data from API
On click of Previous it should load the previous page data from API
Transctions Statistics (Use your created API to fetch the data)  </li>

Here display total amount of sale, total sold items, and total not sold item in the box for the selected month from the drop down (present above table) using API
Transactions Bar Char (Use your created API to fetch the data)

Chart should display the price range and the number of items in that range for the selected month irrespective of the year using API
Month selected from dropdown (above the table) should be applied here
