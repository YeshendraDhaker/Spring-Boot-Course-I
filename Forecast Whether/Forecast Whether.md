**INSTRUCTIONS:**



Problem Statement:



Suppose you are a software developer working at a startup WeatherWatchers. You are assigned to create a console weather forecast application using Spring Boot and the concept of Inversion of Control.



The application will take user details and their location and give a random weather output.



Tasks:



1\. Go to start.spring.io and create a new project.



&nbsp;2. Add the necessary dependencies for the project.



&nbsp;3. Create a User interface with the following methods:-



&nbsp;• setUserDetails()



&nbsp;• setLocationDetails()



&nbsp;• getWeatherForecastForLocation() (This method will return a String printing the result as shown in the sample output.)



&nbsp;4. Create a Location interface with the following methods:-



&nbsp;• setLocation()



&nbsp;• getLocation()



&nbsp;5. Create a WeatherForecast interface with the following method:-



&nbsp;• getWeather() (This method will return a String which will be random whether like “sunny”, “cloudy”, “windy”, “Snowy”, or “rainy”.)



&nbsp;6. Create myUser class which implements the User interface. Override the interface methods, create custom init and destroy methods and add the following attributes:-



&nbsp;• String name



&nbsp;• Integer age



&nbsp;• Location location (added as a dependency)



&nbsp;• WeatherForecast weatherForecast ( added as a dependency)



&nbsp;7. Create myLocation class, which implements the Location interface. Override the interface methods, create a custom init method, and add the following attributes:-



&nbsp;• String City



&nbsp;• String state



&nbsp;• String country



&nbsp;8. Create myForecast class, which implements the WeatherForecast interface. Override the interface methods. You should implement the method in such a way that they give a random weather forecast.



&nbsp;9. Use setter injection to inject the dependencies.



&nbsp;10. In the ApplicationContext.xml file:-



&nbsp;• Create bean of myLocation with scope prototype



&nbsp;• Create beans of myUser and myForecast with singleton scope.



&nbsp;11. Run and test your application.

