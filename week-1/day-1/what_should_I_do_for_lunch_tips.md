## `Tips` for lunch code
1. Always break down the problem
2. Write pseudo code
3. convert pseudo code to JS
4. remove repetitions

## Here's my function code
~~~ javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry){
    if (availableTime < 20){
      console.log("pick up a snack or grab something you have ready at home.");
    } else if (availableTime >= 20 && availableTime <= 30){
      console.log("you deserve a break and should take time to cook a tasty meal.");
    } else if (availableTime >= 30) {
      console.log("this is an intense program after all and you should probably reconsider.");
    }
  } else {
    console.log("Get back to work");
  }
}
~~~


