# Causal Broadcast: How to Forget? [[pdf](https://hal.archives-ouvertes.fr/hal-01923830v2/document)]

_Keywords: Causal broadcast, complexity trade-off, large and dynamic systems_

_Authors: Brice Nédelec, Pascal Molli, Achour Mostéfaoui_

Causal broadcast constitutes a fundamental communication primitive of many
distributed protocols and applications. However, state-of-the-art
implementations fail to forget obsolete control information about already
delivered messages. They do not scale in large and dynamic systems.  In this
paper, we propose a novel implementation of causal broadcast.  We prove that all
and only obsolete control information is safely removed, at cost of a few
lightweight control messages. The local space complexity of this protocol does
not monotonically increase and depends at each moment on the number of messages
still in transit and the degree of the communication graph. Moreover, messages
only carry a scalar clock.  Our implementation constitutes a sustainable
communication primitive for causal broadcast in large and dynamic systems.

## Acknowledgements

This work was partially funded by the French ANR projects O'Browser
([ANR-16-CE25-0005-01](http://www.agence-nationale-recherche.fr/Projet-ANR-16-CE25-0005)),
and Descartes
([ANR-16-CE40-0023](http://www.agence-nationale-recherche.fr/Projet-ANR-16-CE40-0023)).