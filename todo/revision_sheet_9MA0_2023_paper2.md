# Revision Sheet: Edexcel A-level Maths 9MA0/02 (June 2023)

## Score and grade

| | Marks | % |
|---|---|---|
| Full paper (all 15 questions) | 61/100 | 61% |
| Adjusted (excluding Q9 and Q13, topics not yet taught) | 61/80 | 76.3% |

- **Provisional grade (full paper): B**
- **Provisional grade (adjusted): A**
- Q11(a) is marginal. If the λ step is marked strictly, subtract 1 mark (60/100 and 60/80). The grades don't change.

### Boundaries used
Official Pearson notional boundaries for Paper 2 (out of 100):

| A* | A | B | C | D | E |
|---|---|---|---|---|---|
| 80 | 63 | 51 | 39 | 27 | 16 |

Overall 9MA0 boundaries, June 2023 (out of 300, from Maths Genie / Save My Exams):

| A* | A | B | C | D | E |
|---|---|---|---|---|---|
| 244 (81.3%) | 196 (65.3%) | 158 (52.7%) | 121 (40.3%) | 84 (28.0%) | 47 (15.7%) |

Notes:
- Grades are set on all three papers combined. Paper-level boundaries are indicative only.
- Full paper: 2 marks below the Paper 2 A boundary.
- Adjusted: about 8 marks above A, about 3 to 4 marks short of A*.
- Boundaries change every year. Use them as a guide only.

Sources:
- https://qualifications.pearson.com/content/dam/pdf/Support/Grade-boundaries/A-level/2306-gce-notional-component-grade-boundaries.pdf
- https://www.mathsgenie.co.uk/edexcel-a-level-grade-boundaries.php
- https://www.savemyexams.com/learning-hub/grade-boundaries/a-level/edexcel/maths/

## Marks by question

| Q | Mark | Q | Mark |
|---|---|---|---|
| 1 | 3/4 | 8 | 3/6 |
| 2 | 6/6 | 9 | skipped |
| 3 | 5/5 | 10 | 6/7 |
| 4 | 3/4 | 11 | 7/10 |
| 5 | 4/5 | 12 | 8/10 |
| 6 | 6/6 | 13 | skipped |
| 7 | 7/7 | 14 | 1/7 |
| | | 15 | 2/3 |

## Errors and corrections

### Q1(b)(ii): wrong inequality direction (lost 1)
- **You wrote:** concave when x > −2/3.
- **Should be:** f″(x) < 0 means concave, so **x ≤ −2/3** (x < −2/3 also accepted).
- **Rule:** concave means f″ < 0. Convex means f″ > 0. Check by testing a value, for example x = −1 gives f″ = −2 < 0, so it is concave.

### Q4(b): sign error for "cooling" (lost 1)
- **You wrote:** dH/dt = +7.5, which gave B = −0.136.
- **Should be:** cooling means the rate is negative, so dH/dt = −7.5.
- dH/dt = −ABe^(−Bt), so at t = 0: −55B = −7.5, giving **B = 3/22 ≈ 0.136**.
- Final answer: **H = 55e^(−0.136t) + 30**.
- Your final equation matched only by accident. It was inconsistent with your own B, because B = −0.136 would make e^(−Bt) = e^(+0.136t).
- **Rule:** cooling, decreasing or falling gives a negative rate. Check the sign against the context.

### Q5(b): arithmetic slip (lost 1)
- **You wrote:** 40.5 − 81 + 22.5 + 36 **+ 6** + c = −10, so c = −34.
- **Should be:** 40.5 − 81 + 22.5 + 36 = 18, so 18 + c = −10 and **c = −28**.
- Answer: **(0, −28)**. There was no "+6" term.
- **Rule:** write each substituted term on its own line and re-add. Ask whether the answer is sensible.

### Q8(a): exact value needed (lost 1)
- **You wrote:** R = 8.246.
- **Should be:** R = √(2² + 8²) = √68 = **2√17**.
- **Rule:** "Exact" means surd, fraction or π form. Decimals score B0 even if correct.
- α = tan⁻¹(4) = 1.326 was correct.

### Q8(b)(i): never found the maximum value (lost 2)
- **You did:** S₉ = 9cos x + 36 sin x, then went straight to finding x.
- **Should do:** the maximum is 4.5 × R = 4.5 × 2√17 = **9√17**. Alternatively, √(9² + 36²) = 9√17 ≈ 37.1.
- **Rule:** part (i) asks for the value. Part (ii) asks for x. Re-read what each part is asking for.
- (ii) was correct: x ≈ 1.326.

