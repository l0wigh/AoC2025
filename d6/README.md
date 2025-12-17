# Day 6

Well, this is an import day for me. It was the test... Soluna is able to solve this problem.

I also have a video showing me solve it live. Strangely, even with issues, it was faster than in OCaml and Gleam...

## Functions

- each loop to clean the lists
    - lambda to check for " "
    - lambda to convert string to int
- each loop to go through every cols
    - function math: which apply the operator to every elements of the cols
- reduce on the list of calc results that add everything

## Split is broken ?

Maybe. Maybe not. I need to do more tests and check. But yeah that's the reason I used the lambda to check the length of string.

I can to a map that will remove these empty elements in Soluna source (OCaml). 

## How it felt ?

It felt amazingly more rewarding to solve this one. It also enlightened some issues with Soluna and that's great. I'll continue on improving Soluna from my observations on this challenge.

## Update

The day after completion, I fixed the split function to remove empty lists elements by default. The outdated solution is still in the repos for history reason.

It should still works with Soluna >= 0.4.4 but it does a useless filter on lists.
