# Set 01 — Concepts & Solutions (Parent's Copy — do not share with your son before he attempts the questions)

For each question: **Core concept** → **Where students usually go wrong** → **Correct approach, step by step** → **Final answer**.

---

## M1. Polynomials & Real Numbers

**Core concept:** For a quadratic x² − px + q = 0 with roots α, β: sum of roots α+β = p, product αβ = q. Also, α² + β² = (α+β)² − 2αβ. Combining a symmetric-function identity with an integer/prime constraint (real numbers) is a very common JEE-foundation pattern.

**Where it usually goes wrong:** Students either forget the identity α²+β² = (α+β)² − 2αβ entirely, or they find *one* valid (p, q) pair and stop, without checking whether it's actually the *only* one satisfying every stated condition. The question explicitly demands he prove uniqueness — reading that instruction and acting on it is the real test here.

**Correct approach:**
1. α+β = p, αβ = q, so α²+β² = p² − 2q = 58 → p² = 58 + 2q.
2. q must be prime and less than 10, so q ∈ {2, 3, 5, 7}.
3. Test each: q=2 → p²=62 (not a perfect square); q=3 → p²=64=8² ✓; q=5 → p²=68 (not a perfect square); q=7 → p²=72 (not a perfect square).
4. Only q=3 gives an integer p. So **p = 8, q = 3**.
5. (Optional check) x² − 8x + 3 = 0 has discriminant 64−12=52>0, so real roots exist — consistent.

**Final answer:** p = 8, q = 3 (unique).

---

## M2. Trigonometry — Heights & Distances

**Core concept:** Two right triangles sharing the same tower height, with two different angles of elevation from two different ground points, related by cot and tan. This is a standard "derive the formula, then plug in" JEE-foundation type — it tests whether he can *set up* the two equations correctly, not whether he remembers a formula.

**Where it usually goes wrong:** Sign/labelling errors — mixing up which distance corresponds to which angle, or trying to directly use a memorized formula without being able to derive it (which fails the moment the numbers or the setup are changed slightly, as in JEE Advanced–style variants).

**Correct approach:**
1. Let tower height = h, and let the foot of the tower be point O. Let AB = d (distance walked), with B between A and O, so AO = AB + BO = d + BO.
2. From B (closer point), angle of elevation = 90°−θ, so: h / BO = tan(90°−θ) = cotθ → BO = h·tanθ.
3. From A (farther point), angle of elevation = θ, so: h / AO = tanθ → AO = h·cotθ.
4. AO − BO = d → h·cotθ − h·tanθ = d → **h = d / (cotθ − tanθ)**. This proves part (a).
5. Substitute θ=30°: cot30° = √3, tan30° = 1/√3. cot30°−tan30° = √3 − 1/√3 = (3−1)/√3 = 2/√3.
6. h = 20 / (2/√3) = 20 × √3/2 = **10√3 m ≈ 17.3 m**.

**Final answer:** (a) proved as above; (b) h = 10√3 m ≈ 17.3 m.

---

## P1. Refraction through a glass slab

**Core concept:** Snell's law (n = sin i / sin r) to find the refraction angle, then the **lateral displacement formula** for a parallel-sided slab: d = t·sin(i − r) / cos r, where t is slab thickness. NCERT Class 10 introduces lateral displacement only qualitatively — this question pushes him to the quantitative, JEE-Main level version of the same idea.

**Where it usually goes wrong:** Confusing lateral displacement with the emergent ray's *path length* inside the slab, or forgetting that i and r must be measured from the normal, or plugging into the formula without deriving why it works (geometry: it's the perpendicular offset between the incoming ray's original direction and the parallel emergent ray).

**Correct approach:**
1. Snell's law: n = sin i / sin r → √3 = sin60° / sin r → sin r = sin60°/√3 = (√3/2)/√3 = 1/2 → **r = 30°**.
2. Lateral displacement: d = t·sin(i−r)/cos r = 6 × sin(60°−30°) / cos30° = 6 × sin30° / cos30° = 6 × 0.5 / (√3/2) = 3 / (√3/2) = 6/√3 = **2√3 cm ≈ 3.46 cm**.

**Final answer:** (a) r = 30°; (b) lateral displacement = 2√3 cm ≈ 3.46 cm.

