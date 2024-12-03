## Functions

```jsx
#include <stdio.h>

int main(void)
{
    printf("hello, world\n")
}
```

- Notice also the special symbol \n in your code. Try removing those characters and making your program again by executing make hello. Typing ./hello in the terminal window, how did your program change? This \ character is called an escape character that tells the compiler that \n is a special instruction.
  note: #include <stdio.h> this call header file

## Variables

```jsx
#include <stdio.h>

int main(void)
{
    string answer = get_string("What's your name? ");
    printf("hello, %s\n", answer);
}

```

- %s is a placeholder called a format code that tells the printf function to prepare to receive a string. answer is the string being passed to %s.

## Conditionals

```jsx
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int x = get_int("What's x? ");
    int y = get_int("What's y? ");

    if (x < y)
    {
        printf("x is less than y\n");
    }
}

```

## Loops

```jsx
#include <stdio.h>

int main(void)
{
    int i = 3;
    while (i > 0)
    {
        printf("meow\n");
        i--;
    }
}

```

## Operators and Abstraction

```jsx
#include <cs50.h>
#include <stdio.h>

int add(int a, int b);

int main(void)
{
    // Prompt user for x
    int x = get_int("x: ");

    // Prompt user for y
    int y = get_int("y: ");

    // Perform addition
    printf("%i\n", add(x, y));
}

int add(int a, int b)
{
    return a + b;
}

```

## Linux and the Command Line

- Linux is an operating system that is accessible via the command line in the terminal window in VS Code.
- Some common command-line arguments we may use include
- cd, for changing our current directory (folder)
- cp, for copying files and directories
- ls, for listing files in a directory
- mkdir, for making a directory
- mv, for moving (renaming) files and directories
- rm, for removing (deleting) files
- rmdir, for removing (deleting) directories
