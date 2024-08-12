# Homeworks 

## [Homework 0](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework0)

### Overview
#### Details of the Tasks:

#### 1, Languages Definition:

- L1: Consists of all words containing at least three 'a's.
- L2: Consists of all words with an equal number of 'a's and 'b's.

#### 2. Robot Programming:

- The student is tasked to program a hypothetical robot, M, which can show one of two flowers (red for 'a' and blue for 'b') at each second. The programming must ensure the robot's observable behaviors (flower showing sequences) match the conditions of languages L1 and L2 respectively.

**Task 1**: Program the robot so that its behavior fits the description of L1.

**Task 2**: Program the robot so that its behavior matches L2.

#### 3. Memory Usage Argument:
- Task 3: Discuss intuitively why a fixed and finite amount of memory is sufficient for programming the robot for L1, while an unbounded memory is necessary for L2. This part of the homework focuses on understanding how memory requirements change with the complexity of the task a machine (or automaton) needs to perform.

#### 4. Complexity Comparison:

- Task 4: Despite concluding from Task 3 that L2 is more complex than L1 in terms of memory requirements for machine realization, this task challenges students to compare the complexity of individual words from each language. Students are asked to propose a method to measure the complexity of a single word, using examples:
  - w1 = aaababaababaaabbaab (from L1)
  - w2 = aaaaaaaaabbbbbbbbb (from L2)

This part seeks to engage students in thinking critically about how complexity can be assessed not just at the language level but also at the level of individual string patterns.

--- 

## [Homework 1](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework1)

### Overview
#### Topics Covered

#### 1. Regular Expressions:

- Students are tasked with providing examples and counterexamples for specific regular expressions, fostering a deeper understanding of language acceptance criteria defined by regular expressions.

#### 2. Creation of Regular Expressions:

- The homework includes exercises that require students to construct regular expressions for languages with specific properties, such as strings containing more than two '0's, strings that do not contain '01', and more.

#### 3. Language Operations:

- The assignment explores complex operations involving languages, such as concatenation and Kleene star, and their properties. It challenges students to demonstrate and rationalize about the properties of these operations on formal languages.

#### 4. Language Complexity:

- Students explore the complexity and expressiveness of languages, examining the implications of these properties through examples that challenge preconceived notions about language operations.

#### 5. Practical Application:

- The assignment concludes with a practical scenario involving a hypothetical fish tank. Students must apply their understanding of regular expressions to model the possible configurations of fish in the tank over several days, demonstrating the application of theoretical concepts to everyday problems.

#### Specific Tasks
- #####  **Task 1**: Provide an example and a counterexample for two given regular expressions. This task helps students understand the specificity and limits of what each regular expression can represent.

- ##### **Task 2**: Formulate regular expressions for languages defined by specific conditions. This exercises students' ability to synthesize their understanding of regular expressions to match given language descriptions.

- #####  **Task 3**: Prove given properties about operations on languages. This task encourages a deeper theoretical engagement with the properties of language operations.

- ##### **Task 4**: Provide a counterexample to a stated equivalence of language expressions. This task challenges students to critically analyze and question language operation properties.

- #####  **Task 5**: Develop a regular expression to describe possible sequences of fish tank configurations. This real-world scenario bridges theoretical knowledge with practical application, highlighting the utility of formal languages in diverse contexts.
---

## [Homework 2](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework2)

### Overview
#### Topics Covered

#### 1. Properties of Regular Languages:

- Demonstrating that certain operations on regular languages, such as deriving a subset of words that end with a specific symbol, preserve regularity.

#### 2. Manipulation and Reversal of Languages:
- Understanding how to reverse languages and proving that the reversal of a regular language is also regular.

#### 3. Regular Expression Construction:
- Constructing regular expressions that describe complex behaviors and properties, such as ending with a certain symbol or the reversal of languages defined by specific patterns.

#### 4. Practical Application and Algorithm Design:
- Developing an algorithm to find all shortest words in a regular language defined by a given regular expression, which combines theoretical knowledge with practical algorithm design.

#### Specific Tasks
- ##### Task 1: Prove that the subset of a regular language ending with a specific symbol is regular.
- ##### Task 2: Define a regular expression for a given language modified to end with a particular symbol.
- ##### Task 3: Show that the reversal of a regular language is regular, reinforcing the closure properties of regular languages.
- ##### Task 4: Construct a regular expression representing the reversal of a given language.
- ##### Task 5: Identify all shortest words in a defined regular language, applying the knowledge of language properties.
- ##### Task 6: Design an algorithm to find all shortest words for any regular language described by a regular expression.
---

## [Homework 3](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework3)

### Overview

#### Topics Covered

#### 1. DFA Construction and Operations:
- Students are tasked with drawing deterministic finite automata (DFA) for given regular languages and their combinations, enhancing their understanding of how automata can be constructed to represent complex language behaviors.

