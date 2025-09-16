# Test Technique — Développement Front

**Candidat :** Razafitsalama Lovasoa  
**Date :** 16 septembre 2025

---

## Objectif

Reproduire fidèlement l’interface fournie (Adobe XD) au pixel près.  
Les pages sont **statiques**, réalisées uniquement avec **HTML et Tailwind CSS**.

---

## Structure du projet

rec-0925-devfront/
│-- razafitsalama-completez-votre-reservation.html
│-- razafitsalama-paiement.html
│-- README.md

- **Pages :**
  - `/razafitsalama-completez-votre-reservation`
  - `/razafitsalama-paiement`
- **Technologies :**
  - HTML
  - Tailwind CSS v2.2.19
  - Font Awesome (pour les icônes)

---

## Instructions de lancement

- Aucune installation particulière nécessaire.  
- Les pages sont **statiques**, il suffit de les ouvrir dans un navigateur :

```bash
open razafitsalama-completez-votre-reservation.html
open razafitsalama-paiement.html
Notes de design
Les couleurs et typographies sont reproduites au plus proche de la maquette Adobe XD.

Les cartes « Basic », « Assurance » et « Complet » ont la même largeur et hauteur pour un alignement visuel.

Le footer est fixe en bas de page pour toujours afficher le récapitulatif.

Les icônes sont celles de Font Awesome :

Icônes de résultat → fa-clipboard-list + fa-hand-point-up pour reproduire le « point up ».

Marges et padding ajustés pour un rythme vertical harmonisé.

Boutons centrés avec hover effect.

Séparation par ligne fine sous les boutons.

Polices fallback : font-sans → Arial, Helvetica si Tailwind ne charge pas correctement.

Temps passé (indicatif) : ~8 heures.