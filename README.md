****Gene Length Bias in HPV Integration Sites
Statistical analysis of Human Papillomavirus (HPV) integration susceptibility in human genes using KNIME.****

Workflows

**1️⃣ Statistical Workflow (HPV_Stats.knwf)**

This workflow:

Cleans VISDB HPV16 and HPV18 integration data

Cleans Ensembl BioMart gene annotation data

Maps integration sites to host genes

Calculates gene length

Performs log transformation

Classifies genes as:

Integrated

Non-integrated

Conducts Wilcoxon–Mann–Whitney statistical testing

Generates box plot and density visualization

---

**2️⃣ Integrated Hotspots Workflow (Intigrated_Hotspots.knwf)**

This workflow:

Processes HPV16 and HPV18 datasets separately

Extracts integration frequencies per gene

Groups and ranks genes by integration count

Identifies top integration hotspots

---
**Requirements**

KNIME Analytics Platform (4.x or higher recommended)

Java 8+


VISDB integration datasets (HPV16 & HPV18)
Ensembl BioMart gene annotation file

---
**Authors**

Sahil Khandekar (sahil04mail@gmail.com)
Urja Bait (urjabait@gmail.com)
