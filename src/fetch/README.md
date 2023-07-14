#CustomApi Exercise

This goal of this exercise is to take JSON data from an external source, and to visualize it into a simple UI.

You'll be using the 'customApi', which is a silly service that returns random people's favorite fruits as an array. It has one method: .get(callback) which accepts a function that is called with one parameter (JSON response) when the data is ready. Do not modify CustomApi.js.

Use Angular / Vuejs / React to complete this exercise
*note : Make Sure remove node_modules before sent. 

A UX mockup is provided. 
*Follow same like Design.
  
  
##Design spec:

- Load data by calling CustomApi.get().
- Create a horizontal bar chart using css (no more than 400px wide) and populate date using CustomApi.get() and aggragating result that shows how popular each fruit is compared to the others. This should be based on the total number of favorites for each fruit. Each row should have a label for the name of the fruit, plus its total count. There's no need to show an axis with units on it.
- Underneath the css bar chart, display a list of all the items in the array you got from CustomApi.get(). Each item should display the person's name and favorite fruit.
- Each css bar chart should be click-able. when clicked, visually highlight the row and use console.log to output 'Fruit selected: {fruitname}, {fruitnameTotal}'
- Do not cause a browser refresh, or navigate to another html page.  
- When a bar chart row is clicked, the list should be filtered to only display the people that chose that fruit as their favorite.
- Create an animation where the bars grow to their correct width when the data is loaded.
- Stack each bar from top to bottom in order of most popular to least popular.

##Stretch goals! (optional):
- Each bar is a different color.



