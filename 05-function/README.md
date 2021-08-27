# Function

Function is a grouped statements with name. Rather than copying the same codes multiple times, a functions is used. A function needs to be declared in order to use it just like a variable.

```c++
int main();
```

The type indicates the type of value returned by the function. The function name is followed by parenthesis `()` where parameters can be inserted. Parameters are variables that exist only within the function. The parameter takes an argument given during the function call.

```c++
int sum(int x, int y);

int main() {
    std::cout << sum(5, 9) << std::endl;
    std::cin.get;
}
```

To use the function it needs to be defined. A function definition contains the declaration followed by a scope containing statements that will be executed when the function is called.

```c++
int sum(int x, int y) {
    return x + y;
}
```

When creating a function the definition can be separated writing it below the function or below the main function. Or just create the definition when making a function.
