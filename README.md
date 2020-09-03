# Nutrition-Optimization

Welcome to this Food and nutrition planning optimization tool!

The goal is to create a tool to provide individuals with a recommended diet based on their personal health needs.

The model currently used is the the DOcplex linear optimization solver, and it has been built on IBM Watson Studio.

## Instructions
- This project is run in IBM Watson Studio - using decision optimization

## More Stuff
- Food Files Data are currently being gathered from [New Zealand Food composition Data](https://www.foodcomposition.co.nz/foodfiles/) Composing of 2767 food items.
- The daily dietary requirements are currently being gathered from [Nutrient Reference Values for Australia and New Zealand](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwim75TXsLfrAhVDAXIKHaWXD-YQFjADegQIBRAB&url=https%3A%2F%2Fwww.nhmrc.gov.au%2Fabout-us%2Fpublications%2Fnutrient-reference-values-australia-and-new-zealand-including-recommended-dietary-intakes&usg=AOvVaw0sMiZ9bbiYAf7LWJyWpCk4)


## Things to add
- (Currently being worked on) Add more food data, using an API connection the USDA FoodData Central https://fdc.nal.usda.gov/api-key-signup.html
- A better error message if the solution is not feasible i.e. the food options will not meet the desired nutritional requirements. 
- Add a web scraper for the costs of each food item or a REST api connection.
- Add an option to input your gender / age and activity level to ensure the nutritional requirements are set to the individual.