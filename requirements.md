# Kröfulisti

## Viðskiptakröfur

- BO-1: Sameina fjölbreytta ferðamáta (strætó, rútur, rafskútur, deilibílar, leigubílar, hjól, göngur, o.fl.) á einn stað.

  Lýsing: hækka notkun, auka tekjur (t.d. miðasala/samstarf), og styrkja sérstöðu vörunnar.

- BO-2: Minnka heildartíma frá „Skipuleggja ferð“ þar til miði er keyptur.

  Lýsing: Bæta ánægju notenda með hraðara ferli.

- BO-3: Auka notkun almenningssamgangna og umhverfisvænna ferðamáta.

  Lýsing: Styrkja stöðu vörunnar sem sjálfbærar lausnar, efla samstarf og mögulega fá stuðning/styrki tengda vistvænum markmiðum.

- BO-4: skalanleg hönnun: skalast í fleiri markaði/þjónustur (t.d. DK og ferjur/bátar) án arkitektúrbreytinga.

  Lýsing: Styttir „time-to-market“ á nýjum mörkuðum og lækkar tilheyrandi þróunarkostnað.

- BO-5: Hægt á að vera að mæla og sanna einföldun ferlis (tími, fjöldi skrefa, notendakannanir).

  Lýsing: Gera ákvarðanir gagnadrifnar, sanna virði lausnarinnar og forgangsraða fjárfestingum rétt, t.d. fyrir samstarfsaðila.

## Notendakröfur

- UR-1: Geta skipulagt ferð yfir marga ferðamáta með einni leit.

  Lýsing: notendur þurfa að setja inn eina fyrirspurn og fá samsettar leiðir yfir mismunandi ferðamáta.

- UR-2: Velja upphafs-/áfangastað og brottfarar/komutíma.

  Lýsing: notendur þurfa að geta skilgreint staði og tíma til að fá viðeigandi leiðir.

- UR-3: Skoða gagnvirkt kort með stoppistöðvum, þjónustusvæðum og aðgengi (strætó, Hopp o.fl.) með síum.

  Lýsing: Sjónrænir skipuleggjendur og almennir notendur þurfa að geta haft yfirsýn á korti og að geta síað valkosti.

- UR-4: Panta/kaupa miða (í appi eða með djúptengli) fyrir valda þjónustu.

  Lýsing: notendur þurfa að hafa einfalt og öruggt greiðslu-/pöntunarflæði.

- UR-5: Hraðleit – „search + enter“ ætti oft að nægja.

  Lýsing: Tímapressaðir notendur þurfa skjótan aðgang að bestu leið án margra skrefa.

- UR-6: Sjá leiðir raðaðar eftir tíma, kostnaði og umhverfisáhrifum (eða svipuðum mælikvörðum).

  Lýsing: Verð-, tíma- og vistvænnis-meðvituð notendur þurfa samanburð og röðun eftir forgangi.

- UR-7: Nota appið sem gestur (án aðgangs).

  Lýsing: Nýir eða friðhelgis-sinnaðir notendur þurfa að geta notað helstu virkni án skráningar.

- UR-8: Traust leiðaval á álagstímum (svipað og Google Maps upplifun).

  Lýsing: notendur þurfa áreiðanlegar tillögur þegar umferð/álag er mikið.

- UR-9: Veita einfaldlega endurgjöf í könnunum um upplifaða einföldun.

  Lýsing: notendur þurfa fljótlegt form til að gefa til kynna hvort ferlið hafi einfaldað sig.

## Virknikröfur (Functional)

- FR-1: Leiðareiknir sem styður fjölþættar samgöngur og álagstíma/rauntímagögn þar sem það er í boði.

  Lýsing: Reiknar, sameinar og metur leiðir milli punkta yfir ólíka ferðamáta með nýjustu tiltæku gögnum.

- FR-2: Samþætting við þjónustur, t.d. í gegnum API (Klapp, Strætó, Hopp, BSÍ, Bolt o.fl.); aðlögunarhæft fyrir hvern samstarfsaðila.

  Lýsing: Notar tengi (REST/GraphQL/SOAP o.fl.) og millilag til að tala við ólík kerfi.

- FR-3: Kortalög: stoppistöðvar, þjónustusvæði, tiltækni/biðtímar (þar sem við á); síur og togglar.

  Lýsing: Sýnir gagnvirk kortalög og veitir stjórn á birtingu valkosta.

- FR-4: Miðakaup/pöntun: innbyggt checkout eða örugg tenging við þjónustuaðila; styður gestagreiðslu þar sem mögulegt.

  Lýsing: Klárar kaupflæði innan apps með öruggri greiðslu.

- FR-5: Innbyggður tímamælingarhugbúnaður frá skipulagningu til kaupa; með sjálfvirkri óvirknigreiningu og útlagasíun.

  Lýsing: sama og nafn

