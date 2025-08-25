# Birch and Swinnerton–Dyer Conjecture Proof  
Author: Matthew Wheelhouse

## Overview

The Birch and Swinnerton–Dyer (BSD) Conjecture is one of the most important open problems in number theory and mathematics. It relates the arithmetic of an elliptic curve—a geometric object defined by cubic equations—to the behavior of a complex analytic function called the Hasse–Weil L-function associated with the curve.

This repository contains my full, rigorous, and line-by-line proof of the Birch and Swinnerton–Dyer Conjecture, which is a Clay Mathematics Institute Millennium Prize Problem carrying a $1 million reward for a valid solution.

---

## What is the Birch and Swinnerton–Dyer Conjecture?

The BSD Conjecture states that the rank of the group of rational points on an elliptic curve \( E \), which measures how many “independent” solutions with rational coordinates exist, is equal to the order of vanishing (the multiplicity of zero) of the Hasse–Weil L-function \( L(E, s) \) at the special point \( s = 1 \).

Formally:
\[
\text{rank}(E(\mathbb{Q})) = \text{ord}_{s=1}(L(E, s)).
\]

---

## Compilation Instructions

To compile the LaTeX source into a PDF, run these commands in your terminal or command prompt inside the repository folder:

pdflatex BSD_Proof_MatthewWheelhouse.tex
bibtex BSD_Proof_MatthewWheelhouse
pdflatex BSD_Proof_MatthewWheelhouse.tex
pdflatex BSD_Proof_MatthewWheelhouse.tex

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.
