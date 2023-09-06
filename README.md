[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11754600&assignment_repo_type=AssignmentRepo)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length))
    if(foo > a[0]) return foo;
    else return a[0];
}
```

This function is a recursive function that finds the greatest character in an array and returns it. The first line in the function checks if the array has more than one character, if not it returns that character. The second line assigns to the variable, foo, what is returned by the recursively called function that has been given the original array excluding the first value. The third and fourth line compares foo and the first character in the string and returns whichever is greater.

I forgot to add I used the book Javascript pocket reference 3rd edition and the help of Jacob Taylor my classmate.
