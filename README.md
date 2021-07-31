# angular-spring-integration
This project is to demo the angular and spring integration.

Steps to follow for re-creating a similar project:
  Create a spring boot using any IDE.
  Use terminal/command prompt and navigate to src/main
  Run command ng new static - this will create a new angular application with the name static. 
  Create a folder webapp, if it is not already present in src/main. 
  Modify the attribute outputPath in angular.json to ../webapp - this will ensure that ng build commnand will produce the output js files into the webapp. 
  Run the application as a spring boot application. If the angular changes are to be reflected please run the ng build command, which will in turn update the webapp with the js file complied recently.
