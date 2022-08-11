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
### State
````
As a next step, we want the Square component to “remember” that it got clicked, and fill it with an “X” mark. 
To “remember” things, components use state.
````
This helped me understand state a bit better.
It also made me that states are more helpful and important than I previously thoughts.

### Parent and Child components
"To collect data from multiple children, or to have two child components communicate with each other, you need to declare the shared state in their parent component instead.
The parent component can pass the state back down to the children by using props;
this keeps the child components in sync with each other and with the parent component."

I still don't understand 100% how and when to use this, but I do understand the advantages to it and what it theoretically means.

### Immutability
Apparently, there are two general approaches to changing data.
The first is to *mutate* the data, you **directly** change the data's values.
The second one is to replace the data with a new copy, that has the desired changes made to it.

By not mutating the data, we gain several benefits that will be described below.

#### Complex Features Become Simple
Some complex features become much easier to implement.
An example given to us in this tutorial is the "time travel" feature.
You can jump back to some previous moves you made.
This is possible because you didn't change the original data.

Time travel is a common functionality of many apps, so it's worth 

#### Detecting Changes
Since we're cloning the data, and modifying the cloned data, we can still use the original data to compare the changes.

#### Determining When to Re-Render in React
Now we're on to the main benefit of immutability.
It helps you build *pure components* in React.
With immutable data, you can easily determine if changes have been made, through this, you can also easily determine when a component requires re-rendering.

## Subjects I still don't quite understand:
* Passing props
  * What props are exactly
  * (I know they're similar to variables)
* Controlled components
  * Something I should look into, it was only mentioned in the guide.
* Pure components
  * [Read this](https://reactjs.org/docs/optimizing-performance.html#examples)

## Ideas I got on how to do the KahooQuiz App
````
<button className="answer" onClick={function () {'code that sets the hasChosen value of this answer to true }}>
Once user is done with quiz, check all the answers.
Actually, user doesn't even need to be done with quiz, just call a the function with the code below everytime the user clicks on an answer.
If the hasChosen === true && answer === correctAnswer => userPoints++
````

