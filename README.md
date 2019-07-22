# Computational Thinking

## Elements:
* Decomposition (break a big problem into smaller ones)
* Pattern Recognition 
* Abstraction (removing details to get to the big picture)
* Algorithm Design (writing directions)

### Example:  Sum the integers from 1 to 200

#### Decomposition:
- Break it down into smaller addition problems:

-- 1+2, 3+4, 5+6, ...

--- Do you notice any useful patterns?

-- 200 + 1, 199 + 2, 198 + 3, ...

--- Do you notice any useful patterns this time?

## Pattern Recognition:
- The useful pattern is that each pair sums to 201.

- Now need to find the number of pairs...

## Abstraction:
- Our problem can be solved by finding the sum of the pairs, the number of pairs, and the product of those numbers.

-- 201 (sum of pairs) * 100 (200/2 number of pairs)

- In general, if we want to sum the integers from 1 to n the solution is the same...

## Algorithm:
- Find the sum of the pairs (lowest + highest number)

- Find the number of pairs (highest / 2)

- Multiply those two numbers.

Will this algorithm work if we want to sum the numbers from 567 to 8901?  Why or why not?

How can you modify the algorithm to make it work?

In this repository, you will find two additional files, Pattern_Recognition_Challenges and Algorithm_Challenges.
Edit those files with your answers and commit the changes to GitHub.

