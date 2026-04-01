
---

## 21. Unified Quantity Map (Minimal Set)
We now state a **minimal, non-redundant set of basic quantities** and their role in
this framework, keeping the model as lean as possible while remaining physically
meaningful.

**Core set:**
- **Time (\(\mathcal{T}\))**: complex parameter (model core).
- **Length (\(L\))**: spatial scale used in measurements.
- **Mass (\(M\))**: inertia scale (links to energy).
- **Temperature (\(T\))**: thermodynamic scale (imaginary-time period).
- **Charge (\(Q\))**: interaction tag (kept minimal, not expanded).

Derived quantities (kept implicit): energy, momentum, entropy.

---

## 22. Unified Scaling Laws
We introduce a compact scaling structure that ties the core quantities together.

1. **Temporal scale:**
\[
\mathcal{T}(v)=M(v)e^{i\theta(v)}.
\]
2. **Thermal scale:**
\[
\beta=\frac{1}{k_B T},\quad \text{and}\quad T_{\mathrm{eff}}(v)=\frac{\hbar}{k_B M(v)}.
\]
3. **Spatial measurement:** any circumference measurement at resolution \(h\) yields
\(
\pi_h\in\mathbb{Q}
\) with \(\pi_h\to\pi\) as \(h\to 0\).

This defines a **three-axis scaling**: speed \(v\) rotates time, resolution \(h\)
controls spatial approximation, and temperature fixes the imaginary-time period.

---

## 23. Minimal Consistency Diagram (Textual)

- **Speed \(v\)** controls **phase** \(\theta\) of complex time.  
- **Temperature \(T\)** controls **modulus** \(M(v)\) via \(\beta\).  
- **Spatial resolution \(h\)** controls **rational approximation** of \(\pi\).  

Together they determine a **self-consistent measurement triple**:
\[
(v, T, h) \;\Rightarrow\; (\theta, M, \pi_h).
\]

---

## 24. Canonical Universe Model (Unified)
Combine the complex-time framework with Euclidean measurement:

1. **Space:** Euclidean geometry at lab scales.
2. **Time:** complex time \(\mathcal{T}(v)\) with \(\theta(0)=0\), \(\theta(c)=\pi/2\).
3. **Temperature:** \(T\) maps to imaginary-time period \(\beta\hbar\).
4. **Measurement:** finite resolution \(h\) yields rational \(\pi_h\to\pi\).

This produces a **single, coherent universe model** that:  
- Preserves relativistic structure locally.  
- Embeds temperature directly into time structure.  
- Keeps spatial geometry Euclidean while allowing rational finite measurements.

---

## 25. Next Formal Step: Toy Field Theory
To elevate the model from conceptual to predictive, define a toy field theory on
complex time:
\[
S_E=\int_0^{\beta\hbar} d\tau\int d^d x\;\left[\frac{1}{2}(\partial_\tau\phi)^2+\frac{1}{2}(\nabla\phi)^2+\frac{m^2}{2}\phi^2\right].
\]
Then replace \(\tau\) with the complex-time parameterization \(\mathcal{T}(v)\), and
study how correlators and spectra shift as \(v\) varies.

This is the immediate bridge to predictions.
