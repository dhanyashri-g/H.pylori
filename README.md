# 🧬 Novel Drug Target Identification in Multidrug-Resistant *Helicobacter pylori* Using Subtractive Genomics

This repository presents a research project aimed at identifying novel drug targets in **multidrug-resistant *Helicobacter pylori*** using **in silico subtractive genomics** approaches. The findings contribute to combatting rising antimicrobial resistance by proposing specific, essential, and non-host homologous targets for future drug development.

---

## 📁 Details

**Title**: Novel Drug Target Identification in Antimicrobial-Resistant *Helicobacter pylori* Using Subtractive Genomics  
**Author**: Dhanyashri A/P Guruparan  
**Institution**: Management & Science University (MSU), Malaysia  
**Degree**: Bachelor of Bioinformatics (Hons)  
**Year**: 2024  
**Project Type**: Research Project  
**Keywords**: *Helicobacter pylori*, drug-target, subtractive-genomics, antimicrobial-resistance, PBIT, PSORTb, KEGG, in-silico

---

## 📌 Project Overview

*Helicobacter pylori* is a Gram-negative, spiral bacterium infecting over half the global population. It is linked to conditions like gastritis, ulcers, and gastric cancer. With increasing antibiotic resistance, identifying **novel, safe, and specific drug targets** is a priority.

This study applied a **genome-wide subtractive genomics approach** to analyze the H. pylori proteome, filter out human homologs, assess essentiality, virulence, druggability, and subcellular localization, and identify **14 non-homologous, essential, cytoplasmic proteins** as viable drug targets.

---

## 🎯 Objectives

- Retrieve and curate the complete H. pylori proteome.
- Filter sequences for non-redundancy and functional viability.
- Perform subtractive genomic filtering against:
  - Human proteome
  - Human anti-targets
  - Gut microbiota
- Analyze essentiality, virulence factors, druggability, and localization.
- Identify unique cytoplasmic proteins as **novel drug targets**.

---

## 🧪 Tools & Platforms Used

| Tool/Platform     | Purpose                                                         |
|-------------------|------------------------------------------------------------------|
| **NCBI**          | Genome and protein sequence retrieval                           |
| **CD-HIT**        | Removal of paralogous/duplicate sequences                       |
| **Galaxy (EU)**   | Sequence length filtering and preprocessing                     |
| **PBIT**          | Subtractive genomic analysis pipeline                           |
| **KAAS (KEGG)**   | Functional annotation and KO filtering against human pathways   |
| **PSORTb**        | Subcellular localization prediction for Gram-negative bacteria  |

---

## 🔬 Key Findings

### ⚙️ Preprocessing Results

- Sequences retrieved: **1427**
- After redundancy filtering: **1294**
- After KEGG & subcellular filtering: **14** final cytoplasmic targets

### 🎯 Identified Final Drug Targets

| No. | Protein Name |
|-----|--------------|
| 1 | VirB11 – Type IV secretion system ATPase |
| 2 | Aminodeoxychorismate synthase component II |
| 3 | CrdR – Copper response regulator |
| 4 | Polysaccharide deacetylase |
| 5 | Tryptophan synthase subunit alpha |
| 6 | UDP-4-amino transaminase |
| 7 | NADH-quinone oxidoreductase subunit G |
| 8 | Type II/IV secretion system ATPase subunit |
| 9 | Pyridoxine 5'-phosphate synthase |
| 10 | Bifunctional anthranilate synthase/aminotransferase |
| 11 | Pyridoxal phosphate-dependent aminotransferase |
| 12 | Flagellar biosynthesis protein FlhF |
| 13 | Anthranilate synthase component I |
| 14 | Sensor histidine kinase (HAMP domain) |

These proteins are essential for bacterial survival, cytoplasmic in localization, and non-homologous to humans, minimizing off-target effects.

---

## ✅ Conclusion

This study successfully applied subtractive genomics to identify **14 novel, cytoplasmic, non-human homologous drug targets** in *H. pylori*. These proteins represent ideal candidates for **narrow-spectrum antibiotics** that minimize toxicity and off-target effects in humans. This research lays the groundwork for **structure-based drug discovery and future wet-lab validation** against multidrug-resistant H. pylori infections.

---

## 🔭 Future Directions

- Structural modeling and docking of lead inhibitors against identified proteins
- Experimental (wet-lab) validation of cytoplasmic targets
- Exploring these targets in **multi-drug synergy and resistance evasion models**
- Develop **strain-specific antimicrobial therapies** based on these targets

---

---

## 📜 License

This project is licensed under the **MIT License**. It is freely available for academic and research use only. Attribution to the author and MSU is required in derivative works.

---

| This work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.
