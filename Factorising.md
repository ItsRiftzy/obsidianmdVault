---
noteid: 202206071157
datecreated: 2022-06-07
alias: "Factorising Quadratic Equations"
---
tags: #math/algebra, #notes, #unfinished

# Factorising
---

Factorising is  common in [[Math]]. It is where a longer [[Quadratic Equations|quadratic equation]] is turned into a smaller, easier to comprehend form

E.g.
$$x^2 + 7x + 12$$
Will be factorised into:
$$(x+3)(x+4)$$


Because the two brackets multiplied together can create $x^2 + 7x + 12$

---
### Sum and Multiple Method
Factorising is a branch of [[Quadratic Equations]] 

There are many ways to factiorise quadratic equations, the most common and easiest method is known as the *Sum and Multiple Method* where you find the sum of one number that equals the factors of another number.

Let's take our example from above: $x^2 + 7x + 12$, 

For this we find the sum of $b$ that also multiply to make $c$. What that means is that whatever 2 numbers add to make 7 also have to multiply to make 12, which in this case is 4 and 3 (because 4 + 3 = 7 and 4 x 3 = 12)

This method doesn't work sometimes so we have to devise other methods

If we are dealing with a [[Null Factor Law]] equation then we can use the Quadratic Formula:
$$0 = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

When we do this we get two values, this is what $x$ will equal (e.g. x = 10 or x = -10)

---
### Factorising with a coefficient Larger than 1
**Example 1: $2x^2 + 14x + 24$ | Example 2: $2x + 11x + 9$**
If $a$'s coefficient is larger than one then there are two methods of solving 

1. Common Factor
 This is where the entire equation has a common factor and the factor can be moved to the outside while the rest is factorised normally, this is the case for example one

Example solving
1. Divide by the common factor -> $2(x^2 + 7x + 12)$
2. Factorise the inner bracket -> $2(x+3)(x+4)$

2. Grouping
This is when the equation *doesn't* have a common factor we factorise using the [[Factorising#Grouping|Grouping]] technique, this is very similar to the [[Factorising#Sum and Multiple Method|Sum and Multiple]] method, Example 2 is a perfect use case for this.
--- 
Steps taken in Example 2

- Multiply $a$ by $c$: $2 * 9 = 18$ -> lets call this $x$
- Find 2 numbers that add to give $b$ and multiply to give $x$: 9+2 = 11 and 9x2 = 18 (or $x$)
### Finish this!!!!

However there is a method that will work 100% of the time, but it's fairly complicated.

---

### Completing the Square
Completing the square essentially means you will get a number that you can always factorise, afterwards you add on the square roots of the other numbers that didn't get factorised.

Example: $x^2 + 6x + 14$
Example 2: $x+6x-14$ 

**Steps:**
1. First, halve $b$ and square it, then add it and immediately subtract it -> $x^2 + 6x + (\frac{6}{2})^2 - (\frac{6}{2})^2 + 14$
2. Next, solve the values -> $x^2 + 6x + 9 - 9 + 14$
3. Then, factorise the first part of the equation -> $(x+3)^2 - 9 + 14$
4. We're almost there, next add the last 2 values together -> $(x+3)^2 + 5$
5. Finally, add the square root of that number to one bracket, and subtract it in the other bracket -> $(x+3+\sqrt{5})(x+3-\sqrt{5})$ 

That's it!


Let's apply this to a [[Null Factor Law]] equation. This sometimes can, or cannot work. For it to work $c$ will most likely have to be a negative number.

1. Move $c$ to the opposite side -> $x^2 + 6x = 14$ 
2. Next, halve $b$, square that number and add it to both sides -> $x^2 + 6x + (\frac{6}{2})^2 = 14 + (\frac{6}{2})^2$
3. Solve the exponents as well -> $x^2 + 6x + 9 = 14 + 9$ 
4. Next, factorise the first part of the equation -> $(x+3)^2 = 23$ 
5. Square root both sides -> $x+3 = \sqrt{23}$ 
6. Finally, subtract the remaining number from both sides -> $x = \sqrt{23} - 3$ -> $x = 1.79$ 

---




