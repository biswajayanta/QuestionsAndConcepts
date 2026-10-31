# CBSE Class 10: Concept Sheet
### Triangles | Circles | Electricity | Carbon and its Compounds | Heredity

*Read this first, then attempt the questions with this sheet closed. Everything here is within the NCERT / CBSE syllabus.*

---

# 1. TRIANGLES (Maths)

## Similar triangles
Two triangles are **similar** if their corresponding angles are equal and their corresponding sides are in the same ratio. Similar means *same shape*, not necessarily the same size. Congruent triangles are always similar, but similar triangles are **not** always congruent.

**Criteria (any one is enough)**
- **AA:** two angles of one triangle equal two angles of the other.
- **SSS:** all three pairs of sides are in the same ratio.
- **SAS:** two pairs of sides are in the same ratio, and the angles *between* them are equal.

## Basic Proportionality Theorem (BPT, or Thales' theorem)
If a line is drawn parallel to one side of a triangle to meet the other two sides, it divides those sides in the **same ratio**.
In △ABC with DE ∥ BC: **AD/DB = AE/EC**.
**Converse:** if a line divides two sides in the same ratio, it is parallel to the third side.

## Areas of similar triangles
The ratio of the areas of two similar triangles equals the **square** of the ratio of their corresponding sides.
ar(△ABC)/ar(△PQR) = (AB/PQ)² = (BC/QR)² = (CA/RP)²
The ratio of the **perimeters** equals the ratio of the sides (no square).

## Pythagoras theorem and its converse
In a right triangle, (hypotenuse)² = (side 1)² + (side 2)².
**Converse:** if in a triangle the square of one side equals the sum of the squares of the other two, the angle opposite the first side is a right angle.

