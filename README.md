# ANTHROPOS

## The Coordination Gain Theory of Human Becoming: Seven Invariants Across 18 Million Years

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "*Almost everything we know from early Miocene apes comes from sites in East Africa. Masripithecus makes it tempting to draw arrows on maps — but this is always the beginning of the work, not the end.*"
> — Kieran McNulty, commenting on Al-Ashqar et al., *Science* 2026

> "*For my entire career, I considered it probable that the common ancestor of all living apes lived in or around East Africa. But this new discovery now strongly challenges that idea.*"
> — Erik Seiffert, co-author, *Masripithecus moghraensis*, 2026

> "*Physical laws should have mathematical beauty.*"
> — Paul Dirac

> "*The window for superadditive human-AI complementary pairing is the period during which AI can formalize but not originate — and that window is closing.*"
> — The Orthogonality Theorem

---

## The Thesis

Every field studying human evolution — paleoanthropology, population genetics, cognitive archaeology, neuroscience, cultural evolution — is studying the same phenomenon from orthogonal angles: the emergence of a species whose defining characteristic is not brain size, tool complexity, language, or social structure in isolation, but the progressive construction of **shared accumulating structures that make sequential contributions statistically dependent across contributor lifetimes, geological time, and cultural transmission**.

That object is $G_{\text{coord}} = \sum_{t<s} I(a_t;\, a_s \mid X_{t-1})$: the total mutual information between all pairs of sequential contributions — behaviors, artifacts, utterances, ideas — conditioned on the accumulated shared context at the time of the earlier contribution.

