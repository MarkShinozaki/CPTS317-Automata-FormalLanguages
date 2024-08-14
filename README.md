# Slides & Lecture Materials 

## [Course-Intro ](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(1)%20Course%20Intro)

### Instructor Information
- #### Name: Assefaw Gebremedhin
- #### Email: assefaw.gebremedhin@wsu.edu
- #### Webpage: www.eecs.wsu.edu/~assefaw
- #### Research Interests: Data science, graph algorithms, high-performance computing, health informatics, cybersecurity
- #### Lab: Scalable Algorithms for Data Science (SCADS)

### Course Details
- Course Management: All course activities, including lecture notes, homework, and announcements, are managed through Canvas.
- Course Objectives:
  - Introduce automata theory and computation
  - Identify different formal language classes
  - Design grammars and recognizers for languages
  - Prove theorems in automata theory
  - Determine decidability and intractability of computational problems

### Major Course Topics
#### 1. Introduction
#### 2. Regular Languages
#### 3. Context-free Languages
#### 4. Church-Turing Thesis
#### 5. Decidability
#### 6. Reducibility
#### 7. Time Complexity

---

## [Intro to Computation Theory](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(2)%20Intro%20to%20Computation%20Theory)

### [IntroToComputationTheory-part1.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(2)%20Intro%20to%20Computation%20Theory)

This document serves as an introductory guide to the theory of computation, providing an overview and a review of essential mathematical concepts required for understanding computational theory.

- **Three Central Areas of Computation Theory**:
  - **Automata**: Focuses on the definition and properties of mathematical models of computation.
  - **Computability**: Explores what problems can be solved by computers and introduces theoretical models like Turing machines.
  - **Complexity**: Discusses the difficulty levels of computational problems and their classification.

- **Mathematical Notations and Terminology**:

  - **Sets**: Definitions, subsets, union, intersection, and complements.
  - **Sequences and Tuples**: Definitions, differences from sets, and examples.
  - **Functions and Relations**: Definitions, mappings, domains, ranges, and examples.
  - **Graphs**: Basic concepts, representations, and significance in computation.
  - **Strings and Languages**: Alphabet definitions, strings, concatenation, and languages.
  - **Boolean Logic**: Logical operations like AND, OR, NOT, and their relevance in computation.

### [IntroToComputationTheory-part2.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(2)%20Intro%20to%20Computation%20Theory)

This part builds on the introductory concepts and delves deeper into mathematical notions and terminologies used in computation theory.

- **Sets and Functions**:
  
  - Further exploration of sets, sequences, tuples, and Cartesian products.
  - Detailed descriptions of functions and relations, including equivalence relations.
    
- **Graphs**:
  
  - Directed and undirected graphs, paths, cycles, and their use in data representation.
  - Historical context with the ARPANET, the precursor to the internet.
    
- **Strings and Languages**:
  
  - In-depth explanation of strings, operations like concatenation, prefixes, and languages as sets of strings.
    
- **Boolean Logic**:
  
  - Comprehensive overview of Boolean operations and logic gates.
  - Exclusive OR (XOR), equality, and implications.

### [IntroToComputationTheory-part3.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(2)%20Intro%20to%20Computation%20Theory)

This document focuses on the formal aspects of computation theory, emphasizing the role of definitions, theorems, and proofs.

- **Definitions, Theorems, and Proofs**:

  - Importance of precise definitions in mathematics.
  - Structure and significance of theorems and proofs in validating mathematical statements.

- **Proof Techniques**:

  - Proof by Construction: Demonstrating existence by constructing an example.
  - Proof by Contradiction: Establishing truth by disproving the opposite.
  - Proof by Induction: Using base cases and inductive steps to prove statements.

- **Practical Applications**:
  - Examples and exercises illustrating the application of these proof techniques in computational theory.

- **Course Summary**:
  - Overview of the course topics covered, emphasizing the importance of proofs and the foundational role of mathematical logic in computation theory.

--- 
## [Finite Automata](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(3)%20Finite%20Automata)

### [DesigningFiniteAutomata.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/DesigningFiniteAutomata.pdf)

This document focuses on the creative process involved in designing finite automata to recognize specific languages.

- **Finite Automaton Definition**: Explanation of what finite automata are and how they function as simple computational models.

