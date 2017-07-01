# Exercises

## Simple decipherment task
`/data` has two files `alice.en` and `alice.x`. The later is created by applying a simple substitution
set of rules for each letter. Lets call X is the language after coding.

Task:
  1. Take 2000 first sentences of both files as training data,
  the next 200 sentences as development data and the rest for testing.
  2. Build a seq2seq model that learn to map english sentences to language X.
  3. Adding attention mechanism to the model, observing the performance with respect to the length of the input.
  4. Test the system on your testing data.
