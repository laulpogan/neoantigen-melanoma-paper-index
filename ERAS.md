# Eras of neoantigen-directed T-cell therapy in melanoma

Post-assembly partitioning of the 1187-paper corpus into mechanistic / hypothesis-driven eras. Era boundaries follow shifts in the dominant biological hypothesis or technical capability, not arbitrary dates.

---

## Era I — In-vitro sensitization & LAK (1988-1995)

**Dominant hypothesis:** Lymphocytes can be activated ex vivo with cytokines (IL-2) ± autologous tumor lysate, then reinfused to mediate tumor regression.

**Key technical capability:** High-dose IL-2 production (recombinant). Autologous tumor cell harvest from surgical specimens. *No* mechanistic understanding of which T-cell receptor specificities mattered.

**What "neoantigen" meant:** Not yet named. The field used "tumor-specific antigen" for any uncharacterized determinant. The Rosenberg group's IVS protocols implicitly enriched for any reactive specificity, including what we now call neoantigens.

**Therapeutic contribution:** Established that adoptive transfer can produce objective responses in metastatic melanoma. Set IL-2 + lymphodepletion as the conditioning paradigm.

**Limitations recognized at the time:** Response rates 10-20%, durability poor, no biomarker.

**This is the era Theodore worked in.** His autologous-tumor-vaccine + in-vitro-culture protocols are direct lineage from Rosenberg, Lotze, Mazumder.

**Seminal references in corpus:** PMIDs from `01_ivs_lak_era_1988_1995.csv` and `02_til_iL2_era_1988_2000.csv`. Rosenberg's NEJM TIL papers (1988), Lotze IL-2 review, IVS protocol descriptions.

---

## Era II — Defined-antigen / shared-antigen vaccines (1995-2008)

**Dominant hypothesis:** Melanoma expresses identifiable shared tumor antigens (MART-1, gp100, tyrosinase, MAGE-A family) that can be targeted with peptide vaccines or antigen-specific T cells.

**Key technical capability:** MHC-class-I peptide elution + mass spec. T-cell cloning. Tetramer staining.

**Therapeutic contribution:** Proved that *defined* antigens can drive T-cell responses in patients. Some objective responses in vaccine + adoptive-transfer trials (Rosenberg, Hwu, Yee, Romero/Cerottini).

**Failure mode that drove the field forward:** Shared antigens are usually self-antigens with central tolerance leakage; T cells generated against them are low-affinity and show modest tumor control. Shared antigens also have unpredictable expression in any given patient.

**Seminal references in corpus:** PMIDs in `03_defined_antigen_era_1995_2005.csv`. Romero P, Cerottini JC, Lausanne school. Yee C, Riddell SR adoptive T-cell cloning work.

---

## Era III — Adoptive cell transfer with lymphodepletion (2002-2014)

**Dominant hypothesis:** Lymphodepleting conditioning (cyclophosphamide + fludarabine ± TBI) creates "homeostatic space" that allows transferred T cells to persist, expand, and mediate durable regression.

**Key technical capability:** Bulk TIL expansion from tumor explants. High-dose IL-2 support. Standardized lymphodepletion regimens.

**Therapeutic contribution:** Response rates climbed to 50%+ in selected metastatic melanoma patients (Rosenberg group, Surgery Branch NCI). Durability extended; some complete responses sustained > 5 years. This is the era that proved adoptive T-cell therapy works clinically.

**What it left unresolved:** Why some patients respond and others don't. Bulk TIL contains polyclonal T cells of unknown specificity; the "active ingredient" was unidentified.

**Seminal references in corpus:** PMIDs in `04_act_lymphodepletion_era_2002_2015.csv`. Dudley ME, Wunderlich JR, Robbins PF in Rosenberg group. Hwu, Lotze.

---

## Era IV — Neoantigen discovery (2013-2020)

**Dominant hypothesis (paradigm shift):** The "active ingredient" in successful TIL therapy is a small fraction of T cells specific for *patient-unique mutational neoantigens*. Tumors with high mutational burden produce more neoantigens, which is why melanoma (UV-driven, high TMB) responds to checkpoint blockade and TIL therapy.

