# IO Redirections and Filters

## Introduction
This project covers the basics of input/output redirections and filters in a Unix-like operating system. You will learn how to manipulate file descriptors, redirect input and output, and use various filters to process data streams.

## Table of Contents
- [IO Redirections and Filters](#io-redirections-and-filters)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [What are IO Redirections?](#what-are-io-redirections)
  - [Types of Redirections](#types-of-redirections)
  - [Common Filters](#common-filters)
  - [Examples](#examples)

## What are IO Redirections?
IO redirections allow you to change the standard input, output, and error streams of commands. This enables you to read from files, write to files, and chain commands together.

## Types of Redirections
- **Input Redirection (`<`)**: Redirects input from a file to a command.
- **Output Redirection (`>`)**: Redirects output from a command to a file, overwriting the file.
- **Append Redirection (`>>`)**: Redirects output from a command to a file, appending to the file.
- **Error Redirection (`2>`)**: Redirects error messages from a command to a file.
- **Combined Redirection (`&>`)**: Redirects both output and error messages to a file.

## Common Filters
- **`cat`**: Concatenates and displays file content.
- **`grep`**: Searches for patterns in text.
- **`sort`**: Sorts lines of text.
- **`uniq`**: Removes duplicate lines.
- **`wc`**: Counts lines, words, and characters.
- **`head`**: Displays the beginning of a file.
- **`tail`**: Displays the end of a file.
- **`tr`**: Translates or deletes characters.
- **`cut`**: Removes sections from each line of files.

## Examples
- Redirecting input from a file:
    ```sh
    command < inputfile
    ```
- Redirecting output to a file:
    ```sh
    command > outputfile
    ```
- Appending output to a file:
    ```sh
    command >> outputfile
    ```
- Using a filter to process data:
    ```sh
    cat file.txt | grep "pattern"
    ```
