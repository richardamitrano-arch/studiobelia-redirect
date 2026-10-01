# studiobelia.it → www.studiobelia.it

Pagina di rimando: chi apre `studiobelia.it` (senza www) viene portato a
`https://www.studiobelia.it/`, conservando percorso e parametri.

Il sito vero sta su Cloudflare Pages e risponde su `www`. Cloudflare Pages non
accetta un dominio senza www quando il DNS è esterno, quindi il dominio nudo
punta qui (GitHub Pages) e viene rimandato.

DNS (Hostinger): `ALIAS @ → richardamitrano-arch.github.io`.
