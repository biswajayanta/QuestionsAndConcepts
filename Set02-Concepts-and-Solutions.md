# Set 02 — Concepts & Solutions (Parent's Copy)

---

## M1. Trigonometry — complementary angles of depression

**Core concept:** Same "two right triangles sharing a vertical side" idea as Set 01's M2, but reframed as angles of **depression** from the top (instead of angles of elevation from the ground), with the angles related by "complementary" instead of the explicit (90°−θ) phrasing. This is deliberately the *same skill*, dressed differently, to check whether the concept transferred or whether he only remembered the previous problem's specific steps.

**Where it usually goes wrong:** Forgetting that angle of depression from the top equals the angle of elevation from the ground point (alternate angles, parallel lines) — and mixing up which distance (p or q) pairs with which angle.

**Correct approach:**
1. Let the nearer object be at distance p, farther object at distance q from the foot of the building. Let the angle of depression to the nearer object be θ; then the angle of depression to the farther object is (90°−θ), since they're complementary.
2. By alternate angles, angle of elevation from the nearer object to the top = θ: tanθ = h/p.
3. Angle of elevation from the farther object = (90°−θ): tan(90°−θ) = cotθ = h/q.
4. Multiply the two equations: tanθ × cotθ = (h/p) × (h/q) → 1 = h²/(pq) → **h² = pq**.

**Final answer:** Proved as above.

---

## M2. Quadratic Equations — equal roots with a hidden case

**Core concept:** Using the discriminant condition (b²−4ac = 0) for equal roots — but with a twist: the coefficient of x² itself contains k, so there's a hidden case where the "quadratic" stops being a quadratic at all.

**Where it usually goes wrong:** Just setting the discriminant to zero and solving, without checking whether the leading coefficient 2(k+1) could itself be zero — which would make the equation linear, not quadratic, and "equal roots" wouldn't even apply in the usual sense.

**Correct approach:**
1. Here a = 2(k+1), b = −2(k+1), c = 1.
2. **Check the hidden case first:** if k = −1, then a = 0, and the equation becomes 0·x² − 0·x + 1 = 0, i.e., 1 = 0 — not a valid equation at all (no solution, not even linear). So **k = −1 must be excluded**.
3. For k ≠ −1, set discriminant = 0: b² − 4ac = 0
   [−2(k+1)]² − 4[2(k+1)][1] = 0
   4(k+1)² − 8(k+1) = 0
   4(k+1)[(k+1) − 2] = 0
   4(k+1)(k−1) = 0
4. So k = −1 or k = 1. But k = −1 was already excluded as invalid (step 2). So the only valid answer is **k = 1**.

**Final answer:** k = 1 (k = −1 must be explicitly rejected, not just omitted — that's the point of the question).

---

## P1. Human Eye — myopia, and a "no correction needed" trap

**Core concept:** Comparing a person's actual near/far points against the *normal* near point (25 cm) and far point (infinity) to correctly diagnose the defect — and recognizing that a near point *closer* than 25 cm is not a defect at all, it's actually better-than-normal near vision.

**Where it usually goes wrong:** Assuming any deviation from "normal" numbers must be a defect requiring correction, and automatically calculating a lens power for reading at 25 cm without checking whether it's even needed.

**Correct approach:**
1. Normal near point = 25 cm, normal far point = infinity. This person: near point = 15 cm (closer than normal — he can focus on objects even nearer than a normal eye can), far point = 200 cm (much closer than infinity — he cannot see distant objects clearly). This is **myopia (nearsightedness) only** — there is no hypermetropia here, since his near vision is actually better than normal, not worse.
2. Since his near point (15 cm) is already closer than the standard reading distance (25 cm), **he does not need any lens to read at 25 cm** — he can already focus comfortably at that distance without help. This is the trap: many students reflexively calculate a lens power for "reading" without checking this.
3. For distance vision: a concave (diverging) lens is needed to bring distant objects' images within his far point (200 cm = 2 m). Using the lens formula with object at infinity (u = −∞) and image formed at his far point (v = −200 cm, since it's virtual and on the same side):
   1/f = 1/v − 1/u = 1/(−200) − 0 = −1/200
   f = −200 cm = **−2 m**
   Power P = 1/f(in metres) = 1/(−2) = **−0.5 D**