### Q10(b): log algebra error (lost 1)
- Your integration, limits and subtraction were all correct, giving **(k + 6) ln 5 = 21**.
- **You wrote:** k + 6 = e²¹.
- **Should be:** divide by ln 5. **k + 6 = 21/ln 5, so k = 21/ln 5 − 6**.
- **Rule:** "ln 5" here is just a number multiplying the bracket. It is not ln(5(k+6)). Only use e^ when ln is applied to the whole unknown.

### Q11(a): link to λ (marginal, may lose 1)
- **You wrote:** dh/dt = 0.005k/√h.
- **Should add:** "let λ = 0.005k (or k/200), so dh/dt = λ/√h".
- Don't use λ for both constants. If dV/dt = λ/√h, use a different letter or define λ properly.

### Q11(b): didn't integrate (lost 3)
- **You did:** substituted straight into h^(3/2) = At + B.
- **Should do:**
  1. dh/dt = λ/√h gives ∫h^(1/2) dh = ∫λ dt.
  2. (2/3)h^(3/2) = λt + c.
  3. t = 0, h = 1.44: c = 1.152.
  4. t = 8, h = 3.24: λ = 0.342.
  5. h^(3/2) = 0.513t + 1.728.
- Your values A = 0.513 and B = 1.728 were correct, but "use the model" requires integration of the differential equation.
- **Rule:** when a question gives a differential equation, always separate the variables and integrate. Don't jump to the answer form.

### Q12(c): wrong region (lost 2)
- Critical values 5/3 and 13/3 were correct.
- **You wrote:** {t : 5/3 < t < 13/3}.
- **Should be:** N_A > N_B **outside** the intersection points: {t : t < 5/3} ∪ {t : t > 13/3}.
- **Check:** at t = 0, N_A = 7 > N_B = 2, so the region containing t = 0 is correct.
- At t = 3, N_A = 4 < N_B = 8, so the middle is wrong.
- **Rule:** for "find where A > B", sketch both graphs or test one value in each region. For modulus graphs, mark which graph is higher.

### Q14(a): didn't reach the required form (lost 2)
- You used the identities correctly (sec², sin 2θ = 2sinθcosθ, tan = sin/cos), which earned the B1.
- **You stopped at:** 8cosθ + 23sin²θ = 8, after dividing by tan θ. That loses the solutions where tan θ = 0.
- **Should be:**
  1. 2tanθ(8cosθ + 23sin²θ) = 8 sin 2θ sec²θ.
  2. Multiply both sides by cos²θ: 2sinθcosθ(8cosθ + 23sin²θ) = 8 sin 2θ.
  3. sin 2θ(8cosθ + 23(1 − cos²θ)) = 8 sin 2θ.
  4. **sin 2θ(23cos²θ − 8cosθ − 15) = 0**, so A = 23, B = −8, C = −15.
- **Rule:** never divide by a trig factor you want solutions from. Factorise instead and keep it as a product equal to zero.

### Q14(b): not attempted (lost 4)
- sin 2x = 0 gives x = 360° or 540°.
- 23cos²x − 8cosx − 15 = 0 gives cos x = −15/23 (or cos x = 1, which repeats 360° and 540°), so x ≈ 490.7° ≈ 491°.
- Answers: **x = 360°, 491°, 540°**. Exclude 450° as stated.
- **Revision note:** 2x range here is 720° to 1080°. Check every sin 2x = 0 root in [360°, 540°], meaning 2x = 720° and 1080°.

### Q15: variable slip in the contradiction (lost 1)
- **You wrote:** "sin(x) is negative between 180 and 360".
- **Should write:** since 180° < 2x < 360°, **sin 2x < 0**. So 1 − sin 2x > 1, which contradicts 1 − sin 2x < 1.
- **Rule:** keep the variable consistent (2x, not x). Always state clearly "this is a contradiction" and give the final conclusion.

## Summary of error types

1. **Misreading what is asked.** This covers exact values in Q8(a), the maximum value in Q8(b)(i), "use the model" in Q11(b) and the exact region in Q12(c). Underline command words and keywords such as "exact", "value" and "hence".
2. **Sign and direction errors.** These were Q1, Q4 and Q12. Test with a value.
3. **Arithmetic slips.** Q5 and Q10. Write each step on a new line and re-check substitutions.
4. **Incomplete working or method.** Q8, Q11 and Q14. Show every method step the scheme asks for.
5. **Notation.** Q11(a) (λ) and Q15 (sin x vs sin 2x). Keep notation consistent and define new constants.

## Quick targets

Fixing the avoidable errors above would be worth about 11 marks. That would put the adjusted score at about 72/80 (90%).

- [ ] Underline "exact", "value", "hence", "use the model" before starting
- [ ] Test one value for every inequality or region answer
- [ ] Sign check on rates (cooling or decreasing means negative)
- [ ] Re-add every substitution line
- [ ] Never divide by a trig factor. Factorise instead.
- [ ] Learn the trig identity manipulation for products like 2tanθ(...)
