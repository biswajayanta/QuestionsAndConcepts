# Set 03 — Concepts & Solutions (Parent's Copy)

---

## M1. Statistics — missing frequencies from mean

**Core concept:** With two unknown frequencies, you need two independent equations: (1) all frequencies must sum to the given total, and (2) the mean formula (Σfx / Σf = mean) using class midpoints. Solving the resulting simultaneous equations gives both unknowns.

**Where it usually goes wrong:** Trying to find x and y from the total-frequency equation alone (which only gives x+y, not each individually) — the mean equation is essential and is often skipped or set up incorrectly with wrong midpoints.

**Correct approach:**
1. Midpoints: 10, 30, 50, 70, 90.
2. Total frequency: 5+x+10+y+7 = 50 → x+y = 28.
3. Mean equation: (5×10 + x×30 + 10×50 + y×70 + 7×90) / 50 = 58
   → 50 + 30x + 500 + 70y + 630 = 2900
   → 30x + 70y = 1720 → 3x + 7y = 172
4. Substitute x = 28−y: 3(28−y) + 7y = 172 → 84 + 4y = 172 → y = 22, x = 6.

**Final answer:** x = 6, y = 22.

---

## M2. Arithmetic Progressions

**Core concept:** Express each given term as a+(n−1)d, form two linear equations in a and d from the given sums, and solve simultaneously.

**Where it usually goes wrong:** Miscounting the term index (using n instead of n−1 in the formula), or algebra slips when eliminating one variable.

**Correct approach:**
1. a₄+a₈ = (a+3d)+(a+7d) = 2a+10d = 46 → a+5d = 23.
2. a₆+a₁₀ = (a+5d)+(a+9d) = 2a+14d = 62 → a+7d = 31.
3. Subtract: 2d = 8 → d = 4. Then a = 23−20 = 3.
4. S₁₅ = 15/2 × [2a+14d] = 15/2 × [6+56] = 15/2 × 62 = 15×31 = **465**.

**Final answer:** a = 3, d = 4; S₁₅ = 465.

---

## M3. Trigonometric identity

**Core concept:** Convert cot, cosec, tan, sec into sin/cos, combine each bracket into a single fraction, and use s²+c²=1 to simplify the product.

**Where it usually goes wrong:** Trying to expand the product term-by-term directly (messy, error-prone) instead of first simplifying each bracket into one fraction over a common denominator.

**Correct approach (let s=sinθ, c=cosθ):**
1. First bracket: 1 + c/s − 1/s = (s+c−1)/s.
2. Second bracket: 1 + s/c + 1/c = (c+s+1)/c.
3. Product = (s+c−1)(s+c+1) / (sc) = [(s+c)²−1] / (sc)
4. (s+c)² = s²+2sc+c² = 1+2sc (using s²+c²=1). So [(s+c)²−1] = 1+2sc−1 = 2sc.
5. Product = 2sc/(sc) = **2**. Hence proved.

**Final answer:** Proved as above.

---

## M4. Quadratic Equations — speed/time word problem

**Core concept:** Translate the word problem into an equation using time = distance/speed, being careful with the "3 hours less" relationship, which produces a quadratic once cleared of fractions.

**Where it usually goes wrong:** Setting up the equation with the wrong sign (adding instead of subtracting the time difference), or losing track of which unknown represents speed vs. time.