- **Design Approach**: Encourages pretending to be the automaton to understand what information needs to be remembered to recognize a language.

- **Examples**:
  - Designing an automaton to recognize strings with an odd number of 1s.
  - Constructing an automaton to recognize strings containing "001" as a substring.

- **Regular Operations**: Introduction to operations like union, concatenation, and closure (Kleene star) used in manipulating regular languages.

### [DFA-RegExp-Conversion.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/DFA-RegExp-Conversion.pdf)

This document discusses the equivalence of deterministic finite automata (DFAs) and regular expressions, showing how one can be converted into the other.

- **Equivalence Theorem**: States that a language is regular if and only if some regular expression describes it.

- **Conversion Process**:
  
  - Converting DFAs to Generalized NFAs (GNFAs) and then to regular expressions.
  - Step-by-step procedure with examples.

- **GNFAs**: Explanation of how these differ from regular NFAs by allowing transitions labeled with regular expressions.

### [FiniteAutomata.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/FiniteAutomata.pdf)

This document provides an overview of finite automata, their applications, and their role in recognizing regular languages.

- **Finite Automata Basics**: Introduction to finite automata as models of computation with limited memory.

- **Applications**: Examples include controllers for automatic doors, elevators, and thermostats.

- **Formal Definition**: Mathematical description of finite automata and their language recognition capabilities.

### [NFA-DFA-Equivalence.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/NFA-DFA-Equivalence.pdf)

This document explores the equivalence between nondeterministic finite automata (NFAs) and DFAs and the closure properties of regular languages.

- **Equivalence Theorem**: Proof that every NFA has an equivalent DFA that recognizes the same language.
  
- **Conversion Process**: Detailed explanation of converting an NFA to a DFA, focusing on state transitions and subsets.

- **Closure Properties**: Regular languages are closed under union, concatenation, and star operations, demonstrated using NFAs.

### [nondetermisticFA.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/nondetermisticFA.pdf)

This document explains nondeterministic finite automata (NFAs) and their computational properties compared to DFAs.

- **Nondeterminism**: Introduction to nondeterministic computation, where multiple choices may exist for the next state.
  
- **Comparison with DFAs**: NFAs are shown to be equivalent in power to DFAs but often easier to construct for certain languages.

### [PowersetConstruction-NFA2DFA.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/PowersetConstruction-NFA2DFA.pdf)

This document details the powerset construction method for converting NFAs to DFAs.

- **Powerset Construction**: Step-by-step explanation of converting NFAs to equivalent DFAs using the powerset of states.

- **Equivalence**: Emphasizes that NFAs and DFAs recognize the same class of regular languages.

### [RegExp-NFA-Conversion.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/RegExp-NFA-Conversion.pdf)

This document describes the conversion of regular expressions to NFAs, demonstrating their equivalence.

- **Conversion Process**: Outlines the method for constructing an NFA from a given regular expression.

- **Equivalence Theorem**: States that any language described by a regular expression can be recognized by an NFA.

### [RegularExpressions.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/RegularExpressions.pdf)

This document introduces regular expressions and their use in defining patterns for regular languages.

- **Regular Expressions**: Explanation of how regular expressions are constructed using union, concatenation, and star operations.

- **Applications**: Discusses the role of regular expressions in computer science, including their use in compilers and text processing.

--- 

## [Non Regular Languages ](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(4)%20Nonregular%20Languages)

### [NonRegularLanguages-partI.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(4)%20Nonregular%20Languages/NonRegularLanguages-partI.pdf)

This document introduces the concept of non-regular languages and begins to explore their properties.

- **Nonregular Languages**: Discussion of languages that cannot be recognized by any finite automaton (DFA).
  
- **Example Language**: The document explores the language 𝐵 = {0𝑛 1𝑛 ∣ 𝑛 ≥ 0 } and explains why it is non-regular by discussing the limitations of finite automata in keeping track of an unbounded number of 0s and 1s.

- **Pumping Lemma Introduction**: Introduction to the Pumping Lemma, a crucial tool for proving that certain languages are non-regular.
  
- **Proof Techniques**: Uses examples and the pigeonhole principle to explain how finite automata's state limitations lead to non-regularity.

### [PL-exercises.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(4)%20Nonregular%20Languages/PL-exercises.pdf)

This document provides exercises focused on applying the Pumping Lemma to prove the non-regularity of specific languages.

