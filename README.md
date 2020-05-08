# CS 122B Project 4 Autocomplete Example

This example shows how autocomplete search can be implemented.

### To run this example:
1. Clone this repository.
2. Open IntelliJ -> Import Project -> Choose the project you just cloned (The root path must contain the pom.xml!) -> Choose Import project from external model -> choose Maven -> Click on Finish -> The IntelliJ will load automatically
3. For "Root Directory", right click "cs122b-spring20-project4-autocomplete-example" -> Mark Directory as -> sources root
4. In Tomcat Deployment Configuration, make sure the application context is: /cs122b-spring20-project4-autocomplete-example
5. To run the example, follow the instructions here: https://canvas.eee.uci.edu/courses/26486/pages/intellij-idea-tomcat-configuration


### Brief Explanation
`index.html` is the main page. It only contains an input box. It also includes the javascript library files.

`index.js` is the main Javascript file to use this jQuery autocomplete library to implement autocomplete search: https://github.com/devbridge/jQuery-Autocomplete

`HeroSuggestion.java` is a Java servlet searches superhero names and return suggestions in JSON format.
