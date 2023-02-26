## Emails, identite d'expediteur et magic links — P0

Je controle : enregistrements MX, SPF unique et valide, DKIM actif, DMARC (d'abord en observation puis renforce), sous-domaine dedie aux emails transactionnels, coherence entre From, domaine DKIM et domaine des liens, traitement des rebonds et plaintes, expiration/usage unique/revocation des magic links, limitation des tentatives et anti-enumeration des comptes.

Definition of Done : les emails arrivent chez Gmail, Outlook et Proton sans spam, et un lien deja utilise ne peut plus ouvrir de session.

Pour un SaaS a liens magiques, l'email est une composante d'authentification, pas seulement un canal marketing.

