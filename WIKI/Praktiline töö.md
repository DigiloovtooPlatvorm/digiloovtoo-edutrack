# Hetkeolukorra kaardistus
Olemasolevad rakendused katavad üksikuid funktsioone (nt planeerimine või märkmete tegemine), kuid puudub lihtne ja õpilasele suunatud lahendus, mis koondaks automaatselt kooliinfo, ajaplaneerimise ja õppimise ühte keskkonda.
| Arendusnõue | MyStudyLife | Notion |
|---|---|---|
| 1. Automaatne andmete sünk (Stuudium) | ❌ puudub |❌ puudub |
| 2. Kodutööde haldamine (kanban) | ❌ puudub | ✔️ olemas |
| 3. Ühtne ülevaade (dashboard) | ✔️ olemas |  ✔️ olemas |
| 4. Kalender ja tunniplaan | ✔️ olemas | ✔️ olemas (seadistatav) |
| 5. Meeldetuletused | ✔️ olemas | ✔️ olemas |
| 6. Õppimise toetamine (flashcardid, testid) | ❌ puudub | ✔️ võimalik (ise luues) |
| 7. Lihtne ja kiire kasutus | ✔️ väga lihtne | ⚠️ pigem keeruline |
| 8. Kõik ühes kohas | ⚠️ osaliselt | ✔️ olemas |


# Arendusnõuded
1. Andmete automaatne sünkroniseerimine
- Äpp peab tooma automaatselt andmed Stuudiumist
- Kuvatakse kodutööd, tähtajad ja õpetajate lisatud info
- Kasutaja ei pea andmeid käsitsi sisestama
2. Kodutööde haldamine (Kanban vaade). Kodutööd peavad olema jaotatud kategooriatesse:
    - alustamata
    - pooleli
    - tehtud
- Kasutaja saab ülesandeid liigutada ühest staatusest teise, sh. kuvatakse iga ülesande tähtaeg
3. Ühtne ülevaade (dashboard)
- Avalehel kuvatakse:
    - lähenevad tähtajad
    - kõige olulisemad ülesanded
- Kasutaja saab kiiresti aru, mida peab tegema
4. Kalender ja tunniplaan
- Äpp kuvab tunniplaani
- Kalender koondab:
        - kodutööd
        - tunnid
        - huviringid ja muud sündmused
5. Meeldetuletused
- Äpp saadab teavitusi lähenevate tähtaegade kohta
- Kasutaja saab seadistada meeldetuletuste aega
- Eesmärk: vältida viimase hetke avastamist
6. Õppimise toetamine
- Kasutaja saab luua õppimiseks digitaalseid flashcarde, valikvastustega küsimustikke
- Sedeleid saab läbi vaadata ja korrata
- Toetab kontrolltöödeks valmistumist
7. Lihtne ja kiire kasutus
- Äpp peab olema lihtne ja intuitiivne
- Oluline info peab olema kiiresti leitav
- Sobib igapäevaseks kasutamiseks ilma lisapingutuseta
8. Info koondamine ühte kohta
- Kõik õppimisega seotud info on ühes keskkonnas:
        - kodutööd, tähtajad
        - tunniplaan, kalender
        - ise koostatud õppematerjalid

# Lo-Fi protüüp paberil
pilt 1 ja pilt 2

## Kasutajatelt küsitud tagasiside
Kasutajateks olid 7.–9. klassi õpilased.
Üldised küsimused:
- Kas äpp tundub sulle arusaadav ja lihtne kasutada? Miks?
- Mis sulle äpi juures kõige rohkem meeldib?
- Mis jäi segaseks või arusaamatuks?
Funktsioonide kohta:
- Kas kodutööde list ja kanban-vaade on sinu jaoks loogilised?
- Kas kalendri vaade (tunniplaan + sündmused) on kasulik?
- Kas automaatne info toomine Stuudiumist oleks sinu jaoks vajalik?
Õppimise kohta:
- Kas kasutaksid äpis olevat flashcardide (sedeleid) funktsiooni?
- Mis aitaks sul paremini õppida või meelde jätta?
Parendusettepanekud:
- Mis funktsioon võiks veel äpis olla?
- Mis tuleks kindlasti muuta või paremaks teha?

## Kasutajate tagasiside kokkuvõte (Lo-FI prototüübile)
Tagasiside põhjal leiti, et äpp on üldiselt arusaadav ja loogilise ülesehitusega. Õpilastele meeldis eriti see, et kogu vajalik info on koondatud ühte kohta ning ei pea kasutama mitut erinevat keskkonda.
Kõige olulisemaks peeti automaatset andmete sünkroniseerimist Stuudiumiga. Õpilased tõid välja, et nad ei soovi ise kodutöid käsitsi sisestada ning just see funktsioon muudaks äpi nende jaoks päriselt kasulikuks.
Kodutööde kanban-vaade sai positiivset tagasisidet, kuna see aitab visuaalselt näha, millised ülesanded on tegemata, pooleli või valmis. Samas mõned õpilased eelistasid lihtsat nimekirja vaadet, mistõttu peeti oluliseks, et äpis oleks võimalik valida erinevate vaadete vahel.
Kalendri vaadet hinnati kasulikuks, eriti see, et sinna on koondatud nii tunniplaan kui ka muud sündmused (nt trennid ja huviringid). See aitab paremini oma päeva planeerida.
Õppimise funktsioonide osas arvati, et flashcardide loomine on kasulik, kuid see peab olema väga lihtne ja kiire, vastasel juhul ei kasutata seda. Mõned õpilased pakkusid, et äpp võiks pakkuda ka automaatseid küsimusi või teste.
Peamiste parendusettepanekutena toodi välja:
- äpp peab olema võimalikult lihtne ja kiire kasutada
- oluline info peab olema kohe nähtav (nt avalehel)
- võiks olla võimalus valida erinevaid vaateid kalendris (et mida näitab)
- õppimise funktsioon võiks olla veel lihtsam ja mängulisem

# HI-FI esialgne prototüüp
Link: https://drive.google.com/drive/folders/1aVtZC2UynikFwoZwN_StR0gCfs4OaTgo?usp=sharing 

## HI-Fi prototüübi esialgne tagasiside
- „Kanban“ asemel kasutada „Töövoog“
- Ainete nimed on liiga pikad. kasutada lühendeid (nt:
        - matemaatika → mat
        - eesti keel → eesti
        - inglise keel → ingl
- Kalendris võiks info olla paremini nähtav- kalender peaks olema kohe akna vaates nähtav (ilma scrollimata), tähtsam info võiks olla esile toodud värvide kaudu: 
        - ained → roheline
        - huviringid / trennid → lilla
        - muud sündmused → kolmas eraldi värv (nt sinine)
Kokkuvõte
Tagasiside põhjal on äpp kasutajate jaoks arusaadav ja kasulik ning toetab õppimise planeerimist. Suurimaks tugevuseks peetakse info koondamist ühte keskkonda ja visuaalset ülevaadet ülesannetest.
Peamised arendusvajadused on seotud:
- eestikeelse ja arusaadava terminoloogia kasutamisega
- visuaalse selguse parandamisega (värvid, lühendid)
- kalendri parema loetavusega

# HI-FI valmis protoüüp
Link valmis prototüübile: https://blotch-paste-44971541.figma.site 
