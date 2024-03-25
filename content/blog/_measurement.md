---
title: "Measurement"
date: 2024-03-07T21:56:08+02:00
draft: true
math: true
#tags: ["Decision"]
---


This post was inspired by reading Krantz, D. H., Luce, R. D., Suppes, P., & Tversky, A. (1971). Foundations of measurement: Addıtive and polynomial. Representations, 1.

The authors first define a __relational structure__ $ \left( A, \succsim, \circ \right)$ and argue that the point of measurement is to find an homomorphism between it and $\left( \mathbb{R}, \geq, + \right)$. Translated, there must exist a function $m : A \rightarrow \mathbb{R}$ such that for all $x, y \in A$ it holds that $x \succsim y \iff m \left(x \right) \geq m \left( y \right)$, i.e. structure is preserved.

I think this is an illuminating perspective on what the procedure of "measurement" is, and I will comment on the implications for decision theory. What this way of viewing things makes clear is that the relational structure is what you observe. Consider a collection of objects in such that you can "combine" them in some way. The example in the book are rods. Say you have two rods, you can combine them to obtain a third rod. The homeomerphism result, in my translation, would be something like "if you observe things behaving as in this relational structure, then there is a sense in which you can measure them with the function $f$."

Of course, you can or you cannot observe things behaving as that relational structure, you might also observe things behaving according to a different relational structure. You might also obtain something slightly different from a homomorphism in this sense, like in the case of incompleteness, where representations exist, just not in the sense mentioned here. To adapt what was said before, there still exist a sense in which you can measure incomplete preferences, it is just not the same sense in which you measure complete and transitive ones.

From this perspective, a representation result in decision theory may be interpreted as the definition of a measurement procedure for a certain kind of observational structure, i.e. dataset with some properties. Therefore, if you see some axiom violated, you just know that you cannot measure your data in the way the representation theorem does, you have to use something else, if there is a sense in which your data can be measured at all.

