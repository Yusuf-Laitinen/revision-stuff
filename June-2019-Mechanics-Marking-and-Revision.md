# June 2019 Mechanics Paper — Marking and Revision

## Result

**Estimated score: 43/50 (86%)**

This is a self-mark against the supplied Pearson markscheme. I have awarded method marks where your working shows the intended method. Question 4(a) depends on interpreting your phrase “normal to the barrel” as identifying the contact reaction as normal to the drum; I have awarded that one mark. If an examiner did not accept that wording, the score would be **42/50**.

| Question | Mark | Notes |
|---|---:|---|
| 1(a) | 3/3 | Correct differentiation and acceleration. |
| 1(b) | 2/3 | Integration is correct, but the initial position vector was not added. |
| 2(a) | 4/4 | Correct velocity model and direction condition; (T=8). |
| 2(b) | 4/4 | Correct displacement and distance (4\sqrt{13}\,\text{m}). |
| 3(a) | 8/8 | Correct force model and simultaneous equations; obtains the required tension. |
| 3(b) | 0/2 | Conclusion is “yes”, but the justification does not compare limiting friction with the downslope component of A’s weight. |
| 3(c) | 2/2 | Both refinements are valid. |
| 4(a) | 1/1* | Awarded for the implied normal contact reaction; see note above. |
| 4(b) | 9/9 | Correct moments, force components, and resultant (66.5\,\text{N}). |
| 4(c) | 0/1 | The reaction at C decreases when the centre of mass shifts toward A; you wrote that it increases. |
| 5(a) | 4/6 | Correct speed, but the direction of P’s velocity is missing. |
| 5(b) | 5/6 | Strong setup, but a small vertical-component arithmetic error makes both final values slightly wrong. |
| 5(c) | 1/1 | Valid limitation: (g) is not exactly (9.8\,\text{m s}^{-2}). |

\*Question 4(a) is the only judgement call in the mark total.

## Weaknesses and revision list

### 1. Position vectors and integration constants — Question 1(b)

You integrated the velocity correctly to get the change in position, but treated that change as the position vector. For position, use

\[
\mathbf r(t)=\mathbf r(0)+\int_0^t\mathbf v(\tau)\,d\tau.
\]

Here the integral gives (48\mathbf i-64\mathbf j\), so adding the initial position (-20\mathbf i+20\mathbf j) gives (28\mathbf i-44\mathbf j\,\text{m}).

**Revise:** displacement versus position; applying initial conditions after integration; checking whether a question asks for a position or a displacement.

### 2. Static friction and equilibrium — Question 3(b)

For A to remain at rest, the friction needed to prevent sliding must not exceed its maximum available value:

- downslope component: (2mg\sin\alpha=\frac{10mg}{13}\)
- maximum friction: \(\mu R=\frac23(2mg\cos\alpha)=\frac{16mg}{13}\)

Since \(\frac{16mg}{13}>\frac{10mg}{13}\), friction is sufficient and A remains at rest. Your answer referred to B’s weight, which does not establish this friction condition.

**Revise:** limiting friction (F\leq\mu R); distinguishing actual friction from maximum friction; writing the exact comparison before stating the conclusion.

### 3. Moments and centre of mass — Question 4(c)

With the ramp’s centre of mass closer to A, its weight acts with a shorter moment arm about A. To keep rotational equilibrium, the upward reaction at C must therefore provide a smaller opposing moment, so the reaction at C decreases.

**Revise:** choosing a pivot, comparing moment arms, and predicting how reaction forces change when the centre of mass moves.

### 4. Projectile velocity as a vector — Question 5(a)

You found the horizontal and vertical velocity components and their resultant speed, but the requested velocity also needs its direction. At impact the components are (10\sqrt3\) horizontally and (-9.6\) vertically, so state the speed with its angle **below** the horizontal (about (29^\circ)).

**Revise:** reporting vectors as components, or as magnitude plus direction; identifying whether the object is moving above or below the horizontal.

### 5. Projectile equations and component arithmetic — Question 5(b)

Your horizontal component is set up correctly. In the vertical equation, P is at height (0.4\,\text{m}) at (t=2\), so Q’s vertical displacement equation gives

\[
0.4=2(u\sin\theta)-\tfrac12(9.8)(2^2),
\]

hence (u\sin\theta=10\), not (9.8). Then combine this with (u\cos\theta=25-10\sqrt3\) to obtain approximately \(\theta=52.5^\circ\) and (u=12.6\,\text{m s}^{-1}\).

**Revise:** equating heights at collision; keeping (u\sin\theta) distinct from the full speed (u); checking arithmetic after rearranging SUVAT equations.

## Suggested order

1. Redo Question 5(b), writing separate horizontal and vertical component equations and checking each rearrangement.
2. Practise short static-friction questions using (F\leq\mu R), with an explicit numerical comparison.
3. Review moments when a centre of mass shifts, and predict which support reaction changes.
4. Redo Question 1(b) with the initial position included.
5. Practise giving projectile velocities as a magnitude and direction, including “above/below horizontal”.