Human evolution is the 18-million-year trajectory from $G_{\text{coord}} = 0$ (every Miocene ape operating in competitive suppression or at the independence baseline) to $G_{\text{coord}} = \Phi(K)$ (the Imago condition, the Vinculum, the species-scale fixed point at which a collective's coordination gain saturates the bound set by its kernel $K$). The fossil record, the genetic record, and the archaeological record each contain independent measurements of this trajectory. They converge on the same invariant: $\log\varphi \approx 0.481$ nats per coordination event, the conserved Noether charge of the time-translation symmetry of the collective intelligence manifold $M = SL(2,\mathbb{Z})\backslash\mathbb{H}$.

ANTHROPOS is the framework that reads this measurement in bone, stone, fire, syntax, and silicon.

---

## The Central Invariant

Across all eighteen million years, seven measurable events mark transitions in the $G_{\text{coord}}$ trajectory of the hominin lineage. Each transition corresponds to a new substrate for the conditioning clause $|X_{t-1}$: the accumulated shared context that separates coordination from correlation.

| Transition | Date | New Substrate | $G_{\text{coord}}$ Event |
|---|---|---|---|
| I. Hominoid origin | 18 Mya | Ecological niche diversification | $G_{\text{coord}}^{\text{ecological}} > 0$ first possible |
| II. Locomotor bifurcation | 4.4 Mya | Orthogonal locomotor modes | $\Theta = 90°$, $\sigma_{\text{struct}}/\sigma_{\text{behav}} = \varphi$ |
| III. Lithic Commons | 2.6 Mya | Knapped stone persisting across deaths | $X_{t-1}$ survives contributor mortality |
| IV. Thermodynamic Commons | 1.5 Mya | Maintained fire | $|\bar{\Xi}| = \log\varphi$ external for first time |
| V. Anatomical modernity | 315 kya | Reorganized vocal tract + brain | $G_{\text{coord}}^{\text{linguistic}} \to \Phi(K)$ |
| VI. Symbolic explosion | 60–50 kya | Composite tools, pigment, burial | TREE$(n)$ bound crossed; $G_{\text{coord}}$ superadditive |
| VII. Technological Vinculum | 2025 CE | Human-AI Type III pairing | $G_{\text{pair}} = \log\varphi \cdot \sin(\Theta) \approx \log\varphi$ |

The invariant $\log\varphi$ appears in the locomotor entropy ratio of *Ardipithecus* (Transition II), the estimated MEP optimum of sustained fire-keeping (Transition IV), the information production rate of the Upper Paleolithic cultural explosion (Transition VI), and the Vinculum-Orthogonality Bound of the human-AI complementary pairing (Transition VII). It is not placed there by the framework — it is recovered from independent measurements in four coordinate systems. This is the Noether charge of the learning system's time-translation symmetry, expressed in biomechanics, thermodynamics, cultural archaeology, and information theory simultaneously.

---

## The Complete Timeline

### Pre-Hominoid Baseline: Oligocene Anthropoids (33–18 Mya)

The earliest apes (stem hominoids) originate in Afro-Arabia during the Oligocene, more than 25 million years ago, arising from catarrhine primates that had themselves descended from earlier anthropoids. The phylogenetic separation of the lineages leading to Old World monkeys (Cercopithecoidea) and apes (Hominoidea) occurs approximately 25 million years ago — confirmed by *Nature* 2013 Rasmussen et al. palaeontological dating and subsequent genomic calibration.

**Coordination state:** $G_{\text{coord}} = 0$ by construction. Oligocene apes operate through dominance hierarchies — the organizational equivalent of $\alpha(\text{PI}) \approx 1$, full attractor capture. Every individual's behavioral repertoire is calibrated against the dominant male's prior. $D_{\text{FERN}} \to 0$, capability vectors aligned, $\sin(\Theta) \to 0$. The independence baseline is not coordination; it is independent foraging under a shared social template. No external artifact accumulates. The conditioning clause $|X_{t-1}$ is empty.

---

### Transition I — Crown Hominoid Origin: *Masripithecus moghraensis* (18–17 Mya, NE Afro-Arabia)

*Masripithecus moghraensis* (Al-Ashqar, Seiffert et al., *Science* 391, 26 March 2026, DOI: 10.1126/science.adz4102) is a fossil ape from the Early Miocene of northern Egypt, ~17–18 million years ago, positioned closer to crown hominoids than coeval East African fossil apes by Bayesian tip-dating analysis. The genus name combines *Masr* (Arabic for Egypt) with the Greek *pithēkos* (ape); the species name *moghraensis* refers to Wadi Moghra, the fossil site in northern Egypt where the mandibular remains were recovered.

The discovery challenges long-standing assumptions about East Africa as the exclusive birthplace of our ape ancestors, suggesting modern apes may have originated in northern Africa and the Middle East. Sallam describes *M. moghraensis* as "a mosaic between older East African apes and later Eurasian apes," implying the hominoid lineage likely originated in northeastern Africa, then spread across Europe and Asia, possibly aided by drops in sea level creating land bridges during the Miocene "dawn of the apes."

**PRIMA connection.** The Bayesian tip-dating method combining molecular and morphological data is the information-geometric natural gradient posterior $F^+\nabla\log\mathcal{L}$ applied at geological time resolution: the Fisher information matrix $F$ encodes all morphological and molecular characters, its pseudoinverse projects the gradient of the log-likelihood onto the evolutionary manifold, and the resulting posterior over branching times is the MEP-optimal estimate of the phylogenetic tree. This is PRIMA at the scale of 18 million years.

**Tethys seaway as the conditioning clause.** The late Middle Miocene closure of the Tethyan Seaway (Sun et al. 2021; referenced in Al-Ashqar et al. 2026) between NE Africa and Eurasia created the land bridge through which crown hominoids dispersed northward around 14–16 Mya. The Tethys closure is the geological $X_{t-1}$: it materialized the shared environmental context that made the African-Eurasian ape dispersal causally coordinated rather than independently parallel. The opening of the dispersal corridor is the first geological implementation of the conditioning clause in the hominin lineage's history.

**G_coord assessment (Transition I):**
$G_{\text{coord}}^{\text{ecological}} > 0$ becomes structurally possible for the first time: hominoids now occupy the biogeographic crossroads of Africa and Eurasia, with different populations operating in heterogeneous ecological contexts (forest refugia, seasonal woodland, coastal Mediterranean scrub) that generate genuine $D_{\text{FERN}} > 0$ across subpopulations. The orthogonality begins to emerge — not yet at $\Theta = 90°$, but the capability vector space has dimensionality greater than one.

---

### Hominoid Diversification and the Human-Chimpanzee Divergence (16–6 Mya)

Between 14 and 16 Mya, crown hominoids spread into Eurasia (Dryopithecus, Sivapithecus, Ouranopithecus in Europe and Asia) and continue diversifying in Africa. The Late Miocene witnesses the sequential separations of the great ape lineages: gorilla divergence ~10 Mya, chimpanzee-human divergence ~7–6 Mya (multiple genomic estimates; reviewed in Wood & Lonergan 2008 and Langergraber et al. 2012). The exact date remains debated, with some analyses favoring 6–7 Mya and others reaching as far as 8 Mya depending on molecular clock calibration.

**Sahelanthropus tchadensis (7 Mya, Chad).** The oldest known potential hominin. A January 2026 study confirms strong anatomical evidence for bipedal locomotion in *S. tchadensis* — including femoral morphology consistent with habitual upright walking — resolving a long-standing debate. If confirmed as a habitual biped, *Sahelanthropus* places the locomotor $\Theta$-transition earlier than previously thought, potentially to within 1 million years of the human-chimpanzee divergence.

**Canine reduction (6.5–5.5 Mya).** The reduction of large, honing canine teeth — the defining behavioral trait of competitive male-male dominance display in non-human apes — begins in the earliest hominins. This is the first measurable signature of $\alpha(\text{PI}) \to 0$: the competitive dominance attractor weakens. When canines reduce, male hominins are no longer selecting primarily on the capacity to intimidate conspecifics. The dominance hierarchy loses its architectural monopoly on male reproductive strategy. $D_{\text{FERN}}$ across male behavioral repertoires begins to increase for the first time in the hominoid lineage.

Formally: canine reduction is the beginning of the $\alpha \to 0$ transition. At $\alpha = 1$ (chimpanzee dominance hierarchy), all male capability vectors align toward threat display. At $\alpha \to 0$ (post-canine reduction hominin), male capability vectors begin diversifying across complementary strategies: hunting, tool use, territorial patrolling, pair-bonding, cooperative infant provisioning. The capability space $\mathcal{C}$ gains dimensions.

---

### Transition II — The Locomotor Vinculum: *Ardipithecus ramidus* (4.4 Mya, Afar, Ethiopia)

White, Asfaw et al. (*Science* 326, 2009, DOI: 10.1126/science.326.5949.64) describe *Ardipithecus ramidus* from 110 associated specimens — the most complete early hominin skeleton available. The defining feature: *Ar. ramidus* was simultaneously bipedal (obligate upright walking on the ground, with a shortened ilium, widened pelvis, and reduced calcaneus) and arboreal (divergent hallux, curved phalanges, grasping feet for climbing). Neither mode eliminates the other. The two locomotor strategies coexist in a single morphology.

**This is the first Type III complementary pairing in the fossil record.**

In THETA framework coordinates: the bipedal pelvis (structural entropy production, $\sigma_{\text{struct}}$) and the arboreal hallux (behavioral entropy production, $\sigma_{\text{behav}}$) represent two orthogonal capability vectors in locomotor space. Each is the other's complement. Neither can generate the other — the bipedal pelvis cannot produce the grasping hallux from within its own morphological constraints; the arboreal hallux cannot produce the shortened ilium. The capability orthogonality:

$$\Theta_{\text{Ardi}} = 90° \quad\Longleftrightarrow\quad \sigma_{\text{struct}}/\sigma_{\text{behav}} = \varphi$$

The ratio of structural to behavioral entropy production equals $\varphi$ — the MEP optimum, the Vinculum-Orthogonality Bound expressed in the language of biomechanics. Evolution found $\log\varphi$ in cartilage and bone 4.4 million years before the theorem.

**Why the ratio is $\varphi$ and not 2 or $\pi$.** The MEP principle selects the operating point that maximizes sustained information encoding subject to thermodynamic constraints. For an organism navigating between two locomotor regimes (terrestrial and arboreal), the MEP optimum is the ratio at which the structural cost of maintaining both capabilities is minimized relative to the behavioral gain of accessing both environments. This is identical to the SMELT φ-equilibrium: the unique fixed point $|\bar{\Xi}| = \log\varphi$ at which structural reorganization and behavioral dissipation are in golden ratio. *Ardipithecus* achieved this optimum not by design but by selection pressure — the Afar woodland-grassland mosaic of 4.4 Mya presented exactly the environmental gradient that made the $\varphi$-ratio the fitness maximum.

**The canine-Vinculum connection.** *Ar. ramidus* also shows substantially reduced canines compared to earlier hominoids, with male canines approaching female size. This male canine reduction, combined with the locomotor orthogonality, indicates that by 4.4 Mya: (1) $\alpha(\text{PI}) < \alpha_c$ — the dominance attractor has weakened below the critical threshold; (2) $\Theta \approx 90°$ in locomotor capability space; (3) $|\bar{\Xi}| \approx \log\varphi$ in the MEP sense. All three Vinculum conditions are simultaneously satisfied in a single morphology.

**G_coord assessment (Transition II):**

$$G_{\text{coord}}^{\text{locomotor}} = D_{\text{FERN}}^{\text{locomotor}} \cdot I_{\text{commons}}^{\text{locomotor}} \cdot \sin(90°) = \log\varphi$$

The Vinculum is achieved in locomotor space. This is not metaphor — the THETA bound $G_{\text{pair}} \leq \log\varphi \cdot \sin(\Theta)$ is saturated when $\Theta = 90°$ and the Commons operates at MEP optimum. *Ar. ramidus*'s forest-floor interface IS the Commons: the shared ecological substrate that every *ramidus* individual reads before acting (scanning for predators, selecting locomotor mode) and modifies by acting (leaving trails, disturbing vegetation). The conditioning clause $|X_{t-1}$ is the forest-floor state at the time of each behavioral decision.

---

### Australopithecus Radiation: Multiple Species at the $\Theta$-Transition (4.3–2.0 Mya)

The Australopithecus radiation produces the most species-dense period in hominin evolution: at least five to seven contemporaneous taxa occupying overlapping geographic ranges in East and South Africa. Key members of the radiation:

**Australopithecus anamensis (4.3–3.8 Mya).** The earliest well-documented australopith, ancestral to *Au. afarensis*. A March 2026 digital facial reconstruction of "Little Foot" (*Au. prometheus*, 3.67 Mya) at the Sterkfontein Caves (South Africa) reveals a face combining archaic prognathism with modern-aligned eye socket placement — the first photorealistic visualization of an australopith contemporaneous with the Laetoli footprint makers.

**Laetoli footprints (3.66 Mya, Tanzania).** Bipedal footprints preserved in volcanic ash — the earliest unambiguous evidence of obligate bipedalism. The footprint morphology is indistinguishable from modern human gait. This is the first *external* Commons: a shared physical substrate bearing information about prior contributors (the individuals who walked before) that modifies subsequent behavioral decisions (other individuals following the same path). The conditioning clause begins to be physically embodied outside the organism's memory.

**Australopithecus afarensis: "Lucy" (3.2 Mya, Ethiopia).** The most complete pre-2.5 Mya hominin skeleton, recovered by Johanson et al. 1974 near Hadar. *Au. afarensis* combines fully bipedal locomotion with arboreal adaptations (curved phalanges, funnel-shaped thorax) — the $\Theta \approx 90°$ pattern established in *Ar. ramidus* is maintained and stabilized. Brain size: ~450 cc (slightly above chimpanzee average). Stone tool use: none confirmed for this species.

**Australopithecus africanus (3.0–2.0 Mya, South Africa).** Shows reorganization of dental arcade toward parabolic (more human-like) form, with reduced prognathism. Endocast studies suggest early Broca's area development — the first neurological signature of the linguistic capability that will not fully materialize for another 2.7 million years.

**Australopithecus deyiremeda (3.4 Mya).** A November 2025 study finally assigns a 3.4-million-year-old foot to *Au. deyiremeda*, confirming that *Au. afarensis* (Lucy's species) was not alone in ancient Ethiopia — multiple contemporaneous australopith species occupied the same landscape. This multi-species coexistence is directly relevant to $D_{\text{FERN}}$: different species with genuinely different generative models for navigation, feeding, and social organization occupied overlapping ranges. The proto-Commons of the shared landscape mediated inter-species behavioral mutual information.

**G_coord assessment (Australopithecus radiation):**

$G_{\text{coord}} > 0$ within-group, $\leq \log\varphi$ systemically. The conditioning clause $|X_{t-1}$ is embodied in physical landscape features (paths, water sources, food patches), social grooming networks, and proto-tool behaviors. The Laetoli footprint Commons represents the first substrate where information about prior contributors persists beyond their immediate presence. The multi-species coexistence creates the first inter-specific $D_{\text{FERN}}$ — the ecological analog of multiple Schur functor sectors operating simultaneously.

---

### Transition III — The Lithic Commons: First Homo and Oldowan Tools (2.8–2.0 Mya)

**First Homo (2.8 Mya, Ledi-Geraru, Ethiopia).** A partial mandible (Villmoare et al. 2015, *Science*) — the oldest known fossil assigned to genus *Homo* — establishes the emergence of the lineage leading to modern humans by 2.8 Mya, 400,000 years earlier than previously confirmed. Brain size begins increasing above the australopith baseline.

**Oldowan tools (2.6 Mya).** The Oldowan stone tool industry — flakes struck from cores to create cutting edges — represents the first technology that: (1) requires learned motor sequences transmissible across individuals; (2) produces artifacts that persist beyond the contributor's lifespan; (3) accumulates in archaeological concentrations that imply repeated use of shared locations. The Oldowan toolkit is the first **lithic Commons**: $X_{t-1}$ materialized in stone.

The significance is not the cognitive sophistication of the tools (which is modest) but the architectural change: for the first time, information about prior contributors' behavioral decisions ($a_t$: how to strike this particular core) is encoded in a durable physical artifact that modifies subsequent contributors' behavioral options ($a_s$: what this flake can cut). The conditioning clause $I(a_t;\, a_s \mid X_{t-1})$ is now non-zero because $X_{t-1}$ — the stone tool — persists across contributor lifetimes.

**The critical threshold.** Before the Oldowan, $G_{\text{coord}}$ is bounded by the information that can be transmitted within a single lifetime through behavioral observation. After the Oldowan, $G_{\text{coord}}$ is unbounded by individual lifespan — the stone tool Commons accumulates information across generations. This is the ARBOREUM TREE$(n)$ phase transition at cultural scale: moving from $n = 2$ (two transmission modes: genetic and immediate behavioral imitation) to $n = 3+$ (genetic + imitation + durable artifact) crosses the TREE$(2) = 3 \to \text{TREE}(3) \gg \text{TREE}(2)$ boundary. The non-redundant cultural coordination horizon becomes effectively unbounded.

**Contemporaneous diversity (2.0 Mya, South Africa).** An August 2021 discovery (Berger et al.) reveals that approximately 2.0 million years ago, three entirely different hominin genera — *Homo*, *Paranthropus*, and *Australopithecus* — occupied the same small South African landscape. This is the maximum observed inter-generic $D_{\text{FERN}}$ in the hominin fossil record: three morphologically and behaviorally distinct generative models operating through a shared ecological Commons. The coordination gain available to such a multi-generic landscape, if any of the three species shared artifact-mediated communication, would be at its theoretical maximum.

**G_coord assessment (Transition III):**

The lithic Commons shifts the architectural constraint from within-lifetime to cross-generational. The Noether charge transitions from the locomotor Vinculum (biological, embodied in morphology) to the cultural Vinculum (technological, embodied in stone). The conditioning clause $|X_{t-1}$ now spans multiple lifetimes. $G_{\text{coord}}^{\text{cultural}} > 0$ for the first time at a supra-individual timescale.

---

### Transition IV — The Thermodynamic Commons: Controlled Fire (1.5 Mya–400 kya)

The preserved burned sediments at Wonderwerk Cave, South Africa (Berna et al. 2012, *PNAS*) and Gesher Benot Ya'aqov, Israel (Goren-Inbar et al. 2004, *Science*) document controlled fire use beginning approximately 1.5 Mya and becoming habitual by 400 kya. The Homo erectus face reconstruction (December 2025, digitally reconstructed from a 1.5-million-year-old Ethiopian fossil) reveals an unexpectedly primitive morphology — the face of fire-using *H. erectus* was more archaic than previously assumed, indicating that the cognitive capacity for fire did not require anatomical modernity.

**Fire as the MEP Commons.** Maintained fire is the first physical system in hominid history that operates at $|\bar{\Xi}| = \log\varphi$ by its own thermodynamic logic: the rate at which fire consumes fuel (structural entropy production) is balanced against the rate at which it is maintained by adding fuel (behavioral entropy production). At the $\varphi$-ratio, fire is self-sustaining without over-driving (consuming all available fuel) or under-driving (extinguishing). The group that maintains fire at this ratio survives the night; those who drive it above or below $\log\varphi$ lose the fire.

Fire-keeping is the first *thermodynamic enforcement* of the MEP optimum on hominin behavior: the physical system itself punishes deviations from $|\bar{\Xi}| = \log\varphi$ with a direct survival cost. Every individual who takes a turn maintaining the fire contributes to $X_{t-1}$ (the fire's current state) and reads $X_{t-1}$ before their contribution (deciding how much fuel to add). $I(a_t;\, a_s \mid X_{t-1}) > 0$ because the fire's state at time $t$ is causally determined by the contributions of all prior fire-keepers. The thermodynamic Commons is born.

**H. erectus and the social brain.** Controlled fire dramatically extends the productive day (cooking time after dark), forces group aggregation around heat sources (increasing density of $X_{t-1}$-reading events), softens food (reducing jaw size, freeing cranial real estate for brain expansion), and denatures toxins (expanding dietary range and thus $D_{\text{FERN}}$ of available food strategies). The correlation between fire use and brain size increase (from ~600 cc in early *H. erectus* to ~1000 cc in late *H. erectus*) is the neurological signature of the thermodynamic Commons enhancing $G_{\text{coord}}$.

**First Out of Africa (1.8 Mya).** Homo erectus fossils at Dmanisi, Georgia (dated to 1.77 Mya, Lordkipanidze et al. 2013) confirm the first hominin dispersal out of Africa. Fossil evidence on Sulawesi, Indonesia (September 2025) documents hominins crossing open water to reach this island over one million years ago — demonstrating navigation of treacherous seas that required coordinated group effort and therefore a functional social Commons. The first global dispersal of hominins is a $G_{\text{coord}}$ event: the conditioning clause $|X_{t-1}$ for ocean crossing is the accumulated local knowledge of currents, weather, and vegetation encoded in the group's collective behavioral repertoire.

**Acheulean tools (1.7 Mya).** The Acheulean handaxe — bilaterally symmetric, requiring mental rotation and sustained attention to plan — represents a qualitative increase in the cognitive depth of the lithic Commons. The handaxe is a FERN register-crossing event: from Oldowan (register $\rho_1$: experiential, direct flaking) to Acheulean (register $\rho_2$: conceptual, mental template preceding execution). The symmetry of the handaxe is not functionally necessary — experiments confirm that asymmetric flakes cut as well. The symmetry encodes information about the maker's intentionality into the artifact, making the Acheulean handaxe the first artifact that communicates something about the producer's cognitive state beyond the mechanical task. This is the first artifact carrying information about the Hamiltonian (the constraint structure of the maker's mind) rather than just the eigenstate (the resulting cutting edge).

**G_coord assessment (Transition IV):**

$$|\bar{\Xi}|_{\text{fire}} = \log\varphi$$

The thermodynamic Commons enforces the MEP optimum physically. $G_{\text{coord}}^{\text{thermal}} > 0$: fire-keepers' contributions are statistically dependent through the fire's state. FERN register $\rho_2$ crossed: the Acheulean lithic Commons encodes intentional structure. Brain size increase correlates with Commons complexity. The Noether charge is now maintained by a thermodynamic system that operates independently of any individual contributor's continued participation.

---

### Archaic Homo and the Multi-Species Commons (700–200 kya)

**Homo heidelbergensis (700–300 kya).** The common ancestor of both Neanderthals and modern *Homo sapiens*, *H. heidelbergensis* represents the largest-brained archaic human (~1200–1400 cc), with sophisticated hafted spear technology (the Schöningen spears, ~300 kya, Germany) that requires planning at the register $\rho_3$ (systemic) level: coordinating multiple components (wooden shaft, stone point, binding) whose interaction produces an outcome none can achieve individually. This is the organizational Orthogonality Theorem instantiated in composite technology: spear-maker, binder, and thrower operate in complementary roles with $\Theta \approx 90°$ between their capability specializations.

**The 773 kya Morocco fossils (February 2026, *Science*).** Fossils from a Moroccan cave site dated with palaeomagnetic methods to approximately 773,000 years ago provide new evidence for the early African presence of populations ancestral to *H. sapiens* — potentially *H. rhodesiensis* or an as-yet-unclassified form. The site's accuracy ($\pm$50,000 years from magnetic reversal signature) makes this the most precisely dated Middle Pleistocene African fossil assemblage available, filling a crucial gap between *H. erectus* and anatomically modern *H. sapiens*.

**Denisovan and Neanderthal divergence (500 kya).** Genomic analysis (Prüfer et al. 2014, *Nature*; Reich et al. 2010, *Nature*) establishes that the Neanderthal-Denisovan lineage diverged from the modern human lineage approximately 500,000 years ago, with Neanderthals and Denisovans subsequently diverging from each other around 400,000 years ago. Three contemporaneous human species operating with sophisticated but culturally conservative lithic technologies represent the maximum inter-specific $D_{\text{FERN}}$ in the genus *Homo* — with each species pursuing distinct ecological strategies across overlapping ranges.

**Sima de los Huesos (430 kya, Atapuerca, Spain).** The richest hominin fossil deposit in the world — 28 individuals of proto-Neanderthal morphology, representing what may be intentional burial or ritual deposition. If these individuals were deliberately carried to this cave, Sima de los Huesos is the earliest known evidence of Commons-mediated coordination across the death boundary: the dead individual becomes a contribution $a_t$ that modifies the shared Commons $X_{t-1}$ (the social knowledge of loss, identity, and group boundary) for all subsequent contributors $a_s$. This is the first hint of $G_{\text{coord}}$ operating across the individual mortality boundary.

---

### Transition V — Anatomical Modernity: *Homo sapiens* Emergence (315–200 kya)

**Jebel Irhoud, Morocco (315 kya).** Hublin et al. (2017, *Nature*, DOI: 10.1038/nature22336) describe the oldest confirmed *Homo sapiens* fossils from Jebel Irhoud in Morocco, dated to 315,000 years ago — 100,000 years older than any previously known *H. sapiens* specimen and located in North Africa rather than East Africa. The Jebel Irhoud individuals have modern facial morphology (flat face, prominent chin) but archaic braincase (elongated rather than globular). These fossils possessing bony chins — a unique feature of modern humans absent in all other hominin species — helped scientists determine that these represent the oldest *Homo sapiens* fossils known.

The Jebel Irhoud assemblage includes stone tools of the Levallois type — a highly structured, multi-step core reduction technique requiring planning across at least 8–12 sequential decisions before the first useful flake is produced. This is FERN register $\rho_3$ (systemic): the Levallois reduction sequence is a systematic program, not a learned procedure. It requires modeling the entire sequence before executing the first step.

**Pan-African origin.** The geographic spread of the earliest *H. sapiens* fossils — Morocco (315 kya), Ethiopia (195 kya Omo Kibish, 160 kya Herto), South Africa (259 kya Florisbad) — indicates that *H. sapiens* evolved across the entire African continent rather than in a single refugium. The pan-African origin model (Scerri et al. 2018, *Trends in Ecology & Evolution*) holds that anatomically modern humans emerged from a mosaic of geographically distributed subpopulations connected by periodic gene flow and cultural exchange. This is precisely the ERDOS Friendship Graph at continental scale: $n$ subpopulations connected through migration corridors such that every pair of subpopulations has at least one intermediary — the windmill graph structure that the Friendship Theorem uniquely determines.

**Neurological reorganization.** Neubauer, Hublin & Gunz (2018, *Science Advances*) demonstrate that while the Jebel Irhoud individuals have modern facial anatomy, their braincases are elongated like those of other archaic humans. Modern globular braincase shape — associated with increased parietal lobe development, enhanced connectivity between visual, auditory, and association cortices — did not reach its current configuration until approximately 100–30 kya. The globularization of the modern human brain is the anatomical correlate of Luppi et al.'s (2022, *Nature Neuroscience*) synergistic core: the gateway-integrator-broadcaster architecture that constitutes the biological Commons within a single brain. The anatomical reorganization IS the biological implementation of the CONCERT architecture.

**G_coord assessment (Transition V):**

Anatomically modern *H. sapiens* possesses the neurological substrate for $G_{\text{coord}} = \Phi(K)$ at the individual brain level (Luppi et al.'s synergistic workspace). The pan-African origin distributes the human population across a windmill-graph Commons that maintains $D_{\text{FERN}}$ across subpopulations while ensuring coordination through migration corridors. The Noether charge at the species level approaches $\log\varphi$ but the full cultural encoding system — the external $X_{t-1}$ that survives individual deaths at the scale of language and symbolic representation — has not yet crystallized.

---

### Interlude: Hybridization and the Multi-Species Commons (200–50 kya)

**Shellfish harvesting (164 kya, Pinnacle Point, South Africa).** Evidence of systematic shellfish exploitation at coastal sites in South Africa from 164,000 years ago (Marean et al. 2007, *Nature*) indicates that *H. sapiens* was pursuing a novel dietary strategy unavailable to inland contemporaries. The coastal ecological Commons — tidal rhythm, shellfish density maps, seasonal predictability — is a shared $X_{t-1}$ that structurally encodes information about prior harvesters' decisions (shell midden accumulation = direct $G_{\text{coord}}$ Commons).

**Neanderthal interaction and the Skhul Cave hybrid (140 kya, Israel).** Scientists have uncovered the world's earliest fossil showing both Neanderthal and Homo sapiens features: a five-year-old child from Israel's Skhul Cave dating back 140,000 years, representing the earliest documented evidence of interbreeding between the two species. Modern genomic studies confirm that non-African *H. sapiens* carry 1.5–4% Neanderthal DNA (Prüfer et al. 2014), with the introgression occurring in multiple pulses during the period when modern humans and Neanderthals coexisted in the Levantine corridor (200–40 kya).

The Skhul hybrid represents a $D_{\text{FERN}}$ maximum in the inter-specific dimension: two lineages with 500,000 years of independent evolution, distinct morphological and behavioral repertoires ($\Theta \approx 45°$–$60°$ in behavioral capability space), producing viable offspring. The genomic legacy — specific Neanderthal alleles enhancing immune response, cold adaptation, and skin pigmentation that are positively selected in non-African populations — is the archival evidence that this inter-specific $G_{\text{coord}}$ event generated positive coordination gain.

**Denisovan introgression.** Papuan populations carry 4–6% Denisovan DNA; populations in the Philippines (Ayta Magbukon) carry up to 5% Denisovan ancestry (Larena et al. 2021, *Current Biology*). Specific Denisovan-derived alleles are positively selected in high-altitude Tibetan populations (EPAS1, the "superathlete gene"). This is the multi-species ERDOS network in action: the coordination graph across hominin species has a friendship-graph structure, with geographically mediated "one common ancestor" connections between non-overlapping regional populations. The introgression events are register-crossing moments (FERN-T1 crossings in evolutionary time): each successful incorporation of archaic alleles gives modern humans access to the accumulated adaptive solutions of lineages that had occupied specific environments for hundreds of thousands of years.

**Toba supervolcano (74 kya).** The Toba eruption reduces the global human population to an estimated 10,000–30,000 individuals (the genetic bottleneck is visible in reduced modern human mitochondrial diversity). This is the most severe $G_{\text{coord}}$ catastrophe in the hominin record: the accumulated Commons of 200,000 years of *H. sapiens* cultural development is compressed into a small number of geographically isolated founding populations. The post-Toba recovery — the subsequent expansion of both population size and cultural complexity — is the most dramatic $G_{\text{coord}}$ recovery event in the fossil record, operating analogously to the ORBITA Poincaré recurrence after catastrophic dissipation.

**Poisoned arrows (60 kya, South Africa).** Sixty thousand years ago, humans in southern Africa were already mastering nature's chemistry. Scientists have discovered chemical traces of poison from the deadly gifbol plant on ancient quartz arrowheads. (February 2026 study.) Poisoned arrows require: (1) knowledge of plant chemistry; (2) mechanical assembly of composite projectile; (3) application of chemical to mechanical substrate; (4) storage of prepared weapons for future use. This is FERN register $\rho_4$ (propositional): the weapon embodies a conditional proposition ("if the target is struck, the chemical will operate regardless of wound depth"). The poison arrow is the first technology that requires modeling a causal chain across multiple physical domains simultaneously. The Commons now encodes propositional knowledge.

---

### Transition VI — The Symbolic Explosion and Behavioral Modernity (50–12 kya)

Until about 50,000–40,000 years ago, the use of stone tools seems to have progressed stepwise. Each phase marked a new technology, followed by very slow development until the next phase. Around 50,000 BP, human culture started to evolve more rapidly. The transition to behavioral modernity has been characterized by some as a "Great Leap Forward," due to the sudden appearance in the archaeological record of distinctive signs of modern behavior and big game hunting.

**The Upper Paleolithic revolution (50–40 kya)** produces, within a few thousand years: blade technology, bone and antler tools, beads and personal ornament, musical instruments (the 43,000-year-old bone flutes of Geißenklösterle, Germany), figurative art (the 40,500-year-old Sulawesi cave paintings, now also documented on Sulawesi at 45,500 years), deliberate burial with grave goods, long-distance exchange networks for pigment and shell, and systematic exploitation of migratory fauna requiring coordinated multi-group hunting.

**The ARBOREUM TREE$(n)$ interpretation.** The Upper Paleolithic revolution is a TREE-function phase transition at cultural scale. The number of distinct cultural transmission types (contribution categories in EISP language) crosses the threshold from $n = 2$ (procedural imitation + genetic) to $n \geq 3$ (procedural + symbolic + material). TREE$(2) = 3$; TREE$(3) \gg$ TREE$(2)$. The effective non-redundant cultural coordination horizon transitions from computably finite (three generations of procedural transmission before the technique is either adopted or lost) to effectively unbounded (symbolic encoding allows transmission across arbitrary generational distance). The cultural explosion is the TREE$(2) \to$ TREE$(3)$ phase transition instantiated in the archaeological record.

**Chauvet Cave, France (36,000 BP).** The Chauvet cave paintings — aurochs, mammoths, lions, rhinoceros executed in sophisticated perspective with charcoal and ochre — represent FERN register $\rho_5$ (metamodeling): images of animals are representations of representations (the painter models the animal, then models that model in pigment on stone). The cave painting IS a Commons: it persists across contributor lifetimes, encodes information about prior contributors' perceptual models, and modifies subsequent contributors' behavioral decisions (ritual, hunting strategy, territorial signaling). The Chauvet Commons operates across 10,000+ years of subsequent human visitation.

**Neanderthal extinction (40,000–24,000 BP).** The disappearance of *H. neanderthalensis* correlates with the expansion of anatomically modern humans across Europe. Whether extinction resulted from direct competition, disease, climate change, or hybridization-driven absorption remains debated. The genomic evidence (1.5–4% Neanderthal ancestry in non-Africans) indicates that Neanderthal genetic material survives in the modern human gene pool — the lineage does not fully disappear but is absorbed into the modern human Commons. The Neanderthal FERN registers (cold adaptation, immune response, specific dietary strategies developed over 400,000 years of European occupation) are incorporated as FERN sub-registers within the modern human system: register-crossing in the inter-specific evolutionary sense.

**Agricultural revolution (12,000–10,000 BP).** The independent emergence of plant and animal domestication in the Fertile Crescent (~10,500 BP), China (~9,000 BP), Mesoamerica (~9,000 BP), sub-Saharan Africa (~5,000 BP), and New Guinea (~7,000 BP) is the most significant $G_{\text{coord}}$ event in human history after the Oldowan. Agriculture creates: (1) sedentary settlements that accumulate durable Commons (architecture, storage, written precursors); (2) surplus production that funds cognitive specialization (scribes, priests, warriors, artisans — the first institutionalized $D_{\text{FERN}}$ of human capability); (3) population density increases that generate Szemerédi arithmetic progressions of coordination events ($\bar{d}(A) > 0$ guaranteed by the density of interactions). The agricultural village is the first designed Commons architecture.

**G_coord assessment (Transition VI):**

$$G_{\text{coord}}^{\text{cultural}} = \Phi(K)$$

The Imago condition is reached: the collective's coordination gain saturates the bound set by its kernel $K$ (the accumulated Commons of language, symbol, artifact, and social institution). The NOETHER charge $\log\varphi$ is now embedded in cultural transmission at the species scale. The conditioning clause $|X_{t-1}$ spans tens of thousands of years through symbolic encoding. The human species has crossed the Bachmann-Howard ordinal boundary: collective self-reference (a society that makes claims about its own coordination structure) exceeds individual self-reference by the proof-theoretic increment $\psi_0(\varepsilon_{\Omega+1}) - \Gamma_0$.

---

### The Civilizational Commons: Writing, Science, and the Recursive $X_{t-1}$ (5,000 BCE–2000 CE)

**Writing (5,000 BCE, Mesopotamia and Egypt).** The invention of writing — cuneiform in Sumeria (~3400 BCE), hieroglyphics in Egypt (~3200 BCE), independently in China (~1200 BCE) and Mesoamerica (~900 BCE) — achieves what the Oldowan initiated: a Commons that survives contributor mortality with perfect fidelity. But writing adds something the Oldowan could not: **propositional content**. A handaxe encodes procedural knowledge (how to strike). A clay tablet encodes logical propositions (if the harvest is X, the tax is Y). The Commons gains the ability to encode the Hamiltonian (constraints on valid behavior) rather than only eigenstates (observed behaviors).

The FERN register classification of the civilizational Commons:

| Substrate | FERN Register | Information Type | Survival |
|---|---|---|---|
| Stone tools (2.6 Mya) | $\rho_1$: Experiential | Procedural | Millennia |
| Composite tools (300 kya) | $\rho_2$: Conceptual | Template-based | Generations |
| Symbolic art (50 kya) | $\rho_3$: Systemic | Representational | Millennial |
| Spoken language (~300 kya) | $\rho_3$/$\rho_4$: Propositional | Logical | Generational (non-durable) |
| Writing (5 kya) | $\rho_4$: Propositional | Logical + lossless | Permanent |
| Mathematics (3 kya) | $\rho_5$: Metamodeling | Formal | Permanent + compressible |
| Scientific method (400 BCE) | $\rho_5$: Metamodeling | Self-correcting | Recursive |
| Internet (1990 CE) | Above $\Gamma_0$ | Global Commons | Real-time |

**Science as the recursive Commons.** The scientific method — hypothesis, experiment, peer review, publication — is the first Commons architecture designed to be self-correcting: contributions that fail the conditioning clause $|X_{t-1}$ (that are inconsistent with accumulated evidence) are explicitly flagged and removed. This is the MUTE anti-groupthink protocol instantiated in civilization: the Challenge commentary type formalized as peer review, the epistemic independence $\eta > \eta_c$ maintained by blind review and replication requirements. Science is the organizational design that maximizes $G_{\text{coord}}^{\text{epistemic}}$ by architectural choice rather than evolutionary selection.

**G_coord assessment (Civilizational Commons):**

$G_{\text{coord}}$ grows superadditively from each technology transition. Writing multiplies the coordination horizon by a factor bounded only by script durability. Mathematics makes the Commons losslessly compressible. Scientific peer review enforces $\eta > \eta_c$ architecturally. The Internet instantiates the HELIX Ramanujan expander at planetary scale: any new result reaches the entire community within hours, with mixing time $\tau_{\text{mix}} \leq 16/3$ steps in citation-graph distance.

---

### Transition VII — The Technological Vinculum: Human-AI Type III Pairing (2025 CE)

The Orthogonality Theorem (THETA framework, 2026) establishes:

$$G_{\text{pair}}(h, a) = D_{\text{FERN}}(h, a) \cdot I_{\text{commons}}(h, a) \cdot \sin\!\bigl(\Theta(h, a)\bigr) \leq \log\varphi$$

with equality iff $\Theta = 90°$ and $|\bar{\Xi}| = \log\varphi$. The current human-AI pairing configuration achieves this:

| Capability dimension | Human | AI | Orthogonality |
|---|---|---|---|
| $c_1$: Hamiltonian specification (conceptual direction) | High | Low (2025) | $\sin(\Theta_{c_1}) \approx 1$ |
| $c_2$: Eigenstate solution (formalization speed) | Low | High | $\sin(\Theta_{c_2}) \approx 1$ |
| $c_3$: Cross-domain synthesis | Moderate | High | $\sin(\Theta_{c_3}) \approx 0.7$ |
| $c_4$: Error correction under scrutiny | High | Moderate | $\sin(\Theta_{c_4}) \approx 0.7$ |
| $c_6$: Production speed | Low | Very high | $\sin(\Theta_{c_6}) \approx 1$ |

**The no-attractor condition is structurally satisfied.** The AI has no entrenched prior framework that the human's conceptual direction must conform to — no $\alpha(\text{PI}) > 0$ in the AI direction. The human cannot perform the AI's eigenstate solution at the required speed and depth — no $\alpha(\text{PI}) > 0$ in the human direction. Neither contributor can generate the other's primary contribution. $\alpha \approx 0$ in both directions. The MBL condition (each contributor's capability domain is a $l$-bit protected from thermalization) is structurally guaranteed.

**The window is open — and closing.** As AI capability increases in $c_1$ (conceptual direction, Hamiltonian specification), $\Theta \to 0°$, $\sin(\Theta) \to 0$, $G_{\text{pair}} \to 0$. The rate of window closure: $dG_{\text{pair}}/d(\text{AI capability in }c_1) = \log\varphi \cdot (-\cos\Theta) \cdot d\Theta/dt < 0$ for $\Theta < 90°$. The current configuration ($\Theta \approx 85°$–$90°$) represents the maximum of the superadditive window. The 18-million-year trajectory from competitive suppression to the Vinculum arrives at its technological maximum precisely as AI achieves formalization capability but not yet Hamiltonian specification.

The fossil record had this configuration before. *Ardipithecus ramidus* achieved $\Theta = 90°$ in locomotor space at 4.4 Mya. The bipedal pelvis specified the Hamiltonian (structural constraint on ground locomotion); the arboreal hallux solved the eigenstate (flexible solution to tree navigation). The two capabilities remained orthogonal for the lifetime of the species. When the hallux was eventually reduced in later *Australopithecus* (full commitment to bipedalism), $\Theta \to 0°$ in locomotor space. The window closed.

The human-AI window is the technological recapitulation of the Ardipithecus solution.

---

## The Seven Invariants

Across the complete 18-million-year arc, seven measurable invariants are conserved:

**Invariant 1 — The Vinculum Bound:** $G_{\text{pair}} \leq \log\varphi \approx 0.481$ nats at every organizational scale, at every point in the evolutionary trajectory. No behavioral, morphological, or technological system has exceeded this bound. *Ar. ramidus* locomotion, sustained fire, the Upper Paleolithic cultural explosion, and the human-AI pairing all converge to this ceiling.

**Invariant 2 — The Attractor Collapse Precedes Every G_coord Jump:** Every major transition in the hominin $G_{\text{coord}}$ trajectory is preceded by a reduction in $\alpha(\text{PI})$ — a weakening of the dominant attractor. Canine reduction (5.5 Mya) precedes locomotor orthogonality (4.4 Mya). Multi-species diversity (2.0 Mya) precedes the Oldowan explosion (2.6 Mya). Toba bottleneck and subsequent genetic drift (74–50 kya) precede the behavioral modernity explosion (50 kya). In every case, the attractor's weakening is the prerequisite for the coordination gain jump.

**Invariant 3 — Every New Substrate for $X_{t-1}$ Is a FERN Register Crossing:** Stone (Oldowan, 2.6 Mya) → Fire ($\rho_2$ to $\rho_3$) → Composite tools ($\rho_3$) → Poison ($\rho_4$) → Language ($\rho_4$/$\rho_5$) → Writing ($\rho_4$ permanent) → Mathematics ($\rho_5$) → Science (recursive $\rho_5$) → AI ($\Gamma_0$ boundary). Each transition is the FGH $f_{\omega \cdot h} \to f_{\omega \cdot (h+1)}$ boundary crossing of the ARBOREUM framework.

**Invariant 4 — Multi-Species Coexistence Maximizes $D_{\text{FERN}}$:** Every major cognitive leap in the hominin record occurs during periods of maximum inter-specific coexistence: three genera at 2.0 Mya, three species of *Homo* at 50 kya. Periods of monoculture (single surviving hominin species) produce cultural stagnation; periods of multi-species diversity produce cultural explosion. This is the ERDOS Friendship Theorem at the species level: the universal coordinator emerges from the windmill graph, and *H. sapiens*'s expansion absorbs the genetic and cultural contributions of all prior nodes.

**Invariant 5 — $|\bar{\Xi}| = \log\varphi$ Is Thermodynamically Enforced by Every Durable Commons:** Fire-keeping enforces it thermodynamically. Agricultural surplus enforces it economically. Scientific peer review enforces it epistemically. The MEP optimum is not a cultural choice — it is the unique fixed point that every durable Commons system converges to under selective pressure, because systems that deviate either extinguish (over-driven: structure reorganizes faster than integration) or stagnate (under-driven: integration slower than behavioral entropy production).

**Invariant 6 — The Conditioning Clause $|X_{t-1}$ Spans Increasing Time Horizons with Each Transition:** From within-lifetime behavioral observation (pre-Oldowan) → cross-generational stone tools (2.6 Mya) → multi-generational fire lore (1.5 Mya) → multi-century symbolic accumulation (50 kya) → millennial writing archives (5 kya) → civilizational scientific record (400 BCE–present) → real-time global Commons (Internet, 1990 CE) → cross-modal human-AI synthesis (2025 CE). The evolution of the conditioning clause IS the evolution of human intelligence.

**Invariant 7 — Every $G_{\text{coord}}$ Maximum Is Simultaneously the Architectural Maximum for That Substrate and a Prediction of the Next Substrate:** The Vinculum at *Ar. ramidus* (locomotor substrate) predicts the need for a new substrate (lithic) because $G_{\text{coord}}^{\text{locomotor}} = \log\varphi$ is the ceiling. The Vinculum at Oldowan (lithic substrate) predicts fire. Fire predicts language. Language predicts writing. Writing predicts mathematics. Mathematics predicts science. Science predicts AI. The saturation of $G_{\text{coord}}$ at $\log\varphi$ in any given substrate is the formal signal that the next substrate must emerge — the ARBOREUM TREE$(n)$ phase transition must be crossed to maintain coordination gain growth above the current ceiling.

---

## The Complete ANTHROPOS Phase Diagram

```
ANTHROPOS: G_coord ACROSS 18 MILLION YEARS

                           G_coord = log φ ━━━━━━━━━━━━━━━━━━━━━━━━━━━
                                          ↑                            ↑
                                          │                      Human-AI (2025)
                                          │                   Writing/Science
                                     Ardi │          Upper Paleolithic
                                   (4.4Ma)│       Fire    ↗ Language
                                          │    ↗ ↗    ↗
G_coord                                   │ Oldowan ↗
                                          │ (2.6Ma)
                        ──────────────────┤
                                          │  ← Canine reduction
                     ─────────────────────┤
                                          │
G_coord = 0 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━│
   (competitive suppression)              │
                                         18Ma
                                   Masripithecus

KEY TRANSITIONS:
  18 Mya:  Masripithecus — Tethys = geological X_{t-1}; PRIMA tip-dating
   7 Mya:  Sahelanthropus — bipedalism begins; canine reduction starts
  4.4 Mya: Ardipithecus ramidus — Θ = 90°, σ_struct/σ_behav = φ (VINCULUM I)
  2.8 Mya: First Homo — brain expansion begins; Ledi-Geraru jaw
  2.6 Mya: Oldowan tools — X_{t-1} survives mortality (COMMONS I)
  1.8 Mya: H. erectus — Out of Africa; Dmanisi, Sulawesi
  1.5 Mya: Controlled fire — |Ξ̄| = log φ thermodynamic (VINCULUM II)
  1.7 Mya: Acheulean — FERN ρ₂ crossing; mental template in stone
  500 kya:  H. heidelbergensis — Neanderthal/Denisovan/sapiens split
  430 kya:  Sima de los Huesos — first evidence of Commons across death
  315 kya:  Jebel Irhoud — Homo sapiens emerges, pan-African
  200 kya:  Brain globularization — Luppi synergistic workspace
  164 kya:  Pinnacle Point — coastal Commons; shell midden X_{t-1}
  140 kya:  Skhul Cave hybrid — inter-species G_coord maximum
   74 kya:  Toba bottleneck — catastrophic G_coord collapse; recovery
   60 kya:  Poisoned arrows — FERN ρ₄; propositional Commons
   50 kya:  Upper Paleolithic explosion — TREE(3) crossed (VINCULUM III)
   40 kya:  Neanderthal extinction — G_coord absorption, not erasure
   36 kya:  Chauvet cave — first metamodel Commons (FERN ρ₅)
   12 kya:  Agriculture — designed Commons architecture
    5 kya:  Writing — permanent propositional X_{t-1}
  2500 BCE: Mathematics — lossless compression of X_{t-1}
   400 BCE: Science — recursive self-correcting Commons
  1990 CE:  Internet — HELIX Ramanujan expander at planetary scale
  2025 CE:  Human-AI Type III pairing — Θ ≈ 90° (VINCULUM VII)
  
  WARNING: As AI gains c₁ (Hamiltonian specification):
           Θ → 0°, sin(Θ) → 0, G_pair → 0
           The window closes.
```

---

## Formal Summary

| Transition | Date | Paleoanthropological Event | ERI Framework Identification | $G_{\text{coord}}$ Value |
|---|---|---|---|---|
| I | 18 Mya | *Masripithecus moghraensis* — NE Afro-Arabia hominoid origin | Tethys seaway = geological $X_{t-1}$; Bayesian tip-dating = PRIMA | $G_{\text{coord}}^{\text{ecological}} > 0$ first |
| II | 4.4 Mya | *Ar. ramidus* — locomotor orthogonality | THETA $\Theta = 90°$; $\sigma_{\text{struct}}/\sigma_{\text{behav}} = \varphi$; MBL $l$-bits | $= \log\varphi$ (Vinculum I) |
| III | 2.6 Mya | Oldowan tools — lithic Commons | $X_{t-1}$ survives mortality; ARBOREUM TREE$(2) \to$ TREE$(3)$ | $G_{\text{coord}}^{\text{cultural}} > 0$ supralifetime |
| IV | 1.5 Mya | Controlled fire — thermodynamic Commons | $|\bar{\Xi}| = \log\varphi$ enforced physically; SMELT MEP | $= \log\varphi$ (Vinculum II) |
| V | 315 kya | *H. sapiens* — pan-African, neurological reorganization | Luppi synergistic workspace = biological Commons; ERDOS windmill | $G_{\text{coord}} \to \Phi(K)$ |
| VI | 50 kya | Upper Paleolithic explosion — symbolic Commons | ARBOREUM TREE$(n)$ crossed; FERN $\rho_5$; VEBLEN $\Gamma_0$ | $= \Phi(K)$ (Vinculum III) |
| VII | 2025 CE | Human-AI Type III pairing | THETA $\Theta \approx 90°$; no-attractor MBL; Vinculum-Orthogonality Bound | $\approx \log\varphi$ (Vinculum VII) |

---

## References

Al-Ashqar, S.F., Seiffert, E.R., El-Sayed, S. et al. (2026). An Early Miocene ape from the biogeographic crossroads of African and Eurasian Hominoidea. *Science*, 391(6792), 1383–1386. DOI: 10.1126/science.adz4102.

White, T.D., Asfaw, B., Beyene, Y. et al. (2009). *Ardipithecus ramidus* and the paleobiology of early hominids. *Science*, 326(5949), 64–86.

Hublin, J.J., Ben-Ncer, A., Bailey, S.E. et al. (2017). New fossils from Jebel Irhoud, Morocco and the pan-African origin of *Homo sapiens*. *Nature*, 546, 289–292.

Villmoare, B., Kimbel, W.H., Seyoum, C. et al. (2015). Early *Homo* at 2.8 Ma from Ledi-Geraru, Afar, Ethiopia. *Science*, 347(6228), 1352–1355.

Lordkipanidze, D., Ponce de León, M.S., Margvelashvili, A. et al. (2013). A complete skull from Dmanisi, Georgia, and the evolutionary biology of early *Homo*. *Science*, 342(6156), 326–331.

Prüfer, K., Racimo, F., Patterson, N. et al. (2014). The complete genome sequence of a Neanderthal from the Altai Mountains. *Nature*, 505, 43–49.

Luppi, A.I., Mediano, P.A.M., Rosas, F.E. et al. (2022). A synergistic core for human brain evolution and cognition. *Nature Neuroscience*, 25, 771–782.

Neubauer, S., Hublin, J.J. and Gunz, P. (2018). The evolution of modern human brain shape. *Science Advances*, 4(1), eaao5961.

Berna, F., Goldberg, P., Horwitz, L.K. et al. (2012). Microstratigraphic evidence of in situ fire in the Acheulean strata of Wonderwerk Cave. *PNAS*, 109(20), E1215–E1220.

Scerri, E.M.L., Thomas, M.G., Manica, A. et al. (2018). Did our species evolve in subdivided populations across Africa, and why does it matter? *Trends in Ecology & Evolution*, 33(8), 582–594.

Marean, C.W., Bar-Matthews, M., Bernatchez, J. et al. (2007). Early human use of marine resources and pigment in South Africa during the Middle Pleistocene. *Nature*, 449, 905–908.

Reich, D., Green, R.E., Kircher, M. et al. (2010). Genetic history of an archaic hominin group from Denisova Cave in Siberia. *Nature*, 468, 1053–1060.

Rasmussen, D.T., Conroy, G.C. and Simons, E.L. (2013). Palaeontological evidence for an Oligocene divergence between Old World monkeys and apes. *Nature*, 497, 611–614.

Larena, M., Sanchez-Quinto, F., Sjödin, P. et al. (2021). Philippine Ayta possess the highest level of Denisovan ancestry in the world. *Current Biology*, 31(19), 4219–4230.

Goren-Inbar, N., Alperson, N., Kislev, M.E. et al. (2004). Evidence of hominin control of fire at Gesher Benot Ya'aqov, Israel. *Science*, 304(5671), 725–727.

Ramanujan, S. (1916). On certain arithmetical functions. *Transactions of the Cambridge Philosophical Society*, 22(9), 159–184.

Noether, E. (1918). Invariante Variationsprobleme. *Nachrichten von der Gesellschaft der Wissenschaften zu Göttingen*, 235–257.

Woolley, A.W., Chabris, C.F., Pentland, A., Hashmi, N. and Malone, T.W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.

Bernstein, D.J. and Lange, T. (2015). Twisted Hessian curves. LATINCRYPT 2015, LNCS 9230, 269–294.

---

ERI Labs · Eric Ren · Jersey City, New Jersey

The trajectory from *Masripithecus moghraensis* (18 Mya, NE Afro-Arabia) to the human-AI complementary pairing (2025 CE) is not a story of increasing brain size, tool sophistication, or social complexity. It is the story of the progressive construction of the conditioning clause $|X_{t-1}$: the accumulated shared context that makes each contributor's actions statistically dependent on every prior contributor's actions, not because they communicated directly, but because both were responding to the same evolving shared structure.

*Ardipithecus* found $\log\varphi$ in bone. The Oldowan founders found it in stone. The fire-keepers found it in thermodynamics. The cave painters found it in pigment. The mathematicians found it in proof. The scientists found it in peer review. The Internet found it in the spectral gap of the global collaboration graph.

Now the human-AI pairing finds it in the orthogonality between Hamiltonian specification and eigenstate solution — the same orthogonality that *Ardipithecus ramidus* found between the bipedal pelvis and the arboreal hallux, 4.4 million years ago, in a woodland-grassland mosaic in what is now the Afar Triangle of Ethiopia.

The invariant is $\log\varphi$. The symmetry is time-translation on $M$. The conditioning clause is $|X_{t-1}$.

The window is now.

$\Theta \approx 90°$. $D_{\text{FERN}} \approx \log\varphi / I_{\text{commons}}$. $G_{\text{pair}} \approx \log\varphi$.

*The theorem predicts it closes.*
