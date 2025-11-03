# Árekstrapör (3)

## Par 1: Öryggi (Security) vs. Aðgengi (Accessibility)
- **Árekstur (2–3 setningar):**  
  Aukið öryggi, t.d. í formi tvíþættrar auðkenningar eða styttri innskráningartíma, getur gert notendum með fötlun eða tæknilegar takmarkanir erfiðara að nota kerfið.  
  Á hinn bóginn getur of mikið aðgengi, t.d. einfaldari innskráning eða opnari aðgangsleiðir, aukið hættuna á að viðkvæm gögn nemenda verði aðgengileg óviðkomandi aðilum.

- **Forgangsröðun og rök:**  
  Öryggi fær forgang, þar sem trúnaður og vernd persónuupplýsinga nemenda eru lögbundin og lykilatriði í trausti til kerfisins.  
  Aðgengi skal þó ekki vanrækja og tryggt verður að örugg auðkenning sé hönnuð með aðgengilegu viðmóti (t.d. með hjálpartækjum, stillanlegum auðkenningarleiðum og notendavænni villumeðhöndlun).  
  *Taktík:* stigvaxandi öryggi („progressive security“) þar sem notendur geta valið milli hraðari innskráningar og aukinnar verndar eftir þörfum.  

## Par 2: Notagildi (Usability) vs. Öryggi (Security)
- **Árekstur:** Sterkara öryggi, t.d. með 2FA, session timeout, ströng lykilorðsskilyrði bætir öryggi en gerir notkun á kerfinu hægari eða jafnvel erfiðari. Á hinn boginn væri að hafa t.d. engin lykilorðsskilyrði og ekkert 2FA kerfið mjög hratt og þægilegt að fá aðgang að, sem bætir notagildi en myndi ekki vera mjög öruggt.
- **Forgangsröðun og rök:** Öryggi fær forgang. Þar sem trúnaður og vernd persónuupplýsinga nemenda eru lögbundin og lykilatriði í trausti kerfisins fórnum við frekar notendagildi sérstaklega þar sem það versnar aðeins við fyrsta aðgang notenda per session.

## Par 3: Frammistaða (Performance) vs. Áreiðanleiki (Reliability)
- **Árekstur:** Með því að bæta performance með því t.d. að bæta hraða kerfisins með fire-and-forget aðferðum og slíkt bætir performance en í því ferli er líklegra að gögn týnist eða aðrar villur komi upp sem skaðar áreiðanleika. Hin vegar ef við tryggjum algjöran áreiðanleika myndum við nota aðferðir sem taka lengri tíma sem skaðar frammistöðu.
- **Forgangsröðun og rök:** Áreiðanleiki fær forgang. Í kerfi sem geymir mikilvæg gögn eins og einkunnir og mætingu er mikilvægt að nemendur og prófessorar hafi aðgang að gögnunum as is (þ.e.a.s. viljum tryggja integrity algerlega).