**Correct approach:**
1. Let original speed = x km/h. Time taken = 480/x hours.
2. New speed = x+8; new time = 480/x − 3 (3 hours less).
3. New speed × new time = same distance: (x+8)(480/x − 3) = 480.
4. Expand: 480 − 3x + 3840/x − 24 = 480 → −3x + 3840/x − 24 = 0.
5. Multiply through by x: −3x² + 3840 − 24x = 0 → 3x² + 24x − 3840 = 0 → x² + 8x − 1280 = 0.
6. Discriminant = 64 + 5120 = 5184 = 72². x = (−8+72)/2 = 32 (rejecting the negative root, since speed can't be negative).

**Final answer:** Original speed = 32 km/h.

---

## P1. Electricity — series vs. parallel power

**Core concept:** With the same voltage applied across a combination, power = V²/R_equivalent. Series and parallel combinations of the same two resistors have very different equivalent resistances, so power consumed differs a lot — this tests whether the "same battery, different R" logic is clear.

**Where it usually goes wrong:** Using P=I²R with a fixed current instead of realizing the current itself changes because R_equivalent changes; or forgetting parallel resistance is always smaller than either individual resistor.

**Correct approach:**
1. Series: R = 4+6 = 10Ω. P = V²/R = 144/10 = **14.4 W**.
2. Parallel: 1/R = 1/4+1/6 = 3/12+2/12 = 5/12 → R = 12/5 = 2.4Ω. P = V²/R = 144/2.4 = **60 W**.
3. Ratio (parallel:series) = 60/14.4 = **25/6 ≈ 4.17**.

**Final answer:** Series: 14.4 W; Parallel: 60 W; Ratio ≈ 25:6.

---

## P2. Electricity — Joule heating and a "cutting the element" trap

**Core concept:** Resistance of a wire is proportional to its length (R ∝ L). Cutting a heating element in half halves its resistance — and since power at fixed voltage is P=V²/R, *halving* resistance *doubles* power. This directly contradicts the common intuition that "using half the heater gives half the power."

**Where it usually goes wrong:** Assuming cutting the element in half automatically halves the power (a very natural but incorrect intuition) — the correct reasoning requires explicitly using P=V²/R and recognizing R itself has dropped.

**Correct approach:**
1. (a) I = P/V = 1100/220 = **5 A**. R = V/I = 220/5 = **44 Ω** (equivalently V²/P = 48400/1100 = 44Ω).
2. (b) Energy per day = 1100 W × 4 h = 4400 Wh = 4.4 kWh. Over 30 days: 4.4×30 = 132 kWh. Cost = 132 × ₹6 = **₹792**.
3. (c) Cutting the element in half halves its resistance (length halved → R halved): new R = 22Ω. New power at same 220V: P = V²/R = 48400/22 = **2200 W** — which is **double** the original power, not half. This happens because resistance dropped, allowing more current to flow, and power depends on 1/R at fixed voltage.

**Final answer:** (a) 5A, 44Ω. (b) ₹792. (c) Power roughly doubles to 2200W — more, not less, than before.

---

## P3. Magnetic effects — right-hand rule and force between parallel currents

**Core concept:** The right-hand thumb rule gives the direction of magnetic field circles around a current-carrying wire. Two parallel wires carrying current in the same direction attract each other — a standard but often-misremembered fact (students frequently guess it should be the opposite, by loose analogy with magnetic poles).

**Where it usually goes wrong:** Getting the field direction backwards (clockwise vs anticlockwise) when current direction is "out of the page" rather than the more commonly drawn "into the page," and/or guessing the attract/repel result rather than reasoning it through with Fleming's left-hand rule.

**Correct approach:**
1. (a) Right-hand thumb rule: point the thumb in the direction of current (out of the page, toward the reader); the curled fingers show field direction. For current out of the page, the field circles are **anticlockwise** as seen by the reader.
2. (b) Take the field created by conductor 1 at the location of conductor 2 (anticlockwise circles around conductor 1 mean, at conductor 2's position, the field points in a specific direction — work this out from the anticlockwise circle pattern). Applying Fleming's left-hand rule to conductor 2 (carrying current out of the page, in this field) gives a force directed *toward* conductor 1. By Newton's third law, conductor 1 experiences an equal and opposite force toward conductor 2. So the two conductors **attract** each other. (General rule to remember: like currents attract, unlike currents repel — the opposite of what many people guess by loose analogy with magnetic poles.)

**Final answer:** (a) Anticlockwise. (b) They attract.

---

## P4. Lenses — real image vs. magnifying-glass case

**Core concept:** For a convex lens, an object placed beyond the focal length produces a real, inverted image; an object placed *within* the focal length produces a virtual, erect, magnified image (the same principle behind a simple magnifying glass). This question tests both cases with the same lens.

**Where it usually goes wrong:** Using the same sign/logic for both cases without noticing that moving the object inside the focal length fundamentally changes the nature of the image (virtual instead of real) — and forgetting that a virtual image from a converging lens is always enlarged, which is why no full magnification recalculation is even needed.

**Correct approach:**
1. (a) u = −30, f = +20 (convex). 1/v − 1/u = 1/f → 1/v = 1/f + 1/u = 1/20 + (−1/30) = (3−2)/60 = 1/60 → v = **+60 cm**. Real image (positive v), on the opposite side. Magnification m = v/u = 60/(−30) = **−2**; image height = 4×(−2) = **−8 cm** (inverted, 8 cm tall, magnified). This matches the standard case: object between F and 2F → real, inverted, magnified image beyond 2F.
2. (b) u = −15 (now inside the focal length of 20 cm). 1/v = 1/f + 1/u = 1/20 + (−1/15) = (3−4)/60 = −1/60 → v = **−60 cm**. Negative v means the image is **virtual**, on the same side as the object. m = v/u = (−60)/(−15) = **+4** (positive → erect).
3. Qualitative reasoning for why it's enlarged: whenever the object is placed between the lens and its focal point, the refracted rays diverge (rather than converging to a real point), and they only *appear* to come from a point on the same side — this is always a magnified, erect, virtual image for a convex lens (the working principle of a magnifying glass), regardless of the exact object distance within that range.

**Final answer:** (a) v=+60cm, real, inverted, magnified (×2), height 8cm. (b) v=−60cm, virtual, erect, magnified — the "magnifying glass" case, since object is within the focal length.

---

## C1. Corrosion protection — sacrificial anode

**Core concept:** A more reactive metal coating (zinc on iron) corrodes preferentially even after a scratch, protecting the less reactive metal underneath — this only works because zinc is *more* reactive than iron. A *less* reactive coating (like tin) does the opposite: at a scratch, the exposed iron becomes the more reactive metal locally and corrodes faster than if there were no coating at all.

**Where it usually goes wrong:** Treating "galvanization prevents rust" as a fact to memorize rather than understanding the reactivity-based mechanism — which is exactly why the tin-coating contrast case in part (b) often trips students up.

**Correct approach:**
1. (a) Zinc is more reactive than iron. When moisture/air reach the scratch, zinc (being more reactive) corrodes preferentially instead of iron — zinc acts as a "sacrificial" metal, continuing to protect the iron even around the scratch, because it's chemically more willing to react/oxidize than iron is.
2. (b) Tin is *less* reactive than iron. At a scratch with a tin coating, the exposed iron becomes the more reactive metal present, so iron corrodes preferentially and rapidly at that specific spot — actually accelerating localized rusting compared to bare, uncoated iron (which would rust more slowly and more evenly, without this concentrated effect).
3. (c) This mechanism is called **sacrificial protection** (also called cathodic protection).

**Final answer:** (a) Zinc corrodes instead of iron (more reactive). (b) Tin coating worsens rusting at a scratch because exposed iron becomes the more reactive/anodic metal there. (c) Sacrificial protection.

---

## C2. Carbon compounds — alcohol vs. a non-oxidizable isomer

**Core concept:** This previews organic chemistry slightly beyond typical Class 10 depth (structural isomers and functional group reactivity), but builds directly on the standard CBSE reaction: primary alcohols are oxidized by acidified potassium dichromate (color change orange → green, as Cr₂O₇²⁻ is reduced to Cr³⁺), while other C₃H₈O isomers without a free −OH group (like an ether) resist this oxidation entirely.

**Where it usually goes wrong:** Not recognizing that the color change itself (orange→green) is diagnostic of dichromate being *reduced*, which means oxidation happened elsewhere in the reaction (in compound A) — and not realizing two compounds can share a molecular formula while having completely different reactive functional groups.

**Correct approach:**
1. (a) Orange-to-green indicates the dichromate ion has been reduced (Cr₂O₇²⁻, orange, to Cr³⁺, green) — this only happens if something else in the mixture is simultaneously oxidized. Compound A must contain an **−OH (alcohol)** group, which is oxidized under these conditions.
2. (b) Compound B, despite sharing the formula C₃H₈O, must lack a free −OH group in an oxidizable position — it is a different type of compound altogether (a structural/functional isomer), such as an ether, which does not undergo this oxidation reaction under these mild conditions.
3. (c) Compound A is **propan-1-ol** (1-propanol), a primary alcohol, which oxidizes to propanoic acid.

**Final answer:** (a) Alcohol (−OH) group, oxidation occurring. (b) B lacks a free −OH; likely a different functional isomer (e.g. an ether). (c) Propan-1-ol.

---

## C3. Chemical reactions — a reaction that's two types at once

**Core concept:** Reaction-type categories (combination, decomposition, displacement, double displacement, redox, exothermic/endothermic) aren't mutually exclusive — many reactions genuinely belong to more than one category simultaneously. This particular reaction (the thermite reaction) is both a displacement reaction AND a redox reaction at the same time.

**Where it usually goes wrong:** Treating reaction-type labels as if only one can apply, and picking just one (usually "displacement") without recognizing the redox classification applies equally and for a distinct reason.

**Correct approach:**
1. (a) Balanced equation: **Fe₂O₃ + 2Al → Al₂O₃ + 2Fe**.
2. (b) This is a **displacement reaction**: aluminium (more reactive) displaces iron from its oxide, Fe₂O₃. It is *also* a **redox reaction**: aluminium is oxidized (loses electrons, Al → Al³⁺), while iron in Fe₂O₃ is reduced (Fe³⁺ gains electrons to become Fe). The key teaching point: most displacement reactions of this kind are simultaneously redox reactions — oxidation and reduction happening together is exactly *why* the displacement occurs. (This reaction is also known as the thermite reaction, and is strongly exothermic — releasing enough heat to melt the iron produced, which is why it's used for welding railway tracks.)

**Final answer:** Balanced equation as above; the reaction is both a displacement reaction and a redox reaction, for the reasons explained.

---

## C4. Periodic Classification — Modern table and Mendeleev's predictive method

**Core concept:** Atomic number 14 = Silicon (Period 3, Group 14), a metalloid. This question also tests understanding of *how* Mendeleev's table could predict properties of undiscovered elements — by interpolating from neighbouring elements' known properties (a genuinely important historical/conceptual point, not just table lookup).

**Where it usually goes wrong:** Correctly identifying the element but only describing Mendeleev's method vaguely ("he predicted properties") without explaining the actual interpolation logic (using neighbours above/below and left/right).

**Correct approach:**
1. (a) Atomic number 14 → **Silicon**, Period 3, Group 14. Silicon is a **metalloid** — it has properties intermediate between metals and non-metals (e.g., it's a semiconductor), consistent with its position between the non-metallic carbon (above it in Group 14) and metallic germanium/tin/lead (below it).
2. (b) Mendeleev's method: he examined the elements immediately above and below the gap (in the same group) and to the left and right (in the same period), and interpolated/averaged their properties. For element X (silicon) if undiscovered: looking at carbon (above, Group 14, valency 4, forms CO₂) and germanium (below, Group 14, similar valency, forms GeO₂), he would predict X to have a **valency of 4** and form an oxide of formula **XO₂**; he would also predict its **atomic mass roughly midway** between carbon's and germanium's, and a degree of metallic character between carbon (more non-metallic) and germanium (more metallic) — i.e., intermediate/metalloid-like behaviour.

**Final answer:** (a) Silicon, Period 3, Group 14, metalloid. (b) Predicted via interpolation from neighbouring elements (carbon above, germanium below): valency 4, oxide formula XO₂, intermediate atomic mass, intermediate metallic character.

---

## B1. Heredity — test cross and genotype inference

**Core concept:** A cross between a dominant-phenotype individual of unknown genotype and a homozygous recessive individual (a "test cross") reveals the unknown genotype through the offspring ratio: a 1:1 ratio indicates heterozygous (Tt), while an all-dominant result indicates homozygous dominant (TT).

**Where it usually goes wrong:** Assuming a tall parent must automatically be TT, without using the offspring ratio as evidence — this question specifically requires reading the data and reasoning backward to the genotype, not just knowing Mendelian ratios by rote.

**Correct approach:**
1. (a) If the tall parent is **Tt** (heterozygous) crossed with **tt** (dwarf): offspring genotypes are Tt, Tt, tt, tt — a **1:1 tall:dwarf ratio**. This matches the observed ~42:38 (≈1:1) data, so the tall parent is most likely **Tt**.
2. (b) If the tall parent were **TT** crossed with **tt**: all offspring would be Tt (tall) — **100% tall, 0% dwarf**. This does NOT match the observed near-1:1 split, confirming that the tall parent cannot be TT and must be Tt.

**Final answer:** (a) Tt (heterozygous), confirmed by the ~1:1 ratio. (b) TT would give all-tall offspring, which contradicts the actual (roughly 1:1) data.

---

## B2. Energy flow — the 10% law in numbers

**Core concept:** At each trophic level, only about 10% of the energy is transferred to the next level (the rest is lost as heat, used in metabolism, or not consumed) — this is why energy available shrinks by a factor of 10 at every step, quickly becoming too little to support further levels.

**Where it usually goes wrong:** Stating the 10% law correctly in words but not actually calculating the numbers through all 5 levels, which is what makes the "why food chains are short" explanation concrete rather than just a memorized fact.

**Correct approach:**
1. Grass (producer): 100,000 kJ.
2. Grasshopper (primary consumer): 100,000 × 10% = **10,000 kJ**.
3. Frog (secondary consumer): 10,000 × 10% = **1,000 kJ**.
4. Snake (tertiary consumer): 1,000 × 10% = **100 kJ**.
5. Eagle (quaternary consumer): 100 × 10% = **10 kJ**.
6. (b) By the 5th level, only 10 kJ remains out of the original 100,000 kJ (a 10,000-fold reduction) — an amount too small to support the energy needs of a further population of consumers at a 6th level. This exponential decline (not linear) is exactly why food chains are naturally capped at around 4–5 trophic levels.

**Final answer:** 100,000 → 10,000 → 1,000 → 100 → 10 kJ across the five levels; the exponential drop explains the typical 4–5 level limit.

---

## B3. Plant tropisms — auxin and gravity response

**Core concept:** Auxin, a plant growth hormone, redistributes unevenly in response to gravity (accumulating more on the lower side of a horizontal stem), causing faster cell elongation on that side and producing an upward curve — this mechanism works independent of light, which is exactly why it still occurs in complete darkness.

**Where it usually goes wrong:** Naming the tropisms correctly (part a) but for part (b) only restating "the plant grows against gravity" without explaining the actual hormonal mechanism — which is the real point of the question.

**Correct approach:**
1. (a) Bending against gravity = **negative geotropism (negative gravitropism)**. Bending toward light = **positive phototropism**.
2. (b) When a stem lies horizontally, auxin (produced near the growing tip) redistributes so that a higher concentration accumulates on the **lower** side of the stem (a response to gravity itself, not light). This higher auxin concentration promotes greater cell elongation on the lower side compared to the upper side. This unequal, faster growth on the lower side causes the stem to curve upward. Because this entire mechanism is a response to gravity's effect on auxin distribution — not to light — it still happens even in complete darkness.

**Final answer:** (a) Negative geotropism; positive phototropism. (b) Gravity causes asymmetric auxin accumulation (more on the lower side), causing faster growth there and an upward curve — independent of light.

---

## B4. Excretion — selective reabsorption and diabetes

**Core concept:** Selective reabsorption in the nephron's tubule normally recovers all filtered glucose back into the blood, since glucose is a useful substance the body shouldn't lose. This process has a maximum capacity — when blood (and therefore filtered) glucose is abnormally high, as in diabetes, the reabsorption system is overwhelmed and the excess glucose "spills over" into the urine.

**Where it usually goes wrong:** Correctly naming reabsorption in part (a) but not connecting it, in part (b), to the idea of a reabsorption *capacity limit* — simply saying "there's more sugar so some leaks out" without explaining the underlying mechanism (a saturable transport process) misses the real explanatory point.

**Correct approach:**
1. (a) **Selective reabsorption** occurs, primarily in the **tubule (proximal convoluted tubule)** of the nephron — useful substances like glucose, along with most of the water and salts, are reabsorbed back into the surrounding blood capillaries, while urea and excess water/salts continue onward, eventually forming urine. Under normal conditions, essentially all filtered glucose is reabsorbed.
2. (b) In diabetes, blood glucose is abnormally high, so a much larger amount of glucose enters the filtrate at the glomerulus than usual. The tubule's glucose-reabsorption mechanism has a maximum capacity (a limited number of transport proteins working at a limited rate) — when the amount of filtered glucose exceeds what this system can reabsorb, the excess glucose that cannot be reabsorbed in time passes on into the final urine. In a healthy person, filtered glucose stays within this reabsorption capacity, so none is left over to appear in urine.

**Final answer:** (a) Selective reabsorption, mainly in the tubule. (b) Excess filtered glucose in diabetes exceeds the tubule's reabsorption capacity, so the surplus appears in urine.

---

## SST1. History — print culture and the spread of ideas

**Core concept:** The printing press changed not just the volume of material available but also its cost, reach, and the standardization of language — all of which independently made it easier for nationalist/revolutionary ideas to spread across a wider population than was possible with hand-copied manuscripts.

**Where it usually goes wrong:** Giving only a general statement ("printing spread ideas faster") without identifying genuinely distinct mechanisms behind *why*.

**Correct approach — at least two distinct mechanisms:**
1. **Cost and reach:** Printed material could be mass-produced far more cheaply than hand-copied manuscripts, letting ideas reach a much larger audience across social classes and geography, rather than being confined to a small literate elite with access to rare, expensive hand-copied texts.
2. **Standardization of language:** Printing increasingly used vernacular (everyday spoken) languages rather than only Latin, which helped standardize national languages. A shared standardized language fostered a stronger sense of shared identity and community among speakers — an important building block for nationalism, since people could now imagine themselves as part of a shared linguistic/cultural community reading the same material.
3. (Other valid mechanisms: speed of production/reproduction allowing rapid response to events; increased literacy driven by cheaper, more available printed material.)

**Final answer:** Any two genuinely distinct, well-explained mechanisms (cost/reach, language standardization, speed, literacy growth) are acceptable.

---

## SST2. Geography — cropping seasons and climatic requirements

**Core concept:** Crop seasons align with the specific temperature and water requirements of each crop — Kharif crops like rice need warmth and abundant water (matching monsoon conditions), while Rabi crops like wheat need cooler temperatures and less water (matching winter conditions). Irrigation can substitute for natural rainfall, removing water as a seasonal constraint (though not necessarily temperature).

**Where it usually goes wrong:** Describing the seasons correctly without explicitly connecting them to the crop's specific climatic *needs* (temperature and water separately) — and in part (b), not identifying precisely which constraint (water, not temperature) irrigation actually removes.

**Correct approach:**
1. (a) Rice needs high temperature and abundant standing water — the monsoon (Kharif) season naturally provides both heavy rainfall and warm temperatures, matching rice's needs. Wheat needs cooler temperatures and comparatively less water, and is sensitive to high summer heat — the cooler winter (Rabi) season provides suitable temperatures, and wheat's lower water requirement means it doesn't depend on monsoon-level rainfall.
2. (b) Irrigation supplies water artificially, independent of natural rainfall timing. Since water availability (not temperature) is rice's main constraint that the monsoon naturally satisfies, irrigation removes that specific water constraint — letting farmers grow rice in seasons or regions where temperature may still be suitable but natural rainfall is insufficient or absent.

**Final answer:** (a) Rice matches monsoon's heat+water; wheat matches winter's cooler, lower-water conditions. (b) Irrigation removes the water constraint specifically (not the temperature constraint), enabling rice cultivation outside the monsoon.

---

## SST3. Civics — power sharing vs. majoritarianism

**Core concept:** Classic CBSE case-study comparison (Belgium vs. Sri Lanka): power-sharing arrangements give minority communities a genuine stake in the political system, reducing the risk of alienation and conflict, whereas majoritarian systems that exclude minorities from power risk exactly that outcome.

**Where it usually goes wrong:** Describing the two countries' approaches accurately without drawing the explicit causal link between the *type of approach* and the *stability outcome* it tended to produce — the question specifically wants that connection made, with a concrete consequence cited for each.

**Correct approach:**
1. Belgium: its power-sharing arrangement (recognizing Dutch- and French-speaking communities, with substantial regional autonomy and Brussels' special status) helped avoid large-scale ethnic conflict, since minority communities had real political voice and self-governance rather than facing permanent minority status under majority rule.
2. Sri Lanka: its majoritarian approach (e.g., policies like making Sinhala the sole official language, favouring the Sinhala Buddhist majority) fostered alienation among the Tamil minority — widely linked by historians to the eventual outbreak and long duration of civil conflict in Sri Lanka.
3. Conclusion: when a majority group uses its political dominance to exclude minorities from power, minorities may feel they have no real stake in the system, increasing the risk of resentment and instability; power-sharing structures give all major communities a stake in maintaining the system, which tends to support long-term stability.

**Final answer:** Any answer that draws the explicit "power-sharing → stake in system → stability" vs. "majoritarianism → alienation → instability" link, with one specific fact from each country, is acceptable.

---

## SST4. Economics — sectoral productivity mismatch

**Core concept:** A sector's share of GDP relative to its share of the workforce reflects average output per worker (productivity) in that sector. A large workforce-share but small GDP-share (as in agriculture) indicates low productivity per worker; the reverse (as in services) indicates high productivity per worker.

**Where it usually goes wrong:** Describing the mismatch as simply "agriculture earns less" without connecting it to the productivity concept specifically (output per worker), and in part (b), suggesting a policy that doesn't actually address productivity (e.g., just "give farmers more money" without explaining the mechanism).

**Correct approach:**
1. (a) This mismatch indicates that **output (or income) generated per worker is far lower in agriculture than in services** — a very large number of agricultural workers together produce a comparatively small share of total value, while a much smaller number of service-sector workers produce a much larger share, meaning average productivity per worker is far higher in services.
2. (b) Any well-explained policy is acceptable, e.g.: investing in agricultural infrastructure and technology (irrigation, better seeds/inputs, mechanization) to raise output per farmer directly; or supporting the movement of underemployed agricultural workers into higher-productivity industry/services jobs through skill development and job creation (the "structural transformation" idea in development economics — shifting employment from low-productivity to higher-productivity sectors over time).

**Final answer:** (a) Indicates much lower labour productivity in agriculture compared to services. (b) Any well-justified policy addressing agricultural productivity or workforce shift to higher-productivity sectors.

---

## Quick summary — what to watch for in Set 03

| Q | Watch for |
|---|---|
| M1 | Did he set up BOTH the total-frequency and mean equations, or try to solve with only one? |
| M2 | Correct term indices (a+3d for 4th term, not a+4d)? |
| M3 | Did he combine each bracket into a single fraction first, rather than expanding everything at once? |
| M4 | Correct sign setup (new time = old time − 3, not + 3)? Did he reject the negative root? |
| P1 | Did he recompute R_equivalent correctly for each case before applying P=V²/R? |
| P2 | Part (c) is the real test — did he predict "more power," or fall for the "half the heater = half the power" intuition? |
| P3 | Correct field direction for current OUT of the page (anticlockwise, not clockwise)? |
| P4 | Did he correctly identify part (b) as virtual/erect once the object moved inside the focal length? |
| C1 | Does his part (b) explain that iron becomes locally more reactive/anodic at the scratch, not just "tin doesn't protect as well"? |
| C2 | Did he connect the colour change specifically to oxidation of an −OH group? |
| C3 | Did he give both classifications (displacement AND redox) with separate justifications, not just one? |
| C4 | Did he explain Mendeleev's actual interpolation method (neighbours above/below/left/right), not just "he predicted it somehow"? |
| B1 | Did he use the offspring ratio as evidence, not just assert Tt from general knowledge? |
| B2 | Did he compute all five actual numbers, not just state the 10% rule in words? |
| B3 | Does part (b) explain the auxin redistribution mechanism, not just repeat "it grows away from gravity"? |
| B4 | Did he connect diabetes to a reabsorption *capacity limit* being exceeded, not just "more sugar means some leaks out"? |
| SST1 | Are his two mechanisms genuinely distinct? |
| SST2 | Did part (b) correctly identify water (not temperature) as the constraint irrigation removes? |
| SST3 | Did he cite one specific consequence from each country, and draw the explicit causal link to stability? |
| SST4 | Does his answer connect the GDP/workforce mismatch to productivity specifically? |