#### 2. Regular Expressions and Language Properties:
- The homework includes exercises for converting regular languages into regular expressions, particularly focusing on languages resulting from specific operations such as intersection.

#### 3. Language Reversal and Complement:
- Understanding how the reversal and complement operations affect regular languages and proving that these operations preserve the regularity of languages.

#### 4. Practical Application in Encoding Numbers:
- Applying regular expressions to represent sets of numbers based on specific properties, translating mathematical constraints into language constraints.

#### 5. Language Modification by Dropping Symbols:
- Exploring the impact of removing specific symbols from the words of a language and proving the resulting language's regularity.

#### Specific Tasks
- ##### Task 1: Construct DFAs for given regular languages 𝐿1 and 𝐿2, their intersection, and derive the regular expression for the intersection.
- ##### Task 2: Develop regular expressions representing sets of numbers with specific modular properties using unary encoding.
- ##### Task 3: Prove that deterministic finite automata (DFAs) are closed under the complement operation, emphasizing the theoretical underpinnings of DFA operations.
- ##### Task 4: Based on proofs from previous tasks, draw a DFA for the complement of a specific language and provide the corresponding regular expression.
- ##### Task 5: Show that if a regular language undergoes symbol dropping (removing specific symbols from all its words), the resulting language remains regular.

--- 

## [Homework 4](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework4)

### Overview
#### Topics Covered

#### 1. NFA to DFA Conversion:

- Students are tasked with converting a given NFA into an equivalent DFA, ensuring that the translated automaton accepts the same language as the original NFA. This exercise helps students understand the systematic process of state explosion and transition redefinition involved in such conversions.

#### 2. Regular Expression Derivation:

- Alongside the NFA to DFA conversion, students are required to provide a regular expression that describes the language accepted by the automaton. This part of the task ties the graphical representation of automata to the symbolic representation using regular expressions.

#### 3. Application to Programming:

- The assignment includes a task to expand a deterministic program into a non-deterministic format and then determine the regular expression for all input sequences that lead the program to a specific end state (Halt). This exercise helps students apply theoretical knowledge from automata to practical scenarios in programming, emphasizing the concept of non-determinism in a tangible context.

#### Specific Tasks

- ##### Task 1:
  - Convert an NFA to a DFA: Students must construct a DFA that has an equivalent language acceptance as a given NFA. This involves identifying new states based on combinations of NFA states and defining transitions based on the collective behavior of these states.
  - Derive a Regular Expression: After constructing the DFA, derive a regular expression that captures the language it accepts. This part tests the student's ability to abstract the deterministic transitions into a regular pattern description.

- ##### Task 2:
  - Analyze a C-program: Given a snippet of a C-program that behaves non-deterministically based on input characters, students need to deduce the regular expression representing all possible input sequences that would allow the program to reach the Halt statement. This task encourages students to think about how theoretical constructs like regular expressions can model the flow of control in programming languages.
---

## [Homework 5](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework5)

### Overview
#### Topics Covered
#### 1. Lambda-NFA (Λ-NFA) Construction:
- Students are tasked with constructing a Λ-NFA for a complex regular expression. This exercise helps understand the flexibility of NFAs, especially with lambda transitions, in accepting languages.

#### 2. Kleene’s Theorem Application:
- The homework includes a practical application of Kleene’s Theorem to derive a regular expression for a language accepted by a given deterministic finite automaton (DFA).

#### 3. Proving Non-Regular Languages:
- Students must use the Pumping Lemma to show that certain languages do not satisfy the conditions required for regular languages.

#### 4. Regular Language Analysis:
- The assignment asks students to determine whether specified languages are regular and to justify their answers, enhancing their ability to analyze and prove language properties.

#### Specific Tasks

- ##### Task 1: Construct a Λ-NFA for the language specified by the regular expression ((𝑎𝑏∗𝑎 + 𝑏𝑎)∗ + 𝑎∗𝑏)∗ and discuss its features.
- ##### Task 2: Using a given DFA, apply Kleene’s Theorem to find a regular expression that represents the language accepted by the DFA.
- ##### Task 3: Demonstrate that the language 𝐿 = {0𝑛1𝑚 : 𝑛 ≥ 1, 𝑚 ≥ 1, 𝑛 ≤ 𝑚 } is not regular.
- ##### Task 4: Prove that the language 𝐿 = {𝑥𝑥𝑅𝑥 : 𝑥 ∈ (𝑎 + 𝑏)∗} is not regular using the properties of reversal and the Pumping Lemma.
- ##### Task 5: Assess the regularity of several complex languages involving conditions on the sequences and lengths of strings and provide proofs or justifications for the regularity or non-regularity of these languages.

