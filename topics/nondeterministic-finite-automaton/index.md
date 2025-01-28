---
aliases: nondeterministic-finite-automata, nondeterministic-finite-automatons, nfa
created_by: Michael Rabin, Dana Scott
display_name: Nondeterministic finite automaton
related: finite-state-machine, deterministic-finite-automaton, pattern-matching, lexical-analysis, regular-expression
released: April 1959
short_description: A finite-state machine that either accepts or rejects a given sequence of symbols.
topic: nondeterministic-finite-automaton
wikipedia_url: https://en.wikipedia.org/wiki/Nondeterministic_finite_automaton
---
**Nondeterministic finite automata** (NFA) are a generalization of [deterministic finite automata](https://github.com/topics/deterministic-finite-automaton); a state may transition to one of multiple states upon reading a symbol, or the empty string (see [ε-transitions](https://en.wikipedia.org/wiki/Nondeterministic_finite_automaton#NFA_with_%CE%B5-moves)).

Regular expressions can be implemented with NFAs using [Thompson's construction](https://en.wikipedia.org/wiki/Thompson%27s_construction); NFAs can be transformed to regular expressions using [Kleene's algorithm](https://en.wikipedia.org/wiki/Kleene%27s_algorithm) and determinized to [DFAs](https://github.com/topics/deterministic-finite-automaton) using the [powerset construction](https://en.wikipedia.org/wiki/Powerset_construction).