**Key technical capability:** Whole-exome sequencing of tumor + matched germline. MHC-binding prediction (NetMHCpan, MHCflurry). Tetramer + TCR-sequencing of patient T cells.

**Therapeutic contribution (mechanistic, not yet clinical):** Demonstrated that neoantigen-reactive T cells exist in patients, mediate tumor regression in retrospective cohort analyses, and predict response to anti-PD-1 (Snyder, Rizvi 2014-2015 papers; Tran/Robbins NCI work showing neoantigen-reactive TIL drives durable response in epithelial cancers).

**Bridge to therapy:** Set up the rationale for Era V personalized vaccines.

**Seminal references in corpus:** PMIDs in `05_neoantigen_discovery_era_2013_2020.csv`. Schreiber RD's "cancer immunoediting" framework. Snyder/Chan, Rizvi/Wolchok mutational landscape papers. Tran/Robbins/Rosenberg neoantigen-TIL studies.

---

## Era V — Personalized neoantigen vaccines (2017-2023)

**Dominant hypothesis:** A vaccine encoding patient-unique neoantigens can prime a *de novo* anti-tumor T-cell response, expand pre-existing reactive clones, and synergize with checkpoint blockade.

**Key technical capability:** Mutation-to-vaccine pipelines (tumor sequencing → neoepitope prediction → manufacture → infusion) under 2-4 weeks. Synthetic long peptides (Ott/Wu Dana-Farber); RNA-LNP (BioNTech IVAC/CureVac); DNA (Geneos).

**Therapeutic contribution:** Two pivotal melanoma trials demonstrated immunogenicity and clinical signal:
- Ott PA, Hu Z, Keskin DB, ... Wu CJ, Hacohen N. *An immunogenic personal neoantigen vaccine for patients with melanoma.* Nature 2017.
- Sahin U, Derhovanessian E, ... Türeci Ö. *Personalized RNA mutanome vaccines mobilize poly-specific therapeutic immunity against cancer.* Nature 2017.

Subsequent KEYNOTE-942 (mRNA-4157 + pembrolizumab in adjuvant melanoma) reported significant reduction in recurrence in late 2023.

**Seminal references in corpus:** PMIDs in `06_personalized_vaccine_era_2017_2026.csv`.

---

## Era VI — Convergence: TIL + checkpoint + neoantigen (2018-2026)

**Dominant hypothesis:** Best clinical benefit comes from combining (a) bulk or neoantigen-enriched TIL therapy, (b) anti-PD-1 / anti-CTLA-4 checkpoint blockade, and (c) personalized neoantigen vaccination — each addressing a different failure mode (low T-cell number → TIL; T-cell exhaustion → checkpoint; insufficient neoantigen presentation/priming → vaccine).

**Key technical capability + regulatory:** FDA approval of lifileucel (Iovance) in Feb 2024 for advanced melanoma — first cellular therapy approved for a solid tumor. Establishes the regulatory and reimbursement template Theodore's program would follow.

**Open questions this era is trying to answer:** Optimal sequencing (vaccine → TIL or TIL → vaccine?), neoantigen-enriched vs bulk TIL, role of CAR-T against neoantigen-specific TCRs, applicability to patients refractory to checkpoint blockade.

**This is where Theodore's program slots in.** A modernized autologous-tumor + in-vitro-adaptive-culture protocol that uses 2026-vintage neoantigen prediction to enrich the IVS step is a directly fundable mechanism that connects his prior clinical experience to the active research frontier.

**Seminal references in corpus:** PMIDs in `07_til_clinical_modern_era_2018_2026.csv`.

---

## Cross-era through-line

Theodore's hypothesis (autologous tumor vaccination → in-vitro adaptive culture → adoptive transfer) is **Era I methodology refined by Era IV-V mechanistic understanding**. The grant pitch writes itself: *the empirical efficacy Theodore observed in the IVS/LAK era was almost certainly mediated by the neoantigen-specific T cells we can now identify, enrich, and amplify with modern tooling. We propose to redo the protocol he piloted, but with neoantigen-guided enrichment at the in-vitro culture step.*

This is what funders want: a clinician with prior empirical experience of the phenomenon, paired with modern molecular tooling and a hypothesis-driven enrichment strategy.
