# Volume 1, Chapter 2: Basic Physics

Atoms and (quantum) electro dymamics.

Lectures are from early 60s. 
Quantum electro dynamics QED is well understood, but a lot is not known about nuclear physics.
No standard model, no quarks.

He says no direct observation of oscillations above 1E12 Hz (1 tera Hz).

Examples:

* Visible light is 5E14 - 1E15 Hz (just one "octave"). 500-1000 tera Hz or 0.5 to 1 peta Hz.
* 2 grains of sand 1 mm across, 30 m apart. If no cancellation of electrical charge, force would be 3E6 tons.
* Uncertainty principle: \delta x \delta p >= \hbar/2

Some modern constants:

* Visible light: 400-800 THz or 700 - 350 nm
* Light speed: 3.0E8 m/s
* Planck constant \h, Dirac constant \hbar = 1.05E-34 Js
* Electron mass m_e = 9.1E-31 kg
* Electron charge: 1.6E-19C
* Coulombs law: F = 9.0E9 Nm²/C² * q1*q2 / r²
* Uncertainty principle: $ \sigma_x \sigma_p \ge \hbar / 2 $
* Centripetal force F = m v² / r 

| Prefix | Name | Multiplier |
| --- | --- | --- |
| T | tera | 1E12

Light: 500 THz = 500E12 Hz. 
Speed = Wavelength * frequency => Wavelangth = Speed/freq. Eg 3E8m/s / (5E14/s) = 6E-7 m = 600 nm

# Examples

## "Classical atom"

What is the expected size of a hydrogen atom from classical mechanics + uncertainty principle?

Use atom radius $r$ as \sigma_x and p as \sigma_p in uncertaintly principle.
Then we get:

r * p = \hbar/2 = 0.5E-34 Js.
p = m_e * v => v = 5E-35 Js / r / m_e

Coulomb force: F_C = 9.0E9 Nm²/C² * (1.6E-19C)² / r² = 2.3E-28 Nm² / r²

Centripetal force: F_c = m_e * v² / r

Setting F_C = F_c, we get:

m_e * v² / r = 2.3E-28 Nm² / r² <=> m_e v² = 2.3E-28 Nm² / r

Enter v from uncertainty: v = \hbar/2 / r / m_e to get:

(\hbar/2)² /r² /m_e = 2.3E-28Nm / r <=> 
(5E-35 Js)² / m_e / (2.3E-28 Nm) = r = (5E-35 Js)² / 9.1E-31 kg /  (2.3E-28 Nm) = 1.2E-11 m

