Baigiamojo darbo šablonas (LaTeX)
=================================

Šis baigiamųjų darbų šablonas yra sukurtas pagal VU MIF Kompiuterijos katedros 
2015 metų LaTeX šablono V1.0 stilių. Šis šablonas yra perdarytas nuo nulio,
siekiant išspręsti kai kurias problemas bei supaprastinti šablono naudojimą.
Šis šablonas tinkamas kursiniams, bakalauro ir magistro baigiamiesiems darbams,
tereikia pasirinkti tinkamas struktūrines dalis. Šis šablonas pritaikytas
lietuvių kalbai.

Pagrindinis failas: ``thesis.tex``

Norint paruošti aplinką Ubuntu sistemoje šakninėje šio projekto
direktorijoje pakanka įvykdyti ``make ubuntu``. Įvykdžius šią komandą bus
įdiegiami XeLaTeX, Biber bei Palemonas šriftas. 

Sukonstruoti PDF išeities failą galima šio projekto šakninėje direktorijoje
įvykdžius komandą ``make`` (tai galioja Linux distribucijoms).

Keitimų istorija
----------------
- 2015.04.29 (2.1) „Atviras kodas Lietuvai“
   * Šablonas pritaikytas VU MIF Kompiuterijos katedros antrojo stiliaus
     reikalavimams.
- 2015.02.08 (2.0) „Atviras kodas Lietuvai“
   * Pereita prie XeLaTeX, iš šablono pašalinti seni moduliai ir kodas.
   * Pereita prie BibLaTeX su Biber bibliografijos tvarkymui.
     Taip įdiegtas pilnas UTF-8 palaikymas.
   * Atnaujintas šablonas, kad atitiktų 2015 metų Kompiuterijos katedros
     reikalavimus.
- 2014.03.15 (1.3) Albertas Gimbutas ir Gražina Laurinavičiūtė
   * Pridėtas angliškas darbo pavadinimas tituliniame puslapyje.
   * Sukurtas naujas skyriaus tipas, kuris nėra numeruojamas ir nėra
     įtraukiamas į turinį (vumifsectionnonumnocontent).
   * Apibrėžtas ketvirto lygio skyrius
   * Sukurta galimybė nurodyti du autorius
   * Panaikintas dešiniosios paraštės "dantytumas"
- 2007.01.29 (1.2) Laurynas Biveinis
   * Atsisakyta fiksuotų darbo tipų, dabar jis nurodomas laisvai
     ir nėra privalomas.
   * Pridėta galimybė nurodyti recenzentą
   * Pataisyti klaidų pranešimai
   * Stilius licenzijuotas LPPL sąlygomis
- 2005.06.02 (1.1) Albertas Agejevas
   * Idėtas titulinis lapas matematinės informatikos katedrai
- 2005.05.20 (1.0)
   * Pataisytas literatūros sąrašo puslapio numeris turinyje
   * Skyriaus pabaigoje išvedame visus slankius objektus