**Final answer:** (a) Myopia only, no hypermetropia (near point better than normal). (b) No lens needed for reading. (c) Concave lens of power −0.5 D needed for distance vision.

---

## P2. Electricity — series/parallel combinations

**Core concept:** Series resistances add directly (R_series = R₁+R₂+...); parallel resistances combine via 1/R_parallel = 1/R₁+1/R₂+.... Getting a specific target resistance from identical resistors usually requires a mixed (series+parallel) combination, found by trial based on which combinations are even possible.

**Where it usually goes wrong:** Trying only the two "obvious" combinations (all series = 18Ω, all parallel = 2Ω) and concluding 4Ω is impossible, without trying a mixed arrangement.

**Correct approach:**
1. All three in series: 6+6+6 = 18Ω. All three in parallel: 1/R = 1/6+1/6+1/6 = 3/6 = 1/2 → R = 2Ω. Neither is 4Ω, so a mixed combination is needed.
2. Try: two resistors in series (6+6=12Ω), and that combination in parallel with the third 6Ω resistor:
   1/R = 1/12 + 1/6 = 1/12 + 2/12 = 3/12 = 1/4 → **R = 4Ω**. ✓ This works.
3. (b) All three in parallel (calculated above): **R = 2Ω**.

**Final answer:** (a) Two resistors in series (12Ω), that combination in parallel with the third (6Ω), gives 4Ω. (b) All three in parallel gives 2Ω.

---

## C1. Reactivity series — logical deduction from displacement data

**Core concept:** If metal A displaces metal B from B's salt solution, A is more reactive than B. Chaining several such displacement facts lets you build a full reactivity order — a pure logic/comprehension exercise dressed as chemistry.

**Where it usually goes wrong:** Getting confused about direction (who displaces whom means who is *more* reactive), or not using the "does NOT displace" clues, which are just as informative as the "does displace" ones.

**Correct approach:**
1. P displaces Q and R → P is more reactive than Q and more reactive than R.
2. P does NOT displace S → S is more reactive than P.
3. Q displaces R → Q is more reactive than R.
4. Q does NOT displace P (consistent with P>Q above) or S → S is more reactive than Q (already implied since S>P>Q).
5. Combining: S > P > Q > R.
6. (b) Since S is the most reactive of all four, S **will** displace P from its salt solution — a more reactive metal always displaces a less reactive one from its salt solution.

**Final answer:** (a) S > P > Q > R (decreasing reactivity). (b) Yes, S will displace P, since S is more reactive than P.

---

## C2. pH & Neutralisation — revisiting the "don't overclaim" trap

**Core concept:** This is a direct re-test of the Set 01 C2 mistake, with new numbers. pH is a *logarithmic* scale, so "equally far from 7" (pH 3 and pH 11, both 4 units away) tells you nothing certain about whether mixing equal volumes gives pH 7 — that depends on the actual concentrations of H⁺ and OH⁻ ions, and possibly on the strength (degree of dissociation) of the acid/base, not just the pH numbers.

**Where it usually goes wrong (this is the exact trap from before):** Assuming that because pH 3 and pH 11 are symmetric around 7, mixing them equally must give pH 7. This isn't automatically true — pH 3 means [H⁺] = 10⁻³ mol/L, and pH 11 means [OH⁻] = 10⁻³ mol/L (since pOH = 14−11 = 3) — in *this specific case*, the concentrations do happen to match, so equal volumes would actually neutralise exactly! The important skill here is not just getting the "yes" answer, but showing *why* — by explicitly calculating and comparing the ion concentrations, not by assuming from the pH symmetry alone.

**Correct approach:**
1. pH 3 → [H⁺] = 10⁻³ mol/L.
2. pH 11 → pOH = 14 − 11 = 3 → [OH⁻] = 10⁻³ mol/L.
3. Equal volumes (50 mL each) means equal *moles* of H⁺ and OH⁻ are present (moles = concentration × volume, and volumes are equal here), so moles of H⁺ = moles of OH⁻ → they exactly neutralise → **yes, in this specific case, the mixture will be pH 7.**
4. (b) The general condition for this to be guaranteed: moles of H⁺ in the acid solution must equal moles of OH⁻ in the base solution (concentration × volume must match) — it is NOT guaranteed just because the two pH values are symmetric around 7 in general; it happens to work out here because we calculated the actual concentrations and volumes and confirmed they match.