## Where it goes wrong
- Writing corresponding sides in the wrong order. Match the vertices (△ABC ~ △DEF means A↔D, B↔E, C↔F).
- Forgetting to **square** the ratio for areas, or squaring it for perimeters.
- In BPT, writing AD/AB instead of AD/DB. Compare *part to part*, or *part to whole* on both sides, but be consistent.
- In SAS similarity, using an angle that is not between the two proportional sides.
- For shadow and pole problems, not stating *why* the triangles are similar (the sun's angle is the same, and both are vertical to the ground, so **AA**).

---

# 2. CIRCLES (Maths)

- A **tangent** touches the circle at exactly one point (the point of contact). A **secant** cuts it at two points.
- From a point **inside** the circle: **0** tangents. **On** the circle: **1**. **Outside**: **2**.

**Theorem 1:** The tangent at any point of a circle is **perpendicular to the radius** through the point of contact.
*Idea of the proof:* every other point on the tangent lies outside the circle, so the radius to the point of contact is the shortest distance from the centre to the tangent, and the shortest distance is the perpendicular.

**Theorem 2:** The lengths of the two tangents from an external point are **equal**.
*Idea of the proof:* join O to A, B and P. RHS congruence of △OAP and △OBP (right angles at A and B, OA = OB, OP common) gives PA = PB.

**Useful results**
- Tangent length = √(d² − r²), where d is the distance from the point to the centre and r is the radius.
- In quadrilateral OAPB, ∠AOB + ∠APB = 180°.
- A quadrilateral around a circle has **AB + CD = AD + BC**.
- Triangle with an incircle: if the tangent lengths from A, B, C are x, y, z, then the sides are x + y, y + z, z + x.

**Where it goes wrong:** not marking the 90° at the point of contact; forgetting that OP bisects ∠AOB; mixing up which tangent lengths are equal.

---

# 3. ELECTRICITY (Physics)

**Key quantities**

| Quantity | Formula | Unit |
|---|---|---|
| Current | I = Q / t | ampere (A) |
| Potential difference | V = W / Q | volt (V) |
| Ohm's law | V = IR (at constant temperature) | |
| Resistance | R = V / I | ohm (Ω) |
| Resistivity | R = ρl / A | |
| Power | P = VI = I²R = V²/R | watt (W) |
| Heat produced | H = I²Rt | joule (J) |
| Energy | E = Pt; 1 kWh = 3.6 × 10⁶ J | |

**Factors affecting the resistance of a conductor:** directly proportional to its **length**, inversely proportional to its **area of cross-section**, and depends on the **material** (and temperature).

**Series:** same current through all; voltages add; **Rs = R1 + R2 + R3**.
**Parallel:** same p.d. across each; currents add; **1/Rp = 1/R1 + 1/R2 + 1/R3**. The equivalent resistance is *less* than the smallest resistance.
For two resistors in parallel, Rp = R1R2 / (R1 + R2).

**Why household circuits are parallel:** every appliance gets the full voltage, each can be switched on and off independently, and if one fails the others still work.

**Heating effect:** electrical energy turns into heat in a resistor. Heaters, toasters and bulb filaments use this. A **fuse** has a low melting point and breaks the circuit when too much current flows. Tungsten is used for bulb filaments because of its very high melting point.

**Commercial unit of energy:** the kilowatt-hour (kWh). Energy in kWh = power in kW × time in hours.

**Where it goes wrong**
- Using 1/R = 1/R1 + 1/R2 and then forgetting to invert at the end.
- Mixing watts and kilowatts, or minutes and hours, in kWh problems.
- Treating a mixed circuit all at once. Reduce it step by step: combine the parallel part first, then the series part.
- Calling the V–I graph "straight" without saying it passes through the origin.

---

# 4. CARBON AND ITS COMPOUNDS (Chemistry)

**Bonding:** carbon (atomic number 6) has 4 valence electrons. It forms **covalent bonds** by *sharing* electrons, because it cannot easily lose or gain 4 electrons. It shows **tetravalency** and **catenation** (the ability to form long chains, branched chains and rings). That is why there are so many carbon compounds.

**Properties of covalent compounds:** low melting and boiling points (weak forces between molecules) and poor conductors of electricity (no ions).

**Allotropes:** diamond (hard, non-conductor), graphite (soft, conducts electricity), fullerene (C-60, football shape).

**Hydrocarbons**
- Saturated (alkanes): single bonds only, CnH2n+2. Undergo **combustion and substitution**.
- Unsaturated: alkenes (double bond, CnH2n) and alkynes (triple bond, CnH2n−2). Undergo **addition** reactions.
- **Isomers:** same molecular formula, different structures (butane has 2).

**Homologous series:** a family with the same functional group and the same general formula. Successive members differ by **−CH2−** (14 u). Physical properties change gradually (boiling point increases down the series).

**Naming (IUPAC):** word root (meth, eth, prop, but, pent, hex) + suffix.

| Group | Formula | Suffix |
|---|---|---|
| Alcohol | –OH | -ol |
| Aldehyde | –CHO | -al |
| Ketone | >C=O | -one |
| Carboxylic acid | –COOH | -oic acid |
| Halo | –Cl, –Br | chloro-, bromo- |

**Reactions**
- **Combustion:** hydrocarbon + O2 → CO2 + H2O (+ heat and light).
- **Oxidation:** alcohol → carboxylic acid with alkaline KMnO4 or acidified K2Cr2O7.
- **Addition:** CH2=CH2 + H2 → CH3–CH3 (nickel catalyst). Used to make vegetable ghee from oils.
- **Substitution:** CH4 + Cl2 → CH3Cl + HCl (in sunlight).

**Ethanol:** reacts with sodium to give hydrogen. Heated with conc. H2SO4 at 443 K it gives **ethene** (dehydration).
**Ethanoic acid:** turns blue litmus red. Reacts with carbonates and hydrogencarbonates to release **CO2** (which turns limewater milky), and with bases (neutralisation).
**Esterification:** acid + alcohol, with conc. H2SO4, gives an ester (sweet, fruity smell).
**Saponification:** ester + NaOH → alcohol + sodium salt of the acid (this is how soap is made).

**Soaps and detergents:** soaps are sodium or potassium salts of long-chain carboxylic acids. A soap molecule has a **hydrophilic (ionic) head** and a **hydrophobic (hydrocarbon) tail**. In water the tails surround oily dirt and the heads face the water, forming a **micelle** that lifts dirt away. Soaps form scum with hard water (Ca and Mg salts). Detergents (sulphonate salts) do not.

**Where it goes wrong:** missing a bond in structural formulas (every carbon needs exactly four); forgetting that unsaturated hydrocarbons give addition and saturated ones give substitution; not balancing equations; forgetting the catalyst or conditions.

---

# 5. HEREDITY (Biology)

**Variation and inheritance:** offspring resemble parents (inheritance) but are not identical (variation). Variation helps the **species** survive when the environment changes.
**Inherited traits** pass through DNA of germ cells. **Acquired traits** develop in a lifetime and are **not inherited** (they do not change the DNA of germ cells).

**Mendel's work (pea plant)**
- Dominant trait: expressed even with one allele. Recessive: expressed only when both alleles are recessive.
- **Monohybrid:** pure tall (TT) × pure dwarf (tt) → F1 all Tt, tall → F2 **3 tall : 1 dwarf** (genotypic **1 : 2 : 1**).
- **Dihybrid:** round yellow (RRYY) × wrinkled green (rryy) → F1 all round yellow → F2 **9 : 3 : 3 : 1**. The new combinations (round green, wrinkled yellow) show that traits are **inherited independently**.
- Dominance is read from the **F1**. The F2 ratio and new combinations show **independent inheritance**. Answer what the question asks.

**The gamete rule (the most common slip):** a gamete carries **half** the chromosomes: **one** from each pair. So TT gives only T, Tt gives T and t, XX gives only X, XY gives X and Y, and RrYy gives RY, Ry, rY and ry. A human body cell has 46 chromosomes, and the egg and sperm each have 23.

**Flow diagram (as in NCERT):**
Parents → gametes → F1 → F1 gametes → F2 (genotypes and phenotypes) → ratio.

**Sex determination in humans:** 22 pairs of autosomes and 1 pair of sex chromosomes. Female XX, male XY. Every egg carries X. Sperms carry X or Y in equal numbers. X sperm gives a girl (XX) and Y sperm gives a boy (XY). The **father's sperm decides** the sex, and each birth has a **1/2** chance of either.

**Gene and trait:** a gene is a segment of DNA that carries the information to make a **protein** (for example, an enzyme). The enzyme helps make a plant hormone, and the amount of hormone decides tallness. An efficient enzyme gives more hormone, so the plant is tall. A less efficient enzyme gives less hormone, so the plant is dwarf.

**Where it goes wrong:** labelling an egg "XX" or a sperm "XY"; skipping the gamete line in flow diagrams; confusing "tall" with "pure tall"; giving the wrong conclusion for dihybrid ratios.
