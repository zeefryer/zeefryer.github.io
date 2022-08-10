---
layout: page
title: Math research
permalink: /math-research/
---


My main math research interests are in noncommutative algebra and algebraic combinatorics, in particular quantized coordinate rings / quantum algebras and their semi-classical limits, and total nonnegativity in real matrices and the real Grassmannian. I've also co-authored several papers on applications of total nonnegativity in mathematical physics, specifically Wilson loop diagrams in quantum field theory.


- My academic CV is [here](/files/CV2019.pdf).
- (very old!) Python code for computing with positroids is [here](https://github.com/zeefryer/positroids).

Below I've tried to give a very quick intro to what some of the words above mean, along with links to some old work of mine on these subjects and my bibliography of published math papers.


# Background

## Algebra

In math, algebra is the study of _mathematical structures_: given a few basic axioms (e.g. existence of addition and multiplication rules, and rules for how they interact), what can we say about the properties of any structure satisfying these axioms? Or, given an example of a structure (say, the set of all 2x2 real matrices, with standard addition and multiplication), what rules can we expect it to follow or not follow? 

This is a branch of pure math which can seem a bit abstract and pointless from the outside, but its payoffs are unexpected and unpredictable: usually it ends up being some physicist/biologist/computer scientist hearing about research on a theoretical class of structures and going "Hey, that looks almost like what my atoms/cells/neurons are doing, maybe I can use this?"!

For example, there have been a few really interesting attempts to impose various algebraic structures onto deep learning models: I particularly enjoyed [links]. I'd love to see (and to work on!) more research in this direction; the extra structure imposed by (say) requiring a multiplication rule on a vector space could be the link we're missing in understanding how various machine learning models actually work.

## Totally nonnegative matrices

Totally nonnegative (TNN) real matrices are a really cool class of matrix: they're real matrices with the property that any minor (that is, the determinant of any square submatrix) is nonnegative. One particularly nice thing about this is that they're much more concrete to explain and to experiment with: you should be able to come up with some 2x2 examples yourself without too much effort!

TNN matrices have some beautiful combinatorics associated with them, as well as some unexpected but very deep links to quantum algebra; this is how I originally got interested in them. They also have multiple real-world applications, especially in areas of physics requiring nonnegative solutions to systems of equations: my favourite such application is in studying a class of solutions to the KP-equation, which can be used to model shallow water waves and may lead to new insights in the scince of tsunami prediction.

I've yet to see an application of TNN matrices to machine learning (as opposed to nonnegative matrix factorization, which is cool but entirely different) but I'm confident it's out there!



# Links for interested non-mathematicians

Here are some math outreach things I've created or been involved in; they're aimed at mathematically-inclined people but don't require any specialist knowledge. 
- [Poster](/files/poster_SET_low_res.pdf) explaining my PhD work on division rings. This reached the final of the [STEM for Britain](http://www.setforbritain.org.uk/index.asp) poster competition in 2015.
- [Matt Parker's Domino Computer](https://www.youtube.com/watch?v=OpLU__bhu2w), chronicling the efforts of a group of nerds (myself included) to build a 5-bit binary adder out of dominos.

# Further reading for mathematicians or math-adjacent people

The following documents go into more detail about my research, and are listed in roughly increasing order of specialisation.

- [Research proposal](/files/researchplan.pdf) on H-primes, totally nonnegative matrices, and applications to physics (2017, mainly aimed at general mathematicians but includes a lay summary that should be pretty accessible).
- [Research statement](/files/research_statement_2015.pdf) (2015, aimed at algebraists).
- [PhD thesis](/files/thesis.pdf) (2014, aimed at noncommutative algebraists).

# Papers and pre-prints

My math papers are all published as S. Fryer. As per convention in the mathematics community, all authors are listed alphabetically by surname.

- (with S. Agarwala, K. Yeats) Combinatorics of the geometry of Wilson loop diagrams II: Grassmann necklaces, dimensions, and denominators. (Canadian Journal of Mathematics (2021)) [arXiv 1910.12158](https://arxiv.org/abs/1910.12158)
- (with S. Agarwala, K. Yeats) Combinatorics of the geometry of Wilson loop diagrams I: equivalence classes via matroids and polytopes. (Canadian Journal of Mathematics (2021)) [arXiv 1908.10919](https://arxiv.org/abs/1908.10919)
- (with S. Agarwala) A study in \[Nonnnegative Real Grassmannians\]: from the geometric case book of Wilson loop diagrams and SYM N = 4. (Annals IHP D - Comb., Phys. and their Interactions (2021)) [arXiv 1803.00958](https://arxiv.org/abs/1803.00958)
- (with S. Agarwala) An algorithm to construct the Le diagram associated to a Grassmann necklace (Glasg. Math. J. 2017, 1-7) [arXiv 1803.01726](https://arxiv.org/abs/1803.01726)
- (with T. Kanstrup, E. Kirkman, A. Shepler, S. Witherspoon) Color Lie Rings and PBW Deformations of Skew Group Algebras (J. Algebra 518 (2019), 211-236) [arXiv 1801.08855](https://arxiv.org/abs/1801.08855)
- (with M. Yakimov) Separating Ore Sets for Prime Ideals of Quantum Algebras (Bull. Lond. Math. Soc. 49, 2017) [arXiv 1602.05052](http://arxiv.org/abs/1602.05052)
- (with K. Casteels) From Grassmann necklaces to restricted permutations and back again (Algebr. Represent. Theory 20, 2017) [arXiv 1511.06664](http://arxiv.org/abs/1511.06664)
- The Prime Spectrum of Quantum SL3 and the Poisson-prime Spectrum of its Semi-classical Limit (Trans. London Math. Soc. 4, 2017) [arXiv 1505.06627](http://arxiv.org/abs/1505.06627)
- The q-Division Ring and its Fixed Rings (J. Alg 204, 2014) [arXiv 1310.5071](http://arxiv.org/abs/1310.5071)

