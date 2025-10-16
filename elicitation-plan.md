# Áætlun fyrir kröfugreiningarfund

## Markmið
- Lýsa helstu markmiðum kröfusöfnunar fyrir verkefnið sem á að greina
  - Tengja kröfur beint við **viðskiptamarkmið BO-1…BO-4**:
    - **BO-1 (tími → 3,5 mín / stretch 2 mín):** kortleggja skref „leita → bera saman → staðfesta“ og finna tímaþröskulda, biðpunkt og sjálfvirkan stuðning (forsendingar fyrir mælingum og tímabroti).
    - **BO-2 (einföldun):** greina hvaða þjónustur þarf að **sameina á einn stað** (leit, leiðaval, miðakaup, greiðslur, tilkynningar) og hvaða snertipunktar hverfa.
    - **BO-3 (20%→40%+ notkun almenningssamgangna):** skilja hvata/þröskulda sem breyta vali ferðamáta; skilgreina eiginleika sem ýta notendum í almenningssamgöngur (verð, tími, áreiðanleiki, CO₂, gamification).
    - **BO-4 (samstarf 5–8 fyrirtæki):** safna samþættingarkröfum (API, gagnaformat, SLA, lög/leyfi) og samningsbundnum viðskiptareglum.
  - Skilgreina **mælanleg NFR „quality scenarios“** sem styðja BO-1..BO-4 (t.d. 95% svör <2s).
  - Samþykkja 1–2 **lykil notkunartilvik** í „fully dressed“ sniði (Plan Trip, Purchase/Validate Ticket).

## Áætlaður staður og stund fyrir fundinn 
- **Öskja, stofa 131** (hvítborð + skjávarpi).  
- **16. október 2025** (samkvæmt dagskrá hér að neðan).

## Þátttakendur og hlutverk
- Facilitator: **Stefán Steinar Guðlaugsson** — stýrir umræðu, tímastýring, heldur fókus á kröfur og BO-tengingu.
- Ritari: **[Teymismeðlimur A]** — skráir spurningar/svör, ákvarðanir, „opnar spurningar“, sér um upptöku (með samþykki) og yfirfærslu í textaform.
- Viðskiptavinir/hagsmunaaðilar: **Product Owner (Straumur)** — forgangsraðar m.t.t. BO-1..BO-4; **Lykilnotandi** (daglegur notandi/þjónustuborð); **Tæknitengiliður** (samþættingar/API); *(ef við á)* **Reglu-/lagaðili** (samningar, leyfi, persónuvernd).

## Aðferð kröfusöfnunar
- Lýsið aðferð kröfusöfnunar, t.d. ef viðtal, þá spurningar (sjá námsefni)
- Haldinn verður kröfusöfnunarfundur við viðskiptavini.
- **Aðferð:** 45–60 mín. **vinnustofa** með **hálf-stöðluðu viðtali**, **use-case brainstorming** og **mini event-storming** (ferli, viðburðir, reglur). Lokasprettur: **MoSCoW** forgangsröðun m.t.t. BO-1..BO-4.

#### Spurningar
- **BO-1 (tími):** Hvaða skref telja í „skipulagstíma“? Hvar tapast mestur tími núna? Hvaða gögn þarf til sjálfvirkrar útfyllingar? Hvað er ásættanlegur svartími/ GPS uppfærslutíðni?
- **BO-2 (einföldun):** Hvaða þjónustur eiga að vera „á einum stað“ (leit, val, miðakaup, greiðsla, tilkynningar)? Hvaða snertipunktum má eyða? Hvað er „einfalt“ að mati notenda (2–3 mælanleg viðmið)?
- **BO-3 (hegðunarbreyting):** Hvaða eiginleikar myndu sannfæra um almenningssamgöngur (verðsamanburður, ETA+áreiðanleiki, loftslagsmerki, umbun)? Hvaða hindranir (öryggi, seink. óvissa)?
- **BO-4 (samstarf):** Hvaða fyrirtæki eru target 1. árs? Hvaða API/format/SLA hafa þau? Hver er lágmarks-samningsgagnapakki (taxtar, áætl., nýting, tilkynningar)?
- **NFR:** Afköst (95. persentíl < X s), áreiðanleiki (tiltæki X%), öryggi (aðgangsstýring, PCI ef greiðslur), aðgengi (WCAG 2.1), persónuvernd (gagna-minnkun).
- **Viðskiptareglur:** Verðlagning, endurgreiðslur, gögn í skýi/ESB, þjónustustig, villumeðhöndlun.
- **Gögn & samþættingar:** Lykileiningar (TripPlan, Leg, Provider, Fare, User), uppfærslutíðni, cache, offline-stuðningur.

