---
title: Practice Scenario – Prosthetics
---

# Practice Scenario: Prosthetics

[Home](./) · [1. Research](research.md) · [2. Design](design.md) · [3. Plan](plan.md) · [4. Present](present.md) · [Skills](skills.md) · [Practice](practice.md) · **Prosthetics**

This is a **made-up practice scenario**, not a real City & Guilds brief. It shows how to apply the ESP method to a prosthetics brief. Anything in **[square brackets]** is a detail that would come from the real brief. Use the **🔍 searches** to do the general research yourself.

---

## The practice brief (outline)

> A UK medical engineering company, **[company name]**, has been asked by **[client, e.g. an NHS trust or a charity]** to design a **[type, e.g. below-knee prosthetic leg / prosthetic hand / sports blade]** for **[user group, e.g. adults / children / low-income regions]**.
>
> The design must:
> - support **[user mass, e.g. up to X kg]** and **[activity, e.g. everyday walking / running]**
> - be adjustable or fitted to **[the residual limb / growth range]**
> - use **[recycled / sustainable / low-cost]** materials where possible
> - cost no more than **[£ per unit]**, with **[number]** units a year
> - be delivered within **[number] weeks**

**First step, just like the real ESP:** build your requirements table.

| Requirement | Value from brief | How I'll research it |
|---|---|---|
| Prosthesis type | [ ] | |
| User mass / load | [ ] | |
| Activity level | [ ] | |
| Budget per unit | [ ] | |
| Quantity / year | [ ] | |
| Timescale | [ ] | |
| Sustainability | [ ] | |
| Any tech (sensors, motors) | [ ] | |

---

## Task 1: Research (3 hrs, 15 marks)

Research each area, **write down the numbers**, and link every fact to the brief. You won't have the internet in Tasks 2 and 3.

### 1. Types of prosthesis
- 🔍 `transtibial vs transfemoral prosthesis components`
- 🔍 `body-powered vs myoelectric prosthetic hand comparison`
- 🔍 `prosthetic leg components socket pylon foot`

### 2. Materials (compare at least 3)
- 🔍 `carbon fibre vs titanium vs aluminium prosthetic pylon`
- 🔍 `prosthetic socket materials thermoplastic carbon composite`
- 🔍 `prosthetic liner materials silicone gel`
- 🔍 `density yield strength cost table aluminium 6061 titanium Ti-6Al-4V carbon fibre`
- 🔍 `recycled or bio-based materials prosthetics sustainability`

**Note down:** density, yield strength, Young's modulus, cost per kg and recyclability.

### 3. Manufacturing methods
- 🔍 `3D printed prosthetic socket FDM SLS`
- 🔍 `CNC machined prosthetic adapters pyramid connector`
- 🔍 `low cost prosthetics manufacturing developing countries`

### 4. Technology (if the brief includes it)
- 🔍 `myoelectric sensor EMG how it works prosthetic`
- 🔍 `prosthetic hand motor torque grip force typical values`
- 🔍 `microprocessor knee how it works`
- 🔍 `prosthetic hand battery life capacity`

### 5. User needs and ergonomics
- 🔍 `prosthetic socket fit comfort pressure points`
- 🔍 `gait cycle forces walking multiple of body weight`
- 🔍 `prosthetic alignment adjustment pyramid adapter`
- 🔍 `prosthesis weight recommendations user fatigue`

### 6. Standards and regulations
- 🔍 `ISO 10328 structural testing lower limb prostheses`
- 🔍 `ISO 22523 external limb prostheses requirements`
- 🔍 `ISO 13485 medical devices quality management`
- 🔍 `ISO 14971 medical device risk management`
- 🔍 `ISO 10993 biocompatibility skin contact`
- 🔍 `UK Medical Devices Regulations 2002 UKCA marking class I`

### 7. Existing products (analyse 2–3)
- 🔍 `Össur prosthetic foot range`
- 🔍 `Ottobock prosthetic products`
- 🔍 `open source prosthetic hand e-NABLE`

For each, note what works, what doesn't and the approximate cost.

**Reference everything** in Harvard style as you go.

---

## Task 2: Design (8 hrs, 24 marks)

