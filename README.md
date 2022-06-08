# Grade Calculator 🇦

![screenshot](https://user-images.githubusercontent.com/84308096/158198001-e9017006-6726-44d0-8ada-95b709eed7ff.png)

## 🍋 Instructions

1. Create an app called: grade_calculator.
2. Create a stateless widget `HomeScreen` that returns a `Scaffold` widget.
3. Create an `AppBar` with a `title`.
4. Pass a `Column` widget to the `Scaffold` body.
5. Inside the `Column`'s children, create 3 widgets: `TextField`, `ElevatedButton` and a `Text` widget.
6. Style your `TextField`, `Button` and `Text` Widgets.
7. Run the app to make sure that everything is working fine on the screen.
8. Create a `TextEditingController` for the `TextField`, then assign it to the `TextField`'s controller.
9. Create a `String` variable to store the result in, then pass it to the `Text` widget.
10. Create a function that takes the grade as an input and then calculates the result following the conditions below:

```
A if score >= 90%
B if score >= 80%
C if score >= 70%
D if score >= 60%
F if score  < 60%
```

11. In your `onPressed` function:
    - Create a variable called **grade** and store the value of the `TextEditingController` in it.
    - Call the function you created and pass the **grade** variable to it, then assign the returned value to the result variable.
12. Convert the `HomeScreen` to a stateful widget.
13. Call `setState` in your `onPressed` function and move the result assignment to it.