**Final answer:** (a) Yes — but only because direct calculation shows [H⁺]×volume = [OH⁻]×volume here, not merely because 3 and 11 are equidistant from 7. (b) Equal moles of H⁺ and OH⁻ (i.e., matching concentration × volume) is the actual guarantee — pH symmetry around 7 is not sufficient on its own in the general case.

**Note for you:** if he answers "yes, because 3 and 11 are symmetric around 7," that's the same overclaim as before — the fact that it happens to be true here (due to how pH and pOH are defined) doesn't make "symmetry around 7" the valid *reason*. Push him to show the actual concentration calculation before accepting the answer.

---

## B1. Reproduction — cross-pollination vs. self-pollination

**Core concept:** Genetic variation is the evolutionary advantage of cross-pollination — a population with more genetic diversity adapts better to changing environments/diseases, even though self-pollination is more "reliable" in the short term.

**Where it usually goes wrong:** Only naming a mechanism (like showy petals, scent, nectar) without connecting it to *why* cross-pollination matters evolutionarily, or vaguely saying "cross-pollination is better" without the genetic-variation reasoning.

**Correct approach:**
1. (a) Examples of features favouring cross-pollination: bright/showy petals or scent to attract pollinators, production of nectar as a reward, some flowers having anthers and stigma maturing at different times (preventing self-fertilisation), or physical separation of male and female flowers on the same/different plants.
2. (b) Self-pollination produces offspring genetically near-identical to the parent — over generations this reduces genetic diversity in the population. Cross-pollination combines genetic material from two different individuals, increasing genetic variation among offspring. Greater genetic variation gives a population a better chance that *some* individuals will survive a changing environment, new disease, or pest — a population with low genetic diversity risks being wiped out entirely if a single vulnerability affects all (near-identical) individuals. This is the same logic behind why genetic diversity generally matters in evolution.

**Final answer:** Any structurally correct example for (a); reasoning centered on genetic diversity/adaptability for (b).

---

## B2. Hormonal vs. nervous coordination

**Core concept:** Nervous coordination is electrical and travels along fixed pathways (fast, localized, short-lived effect); hormonal coordination is chemical, travels via the bloodstream (comparatively slower to reach all target sites, but effects can be longer-lasting and more widespread). Adrenaline is a special case of a *fast-acting* hormone, precisely because emergency response demands speed.

**Where it usually goes wrong:** Treating "hormonal = slow" as an absolute rule rather than a general tendency, and not being able to explain why adrenaline specifically breaks that generalisation to some degree, or not making a clear comparison on both speed AND duration.

**Correct approach:**
1. (a) Adrenaline is released directly into the bloodstream and is rapidly circulated throughout the body via the fast-flowing blood supply — so even though it's a chemical signal (not an electrical impulse), the "emergency hormone" system is built for rapid, whole-body response specifically because survival situations (fight-or-flight) require it. It reaches multiple organs almost simultaneously (heart, muscles, liver) rather than needing separate individual nerve signals to each.
2. (b) Nervous coordination: signals travel via electrical impulses along neurons — very fast, but effects are localized (specific muscles/glands) and generally short-lived (as soon as the stimulus/signal stops, the response typically stops quickly too). Hormonal coordination: generally slower to initiate (has to be released, travel via blood) but effects tend to be more widespread (affects many organs/tissues at once) and longer-lasting (hormones remain active in the bloodstream for longer, so effects like elevated heart rate/blood sugar persist even after the initial trigger).

**Final answer:** (a) Because it's released directly into the fast-flowing bloodstream and reaches multiple organs simultaneously — specifically evolved for rapid emergency response. (b) Nervous = faster onset, more localized, shorter-lived; Hormonal = generally slower onset, more widespread, longer-lasting effect.

---

## H1. Age of Industrialisation — colonial economic logic (deeper reasoning)

**Core concept:** Classic colonial economic strategy: keep the colony as a source of raw materials and a captive market for the colonial power's finished/manufactured goods, while actively discouraging the colony from developing its own capacity to produce competing finished goods or capital goods (machinery, steel) that would reduce its dependence on the colonial power.

