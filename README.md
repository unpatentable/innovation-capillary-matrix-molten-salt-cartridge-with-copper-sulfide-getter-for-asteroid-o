# Capillary-Matrix Molten Salt Cartridge with Copper Sulfide Getter for Asteroid Oxygen and Metal

> **Note:** This README is an ultra-condensed summary of the research reports published by Unpatentable.org. To view the full innovation documentation and explore the complete research, use the links at the bottom of this document.

**Domain:** [Space & Aerospace](https://unpatentable.org/innovation/?domain=space-aerospace)
**Subdomain:** [Space Resources](https://unpatentable.org/innovation/?domain=space-aerospace&subdomain=space-resources)

---

### Why We Invented This Technology
Recent results from Hayabusa2 (Ryugu) and OSIRIS-REx (Bennu) sample returns, the 2023-2025 in-situ resource utilization demonstrations such as MOXIE oxygen production, and molten regolith electrolysis tests have shown that extraterrestrial materials can be chemically processed into usable metals and oxygen. Combined with falling launch costs and advances in autonomous robotics, the barrier of launching all materials from Earth is weakening. This makes it newly feasible to build open, non-proprietary processing methods for space-derived resources, supporting lower-cost satellite-based services such as climate monitoring, disaster warning, and connectivity, while reducing Earth-based mining pressure. Publishing these methods openly would keep the foundational processing technology from being locked behind patents.

### The Innovation
## Abstract
This report describes a molten-salt electrolysis cartridge meant to work in microgravity on carbonaceous asteroid regolith. It does not use a free salt bath. The CaCl₂–NaCl electrolyte is held by capillarity in a set of porous layers with graded pore sizes, borrowed from molten-carbonate fuel-cell (MCFC) practice. Oxygen leaves through a gas-diffusion inert anode, so no bubbles form in the melt. A copper grid between the cathode and anode is held at a set potential as a third electrode. It captures sulfide ions from the sulfur-rich feed as Cu₂S, which separates the sulfur and protects the oxygen anode. Two further reversals of usual practice complete the system. Space vacuum is used to recover the salt left in the product by distillation, and the cell voltage is capped below the MgO reduction limit, so the MgO left over can be sintered into new separator matrices. The products are oxygen, Fe–Ni–Si alloy, sulfur, and water.

## Background & Prior Work
The FFC-Cambridge process reduces solid oxides to metals in molten salt (CaCl2) at temperatures of around 900 °C, and ESA, Metalysis and Glasgow have applied it to lunar simulants. Those studies also expose its limits. Roughly one third of the total oxygen in the sample was detected in the off-gas, and the remaining oxygen is likely lost to corrosion of the reactor vessel. Other work reports that a significant portion of the mass lost is metal particle loss into the salt. In reduced gravity, parabolic flights showed current density decreases and resistance increases under microgravity, due to the layer of gas bubbles on the electrode. Molten regolith electrolysis (MRE) runs above 1600 °C with iridium anodes. Solid-oxide-membrane (SOM) electrolysis, recalled from the Pal group at Boston University, uses a zirconia membrane at 1100–1300 °C.

Bubble-free 'bubble-free' operation in a capillary-fed electrolysis cell has been shown for aqueous water splitting, and MCFCs hold carbonate electrolyte in LiAlO₂ matrices. Neither has been applied to solid-oxide deoxidation in chloride melts, combined with potential-controlled sulfide capture, or designed around carbonaceous-chondrite (CI-like) feed.

## Competitive Landscape & Strategic Edge
The main players are ESA/Metalysis (FFC in a bath), NASA/Lunar Resources/Blue Origin (MRE), Helios (molten salt, lunar), and Boston University/Pal (SOM). All of them design for the Moon, at 1/6 g, with dry, sulfur-poor feed. Their shared blind spot is volatile-rich C-type asteroids. Sample return showed Bennu contains sodium-bearing phosphates and sodium-rich carbonates, sulfates, chlorides and fluorides, along with phyllosilicates and several weight percent sulfur. Inert oxide anodes suffer badly when sulfide reaches them. The edge claimed here is a cell that does not depend on gravity, uses no bath, captures sulfur, and recycles salt in vacuum. It runs at about 900 °C, well below MRE and SOM temperatures, and its separator matrix can eventually be made from its own residue.

## Core Concept
**1. Process train.** (a) *Staged devolatilization retort*: feed is heated in steps (150 → 450 → 900 °C, closed vessel). Water from dehydroxylation of phyllosilicates is condensed, an estimated ~8–12 wt% of CI-like feed. CO₂ from carbonates and organics is collected. The char left behind is optionally gasified with part of the recovered steam (C + H₂O → CO + H₂) to make syngas. (b) *Wafer forming*: the calcine is pressed and sintered at 900 °C into wafers 1–3 mm thick with 40–50% porosity. The wafers keep their indigenous NaCl, which acts as a sintering aid and as makeup electrolyte. (c) *Cartridge electrolysis* (below). (d) *Vacuum salt distillation*: the reduced wafer is heated to 950–1050 °C and exposed to space vacuum. The salt it carries evaporates and condenses on a cold plate at about 400 °C, then goes back to the cartridge reservoir. A Hertz–Knudsen estimate shows evaporation is fast even at ~10² Pa salt vapor pressure: J = p√(M/2πRT) ≈ 0.09 kg m⁻² s⁻¹ for NaCl at 1273 K. (e) *Getter regeneration*: Cu₂S-loaded grids go to a small molten-sulfide electrolysis cell (Allanore-type, graphite anode), which returns liquid Cu, recast into grids, and S₂ gas. Copper stays in a closed loop.

**2. Cartridge architecture.** Each planar cell is stacked in this order: current collector (Mo or Fe–Ni) / feed wafer cathode / MgO matrix half-layer (0.3 mm) / Cu getter mesh (~100 mesh, 50–80 µm wire) / MgO matrix half-layer (0.3 mm) / bilayer anode / gas channel. The anode has a fine catalytic layer (pores ~1 µm, doped SnO₂ or CaRuO₃–CaTiO₃) and a coarse gas layer (pores 30–50 µm). An edge reservoir felt (pores 10–15 µm) stores spare melt. The electrolyte is CaCl₂ with about 20 mol% NaCl and 0.5–2 wt% CaO, run at 880–920 °C. Pure CaCl₂ is not used lower down because tests found that reducing the temperature of CaCl2 down to 850 °C dropped the current efficiency to below 30%.

The pore sizes are graded so the liquid sits in the right places. From the Young–Laplace relation, p_c = 2γcosθ/r. With γ ≈ 0.15 N/m and θ ≈ 20° (both estimates to be measured), p_c is about 560 kPa for the matrix (r = 0.5 µm), 56 kPa for the wafer (5 µm), 19 kPa for the reservoir (15 µm), and 7 kPa for the anode gas layer (40 µm). Liquid fills the smallest pores first. Holding the gas-side pressure Δp at 10–15 kPa above the liquid therefore keeps the matrix and wafer fully wet, leaves the reservoir partly full, and keeps the anode gas layer drained. Gas cannot break through the matrix (bubble point ~560 kPa). Oxygen forms where gas, liquid and solid meet in the fine anode layer and leaves through the coarse layer, so no free bubbles enter the melt.

Acceleration barely matters. Pressure head ρgL at 1 m/s² over 0.1 m is about 210 Pa, far below every capillary threshold, so the same cartridge works on an asteroid, on the Moon, or during spacecraft maneuvers. Electrolyte inventory is about 0.25–0.3 g/cm², roughly 0.7–0.8 g of salt per gram of feed. A bath needs several times that, though this is an estimate.

**3. Potential-controlled copper sulfide getter.** During reduction, FeS + 2e⁻ → Fe + S²⁻. If that sulfide reached the oxide anode it would form SO₂ or SnS. The Cu mesh is held, against a Ni/NiO or Ag/AgCl reference electrode, at a potential E_g where sulfide is oxidized to Cu₂S (4Cu + 2S²⁻ → 2Cu₂S + 4e⁻) but copper is not oxidized to Cu₂O and does not dissolve as CuCl.

Standard Gibbs energies at about 1170 K (textbook-data estimates) put Cu₂S formation ~0.9 V negative of O₂ evolution, Cu₂O formation ~0.45 V negative, and CuCl dissolution ~0.4 V negative. The low CaO activity (~0.02) moves Cu₂O formation a further ~0.2 V positive (Nernst term (RT/2F)·ln(1/a_CaO)). A dilute sulfide activity a_S moves Cu₂S formation positive by (RT/2F)·ln(1/a_S), about +0.35 V at 10⁻³.

**Control rule:** set E_g at 0.40–0.50 V negative of the measured anode potential, and confirm the exact window by cyclic voltammetry on the real melt. The getter should then lower sulfide activity to about 10⁻³–10⁻⁴. The getter current (charge spent on sulfur) should be about 10% of cell charge for feed with 5 wt% S (3.1 vs 31 mol e⁻ per kg, estimate). It carries about 0.2 kg Cu per kg feed in the loop, and that copper is recycled, not used up. Silver is an alternative grid metal because it forms no oxide at this temperature, but it weighs more per unit of sulfur captured.

**4. Staged cathode reduction with a voltage cap that protects the matrix.** Thermodynamic cell voltages against an O₂ anode at ~1170 K (estimates): FeS → Fe ≈ 0.9 V; NiO ≈ 0.7 V; FeO ≈ 1.0 V; Mg₂SiO₄ → Si + MgO ≈ 2.0 V; MgO ≈ 2.5 V; CaO ≈ 2.7 V; chloride breakdown ≈ 3.2 V.

- Stage 1: IR-corrected cell voltage 1.1–1.4 V until the sulfur getter current drops below 5% of cell current. This releases sulfur and makes Fe–Ni–Co metal.
- Stage 2: 1.9–2.3 V, with a hard cap at 2.3 V. This reduces silicon and titanium.

The cap does two jobs. It keeps the MgO matrix thermodynamically stable, and it leaves the feed's MgO (~23 wt% of CI calcine) as refractory residue that can be sintered into new matrix layers. That closes the loop for the separator material. The stopping point follows ESA's finding that targeting 60 % oxygen extraction may afford the most oxygen in the least time, while targeting 70–80 % extraction would maximise power efficiency.

Estimated yield is ~170 g O₂ per kg calcine (70% of ~24 wt% extractable O in FeO + NiO + SiO₂), plus about 0.4 kg of Fe–Si–Ni sponge mixed with MgO. Crushing and magnetic separation divide the two, and magnetic separation works without gravity.

**5. Electrolyte-management control loop.** The controller watches high-frequency resistance (HFR, 10 kHz) and the low-frequency anode impedance arc (EIS, 1 Hz).
- HFR up more than 15%: the matrix or wafer is drying out. Raise Δp in 2 kPa steps, up to 18 kPa, to push melt from the reservoir.
- Anode charge-transfer resistance up more than 25%: the anode is flooding. Lower Δp, down to 8 kPa.
- Both up together: inventory is short. Trigger salt return from the distillation cold plate.

Sizing estimate: 1 kg O₂ per day needs about 140 A at 100% current efficiency, or about 350 A at 40%. At 0.1 A/cm², that is ~3,500 cm², or 14 cells of 16 × 16 cm.

## Physics & Logical Feasibility
Every mechanism rests on established physics: Young–Laplace capillarity, Nernst and Gibbs thermodynamics, Faraday's law, and Hertz–Knudsen evaporation. Energy: at an average of 2.0 V, 4F per O₂ gives ~24 MJ (6.7 kWh) per kg O₂ at 100% current efficiency. At an estimated 40–60% efficiency that becomes ~11–17 kWh/kg, plus heat losses. Heat flows from Joule self-heating and insulated stack walls; the distillation and cold-plate heat is rejected by radiators. The electrochemistry has precedent. The getter window is thermodynamically open, but it narrows as sulfide is depleted, and it has to be measured. Three assumptions are critical: chloride melts wet MgO and the metal sponge (θ < 40°); dissolved O₂ crossing the thin matrix does not seriously cut efficiency; and MgO is stable in CaCl₂–CaO below 2.3 V. One version is more ambitious and riskier: running the cell up to ~2.8 V (calcium-mediated) to reduce more oxide. That would require a Y₂O₃ matrix and could reduce it, so it is disclosed only as an option.

## Implementation Readiness & Key Constraints
The roadmap has five steps. (1) Bench-scale (5 cm²) cells with sintered CI simulant (e.g., UCF/Exolith CI-type) to measure wetting angles, Δp windows, and the getter window by voltammetry. (2) A 16 × 16 cm cartridge with off-gas mass spectrometry, run in several orientations as a ground proxy for gravity independence. (3) Parabolic-flight and suborbital tests of a hot cartridge. (4) Integration with the vacuum-distillation and Cu-loop modules in a thermal-vacuum chamber. (5) An ISS external payload or rideshare demonstration. Estimated cost is $12–18M over 6–8 years, within the $20M ceiling.

The hardest problems: inert-anode durability with leftover sulfide and chloride; keeping the cartridge seal intact through thermal cycling (a Ni-alloy can with a cooled gland); mechanical stability of the matrix as wafer porosity rises from ~45% to ~70% during reduction; and molten-sulfide regeneration, which remains at low technology readiness (TRL).

## Utility & Purpose
The system makes propellant oxygen, structural Fe–Ni–Si alloy, water, sulfur for sulfur concrete, and MgO refractory from near-Earth C-type asteroids. These bodies are the easiest to reach and the richest in volatiles, but the most hostile to existing refining processes. Because it needs no gravity and no bath, the same hardware works on the Moon, on Phobos, or in free flight. That could cut mass launched from Earth for depots and in-space manufacturing. Likely users are space agencies (ESA, NASA, JAXA), propellant-depot operators, asteroid-prospecting firms, and lunar surface programs that want one process for different gravity levels.

## Potential Applications & Impact
The direct uses are propellant depots supplied from asteroid feed, metal feedstock for orbital additive manufacturing, and life-support oxygen. Each module can also serve terrestrial metallurgy. Matrix-held chloride electrolysis could shrink FFC/Metalysis titanium and tantalum reactors and reduce bath losses, and the potential-controlled sulfide getter is relevant to deoxidizing sulfidic ores and recycled scrap.

Wider effects: it offers a way to bring fuel-cell electrolyte-management science into extractive metallurgy, makes gas-diffusion electrodes for molten salts a research topic, and gives a value to asteroid evaporites and sulfides, which spectroscopy-based prospect ranking currently treats as liabilities. The cartridge's ability to regenerate its own matrix is a step toward self-replicating industry in space.

## Market/Adoption Feasibility
Each cartridge is a sealed, swappable unit, so capacity scales by adding units, with no need to re-engineer the reactor. Materials are mostly common: MgO, Ni alloys, Cu, and chloride salts. The scarce exception is the anode catalyst, Ru or Sn based. Estimated flight unit mass is ~150–250 kg for 1 kg O₂/day, including power conditioning, excluding solar arrays (estimate). Enabling trends are falling launch costs, ~10 kW-class solar power on small spacecraft, and asteroid sample characterization from Hayabusa2 and OSIRIS-REx. The main barrier is the mission-integration risk of a first in-space demonstration. Adoption would be helped by the low ~900 °C operating temperature, compatibility with existing ESA FFC data, and on-Earth markets for compact chloride electrolysis that de-risk the technology before flight.

## Risk & Counterarguments
Failure modes:
- The gas-filled anode layer floods because of wetting hysteresis.
- Cracked matrix lets gas cross over.
- Cathodic metal is reoxidized by dissolved O₂.
- The getter window closes on real melts with fluoride and phosphate impurities, which Bennu salts contain.
- Wafers swell or spall.
- Copper is lost slowly from the regeneration loop.

Critics may argue that rolling cathodes or a centrifuge could solve bubble detachment more simply. Those approaches still need a bath, though, and they do not deal with sulfur. On regulation: asteroid mining falls under Outer Space Treaty questions and national resource laws (US 2015, Luxembourg 2017). Planetary-protection rules for return of carbonaceous material, and handling SO₂/S₂ in crewed settings, add further constraints. The process makes no harmful products when contained.

## Open Questions & Future Research Directions
Several questions need measurement:
- The real wetting angles of CaCl₂–NaCl on MgO and on partly reduced sponge.
- The getter window when fluoride, phosphate and carbonate are present.
- How much Ca uptake slows silicate reduction below 2.3 V.
- Matrix creep after more than 500 hours.
- How fast O₂ crosses the matrix.

Next steps include: manufacturing MgO matrices from residue in space; continuous roll-to-roll wafer feeding that avoids batch cartridges; staged cathode contacts that pull an Fe–Ni fraction out before silicon reduction so the two metal fractions come out separately; machine-learned EIS signatures to classify how heterogeneous each feed batch is; and adapting the cell to Mars perchlorate-bearing regolith, where chloride makeup would also come from the local material.

## Novelty Threshold Justification
**Medium-to-High Novelty.** The closest prior art: FFC-Cambridge lunar work (Lomax et al. 2020, 2025; Meurisse et al. 2022), which uses bath cells; aqueous capillary-fed electrolysis, noted in the Akay et al. 2022 npj Microgravity review (https://www.nature.com/articles/s41526-022-00239-y); MCFC matrix electrolytes; and SOM and MRE.

None of these discloses: (i) a molten chloride held by capillarity across a graded set of pore sizes, combined with a solid-oxide wafer cathode and a bubble-free gas-diffusion O₂ anode; (ii) a third-electrode copper sulfide getter held inside the matrix stack within a computed potential window; (iii) a cell voltage capped below MgO reduction so the residue can regenerate the separator; or (iv) recycling entrained salt with space vacuum, with indigenous evaporite chloride as makeup. Each element alone has relatives. The combination and the specific getter mechanism do not appear in prior art I found, though only three searches were run.

## References & Prior Art Checks
- Lomax et al., Planet. Space Sci. 180, 104748 (2020): https://www.sciencedirect.com/science/article/abs/pii/S0032063319301758
- Lomax et al., Acta Astronautica 234 (2025): https://www.sciencedirect.com/science/article/pii/S0094576525002504
- Meurisse et al., Planet. Space Sci. 211 (2022): https://www.sciencedirect.com/science/article/abs/pii/S0032063321002476
- Akay et al., npj Microgravity 8:56 (2022): https://www.nature.com/articles/s41526-022-00239-y
- McCoy et al., Nature 637 (2025): https://www.nature.com/articles/s41586-024-08495-6
- Frontiers Space Tech. (2024), modeling reduced-gravity electrolysis: https://www.frontiersin.org/journals/space-technologies/articles/10.3389/frspt.2024.1304579/full
- From recall (no URL): Chen, Fray & Farthing, Nature 407 (2000); Sahu & Allanore, molten sulfide electrolysis (MIT); MCFC LiAlO₂ matrix literature.

**Prior art searched:**
1. "molten salt electrolysis microgravity porous matrix capillary regolith oxygen": Frontiers 2024 modeling paper; Akay et al. npj Microgravity review (capillary-fed aqueous cell); JES 2026 molten-salt regolith review.
2. "Bennu sample evaporite minerals sodium carbonate brine Nature 2025": McCoy et al., Nature 637.
3. "FFC Cambridge lunar regolith oxygen extraction molten CaCl2 Lomax": Lomax 2020, Lomax 2025, Meurisse 2022.

---

### About the Reports
Each innovation on Unpatentable.org is published as a three-part open documentation set:
- **Innovation Report** – the master blueprint describing the first principals concept, mechanism, and rationale behind the invention.
- **Implementation Guide** – a step-by-step, practical manual detailing how to build or prototype the innovation. Includes estimated cost breakdown.
- **Industry Impact Report** – an analytical overview exploring the potential economic, industrial, and societal effects of the innovation.

Together, these documents form a complete public disclosure package — enabling researchers, developers, and policymakers to understand, replicate, and build upon each invention.

---

### Explore this Innovation
- [Innovation Report](https://unpatentable.org/innovation/capillary-matrix-molten-salt-cartridge-with-copper-sulfide-getter-for-asteroid-oxygen-and-metal)
- [Implementation Guide](https://unpatentable.org/innovation/implementation-guide-capillary-matrix-molten-salt-cartridge-with-copper-sulfide-getter-for-asteroid-oxygen-and-metal)
- [Industry Impact Report](https://unpatentable.org/innovation/industry-impact-report-capillary-matrix-molten-salt-cartridge-with-copper-sulfide-getter-for-asteroid-oxygen-and-metal)

### Download PDFs
- [Innovation Report (PDF)](https://unpatentable.org/wp-content/uploads/2026/11/Capillary-Matrix-Molten-Salt-Cartridge-with-Copper-Sulfide-Getter-for-Asteroid-Oxygen-and-Metal.pdf)
- [Implementation Guide (PDF)](https://unpatentable.org/wp-content/uploads/2026/11/Implementation-Guide-Capillary-Matrix-Molten-Salt-Cartridge-with-Copper-Sulfide-Getter-for-.pdf)
- [Industry Impact Report (PDF)](https://unpatentable.org/wp-content/uploads/2026/11/Industry-Impact-Report-Capillary-Matrix-Molten-Salt-Cartridge-with-Copper-Sulfide-Getter-fo.pdf)

---

**Timestamps:**
- [View Main Innovation Report on Arweave](https://arweave.net/pnKtNQCZ9PVwrdJ_Pc1iBlq69cQYa3yv0EaKBugi5BM)
- [View Implementation Guide on Arweave](https://arweave.net/7m_CD2NJKyCC9eExNi7CsjXMWUVvgvDYrwV_PTVuFWk)

**Suggested Citation:**
> Unpatentable.org (2026). *Capillary-Matrix Molten Salt Cartridge with Copper Sulfide Getter for Asteroid Oxygen and Metal.* Defensive Publication Series.
> https://unpatentable.org/innovation/capillary-matrix-molten-salt-cartridge-with-copper-sulfide-getter-for-asteroid-oxygen-and-metal

---

```json
{
  "domain": "Space & Aerospace",
  "subdomain": "Space Resources",
  "published": "2026-11-13",
  "arweave_main_tx": "pnKtNQCZ9PVwrdJ_Pc1iBlq69cQYa3yv0EaKBugi5BM",
  "license": "CC BY 4.0",
  "arweave_implementation_tx": "7m_CD2NJKyCC9eExNi7CsjXMWUVvgvDYrwV_PTVuFWk",
  "value_unlocked": "$12B"
}
```

Unpatentable.org is a public library of timestamped defensive publications —
open innovations released into the commons to prevent monopolization, democratize knowledge, and accelerate human progress.

License: CC BY 4.0
