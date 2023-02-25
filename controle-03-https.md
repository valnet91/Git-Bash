## HTTPS, certificats et en-tetes de securite — P0

Je verifie pour chaque hote : certificat valide pour le domaine, www et les sous-domaines, redirection HTTP vers HTTPS en une seule etape, absence de contenu mixte, TLS moderne, en-tetes Strict-Transport-Security (apres validation de tous les sous-domaines), Content-Security-Policy, X-Content-Type-Options nosniff, Referrer-Policy, Permissions-Policy, protection contre l'affichage en iframe via CSP frame-ancestors.

Definition of Done : aucun avertissement navigateur, certificat supervise et politique CSP testee sans casser Mollie, les formulaires ou le cockpit.

OWASP recommande ces en-tetes comme couche de defense contre le XSS, le clickjacking et les fuites d'information.

