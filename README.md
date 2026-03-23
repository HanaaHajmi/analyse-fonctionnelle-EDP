# Analyse fonctionnelle et EDP

Exploration numérique et théorique des outils fondamentaux de l'analyse fonctionnelle
et des équations aux dérivées partielles classiques.

## Structure du dépôt

```
analyse-fonctionnelle-EDP/
├── notebooks/
│   ├── 01_topologie_espaces_normes.ipynb
│   ├── 02_espaces_hilbert.ipynb
│   ├── 03_distributions_sobolev.ipynb
│   ├── 04_formulation_variationnelle.ipynb
│   ├── 05_edp_poisson_chaleur_ondes.ipynb
│   └── 06_fourier_analyse_harmonique.ipynb
├── requirements.txt
└── README.md
```

## Fil conducteur

Les six notebooks forment une progression cohérente :

1. **Topologie et espaces normés** — compacité, complétude, théorème de Baire, espaces de Banach
2. **Espaces de Hilbert** — produit scalaire, projection orthogonale, bases de Hilbert, théorème de Riesz
3. **Distributions et espaces de Sobolev** — dérivation au sens des distributions, H¹(Ω), H²(Ω), traces
4. **Formulation variationnelle** — lemme de Lax-Milgram, problème de Poisson faible, coercivité
5. **EDP classiques** — Poisson (éléments finis P1), chaleur (Euler implicite), ondes (Newmark)
6. **Fourier et analyse harmonique** — série de Fourier, DFT, FFT, lien avec les EDP

