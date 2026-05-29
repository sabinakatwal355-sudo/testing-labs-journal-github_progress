# Boolean expressions

## Complete de following tables

### Basic Completion

| $A$ | $B$ | $A \times B$ | $A + B$ |
|:---:|:---:|:---------:|:--------:|
| 0 | 0 |    0   |   0   |
| 0 | 1 |    0    |   1    |
| 1 | 0 |    0    |   1    |
| 1 | 1 |    1    |   1    |

### Compound Expression

| $A$ | $B$ | $C$ | $A + B$ | $\overline C$ | $(A + B) \times \overline C$ |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 0 | 0 | 0 |   0    |   1    |         0          |
| 0 | 0 | 1 |   0    |   0    |         0          |
| 0 | 1 | 0 |   1    |   1    |         1          |
| 0 | 1 | 1 |   1    |   0    |         0          |
| 1 | 0 | 0 |   1    |   1    |         1          |
| 1 | 0 | 1 |   1    |   0    |         0          |
| 1 | 1 | 0 |   1    |   1    |         1          |
| 1 | 1 | 1 |   1    |   0    |         0          |

### Match the Expression

**Expressions:**
1. $A \land B$ matches table B
2. $A \lor B$ matches table C
3. $\neg A$ matches table D
4. $A \oplus B$ (XOR) matches table A

**Truth Tables:**

**Table A**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Table B**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Table C**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

**Table D**

| A | Output |
|---|--------|
| 0 |   1    |
| 1 |   0    |



