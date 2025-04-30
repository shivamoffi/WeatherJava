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
Download and install Eclipse IDE (or IntelliJ IDEA).
Download and install Apache Tomcat 10.1.1.
Open Eclipse IDE and configure it with Apache Tomcat:
Go to Window -> Preferences.
Navigate to Server -> Runtime Environments.
Click Add and select Apache Tomcat v10.1.1.
Provide the Tomcat installation directory and finish the setup.
Clone the repository to your local machine using git clone <repository_url>.
Import the project into Eclipse IDE:
Go to File -> Import.
Select Existing Projects into Workspace.
Choose the cloned project directory and import it into Eclipse.
Ensure that the Gson library is included in the src/webapp/WEB-INF/lib directory of your project. If not, add it manually to the build path.
Obtain an API key from OpenWeatherMap and replace the placeholder myApiKey in MyServlet.java with your actual API key.
Run the application on your local Apache Tomcat server:
Right-click on the project in Eclipse.
Go to Run As -> Run on Server.
Select your configured Tomcat server and click Finish.
Access the WeatherApp through your web browser using the provided URL (usually http://localhost:8080/WeatherApp).
