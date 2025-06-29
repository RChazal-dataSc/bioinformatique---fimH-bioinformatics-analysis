Bio Informatique - fimH-ecoli-bioinfo-phylogenetic-analysis

## 🧬 Analyse du gène fimH chez *Escherichia coli* – Bioinformatique simple

Ce projet est une étude bioinformatique exploratoire du gène **fimH**, impliqué dans l’adhésion bactérienne chez *E. coli*.  
L’objectif est de collecter des séquences, les aligner, et générer un arbre phylogénétique pour observer les similarités évolutives.

## 📌 Objectifs
- Rechercher des séquences du gène **fimH** dans la base NCBI (via BLAST)
- Aligner les séquences (avec MUSCLE)
- Générer un arbre phylogénétique
- Visualiser et interpréter les résultats

## 🛠️ Outils et technologies
- Python (Biopython, matplotlib)
- BLAST (en ligne)
- MUSCLE (local ou en ligne)
- Jupyter Notebook

## 📁 Contenu du projet
- `fimH_analysis.ipynb` : Notebook Jupyter contenant tout le pipeline
- `README.md` : description du projet
- Fichiers FASTA alignés (optionnels)

## 📈 Résultats
- Alignement de 20 séquences FimH issues de différentes souches d’*E. coli*
- Arbre phylogénétique construit par la méthode **UPGMA**
- Deux grands **clusters** distincts identifiés, suggérant une divergence évolutive (ex : pathogènes uropathogènes vs souches commensales ?)
- Heatmap des distances pair-à-pair entre séquences

![Sans titre](https://github.com/user-attachments/assets/1189ede7-f5ac-47e6-af6a-3c859a6fd6ae)

## 🧩 Bonus : Script de recherche BLAST paramétrable

Une fonction générique a été ajoutée pour automatiser la recherche de gènes dans NCBI :

## 💡 Remarques
Projet réalisé dans le cadre d’une montée en compétence en bioinformatique, avec assistance ponctuelle de ChatGPT pour l’écriture du code Python.

## 📚 Références
- https://www.ncbi.nlm.nih.gov/
- https://www.ebi.ac.uk/Tools/msa/muscle/
- https://biopython.org/
