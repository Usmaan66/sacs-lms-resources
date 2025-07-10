# Chapter 1

## SETS

### 1.1 Introduction

* The concept of **set** is fundamental in modern mathematics.
* Sets are used across almost all branches of mathematics, including defining **relations** and **functions**, and in the study of **geometry**, **sequences**, and **probability**.
* The theory of sets was developed by the German mathematician **Georg Cantor** (1845-1918). He encountered sets while working on problems related to "trigonometric series".

**Key Takeaways:** Sets are a basic building block in mathematics, crucial for understanding many other mathematical concepts.

### 1.2 Sets and their Representations

* A **set** is defined as a **well-defined collection of objects**.
    * **Well-defined** means that for any given object, we can clearly decide whether it belongs to the collection or not.
    * **Example of a well-defined collection**: "Odd natural numbers less than 10" (1, 3, 5, 7, 9). You can definitively say if a number belongs or not.
    * **Example of a collection that is NOT well-defined**: "The collection of ten most talented writers of India," because "most talented" is subjective and can vary from person to person.
* **Objects**, **elements**, and **members** are all synonymous terms when referring to the components of a set.
* Sets are typically denoted by **capital letters** (e.g., A, B, C, X, Y, Z).
* The elements of a set are usually represented by **small letters** (e.g., a, b, c, x, y, z).
* If 'a' is an element of set A, we write $a \in A$. The symbol $\in$ (epsilon) means "belongs to".
* If 'b' is not an element of set A, we write $b \notin A$. This means "b does not belong to A".
    * **Example**: For the set V of vowels {a, e, i, o, u}, $a \in V$ but $b \notin V$.

#### Special Sets in Mathematics

* **N**: The set of all **natural numbers** (positive integers: 1, 2, 3, ...).
* **Z**: The set of all **integers** (..., -2, -1, 0, 1, 2, ...).
* **Q**: The set of all **rational numbers** (numbers that can be expressed as a fraction $p/q$, where $p, q \in Z$ and $q \ne 0$).
* **R**: The set of **real numbers**.
* **$Z^{+}$**: The set of **positive integers**.
* **$Q^{+}$**: The set of **positive rational numbers**.
* **$R^{+}$**: The set of **positive real numbers**.

#### Methods of Representing a Set

There are two main methods to represent a set:

1.  **Roster or Tabular Form**
    * In this form, all elements of the set are listed.
    * Elements are separated by commas and enclosed within curly braces `{}`.
    * **Example**: The set of all even positive integers less than 7 is $\{2, 4, 6\}$.
    * **Order does not matter**: The order in which elements are listed is not important. $\{1, 2, 3\}$ is the same as $\{3, 1, 2\}$.
    * **No repetition**: Elements are generally not repeated. Each element is considered distinct. For example, the letters in the word 'SCHOOL' are represented as $\{S, C, H, O, L\}$.
    * **Ellipsis (...)**: For sets with many elements or infinite sets, three dots (...) are used to indicate that the pattern continues.
        * **Example**: The set of odd natural numbers is $\{1, 3, 5, ...\}$.

2.  **Set-builder Form**
    * In this form, a set is described by a common property that all its elements possess, and no element outside the set has this property.
    * It uses a symbol (like 'x', 'y', or 'z') to represent any element, followed by a colon `:` (read as "such that"). After the colon, the characteristic property of the elements is written. The entire description is enclosed in braces `{}`.
    * **Format**: $\{x : \text{property of x}\}$
    * **Example**: The set of all vowels in the English alphabet, denoted by V, is written as $V = \{x : x \text{ is a vowel in English alphabet}\}$.
    * **Example**: The set A containing natural numbers between 3 and 10 (excluding 3 and 10) is written as $A = \{x : x \text{ is a natural number and } 3 < x < 10\}$. This set in roster form is $\{4, 5, 6, 7, 8, 9\}$.

**Key Takeaways:** Sets are well-defined collections. They can be represented by listing all elements (roster form) or by describing a common property (set-builder form). Symbols like $\in$ and $\notin$ show membership.

### 1.3 The Empty Set

* **Definition**: An **empty set**, also called a **null set** or **void set**, is a set that does not contain any elements.
* **Notation**: The empty set is denoted by the symbol $\phi$ or by empty curly braces `{}`.
* **Examples**:
    * $A = \{x : 1 < x < 2, \text{ x is a natural number}\}$ is an empty set because there are no natural numbers between 1 and 2.
    * $B = \{x : x^2 - 2 = 0 \text{ and x is rational number}\}$ is an empty set because the equation $x^2 - 2 = 0$ (meaning $x = \pm \sqrt{2}$) has no rational solutions.
    * $C = \{x : x \text{ is an even prime number greater than 2}\}$ is an empty set because 2 is the only even prime number.
    * $D = \{x : x^2 = 4, \text{ x is odd}\}$ is an empty set because the solutions for $x^2 = 4$ are $x = \pm 2$, which are not odd numbers.

