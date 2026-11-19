# Revision Report: Edexcel AS Maths 8MA0 Paper 21 (Statistics), Summer 2023

## Score and provisional grade

| | |
|---|---|
| Score | **23 / 30 = 76.7%** |
| Cautious score (if the 3 borderline marks are withheld: Q2(a), Q2(b), Q3(b) M1) | 20 / 30 = 66.7% |
| Provisional grade | **A range (indicative only)** |

Marks lost: Q2(c) 1, Q2(d) 1, Q3(b) 3, Q5(b) 2 (total 7).

### Boundaries (Pearson, June 2023, AS Mathematics 8MA0)

| Grade | Overall /160 | % | Paper 2 notional /60 | % |
|---|---|---|---|---|
| A | 103 | 64.4% | 38 | 63.3% |
| B | 90 | 56.3% | 33 | 55.0% |
| C | 77 | 48.1% | 28 | 46.7% |
| D | 64 | 40.0% | 24 | 40.0% |
| E | 52 | 32.5% | 20 | 33.3% |

For reference, A-level (9MA0) /300: A* 244, A 196, B 158, C 121, D 84, E 47.

Caveats:
- Real grades come from the whole qualification (Paper 1 Pure is 100 marks and Paper 2 is 60 marks, of which this Statistics section is 30).
- Notional component boundaries do not equal a certificated grade.
- Subject boundaries were taken from a school-hosted copy of Pearson's published document.

Sources:
- https://qualifications.pearson.com/content/dam/pdf/Support/Grade-boundaries/A-level/2306-gce-notional-component-grade-boundaries.pdf
- https://www.bishopwordsworths.org.uk/assets/Uploads/Edexcel-GCE-Grade-Boundaries-June-2023.pdf

---

## Errors and what you should have written

### Q5(b): lost 2 marks (HIGH PRIORITY)
**Question:** Yuki picks 10 letters with replacement from DEVIATION. Find P(E selected at least 4 times).

**What you did:** 10C4 (1/9)^4 (8/9)^6 = 0.0158. This is P(J = 4) only.

**Should have been:**
- J ~ B(10, 1/9), because E appears once in 9 letters.
- "At least 4" means P(J ≥ 4) = 1 − P(J ≤ 3) = 1 − 0.98157 = **0.0184**.

**Rule to remember:** "at least k" means 1 − P(X ≤ k−1). Never a single term.

### Q3(b): lost 3 marks (HIGH PRIORITY)
**Question:** 45 students, 25 do Art, 12 do both, x do Music. Can A and M be independent?

**What you did:** P(A∩B) = P(A)P(B), then wrote "12 = 25 × x" and compared it with 12 ≤ x ≤ 32.

**Errors:**
- Counts and probabilities were mixed in one equation.
- You used B for the event M.
- The conclusion was right but the reasoning was invalid.

**Should have been:**
1. Independence needs P(A)P(M) = P(A∩M).
2. (25/45) × (x/45) = 12/45, so x = 12 × 45 / 25 = **21.6**.
   - Equivalent route: P(M) = (12/45) ÷ (25/45) = 12/25 = 0.48, and 0.48 × 45 = 21.6.
3. x must be a whole number, so **A and M cannot be independent**.

**Mark scheme:** M1 for the definition using A and M, A1 for 0.48 or the correct equation, A1 for 21.6 (or y = 9.6), A1 for the conclusion.

### Q2(d): lost 1 mark (answer: "Honestly idk")
**Should have been:** In the large data set, Daily Mean Wind Speed (Beaufort) is a **qualitative / categorical** variable (it is given in words, e.g. "light"). A linear relationship is not meaningful for it.

### Q2(c): lost 1 mark (answer: "1.01 hPa")
**Should have been:** any value from **990 to 1040 hPa** (for example 1010 hPa). Daily mean pressure in the large data set is around 1000 hPa, and the value must lie inside the range of the data.

*(Note on Q2(c) and Q2(d): these are the only large-data-set marks on this paper, 2 marks in total. They are learnt facts, not skills. Your call whether they are worth a look.)*

### Q2(b): borderline mark, risky wording
**What you did:** "t ∝ k/p so t is inversely proportional to p. The mean air temperature decreases with pressure."

**Error:** The inverse proportion claim is wrong. The scatter shows a roughly linear negative trend. The scheme gives 0 for "inversely proportional" on its own, and you only got credit for the second sentence.

**Should have been:** "As pressure increases, temperature decreases (negative correlation)."

---

## Revision list

**High priority**
1. "At least / at most / more than / fewer than" translates to cumulative binomial probabilities (Q5(b) pattern).
2. Independence tests: write P(A)P(B) = P(A∩B) with *all terms as probabilities*. Convert counts by dividing by the total (Q3(b) pattern).

**Medium priority**
3. Describing correlation (Q2(a)). Your answer, "no direct correlation", was ambiguous because "direct" can mean "positive". Use "no (linear) correlation" or "weak correlation", and add "negative" or "positive" only if clear. **(Added to the list as you asked.)**
4. Interpreting a scatter diagram in context: "as p increases, t decreases". Do not claim proportionality from a scatter.

**Low priority (quick recap)**
5. Use the labels given in the question (A and M, not B) so the mark scheme's "must use A and M" condition is met. **(Added as you suggested.)**
6. Give answers to 3 s.f. when the paper says so (1.59, not 1.588).
7. Large data set facts (Q2(c), Q2(d)): pressure about 990–1040 hPa, and Beaufort wind speed is categorical.

---

## Quick reference: what went well (no action needed)
Q1 (grouped mean and standard deviation, effect of a shift), Q3(a) (range), Q4 (hypothesis test, critical region, conclusion in context) and Q5(a) (probability distribution) were all full marks.
