Deep-Sea Biodiversity Analysis using AI-driven eDNA Pipeline
🌊 Background

The deep ocean—covering abyssal plains, hydrothermal vents, and seamounts—harbors a vast share of Earth’s biodiversity. However, much of this life remains undiscovered due to extreme inaccessibility. Understanding deep-sea biodiversity is crucial for:

Exploring ecological processes like food webs and nutrient cycling

Informing conservation strategies for fragile marine ecosystems

Discovering novel eukaryotic species with ecological and biotechnological value

Environmental DNA (eDNA) has emerged as a powerful, non-invasive tool to study these hidden ecosystems. By capturing genetic traces from seawater or sediments, eDNA allows species detection without disturbing habitats. Marker genes such as 18S rRNA and COI enable the identification of diverse taxa including protists, cnidarians, and rare metazoans, offering insights into species richness and community structure.

🧪 Project Description

The Centre for Marine Living Resources and Ecology (CMLRE) conducts deep-sea expeditions to collect water and sediment samples from biodiversity hotspots. These samples undergo eDNA extraction and high-throughput sequencing for biodiversity monitoring.

⚠️ Current Challenges

Poor database representation: Deep-sea taxa are underrepresented in reference databases (SILVA, PR2, NCBI).

Misclassifications & unassigned reads: Result in biodiversity underestimation.

Traditional pipeline limitations: Tools like QIIME2, DADA2, and mothur rely heavily on incomplete databases.

High computational cost: Large eDNA datasets increase processing time.

These issues hinder accurate biodiversity assessments and limit discovery of novel taxa.

🤖 Proposed Solution

We propose an AI-driven eDNA analysis pipeline that leverages deep learning and unsupervised learning to classify and annotate sequences directly from raw reads.

✅ Key Features

Database independence: Minimizes reliance on incomplete references.

Faster processing: Optimized workflows reduce computational time.

Novel taxa discovery: Enables identification of previously unknown species.

Biodiversity insights: Provides accurate abundance estimation and ecological patterns.

This approach ensures more robust biodiversity monitoring, paving the way for improved conservation strategies in rapidly changing deep-sea environments.

🚀 Impact

By combining cutting-edge AI with eDNA sequencing, this project advances:

Marine ecosystem monitoring

Discovery of novel eukaryotic lineages

Conservation of vulnerable deep-sea habitats
