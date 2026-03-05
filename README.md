# iuytresdcvbhnt — Guide ERP & CRM

[![Netlify](https://img.shields.io/badge/Netlify-Déployé-00C7B7?logo=netlify)](https://sidz0801.netlify.app/)
[![IGE511](https://img.shields.io/badge/Cours-IGE511-b5390a)](https://www.usherbrooke.ca/)
[![Auteur](https://img.shields.io/badge/CIP-sidz0801-1a1a1a)](https://github.com/ZoubaGate)

> Projet réalisé dans le cadre du cours **IGE 511 — Aspects informatiques du commerce électronique**  
> Université de Sherbrooke · **Siddharth Zoubagate** · CIP : `sidz0801`

---

## 🌐 Site en ligne

**[https://sidz0801.netlify.app/](https://sidz0801.netlify.app/)**

---

## 📋 Description du projet

Ce projet est un **concours de référencement SEO** dont l'objectif est d'être indexé et positionné le mieux possible sur Google pour le mot-clé unique : **`iuytresdcvbhnt`**.

**Thème choisi : les logiciels ERP et CRM**, un sujet central du commerce électronique et de la gestion d'entreprise numérique. Le site va plus loin qu'un simple exercice SEO : il propose un guide pratique sur les combinaisons ERP + CRM les plus adaptées selon le profil de l'entreprise.

---

## 🏗️ Structure du projet

```
iuytresdcvbhnt/
├── index.html       # Page principale — HTML sémantique + JSON-LD
├── styles.css       # Feuille de styles externe (Lora serif + Source Sans 3)
├── robots.txt       # Instructions pour les robots d'indexation
├── sitemap.xml      # Plan du site soumis à Google Search Console
└── README.md        # Ce fichier
```

---

## 🎯 Contenu du site

### Sections principales

| Section | Contenu |
|---------|---------|
| **Accueil / Hero** | Présentation du guide avec diagramme architectural ERP/CRM |
| **Qu'est-ce que iuytresdcvbhnt ?** | Contexte du projet, définitions ERP et CRM |
| **Quel type d'ERP choisir ?** | SAP S/4HANA, Odoo, Microsoft Dynamics 365, Oracle NetSuite |
| **Les meilleurs CRM** | Salesforce, HubSpot, Zoho CRM, Pipedrive |
| **Pairings ERP + CRM recommandés** | 4 combinaisons selon profil d'entreprise |
| **Tableau comparatif ERP vs CRM** | 8 critères comparés sur 3 types de solutions |
| **Ressources & liens** | 6 liens externes indexés (Mallek, Instagram, GitHub, Trailhead, Odoo) |
| **FAQ** | 6 questions/réponses schema.org FAQPage |
| **Changelog** | 7 entrées datées depuis le début du TP1 |

### Section phare : Pairings ERP + CRM

La section originale de ce site explique **quelle combinaison ERP + CRM choisir** selon 4 profils :

- 🏢 **SAP S/4HANA** → SAP Sales Cloud ⭐ / Salesforce ✅ / Dynamics Sales 🔶
- 🏪 **Odoo (PME)** → Odoo CRM intégré ⭐ / HubSpot ✅ / Zoho CRM 🔶
- 🏦 **Microsoft Dynamics 365** → Dynamics Sales ⭐ / Salesforce ✅ / HubSpot 🔶
- 🚀 **Oracle NetSuite (Scale-up)** → Salesforce ⭐ / HubSpot ✅ / Zoho CRM 🔶

---

## 🔍 Stratégies SEO implémentées

### On-page
- `<title>` optimisé avec le mot-clé cible et intention de recherche
- `<meta description>` naturelle et incitative au clic
- **H1 unique** avec mot-clé principal — typographie serif naturelle (Lora)
- Contenu riche (+2 000 mots), densité de mot-clé contrôlée et naturelle
- Structure sémantique HTML5 : `<header>`, `<main>`, `<nav>`, `<section>`, `<footer>`, `<details>`/`<summary>`
- Attributs `aria-label` sur tous les liens et éléments interactifs

### Données structurées (JSON-LD / Schema.org)
- **`WebSite`** — identification du site et de l'auteur
- **`WebPage`** — description de la page principale avec sujet associé
- **`FAQPage`** — 6 questions/réponses (éligibles aux rich snippets Google)
- **`BreadcrumbList`** — fil d'Ariane avec 4 niveaux

### Technique
- **`robots.txt`** — autorisation complète d'indexation + pointeur sitemap
- **`sitemap.xml`** — soumis à Google Search Console, `changefreq: weekly`
- **Canonical URL** — évite le contenu dupliqué entre http/https et www/non-www
- **`<meta name="robots">`** — `max-snippet:-1`, `max-image-preview:large`
- **Open Graph** (Facebook, LinkedIn) et **Twitter Card** pour le partage social
- **CSS externe** (`styles.css`) — meilleure séparation contenu/présentation, chargement optimisé

### Design & typographie
- **Lora** (serif, Google Fonts) pour les titres — typographie naturelle et lisible
- **Source Sans 3** pour le corps de texte — clarté et confort de lecture
- Design responsive avec grilles CSS — adapté mobile, tablette, desktop

### Off-page & linking
- **Liens entrants** : ce README sur GitHub, Netlify
- **Liens sortants pertinents** : SAP, Odoo, Salesforce, HubSpot, Zoho, Pipedrive, NetSuite, Salesforce Trailhead
- **Lien croisé** vers le site [hanm1601.netlify.app](https://hanm1601.netlify.app/) — autre projet IGE 511 indexé sur le même mot-clé
- **Signal social** via Instagram @iuytresdcvbhnt et TikTok @iuytresdcvbhnt

---

## 📊 Changelog

| Date | Modification |
|------|-------------|
| 2025-01-28 | Création initiale du site sur Netlify, structure HTML de base, méta-données SEO, robots.txt, sitemap.xml |
| 2025-02-04 | Ajout Open Graph, Twitter Card, JSON-LD complets (WebSite, WebPage, FAQPage, BreadcrumbList) |
| 2025-02-11 | Refonte visuelle : Lora serif pour titres, Source Sans 3 pour le corps, palette couleur, hero deux colonnes |
| 2025-02-18 | Tableau comparatif ERP vs CRM, 8 cartes solutions avec liens officiels |
| 2025-02-25 | Section Ressources : liens hanm1601.netlify.app, Instagram @iuytresdcvbhnt, Salesforce Trailhead, blog Odoo. Stratégie linking externe. |
| 2025-03-04 | Optimisation SEO avancée, FAQ étendue à 6 questions, améliorations accessibilité, Search Console |
| 2025-03-05 | CSS externalisé, police naturelle serif, section Pairings ERP+CRM (4 profils), mention IA (Claude), README complet |
| 2025-03-05 | Section Ressources enrichie : ERP (SAP, Odoo, Dynamics, NetSuite) + CRM (Salesforce, HubSpot, Zoho, Trailhead). Ajout TikTok @iuytresdcvbhnt. Nom et CIP agrandis dans le footer. |

---

## 🔗 Liens connexes

| Ressource | URL |
|-----------|-----|
| 🌐 Mon site Netlify | [sidz0801.netlify.app](https://sidz0801.netlify.app/) |
| 🐙 Mon GitHub | [github.com/ZoubaGate](https://github.com/ZoubaGate) |
| 📸 Instagram @iuytresdcvbhnt | [instagram.com/iuytresdcvbhnt](https://www.instagram.com/iuytresdcvbhnt/) |
| 🎵 TikTok @iuytresdcvbhnt | [tiktok.com/@iuytresdcvbhnt](https://www.tiktok.com/@iuytresdcvbhnt) |
| 🌐 Site IGE 511 connexe | [hanm1601.netlify.app](https://hanm1601.netlify.app/) |
| ☁️ Salesforce CRM | [salesforce.com/ca/crm](https://www.salesforce.com/ca/crm/) |
| 🟠 HubSpot CRM | [hubspot.com/products/crm](https://www.hubspot.com/products/crm) |
| 🟣 Odoo ERP | [odoo.com/fr_FR](https://www.odoo.com/fr_FR) |
| 🏢 SAP S/4HANA | [sap.com/canada-fr](https://www.sap.com/canada-fr/products/erp.html) |
| 🔷 Microsoft Dynamics 365 | [microsoft.com/fr-ca/dynamics-365](https://www.microsoft.com/fr-ca/dynamics-365) |
| 🎓 Salesforce Trailhead CRM | [trailhead.salesforce.com](https://trailhead.salesforce.com/fr/content/learn/modules/crm) |

---

## 🤖 Utilisation de l'intelligence artificielle

Conformément aux directives du TP1 (IGE 511) qui autorisent l'utilisation d'outils d'IA, ce projet a été développé **en collaboration avec Claude (Anthropic)**.

L'IA a assisté dans les tâches suivantes :
- Génération et structuration du contenu HTML/CSS
- Rédaction du contenu sur les ERP, CRM et leurs combinaisons
- Optimisation des balises SEO (title, meta, JSON-LD, Open Graph)
- Conception de la section originale "Pairings ERP + CRM recommandés"
- Rédaction du README et du changelog

> Les choix de thème, de stratégie SEO, et les décisions de déploiement ont été effectués par l'auteur. L'IA a servi d'outil d'assistance, non de substitut à la réflexion personnelle.

---

## 👤 Auteur

**ZOUBAIR SIDIBE**  
CIP : `sidz0801`  
Université de Sherbrooke — Département d'informatique, faculté des sciences  
Cours : **IGE 511 — Aspects informatiques du commerce électronique**

---

*Mot-clé cible : **iuytresdcvbhnt** · Hébergement : Netlify · Domaine : [sidz0801.netlify.app](https://sidz0801.netlify.app/)  
Développé avec l'aide de **Claude (Anthropic)***
