# A Kanban útmutató Scrum csapatoknak

2019\. szeptember

Fejleszti és fenntartja a Scrum.org és Daniel Vacanti

## Cél

A Kanban áramlás-alapú nézőpontja kiegészítheti és hatékonyabbá teheti a Scrum keretrendszert és annak megvalósítását.
A csapatok akkor is alkalmazhatnak kiegészítő Kanban gyakorlatokat, ha most kezdenek Scrumot használni, vagy ha már régóta használják.

_A Kanban útmutató Scrum csapatoknak_ a Scrum.org közösség tagjainak és a Kanban közösség vezetőinek az együttműködésének az eredménye.
Ők együtt állnak _A Kanban útmutató Scrum csapatoknak_ mögött.
Közös hitvallásuk, hogy a termékfejlesztésben dolgozó szakemberek számára hasznos lehet a Kanban és Scrum együttes alkalmazása.

## Kapcsolat A Scrum útmutatóval

Ez az útmutató nem írja felül és nem hagyja figyelmen kívül _A Scrum útmutató_ bármely részét.
Abból a célból írtuk, hogy kiegészítse és hatékonyabbá tegye a Scrum gyakorlatait.
Ez az útmutató feltételezi, hogy az olvasó a Scrum keretrendszert használó folyamatokat alkalmaz.
Ebből következően _A Scrum útmutató_ teljes egészében érvényes.

## A Kanban definíciója

Kanban (főnév): egy olyan stratégia, mely az érték áramlásának optimalizálását célozza egy olyan folyamaton keresztül, amely egy vizuális, a folyamatban levő munkát (Work in Progress, WIP) korlátozó húzórendszert (pull system) használ.

## Kanban és Scrum elmélet

### Áramlás és empirizmus

A Kanban definíciójában központi fogalom az "áramlás" (flow).
Az áramlás az érték mozgása a termékfejlesztési rendszeren keresztül.
A Kanban az áramlást optimalizálja azáltal, hogy egy folyamat átfogó hatékonyságát, hatásosságát és kiszámíthatóságát növeli.

Az áramlás Scrum környezetben való optimalizáláshoz szükséges definiálni, hogy mit jelent az áramlás a Scrum esetében.
A Scrum a tapasztaláson alapuló folyamatellenőrzési elméleten, vagy más néven empirizmuson alapul.
Az empirikus folyamatellenőrzéshez kulcsfontosságú az átláthatóság (transparency), ellenőrzés (inspection) és korrekció (adaptation) ciklusa, amit megfogalmazhatunk úgy is, hogy a visszacsatolási hurok ciklusideje.

Amikor Kanban gyakorlatokat használunk Scrum környezetben, azok a visszacsatolási hurkon keresztül segítenek az áramlás javítására összpontosítani; az átláthatóságot és az ellenőrzés és korrekció gyakoriságát optimalizálva mind a termék, mind a folyamat szempontjából.

### Az áramlás alapvető mérőszámai

Az áramlás négy alapvető mérőszáma, melyeket a Kanbant használó Scrum Csapatoknak (Scrum Team) követnie kell, az alábbiak:

* **Folyamatban levő munka (Work in Progress, WIP):** A már megkezdett, de még be nem fejezett munkaelemek száma.
  Vegyük észre a WIP mérőszám és a Scrum Csapat (Scrum Team) által használt WIP korlátok közti különbséget.
  A csapat a WIP mérőszámot használhatja arra, hogy láthatóvá tegyék, hogyan haladnak a WIP csökkentésével és az áramlás javításával.
* **Ciklusidő (Cycle Time):** Adott munkaelem elkezdésétől annak befejezéséig eltelt idő.
* **Munkaelem életkora (Work Item Age):** Adott munkaelem elkezdésétől mostanáig eltelt idő.
  Ez csak a folyamatban levő munkaelemekre értelmezhető.
* **Áteresztőképesség (Throughput):** Adott időegységen belül befejezett munkaelemek száma.

