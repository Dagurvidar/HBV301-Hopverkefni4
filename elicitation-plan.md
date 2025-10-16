# Áætlun fyrir kröfugreiningarfund

## Markmið
- Lýsa helstu markmiðum kröfusöfnunar fyrir verkefnið sem á að greina
- Skilgreina umfang (in/out) og árangursviðmið verkefnisins
- Kortleggja lykilnotendur/hlutverk og markmið þeirra (actors & goals)
- Safna og flokka kröfur: notendakröfur, gæðaeiginleikar, viðskiptareglur, gögn/samþættingar
- Staðfesta 1–2 lykil notkunartilvik (use cases) fyrir „fully dressed“ lýsingu
- Forgangsröðun (MoSCoW) fyrir útgáfu 1 og skrá opnar spurningar

## Áætlaður staður og stund fyrir fundinn 
- **Staður:** Öskja, stofa 131 (hvítborð + skjávarpi)
- **Stund:** 16. október 2025  
  - Hópur 7 safnar frá 8: **13:30–14:15**  
  - Hópur 8 safnar frá 7: **14:30–15:15**

## Þátttakendur og hlutverk
- Facilitator: **Stefán Steinar Guðlaugsson** — stýrir umræðu, heldur utan um tíma, tryggir að fókus haldist á kröfur (ekki lausnahönnun)
- Ritari: **[Teymismeðlimur A]** — skráir spurningar/svör, ákvarðanir, opnar spurningar; sér um upptöku ef samþykki fæst og yfirfærslu í textaform
- Viðskiptavinir/hagsmunaaðilar: **Product Owner**, **Lykilnotandi/þjónustuaðili**, **Tæknitengiliður**, *(ef við á)* **Reglu-/lagaðili** — svara spurningum, staðfesta ferla og reglur, forgangsraða

## Aðferð kröfusöfnunar
- Lýsið aðferð kröfusöfnunar, t.d. ef viðtal, þá spurningar (sjá námsefni)
- Haldinn verður kröfusöfnunarfundur við viðskiptavini.
- Aðferð: 45 mín. **vinnustofa** með **hálf-stöðluðu viðtali**, **use-case brainstorming** og **mini event-storming** á hvítborði. Lokasprettur: **MoSCoW** forgangsröðun.

#### Spurningar
- Viðskiptamarkmið: *Hvað breytist ef kerfið tekst? Hvernig mælum við árangur?*
- Notendur/hlutverk: *Hverjir nota? Hver er hvati/þörf hvers aðila?*
- Ferli („happy path“): *Gakktu í gegnum dæmigerða aðgerð frá upphafi til enda.*
- Undantekningar: *Hvað gerist ef skref X mistekst? Hver bregst við og hvernig?*
- Gögn: *Hvaða lykilgögn þarf? Uppruni, eigandi, líftími, persónugögn?*
- Gæðaeiginleikar: *Afköst, öryggi, notagildi, áreiðanleiki, aðgengi — mælanleg viðmið?*
- Viðskiptareglur: *Hvaða reglur mega aldrei rofna? Stefnur/lög/heimildir?*
- Samþættingar: *Hvaða ytri kerfi/APIs? Tíðni, stefna, villumeðhöndlun?*
- Takmarkanir/áhætta: *Hvað gæti tafið? Hver þarf að samþykkja hvað?*

## Líkön til að kveikja umræðu, skjöl og kerfi 
- Búðu til einföld drög (t.d. flæði ferla, notkunartilvik, grófar skjámyndir) til að kveikja umræðu. 
  - Notendakort (actors ↔ markmið)
  - Ferilflæði („happy path“ + 2–3 undantekningar) á hvítborði
  - Notkunartilvikayfirlit (2–5 UC titlar) og grófar skjámyndir (low-fi) af lykilskjám
  - Gagnakort (lykileiningar og tengsl)
- Má t.d. vera mynd(ir) 
- Ef þú vilt skoða núverandi kerfi með viðskiptakerfi vertu búin að undirbúa það 
  - Aðganga/lykill, demo-senaríó og skjáupptökuverkfæri tilbúið
- Stjórnandi: **kynnir líkön, heldur flæði, stýrir tímasetningum**
- Ritari: **fangar UC skref, viðskiptareglur, NFR „quality scenarios“, tekur myndir af töflum**
- Viðskiptavinir/hagsmunaaðilar: **staðfesta raunsæi ferla, bæta inn undantekningum og forgangi**

## Dagskrá/Tímalína
Kröfusöfnunarfundur (Hópur 7 safnar frá 8): 16. október kl 13:30 🕜Kröfusöfnunarfundur (Hópur 8 safnar frá 7): 16. október kl 14:30 🕝
- 00:00–00:05 Kynning, markmið og rammafundar (vinnureglur, upptaka, orðalisti)
- 00:05–00:10 Viðskiptamarkmið & umfang (in/out, árangursviðmið)
- 00:10–00:20 „Happy path“ yfir lykilferli + staðfesting aðila
- 00:20–00:30 Notkunartilvik: brainstorm → velja 1–2 lykil UC (útgáfa 1)
- 00:30–00:40 Undantekningar, viðskiptareglur, gögn og samþættingar
- 00:40–00:45 Gæðaeiginleikar sem „quality scenarios“ (mælanleg atriði)
- 00:45–00:50 Forgangsröðun (MoSCoW) og samþykkt næstu skref
- 00:50–00:55 Yfirlit yfir opnar spurningar, eigendur og skiladagsetningar

## Áætlaðar afurðir sem koma út úr kröfusöfnuninni 
Safnið og flokkið kröfur þeirra í:

notendakröfur
- Yfirlit yfir notkunartilvik (UC titlar + stutt lýsing), „happy path“ skref og 1–2 undantekningar

gæðaeiginleika (nonfunctional requirements)
- Mælanleg „quality scenarios“ (t.d. 95% beiðna < 2s; aðgangsstýring; SLA; aðgengi)

viðskiptareglur
- Reglur/heimildir/reiknireglur sem verða bundnar í kerfið (ákvarðanatré/tafla ef við á)

o.fl. eins og við á.
- Gögn & samþættingar (lykileiningar, eigendur, API tengingar)
- MoSCoW forgangsröðun fyrir útgáfu 1
- **Fully dressed** notkunarlýsing fyrir 1 lykil UC (Actor, Trigger, Preconditions, Main/Alternate Flows, Postconditions, Business Rules, NFR)
- Opnar spurningar með eigendum og næstu skrefum

Hálf blaðsíða: Áætlun fyrir kröfusöfnun, punktalisti

## Áhætta sem getur hindrað kröfusöfnun 
- Ófullnægjandi þátttaka (PO/ákvarðanataki mætir ekki) → *tryggja staðfestingu í lok fundar/fjarfundar*
- Scope-creep og lausnahopp (of snemmbúin UI/arkitektúr umræða) → *parkera í „bíður“ lista*
- Óskýr hugtök/gagnamerking → *setja upp lifandi orðalista (glossary) á staðnum*
- Tímahalli → *tímahákar á hverju dagskráratriði; skrá ósvarað sem opnar spurningar*
- Persónuvernd/öryggi óskýrt → *bóka sérfund með reglu-/öryggisaðila, skjalfesta ákvæði*
- Engin upptaka/óljósar glósur → *samþykki fyrir upptöku; annars tvöföld skráning + myndir af hvítborði*
