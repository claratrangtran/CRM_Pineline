** **🇬🇧 English Version** **

#  CRM Sales Pipeline Analytics 🚀

##  📊 Project Overview

This project simulates a complete end-to-end Business Intelligence solution. I generated a synthetic CRM dataset using Python, performed exploratory data analysis and schema modeling using SQL, and finally built an interactive Power BI dashboard to track sales performance and pipeline health.

The Goal: Provide sales leadership with real-time visibility into the pipeline, conversion rates, and representative performance.

##  ❓ Business Questions Answered

Pipeline Health: What is the total value of deals currently in "open" stages vs. those closed? 💰

Conversion Efficiency: What is the win/loss ratio across different sales regions? 🌍

Sales Cycle: How many days does it take to move a deal from "Prospecting" to "Closed Won"? ⏳

Rep Performance: Who are the top-performing sales reps based on revenue? 🏆

##  🛠️ Tech Stack & Project Steps

### Step 1: Data Generation (Python) 🐍

Using the Faker library and Pandas, I developed a script (Python_create data set.txt) to create a relational database schema.

Files Created: Dim_SalesReps.csv, Dim_Accounts.csv, Dim_Products.csv, and Fact_Opportunities.csv.

### Step 2: Data Modeling & Analysis (SQL) 🗄️

I imported the data into a SQL environment to structure the database.

Schema Design: Implemented Primary Keys and Foreign Key constraints.

Key Queries: Developed analysis for regional conversion rates and pipeline bottlenecks.

### Step 3: Visualization (Power BI) 📈

<img width="1293" height="728" alt="pineline 2" src="https://github.com/user-attachments/assets/ebc6f1a3-512d-4d25-9507-1388e24ca8c7" />


<img width="1297" height="722" alt="Pineline 1" src="https://github.com/user-attachments/assets/3de69c18-2098-46bf-a187-f78a7c9205b1" />

Connected the model to Power BI for advanced analytics.

DAX Engineering: Created measures for Pipeline Value, Open Deals Count, and Win Rate %.

Fixed alphabetical sorting using a custom Stage Sort Order.

## 🖥️ Final Dashboard & How to Use

Slicers: Filter by Region or Sales Manager to see localized performance.

Interactive Funnel: Click on any stage (e.g., "Negotiation") to see which specific accounts are at risk or ready to close.

## 📝 Conclusions & Limitations

Insight: The dashboard reveals specific bottlenecks in the "Proposal" stage where deal velocity slows down.

Limitation: The current model assumes a linear flow; future updates will include a "Historical Trend" (SCD Type 2) to track deal movement over time.

** **🇫🇷 Version Française** **

Analyse du Pipeline de Ventes CRM et Ingénierie de Données 🚀

## 📊 Aperçu du Projet

Ce projet simule une solution complète de Business Intelligence. J'ai généré un jeu de données CRM synthétique avec Python, effectué l'analyse exploratoire et la modélisation du schéma via SQL, et enfin construit un tableau de bord Power BI interactif.

L'Objectif : Offrir à la direction commerciale une visibilité en temps réel sur le pipeline, les taux de conversion et la performance des commerciaux.

## ❓ Questions Business Résolues

Santé du Pipeline : Quelle est la valeur totale des opportunités en cours vs celles clôturées ? 💰

Efficacité de Conversion : Quel est le ratio gain/perte par région commerciale ? 🌍

Cycle de Vente : Combien de jours faut-il pour passer de "Prospection" à "Gagné" ? ⏳

Performance des Vendeurs : Qui sont les meilleurs commerciaux selon le chiffre d'affaires ? 🏆

## 🛠️ Stack Technique et Étapes

### Étape 1 : Génération des Données (Python) 🐍

Utilisation des bibliothèques Faker et Pandas pour créer un schéma relationnel.

### Étape 2 : Modélisation et SQL 🗄️

Structuration des données dans un environnement SQL.

Conception : Mise en place des clés primaires et étrangères pour l'intégrité des données.

Requêtes : Analyse des taux de conversion régionaux.

### Étape 3 : Visualisation (Power BI) 📈

<img width="1297" height="722" alt="Pineline 1" src="https://github.com/user-attachments/assets/3de69c18-2098-46bf-a187-f78a7c9205b1" />

<img width="1293" height="728" alt="pineline 2" src="https://github.com/user-attachments/assets/ebc6f1a3-512d-4d25-9507-1388e24ca8c7" />

DAX : Création de mesures calculées pour la valeur du pipeline et le taux de succès.

Organisation personnalisée des étapes de vente (Entonnoir).

## 🖥️ Tableau de Bord et Utilisation

Filtres : Filtrez par Région ou Manager pour analyser les performances locales.

Entonnoir Interactif : Cliquez sur une étape pour voir quels comptes sont actuellement en cours de négociation.

## 📝 Conclusions et Limites

Insight : Le tableau de bord identifie des blocages à l'étape "Proposition" où la progression ralentit.

Limite : Le modèle actuel est statique ; une version future inclura un suivi historique (SCD Type 2).
