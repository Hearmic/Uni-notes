Rules of inference are logical principles that allow us to **derive valid conclusions** from given premises. They form the foundation for [[M1019 Proofs|proofs]]. In a **proof**, every **premise** or **previously derived statement** is assumed true within the scope of the argument
### 1. Rules of Inference for Propositional Logic

These rules work with **propositional statements** — ones that are **either true or false** — using connectives such as ¬ (not), ∧ (and), ∨ (or), → (implies), and ↔ (if and only if).

 $\therefore$ <- Therefore (it can be subbstitutedwith "$\implies$")

| **Rule Name**                   | **Form (Formula)**                                                     | **Example**                                                                                                                                            |
| ------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Modus Ponens (MP)**           | p $\implies$ q<br>p<br>$\therefore$  q                                 | If it rains, the ground is wet.<br>It rains.<br>Therefore, the ground is wet.                                                                          |
| **Modus Tollens (MT)**          | p $\implies$ q<br>¬q<br>$\therefore$  ¬p                               | If I study (p), I pass (q).<br>I did not pass ($\neg$q)<br>Therefore, I did not study.                                                                 |
| **Hypothetical Syllogism (HS)** | p $\implies$ q<br>q $\implies$ r<br>$\therefore$  p $\implies$ r       | If I study (p), I learn (q).<br>If I learn (q), I pass (r).<br>Therefore, if I study (p), I pass (r).                                                  |
| **Disjunctive Syllogism (DS)**  | p ∨ q <br>¬p<br>$\therefore$  q                                        | Either I’ll code (p) or read (q).<br>and I won’t code <br>Therefore, I’ll read.                                                                        |
| **Simplification (SIMP)**       | p ∧ q<br>$\therefore$  p<br>--------------<br>p ∧ q<br>$\therefore$  q | It’s raining and windy<br>Therefore, it’s raining.<br>----------------------------------------<br>It’s raining and windy<br>Therefore, it’s windy.<br> |
| **Conjunction (CONJ)**          | p<br>q<br>$\therefore$ p ∧ q                                           | It’s Monday <br>I’m tired <br>$\therefore$ It’s Monday and I’m tired.                                                                                  |
| **Addition (ADD)**              | p<br>$\therefore$ p ∨ q                                                | I’m studying (True)<br>$\therefore$ I’m studying or doing anything else (also True)                                                                    |
| **Resolution (RES)**            | p ∨ q<br>¬p ∨ r<br>$\therefore$ q ∨ r                                  | if (p or q) is True<br>and (¬p or r) is True<br>$\therefore$ (q or r) is True                                                                          |

---

### 2. Rules of Inference for Predicate Logic (Quantifiers)

When statements contain **quantifiers** (∀ “for all”, ∃ “there exists”), propositional rules extend with additional rules that allow reasoning about **elements in a domain**.


| Rule name                  | Form(formula)                                              | Example |
| -------------------------- | ---------------------------------------------------------- | ------- |
| Universal Instantation     | $\forall x P(x)$<br>$\therefore P(c)$                      |         |
| Universal generalization   | $P(c)$ for an arbitrary $c$<br>$\therefore \forall x P(x)$ |         |
| Existential instantation   | $\exists xP(x)$<br>$P(c)$ for some c                       |         |
| Existential generalization | $P(c)$for some c<br>$\exists xP(x)$                        |         |

You can practice all of these rules here:
https://quizlet.com/49259264/rules-of-inference-flash-cards/