- **How to Apply the Pumping Lemma**: Step-by-step guide on using the Pumping Lemma to prove that a language is non-regular.

- **Exercises**: Includes multiple exercises where the Pumping Lemma is applied to demonstrate the non-regularity of various languages, such as:
  - 𝐸 = { 0𝑖1𝑗 ∣ 𝑖 > 𝑗}
  - 𝐹 = {0𝑛 1𝑚 0𝑛 ∣ 𝑚, 𝑛 ≥ 0}
  - 𝐺 = {0𝑚 1𝑛 ∣ 𝑚 ≠ 𝑛}

- **Proof Strategies**: Discusses different strategies for finding contradictions when assuming a language is regular.

### [PumpingLemma.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(4)%20Nonregular%20Languages/PumpingLemma.pdf)

This document provides a detailed exploration of the Pumping Lemma and how it is used to demonstrate that certain languages are not regular.

- **Pumping Lemma Explanation**: Provides a formal definition of the Pumping Lemma for regular languages and explains its conditions.

- **Application of the Lemma**: Details how to apply the Pumping Lemma to prove the non-regularity of languages by assuming regularity and finding contradictions.

- **Examples**:
  - Proving the non-regularity of 𝐵={0^𝑛 1^𝑛 ∣ 𝑛 ≥ 0}
  - Proving the non-regularity of 𝐶 = {𝑤 ∣ 𝑤 has an equal number of 0s and 1s }
  - Analyzing the non-regularity of other languages using specific examples.

--- 

## [Context Free Languages](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(5)%20Context-free%20Languages)


### [CFG-PDA-conversion.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/CFG-PDA-conversion.pdf)

This document discusses the equivalence between context-free grammars (CFGs) and pushdown automata (PDAs), specifically focusing on the conversion process from a CFG to a PDA.

- **CFG to PDA Conversion**: Explains the method of converting a CFG into an equivalent PDA that recognizes the same language.

- **Step-by-Step Conversion**: Details the process of designing a PDA that can simulate the derivations of a CFG by using non-deterministic choices to select production rules.

### [ChomskyNormalForm.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/ChomskyNormalForm.pdf)

This document introduces the Chomsky Normal Form (CNF) for context-free grammars.

- **CNF Overview**: Describes the properties of Chomsky Normal Form, a specific format for CFGs where each production rule is restricted to a specific form.

- **Conversion Process**: Details the procedure for converting any CFG into CNF, including the removal of epsilon rules, unit rules, and 
simplifying productions to fit the CNF format.

### [context-free-grammars.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/context-free-grammars.pdf)

This document introduces context-free grammars and their applications.

- **Introduction to CFGs**: Explains the basic structure of CFGs, including variables, terminals, and production rules.

- **Applications of CFGs**: Discusses the use of CFGs in areas such as compilers and human language processing.

### [Converting_Context_Free_Grammars_to_CNF.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/Converting_Context_Free_Grammars_to_CNF.pdf)

This document provides a detailed guide on converting context-free grammars (CFGs) to Chomsky Normal Form (CNF).

- **Conversion Process**: Offers a step-by-step explanation of converting CFGs to CNF, highlighting why each transformation is made and how it preserves the language generated by the grammar.

- **Invalid Rules in CNF**: Discusses the types of rules that are not allowed in CNF and how to address them during the conversion.

### [DCFL+Review.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/DCFL%2BReview.pdf)

This document reviews Deterministic Context-Free Languages (DCFLs) and related concepts.

- **Introduction to DCFLs**: Defines DCFLs and explores their properties.

- **Comparison with Non-Deterministic CFLs**: Discusses the differences between deterministic and non-deterministic context-free languages.


### [designingCFGs.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/designingCFGs.pdf)

This document provides strategies for designing context-free grammars (CFGs).

- **Techniques for Designing CFGs**: Offers various techniques to construct CFGs, including breaking down complex languages into simpler components and handling recursive structures.

- **Ambiguity in CFGs**: Discusses the concept of ambiguity in CFGs and how it can be identified and addressed.

### [PDA-to-CFG-conversion.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/PDA-to-CFG-conversion.pdf)

This document covers the process of converting pushdown automata (PDAs) into context-free grammars (CFGs).

