# My Discrete Math Repository

## Homework 2 - 202655377 CHO HYEONG CHAN

### 2.1 Equation Editing
| # | text | formula |
|---|------|---------|
| 1 | IF (P AND Q) THEN R | $$(P\land Q) \to R$$|
| 2 | (P XOR Q) OR R | $$(P \oplus Q) \lor R $$      |
| 3 | NOT P IFF Q |  $$\neg P \leftrightarrow Q$$   |
| 4 | FOR ALL x, P(x) | $$(\forall x) P(x)$$  |
| 5 | THERE EXISTS AN x, NOT Q(x) | $$(\exists x) \neg Q(x)$$ |
| 6 | IF P THEN Q EQUIVALENT TO NOT P OR Q | $$P \to Q \equiv  \neg P \lor Q$$ |
| 7 | Euler's Identity |  $$e^i\pi + 1 = 0$$  |
| 8 | SUM of n from 1 to 100 Equals 5050 | $$\sum_{n=1}^{100} n = 5050$$ |

### 2.2 Translation
Using the propositions 

* $p$ = "I study"
* $q$ = "I will pass the course"
* $r$ = "The professor accepts bribes" 

Translate the following into statements of propositional logic:

1. If I do not study, then I will only pass the course if the professor accepts bribes.<br>
  $$\neg p \to (q \to r)$$
2. If the professor accepts bribes, then I do not study.<br>
  $$r \to \neg p$$
3. The professor does not accept bribes, but I study and will pass the course.<br>
  $$\neg r \land p \land q$$
4. If I study, the professor will accept bribes and I will pass the course.<br>
  $$p \to (r \land q)$$
5. I will not pass the course but the professor accepts bribes.<br>
  $$\neg q \land r $$
