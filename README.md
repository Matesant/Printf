# Printf

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="header-container">
        <img src="https://raw.githubusercontent.com/ayogun/42-project-badges/main/covers/cover-libft-bonus.png" width="400" alt="Imagem 1"/>
        <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMGJiY2ZpcnVtZmtlMXRxY3VscXFwMjd4M29xN3h0eDcycnd4cG9pbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2JhwdnrGvfnoXrzi/giphy.webp" width="200" alt="Imagem 2"/>
	<img src="https://raw.githubusercontent.com/ayogun/42-project-badges/main/covers/cover-libft-bonus.png" width="400" alt="Imagem 1"/>
    </div>
</body>
</html>


<h1 align="center">School 42 printf()</h1>

This repository contains the third project of 42 curriculum, the Printf function. This projects make we replicate the original [`printf()`](https://es.wikipedia.org/wiki/Printf) function part of `<stdio.h>` library

<h2 align="center">
	<a href="#about">About</a>
	<span> · </span>
	<a href="#requirements">Requirements</a>
	<span> · </span>
	<a href="#instructions">Instructions</a>
	<span> · </span>
	<a href="#testing">Testing</a>
</h2>

## About
Our printf function does not need to manage a buffer but should return an integer representing the size of the printed output. It needs to support the following types of variables:

`char` type variables: `%c`
`string` type variables: `%s`
`int` type variables: `%d`
`unsigned int` type variables: `%u`
`hexadecimal int` type variables (both uppercase and lowercase): `%x` and `%X`
`pointer` type variables: `%p`

### Structure
The biggest challenge in this project is handling multiple arguments and returning a integer that is correct.

## Requirements
The functions are written in __C language__ and need the `gcc` compiler, with `<stdlib.h>`, `<stdarg.h>` and `<unistd.h>` standard libraries to run.

## Instructions

### 1. Compiling the archives

To compile the proiect, go to its path and run:

For __mandatory__ functions:
```
$ make
```
### 2. Cleaning all binary (.o) and executable files (.a)

To delete all files generated with make, go to the path and run:
```
$ make fclean
```

### 3. Using it in your code

To use this project in your code, simply include this header:
```
#include "ft_printf.h"
```

## Testing
This function have been tested with [Francinette](https://github.com/xicodomingues/francinette).
