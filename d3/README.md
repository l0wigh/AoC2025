# Day 3

This is in fact the second challenge I did. I skipped the second one because it felt a bit too complicated for the small time I had to solve it.

I really like the solution I wrote for this one

## Functions

- get_highest_number: Started as a really small function, I had to make a function with 2 modes to be able to handle the first and second number differently. With the first number, you should stop before the end, even if the next one is bigger.
- split_list: Very elegant "manual" way to split the list at the first occurence of the biggest number we found. Probably could do it using a built-in function, but I prefer this.
- get_pair: Also a beautiful function that will get both numbers and add them together using int and not string conversion.
- resolve: Same as all code in this repo, just a simple "loop" going through every elements in the input (tail recursive on this one !)

## How it felt ?

Quite nice ! I haven't used Gleam in a long time and the experience there was awesome. I really get why Gleam is loved by many users. My only pain with it is that it can't really be compiled to run in "standalone".

It felt easier to solve this one than the day 1, and I must say it's not because of the language (OCaml IS awesome), but rather more because functionnal programming is slowly getting into my brain and was perfectly fitted for this challenge.

The only small difficulty I had was to deal with lack of if / else, but now I want to use this kind of pattern matching even in OCaml.

Very elegant solution. I guess every functionnal language give that kind of feeling ? (Maybe not Haskell...)
