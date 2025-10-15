# Áætlun fyrir kröfugreiningarfund

## Markmið
- Skilja viðskiptamarkmið kerfisins (hvers vegna verkefnið er til).
- Kortleggja lykilnotendur/aðila og markmið þeirra.
- Safna og flokka kröfum í:
  - **Notendakröfur (functional):** aðgerðir/hlutverk kerfisins, lykilferli og undantekningar.
  - **Gæðaeiginleika (nonfunctional):** afköst, öryggi, notagildi, áreiðanleiki, viðhald, samvirkni o.fl.
  - **Viðskiptareglur/þvinganir:** reglur, lög, stefna, reiknireglur, heimildir.
  - **Gögn & samþættingar:** aðalgagnatög, líftími, ytri kerfi/biðlaraþjónar.
- Stiga og raðgreina (MoSCoW) fyrstu útgáfu.
- Samþykkja **lykilnotkunartilvik** sem verður skrifað í „fully dressed“ notkunarlýsingu eftir fund.

## Áætlaður staður og stund fyrir fundinn
- **Kl. 14:30, 16/10/2025**, **Öskju — stofa 131**.

## Þátttakendur og hlutverk
- **Facilitator:** *Stefán Steinar Guðlaugsson* — stýrir umræðu, heldur utan um tíma og ramma.
- **Ritari:** *[Teymismeðlimur A]* — skráir helstu atriði, ákvarðanir, opnar spurningar (og sér um upptöku ef samþykki fæst).
- **Viðskiptavinir/hagsmunaaðilar (hitt teymi):**
  - **Product Owner:** markmið, forgangsröðun, samþykki.
  - **Lykilnotandi/þjónustuaðili:** lýsir raunverulegum verkferlum/verkefnum.
  - **Tæknitengiliður:** staðfestir samþættingar og tæknileg mörk.
  - **Reglu-/lagaðili (ef við á):** staðfestir viðskiptareglur/skyldur.

## Aðferð kröfusöfnunar
- **Vinnustofa (45–60 mín)** með **hálf-stöðluðu viðtali**, **use-case brainstorming** og **mini-event storming** á hvítborði.
- **Spurningar (dæmi):**
  - *Viðskiptamarkmið:* „Hvað breytist ef kerfið tekst? Hver er árangursmæling?“
  - *Aðilar/hlutverk:* „Hverjir nota kerfið? Hver er helsti hvati hvers aðila?“
  - *Ferli:* „Gakktu í gegnum ‘happy path’. Hvað gerist ef [X] bregst?“
  - *Gögn:* „Hvaða lykilgögn þarf? Hver býr þau til? Hver má breyta?“
  - *Gæðaeiginleikar:* „Hversu hratt? Hversu öruggt? Hvað þýðir góð notkunarupplifun hér?“
  - *Viðskiptareglur:* „Hvaða reglur mega aldrei rofna? Undir hvaða skilyrðum?“
  - *Samþættingar:* „Hvaða ytri kerfi? Vinnsluflæði milli kerfa?“
  - *Takmarkanir/áhætta:* „Hvað gæti tafið eða torveldað innleiðingu?“
- **Forgangsröðun:** MoSCoW (Must/Should/Could/Won’t for now) fyrir útgáfu 1.

## Líkön til að kveikja umræðu, skjöl og kerfi
- **Notendakort** (actors ↔ markmið).
- **Hátt-í-lofti ferilflæði** (context + helstu skref „happy path“ og 2–3 undantekningar).
- **Notkunartilvikayfirlit** (2–5 UC titlar til að hrinda af stað umræðu).
- **Grófar skjámyndir (low-fi wireframes)** af 1–2 lykilskjám (t.d. „Búa til beiðni“, „Yfirlit“).
- **Gagnakort** (lykileiningar: {Entity, eiginleikar, tengsl}).
- **Undirbúningur:** Facilitator kemur með eyðublöð fyrir UC, NFR quality-scenario snið, MoSCoW-töflu.
- **Hlutverk m.t.t. líkanna:**
  - **Stjórnandi:** sýnir módel, heldur flæði (tímatök).
  - **Ritari:** fangar UC-titla, skref, viðskiptareglur, NFR-setningar.
  - **Viðskiptavinir/hagsmunaaðilar:** staðfesta raunsæi, fylla í eyður, merkja forgang.

## Dagskrá/Tímalína (60 mín)
- **00:00–00:05** Kynning, markmið, vinnureglur (tímastýring, opnar spurningar skráðar).
- **00:05–00:10** Viðskiptamarkmið & umfang (hvað inn/út, árangursviðmið).
- **00:10–00:20** Aðilar & „happy path“ (teikna ferli, staðfesta skref).
- **00:20–00:30** Notkunartilvik (brainstorm → velja 1–2 lykil UC fyrir útgáfu 1).
- **00:30–00:40** Undantekningar/viðskiptareglur, gögn, samþættingar.
- **00:40–00:50** Gæðaeiginleikar (NFR) sem „quality scenarios“ (mælanlegt form).
- **00:50–00:55** Forgangsröðun (MoSCoW), staðfesting á umfangsgrunni.
- **00:55–01:00** Næstu skref, eigendur verkþátta, afhending gagna.

## Áætlaðar afurðir sem koma út úr kröfusöfnuninni
- **Flokkaður punktalisti krafna:**
  - **Notendakröfur:** [UC-titlar + stutt lýsing], helstu skref/viðmót.
  - **Gæðaeiginleikar:** afkastakröfur (t.d. 95% færslna < 2s), öryggi (aðgangsstýring, audit), áreiðanleiki (SLA), notagildi (NPS/Task success), viðhald (skráning), samvirkni (API).
  - **Viðskiptareglur:** ákvörðunarreglur, réttindastýring, lög/staðlar.
  - **Gögn/samþættingar:** lykileiningar, eigendur gagna, ytri API tengingar.
- **Fully dressed notkunarlýsing** fyrir **1 lykilnotendakröfu** (Actor, Trigger, Preconditions, Main Flow, Alternate/Exception Flows, Postconditions, Business Rules, NFR).
- **MoSCoW tafla** fyrir útgáfu 1.
- **Opnar spurningar/ályktanir** með eigendum og skiladögum.

## Áhætta sem getur hindrað kröfusöfnun
- **Án ákvarðanatökuvalds** mætir enginn → óljós forgangsröðun.  
  - *Mótvægisaðgerð:* tryggja PO á staðnum; annars fjarfundarsamþykki í lok fundar.
- **Scope-creep/lausna-hoppar** (rífast í UI/arkitektúr of snemma).  
  - *Mótvægisaðgerð:* halda sig við „vandamál → ferli → kröfur“; skrá „bíður“.
- **Óskýr hugtök/gagnamerkingar.**  
  - *Mótvægisaðgerð:* setja **orðalista/glossary** á staðnum.
- **Tími rennur út.**  
  - *Mótvægisaðgerð:* tímahákar, stoppa djúp-köfur → setja sem „opnar spurningar“.
- **Ófullnægjandi umboð frá reglu-/öryggishliðum.**  
  - *Mótvægisaðgerð:* bóka eftirfylgni með regluaðila, staðfesta viðkvæm atriði skriflega.
- **Engin upptaka/ófull gögn.**  
  - *Mótvægisaðgerð:* fá samþykki fyrir upptöku; annars tvöföld ritaraskrá + myndir af töflum.
