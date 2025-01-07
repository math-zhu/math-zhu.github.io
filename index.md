---
layout: default
title: "Welcome to Yi Zhu's Website"
---

# Hello, I'm Yi Zhu!

Welcome to my personal website. 

## About Me

I am passionate about mathemtics.

# Proof that There Are Infinitely Many Primes

The classic proof that there are infinitely many prime numbers is attributed to **Euclid** and is based on a **proof by contradiction**. Here's how the proof works:

## Proof by Contradiction

1. **Assume the contrary**: Suppose there are only finitely many primes. Let these primes be \( p_1, p_2, p_3, \dots, p_n \), where \( n \) is some finite number of primes.

2. **Consider a new number**: Now, consider a new number \( N \) defined as follows:
   \[
   N = p_1 \cdot p_2 \cdot p_3 \cdot \dots \cdot p_n + 1
   \]
   Here, \( N \) is the product of all the primes plus 1.

3. **Analyze the divisibility of \( N \)**: Now, consider the prime divisors of \( N \). By construction, \( N \) is **not divisible by any of the primes** \( p_1, p_2, p_3, \dots, p_n \). To see this, notice that when you divide \( N \) by any \( p_i \), you get a remainder of 1:
   \[
   N \div p_i = (p_1 \cdot p_2 \cdot \dots \cdot p_n + 1) \div p_i = \text{some integer} + \frac{1}{p_i}
   \]
   So, \( N \) is not divisible by \( p_1, p_2, p_3, \dots, p_n \).

4. **Conclusion**: Since \( N \) is greater than 1 and is not divisible by any of the primes \( p_1, p_2, \dots, p_n \), it must either be:
   - **Prime itself**, or
   - Have a prime factor not in the list \( p_1, p_2, \dots, p_n \).

   In either case, we have found a prime that is not in our original list of primes. This contradicts our assumption that there were only finitely many primes. Therefore, the assumption that there are finitely many primes must be false.