- **PDA to CFG Conversion**: Explains how to construct a CFG that generates the same language as a given PDA.

- **Conversion Strategy**: Provides a detailed strategy for designing a CFG based on the transitions and stack operations of a PDA.

### [pushDownAutomata-Examples.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/pushDownAutomata-Examples.pdf)

This document provides examples of pushdown automata (PDAs) and their application in recognizing context-free languages.

- **Introduction to PDAs**: Recaps the basic structure and function of PDAs, highlighting their ability to recognize context-free languages.

- **Examples of PDAs**: Offers detailed examples of PDAs designed to recognize specific languages, including languages like 𝐵 = {0^𝑛 1^𝑛 ∣ 𝑛 ≥ 0} and palindromes.

- **PDA Design**: Guides the reader through the process of designing PDAs for various languages, including both the formal definition and shorthand notation for transitions.

### [pushDownAutomata.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(5)%20Context-free%20Languages/pushDownAutomata.pdf)

This document introduces pushdown automata (PDAs) and their role in recognizing context-free languages.

- **Introduction to PDAs**: Describes how PDAs extend finite automata with a stack, allowing them to recognize a broader class of languages.

- **Comparison with NFAs**: Discusses the differences between NFAs and PDAs, emphasizing the additional power provided by the stack.

--- 

## [Equivalence of Automata](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(6)%20Equivalence%20of%20Automata)

### [DFA-equivalence.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(6)%20Equivalence%20of%20Automata/DFA-equivalence.pdf)

- **Equivalence of DFAs**: Discusses how to determine whether two DFAs are equivalent, meaning they recognize the same language.

- **Minimization of DFAs**: Explains the process of minimizing a DFA by removing unreachable states and combining equivalent states to produce the smallest possible DFA.

- **Table Filling Algorithm**: Provides a step-by-step guide to the table filling algorithm, which is used to identify equivalent states within a DFA. The document details how to fill the table by comparing states and their transitions, eventually leading to the identification of equivalent states.

- **Special Cases**: Discusses special cases in DFA minimization, such as handling multiple final states and how to treat them during the minimization process.

- **Applications**: The concepts are illustrated through examples and applications, such as comparing two DFAs to determine if they are equivalent by constructing a unified DFA and applying the table filling algorithm.


---

## [Turning Machines](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(7)%20Turing%20Machines)

### [TuringMachines.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(7)%20Turing%20Machines/TuringMachines.pdf)

This document provides an introduction to Turing Machines as part of the broader topics in automata theory, computability theory, and complexity theory.

- **Introduction to Turing Machine**s: Discusses the foundational aspects of Turing Machines (TMs), a more powerful computational model compared to finite automata and pushdown automata.

- **Structure of Turing Machines**: Explains the components of a TM, including the infinite tape, tape head, and transition function.

- **Differences from Finite Automata**: Highlights how TMs differ from finite automata, particularly their ability to both read and write on the tape, move in both directions, and operate with an infinite tape.

- **Definition**: Introduces the formal definition of a TM, including the transition function and the concept of configurations.

### [TuringMachinesII.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(7)%20Turing%20Machines/TuringMachinesII.pdf)

This document is the second part in the series on Turing Machines, building on the concepts introduced in the first document.

- **Formal Definition Recap**: Revisits the formal definition of a TM and how it computes.

- **Turing Recognizable and Decidable Languages**: Discusses the distinction between Turing-recognizable (recursively enumerable) languages and Turing-decidable (recursive) languages.

- **State Diagrams**: Includes state diagrams for the TMs discussed, helping to visualize their operation.

### [TuringMachinesIII.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(7)%20Turing%20Machines/TuringMachinesIII.pdf)

This document, part three in the series, explores variants of Turing Machines and their robustness.

- **Variants of Turing Machines**: Discusses different types of TMs, including multitape TMs, nondeterministic TMs, and enumerators, and how they compare to standard TMs.

- **Simulation of Multitape TMs**: Explains how a single-tape TM can simulate a multitape TM by using a special delimiter to separate the contents of different tapes.

- **Nondeterministic TMs**: Describes how nondeterministic TMs work, where the machine can follow multiple computational paths simultaneously, and their equivalence to deterministic TMs.

- **Enumerators**: Introduces enumerators, a variant of TMs that can list all strings in a language, and discusses their equivalence to Turing-recognizable languages.