---

## [Homework 6](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework6)

### Overview
#### Topics Covered
#### 1. Minimization of Finite Automata:
- Students are required to reduce a given finite automaton to its minimal equivalent. This involves identifying and merging equivalent states to simplify the automaton while preserving its language.

#### 2. Algorithm for Language Difference:
- The assignment includes demonstrating an algorithm to determine if two finite automata recognize different languages. This involves understanding language differences and constructing automata to check language emptiness.

#### 3. Closure Properties of Regular Languages:
- Proving that operations like reversal (LR), prefix (Prefix(L)), and a complex operation called half (Half(L)) result in regular languages if the original language is regular.

#### Specific Tasks
- ##### Task 1: Minimize the given finite automaton by identifying and merging equivalent states to create a minimal-state automaton that accepts the same language.
- ##### Task 2: Develop an algorithm to check whether two finite automata have differing languages by constructing an automaton that represents the symmetric difference of the languages and checking for emptiness.
- ##### Task 3: Prove that the reversal of a regular language is regular, using structural induction and the properties of NFAs and DFAs.
- ##### Task 4: Prove that the prefix of a regular language is regular, showing how a modified automaton can accept all prefixes of words in the language.
- ##### Task 5: Prove that the operation Half(L), which involves splitting words into two equal parts, results in a regular language when the original language is regular. This task involves a more complex proof using the properties of NFAs and synchronized runs.
--- 

## [Homework 7](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework7)

### Overview
#### Topics Covered

#### 1. Language Description by Grammars:
- Students are tasked with describing the languages generated by specific grammars, which requires understanding the structure and rules of context-free grammars.

#### 2. Designing Context-Free Grammars:

- The homework involves creating CFGs for various languages, including regular languages and more complex ones that require careful design to ensure all constraints are met.

#### 3. Elimination of Productions:
- Exercises include the elimination of ε-productions (Λ-productions) and unit productions from CFGs, an essential skill in simplifying and standardizing grammars.

#### 4. Chomsky Normal Form (CNF) Transformation:
- The final task is to transform a given grammar into Chomsky Normal Form, which is a standardized form that facilitates parsing and theoretical analysis.

#### Specific Tasks
- ##### Task 1-3: Describe the languages generated by given CFGs. These tasks test the ability to analyze and interpret CFGs to determine the sets of strings they generate.
- ##### Task 4-8: Design CFGs for specific languages, including regular and non-regular ones. This requires understanding how to construct rules that accurately generate all and only the strings in the given languages.
- ##### Task 9: Eliminate ε-productions from a CFG, ensuring that the resulting grammar is equivalent but without nullable rules.
- ##### Task 10: Remove unit productions from a CFG, simplifying the grammar by eliminating direct substitutions that lead to inefficiencies.
- ##### Task 11: Transform a CFG into Chomsky Normal Form, where each rule is either a single terminal or two non-terminals, which aids in certain parsing algorithms.
---

## [Homework 8](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework8)

### Overview
#### Topics Covered
#### 1. Deterministic Pushdown Automata (DPDA):
- Students construct a DPDA for a specific language, focusing on designing a deterministic machine that accepts a language based on balanced symbols.

#### 2. Pushdown Automata (PDA) for Non-trivial Languages:
- Constructing a PDA for languages with more complex conditions, like balancing counts of different symbols, requires understanding of how to use stacks effectively.

#### 3. Prefix Language Acceptance:
- Building PDAs for languages that enforce conditions on prefixes, expanding the understanding of how automata can be designed to check conditions dynamically as strings are processed.

#### 4. Program Simulation Using PDAs:
- Translating a simple C-like program into a PDA, illustrating how computational processes can be modeled by automata.

#### Specific Tasks

- ##### Task 1: Construct a DPDA for the language {0𝑛 13𝑛 : 𝑛 ≥ 1 }. This involves creating a deterministic stack-based machine that handles a fixed ratio between counts of two symbols.

- ##### Task 2: Create a PDA that accepts strings where the number of '0's is greater than or equal to the number of '1's, demonstrating the ability to use a stack to count and compare symbol occurrences dynamically.

- ##### Task 3: Construct a PDA for a language where each prefix must satisfy the condition of having at least as many '0's as '1's, requiring careful design to ensure each step enforces the prefix condition.

- ##### Task 4: Describe a PDA construction that accepts the prefix of a language accepted by a given PDA, exploring how to simulate and extend automata behavior through additional guessed inputs.

- ##### Task 5: Convert a simple pseudo-C program into a PDA, illustrating how program logic and counters can be simulated using stacks and state transitions in a PDA.
---

## [Homework 9](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework9)

### Overview

---

## [Homework 10](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework10)

### Overview

---

## [Homework 11](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Homeworks/Homework11)

### Overview






