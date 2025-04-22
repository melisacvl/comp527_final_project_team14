# COMP 527 Final Project 
# Team 14: Tortoise and the Achilles
## Studying the extension of ordinary logic with natural numbers and recursion over natural numbers


Gödel's System T is an extension of the Natural Deduction Calculus (ND) which introduces the natural numbers as a connective. System T also introduces a recursion scheme called Primitive Recursion over the natural numbers. Gödel's work took place in the mid 20th century when mathematicians were attempting to fit mathematics into a formal logical framework, one example of which is Dedekind-Peano arithmetic [1]. System T integrates the axioms laid out by Dedekind & Peano with ND. 

Although System T was first introduced in 1958 [2], the logic has maintained relevance. For example, it was recently mechanized in Agda [3], and is often used as a jumping-off point for modern works (as seen in [4]). System T has many properties of note; studied here are the Weak Normalization, as well as the ability to encode typical arithmetic operations via primitive recursion. Weak normalization says that every proof either steps, or reaches a normal form [5]. One can also prove strong normalization, which says that every proof reaches a normal form [4], but that was not feasible given the time constraints of this project. The relevance of these properties are further explored in the formalization section. Finally, it seemed natural to include a mechanization of System T in Beluga; proof mechanization and the Curry-Howard correspondence have been central themes of this course, and the mechanization of System T in Agda motivates a similar mechanization in Beluga. 

## Description of deliverables
- The Beluga file titled system_T.bel is our Beluga Mechanization.
- The PDF titled Formalization and WN is our on-paper formalization of System T and our Weak Normalization proof.
- The PDF titled COMP 527 Consent To Post on Ed includes our consent to post as well as each members contributions to the project.
- The PDF titled Formalization and Mechanization of Gödel’s System T is our 2-page abstract.
- Finally, the link to our video: 


### References:

[1] nLab authors. Peano arithmetic. https://ncatlab.org/nlab/show/Peano+arithmetic, April 2025. Revision 17.

[2] Von Kurt Gödel. Über eine bisher noch nicht benÜtzte erweiterung des finiten standpunktes. Dialectica, 12:280–287, 12
1958.

[3] Ana Bove and Peter Dybjer. Dependent Types at Work, pages 57–99. Springer Berlin Heidelberg, Berlin, Heidelberg,
2009.

[4] Ulrich Berger. Continuous semantics for strong normalization. In S. Barry Cooper, Benedikt Löwe, and Leen Torenvliet,
editors, New Computational Paradigms, pages 23–34, Berlin, Heidelberg, 2005. Springer Berlin Heidelberg.

[5] The Stacks project authors. The stacks project. https://stacks.math.columbia.edu, 2025.
