
A **proof** is a sequence of logical steps that demonstrates the truth of a proposition using:
-  [[M1019 Rules of inference|Rules of inference]]
- **Given premises (axioms or assumptions)**
- **Previously established theorems**
  
Each statement in a proof must **follow logically** from previous statements or from accepted premises.

A typical proof follows this structure:

| **Step** | **Statement**     | **Justification**                |
| -------- | ----------------- | -------------------------------- |
| 1        | $p \rightarrow q$ | Premise                          |
| 2        | p                 | Premise                          |
| 3        | q                 | From 1 and 2 by **Modus Ponens** |

Every new statement must be justified by a **rule of inference** or defined as a **premise**.
###  Types of Proofs

| **Type**                            | **Description**                                                                          | **Example**                                 |
| ----------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------- |
| **Direct Proof**                    | Start with premises and use logical reasoning to reach the conclusion.                   | Prove: If n is even, then $n^2$ is even.    |
| **Indirect Proof (Contrapositive)** | Prove $p \rightarrow q$ by proving $\neg q \rightarrow \neg p$.                          | To show: “If $n^2$is even, then n is even.” |
| **Proof by Contradiction**          | Assume the opposite of what you want to prove and show that it leads to a contradiction. | Assume √2 is rational → contradiction.      |
| **Proof by Cases**                  | Divide into cases that together cover all possibilities.                                 | If n is even or odd → handle both cases.    |
| **Mathematical Induction**          | Used to prove statements about integers.                                                 | Prove 1 + 2 + … + n = $\frac{n(n+1)}{2}.$   |

### Truth Flow in a Proof

1. **Premises** — assumed true.
2. **Rules of inference** — preserve truth.
3. **Conclusions** — therefore must also be true (within the logical system).

🧠 In simple terms:
If every inference is valid and the premises are true → the conclusion must be true.

###  Example: 

| **Step** | **Statement**                               | **Justification**                              |
| -------- | ------------------------------------------- | ---------------------------------------------- |
| 1        | $\forall x (S(x) \rightarrow P(x))$         | Premise: all students who took the exam passed |
| 2        | $S(\text{John})$                            | Premise: John is a student                     |
| 3        | $S(\text{John}) \rightarrow P(\text{John})$ | From 1 by **Universal Instantiation**          |
| 4        | $P(\text{John})$                            | From 2 and 3 by **Modus Ponens**               |