### [TuringMachinesIV.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(7)%20Turing%20Machines/TuringMachinesIV.pdf)

This document, the fourth part in the series, focuses on the definition of algorithms through the lens of Turing Machines and their equivalence to other computational models.

- **Definition of Algorithm**: Discusses the historical development of the concept of an algorithm, leading to the formal definition through the Church-Turing thesis, which equates the intuitive notion of algorithms with Turing machine algorithms.

- **Hilbert's Problems**: Explores one of Hilbert's famous problems related to algorithms and decidability, demonstrating the limitations of algorithms and their formalization.

- **Equivalence with Other Models**: Describes how various computational models with unrestricted memory access are equivalent in power to TMs, emphasizing the profound implications for the definition of algorithms.

- **High-Level TM Examples**: Provides examples of how TMs can be described at a high level, focusing on conceptual steps rather than detailed state transitions.

--- 

## [Decidability](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(8)%20Decidability)

### [decidability.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(8)%20Decidability/decidability.pdf)

This document introduces the concept of decidability in the context of automata theory, computability theory, and complexity theory.

- **Decidability**: Explores the limits of algorithmic solvability, discussing problems that can and cannot be solved algorithmically.

- **Decidable Languages**: Introduces decidable languages concerning finite automata and context-free grammars, including acceptance, emptiness, and equivalence problems.

- **Theorems and Proofs**: Provides theorems related to the decidability of specific problems, such as whether a DFA or NFA accepts a given string, whether a regular expression generates a particular string, and whether the language of a DFA is empty.


### [decidabilityII-JH.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(8)%20Decidability/decidabilityII-JH.pdf)

This document continues the discussion on decidability, focusing on context-free grammars (CFGs) and languages.

- **Decidable Problems in CFGs**: Covers the decidability of problems related to CFGs, such as generation, emptiness, and equivalence.

- **Chomsky Normal Form (CNF)**: Discusses the conversion of CFGs into CNF as part of proving that certain problems related to CFGs are decidable.

- **Pushdown Automata (PDA)**: Explains how PDAs are related to CFGs and how decidability results for CFGs apply to PDAs.

- **Undecidable Problems**: Introduces the concept of undecidability in the context of CFGs, leading into discussions about more complex languages.

### [undecidability.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(8)%20Decidability/undecidability.pdf)

This document shifts the focus to undecidability, presenting key theorems and proofs in the theory of computation.

- **Undecidability**: Introduces the concept that some problems are algorithmically unsolvable, meaning no Turing Machine can decide them.

- **ATM Problem**: Discusses the acceptance problem for TMs (ATM) and proves its undecidability using diagonalization.

- **Cantor's Diagonalization**: Explains the diagonalization method used by Georg Cantor to show that certain sets, like the set of real numbers, are uncountable and applies this technique to prove undecidability in computation.

- **Universal Turing Machine**: Describes the Universal Turing Machine, which can simulate any other TM, and how this leads to the proof that ATM is undecidable.

### [undecidabilityII.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(8)%20Decidability/undecidabilityII.pdf)

This document continues the exploration of undecidability and its implications in computation theory.

- **Uncountable Languages**: Explains why some languages are not Turing-recognizable due to the uncountability of the set of all languages versus the countability of TMs.

- **Proof of ATM's Undecidability**: Provides a detailed proof that ATM is undecidable by constructing a TM that leads to a contradiction when attempting to decide ATM.

- **Co-Turing-Recognizable Languages**: Introduces the concept of co-Turing-recognizable languages and proves that a language is decidable if and only if both it and its complement are Turing-recognizable.

--- 

## [Reducibility](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(8)%20Decidability)


### [reducibility-part1.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(9)%20Reducibility/reducibility-part1.pdf)

This document introduces the concept of reducibility in computability theory, focusing on how it can be used to demonstrate that certain problems are undecidable.

- **Reducibility**: The process of converting one problem (A) into another problem (B) such that solving B would provide a solution to A. This concept is crucial for classifying problems by their decidability and complexity.

- **Undecidable Problems**: The document discusses several undecidable problems, including the Halting Problem (HALTTM), the Emptiness Problem for TMs (ETM), and the Regular Language Problem for TMs (REGULARTM).

