---
title: Maths, English & Digital
---

# Maths, English & Digital (AO4)

[Home](./) · [1. Research](research.md) · [2. Design](design.md) · [3. Plan](plan.md) · [4. Present](present.md) · **Skills** · [Practice](practice.md)

**Marks:** 9 (3 each), judged across **all** tasks.

| Skill | Top band |
|---|---|
| Maths (AO4a) | Accurate calculations in the correct format, with evidence of checking |
| English (AO4b) | Fluent and accurate throughout, and clearly audible in the presentation |
| Digital (AO4c) | Digital tools used effectively, the way industry would, adding real value |

---

## How to set out any calculation

1. **State what you're finding**, e.g. "Maximum horizontal impact force on the bollard"
2. **State assumptions**, e.g. vehicle mass, speed, stopping distance or time
3. **Write the formula** in symbols
4. **Substitute values with units**
5. **Work through it step by step**
6. **Give the answer** with units and sensible significant figures
7. **Sense-check:** is it realistic? What does it mean for the design?

## Worked example: vehicle impact force

**Assumptions:** a car of mass *m* = 1,500 kg at 30 mph (≈ 13.4 m/s) hits the bollard and stops over a deformation distance *d* = 0.5 m.

**Method 1: energy (work done)**

- Kinetic energy: KE = ½ *m v*² = 0.5 × 1500 × 13.4² = **134,670 J** (≈ 135 kJ)
- Work done = force × distance, so F = KE ÷ d = 134,670 ÷ 0.5 = **269,340 N ≈ 269 kN**

**Method 2: impulse (change in momentum)**

- Assume the stop takes *t* = 0.1 s
- F = *m* Δ*v* ÷ *t* = 1500 × 13.4 ÷ 0.1 = **201,000 N ≈ 201 kN**

**Sense-check:** both methods give roughly 200–270 kN, which is a realistic order of magnitude for a car impact. Design for the **worst case** and add a factor of safety.

**Taking it further (extra AO2 marks):**

- Bending moment at the base: M = F × h. With impact at h = 0.5 m above ground: 269 kN × 0.5 m ≈ **135 kNm**
- Bending stress: σ = M y ÷ I. Compare it with the material's yield strength to check the section size
- Factor of safety: FoS = yield strength ÷ working stress (aim for at least 1.5–2)

## Other useful formulas

| Quantity | Formula |
|---|---|
| Stress | σ = F ÷ A |
| Strain | ε = ΔL ÷ L |
| Young's modulus | E = σ ÷ ε |
| Power | P = V × I |
| Energy (electrical) | E = P × t (Wh = W × h) |
| Battery capacity | Ah = Wh ÷ V |
| Solar panel size | W = daily Wh needed ÷ peak sun hours (winter UK ≈ 1) |
| LED power | W = lumens ÷ efficacy (lm/W) |
| Unit cost | total cost ÷ number of units |
| Production weeks | total units ÷ units per week |

**Example energy budget:** a 600 lm LED at 120 lm/W needs 5 W. Over 14 hours of winter darkness that's 70 Wh a day. Add the sensor and controller (say 1 W × 24 h = 24 Wh), giving ≈ 94 Wh a day. Allow 3 days with no sun (autonomy), so the battery needs ≈ 282 Wh, which is ≈ 23.5 Ah at 12 V.

---

## English tips

- Use headings, short paragraphs and full sentences
- Use technical vocabulary correctly
- Proofread for spelling and grammar in the last 10 minutes of every session
- In the presentation, speak clearly, at a steady pace and facing the camera or audience

## Digital tips

- CAD (e.g. Fusion 360, SolidWorks, AutoCAD, Onshape) for the final drawing
- Excel or Project for the Gantt chart and decision matrices
- PowerPoint with your own visuals
- **Name files clearly**, e.g. `Surname_Task2_FinalCAD.pdf`
