# FT_PRINTF

Welcome to the ft_printf repository! This project is part of the curriculum at School 42 and focuses on implementing your own version of the printf function in C.

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In this repository, you will find the ft_printf project, which is a crucial step in developing a deep understanding of formatted output in C. The main objective is to recreate the behavior of the standard printf function, providing a flexible and extensible solution for formatted printing.

Explore the repository, study the code, and enhance it to improve your C programming skills.

## Objective

The objective of the ft_printf project is to enhance your understanding of variadic functions and string formatting in C. By implementing your own version of printf, you will gain insight into how the function works under the hood and develop a better understanding of format specifiers, conversions, and flags.

Moreover, the project aims to improve your problem-solving skills, code organization, and attention to detail. You will encounter various challenges while implementing the ft_printf function, allowing you to grow as a programmer.

## Features

- Support for various format specifiers, such as `%d`, `%s`, `%c`, `%x`, and more.
- Handling of flags, such as `0`, `-`, `+`, `#`, and space.
- Width and precision modifiers.
- Handling of variadic arguments.

## Technologies Used

- C programming language
- Makefile

## Installation

To use the ft_printf function in your projects, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/ft_printf.git

2. Change to the project directory:
    ```shel
    cd ft_printf
    
3. Compile the project:

    ```shell
    make

4. Include the ft_printf.h header file in your code:

    ```c
    #include "ft_printf.h"

5. Compile your project with the ft_printf function:

     ```shell
    gcc your_project.c libftprintf.a -o your_project

Now you can use the ft_printf function in your project by including the ft_printf.h header file and linking the libftprintf.a library.

## Usage

- To use the ft_printf function, call it in your code with the desired format specifier and arguments, similar to the standard printf function.
  
    ```c
    #include "ft_printf.h
    
    int main(void)
    {
        ft_printf("Hello World! %d", 2023);
        return (0);
    }
## Contributing

Contributions to the ft_printf project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Your contributions can help enhance the function and make it even more valuable for others.

This project was completed as part of the curriculum at School 42.
