# Grade Calculator

This is the template for tasks. These repos are the starting points and instructions for students to explore a concept.

## Instructions

1. Create an app called: grade_calculator.
2. Create a stateless widget `HomeScreen` with a `Scaffold`.
3. Create an `AppBar` with a `title`.
4. In your scaffold body, create a `Column` widget.
5. Inside the Column widget, create 3 widgets: `TextField`, `ElevatedButton` and a `Text` widget.
6. Style your TextField, Button and text Widgets.
7. Create a `TextEditingController` for the `TextField` and assign it to the `TextField`.
8. Create a `String` variable to store the result in and replace it with the text in your `Text` widget.
9. Create a function to calculate the result following those conditions:

```
A if score >= 90%
B if score >= 80%
C if score >= 70%
D if score >= 60%
F if score  < 60%
```

10. In your `onPressed` function, create a variable and store the value of the `TextEditingController` in it.
11. Call the function you created and pass the variable to it, then assign the returned value to the result variable.
12. Convert the `HomeScreen` to a stateful widget.
13. Call `setState` and move the result assignment to it.
