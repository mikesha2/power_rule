# power_rule
A constructive proof in Lean 3.48.0 of the power rule from calculus.

A great learning experience for me. Polynomial derivatives are defined formally in mathlib, and the proofs are thus non-computable.

Here, I explicitly implement a proof that the function ```x_to_n (x : ℝ) (n : ℕ) := x ^ n``` is differentiable on ℝ, with derivative ```x_to_n' (x : ℝ) (n : ℕ) := n * x ^ n```. This result is encapsulated in the final theorem, ```deriv_of_power```, which states it is Fréchet differentiable on the real line.
