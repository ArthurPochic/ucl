# ucl
Web page presenting the 24 clubs qualified for the knockouts of the 25/26 UCL 
# ⚽ Champions League 2025-2026 — Clubs & Effectifs

Page web interactive présentant les clubs et effectifs participants à la UEFA Champions League 2025-2026.

## Description

Ce projet présente les données de 24 participant à la Champions League 2025-2026, incluant pour chaque club :
- Les informations générales (ville, pays, stade)
- Le staff technique (entraîneur)
- L'effectif complet avec pour chaque joueur : nom, prénom, numéro, poste, nationalité, taille, pied fort et date de naissance

## Technologies utilisées

- **XML** — Stockage des données
- **XSD** — Validation de la structure XML
- **XSL/XSLT** — Transformation et affichage des données
- **HTML/CSS** — Mise en page et style

## Structure du projet
```
├── championsleague.xml     # Base de données des clubs et joueurs
├── championsleague.xsl     # Feuille de transformation XSL
├── champions_league.xsd    # Schéma de validation XSD
└── style.css               # Feuille de style CSS
```

## 🏟️ Clubs présents

| Club | Pays |
|------|------|
| PSG | France |
| FC Barcelona | Espagne |
| Real Madrid CF | Espagne |
| Arsenal FC | Angleterre |
| FC Bayern München | Allemagne |
| Manchester City | Angleterre |
| Liverpool FC | Angleterre |
| Chelsea FC | Angleterre |
| Bodo/Glimt | Norvège |
| AS Monaco | Monaco |
| Tottenham Hotspur | Angleterre |
| Sporting CP | Portugal |
| Atalanta BC | Italie |
| Galatasaray | Turquie |
| Newcastle United | Angleterre |
| Bayer Leverkusen | Allemagne |
| Juventus FC | Italie |
| SL Benfica | Portugal |
| Inter Milan | Italie |
| Atletico Madrid | Espagne |
| Qarabag FK | Azerbaïdjan |
| Borussia Dortmund | Allemagne |
| Club Bruges | Belgique |
| Olympiakos | Grèce |

## Lancer le projet en local

1. Clone le repository :
\```bash
git clone https://github.com/tonnom/champions-league-clubs.git
\```

2. Lance un serveur local avec Python :
\```bash
cd champions-league-clubs
python -m http.server 8080
\```

3. Ouvre dans Firefox :
\```
http://localhost:8080/championsleague.xml
\```

> ⚠️ **Note** : Le fichier XML doit être ouvert via un serveur local (pas directement depuis l'explorateur de fichiers) en raison des restrictions de sécurité des navigateurs modernes concernant les transformations XSLT.

## Données

Les données des joueurs ont été collectées depuis **Transfermarkt** et incluent :
- 625 joueurs recensés
- Données mises à jour pour la saison **2025-2026**

## Auteur

**Arthur Pochic** — Étudiant à CY Tech
