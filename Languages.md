---
Backlink: "[[Index]]"
Title: Languages
---
## Language and its types
In theory of computation, "language" refers to a set of string of sequences of symbols generated by an [[#^ea5513| Alphabet]]. A language can be finite or infinite, depending on whether it contains a finite or infinite number of string.

**Alphabet** is a finite set of symbols.  ^ea5513

Languages can be one of various types
1. **[[Regular Languages]]**
   These are described by regular expressions and can be recognised by finite automata. They are the simplest type of formal language and have application in lexical analysis, string matching and more.
   
2. **[[Context-Free Languages]]**
   These languages are generated by context-free grammars and are recognised by pushdown automata. They are used in syntax analysis phase of compilers and for describing the structure of programming languages.
   
3. **Context-Sensitive Languages**
   These are more powerful than context-free languages and are described by context sensitive grammar. They find applications in natural language processing and other areas requiring more complex language structure.
   
4. **Recursively Enumerable Languages**
   These languages are recognised by [[Turing Machines]]. They include all the languages that can be accepted by algorithms that may not halt on certain inputs.


## Operations on language
There are several fundamental operations that can be performed on languages. These operations help in manipulating, combining, or transforming languages to derive new languages. Here are some basic operations on languages : 
1. **Union (L1 ∪ L2):**
   The union of two languages L1 and L2 is a new language containing all the string that belong to either L1 or L2, or both. Formally, for languages L1 and L2 the union is represented as L1​∪L2​={x:x∈L1​ or x∈L2​}

2. **Concatenation (L1 ⋅ L2)**
   The concatenation of two languages L1 and L2 involves combining every string in L1 with every string in L2 in all possible ways. Formally, for languages L1 and L2, the concatenation is represented as L1​⋅L2​={xy:x∈L1​ and y∈L2​}

3. **Kleene Star (L\*)**
   The Kleene star operation applied to a language LL generates a new language containing all possible concatenations of zero or more strings from LL. Formally, for a language LL, the Kleene star is represented as L∗={x1,x2,...,xn : n≥0 , and xi∈L for 1≤i≤n}L∗={x1​x2​…xn​:n≥0, and xi​∈L for 1≤i≤n}