---

## P2. Concave mirror — magnification

**Core concept:** Magnification m = −v/u. A magnitude of |m| = 3 is consistent with **two** physically different situations for a concave mirror: a real, inverted image (m = −3, object between F and C) or a virtual, erect image (m = +3, object between P and F). This is exactly the kind of "the question doesn't fully pin down the scenario — you must consider all cases" comprehension trap JEE Main loves.

**Where it usually goes wrong:** Students assume "magnified image in a concave mirror" automatically means real and inverted, solve only that case, and miss the virtual case entirely — even though nothing in the question ruled it out.

**Correct approach (using 1/v + 1/u = 1/f, m = −v/u, f = −15 cm for concave mirror):**

*Case 1 — real, inverted image (m = −3):*
−v/u = −3 → v = 3u.
1/(3u) + 1/u = 1/f → 4/(3u) = 1/f → u = 4f/3 = 4(−15)/3 = **−20 cm**.
v = 3u = **−60 cm** (real, in front of mirror).
Object lies between F(15) and C(30) — consistent with a real, magnified image.

*Case 2 — virtual, erect image (m = +3):*
−v/u = 3 → v = −3u.
1/(−3u) + 1/u = 1/f → 2/(3u) = 1/f → u = 2f/3 = 2(−15)/3 = **−10 cm**.
v = −3u = **+30 cm** (positive → virtual, behind the mirror).
Object lies between P(0) and F(15) — consistent with a virtual, magnified image.

**Final answer:** Two valid positions — object at 20 cm (real image at 60 cm, inverted) OR object at 10 cm (virtual image at 30 cm behind the mirror, erect).

---

## C1. Reactivity & amphoteric behaviour

**Core concept:** Aluminium is amphoteric — it reacts with both acids and bases to liberate H₂ gas, unlike typical metals which react only with acids. This links "Chemical Reactions & Equations" forward to "Metals and Non-metals," a deliberate preview.

**Where it usually goes wrong:** Guessing a generic metal (zinc, iron) that reacts only with acid, and missing the base reaction entirely, or being unable to balance the NaOH equation (which produces sodium aluminate, NaAlO₂, not a simple hydroxide salt).

**Correct approach:**
1. Colourless, odourless gas that pops with a flame = hydrogen. A metal reacting with both dilute acid and a base to give H₂ → **X = Aluminium**.
2. With acid: 2Al + 6HCl → 2AlCl₃ + 3H₂↑
3. With base: 2Al + 2NaOH + 2H₂O → 2NaAlO₂ + 3H₂↑
4. Explanation: Aluminium is **amphoteric** — its oxide layer (and the metal itself) can react with both H⁺ ions (acid) and OH⁻ ions (base), which is unusual because most common metals are only reactive toward acids, not bases.

**Final answer:** X = Aluminium; equations as above; explanation = amphoteric nature.

**Note on Zinc as an alternative answer:** Zinc is also amphoteric, and a student may reasonably answer Zn instead of Al. The distinguishing factor the question is actually built on: Aluminium reacts with **NaOH solution at room temperature** (the mild, CBSE-textbook-standard reaction quoted above) — this is the specific reaction taught in the Class 10 syllabus. Zinc *does* react with NaOH to give H₂ (Zn + 2NaOH → Na₂ZnO₂ + H₂↑), but only under **concentrated, hot NaOH**, which is outside the syllabus and not what "NaOH solution" ordinarily implies in a textbook question. So Al is the intended/expected answer, but if he answers Zn with the concentrated-hot-NaOH reasoning, treat that as a strong answer, not a wrong one — it shows he's reasoning correctly about amphoteric behaviour, just applying a fact slightly beyond what was asked. Worth explicitly telling him both metals are amphoteric, and that the "NaOH solution" wording is the intended clue pointing to Al specifically.

---

## C2. pH, neutralisation, strength vs. concentration

**Core concept:** Neutralisation reaction: acid + base → salt + water. The *end pH* of a mixed acid-base solution depends on the relative **moles of H⁺ and OH⁻** present — which is a function of both concentration *and* strength (degree of dissociation), not strength alone. This question is designed to stop him from reflexively saying "A and C must be equally strong" without justification.

