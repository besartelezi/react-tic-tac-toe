# React: Raspberry Extract And Chocolate Toppings
One of the assignments given to us by BeCode was to create a lil' Kahoot app of our own using React.
I read through all the documentation of React and wrote everything down to help me understand it.
But I'm not the type of person to just learn by reading, I need to make my hands dirty and work on something if I want to really understand and learn it.

As I was reading through the React documentation, I stumbled upon [this cool link!](https://reactjs.org/tutorial/tutorial.html)
The official React documentation gave us a guide on how to get started on React by making a tic-tac-toe game.
So that's what I'm going to do before working any further on the personalized Kahoot/Quiz app.

This might not be the most optimal way to do it, but I do not care.
If finishing this tic-tac-toe game will help me understand React on a more **FUN**demental level, then it won't matter how much time I spend on this.

I still intend to finish the Kahoot/Quiz app, but right now, I'd rather learn how to create something properly with React than to finish the app without really understanding how it works.

I also won't be documenting everything regarding this tic-tact-toe app, since the documentation for is it available on the React website.

## Things I learned
````
As a next step, we want the Square component to “remember” that it got clicked, and fill it with an “X” mark. 
To “remember” things, components use state.
````
This helped me understand state a bit better.
It also made me that states are more helpful and important than I previously thoughts.

## Subjects I still don't quite understand:
* Passing props
  * What props are exactly
  * (I know they're similar to variables)

## Ideas I got on how to do the KahooQuiz App
````
<button className="answer" onClick={function () {'code that sets the hasChosen value of this answer to true }}>
Once user is done with quiz, check all the answers.
Actually, user doesn't even need to be done with quiz, just call a the function with the code below everytime the user clicks on an answer.
If the hasChosen === true && answer === correctAnswer => userPoints++
````