**Key Takeaways:** An empty set contains no elements and is denoted by $\phi$ or {}. It represents impossible collections.

### 1.4 Finite and Infinite Sets

* **Definition**:
    * A set is called a **finite set** if it is either an empty set or consists of a definite (countable) number of elements.
    * Otherwise, the set is called an **infinite set**.
* The **number of elements** in a set S is denoted by $n(S)$. If $n(S)$ is a natural number, then S is a non-empty finite set.
* **Examples of Finite Sets**:
    * $A = \{1, 2, 3, 4, 5\}$, here $n(A) = 5$.
    * $B = \{a, b, c, d, e, g\}$, here $n(B) = 6$.
    * The set of days of the week is a finite set.
    * The set of solutions to $x^2 - 16 = 0$ is $\{4, -4\}$, which is finite.
* **Examples of Infinite Sets**:
    * The set of natural numbers $\{1, 2, 3, ...\}$ is infinite because there is an endless count of natural numbers.
    * The set of points on a line is an infinite set.
    * Sets like $\{1, 3, 5, 7, ...\}$ (odd natural numbers) and $\{..., -3, -2, -1, 0, 1, 2, 3, ...\}$ (integers) are infinite.
* **Representation of Infinite Sets in Roster Form**: It's not possible to list all elements of an infinite set. We use a few elements to indicate the pattern, followed by three dots (...).
* **Limitation**: Not all infinite sets can be described in roster form. For example, the set of real numbers cannot be listed as its elements do not follow a specific pattern.

**Key Takeaways:** Sets are either finite (countable elements, including empty) or infinite (uncountable elements). Infinite sets are often represented with "..." in roster form.

### 1.5 Equal Sets

* **Definition**: Two sets, A and B, are considered **equal** (written as $A = B$) if and only if they have exactly the same elements. This means every element of A is also an element of B, and every element of B is also an element of A.
* If sets A and B do not have the same elements, they are **unequal** (written as $A \ne B$).
* **Important Note**: The repetition of elements within a set does not change the set itself.
    * **Example**: If $A = \{1, 2, 3\}$ and $B = \{2, 2, 1, 3, 3\}$, then $A = B$ because both sets contain the same distinct elements {1, 2, 3}.
    * Due to this, elements are generally not repeated when describing a set.
* **Examples**:
    * If $A = \{1, 2, 3, 4\}$ and $B = \{3, 1, 4, 2\}$, then $A = B$.
    * Let A be the set of prime numbers less than 6 ($A = \{2, 3, 5\}$). Let P be the set of prime factors of 30 ($P = \{2, 3, 5\}$). Then $A = P$.

**Key Takeaways:** Two sets are equal if they contain precisely the same elements, regardless of order or repetition.

### 1.6 Subsets

* **Definition**: A set A is said to be a **subset** of a set B (denoted as $A \subset B$) if every element of set A is also an element of set B.
    * This can be written using the implication symbol $\Rightarrow$: $A \subset B \text{ if } a \in A \Rightarrow a \in B$.
* If A is not a subset of B, we write $A \not\subset B$.
* **Properties of Subsets**:
    * Every set is a subset of itself: $A \subset A$.
    * The empty set ($\phi$) is a subset of every set: $\phi \subset A$.
* **Relationship between Subsets and Equal Sets**: If $A \subset B$ and $B \subset A$, then $A = B$. This is a two-way implication, often read as "if and only if" (iff).
* **Proper Subset and Superset**:
    * If $A \subset B$ and $A \ne B$, then A is called a **proper subset** of B.
    * In this case, B is called the **superset** of A.
    * **Example**: $A = \{1, 2, 3\}$ is a proper subset of $B = \{1, 2, 3, 4\}$.
* A set with only one element is called a **singleton set**. For example, $\{a\}$ is a singleton set.

**Examples**:
* The set Q of rational numbers is a subset of the set R of real numbers, so $Q \subset R$.
* If A is the set of all divisors of 56 and B is the set of all prime divisors of 56, then $B \subset A$.
* If $A = \{a, e, i, o, u\}$ and $B = \{a, b, c, d\}$, then A is not a subset of B (because $e \in A$ but $e \notin B$), and B is not a subset of A (because $b \in B$ but $b \notin A$).

