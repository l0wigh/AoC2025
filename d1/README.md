# Day 1

This day was kinda hard because I wanted to do an elegant solution. In fact it's not that hard and it's great to do in functionnal style. 

## Functions

- get_mov: Take the first letter of the string and then convert to int the rest of the string. I use 0 - value for left to get a negative movement.
- calc_mov: The kinda ugly function of the code. It works by using an auxiliary function. The aux function get the function to apply (- or +), the limit (aka the movement), a counter and the calculation. It's basically a loop that check multiple conditions.
- resolve: Interesting function since I used a tuple as argument to be able to return 2 variables from `calc_mov`. It will go through all the input strings one by one and do a chain with the previous functions then call itself.

## Ugly design

I first wanted to do `calc_mov` in pure pattern matching but faced some issues and "special" cases that couldn't be handled without using if / else.

It's still purely functionnal and it's not using imperative tricks to avoid issues. input -> function chain -> output.

## How it felt ?

It felt nice to solve even if it was a bit messy. Finding the exact reason on why it wasn't working was a bit of a headache. Nonetheless I was happy to be able to solve this first challenge in OCaml using only the documentation.
