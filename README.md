# Knights2

Add knowledge to knowledge bases knowledge0, knowledge1, knowledge2, and knowledge3 to solve the following puzzles.

Puzzle 0 is the puzzle from the Background. It contains a single character, A.
A says “I am both a knight and a knave.”
Puzzle 1 has two characters: A and B.
A says “We are both knaves.”
B says nothing.
Puzzle 2 has two characters: A and B.
A says “We are the same kind.”
B says “We are of different kinds.”
Puzzle 3 has three characters: A, B, and C.
A says either “I am a knight.” or “I am a knave.”, but you don’t know which.
B says “A said ‘I am a knave.’”
B then says “C is a knave.”
C says “A is a knight.”
In each of the above puzzles, each character is either a knight or a knave. Every sentence spoken by a knight is true, and every sentence spoken by a knave is false.

Once you’ve completed the knowledge base for a problem, you should be able to run python puzzle.py to see the solution to the puzzle.

Concepts
Sentence: an assertion about the world in a knowledge representation language.
Knowledge base: a set of sentences known by a knowledge-based agent.
Entailment: a entails b if in every model in which sentence a is true, sentence b is also true.
Inference: the process of deriving new sentences from old ones.
Conjunctive normal form: logical sentence that is a conjunction of clauses.
First order logic: Propositional logic.
Second order logic: Proposition logic with universal and existential quantification.
Algorithms
Model checking: enumerate all possible models and see if a proposition is true in every one of them.
Conversion to CNF and Inference by resolution
