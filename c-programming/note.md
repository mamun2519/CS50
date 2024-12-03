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
