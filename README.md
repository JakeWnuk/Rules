<h1 align="center">
Hashcat Rules
</h1>

## Designed for Full Candidates

### Local Rules
Iterative rules designed for consistent coverage. Hand-selected to ensure efficient tasks.
- Each rule set is built off the last
- Rules were hand selected to match generic password structure and avoid highly specific rules
- Rule sets have been optimized with [ruleprocessorY](https://github.com/TheWorkingDeveloper/ruleprocessorY)
- Rules were designed to be applied against full candidates while the others were designed for base words.

### Post Rules
Focused rules for "post-processing" after base changes.
- Transformation rules (no `$`, `^`, `i`, `o`, `t`, ect)

### Slide Rules
"Encapsulating" rules of special characters.
- Insert and append rules

## Designed for Partial Candidates

### Join Rules
"Joins" for words seen in the wild and verbs in different tenses.
- Append format