### Little-törvény – az áramlás irányításának kulcsa

Az áramláselmélet egyik legfontosabb tana a Little-törvény (Little's Law), ami az alábbi kapcsolatot megadó irányelv:

```
                      átlagos folyamatban levő munka
átlagos ciklusidő  =  ——————————————————————————————
                        átlagos áteresztőképesség
```

A Little-törvény kimondja, hogy adott folyamat és adott áteresztőképesség esetén, minél több dolgon dolgozunk egyszerre egy adott pillanatban (átlagosan), annál több ideig fog tartani azok befejezése (átlagosan).

Ha a ciklusidők túl hosszúak, akkor az első lépés, amit a Scrum Csapatoknak (Scrum Team) meg kell fontolni, az a WIP csökkentése.
A Kanban egyéb elemeinek legtöbbje a WIP és a ciklusidő kapcsolatára épít.

A Little-törvény arra is rámutat, hogy hogyan alapszik az áramláselmélet az empirizmuson: az áramlási mérőszámokat és adatokat használja a historikus áramlás láthatóvá tételére, majd ezen adatokat használja az áramlás ellenőrzését és korrekcióját szolgáló kísérletekhez.

## Kanban gyakorlatok

A Scrum Csapatok (Scrum Team) az áramlás optimalizálását az alábbi négy gyakorlat használatával érhetik el:

* A munkafolyamat vizualizációja
* A folyamatban levő munka (WIP) korlátozása
* A folyamatban levő munkaelemek aktív menedzsmentje
* A munkafolyamatuk definíciójának ellenőrzése és korrekciója

### A "munkafolyamat" definíciója

A négy Kanban gyakorlat használatát a Scrum Csapat (Scrum Team) munkafolyamat-definíciója teszi lehetővé.
Ez a definíció jeleníti meg a Scrum Csapat (Scrum Team) tagjainak világos értelmezését arra vonatkozólag, hogy milyen szabályok alapján követik a Kanban gyakorlatokat.
Ez a közös értelmezés növeli az átláthatóságot és lehetővé teszi az önszerveződést.

Megjegyzendő, hogy a munkafolyamat definíciója a Sprinten és a Sprint Teendőlistán (Sprint Backlog) túlra is nyúlhat.
Például egy Scrum Csapat (Scrum Team) munkafolyamat-definíciója tartalmazhat Sprinten belüli és/vagy Sprinten kívüli áramlást.

A munkafolyamat definíciójának létrehozása és korrekciója a Scrum Csapat (Scrum Team) megfelelő szerepköreinek a felelőssége, _A Scrum útmutató_-ban leírtak szerint.
A Scrum Csapaton (Scrum Team) kívül senki nem mondhatja meg a Scrum Csapatnak (Scrum Team), hogyan definiálják a munkafolyamatukat.
Ehhez hasonlóan, a Fejlesztőcsapaton (Development Team) kívül senki – beleértve a Terméktulajdonost (Product Owner) és a Scrum Mastert is – nem mondhatja meg a csapatnak, hogyan definiálják a munkafolyamat azon szempontjait, amelyek a Fejlesztőcsapat (Development Team) munkájának belső részletei.

### A munkafolyamat vizualizációja – a Kanban tábla

A Scrum Csapat (Scrum Team) a Kanban táblával történő vizualizációval teszi átláthatóvá a munkafolyamatát.
A tábla megjelenése a megfelelő időben a megfelelő párbeszédekre kell, hogy ösztönözzön, és proaktívan kell sugallnia fejlődési lehetőségeket.

A vizualizációnak tartalmaznia kell az alábbiakat:

* Meghatározott pontok, amelyeknél a Scrum Csapat (Scrum Team) megkezdettnek, illetve befejezettnek tekinti a munkát.
* A munkaelemek definíciója – az érték azon körülhatárolt egységei (ügyfélérték, tudásbeli érték, folyamatkorrekciós érték), amelyek a Scrum Csapat (Scrum Team) rendszerén keresztül áramlanak (leggyakrabban Termék Teendőlista Tételek (Product Backlog Item, PBI)).
* A munkafolyamat azon állapotainak definíciója, amelyeken át a munkaelemek áramlanak az elejétől a végéig (és amelyekből legalább egynek aktív állapotnak kell lennie).
* Világos szabályok arra vonatkozólag, hogy a munka hogyan áramlik az egyes állapotokon keresztül. (Ezen szabályok közé sorolhatóak a Scrum Csapat (Scrum Team) "kész" definíciójának elemei és az állapotok közti húzó szabályok.)
* Annak szabályai, hogy a folyamatban levő munka (Work in Progress, WIP) korlátozása hogyan történik.

### A folyamatban levő munka (WIP) korlátozása

A folyamatban levő munka (Work in Progress, WIP) azokat a munkaelemeket jelenti, amelyeket a Scrum Csapat (Scrum Team) már elkezdett, de még nem fejezett be.

A Kanbant használó Scrum Csapatoknak (Scrum Team) ezeket a folyamatban levő munkaelemeket határozottan korlátoznia kell.
Egy Scrum Csapat (Scrum Team) úgy korlátozza a WIP-et, ahogy azt jónak látja, azonban amint megállapodtak a korlátban, azt be kell tartaniuk.

A WIP korlátozásának elsődleges hatása, hogy egy húzórendszert (pull system) hoz létre.
Azért nevezzük ezt húzórendszernek, mert a Scrum Csapat (Scrum Team) csak akkor kezd dolgozni egy munkaelemen ("húz be munkát"), amikor egyértelmű, hogy van rá kapacitása.
Amikor a WIP egy adott érték alá esik, az jelzi, hogy új munkát lehet kezdeni.
Megjegyzendő, hogy ez különbözik a tolórendszertől (push system), ami azt igényli, hogy a munkát akkor kezdjék el egy munkaelemen, amint azt kérik.

A WIP korlátozása javítja az áramlást, és növeli a Scrum Csapat (Scrum Team) önszerveződését, fókuszát, elkötelezettségét és együttműködését.

### A folyamatban levő munkaelemek aktív menedzsmentje

A WIP korlátozása az áramlás elérésének egy szükséges eleme, de önmagában nem elegendő.
Az áramlás elérésének harmadik gyakorlata a folyamatban levő munkaelemek aktív menedzsmentje.
A Sprinten belül ennek a Fejlesztőcsapat (Development Team) általi menedzsmentnek több formája lehetséges, beleértve többek közt az alábbiakat:

* Annak biztosítása, hogy munkaelemeket csak azzal nagyjából egyező ütemben húzunk be a munkafolyamatba, mint ahogy azok elhagyják a munkafolyamatot.
* Annak biztosítása, hogy a munkaelemek nem avulnak el.
* Gyors reagálás elakadt vagy feltorlódott munkaelemekre, valamint azokra, amelyek túllépték a csapat által várt ciklusidejüket. (Lásd a "Szolgáltatási szint várakozások (SLE)" részt.)

#### Szolgáltatási szint várakozások (SLE)

Egy szolgáltatási szint várakozás (Service Level Expectation, SLE) előrejelzi, mennyi időbe telhet egy elemnek a Scrum Csapat (Scrum Team) munkafolyamatának a kezdetétől a végéig áramlania.
A Scrum Csapat (Scrum Team) az SLE segítségével találja meg az áramlás aktív problémáit, és azt használja ellenőrzésre és korrekcióra, amikor az elvárt szintek alá esik.

Az SLE két részből áll: az eltelt napok számából és egy ahhoz kapcsolódó valószínűségből (pl. "a munkaelemek 85%-át fejezzük be 8 napon belül").
Az SLE a Scrum Csapat (Scrum Team) historikus ciklusidején (cycle time) alapszik, és amint kiszámolták, a Scrum Csapatnak (Scrum Team) azt átláthatóvá kell tenni.
Ha nincsen adat historikus ciklusidőre vonatkozólag, akkor a Scrum Csapatnak (Scrum Team) egy becslést érdemes adnia, majd azt korrigálnia, amint van elegendő historikus adat valós SLE számításhoz.

### A munkafolyamat-definíció ellenőrzése és korrekciója

A Scrum Csapat (Scrum Team) a meglévő Scrum eseményeket használja a munkafolyamata definíciójának ellenőrzésére és korrekciójára, így növelve az empirizmust és optimalizálva a Scrum Csapat (Scrum Team) által szállított értéket.

A Scrum Csapat (Scrum Team) eldöntheti, hogy alkalmazza-e a munkafolyamat-definíció következő szempontjait:

* Vizualizációs szabályok – például a munkafolyamat állapotai –, melyek vagy az aktuális munkafolyamatot változtatják meg, vagy jobb átláthatóságot adnak egy olyan területen, melyet a csapat ellenőrizni és korrigálni akar.
* "Hogyan dolgozunk" szabályok – ezek kimondottan egy akadály elhárítását célozzák.
  Például: drámai hatása lehet a WIP korlátok és SLE-k utánállításának; vagy annak, hogy a kötegek méretét változtatjuk; vagy hogy a munka egyes állapotok közti áthúzásának gyakoriságát változtatjuk.

## Áramlás alapú események

A Kanban Scrum környezetben nem követel meg új eseményeket _A Scrum útmutató_-ban felsoroltakon kívül.
Mindazonáltal, az áramlás alapú nézőpont és az áramlási mérőszámok használata a Scrum események során erősíti a Scrum empirikus megközelítését.

### A Sprint

A Kanban kiegészítő gyakorlatai nem helyettesítik a Scrum Sprintet.
Még olyan környezetekben is, ahol a folyamatos áramlás kívánatos/elérhető, a Sprint mind a termék, mind a folyamatok ellenőrzésének és korrekciójának üteme, avagy "szívritmusa".
A Scrumot Kanbannal együtt használó csapatok a Sprint eseményeit visszacsatolásként használják úgy, hogy együttműködésben ellenőrizzék és korrigálják a munkafolyamat-definíciójukat és az áramlási mérőszámokat.

A Kanban gyakorlatok segíthetnek a Fejlesztőcsapatnak (Development Team) az áramlás javításában és egy olyan környezet kialakításában, amelyben a döntéseket a Sprint során "éppen jókor" ("just in time") hozzák meg ellenőrzés és korrekció alapján.
Ilyen környezetben a Fejlesztőcsapatok (Development Team) a Sprint Cél (Sprint Goal) és a Terméktulajdonossal (Product Owner) való szoros együttműködés segítségével optimalizálják a Sprint során szállított értéket.

### Sprint Tervezés

Az áramlás alapú Sprint Tervezés (Sprint Planning) áramlási mérőszámokat használ a Sprint Teendőlista (Sprint Backlog) kialakításához.
Például a historikus áteresztőképesség használható a Scrum Csapat (Scrum Team) következő Sprintre vonatkozó kapacitásának megértésére.

### Napi Scrumok

Az áramlás alapú Napi Scrum (Daily Scrum) arra fókuszál, hogy a Scrum Csapat (Scrum Team) mindent megtegyen az áramlás mindennapi fenntartásához.
Bár a Napi Scrumok (Daily Scrum) célja továbbra is ugyanaz, ami _A Scrum útmutató_-ban le van írva, a találkozó a Kanban tábla körül történik, és arra fókuszál, hogy hol akadozik az áramlás és a Scrum Csapatnak (Scrum Team) mit kell tennie, hogy a munka újbóli áramlását biztosítsa.

Néhány újdonság, amiket egy áramlás alapú Napi Scrum (Daily Scrum) során meg kell fontolni:

* Mely munkaelemek akadtak el, és mit tehet a Scrum Csapat (Scrum Team) ezek feloldására?
* Milyen munka áramlik a vártnál lassabban?
  Mi az egyes folyamatban levő munkaelemek életkora?
  Melyik munkaelemek sértették meg vagy fogják megsérteni az SLE-jüket, és mit tehet a Scrum Csapat (Scrum Team) ezek befejezésének érdekében?
* Van-e bármi, ami befolyásolhatja a Scrum Csapat (Scrum Team) képességét a munka mai befejezésére, de nem látható a táblán?
* Tudtunk-e meg bármi újat, ami megváltoztathatja, hogy a Scrum Csapat (Scrum Team) min dolgozzon ezután?
* Megsértettük-e a WIP korlátainkat?
  És mit tehetünk annak érdekében, hogy a folyamatban levő munkát befejezzük?

### Sprint Áttekintés

_A Scrum útmutató_ részletes vázlatot ad a Sprint Áttekintés (Sprint Review) folyamatáról.
Ha az áttekintés részeként megvizsgáljuk a Kanban áramlási mérőszámokat, az új párbeszédeket indíthat a cél felé való haladás megfigyeléséről.
Az áteresztőképesség áttekintése további információt nyújthat, amikor a Terméktulajdonos (Product Owner) lehetséges szállítási dátumokról tárgyal.

### Sprint Visszatekintés

Az áramlás alapú Sprint Visszatekintés (Sprint Retrospective) az áramlási mérőszámok vizsgálatát és olyan elemzéseket nyújt, melyek segítenek megállapítani, milyen javításokat eszközölhet a Scrum Csapat (Scrum Team) a saját folyamatain.
A Kanbant használó Scrum Csapat (Scrum Team) a munkafolyamat-definícióját is ellenőrzi és korrigálja annak érdekében, hogy optimalizálja az áramlást a következő Sprintben.
Hasznos lehet halmozott áramlás diagramot (cumulative flow diagram) használni a Scrum Csapat (Scrum Team) folyamatban levő munkájának (WIP), átlagos megközelítő ciklusidejének (Cycle Time) és átlagos áteresztőképességének (Throughput) a vizualizálására.

A Sprint Visszatekintés (Sprint Retrospective) mellett a Scrum Csapat (Scrum Team) számára az is megfontolandó, hogy kihasználják azokat a lehetőségeket a folyamatok ellenőrzésére és korrekciójára, melyek a Sprint során merülnek fel.

Hasonlóképp, a csapat munkafolyamat-definíciójának módosításai is történhetnek bármikor.
Ezeknek a módosításoknak jelentős hatása van a Scrum Csapat (Scrum Team) teljesítményére, így a Sprint Visszatekintés (Sprint Retrospective) állandó ütemére végzett módosítások csökkentik a komplexitást és növelik az átláthatóságot.

## Növekmény

A Scrum megköveteli, hogy a csapat minden Sprintben a "kész" termék (legalább) egy potenciálisan szállítható növekményét (inkrementum, Increment) hozza létre.
A Scrum empirizmusa támogatja, hogy a Sprint során több potenciálisan szállítható növekményt is létrehozzanak annak érdekében, hogy gyors ellenőrzési és korrekciós visszacsatolások lehessenek.
A Kanban segít ezen visszacsatolások áramlását világosabban menedzselni, és lehetővé teszi, hogy a Scrum Csapat (Scrum Team) megtalálja a szűk keresztmetszeteket, megszorításokat és akadályokat a gyorsabb és folyamatosabb értékszállítás érdekében.

## Végjegyzet

A Scrum nem egy folyamat vagy módszer.
A Scrum egy "olyan keretrendszer, melynek segítségével emberek komplex problémákat tudnak adaptív módon kezelni úgy, hogy közben termelékenyen és kreatívan szállítják le a lehető legértékesebb termékeket".
Amint arra _A Scrum útmutató_ felhívja a figyelmet, más módszerek, módszertanok és gyakorlatok kereteként működik jól.

A Kanban áramlást optimalizáló gyakorlatai a Scrum Csapatoknak (Scrum Team) további lehetőségeket nyújtanak a megfelelő dolog megfelelő időben történő ellenőrzésére, majd ezen ellenőrzések alapján a korrekcióra.
A Kanban átláthatóságra, vizualizációra és áramlásra irányított éles fókusza maximalizálja a visszacsatolásokat, az empirizmust és végeredményben az értékszállítást.

## Történet és köszönetnyilvánítás

Az együttesen Kanbanként ismert gyakorlatok többsége 2006-ban kezdődtek egy csapatnál a Corbis-ban, ami egy Bill Gates tulajdonában álló médialicencelő cég.
Ezek a gyakorlatok gyorsan terjedtek egy nagy és változatos nemzetközi közösséget létrehozva, akik az évek során ezt a megközelítést erősítették és fejlesztették.

Ez az útmutató a Scrum.org, a Professional Scrum Trainer Közösség, Steve Porter, Yuval Yeret és Daniel Vacanti együttműködésének eredménye.

Külön köszönet Louis-Philippe Carignannek, Charles Bradley-nek, Jose Casalnak, Andy Hiles-nak és Jesse Houwingnak a közreműködésükért.
Ugyancsak hálával tartozunk mindazon szakmabelieknek, akik a múltban hozzájárultak ahhoz, hogy a Kanban életképes és sikeres lean-agile stratégia lehessen.

## Fordítás

Ezt az útmutatót a 2019-es, eredeti angol verzióról [Varga Patrik](https://www.linkedin.com/in/patrikvarga/) fordította magyar nyelvre.

Lektorálta [Tolvaj Ákos](https://www.linkedin.com/in/akostolvaj/).

## Változások – 2019. szeptember

Ez a változat _A Kanban útmutató Scrum csapatoknak_ érthetőségét és felépítését szándékozik javítani.
Több fogalmat finomítottunk és néhány témát, ami eddig függelékben és kiegészítő anyagokban volt elérhető, beemeltünk magába az útmutatóba.
Konkrét változtatások többek között:

* Átalakított elméleti rész, amely érthetőbbé teszi az áramlás és empirizmus közti kapcsolatot, valamint bevezeti az áramlási mérőszámokat és a Little-törvényt.
* A munkafolyamat-definíció rész tisztázása, és ennek keretében néhány példa áthelyezése a Kanban gyakorlatok közé.
* Néhány szabály általánosítása, hogy a részletes előírásokat csökkentsük és helyettük az elvekre koncentráljunk.
* Átalakítottuk a vizualizáció és felelősség hatályát a munkafolyamat-definíciót illetően.
* Készült egy új fejezet arról, hogy az áramlás hogyan érinti a növekményt.
* Az SLE "A folyamatban levő munkaelemek aktív menedzsmentje" fejezet része lett.

## Fordítói megjegyzések

A Scrum.org Translation Guidelines alapján a Scrum Guide és Kanban Guide által definiált fogalmak (pl. "Sprint Review", "Scrum Team", "Increment", "flow", "workflow") angolul írandók a különböző nyelvű fordításokban is. A [Scrum.org oldalon publikált PDF fordításokban](https://www.scrum.org/resources/kanban-guide-scrum-teams) így ezek a fogalmak angolul jelennek meg folyó magyar szövegben is.

A könnyebb érthetőség és olvashatóság érdekében ezeket mi jobbnak láttuk lefordítani magyarra (angol hivatkozással), így ez a Markdown verzió ennyiben különbözhet a hivatalos PDF-től.

---

© 2018–2019 Scrum.org. Elérhető a "Nevezd meg! – Így add tovább!" Creative Commons licenc alapján. A licenc elérhető a <https://creativecommons.org/licenses/by-sa/4.0/legalcode> oldalon, valamint a <https://creativecommons.org/licenses/by-sa/4.0/deed.hu> oldalon összefoglalva. A felhasználó _A Kanban útmutató Scrum csapatoknak_ használatával elismeri, hogy a Creative Commons "Nevezd meg! – Így add tovább!" licencet megismerte, és vállalja, hogy azt betartja.
