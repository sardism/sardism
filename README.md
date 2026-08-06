# 👋 Hi, I'm Marios Sardis

Protein biochemist and molecular biologist with 15+ years of experience in recombinant protein engineering, expression, purification, and biophysical characterization across bacterial and mammalian systems (~200 constructs engineered, expressed, and characterized). I have built three research laboratories from the ground up covering protein biochemistry and biophysics, BSL-2 mammalian cell biology, and BSL-2 microbiology. I enjoy the full arc of research, from strategic organisation and infrastructure build-out to getting into the weeds of data capture and analysis.

I have extensive hands-on experience with ÄKTA-based multi-modal chromatography, orthogonal biophysical characterization (SEC-MALS, DLS, DSF, ITC, BLI, CD spectroscopy, limited proteolysis, peptide mapping), and protein-protein and protein-small molecule interaction studies. I have contributed to 4 international patents and multiple peer-reviewed publications in microbiology and cell biology.

I am currently expanding into computational tools, which I think have the potential to transform how individual researchers approach problems that previously required large teams and significant infrastructure.

## 💻 Computational & Programming Work

I develop Python-based tools and pipelines to extend and accelerate wet-lab research:

Automated high-throughput data analysis and statistical workflows (NumPy, SciPy, Pandas, Seaborn, Matplotlib)
Protein structure prediction and modeling (AlphaFold2, OpenFold, iTASSER)
Protein-protein and protein-ligand docking pipelines (HADDOCK, AutoDock Vina, Gnina)
Cheminformatics workflows (RDKit, SMILES, PDBQT)
GPU-accelerated computing and WSL/Linux environments
Database management (SQLite)
LLM-assisted scientific workflows and coding (Claude, ChatGPT, Gemini)

## 🧬 De Novo Antibody Design

I am building an open-source computational pipeline for de novo antibody design against neglected tropical disease targets, running entirely on personal hardware.

Current project: Basement Antibody Works designs antibodies against T. cruzi trans-sialidase, the primary virulence enzyme of Chagas disease, using a multi-fidelity Bayesian co-optimisation approach that simultaneously explores epitope and antibody geometry.

Multi-structure SASA analysis across all available PDB crystal structures to identify conformationally robust surface-exposed epitopes (BioPython, UniProt REST API, PairwiseAligner)
Bayesian optimisation loop with Gaussian process surrogate and Expected Improvement acquisition function for hotspot combination search (BoTorch, Ax)
De novo antibody backbone design and CDR sequence optimisation (RFantibody, ProteinMPNN)
Structure prediction and interface scoring (Boltz-2)
All code and progress published openly: github.com/sardism/sialidaseantibodies

## 🔬 Basement Drug Discovery

One scientist. One laptop. A consumer GPU. Can a single person build a drug discovery pipeline using only open-source tools and free databases and find something real?

Basement Drug Discovery screens all FDA-approved drugs against validated protein targets in fungal pathogens responsible for killing immunocompromised patients worldwide. Every compound in the library has already cleared human safety trials. If something works computationally the path to patients is shorter than starting from scratch.

Current targets: CYP51 from Candida albicans and Aspergillus fumigatus with human CYP51 as a selectivity counter-screen.

Top hit: Atogepant, an FDA-approved migraine drug, scores stronger than every known antifungal against both fungal targets.

This work was submitted in response to FDA Docket FDA-2026-N-4492, Drug Repurposing for Unmet Medical Needs. All notebooks, results, and decisions are documented in real time on Substack. Anyone can reproduce this on their own laptop.

Follow along: basementdrugdiscovery.substack.com

## 🎨 Color Analysis & Digital Archiving

I build image analysis tools for calibrated color extraction, shade classification, and algorithmic cataloging of historical artifacts, combining scientific imaging methodology with cultural preservation.

Calibrated color extraction and shade comparison (LAB/XYZ color spaces)
Image segmentation and classification pipelines (OpenCV, Pillow, scikit-image)
Metadata integration for digital archiving and research

## 🛠️ Tools & Environments

Python • Jupyter • NumPy • SciPy • Pandas • Matplotlib • Seaborn • OpenCV • RDKit • PyMOL • HADDOCK • AutoDock Vina • Gnina • AlphaFold2 • OpenFold • iTASSER • RFantibody • ProteinMPNN • Boltz-2 • BoTorch • SQLite • Conda • WSL/Linux • GPU computing • LLMs

## 🌱 Currently exploring

De novo antibody design • Bayesian optimisation for protein engineering • Multi-fidelity computational pipelines • Structural bioinformatics • AI for life sciences • Scientific data visualization

<!--- sardism/sardism is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile. You can click the Preview link to take a look at your changes. --->
