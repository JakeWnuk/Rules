<h1 align="center">
Hashcat Rules
</h1>

## Designed for Full Candidates

### Local Rules
Iterative rules designed for consistent coverage. Hand-selected to ensure efficient tasks.
- Each rule set is built off the last
- Rules were hand selected to match generic password structure and avoid highly specific rules
- `50k` version includes top rules from the `partial candidate` rules
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
Append and toggle rules in one from frequency sorted data.
- Append and toggle rules in one per rule
- In order by performance

### Poggle Rules
Prepend and toggle rules in one from frequency sorted data.
- Prepend and toggle rules in one per rule
- In order by performance

### Bad Rules
Rules for bad passwords.
- `25` total
