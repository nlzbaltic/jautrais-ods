# Atslēgvārdu izpēte: kafejnīca Jautrais Ods (Smiltene)

Datums: 2026. gada oktobris.

**Avoti:**

- Google meklēšanas automātiskie ieteikumi (autocomplete), latviešu valodā, Latvijas reģionā;
- Smiltenes novada tūrisma ceļvedis 2025 (visit.smiltene.lv).

**Svarīgi:** autocomplete parāda, ko cilvēki reāli meklē, bet nesniedz meklējumu apjomu. Pirms prioritāšu galīgas noteikšanas apjomus ieteicams pārbaudīt:

- Google Ads → Keyword Planner;
- pēc palaišanas Google Search Console (Performance → Queries).

## 1. Klasteri un meklēšanas nolūks

| Klasteris | Atslēgvārdi | Nolūks | Prioritāte |
|---|---|---|---|
| **A. Ēšana Smiltenē** | kafejnīca smiltenē, restorāns smiltenē, kur paēst smiltenē, kur var paēst smiltenē, kur garšīgi paēst smiltenē, pusdienas smiltenē, ēdināšana smiltenē | Transakcionāls / lokāls | Augstākā |
| **B. Ēšana ceļā / Vidzemē** | kur paēst vidzemē, kafejnīcas vidzemē, vidzemes šoseja a2, kafejnīca pie šosejas, elektroauto uzlāde | Lokāls / ceļotāji | Augsta |
| **C. Ko apskatīt** | smiltene ko apskatīt, ko apskatīt smiltenes novadā, ko darīt smiltenē, smiltenes muižas komplekss, smiltenes pilsdrupas, kalnamuiža, gaujienas pils/muiža | Informatīvs | Vidēja (blogs) |
| **D. Ģimenes** | ko darīt smiltenē ar bērniem, smiltene bērniem, ko apskatīt vidzemē ar bērniem, ko darīt vidzemē ar bērniem | Informatīvs | Vidēja (blogs) |
| **E. Daba** | smiltenes takas, dabas takas smiltenes novadā, pastaigu takas smiltenes novadā, ezers smiltenes novadā, tepera ezers | Informatīvs | Vidēja (blogs) |
| **F. Aktīvā atpūta** | aktivitātes smiltenē, teperis (kartingi, autotrase, pasākumi), slēpošana smiltenē, smiltene velo, abuls (disku golfs, sidrs) | Informatīvs / komerciāls | Vidēja (blogs) |
| **G. Pasākumi** | smiltene pasākumi 2026, smiltenes pilsētas svētki 2026, apes robežtirgus, apes pilsētas svētki 2026 | Informatīvs, sezonāls | Zema (mainīgi datumi) |
| **H. Virtuve** | latviešu virtuve, karbonāde, kur paēst ar suni | Informatīvs | Zema |

## 2. Atslēgvārdu sadalījums pa lapām

| Lapa | Galvenais atslēgvārds | Papildu atslēgvārdi | SEO title |
|---|---|---|---|
| Sākumlapa | kafejnīca smiltenē | restorāns smiltenē, kafejnīca smiltenes novadā, pusdienas | Kafejnīca Smiltenē – Jautrais Ods |
| Ēdienkarte | ēdienkarte / pusdienas smiltenē | latviešu virtuve, karbonāde, zupas | Ēdienkarte – kafejnīca Jautrais Ods Smiltenē |
| Par mums | restorāns smiltenē | kamīnzāle, terase, dārzs | Par mums – Jautrais Ods pie Smiltenes |
| Kontakti | kafejnīca pie vidzemes šosejas | darba laiks, kā nokļūt, Launkalnes pagasts | Kontakti un darba laiks – Jautrais Ods |
| Blogs 01 | kur paēst smiltenē | kur garšīgi paēst, ēdināšana smiltenē | Kur paēst Smiltenē – kafejnīcas un pusdienas |
| Blogs 02 | ko apskatīt smiltenē | smiltenes pilsdrupas, kalnamuiža, tepera ezers | Ko apskatīt Smiltenē un Smiltenes novadā |
| Blogs 03 | ko darīt smiltenē ar bērniem | smiltene bērniem, vidzemē ar bērniem | Ko darīt Smiltenē ar bērniem |
| Blogs 04 | dabas takas smiltenes novadā | smiltenes takas, ezers smiltenes novadā | Dabas takas Smiltenes novadā |
| Blogs 05 | vidzemes šoseja a2 | kur paēst vidzemē, kafejnīcas vidzemē, EV uzlāde | Vidzemes šoseja A2 – kur paēst ceļā |
| Blogs 06 | aktivitātes smiltenē | teperis, slēpošana smiltenē, smiltene velo | Aktivitātes Smiltenē visos gadalaikos |

Katrs blogs iekšēji saista uz ēdienkarti, kontaktiem un 1–2 citiem rakstiem. Tā veidojas tēmu klasteris ap "Smiltene + ēšana/atpūta".

## 3. Ieteikumi

1. **Google Business Profile** ir svarīgākais lokālajam SEO ("kafejnīca smiltenē" rezultātos dominē kartes bloks):
   - kategorija "Kafejnīca", papildu kategorija "Restorāns";
   - aktuāls darba laiks, arī svētku dienās;
   - ēdienkartes saite uz /edienkarte;
   - regulāri jauni foto un ieraksti (Posts);
   - atbildes uz atsauksmēm.
2. **NAP konsekvence:** nosaukums, adrese (Launkalnes pagasts, Smiltenes novads) un tālrunis +371 64772610 visur vienādi: mājaslapā, Google, Facebook, 1188.lv, visitsmiltene.lv.
3. **Strukturētie dati:**
   - `Restaurant` / `CafeOrCoffeeShop` ar `openingHoursSpecification`, `geo`, `hasMenu`, `servesCuisine`;
   - `BlogPosting` katram rakstam;
   - `FAQPage` raksta BUJ sadaļām.
4. **Next.js + Sanity:**
   - katram rakstam atsevišķs URL `/blogs/<slug>`;
   - `title` un `description` no Sanity laukiem `seo_title` un `description`;
   - sitemap.xml ar visiem rakstiem;
   - Open Graph bildes.
5. **Saites no ārpuses:** lūgt Smiltenes TIC (visitsmiltene.lv) pievienot saiti uz mājaslapu sadaļā "Garšo".
6. **Sezonāls saturs:** pirms vasaras un ziemas atjaunot rakstus 04 un 06. Pasākumu rakstiem izmantot tikai oficiālus datumus no smiltenesnovads.lv.
7. **Nākamie raksti (idejas):**
   - Latviešu virtuves klasika: karbonāde, frikadeļu zupa;
   - Elektroauto uzlāde Vidzemē;
   - Gaujiena un Ziemeļgauja vienā dienā;
   - Svinības un grupu pusdienas pie Smiltenes (ja piedāvājat).
