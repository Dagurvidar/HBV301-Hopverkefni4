# Kröfulisti

## Viðskiptakröfur

- BO-1: Sameina fjölbreytta ferðamáta (strætó, rútur, rafskútur, deilibílar, leigubílar, hjól, göngur, o.fl.) á einn stað.

- BO-2: Minnka heildartíma frá „Skipuleggja ferð“ þar til miði er keyptur.

- BO-3: Auka notkun almenningssamgangna og umhverfisvænna ferðamáta.

- BO-4: skalanleg hönnun: skalast í fleiri markaði/þjónustur (t.d. DK og ferjur/bátar) án arkitektúrbreytinga.

- BO-5: Hægt á að vera að mæla og sanna einföldun ferlis (tími, fjöldi skrefa, notendakannanir).

## Notendakröfur

- UR-1: Geta skipulagt ferð yfir marga ferðamáta með einni leit.

- UR-2: Velja upphafs-/áfangastað og brottfarar/komutíma.

- UR-3: Skoða gagnvirkt kort með stoppistöðvum, þjónustusvæðum og aðgengi (strætó, Hopp o.fl.) með síum.

- UR-4: Panta/kaupa miða (í appi eða með djúptengli) fyrir valda þjónustu.

- UR-5: Hraðleit – „search + enter“ ætti oft að nægja.

- UR-6: Sjá leiðir raðaðar eftir tíma, kostnaði og umhverfisáhrifum (eða svipuðum mælikvörðum).

- UR-7: Nota appið sem gestur (án aðgangs).

- UR-8: Traust leiðaval á álagstímum (svipað og Google Maps upplifun).

- UR-9: Veita einfaldlega endurgjöf í könnunum um upplifaða einföldun.

- UR-10: Nota síur til að fela/sýna tiltekna ferðamáta (t.d. einungis göngur + strætó).

## Virknikröfur (Functional)

- FR-1: Leiðareiknir sem styður fjölþættar samgöngur og álagstíma/rauntímagögn þar sem það er í boði.

- FR-2: Samþætting við þjónustur, t.d. í gegnum API (Klapp, Strætó, Hopp, BSÍ, Bolt o.fl.); aðlögunarhæft fyrir hvern samstarfsaðila.

- FR-3: Kortalög: stoppistöðvar, þjónustusvæði, tiltækni/biðtímar (þar sem við á); síur og togglar.

- FR-4: Miðakaup/pöntun: innbyggt checkout eða örugg tenging við þjónustuaðila; styður gestagreiðslu þar sem mögulegt.

- FR-5: Innbyggður tímamælingarhugbúnaður frá skipulagningu til kaupa; með sjálfvirkri óvirknigreiningu og útlagasíun.

- FR-6: Mæling á fjölda notendaskrefa í lykilflæði.

- FR-7: Einkenni leiða: reikna og birta tíma, kostnað og áætluð umhverfisáhrif; raða eftir forgangi notanda.

- FR-8: Virkni fyrir gestaaðgang með lágmörkuðum gagnaafnotum.

- FR-12: Notendaviðmót fyrir flýtileiðir: „Plana“, „Kort“, „Panta“, „Kaupa miða“ o.fl.

## Gæðakröfur (Non-functional)

- QR-1: Afköst: skjáopnanir og leitarsvörunartími (t.d. <1–2s fyrir algengar aðgerðir – nákvæm mörk skilgreind síðar).

- QR-2: Aðgengi: uppfylla a.m.k. WCAG 2.2 AA.

- QR-3: Áreiðanleiki/Framboð: „Liggur aldrei niðri“ → hár framboðsmarkmið (t.d. ≥99.9% á mánuði) og sjálfvirk vöktun.

- QR-4: Öryggi og persónuvernd: geyma notenda- og kortagögn skv. stöðluðum öryggisstaðlum (dulkóðun í hvíld/flutningi, aðgangsstýringar).

- QR-5: Ef ytri þjónusta bilar; skýrar villuskýringar.

## Viðskiptareglur

- BR-1: Notendur mega aldrei sjá staðsetningu annarra notenda.

- BR-2: Forgangsröðun ákvarðana: Notendur og samstarfsaðilar „nr. 1“ þegar hagsmunir rekast á.

- BR-3: Mælingarregla: Ferðaskipulagstími mælist frá „Skipuleggja“ → „Kaupa miða“; óvirkni yfir X mín fellur út

- BR-4: Samstarfsval í V1: Helstu aðilar fyrir lykilferðamáta (Strætó, Hopp, Bolt, BSÍ).

- BR-5: Samþættingarform: Nota API; velja REST/GraphQL/SOAP eftir aðila; byggja sérsniðin integration ef þarf.

- BR-6: Markmiðsskilgreining: 75% ánægjuhlutfall er ásættanleg fyrir áframhald; undir því → endurskoðun/pivot.

- BR-7: Forgangsraða samstarf/integrationum (Klapp, Hopp, rútufyrirtæki o.s.frv.) fram yfir hraða og einfaldleika í V1.

- BR-8: Sýna virði fyrir samstarfsaðila (meiri kúnnar+sýnileiki) og fá jákvæða endurgjöf innan árs.

- BR-9: Byggja upp sterka vörumerkjaupplifun: fallegt, hraðvirkt og ávallt aðgengilegt app.

- BR-10: Persónuverndarstefna: Hugsa um öryggi frá hönnunarstigi; „privacy by design.“
