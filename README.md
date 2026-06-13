# Golf Score Translator 🏌️‍♂️

A JavaScript utility function that calculates a golfer's scoring nickname based on the hole's `par` and the number of `strokes` taken.

---

## 🧭 Score Mapping Reference

The program evaluates the relationship between strokes and par using the following logic:

| Strokes | Return Value | Nickname Meaning |
| :--- | :--- | :--- |
| `1` | `"Hole-in-one!"` | Ball cleared in a single shot |
| `<= par - 2` | `"Eagle"` | Two or more shots under par |
| `par - 1` | `"Birdie"` | One shot under par |
| `par` | `"Par"` | Exactly equal to par |
| `par + 1` | `"Bogey"` | One shot over par |
| `par + 2` | `"Double Bogey"` | Two shots over par |
| `>= par + 3` | `"Go Home!"` | Three or more shots over par |

---
