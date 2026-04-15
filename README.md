# GestEBEP

**Application de gestion des AESH et EBEP — PIAL / PAS**

> Outil conçu pour les coordonnateurs PIAL/PAS 

## Présentation

GestEBEP est une application web monopage (un seul fichier HTML) pour coordonner les accompagnements des élèves à besoins éducatifs particuliers (EBEP) dans le cadre d'un PIAL ou d'un PAS.

**Fonctionnalités principales :**
- Gestion des fiches AESH (contrat, temps partiel, absences, établissements)
- Gestion des fiches élèves EBEP (notifications MDPH, plans, soins, AESH affectées)
- Plannings hebdomadaires multi-vues : AESH · Élève · Classe · Établissement · Dispositif ULIS
- Gestion complète des dispositifs ULIS (AESH CO, créneaux élèves, vue unifiée)
- Requêtes croisées avec filtres multi-critères et export PDF / CSV
- Alertes automatiques (conflits, quotas, absences, événements)
- Gestion des événements (sorties, voyages, activités régulières)
- Synchronisation en temps réel multi-utilisateurs (Supabase)
- Fonctionne dans le navigateur, sans installation

## Accès

L'application est déployée sur Netlify :  
👉 **https://gestEBEP.netlify.app**

Chaque PIAL/PAS dispose d'un code d'accès propre qui isole ses données.

## Utilisation

1. Ouvrir l'URL dans Chrome ou Edge
2. Saisir le code de votre PIAL/PAS
3. C'est tout — aucune installation requise

La documentation complète est disponible dans le fichier `GestEBEP_Guide_utilisateur.docx`.

## Structure du projet

```
aesh-manager.html              # Application complète (fichier unique)
GestEBEP_Guide_utilisateur.docx  # Guide utilisateur détaillé
README.md                      # Ce fichier
LICENSE                        # Licence CC BY-SA 4.0
```

## Contexte

Conçu à l'École Laforet (Saint-Gilles, 30) — école REP/QPV.  
Utilisé dans le cadre de la coordination PIAL/PAS du Gard.

## Licence

© A. Juarez — Licence [Creative Commons Attribution – Partage dans les mêmes conditions 4.0 (CC BY-SA 4.0)](LICENSE)

Vous pouvez utiliser, modifier et redistribuer cet outil librement, à condition de citer l'auteure et de partager sous la même licence.
