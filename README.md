<h1 align="center">
Hashcat Rules
</h1>

## Designed for Full Candidates

### Local Rules
Iterative rules designed for consistent coverage. Hand-selected to ensure efficient tasks.
- Each rule set is built off the last
- Rules were hand selected to match generic password structure and avoid highly specific rules
- Rule sets have been optimized with [ruleprocessorY](https://github.com/TheWorkingDeveloper/ruleprocessorY)
- Rules were designed to be applied against full candidates
- In order by length

### Post Rules
Focused rules for "post-processing" after base changes.
- Transformation rules (no `$`, `^`, `i`, `o`, `t`, etc)
- In order by length

## Designed for Partial Candidates

### Append Rules
Append rules from frequency sorted data.
- Non-alpha append rules
- In order by performance

### Prepend Rules
Prepend rules from frequency sorted data.
- Alpha prepend rules
- In order by performance

### Taggle Rules
Prepend/Append and toggle rules in one from frequency sorted data.
- Prepend/Append and toggle rules in one per rule
- In order by performance

### Poggle Rules
Prepend and toggle rules in one from frequency sorted data.
- Prepend and toggle rules in one per rule
- In order by performance