**Where it usually goes wrong:** Jumping straight to "the acid and base are equally strong" — which isn't actually what a final pH of 7 proves. It only proves the **moles of H⁺ from A and moles of OH⁻ from C were equal** in the volumes mixed — this could happen with a strong acid + weak base at appropriately different concentrations too, not only with equal strength.

**Correct approach:**
1. Reaction type: **neutralisation**. General equation: Acid + Base → Salt + Water (e.g., HCl + NaOH → NaCl + H₂O).
2. pH 7 after mixing equal volumes means the H⁺ ions from A and OH⁻ ions from C exactly cancelled out — i.e., moles of H⁺ = moles of OH⁻ in those volumes.
3. This does **not** by itself prove A and C are equally "strong" acids/bases (strength = degree of ionisation) — only that, at the concentrations used, their available H⁺ and OH⁻ happened to match exactly. Equal pH values that are "mirror" numbers (4 and 10, both 3 units from 7) is a hint but not a rigorous proof of equal strength unless concentrations are also stated to be equal.
4. If (and only if) A and C are also stated/assumed to be equal concentration, *then* pH 4 and pH 10 being mirror images around 7 would support them being of comparable strength.

**Final answer:** Neutralisation, general equation as above; final pH tells us moles of H⁺ (from A) = moles of OH⁻ (from C) in the volumes mixed — it does not, on its own, prove equal strength unless concentration is also controlled for. (This is the subtle point — if he just wrote "they're equally strong," that's the trap; walk him through why.)

---

## B1. Life Processes — respiration

**Core concept:** Aerobic vs. anaerobic respiration, and the specific anaerobic pathway that occurs in oxygen-starved human muscle (as opposed to yeast) — a classic point of confusion because *the same general process* ("anaerobic respiration") gives different end products in different organisms.

**Where it usually goes wrong:** Saying "anaerobic respiration produces alcohol" as a blanket statement — that's only true for yeast/plants, not human muscle, which produces lactic acid.

**Correct approach:**
1. In human muscle cells, oxygen shortage → **anaerobic respiration via lactic acid fermentation** → end product: **lactic acid** (causes the burning sensation/cramp).
2. In yeast, anaerobic respiration → **alcoholic fermentation** → end products: **ethanol (alcohol) and CO₂**.
3. ATP yield: aerobic respiration yields roughly **~36–38 ATP** per glucose molecule (via glycolysis + Krebs cycle + electron transport chain), while anaerobic respiration yields only **~2 ATP** per glucose molecule (glycolysis only, no further breakdown of pyruvate). This ~18x difference is why aerobic respiration is far more efficient.

**Final answer:** Human muscle → lactic acid; yeast → ethanol + CO₂; aerobic ATP yield ≈ 36–38 vs. anaerobic ≈ 2 per glucose.

---

## B2. Control & Coordination — reflex arc

**Core concept:** The reflex arc bypasses the brain (goes through the spinal cord) for speed, which is exactly why the reflex action happens before conscious awareness — awareness itself requires the signal to *also* separately travel up to the brain.

**Where it usually goes wrong:** Listing components out of order, or thinking the brain is involved in generating the reflex movement itself (it isn't — the spinal cord decides the motor response; the brain only becomes aware afterward, via a separate slower pathway).

**Correct approach:**
1. Correct sequence: **Receptor → Sensory neuron → Relay neuron (in spinal cord) → Motor neuron → Effector (muscle)**.
2. Why faster than a voluntary action: the reflex signal only has to travel receptor → spinal cord → muscle, a short path, and the spinal cord itself issues the motor command. A voluntary action (like catching a ball) requires the signal to travel all the way up to the brain, be processed/decided upon, and then travel back down — a much longer path, hence slower.
3. If the pathway from spinal cord *up to the brain* were damaged (but the reflex arc itself intact), the knee-jerk would still occur (spinal cord alone triggers it) — but the person would never consciously feel the tap, because that requires the signal reaching the brain, which is a separate branch of the pathway.

**Final answer:** Sequence as above; reflex is faster because it doesn't route through the brain; the "feeling" pathway (spinal cord → brain) is the part that, if damaged, removes awareness without affecting the reflex itself.

---

## H1. Nationalism in Europe

**Core concept:** Between 1815–1848, there was a continuous tug-of-war: conservative regimes (post-Congress of Vienna) tried to suppress liberal-nationalist movements, but these movements kept resurfacing, and by 1848 nationalism had become impossible to fully suppress even where individual revolts failed militarily.

**Where it usually goes wrong:** Just listing dates/events without connecting them to the actual question asked — "how did conservatives respond" and "what changed by 1848" require an argument, not a timeline.

**Correct approach (example answer shape):**
1. Example 1: The **Greek War of Independence (1821–1832)** — a nationalist uprising against Ottoman rule; conservative European powers were initially wary of supporting any nationalist revolt (fearing it would encourage similar movements elsewhere), but public sympathy (Romanticism, poets like Byron) eventually pushed Britain, France, and Russia to intervene and support Greek independence — showing conservative governments weren't fully unified in suppression once nationalism aligned with other interests.
2. Example 2: The **Revolutions of 1830 and 1848** (e.g., July Revolution in France 1830, and the widespread 1848 revolutions across German and Italian states) — conservative regimes initially used censorship, army repression, and the Metternich system to crush these; but by 1848, liberal-nationalist demands (constitutions, unification, ending feudal privileges) had become so widespread across so many states simultaneously that pure repression could no longer contain them — even though most of the 1848 revolutions were eventually suppressed, the *idea* and momentum of nationalism had, by then, become unstoppable in the long run (leading eventually to German and Italian unification by 1871).
3. Conclusion: conservative forces responded consistently with repression/censorship/military force, but by 1848 the sheer scale and simultaneity of nationalist movements showed that conservatism could win individual battles but was losing the broader argument.

**Final answer:** Any two well-explained examples following this reasoning shape are acceptable — check that he explains *cause and effect*, not just facts.

---

## H2. Age of Industrialisation

**Core concept:** Handicraft producers survived not by "resisting" industrialisation uniformly, but because of specific structural reasons: (1) demand for certain product categories that machine production couldn't easily replicate or that had export demand elsewhere, and (2) cheap, flexible labour that let handicraft production remain cost-competitive in downturns.

**Where it usually goes wrong:** Giving one reason twice in different words (e.g., "cheap labour" and "low wages" as if they're two separate reasons), instead of two genuinely distinct economic mechanisms.

**Correct approach — two distinct valid reasons:**
1. **Product differentiation / niche demand:** Certain items (fine, elaborately worked saris and cloth for specific social occasions, for example) had a market that machine-made cloth could not easily serve, because machine production favoured uniform, coarse, low-cost cloth for mass markets. So handicraft producers who specialised in these niches retained demand even as bulk cloth production shifted to mills. *Economic logic:* when products aren't perfect substitutes, competition on price alone doesn't eliminate the higher-value niche producer.
2. **Flexible, low fixed-cost labour and off-season/family labour:** Handloom weavers often had very low fixed costs (working from home, using family labour, no large capital investment in machinery) and could adjust their output flexibly, including working through agricultural off-seasons. This let them survive even at lower profit margins than a mill, which had high fixed costs (capital equipment) that had to be covered regardless of demand fluctuations. *Economic logic:* low fixed cost + flexible supply gives a cost-structure advantage in specific conditions (fluctuating demand, small-batch orders) that a large, high-fixed-cost mill can't easily match.

**Final answer:** Any two genuinely distinct reasons of this type, each with the underlying economic "why," are acceptable.

---

## Quick summary — what to watch for in his responses

| Q | Watch for |
|---|---|
| M1 | Did he check *all* prime values of q, or stop at the first one that worked? |
| M2 | Did he *derive* the formula from the two triangles, or just recall it? |
| P1 | Did he get r=30° correctly before attempting lateral displacement? |
| P2 | Did he find **both** cases (real and virtual), or only the "obvious" real one? |
| C1 | Did he correctly identify Aluminium (not Zinc/Iron), and balance both equations? |
| C2 | Did he claim "equal strength" without justification — the actual trap in this question? |
| B1 | Did he correctly separate human-muscle vs. yeast end products, not blend them? |
| B2 | Did he get the reflex-arc sequence exactly right, and correctly explain the "feeling vs. reflex" distinction? |
| H1 | Did he explain *cause and effect*, not just recite events? |
| H2 | Are his two reasons genuinely distinct mechanisms, not restatements of one idea? |
