# CPTS317-Automata-FormalLanguages

## Midterm Grade: 46/57

###

1.2. (0+1)101(0+1)*010(0+1) + (0+1)010(0+1)*101(0+1) + (0+1)0101(0+1) + (0+1)1010(0+1) 1.4. (0+1)*1 + ^
Eshwar Nag Pilli, Oct 10, 2022 at 4:32pm
3. transitions and state missing. 4. Incomplete steps 7. Needed to show L = L1 ∩ L̅2 ∩ L̅3, regularity is closed under intersection and complement.


## Final Grade: 99/140

### 

1. S -> FB | GE A -> CD B -> DE C -> a D -> b E -> c F -> AA G -> CD 
3. S -> Sa | Aa A -> aAaaa | B B -> bBaaaa | ^
4. 4. Define L’ = L ∩ L’’ where L’’ is the set of all words with odd lengths. Notice that L’’ = ( Σ .  Σ)* is regular, and hence L’ is a context-free language (c.f. language are closed under intersecting with regular languages). Notice that L’ ≠ ϕ iff there is a word in L with an odd length. The result follows since whether a context-free language is empty is decidable.
6. δ(q0,a) = (q1, a, R) δ(q1,a) = (q2, a, R) δ(q2,a) = (q1, a, R) δ(q1,a) = (q3 a, R) δ(q3,a) = (q4, a, R) 8. Since L1 is r.e, we have a TM M1 to accept it. Since L2 is recursive, we have all M2 to recognize it. To show that L1 ∪ ¬L2 is r.e. we construct a TM to accept it as follows: input x Run M1 on x and in parallel to this Rum M2 on x. if M1 says yes, ret yes, if M2 says no, ret yes. Clearly, M accepts L1 ∪ ¬L2 10. {1^(2n) 0^(2n+1) : n>-0} 12. Since L is recursive, we have a TM M(which is analog) to recognize it. We now construct an algorithm M’ to recognize the given language {x: ∃y |x|=|y|, xy∈L} as follows: M’: input x Enumerate all words y with the same length as |x|, Run M on xy, if M says yes ret yes. Ret No.
Eshwar Nag Pilli, Dec 15, 2022 at 11:23pm
7. Garbage Instruction not given ''
9. Since L is reg, Let M be a FA to accept it. We now construct a PDA M’ to accept L’ = {xxr : Ǝy xy ∈ L, |x| = |y|} M’ runs on input w as follows. It keeps reading the input and pushes the symbol into stack. At the same time it stimulate FA M working on the same input in parallel. Some moments later, M guesses it is in the middle of the input. For each symbol it reads from the input it pops and compares it with the top of the stack and at the same time , it guesses a symbol and let FA M continue to run on the guessed symbol. At the end of the input M’ says yes if stack is empty and the FA M says yes. '' 11 5 correct 13. Since LE is r.e., we have a TM to accept it. We create a TM to accept the given language { x : Ǝy. xy∈ L} as follows M’ input x for each n from 0 to ∞ , enumerate all words with length <= n. Run M on each of the enumerated words for up to n steps. If one of the steps says yes return yes. Clearly M’ accepts language. ''
