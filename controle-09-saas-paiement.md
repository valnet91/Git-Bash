## Integrite du SaaS, paiement et conformite commerciale — P0

Je verifie le parcours de bout en bout : creation de compte, magic link, ajout de domaine, lancement du scan, limitation selon l'abonnement, paiement Mollie, signature et idempotence des webhooks, activation apres paiement reellement confirme, facture, renouvellement, resiliation, remboursement, suppression ou export des donnees, consentement newsletter distinct du service, identite juridique exacte sur toutes les pages.

Definition of Done : aucun prix ni droit d'acces n'est code manuellement dans plusieurs fichiers differents. Le prix affiche, le prix envoye a Mollie, le montant facture, le JSON-LD et les CGV viennent de la meme source de verite applicative.

