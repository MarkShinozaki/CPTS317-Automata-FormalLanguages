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

- **Examples**: Several finite automata are provided, illustrating their structure and behavior on input strings.

### [NFA-DFA-Equivalence.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/NFA-DFA-Equivalence.pdf)

This document explores the equivalence between nondeterministic finite automata (NFAs) and DFAs and the closure properties of regular languages.

- **Equivalence Theorem**: Proof that every NFA has an equivalent DFA that recognizes the same language.
  
- **Conversion Process**: Detailed explanation of converting an NFA to a DFA, focusing on state transitions and subsets.

- **Closure Properties**: Regular languages are closed under union, concatenation, and star operations, demonstrated using NFAs.

### [nondetermisticFA.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/nondetermisticFA.pdf)

This document explains nondeterministic finite automata (NFAs) and their computational properties compared to DFAs.

- **Nondeterminism**: Introduction to nondeterministic computation, where multiple choices may exist for the next state.
  
- **Comparison with DFAs**: NFAs are shown to be equivalent in power to DFAs but often easier to construct for certain languages.
  
- **Examples**: Illustrations of NFAs recognizing languages based on patterns and specific conditions.

### [PowersetConstruction-NFA2DFA.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/PowersetConstruction-NFA2DFA.pdf)

This document details the powerset construction method for converting NFAs to DFAs.

- **Powerset Construction**: Step-by-step explanation of converting NFAs to equivalent DFAs using the powerset of states.

- **Example**: A visual example demonstrates the conversion process, illustrating state transitions and acceptance conditions.

- **Equivalence**: Emphasizes that NFAs and DFAs recognize the same class of regular languages.

### [RegExp-NFA-Conversion.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/RegExp-NFA-Conversion.pdf)

This document describes the conversion of regular expressions to NFAs, demonstrating their equivalence.

- **Conversion Process**: Outlines the method for constructing an NFA from a given regular expression.

- **Examples**: Several examples are provided, illustrating how different regular expressions are translated into NFAs.

- **Equivalence Theorem**: States that any language described by a regular expression can be recognized by an NFA.

### [RegularExpressions.pdf](https://github.com/MarkShinozaki/CPTS317-Automata-FormalLanguages/blob/Slides-Lectures/(3)%20Finite%20Automata/RegularExpressions.pdf)

This document introduces regular expressions and their use in defining patterns for regular languages.

- **Regular Expressions**: Explanation of how regular expressions are constructed using union, concatenation, and star operations.

- **Examples**: Illustrative examples showing how regular expressions define languages with specific properties.

- **Applications**: Discusses the role of regular expressions in computer science, including their use in compilers and text processing.

--- 