**Key Takeaways:** A set A is a subset of B if all elements of A are also in B. Every set is a subset of itself, and the empty set is a subset of all sets.

### 1.6.1 Subsets of set of real numbers

* Many important sets of numbers are subsets of the set of real numbers (R).
* **Natural Numbers (N)**: $N = \{1, 2, 3, 4, 5, ...\}$
* **Integers (Z)**: $Z = \{..., -3, -2, -1, 0, 1, 2, 3, ...\}$
* **Rational Numbers (Q)**: $Q = \{x : x = \frac{p}{q}, \text{ p, } q \in Z \text{ and } q \ne 0\}$.
    * Examples include $-5$ (which is $\frac{-5}{1}$), $\frac{5}{7}$, $\frac{2}{13}$.
* **Irrational Numbers (T)**: $T = \{x : x \in R \text{ and } x \notin Q\}$. These are real numbers that cannot be expressed as a fraction of two integers.
    * Examples include $\sqrt{2}$, $\sqrt{5}$, and $\pi$.

* **Relationships between these subsets**:
    * $N \subset Z \subset Q$
    * $Q \subset R$
    * $T \subset R$
    * $N \not\subset T$ (Natural numbers are not irrational numbers)

**Key Takeaways:** Important number sets like natural, integers, rational, and irrational numbers are all subsets of real numbers, each with specific properties.

### 1.6.2 Intervals as subsets of R

* Intervals are special subsets of real numbers. Let $a, b \in R$ and $a < b$.
* **Open Interval**: Denoted by $(a, b)$.
    * Definition: $\{y : a < y < b\}$.
    * This interval includes all real numbers between 'a' and 'b', but **does not include** the endpoints 'a' and 'b'.
* **Closed Interval**: Denoted by $[a, b]$.
    * Definition: $\{x : a \le x \le b\}$.
    * This interval includes all real numbers between 'a' and 'b', **including** the endpoints 'a' and 'b'.
* **Semi-Open/Semi-Closed Intervals**:
    * $[a, b)$: Open from 'a' to 'b', including 'a' but excluding 'b'.
        * Definition: $\{x : a \le x < b\}$.
    * $(a, b]$: Open from 'a' to 'b', including 'b' but excluding 'a'.
        * Definition: $\{x : a < x \le b\}$.
* **Infinite Intervals**:
    * $[0, \infty)$: Represents the set of all **non-negative real numbers**.
    * $(-\infty, 0)$: Represents the set of all **negative real numbers**.
    * $(-\infty, \infty)$: Represents the entire set of **real numbers**.
* An interval contains **infinitely many points**.
* **Length of an interval**: For any interval $(a, b)$, $[a, b]$, $[a, b)$, or $(a, b]$, the length is given by $(b - a)$.

**Examples of Interval and Set-Builder Form Conversion**:
* The set $\{x : x \in R, -5 < x \le 7\}$ can be written as the interval $(-5, 7]$.
* The interval $[-3, 5)$ can be written in set-builder form as $\{x : -3 \le x < 5\}$.

**Key Takeaways:** Intervals are continuous subsets of real numbers, defined by their endpoints and whether these endpoints are included (closed, using `[]`) or excluded (open, using `()`).

### 1.7 Universal Set

* **Definition**: In a specific context, the **universal set** (usually denoted by **U**) is the basic set that contains all elements relevant to that particular discussion. All other sets in that context are considered subsets of the universal set.
* Subsets of the universal set are typically denoted by capital letters like A, B, C.
* **Examples**:
    * When studying number systems, the set of rational numbers (Q) or the set of real numbers (R) could be considered a universal set for the set of all integers (Z) or the set of prime numbers.
    * In human population studies, the set of all people in the world would be the universal set.

**Key Takeaways:** The universal set (U) is the overarching set containing all possible elements related to a specific problem or discussion.

### 1.8 Venn Diagrams

* **Introduction**: **Venn diagrams** are graphical representations used to show the relationships between sets.
* **Origin**: They are named after the English logician **John Venn** (1834-1883).
* **Components**:
    * The **universal set (U)** is usually represented by a **rectangle**.
    * **Subsets** of the universal set are represented by **closed curves**, typically **circles**, drawn within the rectangle.
    * The elements of the sets are written within their respective circles.

**Key Takeaways:** Venn diagrams provide a visual way to understand set relationships, using rectangles for the universal set and circles for subsets.