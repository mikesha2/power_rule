# power_rule
A constructive proof in Lean 3.48.0 of the power rule from calculus.

A great learning experience for me. Polynomial derivatives are defined formally in mathlib, and the proofs are thus are non-computable.

Here, I explicitly implement a proof that the function ```f (x : ℝ) (n : ℕ) := x ^ n``` is differentiable on ℝ, 
with derivative ```f' (x : ℝ) (n : ℕ) := n x ^ n```