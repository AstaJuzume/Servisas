# Autoserviso darbų ir užimtumo prototipas

Interaktyvi demonstracinė aplikacija kelių autoservisų vadovui ir mechanikams. Vadovas gali pasirinkti visus servisus arba vieną padalinį ir matyti jo aktyvius darbus, užregistruotą laiką bei komandos užimtumą. Kiekvienas darbas ir darbuotojas priklauso konkrečiam servisui. Darbuotojas gali pradėti, pristabdyti, tęsti bei užbaigti jam priskirtą darbą.

## Įkėlimas į GitHub Pages

1. Sukurkite naują GitHub saugyklą, pavyzdžiui, `autoserviso-prototipas`.
2. Įkelkite **šio aplanko** `index.html` ir `README.md` į saugyklos pagrindinį katalogą (šaknį). Galite išskleisti ZIP ir įkelti abu failus arba naudoti **Add file → Upload files**.
3. GitHub saugykloje atverkite **Settings → Pages**. Skiltyje **Build and deployment** pasirinkite **Deploy from a branch**, šaką **main**, aplanką **/(root)** ir išsaugokite.
4. Kai GitHub baigs publikavimą, puslapio adresą rasite tame pačiame **Pages** lange. Paprastai jis bus `https://NAUDOTOJAS.github.io/autoserviso-prototipas/`.

Nereikia diegti paketų ar vykdyti build komandos. `index.html` yra visas prototipas.

## Demonstracinės versijos ribos

- Pradiniai automobiliai, klientai ir darbuotojai yra pavyzdiniai duomenys.
- Demonstracijoje yra du pavyzdiniai servisai. Naują darbą galima priskirti tik pasirinkto serviso darbuotojui.
- Nauji darbai ir būsenų pakeitimai saugomi tik atidarytos naršyklės `localStorage`. Skirtingi įrenginiai duomenimis nesidalija.
- Atidarius puslapį privačiame lange ar išvalius naršyklės svetainės duomenis, pakeitimai dings.
- GitHub Pages viešoje saugykloje prototipo kodas ir pavyzdiniai duomenys yra matomi kitiems. Nenaudokite tikrų klientų duomenų.

Tai demonstracinis prototipas, skirtas aptarti ekranus ir darbo eigą. Realiai keliems darbuotojams vienu metu naudoti reikėtų bendros duomenų bazės, prisijungimo ir teisių valdymo.