### Concept ideas to sketch (pick 2–3)
- A modular design with a **standard pyramid adapter**, so parts can be swapped or adjusted
- A **3D-printed socket** with a **machined metal pylon**
- An **adjustable-length pylon** (good for growth or alignment)
- For hands: **body-powered** vs **myoelectric** vs **passive** concept

**Annotate:** materials (with reasons), connection points, adjustment features, the liner/socket interface, weight-saving features, cleaning and maintenance, and the link to each brief requirement.

### Calculation templates (fill in from your research and the brief)

**Pylon compressive stress**
- Peak load: F = [user mass] × 9.81 × [dynamic factor from your gait research]
- Pylon area (tube): A = π/4 × (D² − d²), where D = [outer dia] and d = [inner dia]
- Stress: σ = F ÷ A
- Factor of safety: FoS = [yield strength] ÷ σ

**Pylon bending (heel strike / toe-off)**
- Bending moment: M = F × [offset distance]
- Second moment of area (tube): I = π/64 × (D⁴ − d⁴)
- Bending stress: σ = M × (D/2) ÷ I

**Buckling check (long pylon)**
- Euler: F_crit = π² E I ÷ (K L)², with L = [pylon length]

**Myoelectric hand (if relevant)**
- Grip force from torque: F = T ÷ r
- Battery life: hours = battery Wh ÷ average power W

🔍 `Euler buckling formula effective length factor`
🔍 `second moment of area hollow tube formula`

### Final CAD drawing
- Orthographic views + an exploded isometric of the assembly
- A **parts list** (socket, liner, adapter, pylon, foot or hand, fixings)
- Dimensions and tolerances on the **connection interfaces**
- Material and finish notes

### Evaluation
Go requirement by requirement: met / partly met / not met. Think about **comfort, weight, cost, durability and adjustability**.

---

## Task 3: Plan (5 hrs, 18 marks)

### Stages specific to a medical device
1. Design sign-off *(milestone)*
2. Prototype manufacture
3. **Mechanical testing** to the structural standard
4. **User trials / clinical evaluation** with prosthetists
5. Design changes
6. **Regulatory approval**: technical file, risk management, UKCA marking *(milestone)*
7. Procurement (carbon fibre, titanium, electronics, liners)
8. Batch production: [units] ÷ [rate per week] = [weeks]
9. Quality inspection with **traceability** (batch and serial numbers)
10. Distribution to clinics
11. **Patient fitting and alignment** by prosthetists
12. Contingency

🔍 `medical device development process stages UK`
🔍 `medical device technical file contents`

### Supporting statement: things to search and cover
- **H&S:** composite dust (🔍 `carbon fibre machining dust COSHH`), resin and epoxy hazards, CNC (PUWER), 3D printer fumes
- **Quality:** 🔍 `ISO 13485 traceability requirements`, cleanroom or clean assembly if needed
- **Waste:** 🔍 `carbon fibre composite recycling`, 🔍 `3D printing PLA waste recycling`, WEEE for electronics, battery disposal
- **Assumptions:** shifts, lead times, number of prosthetists available

---

## Task 4: Present (2 hrs prep + 30 min)

**Slide plan:** brief → user needs → research highlights → challenge 1 (strength vs weight) → challenge 2 (comfort / fit) → challenge 3 (cost / tech) → concepts and decision matrix → final design → calculations → materials and sustainability → cost → manufacturing plan → regulation and testing → evaluation → improvements.

### Likely questions to prepare for
- "How do you know it's strong enough for a heavier or more active user?"
- "How does the socket fit different residual limbs?"
- "What testing would it need before patients use it?"
- "How would you make it cheaper for low-income regions?"
- "How easy is it to repair or replace parts?"
- "Why not use 3D printing for everything?"
- "What happens at end of life?"

---

## Extra searches for background understanding

- 🔍 `how prosthetic legs work explained`
- 🔍 `osseointegration prosthesis pros and cons`
- 🔍 `role of a prosthetist NHS`
- 🔍 `prosthetics engineering careers UK`
- 🔍 `targeted muscle reinnervation prosthetics`

> **Reminder:** this page is for **practice**. In the real ESP, write everything in your own words for the actual brief.
