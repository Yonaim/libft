# Libft

Libft is a personal study project in École 42 in which I re-implemented various functions from the standard C library. The main goal of this project was to reinforce my foundational computer science knowledge and programming skills by manually implementing common standard library functions.

## Goals

By manually coding standard library functions, I aimed to:

- Deepen my understanding of how basic library functions are structured and executed.
- Strengthen my skills and fluency in the C programming language.
- Enhance debugging and problem-solving abilities.
- Explore memory management concepts and algorithm efficiency in-depth.

## Implemented Functions

### Libc Functions

| Function Name | Description                        |
|---------------|------------------------------------|
| ft_memset     | Fill memory with a constant byte   |
| ft_bzero      | Zero a byte string                 |
| ft_memcpy     | Copy memory area                   |
| ft_memmove    | Copy memory area safely            |
| ft_memchr     | Scan memory for a character        |
| ft_memcmp     | Compare memory areas               |
| ft_strlen     | Calculate string length            |
| ft_strdup     | Duplicate a string                 |
| ft_strcpy     | Copy a string                      |
| ft_strncpy    | Copy a string with max length      |
| ft_strcat     | Concatenate two strings            |
| ft_strncat    | Concatenate strings with max length|
| ft_strchr     | Locate character in a string       |
| ft_strrchr    | Locate character from end of string|
| ft_strstr     | Locate substring                   |
| ft_strcmp     | Compare two strings                |
| ft_strncmp    | Compare strings with max length    |
| ft_atoi       | Convert ASCII to integer           |
| ft_isalpha    | Check for alphabetic character     |
| ft_isdigit    | Check for digit character          |
| ft_isalnum    | Check for alphanumeric character   |
| ft_isascii    | Check for ASCII character          |
| ft_isprint    | Check for printable character      |
| ft_toupper    | Convert to uppercase               |
| ft_tolower    | Convert to lowercase               |

### Additional Utility Functions

| Function Name | Description                           |
|---------------|---------------------------------------|
| ft_substr     | Extract substring from a string       |
| ft_strjoin    | Concatenate two strings               |
| ft_strtrim    | Trim characters from a string         |
| ft_split      | Split string by delimiter             |
| ft_itoa       | Convert integer to string             |
| ft_strmapi    | Apply function to each char of string |
| ft_putchar_fd | Output character to file descriptor   |
| ft_putstr_fd  | Output string to file descriptor      |
| ft_putendl_fd | Output string with newline to fd      |
| ft_putnbr_fd  | Output integer to file descriptor     |

## Installation

Clone this repository and build with provided Makefile:

```bash
git clone https://github.com/Yonaim/libft.git
cd libft
make
```

The `libft.a` library will be created after compilation.

## Usage

Include the `libft.h` header file and link the library in your C projects:

```c
#include "libft.h"
```

Compile your code with the libft library:

```bash
gcc yourfile.c -L. -lft -I includes -o yourprogram
```
