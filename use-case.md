# Fully Dressed Use Case

**ID:** UC-1  
**Heiti:** Skipuleggja ferð og kaupa miða 
**Aðal aðili:** Notandi Straums (gestur eða innskráður)  
**Aukaaðilar:** Greiðslugátt, Samgönguveitur (Strætó, Hopp, rútur o.fl.), Staðsetningarþjónusta (GPS), Tilkynningaþjónusta, Auðkenningarþjónusta (ef innskráning á sér stað)

## Forsendur
- Notandi hefur aðgang að Straumi (app eða vef) og nettengingu.
- Samstarfsaðilar sem styðja fyrstu útgáfu eru tengdir (minnst Strætó + 1 örflutningsveita).
- Kerfið má nota í **gestaham** (án aðgangs); innskráning gefur aukna virkni (sögu, kvittanir o.fl.).
- Leyfi fyrir staðsetningu er valkvætt, en bætir niðurstöður (upphafsstaður sjálf-fyllist).

## Eftirskilyrði
- Ferð hefur verið skipulögð og miði keyptur (ef nauðsynlegt fyrir valinn ferðamáta).
- Kerfið skráir **skipulagstíma** (frá „Byrja skipulagningu“ til „Staðfest kaup“) fyrir BO-1.
- Notandi fær staðfestingu/kvittun og getur skoðað ferð í „Mínar ferðir“ (ef innskráður) eða í staðbundinni geymslu (gestur).

## Aðalflæði
1. Notandi opnar Straum og velur **„Plana ferð“**.
2. Kerfið birtir leitarskjá með reitunum **Frá**, **Til**, **Brottfarartími/Komutími**, sía (ferðamátar) og **Leita**.
3. *(Val)* Kerfið leggur til **Frá** út frá GPS/stefnu; notandi getur breytt.
4. Notandi setur inn **Til** (áfangastað) og velur tíma (núna eða síðar); ýtir á **Leita**. → **Tímamælir BO-1 byrjar.**
5. Kerfið sækir leiðir, sameinar þjónustur (t.d. Strætó + Hopp) og sýnir **samanburð** (tími, kostnaður, CO₂, göngulengd, áreiðanleiki).
6. Notandi velur **leið** og skoðar nánari skref með kortsýningu og brottfarartímum í rauntíma ef tiltækt.
7. Notandi velur **Kaupa/Reserva** (ef leið krefst miða) og setur greiðslumáta (Apple/Google Pay eða kort).  
   - Ef **gestur**, kerfið biður um tölvupóst fyrir kvittun (valkvætt).
8. Kerfið **staðfestir kaup**, birtir kvittun og geymir miða/heimild (QR/NFC) og leiðarskref.
9. **Tímamælir BO-1 stoppar.** Kerfið skráir heildartíma og lykilskref (til greiningar BO-1/BO-2).
10. Kerfið býður **leiðsögn/tilkynningar** (t.d. „Ferð seinkar 3 mín“) og geymir ferð.

## Valflæði
- **A1: Innskráning fyrir kaup**  
  Notandi velur „Innskrá“ (eða „Halda áfram sem gestur“). Eftir árangursríka innskráningu heldur aðalflæði áfram í skref 7.
- **A2: Breyta forgangi (hraði vs. verðsparnaður vs. umhverfi)**  
  Notandi velur sía/vigtun (t.d. „hraðast“, „ódýrast“, „lágmarks CO₂“); kerfið endurraðar niðurstöðum; heldur áfram í skref 6.
- **A3: Engin greiðsla nauðsynleg (ókeypis leg eða staðfesting nægir)**  
  Skref 7 fellur niður; kerfið staðfestir bókun/leið og fer beint í skref 9.
- **A4: Staðsetningarleyfi hafnað**  
  Kerfið biður um handvirkt „Frá“; heldur áfram í skref 4.

## Undantekningar
- **E1: Engar leiðir fundust**  
  Kerfið stingur upp á nálægum stoppum/tímum og biður um að breyta viðmiðum (dagsetning/sía); ef notandi hafnar, UC lýkur með stöðu „enginn kostur“.
- **E2: Veituskekkja/niður í API hjá samstarfsaðila**  
  Kerfið sýnir aðra kosti og merkingu „veita ótiltæk“; loggar til BO-4/SLA; heldur áfram ef mögulegt, annars „reyna aftur“.
- **E3: Greiðsla hafnað**  
  Kerfið biður um annan greiðslumáta eða „vista leið án kaupa“; ef mistókst aftur, UC lýkur án kaupa.
- **E4: Óvirkni notanda (tímamælir)**  
  Eftir X mín. birtist „Viltu halda áfram?“; ef ekki svar, tímamælir stöðvast og gögn vistast í „drög“; UC lýkur.
- **E5: Verð/tími breytist á meðan á kaupum stendur**  
  Kerfið sýnir breytingu og biður um samþykki; ef hafnað, aftur í skref 6.

## Tengsl (Traceability)
- BO: BO-1, BO-2, BO-3, BO-4, BO-5
- FR: FR-1, FR-2, FR-3, FR-4, FR-5, FR-6, FR-7, FR-8, FR-12
- UR: UR-1, UR-2, UR-3, UR-4, UR-5, UR-6, UR-7, UR-8, UR-9, UR-10
- QR: QR-1, QR-2, QR-3, QR-4, QR-5
- BR: BR-1, BR-2, BR-3, BR-4, BR-5, BR-6, BR-7, BR-8, BR-9, BR-10


## Tengsl (Traceability)
- BO: BO-1 (tímamælir í skrefum 4 & 9), BO-2 (sameining í skrefum 5–8), BO-4 (fallback E2)
- FR: FR-1 (leiðareiknir – skref 5–6), FR-2 (samþættingar – skref 5–8/E2), FR-4 (kaup – skref 7–8), FR-5 (tímamæling – skref 4 & 9), FR-7 (röðun – skref 5–6), FR-8 (gestahamur – forsendur/A1), FR-12 (flýtileiðir – skref 1–2)
- UR: UR-1 (multimodal – skref 5–6), UR-2 (Frá/Til/tími – skref 2–4), UR-5 („search+enter“ – skref 2–4), UR-6 (raða – skref 5–6), UR-7 (gestur – forsendur/A1)
- QR: QR-1 (afköst – skref 2,5,7–8), QR-2 (aðgengi – leit/checkout), QR-3 (áreiðanleiki – E2), QR-4 (öryggi – skref 7–8), QR-5 (villur – E2/E3)
- BR: BR-1 (ekki sýna aðra notendur – skref 6), BR-3 (mælingarregla – skref 4 & 9/E4), BR-5 (integration form – E2)



