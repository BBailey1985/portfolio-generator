# portfolio-generator

THis is a Node.JS application to create a portfolio based off a user and their GitHub projects.

## How it Works
When the app is ran, a series of questions are asked.
-What is your name? (Required field)
-Enter your Github Username? (Required field)
-Would you like to enter some information about yourself for an "About" section?
  -If this is selected, an additonal question comes up, "Provide some information on yourself"
-What is the name of your project?
-Provide a description of the project (Required field)
-What did you build this project with? (Check all that apply)
  -Choices are Javascript, HTML, CSS, ES6, jQuery, Bootstrap, Node
-Enter the Github link to your project. (Required field)
-Would you like to feature this project?
-Would you like to enter another project?

Once these repsonses have been made, the data is inserted into an HTML template.
Then the file is written and copied into the dist folder.
Then the css is copied ffrom the src folder to the dist folder.

## Error catching
At each step, this app contains error catching and will not let you proceed if required fields are not filled out

I hope you enjoy using this app to make great portfolios!
