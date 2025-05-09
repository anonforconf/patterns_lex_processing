# Patterns of Lexical Storage and Processing
This repository contains the dataset put up for the study titled "What Word-Guessing Reveals About Your Brain: Patterns of Lexical Storage and Processing" 

**Description of the Variables**

| **Variable Name** | **Type**      | **Description**                                                                                                  | **Values / Format**                                                                 |
|-------------------|---------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| `target_word`     | String        | The word that participants tried to guess based on clues.                                                       | Unique word tokens                                                                 |
| `concreteness`    | Categorical   | Indicates whether the target word is abstract or concrete in nature.                                            | `Concrete`, `Abstract`                                                              |
| `pos`             | Categorical   | Part of speech of the target word.                                                                              | `Noun`, `Adjective`, `Verb`                                                         |
| `frequency`       | Numeric       | Corpus-based word frequency (from Ruscorpora). Higher values = more common usage.                            | Integer                                                                             |
| `strategy`        | Categorical   | Type of the clue used to describe the target word.                                                             | `Antonym`, `Synonym`, `Co-hyponym`, `Hyponym`, `Hypernym`, `Collocation`, `Definition`, `Real-life example` |
| `trial_number`    | Ordinal       | Indicates the number of the trial.                                        | `1st Trial`, `2nd+ Trial`                                                           |
| `guessed`         | Binary        | Whether the word was successfully guessed on a given trial.                                                                      | `Yes`, `No`                                                                         |

### 🔍 Variable Classifications

- **Distributional Strategies**:  
  Based on co-occurrence and linguistic relationships.  
  Includes: `Real-life example`, `Collocation`

- **Attributional Strategies**:  
  Based on descriptive features or world knowledge.  
  Includes: `Definition`, `Antonym`, `Synonym`, `Co-hyponym`, `Hyponym`, `Hypernym`,