- **Proof Techniques**: Explains how to use reducibility to prove that certain problems are undecidable by showing that if a solution to one undecidable problem existed, it could solve another undecidable problem, leading to a contradiction.

### [reducibility-part2.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(9)%20Reducibility/reducibility-part2.pdf)

This document continues the discussion on reducibility, focusing on additional undecidable problems and further refining the concept.

- **Further Examples of Undecidable Problems**: Introduces the EQTM problem (whether two TMs recognize the same language) and demonstrates its undecidability using reducibility.

- **Computation Histories**: Introduces the concept of computation histories, a technique used to track the sequence of configurations in a TM, which can be employed in proofs involving reducibility.

- **Linear Bounded Automata (LBA)**: Begins the discussion on LBAs, a restricted form of TMs with bounded memory, and their relation to undecidability.

### [reducibility-part3.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(9)%20Reducibility/reducibility-part3.pdf)

This document concludes the discussion on reducibility and introduces more advanced topics such as mapping reducibility.

- **Linearly Bounded Automata (LBA)**: Continues the discussion on LBAs, including their properties and how they relate to decidability.

- **Mapping Reducibility**: Formalizes the concept of reducibility by introducing mapping reducibility, a method used to show that certain languages are not Turing-recognizable.

- **Applications of Mapping Reducibility**: Explores how mapping reducibility can be applied to both decidable and undecidable problems, providing a framework for proving non-recognizability.


--- 

## [Time Complexity](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(8)%20Decidability)


### [timeComplexity.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(10)%20Time%20Complexity/timeComplexity.pdf)

- **Time Complexity Overview**: Provides an introduction to measuring the time complexity of algorithms and classifying problems according to the time required to solve them.

- **Asymptotic Analysis**: Discusses Big-O notation and its use in analyzing the time complexity of algorithms.

- **Classifying Languages by Time Requirements**: Explores how languages can be classified based on the time complexity of the algorithms that decide them, comparing single-tape and multi-tape Turing machines.

- **Complexity Theory vs. Computability Theory**: Highlights the differences between complexity theory, which focuses on resource usage, and computability theory, which focuses on the ability to solve problems.

### [timecomplexity-part2.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(10)%20Time%20Complexity/timecomplexity-part2.pdf)

- **Complexity Classes**: Introduces and defines important complexity classes such as P (polynomial time) and NP (nondeterministic polynomial time).

- **Single-Tape vs. Multi-Tape Turing Machines**: Discusses the simulation of multi-tape Turing machines by single-tape machines and the impact on time complexity.

- **Deterministic vs. Nondeterministic Turing Machines**: Explores the relationship between deterministic and nondeterministic Turing machines, including the simulation of the latter by the former and the resulting impact on time complexity.

- **Polynomial Time**: Explains why polynomial time is considered a reasonable boundary for tractable problems and the significance of the separation between polynomial and exponential time.

- **The Class P**: Defines the class P, providing examples of problems in P and discussing why they are considered efficiently solvable.

- **The Class NP**: Introduces the class NP and discusses the P vs NP problem, one of the most significant open questions in theoretical computer science

---

## [review.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/tree/Slides-Lectures/(11)%20Course%20Wrap-up)


- **Why Study Theory of Computation?**: Discusses the relevance and importance of computation theory in practical applications, personal intellectual growth, and the broader field of computer science.

- **Three Central Areas of Computation Theory**: Summarizes the focus areas of automata theory, computability theory, and complexity theory, and how they are interconnected by the fundamental question of what computers can and cannot do.

- **Complexity Theory**: Provides an overview of complexity theory, including the classification of computational problems according to their difficulty, practical utility, and the significance of the P vs. NP problem.

- **Computability Theory**: Discusses the work of Gödel, Turing, and Church in discovering that some problems are unsolvable by computers, leading to the development of theoretical models of computation.

- **Automata Theory**: Covers the definitions and properties of mathematical models of computation, such as finite automata and context-free grammars, and their applications in areas like text processing and programming languages.

- **Topics Covered in the Course**: Outlines the three major parts of the course:

  - **Part One**: Automata and Languages: Regular languages, context-free languages, and related models like finite automata and pushdown automata.

  - **Part Two**: Computability Theory: Turing machines, decidability, and undecidability.
    
  - **Part Three**: Complexity Theory: Time complexity, Big-O notation, and the classes P and NP.












