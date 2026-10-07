# 📈 Simulateur de Retraite et Épargne – Fonctionnaire d'État (début de carrière)

[![V01 Mode Expert](https://img.shields.io/badge/V01-Mode%20Expert-blue.svg)](https://github.com/J34NMY/simulateur-retraite-et-epargne-fonctionnaire/blob/main/simulateur_fonctionnaire_capitalisation_expert.html)
[![Statut : en ligne](https://img.shields.io/badge/statut-en%20ligne-brightgreen.svg)](https://simulateur-citoyen.fr/simulateur-retraite-et-epargne-fonctionnaire/)
[![Licence CC BY-NC-SA 4.0](https://img.shields.io/badge/licence-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE.md)

Outil pédagogique gratuit pour les **fonctionnaires d'État, catégorie sédentaire, en début de carrière** : projette votre future pension (méthode SRE) et compare vos options d'épargne (CTO, PEA, PER) pour la compléter.

> ⚠️ **Outil éducatif non officiel.** Pour votre estimation retraite officielle, consultez [info-retraite.fr](https://www.info-retraite.fr) (simulateur M@rel, tous régimes confondus).

> 💡 **Pourquoi ce nom ?** La retraite par répartition n'offre aucun choix individuel. Votre RAFP (retraite additionnelle) est, elle, un vrai régime par capitalisation collective — mais vous n'en choisissez pas la gestion. Le CTO, le PEA et le PER vous laissent, eux, décider où va votre argent. Ce simulateur montre les deux, sans jamais laisser penser que la retraite française serait "par capitalisation" — elle reste, et reste obligatoirement, par répartition.

---

## 📂 Périmètre

Ce simulateur couvre les **fonctionnaires d'État, catégorie sédentaire**, en début de carrière. Il ne couvre **pas** :
- Les **salariés du régime général** → voir [simulateur-retraite-et-epargne-regime-general](https://github.com/J34NMY/simulateur-retraite-et-epargne-regime-general)
- Les **fonctionnaires en catégorie active**
- Les agents relevant de la **CNRACL** (territoriaux, hospitaliers)
- Les **travailleurs indépendants** et **professions libérales**

---

## ✨ Fonctionnalités

- **Projection de carrière** : 30 à 40 ans, indice constant ou par paliers (avancements d'échelon/grade), en euros constants
- **Pension à la retraite (méthode SRE)** : taux maximum 75% du traitement indiciaire, formule multiplicative (décote/surcote 1,25%/trimestre), barème de la réforme 2023 (pas le gel temporaire 2026-2028, non pertinent pour une carrière projetée sur 30-40 ans)
- **Enfants** : bonification 4 trimestres liquidables/enfant (avant 2004), majoration 2 trimestres de durée d'assurance/enfant (depuis 2004, dont 1 devenu liquidable depuis le 01/09/2026 pour les mères ayant accouché après leur recrutement — décret n°2026-699), et majoration familiale de pension +10%/+5% à partir de 3 enfants élevés (Art. L18 CPCMR)
- **Comparateur d'épargne** : 100% investi sur chaque enveloppe séparément (CTO, PEA, PER), fiscalité 2026 (flat tax 31,4%, PEA 18,6%, PER mixte)
- **ETF réels vérifiés** (ISIN, frais, éligibilité PEA) pour 4 indices : MSCI World, S&P 500, MSCI Emerging Markets, MSCI ACWI
- **RAFP expliquée** : encadré pédagogique sur le fonctionnement de la retraite additionnelle (capitalisation collective sur les primes), sans tentative de la chiffrer (primes trop variables selon le corps)
- **Mode Expert** : tableau année par année, ETF personnalisé, export PDF (séparé par onglet), comparaison multi-scénarios
- **Épargne de précaution** : rappel systématique avant toute simulation d'épargne
- 100% local : aucune donnée transmise, fonctionne hors ligne une fois la page chargée

---

## ⚡ Utilisation

1. Rendez-vous sur [simulateur-citoyen.fr/simulateur-retraite-et-epargne-fonctionnaire](https://simulateur-citoyen.fr/simulateur-retraite-et-epargne-fonctionnaire/)
2. Choisissez le **Mode Guidé** (première utilisation) ou le **Mode Expert** (fonctionnalités avancées)
3. Si vous avez déjà des trimestres validés, récupérez-les sur votre relevé de carrière ([info-retraite.fr](https://www.info-retraite.fr))
4. Consultez le [Mode d'emploi](mode-emploi.html) pour un guide détaillé

---

## ⚠️ Limite connue

Cet outil suppose une **carrière continue à temps plein** depuis le début (trimestres d'assurance = trimestres liquidables). Si vous avez travaillé dans le privé avant d'intégrer la fonction publique, ou connu du temps partiel, utilisez plutôt le [simulateur Retraite Progressive Fonctionnaire](https://github.com/J34NMY/simulateur-retraite-progressive) pour votre pension précise — le comparateur d'épargne de cet outil-ci est indépendant du calcul de pension et peut être repris séparément (même date de retraite, même montant épargné).

---

## 🗺️ Feuille de route

- [x] Moteur de calcul SRE (méthode multiplicative, 75% max, barème réforme 2023)
- [x] Comparateur d'épargne CTO/PEA/PER avec fiscalité 2026
- [x] ETF réels vérifiés individuellement (ISIN, TER)
- [x] Mode Guidé et Mode Expert
- [x] Tableau annuel, export PDF, ETF personnalisé, multi-scénarios (Expert)
- [x] Mise en ligne (GitHub Pages)
- [x] Enfants : bonifications/majorations, décret n°2026-699, majoration familiale (Art. L18)
- [ ] Modélisation RAFP chiffrée (si des données de primes moyennes fiables deviennent disponibles)

---

## 🔗 Liens officiels

- [info-retraite.fr](https://www.info-retraite.fr) — Relevé de carrière, simulateur M@rel (source unique tous régimes)
- [rafp.fr](https://www.rafp.fr) — Retraite additionnelle de la fonction publique

---

*Développé bénévolement par J34NMY avec l'assistance de Claude (Anthropic) · Licence CC BY-NC-SA 4.0 · Juillet 2026*
