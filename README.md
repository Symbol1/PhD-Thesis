# Complexity and Second Moment of the Mathematical Theory of Communication

This is my PhD dissertation and defense slides.

## Abstract

The performance of an error correcting code is evaluated by
its block error probability, code rate, and encoding and decoding complexity.
The performance of a series of codes is evaluated by,
as the block lengths approach infinity,
whether their block error probabilities decay to zero,
whether their code rates converge to channel capacity,
and whether their growth in complexities stays under control.

Over any discrete memoryless channel, I build codes such that:
for one, their block error probabilities and code rates scale like random codes';
and for two, their encoding and decoding complexities scale like polar codes'.
Quantitatively, for any constants $\pi, \rho > 0$ such that $\pi + 2\rho < 1$,
I construct a series of error correcting codes with
block length $N$ approaching infinity,
block error probability $\exp(-N^\pi)$,
code rate $N^{-\rho}$ less than the channel capacity,
and encoding and decoding complexity $O(N \log N)$ per code block.

Over any discrete memoryless channel, I also build codes such that:
for one, they achieve channel capacity rapidly;
and for two, their encoding and decoding complexities
outperform all known codes over non-BEC channels.
Quantitatively, for any constants $\tau,\rho>0$ such that $2\rho<1$,
I construct a series of error correcting codes with
block length $N$ approaching infinity,
block error probability $\exp(-(\log N)^\tau)$,
code rate $N^{-\rho}$ less than the channel capacity,
and encoding and decoding complexity $O(N \log(\log N))$ per code block.

The two aforementioned results are built upon two
pillars---a versatile framework that generates codes on the basis of channel polarization,
and a calculus--probability machinery that evaluates the performances of codes.

The framework that generates codes and the machinery that evaluates codes
can be extended to many other scenarios in network information theory.
To name a few:
lossless compression with side information,
lossy compression,
Slepian--Wolf problem,
Wyner--Ziv Problem,
multiple access channel,
wiretap channel of type I,
and broadcast channel.
In each scenario, the adapted notions of block error probability and code rate
approach their limits at the same paces as specified above.
