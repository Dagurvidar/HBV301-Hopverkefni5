# Gæðakrafa lýst í PLanguage 

> Þetta skjal sýnir hvernig á að skilgreina eina **gæðakröfu** með aðferðinni **P-Language** samkvæmt Wiegers & Beatty (kafli 14).

---

## Merkimiði (TAG)
Quality.Testability.CodeCoverage

---

## Tilgangur / Ásetningur (AMBITION)
Kóði kerfisins skal vera auðprófanlegur og að sjálfvirkar prófanir nái yfir hæfilega stóran hluti virkni þess til þess að villur greinist snemma og breytingar valda ekki ófyrirséðum afleiðingum. Þetta er til að spara tíma við yfirferð og viðhald og til að auka áreiðanleika kerfisins.

---

## Mælikvarði (SCALE)
Hlutfall kóða sem er keyrður að minnsta kosti einu sinni af sjálfvirkum einingaprófum, mælt með prósentu (code coverage %)

---

## Mælir / Mæliaðferð (METER)
Keyrsla á npm run test:coverage með Jest á helstu einingum. Coverage niðurstöður teknar úr Github Actions. Prófanir keyrðar við hvert merge á main branch.

---

## Markmið (GOAL)
Coverage skal vera a.m.k. 80% í einingum kerfis sem sjá um virkni eða geymslu gagna. (e.t.v. domain/ eða einfaldlega src/).

---

## Æskilegt (STRETCH)
Coverage >= 90%

---

## Óska (WISH)
100% coverage kóða

---

## Grunnkerfi (BASE PLATFORM)
Windows 11 x64, Node.js 20 LTS, Jest 29+, GitHub Actions CI með 4 vCPU / 8 GB RAM, PostgreSQL 15, dæmigerður gagnagrunnur með 10 000 skrám í prófunargögnum.

---

