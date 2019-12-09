This is the data accompanying the paper 
"Deep Reinforcement Learning in HOL4".

The sub-folder "datasets" contains three files:
- train for the training set
- valid for the validation set
- test for the test set

Each line of these files consists of an arithmetical expression 
in S-expression format, its value and the length of its 
left-outermost derivation. 

The sub-folder "datasets_hol4" contains the same sets of 
expressions in a format that can 
be easily imported into HOL4 using 
the `mlTacticData.import_terml` function.

All experiments can be replicated by running the commands in comments
at the end of the files (mleEntail, mleCompute, mleSynthesize, mleRewrite)
in the HOL/src/AI/experiments folder in an interactive HOL4 session.
