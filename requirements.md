# Kröfulisti

## Viðskiptakröfur

- BR-1: Sameina fjölbreytta ferðamáta (strætó, rútur, rafskútur, deilibílar, leigubílar, hjól, göngur, o.fl.) á einn stað.

- BR-2: Minnka heildartíma frá „Skipuleggja ferð“ þar til miði er keyptur.

- BR-3: Stuðningur við gestaaðgang (án innskráningar) í fyrstu útgáfu.

- BR-4: Forgangsraða samstarfi/integrationum (Klapp, Hopp, rútufyrirtæki o.s.frv.) fram yfir hraða og einfaldleika í V1.

- BR-5: Auka notkun almenningssamgangna og umhverfisvænna ferðamáta.

- BR-6: Sýna virði fyrir samstarfsaðila (meiri kúnnar/sýnileiki) og fá jákvæða endurgjöf innan árs.

- BR-7: Hafa lausn sem skalar í ný lönd (t.d. DK) og fleiri samgöngur (ferjur/bátar).

- BR-8: Byggja upp sterka vörumerkjaupplifun: fallegt, hraðvirkt og ávallt aðgengilegt app.

- BR-9: Taka gagnadrifnar ákvarðanir um áframhald (t.d. 5–10% aukning í notkun er ásættanleg en kallar á endurskoðun).

- BR-10: Mæla og sanna einföldun ferlis (tími, fjöldi skrefa, notendakannanir).

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

- FR-1: Leiðareiknir sem styður fjölþættar samgöngur og álagstíma/rauntímagögn þar sem í boði.

- FR-2: Samþætting við þjónustur í gegnum API (Klapp, Strætó, Hopp, BSÍ, Bolt o.fl.); aðlögunarlag fyrir hvern samstarfsaðila.

- FR-3: Kortalög: stoppistöðvar, þjónustusvæði, tiltækni/biðtímar (þar sem við á); síur og togglar.

- FR-4: Miðakaup/pöntun: innbyggt checkout eða örugg djúptenging yfir í þjónustuaðila; styður gestagreiðslu þar sem mögulegt.

- FR-5: Innbyggður „skeiðklukku“-mælingarferill frá skipulagningu til kaupa; með sjálfvirkri óvirknigreiningu og útlagasíun.

- FR-6: Mæling á fjölda notendaskrefa í lykilflæði.

- FR-7: Einkenni leiða: reikna og birta tíma, kostnað og áætluð umhverfisáhrif; raða eftir forgangi notanda.

- FR-8: Gestasession (án reiknings) með lágmörkuðum gagnaafnotum.

- FR-9: Könnunar-/NPS-eining til að safna mati á einföldun.

- FR-10: Villa-/niðutíma-meðhöndlun: sýna varaleiðir ef API samstarfsaðila bregst.

- FR-11: Stillingar fyrir land/markað (t.d. DK) og viðbót ferðamáta (t.d. ferjur).

- FR-12: Yfirborð (UI) fyrir flýtileiðir: „Plana“, „Kort“, „Panta“, „Kaupa miða“ o.fl.

## Gæðakröfur (Non-functional)

- QR-1: Afköst: skjáopnanir og leit svara hratt (t.d. <1–2s fyrir algengar aðgerðir – nákvæm mörk skilgreind síðar).

- QR-2: Aðgengi: uppfylla a.m.k. WCAG 2.2 AA.

- QR-3: Áreiðanleiki/Framboð: „Liggur aldrei niðri“ → hár framboðsmarkmið (t.d. ≥99.9% á mánuði) og sjálfvirk vöktun.

- QR-4: Öryggi og persónuvernd: geyma notenda- og kortagögn skv. stöðluðum öryggisstaðlum (dulkóðun í hvíld/flutningi, aðgangsstýringar).

- QR-5: Persónuvernd: ekki birta staðsetningu annarra notenda; „privacy by design“.

- QR-6: Stigvaxandi hönnun: skalast í fleiri markaði/þjónustur án arkitektúrbreytinga.

- QR-7: Seigla: graceful degradation ef ytri þjónusta bilar; skýrar villuskýringar.

- QR-8: Lókal-væðing: fjöltyngt UI (a.m.k. is/en; markaðstengt).

- QR-9: Laga-/reglu-samræmi: GDPR/EEA samræmi og geymsluþol gagna skilgreint.

- QR-10: Vistspor: gera umhverfisáhrif gagnsæ og endurtakanleg (kvarðar/aðferðafræði skjalfest).

## Viðskiptareglur

- BRULE-1: Notendur mega aldrei sjá staðsetningu annarra notenda.

- BRULE-2: Forgangsröðun ákvarðana: Notendur og samstarfsaðilar „nr. 1“ þegar hagsmunir rekast á.

- BRULE-3: Mælingarregla: Ferðaskipulagstími mælist frá „Skipuleggja“ → „Kaupa miða“; óvirkni yfir X mín fellur út (útlagasía).

- BRULE-4: Samstarfsval í V1: Helstu aðilar fyrir lykilferðamáta (Strætó, Hopp, Bolt, BSÍ).

- BRULE-5: Samþættingarform: Nota API; velja REST/GraphQL/SOAP eftir aðila; byggja sérsniðin integration ef þarf.

- BRULE-6: Markmiðsskilgreining: 10% aukning í notkun er ásættanleg fyrir áframhald; undir því → endurskoðun/pivot.

- BRULE-7: Stefna um sveigjanleika: Breyta stefnu ef meirihluti notenda vill annað og það „meikar sense“.
