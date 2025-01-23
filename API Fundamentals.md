# *What's an API?*

>API stands for Application Programming Interface.

>API is a bunch of code that takes an input and gives you predictable outputs.

>In simple terms, you can think of an API as a middleman that enables applications to interact without needing direct access to each other's code or database.
>
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*Some API Examples*
-------------------

1. Uber Ride API

   > If you provide a pickup and destination address, the API finds the nearest available driver and calculates the estimated fare.

2. Sorting API
   > If you provide a list of numbers ([5, 3, 8, 1]), the API returns the sorted list ([1, 3, 5, 8]).

3. Weather API
   > If you provide a city name as input ("New York"), the API returns the current temperature, humidity, and weather conditions.

---------------------------------------------------------------------------------------------------------------------------------------------

*Building APIs*
---------------

When engineers build APIs, they clearly define what inputs the API accepts and what outputs it produces, ensuring consistent behavior across different applications.

 APIs follow a simple request-response model:

  1. A client (such as a web app or mobile app) makes a request to an API.

  2. The API (hosted on an API server) processes the request, interacts with the necessary databases or services, and prepares a response.

  3. The API sends the response back to the client in a structured format (usually JSON or XML).



API Input
---------
+ Every API requires specific types of inputs, and passing incorrect data can result in errors.
+ For example: If you tried putting your name into the Google Maps API as an input, that wouldn’t work very well.
+ APIs often validate inputs to ensure they are correct before processing them, which helps maintain accuracy and security.

API Output
----------
+ Just as APIs require specific inputs, they also return well-structured outputs.
+ For example, the Google Maps API always returns coordinates in the same format.
    >{
    > "latitude": 40.6892,
  "longitude": -74.0445 }
+ If the API can’t find the location, it provides an error response explaining why.
   >{
  "error": "Invalid address format",
  "code": 400
}

---------------------------------------------------------------------------------------------------------------------------------------------

*How APIs Power Modern Applications*
------------------------------------

+ The apps you use every day—whether it's Gmail, Instagram, Uber, or Spotify—are essentially a collection of APIs with a polished user interface (UI) on top.

Most applications follow the frontend/backend architecture, where:
+ The backend consists of APIs that handle data processing, business logic, and communication with databases.
+ The frontend is a graphical user interface (GUI) that interacts with these APIs, making applications user-friendly and accessible without requiring users to write code.

 Real-world example: Uber 
+ App : Uber
+ APIs: FindNearByDrivers , Calculating Fares & Routes API, RequestRide, ProcessPayment

  Points to Remember:
  > Q: These APIs run on Uber’s servers, forming the backend infrastructure. Then Why even need frontend?
    + Every time you request a ride, track your driver, or make a payment, these backend APIs handle the request.
    + The backend APIs handle all the complex logic, but they only work through code—which isn't practical for everyday users. That’s why companies build a frontend (user interface) on top of these APIs, allowing users to interact with the system visually and intuitively.
    + When you enter your pickup & destination address, the frontend sends an API request to find nearby drivers and displays available cars.
    + Once the trip is complete, the frontend may call the process payment API to display the receipt.

 ---------------------------------------------------------------------------------------------------------------------------------------------

*Types of APIs*
---------------

Type of API depends on
+ who can access them
+ how they are used
+ what purpose they serve.


1. Public APIs (Open APIs)

   > are accessible to external developers with minimal restrictions.


2. Private APIs (Internal)
   
   > are designed exclusively for internal use within an organization. 

3. Code Interfaces



   



---------------------------------------------------------------------------------------------------------------------------------------------

      

  