**Where it usually goes wrong:** Describing what happened without explaining the underlying colonial economic logic — i.e., listing facts (some industries grew, others didn't) without connecting it to *why* that pattern specifically served British interests.

**Correct approach (example answer shape):**
1. Industries like cotton textiles and jute were allowed to grow partly because India already had raw material advantages (cotton, jute fibre) and a large domestic/export market, and because these were "light," consumer-goods industries that, while competing with some British textile exports, didn't threaten Britain's core industrial and strategic advantage.
2. Heavy industries — steel, machine tools, capital goods — were a different matter: these industries produce the *machines that make other machines*, i.e., they build up a country's independent industrial capacity. If India developed strong heavy industry, it would need to import far less machinery and capital equipment from Britain, directly undermining Britain's position as India's primary supplier of manufactured/capital goods, and reducing India's economic dependence on the British economic system altogether.
3. In short: colonial economic policy generally favoured industries that kept India as (a) a raw-material exporter, and (b) a market for British finished goods and machinery — and was far more cautious about industries that would let India build genuine independent industrial capacity, which cotton/jute (as consumer-goods industries reliant on imported machinery) didn't fully threaten, but heavy/capital-goods industries would have.

**Final answer:** Any answer that clearly articulates the "raw material exporter + captive market" colonial logic, and specifically explains why heavy/capital-goods industry was more threatening to that model than light consumer-goods industry, should be accepted.

---

## H2. Resources & Development — why land area ≠ abundant resources

**Core concept:** "Resources" in geography are classified by several dimensions — availability/exhaustibility (renewable vs. non-renewable), status of development (potential, developed/actual, reserve, stock), and ownership. Large land area alone says nothing about how much of that land is actually usable, arable, or resource-rich — climate, terrain, soil quality, and existing competing land uses all constrain what's genuinely usable.

**Where it usually goes wrong:** Giving only one reason, or giving reasons that are really the same underlying idea restated (e.g., "mountains" and "hilly terrain" as if they're two separate constraints).

**Correct approach — pick any two genuinely distinct constraints, e.g.:**
1. **Terrain/topography constraint:** Large parts of a country's land area may be mountainous, desert, or otherwise physically unsuitable for agriculture or settlement (e.g., the Himalayan region, the Thar Desert) — so total land area overstates usable/arable land.
2. **Competing land use constraint:** Land already has multiple, often competing uses — forests, wildlife reserves, urban settlement, industrial use — so land counted in the "total area" figure isn't automatically available for agriculture or new resource extraction; much of it is already allocated elsewhere or needs to be protected (e.g., for ecological reasons).
3. (Other valid options: soil quality/fertility varying regionally, water availability, or the renewable/non-renewable classification limiting how much of a resource can be sustainably used regardless of how much land contains it.)

**Final answer:** Any two genuinely distinct, well-explained constraints (terrain, competing land use, soil/climate, or resource exhaustibility) are acceptable — the key is that the two reasons must be different underlying mechanisms, not restatements.

---

## Quick summary — what to watch for in Set 02

| Q | Watch for |
|---|---|
| M1 | Did he correctly identify which distance (p vs q) pairs with which angle, and use alternate angles correctly? |
| M2 | Did he catch and explicitly reject the k=−1 case, or did he just report both roots of the discriminant equation? |
| P1 | Did he realize no lens is needed for reading — or did he calculate one anyway out of habit? |
| P2 | Did he find the mixed series+parallel combination, or only try the two "obvious" all-series/all-parallel options? |
| C1 | Did he correctly use both the "displaces" and "does not displace" clues to build the full order? |
| C2 | Did he calculate actual ion concentrations, or just assume "symmetric pH = automatically neutral" again? This is the big one to check carefully. |
| B1 | Did his part (b) actually reach the genetic-diversity/adaptability argument, or stop at "it's more reliable/better"? |
| B2 | Did he explain both speed AND duration, or only address one? |
| H1 | Did he explain the underlying colonial economic logic, or just restate which industries grew and which didn't? |
| H2 | Are his two constraints genuinely distinct mechanisms? |
