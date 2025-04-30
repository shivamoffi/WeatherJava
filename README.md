WeatherJava
# Description
WeatherApp is a simple Java web application developed using Servlets, JSP, HTML, CSS, and JavaScript. It integrates with the OpenWeatherMap API to fetch weather data for a given city and display it to the user.

# Features
Fetch weather data based on the user's input city name. Display current weather conditions including temperature, humidity, wind speed, visibility, and cloud cover, etc.

# Technologies Used
Java Servlets
JavaServer Pages (JSP)
HTML
CSS
JavaScript
OpenWeatherMap API
#  Setup Instructions
1.Download and install Eclipse IDE (or IntelliJ IDEA).
2.Download and install Apache Tomcat 10.1.1.
3.Open Eclipse IDE and configure it with Apache Tomcat:
Go to Window -> Preferences.
Navigate to Server -> Runtime Environments.
Click Add and select Apache Tomcat v10.1.1.
Provide the Tomcat installation directory and finish the setup.
4.Clone the repository to your local machine using git clone <repository_url>.
5.Import the project into Eclipse IDE:
Go to File -> Import.
Select Existing Projects into Workspace.
Choose the cloned project directory and import it into Eclipse.
6.Ensure that the Gson library is included in the src/webapp/WEB-INF/lib directory of your project. If not, add it manually to the build path.
7.Obtain an API key from OpenWeatherMap and replace the placeholder myApiKey in MyServlet.java with your actual API key.
8.Run the application on your local Apache Tomcat server:
9.Right-click on the project in Eclipse.
Go to Run As -> Run on Server.
Select your configured Tomcat server and click Finish.
10.Access the WeatherApp through your web browser using the provided URL (usually http://localhost:8080/WeatherApp).