- FR-6: Mæling á fjölda notendaskrefa í lykilflæði.

  Lýsing: Telur og skráir notendaskref til að meta einföldun.

- FR-7: Einkenni leiða: reikna og birta tíma, kostnað og áætluð umhverfisáhrif; raða eftir forgangi notanda.

  Lýsing: Býr til samanburðartöflu og raðar samkvæmt viðmiðum.

- FR-8: Virkni fyrir gestaaðgang með lágmörkuðum gagnaafnotum.

  Lýsing: Styður tímabundin session og geymir aðeins nauðsynleg gögn.

- FR-9: Notendaviðmót fyrir flýtileiðir: „Plana“, „Kort“, „Panta“, „Kaupa miða“ o.fl.

  Lýsing: Veitir skýra yfirsýn og hraðaðgang að helstu verkþáttum.

## Gæðakröfur (Non-functional)

- QR-1: Afköst: skjáopnanir og leitarsvörunartími (t.d. <1–2s fyrir algengar aðgerðir – nákvæm mörk skilgreind síðar).

  Lýsing: Lágur seinkunartími bætir upplifun og hækkar umbreytingar.

- QR-2: Aðgengi: uppfylla a.m.k. WCAG 2.2 AA.

  Lýsing: Tryggir nothæfi fyrir breiðan hóp og dregur úr lagalegri áhættu.

- QR-3: Áreiðanleiki/Framboð: „Liggur aldrei niðri“ → hár framboðsmarkmið (t.d. ≥99.9% á mánuði) og sjálfvirk vöktun.

  Lýsing: Viðheldur trausti og dregur úr tekjutapi vegna niðritíma.

- QR-4: Öryggi og persónuvernd: geyma notenda- og kortagögn skv. stöðluðum öryggisstaðlum (dulkóðun í hvíld/flutningi, aðgangsstýringar).

  Lýsing: Verndar gögn, uppfyllir reglur og styrkir vörumerki.

- QR-5: Ef ytri þjónusta bilar; skýrar villuskýringar.

  Lýsing: Seigla og gagnsæi draga úr pirringi og auka traust þegar eitthvað bilar.

## Viðskiptareglur

- BR-1: Notendur mega aldrei sjá staðsetningu annarra notenda.

  Lýsing: Persónuvernd og öryggi; eykur traust og einfaldar reglu-samræmi.

- BR-2: Forgangsröðun ákvarðana: Notendur og samstarfsaðilar „nr. 1“ þegar hagsmunir rekast á.

  Lýsing: Skýr ákvarðanarammi sem tryggir virðis-fókus og langtímasamstarf.

- BR-3: Mælingarregla: Ferðaskipulagstími mælist frá „Skipuleggja“ → „Kaupa miða“; óvirkni yfir X mín fellur út

  Lýsing: Tryggir samræmi og áreiðanleika í mælingum, kemur í veg fyrir skekkju.

- BR-4: Samstarfsval í V1: Helstu aðilar fyrir lykilferðamáta (Strætó, Hopp, Bolt, BSÍ).

  Lýsing: Fókus á áhrifamestu tengingarnar skilar fljótt mælanlegu virði.

- BR-5: Samþættingarform: Nota API; velja REST/GraphQL/SOAP eftir aðila; byggja sérsniðin integration ef þarf.

  Lýsing: Sveigjanleiki gagnvart hétrogenúm vistkerfi; meiri viðhaldskostnaður en hraðari innleiðing.

- BR-6: Markmiðsskilgreining: 75% ánægjuhlutfall er ásættanleg fyrir áframhald; undir því → endurskoðun/pivot.

  Lýsing: Skýr „go/no-go“ viðmið sem stýra fjárfestingum og forgangi.

- BR-7: Forgangsraða samstarf/integrationum (Klapp, Hopp, rútufyrirtæki o.s.frv.) fram yfir hraða og einfaldleika í V1.

  Lýsing: gæti seinkað afhendingu en eykur notagildi.

- BR-8: Sýna virði fyrir samstarfsaðila (meiri kúnnar+sýnileiki) og fá jákvæða endurgjöf innan árs.

  Lýsing: Tryggir endurnýjun/útvíkkun samstarfa og tekjur til lengri tíma.

- BR-9: Byggja upp sterka vörumerkjaupplifun: fallegt, hraðvirkt og ávallt aðgengilegt app.

  Lýsing: Mismunar á markaði, hækkar user retention.

- BR-10: Persónuverndarstefna: Hugsa um öryggi frá hönnunarstigi; „privacy by design.“

  Lýsing: Fyrirbyggir áhættu og einfaldar samræmi með öryggi innbyggðu í þróunarlífsferil.
