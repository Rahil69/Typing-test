# Learning Progress

## State modelling / derived state
- Demonstrated understanding: proposed storing only the user's typed input in state, keeping the target text as a plain string, and computing each letter's colour by comparing input[i] to target[i]. The colour is derived, not stored.
- Needs reinforcement: the grey case means "not typed yet" (index beyond the input length); learner described it as "missed".

## Pending decision
Build checkpoint: alignment of input and target (stage: awaiting reasoning). With a single flat comparison, one extra or skipped character shifts every later letter, so they all turn red. Asked the learner whether that's acceptable for v1 or how they'd handle it (e.g. comparing word by word).

Also outstanding: the project is nested at ~/typing-test/typing-test with stray package files in the outer folder. Learner was given commands to flatten it; not done yet as of last check.
