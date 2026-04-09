## CS 6795 Term-Project (Computational Model/Tool Track  )

---

## Overview

This notebook implements a computational prototype to examine how different explanation styles influence human understanding of AI-generated decisions.

The system generates two explanation formats for the same decision:
- Structured step-by-step explanation
- Concise summary explanation

The goal is to analyze how explanation structure affects cognitive processing, particularly in terms of cognitive load and mental model formation.

---

## Research Question

How do structured step-by-step explanations versus concise summary explanations affect cognitive load and mental model formation in human understanding of AI-generated decisions?

---

## Cognitive Science Foundations

This project is grounded in key cognitive science theories:

- **Mental Model Theory (Johnson-Laird)**  
  Explains how individuals construct internal representations to understand systems and reasoning processes.

- **Cognitive Load Theory (Sweller)**  
  Describes how working memory limitations affect information processing and comprehension.

- **Information Processing Theory**  
  Explains how information is encoded, structured, and integrated into understanding.

- **Explanatory Coherence (Thagard)**  
  Suggests that structured and coherent explanations improve reasoning and understanding.

---

## Implementation Summary

The prototype is implemented using a rule-based approach.

For each simulated decision scenario, the system:
1. Accepts a decision outcome and contributing factors
2. Generates:
   - A step-by-step explanation (multiple reasoning steps)
   - A summary explanation (single compressed reasoning step)
3. Computes simple quantitative indicators:
   - Word count
   - Step count
   - Information density
   - Estimated cognitive load (proxy measure)

---

## Purpose of the Notebook

This notebook demonstrates:
- The implementation of the explanation generation system
- A comparison between explanation styles
- Quantitative indicators used to approximate cognitive processing differences

The results are used to support analysis in the final report.
