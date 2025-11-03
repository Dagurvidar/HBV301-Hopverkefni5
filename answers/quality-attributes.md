# 5 ytri + 3 innri gæðaeiginleikar

> Ytri (external) — upplifun notenda/rekstur: 
> Innri (internal) — viðhald/þróun: 

Veljið eina kröfu og lýsið henni í sér skrá með PLanguage sniði 

| Eiginleiki | Krafa (1 setning) | Rök/forsemdir (2–3 setn.) |
|---|---|---|
| **1. Notagildi (Usability)** | Kerfið skal vera þannig hannað að nýr notandi geti framkvæmt helstu aðgerðir (skoðað einkunnir, skilað verkefnum) án leiðbeininga innan 2 mínútna. | Nemendur eru fjölbreyttur hópur með mismunandi tæknifærni og þurfa að geta notað kerfið án flókins námsferils. Einfalt viðmót dregur úr villum og stuðlar að ánægju notenda. Ef notagildi er lágt gæti það dregið úr notkun og trausti á kerfinu. |
| **2. Frammistaða (Performance)** | Kerfið skal hlaða helstu síðum (t.d. yfirlit yfir einkunnir) innan 3 sekúndna í 95% tilvika. | Nemendur og kennarar vinna undir tímaþrýstingi, sérstaklega í lok annar. Hraðvirk svörun eykur trúverðugleika kerfisins og dregur úr pirringi notenda. Takmarkaður fjárhagsrammi kallar á skilvirka kóðun og gagnageymslu. |
| **3. Öryggi (Security)** | Kerfið skal tryggja að aðeins viðkomandi notandi hafi aðgang að sínum gögnum með öruggri auðkenningu og dulkóðun gagna í flutningi. | Kerfið vinnur með viðkvæmar persónuupplýsingar um námsárangur og verkefni sem falla undir persónuverndarlög. Öruggt aðgengi byggir upp traust og uppfyllir lagakröfur. Vanræksla í öryggi gæti valdið trúnaðarbresti og ímyndarskaða. |
| **4. Aðgengi (Accessibility)** | Kerfið skal uppfylla WCAG 2.1 Level AA staðal til að tryggja nothæfi fyrir notendur með sjón- eða hreyfihömlun. | Skólakerfi þurfa að vera aðgengileg öllum, óháð líkamlegum eða tæknilegum hindrunum. Með því að fylgja stöðlum tryggjum við jöfnuð í aðgengi og lagalegt samræmi. Ef aðgengi er takmarkað geta sumir notendur ekki nýtt kerfið sjálfstætt. |
| **5. Áreiðanleiki (Reliability)** | Kerfið skal hafa aðgengi (uptime) að lágmarki 99% yfir önnina og endurheimta þjónustu innan 10 mínútna við minniháttar truflanir. | Einkunnagjöf og verkefnaskil eru tímaháð, svo notendur þurfa stöðugan aðgang að kerfinu. Hátt þjónustuhlutfall byggir á stöðugu hýsingarumhverfi og sjálfvirkri viðvörunarkerfi. Truflanir geta haft bein áhrif á námsframvindu og traust. |


## Innri (3)
| Eiginleiki | Krafa (1 setning) | Rök/forsemdir (2–3 setn.) |
|---|---|---|
| 1. Skalanleiki (Scalability) | Kerfið skal styðja fjönotendaaðgang og gagnavinnslu með hæfilegum viðbragðstíma (< 3 sek) þegar notendafjöldi tvöfaldast | Skalanleiki tryggir að kerfið viðhaldi frammistöðu þegar álag eykst, sem er mikilvægt fyrir kerfi með marga nemendur og kennara sem nota kerfið misjafnt fyrir utan sérstaka viðburði t.d. eins og einkunnaútgjöf. Skipulögð gagnavinnsla og kerfisbundið caching draga úr hættu á að kerfið hægist við hámarksnotkun. |
| 2. Prófunarleiki (testability) | Prófanir ættu að prófa meira eða jafnt og 80% af kóða (coverage >= 80%) | Tryggir að villur greinist snemma og breytingar brjóti ekki kerfið. Þetta er mikilvægt svo að forritarar viti áður en þeir geta skilað inn breytingum hvort þær hafi haft óæskilegar afleyðingar. Þetta sparar þeim sem fara yfir kóðann tíma. |
| 3. Viðhaldleiki (maintainability) | Föll <= 50 línur, ESList án villna. | Styður áreiðanleika, notkunargildi, aðgengi og lesanleika. Með því að hafa gott modularity er kóðinn lesanlegri og einnig styttri þar sem föll sem skipt eru í nokkur hjálparföll geta verið notuð annars staðar í kóðanum |