## Líkön til að kveikja umræðu, skjöl og kerfi 
- Búðu til einföld drög (t.d. flæði ferla, notkunartilvik, grófar skjámyndir) til að kveikja umræðu. 
  - **Ferilflæði:** „Leit áfangastaðar → Samanburður → Val → Miðakaup → Staðfesting“ (+ undantekningar).
  - **Use-case yfirlit:** *Plan Trip*, *Compare Options*, *Purchase Ticket*, *Realtime Disruption Handling*.
  - **Wireframes (low-fi):** Leitar-skjár + Samanburðarlista + Checkout.
  - **Gagnakort:** TripPlan, Leg, ServiceProvider, Fare, Payment, User, Consent.
- Má t.d. vera mynd(ir) 
- Ef þú vilt skoða núverandi kerfi með viðskiptakerfi vertu búin að undirbúa það 
  - Demo-aðgangur, dæmi um API svör (JSON), skjáupptökuverkfæri, mælaborð fyrir tíma-mælingar.
- Stjórnandi: **setur módel á hvítborð, heldur fókus á BO-tengingu og tíma**
- Ritari: **fangar UC-skref, viðskiptareglur, NFR „quality scenarios“, tekur myndir af töflum**
- Viðskiptavinir/hagsmunaaðilar: **staðfesta ferli, forgangsraða m.t.t. BO-1…BO-4, benda á samþættingar**

## Dagskrá/Tímalína
Kröfusöfnunarfundur (Hópur 7 safnar frá 8): 16. október kl 13:30 🕜Kröfusöfnunarfundur (Hópur 8 safnar frá 7): 16. október kl 14:30 🕝
- 00:00–00:05 Kynning, fundarreglur, samþykki fyrir upptöku
- 00:05–00:10 Yfirlit yfir BO-1..BO-4 og umfang (in/out)
- 00:10–00:20 „Happy path“ Plan Trip (tímatöku-punkta merktir fyrir BO-1)
- 00:20–00:30 Sameining þjónusta (BO-2) + wireframe walkthrough
- 00:30–00:38 Samþættingar & viðskiptareglur (BO-4), API/SLA/leyfi
- 00:38–00:45 Hegðunarhvatar & mælir fyrir BO-3 (mælikvarðar, tilraunir)
- 00:45–00:52 NFR „quality scenarios“ (afköst, öryggi, aðgengi)
- 00:52–00:57 MoSCoW forgangsröðun útgáfu 1 (tengd BO)
- 00:57–01:00 Næstu skref, eigendur, skiladagar & opnar spurningar

## Áætlaðar afurðir sem koma út úr kröfusöfnuninni 
Safnið og flokkið kröfur þeirra í:

notendakröfur
- UC-listi (Plan Trip, Compare Options, Purchase Ticket, Realtime Alerts) + „happy path“ og 1–2 undantekningar/UC; tenging við BO-1..BO-4.

gæðaeiginleika (nonfunctional requirements)
- „Quality scenarios“ (t.d. **BO-1:** 95% leiða < 2s útreikningur; **BO-2:** ≤3 skref í miðakaupum; **BO-3:** A/B-tilraunir á hvötum; **BO-4:** 99.5% API-upptími fyrir samstarfsaðila).

viðskiptareglur
- Samnings- og rekstrureglur (taxtar, endurgreiðslur, heimildir, villumeðhöndlun, gagna-varðveisla, persónuvernd); mapping í ákvörðunartöflur.

o.fl. eins og við á.
- **Gögn & samþættingar:** Entity-listi, gagnalífsferill, API-samþættingar og SLA.
- **MoSCoW tafla** fyrir útgáfu 1 tengd BO-1..BO-4.
- **Fully dressed** notkunarlýsing fyrir lykil-UC (*Plan Trip* eða *Purchase Ticket*).
- **BO-traceability matrisa** (kröfur ↔ BO).

Hálf blaðsíða: Áætlun fyrir kröfusöfnun, punktalisti

## Áhætta sem getur hindrað kröfusöfnun 
- **Ákvarðanataka vantar (PO ekki til staðar)** → tryggja staðfestingarfund strax að loknum vinnustofu.
- **Skilgreining á „skipulagstíma“ (BO-1) óljós** → setja formlega skilgreiningu & mælingapunkta á fundi.
- **Survey-bias (BO-2)** → skilgreina spurningalista og grunnlínu áður; blinda hluta mats.
- **Aðgengi að samstarfsaðila-API (BO-4) tafist** → forgangslista „low-friction“ aðila, fallback gagnaveitur.
- **Hegðunarbreyting (BO-3) óviss** → setja A/B-tilraunaráætlun og forgangssetja hvata sem prófanlegir í útgáfu 1.
- **Persónuvernd/greiðsluöryggi** → DPIA/PCI-mat áður en greiðslur eru virkjaðar; lágmörkun gagna.
