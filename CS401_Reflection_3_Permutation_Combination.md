1. k-permutations WITHOUT repetitions – number of ORDERED subsets (k out of n)– P(n, k)
   
- What kind of question does this solve?
  – the number of ORDERED subsets with k objects out of a set of n objects
  – from n objects, choose k of them, then arrange them in order.(reference: the beginning of video 3)

- There are n! ways to arrange n elements in order.
  - e.g. How many ways can we organize 24 people in order? 24*23*22..*1 = 24!

- In how many ways can we order a subset of size k when taken out of a set of size n? 
  - n(n-1)(n-2)...(n-k+1) ways. 
  - This is called P(n,k) (Rosen 6.3). 
  - Proof: Let’s create k slots. The first slot has n possibilities; the 2nd slot has (n-1) possibilities; the 3rd slot has (n-2) possibilities… and the number k slot has (n-k+1) possibilities. We multiply them according to the product rule.

- Note:  
  - ∵ n! = n(n-1)(n-2)...(n-k+1)(n-k)(n-k-1)(n-k-2)...1
  - (n-k)! = (n-k)(n-k-1)(n-k-2)...1
  - ∴n!/(n-k)! = n(n-1)(n-2)...(n-k+1)
  - P(n, k) = n!/(n-k)! = n(n-1)(n-2)...(n-k+1)

- Definition of permutation and k-permutation:
   - A permutation of a set of distinct objects is an ordered arrangement of these objects.We also are interested in ordered arrangements of some of the elements of a set. An ordered arrangement of k elements of a set is called an k-permutation (Rosen 6.3).
 
2.  k-combinations WITHOUT repetitions – number of UNORDERED subsets (k out of n); – C(n, k)
   
- What kind of problem does it solve?
   - Finding the number of UNORDERED subsets with k elements of a set with n elements.
   - From a set with n elements, just choose k of them; leave them unarranged and unordered.
- Definition of k-combination:
   - An k-combination of elements of a set is an unordered selection of k elements from the set.
   - Thus, an k-combination is simply a subset of the set with k elements.(Rosen 6.3)
- How to calculate the number of k-combinations:
   - k-permutations/k! = n!/(n-k)!k!
   - = n choose k = C(n, k)
   - We need to divide k-permutations, which is n!/(n-k)! by k! – this is for excluding the ones calculated repeatedly.
   - There are k! ways to arrange a subset of k elements. When calculating the number of (ordered) k-permunations, we count EACH of the k! possibilities (e.g. {1,2,3}{1,3,2}{2,1,3}{2,3,1}{3,1,2}{3,2,1}; here k=3, k!=3*2*1=1). But when calculating the number of k-combinations, all those possibilities consisting of k element are only count ONCE (e.g. {1,2,3} is the same with {3,2,1})
-  C(n,k) = C(n, n-k)
   - Every time you choose k from n, you exclude (n-k) from n.
 
3. k-permutations WITH repetitions, ORDERED– k^n (slots, k options)
   - (I just copied and pasted from my reflection 1 here.) The product rule is a counting technique. It counts the number of steps it takes to complete a task. If there are n steps, and each step has k options, there should be k^n ways to complete that task. We should pay attention that k, the number of options to complete each step, is the base（底数）, and n, the number of steps (or “layers”), is the exponent （指数）.

4. k-combinations WITH repetitions; UNORDERED – “Stars and Bars”
   - What kind of questions does this model solve?
     - Using (k-1) bars to split n objects.
   - e.g. How many ways do we have to distribute n cupcakes to k people?
     - (note: all cupcakes are the same, so the order doesn’t matter)
     - Solution: To distribute n cupcakes to k people, we just need to put (k-1) bars inbetween the gaps of n cupcakes (“stars”). The number of “bars” and “stars” are (n+k-1) in total.
     - Now let’s imagine we create (n+k-1) slots, we know that n of them are cupcakes, and (k-1) of them are bars. If the stars are fixed and we put bars inbetweem them, the number of ways we can arrange the bars are C(n+k-1, k-1). Similarly, if the bars are fixed and we put the stars in between them, the number of ways we arrange the stars are C(n+k-1, n).
Now matter which is solution we take, the number should be the same.
   - So C(n+k-1, k-1) = C(n+k-1, n) = (n+k-1)!/k!(n-1)!
    
