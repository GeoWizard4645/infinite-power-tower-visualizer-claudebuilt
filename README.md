# Infinite Power Tower Visualizer

An interactive, single-file visualization of the infinite power tower (tetration):

$$x^{x^{x^{x^{\cdots}}}} = a$$

Open [`power-tower.html`](power-tower.html) in any browser — no build, no dependencies.

## What it shows

- A **slider** to set the value `a` that the tower converges to.
- Live answers for **`x`, `x²`, and `x³`**.
- A **convergence chart** watching the tower build up level by level (`x`, `x^x`, `x^x^x`, …) until it settles on `a`.
- The **`a = x^(1/x)` map**, with its peak at `x = e` and the fold that creates the famous √2 paradox.
- A full **step-by-step math explanation** beneath the chart.

## The math in one line

If the tower equals `a`, then because the exponent *is* the whole tower again, `x^a = a`, so:

$$x = a^{1/a}, \qquad x^2 = a^{2/a}, \qquad x^3 = a^{3/a}$$

For the classic case `a = 2`: `x = √2`, `x² = 2`, `x³ = 2√2 ≈ 2.828`.

The tower converges only for `e^(-e) ≤ x ≤ e^(1/e)` (equivalently `1/e ≤ a ≤ e`). And the √2 paradox — where `√2^a = a` is solved by both 2 and 4 — resolves to **2**, because only the lower root is a stable attractor.

---

🤖 Built with [Claude Code](https://claude.com/claude-code)
