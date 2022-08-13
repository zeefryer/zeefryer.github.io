---
layout: default
title: Math research
permalink: /math-research/
---

# Math research

My main math research interests are in noncommutative algebra and algebraic combinatorics, in particular quantized coordinate rings / quantum algebras and their semi-classical limits, and total nonnegativity in real matrices and the real Grassmannian. I've also co-authored several papers on applications of total nonnegativity in mathematical physics, specifically Wilson loop diagrams in quantum field theory.


You can find my academic CV [here](/files/CV2019.pdf), and a list of publications on the [Publications page](/publications/).

Below I've tried to give a very quick lay intro to some of my resesarch areas and potential applications to machine learning. There's also links to some old math outreach work I did when I was in grad school, and some more technical writings (including my PhD thesis) for anyone interested.


## Background

### **Algebra**

In math, algebra is the study of _mathematical structures_: given a few basic axioms (e.g. existence of addition and multiplication rules, and rules for how they interact), what can we say about the properties of any structure satisfying these axioms? Or, given an example of a structure (say, the set of all 2x2 real matrices, with standard addition and multiplication), what rules can we expect it to follow or not follow? 

This is a branch of pure math which can seem a bit abstract and pointless from the outside, but its payoffs are unexpected and unpredictable: usually it ends up being some physicist/biologist/computer scientist hearing about research on a theoretical class of structures and going "Hey, that looks almost like what my atoms/cells/neurons are doing, maybe I can use this?"!

For example, there have been a few really interesting attempts to impose various algebraic structures onto deep learning models; some papers I particularly enjoyed are:
- Beyond Fully-Connected Layers with Quaternions: Parameterization of Hypercomplex Multiplications with 1/n Parameters \[[link](https://openreview.net/pdf?id=rcQdycl0zyk)\]
- AlgebraNets \[[link](https://arxiv.org/abs/2006.07360)\]

I'd love to see (and to work on!) more research in this direction; the extra structure imposed by requiring a multiplication rule on a vector space could be the link we're missing in understanding how various machine learning models actually work.

### **Totally nonnegative matrices**

Totally nonnegative (TNN) real matrices are a really cool class of matrix: they're real matrices with the property that any [minor](https://en.wikipedia.org/wiki/Minor_(linear_algebra)) (that is, the determinant of any square submatrix) is nonnegative. One particularly nice thing about this is that they're much more concrete to explain and to think about than abstract algebraic structures are: you should be able to come up with some 2x2 examples yourself without too much effort!

TNN matrices have some beautiful combinatorics associated with them, as well as some [unexpected but very deep links](https://arxiv.org/abs/0911.2990) to quantum algebra; this is how I originally got interested in them. They also have multiple real-world applications, especially in areas of physics requiring nonnegative solutions to systems of equations: my favourite such application is in studying [a class of solutions to the KP equation](https://arxiv.org/abs/1106.0023), which can be used to model shallow water waves and may lead to new insights in the scince of tsunami prediction.

I've yet to see an application of TNN matrices to machine learning (as opposed to nonnegative matrix factorization, which is cool but a completely different technique) but I'm confident it's out there!



## Links for interested non-mathematicians

Here are some math outreach things I've created or been involved in; they're aimed at mathematically-inclined people but don't require any specialist knowledge. 
- [Poster](/files/poster_SET_low_res.pdf) explaining my PhD work on division rings. This reached the final of the [STEM for Britain](http://www.stemforbritain.org.uk) poster competition in 2015.
- [Matt Parker's Domino Computer](https://www.youtube.com/watch?v=OpLU__bhu2w), chronicling the efforts of a group of nerds (myself included) to build a 5-bit binary adder out of dominos.

## Further reading for mathematicians or math-adjacent people

The following documents go into more detail about my research, and are listed in roughly increasing order of specialisation.

- [Research proposal](/files/researchplan.pdf) on H-primes, totally nonnegative matrices, and applications to physics (2017, mainly aimed at general mathematicians but includes a lay summary that should be pretty accessible).
- [Research statement](/files/research_statement_2015.pdf) (2015, aimed at algebraists).
- [PhD thesis](/files/thesis.pdf) (2014, aimed at noncommutative algebraists).
