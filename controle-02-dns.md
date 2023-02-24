## DNS et propagation mondiale — P0

Je controle : A et eventuellement AAAA du domaine racine, CNAME des sous-domaines, coherence entre www et domaine nu, serveurs NS redondants, TTL adaptes, CAA pour limiter les autorites de certification, DNSSEC si le registrar et l'hebergeur le permettent, absence de wildcard DNS inutile, resolution coherente depuis plusieurs resolveurs (Google, Cloudflare, Quad9, serveurs autoritatifs).

Definition of Done : tous les resolveurs retournent la meme cible, sans SERVFAIL, boucle CNAME ou ancienne IP.

