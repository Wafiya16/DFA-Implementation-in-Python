
DFA refers to deterministic finite automata. Deterministic refers to the uniqueness of the computation. The finite automata are called deterministic finite automata if the machine is read an input string one symbol at a time. In DFA, there is only one path for specific input from the current state to the next state. DFA does not accept the null move, i.e., the DFA cannot change state without any input character. DFA can contain multiple final states.

DFA is implemented in python using oop approach. A class is made which accepts given states, alphabets , transition function, starting state, accepting states and reads input strings using file.txt and determine whether string is accepted or rejected. Few examples are given.
