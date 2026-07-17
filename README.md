<!-- GENERE depuis base.csv par Prog_Main_B.r -- NE PAS EDITER A LA MAIN -->
---
canonical: https://alchimiste-ia.com/Git-Bash
author: Jean-Jacques Valognes
publisher: Alchimiste-IA
rna: W912007379
---

# Git-Bash

> Documentation AI-READY d'Alchimiste-IA, par Jean-Jacques Valognes.
> https://alchimiste-ia.com/ · RNA W912007379

## Sommaire

  - [🔐 Propriete, marque et souverainete du domaine — P0](#propriete-marque-et-souverainete-du-domaine-p0)
  - [🌐 DNS et propagation mondiale — P0](#dns-et-propagation-mondiale-p0)
  - [🔒 HTTPS, certificats et en-tetes de securite — P0](#https-certificats-et-en-tetes-de-securite-p0)
  - [📧 Emails, identite d'expediteur et magic links — P0](#emails-identite-d-expediteur-et-magic-links-p0)
  - [🔍 SEO technique et maitrise de l'indexation — P0/P1](#seo-technique-et-maitrise-de-l-indexation-p0-p1)
  - [🌍 SEO international des 19 langues — P1](#seo-international-des-19-langues-p1)
  - [🤖 GEO, agents IA et donnees structurees — P1](#geo-agents-ia-et-donnees-structurees-p1)
  - [⚡ Performance, accessibilite et HCI — P1](#performance-accessibilite-et-hci-p1)
  - [💳 Integrite du SaaS, paiement et conformite commerciale — P0](#integrite-du-saas-paiement-et-conformite-commerciale-p0)
  - [📊 Observabilite, non-regression et continuite — P0/P1](#observabilite-non-regression-et-continuite-p0-p1)

<a id="propriete-marque-et-souverainete-du-domaine-p0"></a>
### 🔐 Propriete, marque et souverainete du domaine — P0

Je verifie : compte registrar protege par 2FA, verrouillage du transfert, renouvellement automatique et moyen de paiement de secours, adresse de recuperation independante du domaine, acces partage et documente (pas uniquement detenu par le fondateur), disponibilite ou protection de la marque aupres de l'INPI/EUIPO, reservation des variantes (sans tiret, fautes frequentes, .fr, comptes sociaux).

Definition of Done : la perte d'un telephone, d'un collaborateur ou d'une carte bancaire ne peut pas provoquer la perte du domaine.

<a id="dns-et-propagation-mondiale-p0"></a>
### 🌐 DNS et propagation mondiale — P0

Je controle : A et eventuellement AAAA du domaine racine, CNAME des sous-domaines, coherence entre www et domaine nu, serveurs NS redondants, TTL adaptes, CAA pour limiter les autorites de certification, DNSSEC si le registrar et l'hebergeur le permettent, absence de wildcard DNS inutile, resolution coherente depuis plusieurs resolveurs (Google, Cloudflare, Quad9, serveurs autoritatifs).

Definition of Done : tous les resolveurs retournent la meme cible, sans SERVFAIL, boucle CNAME ou ancienne IP.

<a id="https-certificats-et-en-tetes-de-securite-p0"></a>
### 🔒 HTTPS, certificats et en-tetes de securite — P0

Je verifie pour chaque hote : certificat valide pour le domaine, www et les sous-domaines, redirection HTTP vers HTTPS en une seule etape, absence de contenu mixte, TLS moderne, en-tetes Strict-Transport-Security (apres validation de tous les sous-domaines), Content-Security-Policy, X-Content-Type-Options nosniff, Referrer-Policy, Permissions-Policy, protection contre l'affichage en iframe via CSP frame-ancestors.

Definition of Done : aucun avertissement navigateur, certificat supervise et politique CSP testee sans casser Mollie, les formulaires ou le cockpit.

OWASP recommande ces en-tetes comme couche de defense contre le XSS, le clickjacking et les fuites d'information.

<a id="emails-identite-d-expediteur-et-magic-links-p0"></a>
### 📧 Emails, identite d'expediteur et magic links — P0

Je controle : enregistrements MX, SPF unique et valide, DKIM actif, DMARC (d'abord en observation puis renforce), sous-domaine dedie aux emails transactionnels, coherence entre From, domaine DKIM et domaine des liens, traitement des rebonds et plaintes, expiration/usage unique/revocation des magic links, limitation des tentatives et anti-enumeration des comptes.

Definition of Done : les emails arrivent chez Gmail, Outlook et Proton sans spam, et un lien deja utilise ne peut plus ouvrir de session.

Pour un SaaS a liens magiques, l'email est une composante d'authentification, pas seulement un canal marketing.

<a id="seo-technique-et-maitrise-de-l-indexation-p0-p1"></a>
### 🔍 SEO technique et maitrise de l'indexation — P0/P1

Je verifie : codes HTTP reels (200, 301, 404, 410), un seul domaine canonique, balises title/description/canonical, un seul h1 pertinent par page, robots.txt, sitemap.xml ne contenant que les URL canoniques, inscription Google Search Console et Bing Webmaster Tools, pages privees/cockpit/paiements en noindex, pages d'erreur reellement servies en 404, liens internes sans dependance exclusive au JavaScript.

Definition of Done : les pages commerciales sont indexables, les ecrans d'authentification, de paiement et de cockpit ne le sont pas.

<a id="seo-international-des-19-langues-p1"></a>
### 🌍 SEO international des 19 langues — P1

Je verifie : URL distincte par langue, attribut lang HTML correct, hreflang reciproques, x-default sur le selecteur de langue, canonical vers la page de la meme langue, titres/descriptions/JSON-LD localises, selecteur de langue accessible sur chaque page, aucune redirection forcee selon l'adresse IP, absence de melange linguistique.

Definition of Done : chaque page dispose de sa propre URL localisee, avec hreflang et canonical coherents, sans redirection geographique forcee.

<a id="geo-agents-ia-et-donnees-structurees-p1"></a>
### 🤖 GEO, agents IA et donnees structurees — P1

Je distingue quatre niveaux : HTML reellement lisible sans execution complexe, entites et donnees structurees coherentes, documents citables/dates/sources, fichiers experimentaux destines aux agents. Je controle notamment : JSON-LD Organization/WebSite/SoftwareApplication/Product/Offer, coherence entre prix visible/JSON-LD/CGV, pages methode/documentation/securite/auteur, robots.txt par type d'agent si besoin, flux RSS/Atom ou changelog, /llms.txt lisible et structure, sources primaires derriere chaque affirmation technique, date et version du referentiel de scoring.

Point doctrinal : llms.txt reste une proposition, pas une norme IETF ni une garantie de visibilite ou de citation. Il doit rester un bonus, jamais un critere bloquant devant l'HTML, le SEO, les donnees structurees et l'autorite editoriale.

<a id="performance-accessibilite-et-hci-p1"></a>
### ⚡ Performance, accessibilite et HCI — P1

Je mesure : Core Web Vitals reels (LCP, INP, CLS), TTFB par region, poids HTML/CSS/JS/images, comportement mobile, parcours clavier, contraste et focus visible, textes alternatifs, labels des formulaires, annonces accessibles des erreurs, experience quand JavaScript echoue, lisibilite des prix/CTA/confirmations.

Definition of Done : une personne peut comprendre l'offre, renseigner son email, payer et consulter son rapport sur mobile, au clavier et avec une connexion mediocre.

Les Core Web Vitals doivent etre mesures sur l'experience reelle des visiteurs, Lighthouse restant essentiellement un outil de diagnostic en laboratoire.

<a id="integrite-du-saas-paiement-et-conformite-commerciale-p0"></a>
### 💳 Integrite du SaaS, paiement et conformite commerciale — P0

Je verifie le parcours de bout en bout : creation de compte, magic link, ajout de domaine, lancement du scan, limitation selon l'abonnement, paiement Mollie, signature et idempotence des webhooks, activation apres paiement reellement confirme, facture, renouvellement, resiliation, remboursement, suppression ou export des donnees, consentement newsletter distinct du service, identite juridique exacte sur toutes les pages.

Definition of Done : aucun prix ni droit d'acces n'est code manuellement dans plusieurs fichiers differents. Le prix affiche, le prix envoye a Mollie, le montant facture, le JSON-LD et les CGV viennent de la meme source de verite applicative.

<a id="observabilite-non-regression-et-continuite-p0-p1"></a>
### 📊 Observabilite, non-regression et continuite — P0/P1

Je mets en place : surveillance du domaine/DNS/certificat, tests synthetiques du site/login/paiement, suivi des erreurs front et back, journaux d'audit, alertes sur les echecs d'email et de webhook, mesure du tunnel visite-scan-email-compte-paiement, sauvegardes automatiques, test de restauration reel, controle SEO/GEO a chaque deploiement, politique de rollback, page de statut separee, SLO mesurable et rapport mensuel.

