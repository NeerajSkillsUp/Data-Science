# R Programming Notes

This repository contains notes and examples on key R programming concepts.

---

## 1. Data Types in R

- **Numeric**: default type for numbers (`10`, `3.14`)
- **Integer**: created with `L` suffix (`10L`)
- **Character**: text values (`"hello"`)
- **Logical**: `TRUE` / `FALSE`
- **Factor**: categorical data with levels

```r
x <- 10      # numeric
y <- 10L     # integer
z <- "hi"    # character
w <- TRUE    # logical
f <- factor(c("red","blue","red"))
```

## 2. Scoping Rules and Control Flow

### Scoping

    Lexical scoping: R looks for variables first in the current environment, then in parent environments.

    Functions can access variables defined outside them.

### Control Flow

    if / else

    for / while / repeat loops

## 3. Apply Functions

    lapply: applies a function to each element of a list, returns a list

    sapply: simplified version, returns vector/matrix if possible

    tapply: applies function over subsets of a vector

    apply: applies function over rows/columns of a matrix

    split + lapply often replicates tapply

## 📘 Learning Goals

    Understand R’s basic data types

    Learn variable scoping and how control flow works

    Use apply family of functions for efficient computation
