# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
Követelmények, felhasználói történetek, műszaki tervek és a kód kiértékelése
Meghibásodások okozása és hibák megtalálása
A szükséges lefedettség biztosítása a teszt tárgyának
A nem megfelelő szoftverminőség kockázati szintjének csökkentése
Annak igazolása, hogy bizonyos követelmények teljesültek-e
Annak igazolása, hogy a teszt tárgya megfelel a szerződésben foglalt, jogi vagy szabályozási
követelményeknek
Információ biztosítása az érdekelt feleknek, hogy ezáltal megalapozott döntéseket hozhassanak
Bizalom kiépítése a teszt tárgyának minőségével kapcsolatban
Annak validálása, hogy a teszt tárgya elkészült és az érdekelt felek elvárásainak megfelelően
működik.
#### ✅ Mik a tesztelési alapelvek?
A tesztelés a hibák jelenlétét mutatja, nem a hiányukat.
Nem lehetséges kimerítő teszt.
A korai tesztelés időt és pénzt spórol
Hibafürtök megjelenése
A tesztek elkopnak
A tesztelés függ a körülményektől
A hibamentesség téveszméje
#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Komponenstesztelés (más néven egységtesztelés): az egyes komponensek elkülönítve történő
tesztelésére összpontosít. Gyakran speciális támogatást igényel, például teszttámogató
szoftverkörnyezetet vagy egységteszt-keretrendszert. A komponenstesztelést általában a fejlesztők
végzik a saját fejlesztési környezetükben.
#### ✅ Mik a tesztszintek, és mi a különbség köztük?
-Öt tesztszintet sorolhatunk fel: 
Komponenstesztelés, Komponensintegrációs tesztelés, Rendszertesztelés, Rendszerintegrációs tesztelés, Elfogadási tesztelés
-A tesztszintek megkülönböztethetőek a következő, nem kimerítő paraméterek alapján, hogy elkerülhető
legyen a teszttevékenységek átfedése:
Teszt tárgya, Tesztcélok, Tesztbázis, Hibák és meghibásodások, Megközelítés és felelősségek
#### ✅ Mi a különbség a verifikáció és a validáció között?
A verifikációra, a meghatározott követelményeknek való megfelelés ellenőrzése. Ezzel szemben a validáció azt ellenőrzi, hogy a rendszer
megfelel-e a felhasználói, illetve más érdekelt felek igényeinek a működési környezetben.
#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
A teszttípusok teszttevékenységek olyan csoportjai, amelyek specifikus minőségjellemzőkhöz kapcsolódnak.
Ezeknek a tevékenységeknek a többségét minden tesztszinten el lehet végezni.

Funkcionális tesztelés: a komponens vagy rendszer működését vizsgáljuk, abból a szempontból, hogy elvégzi-e a meghatározott funkcióit.
Nemfunkcionális tesztelés: A nemfunkcionális tesztelés azt vizsgálja, hogy „miként" viselkedik a rendszer.
Feketedoboz tesztelés: dokumentációkból származtatjuk a teszteseteket. A feketedoboz tesztelés fő célja a rendszer viselkedésének ellenőrzése a rendszer specifikációinak szempontjából.
Fehérdoboz tesztelés: egy struktúraalapú teszttípus, ahol a rendszer belső
szerkezete vagy az implementációja (például: kód, architektúra, munkafolyamat, adatfolyam) alapján
származtatjuk a teszteseteket.
#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
A white box a szoftvertesztelés egyik kategóriája, amely a szoftver belső szerkezetének és felépítésének működésére vonatkozó tesztelési módszerekre utal. Ellentétben áll a fekete dobozos teszteléssel, amely olyan tesztelés, amely nem foglalkozik a szoftver belső műveleteivel, hanem csak a szoftver külső kimeneteit teszteli.

A szürke dobozos tesztelés a tesztelés olyan formája, amely a fehérdobozos és a fekete dobozos tesztelést ötvözi, felhasználva a mögöttes tervezés és a rendszer megvalósítási módjának részleges megértését. Ez a kombináció azt jelenti, hogy a tesztelő a háttérben zajló folyamatok egy részét ismeri anélkül, hogy teljes mértékben ismerné a kódot, ami nagyobb rálátást biztosít a szoftverben felmerülő problémák lehetséges okaira, amikor azok felmerülnek.
#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
Rendszertesztelés: Technikai és funkcionális elemek vizsgálata (például funkciók, teljesítmény, felhasználhatóság, biztonság), gyakran részletes, alapos elemzést igényel.
Elfogadási tesztelés: A rendszer üzleti szempontból releváns viselkedésének vizsgálata, vagyis hogy az ügyfél vagy végfelhasználó számára használható-e a termék a valós környezetben.
#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
Ha a szoftver az új vagy megváltozott funkciók bevezetése miatt veszít a funkcionalitásából, akkor azt mondjuk, hogy visszafejlődött egy kevésbé fejlett állapotba.
A regressziós tesztelést arra használják, hogy felderítsék ezeket a hibákat, és helyreállítsák az alkalmazás stabilizálását.

A füsttesztelés a szoftver tesztelésének folyamata annak biztosítása érdekében, hogy az megfeleljen az alapvető funkcionalitási és stabilitási követelményeknek. Ez lényegében egyfajta miniatűr, gyors regressziós tesztelés, amely a szoftver legfontosabb funkcióinak tesztelését foglalja magában, hogy megbizonyosodjon arról, hogy azok alapszinten működnek.

Újratesztelés: Annak ellenőrzése, hogy egy konkrét hiba valóban kijavításra került-e. Egy adott hiba újbóli tesztelése, amely korábban jelentve lett.
#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
A dinamikus teszteléssel ellentétben, statikus tesztelés esetén a tesztelés alatt álló szoftver futtatása nem
szükséges. Kódot, folyamat specifikációt, rendszer felépítés specifikációt vagy más munkatermékeket
értékelünk manuális vizsgálatok során (például felülvizsgálatokkal) vagy eszköz segítségével (például
statikus elemzés során). Tesztcél lehet a minőség javítása, a hibák felderítése, vagy például olyan jellemzők
vizsgálata, mint olvashatóság, a teljesség, a helyesség, tesztelhetőség és a konzisztencia. Statikus tesztelést
alkalmazhatunk mind verifikálás, mind validálás során. 

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
Vízesés modell Jellemzői: Lineáris, szakaszokra bontott folyamat. A tesztelés csak a fejlesztési folyamat végén indul el, ami késlelteti a hibák feltárását.
Alkalmas egyszerűbb, jól meghatározott projektekre.
Előnye: Könnyen érthető és követhető struktúra.

Agile jellemzői: Iteratív és inkrementális fejlesztési ciklusokban zajlik. Tesztelés minden iterációban történik, és a tesztelők szerves részei a csapatnak.
Az ügyfelek és a fejlesztők szoros együttműködése jellemzi.
Előnye: Gyors visszacsatolás a hibák javításához. Nagy rugalmasság a változtatások kezelésében.

V-modell Jellemzői: A tesztelési tevékenységek minden fejlesztési fázishoz kötődnek (pl. a rendszertervezéshez kapcsolódik a rendszer szintű tesztelés).
Tesztelés már a projekt kezdeti szakaszaiban tervezésre kerül. Az előre meghatározott folyamatok és a részletes dokumentáció teszi hatékonnyá.
Előnye: Korán azonosíthatók a hibák, mivel a tesztelés párhuzamosan történik a fejlesztéssel.

<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">





## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
Először reprodukálom a hibát, majd dokumentálom a részleteket (lépések, várt/tényleges eredmény, környezet), végül elküldöm a hibajelentést priorizálva.
#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
Gyakori jelentések a hibajelentés, teszteset-összefoglaló és napi jelentés, mind tartalmazza a hiba leírását, lépéseit és súlyosságát.
#### ✅ Mit tartalmaz egy hibajelentés?
Egy hibajelentés tartalmazza a címét, leírást, reprodukálási lépéseket, várt/tényleges eredményt, súlyosságot, prioritást és környezeti adatokat.
#### ✅ Hogyan rangsorolnál egy hibát? 
A súlyosság (kritikus, major, stb.) és a prioritás (azonnali, magas, stb.) alapján, pl. egy összeomlás kritikus és azonnali, míg egy elírás minor és alacsony prioritású.

## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
Automatizálhatóak az ismétlődő, időigényes vagy kritikus funkciók (pl. regressziós tesztek), de nem szükséges automatizálni a ritkán futó teszteket.
#### ✅ Írj le egy jó automatizált tesztet!
Egy jó automatizált teszt rövid, karbantartható, és csak egy funkciót ellenőriz (pl. bejelentkezés helyes adatokkal).
#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
A Selenium egy webtesztelő keretrendszer, az IDE rekord-lejátszó eszköz, a WebDriver pedig kódalapú tesztelésre szolgál.
#### ✅ Hogyan lehet azonosítani a webes elemeket?
XPath, CSS selector, ID vagy név alapján lehet azonosítani, a legstabilabb az ID vagy egyedi CSS selector.
#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
Használható explicit vagy implicit várakozás; hibák lehetnek időtúllépés, elem eltűnése vagy dinamikus betöltés.
#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
A POM (Page Object Model) strukturáltabb és kódalapú, míg a Keyword Driven könnyebben olvasható, de kevésbé rugalmas.
#### ✅ Mi a különbség a TDD és BDD között?
A TDD (Test-Driven Development) fejlesztőközpontú, míg a BDD (Behavior-Driven Development) üzleti és tesztelői nyelvet használ.
#### ✅ Mi az API tesztelés és miért hasznos?
Az API tesztelés a backend logikát ellenőrzi, gyorsabb és megbízhatóbb, mint a felületi tesztelés.
#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
Adatvezérelt tesztelésben ugyanaz a teszt különböző adatokkal fut, hatékonyabb és kevesebb kódismétlést igényel.

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
Adatvezérelt tesztelés egy szoftvertesztelési módszer, amelyben a tesztadatokat táblázat vagy táblázat formájában tárolják. Az adatvezérelt tesztelés lehetővé teszi a tesztelők számára, hogy egyetlen tesztszkriptet vigyenek be, amely képes tesztelni egy tábla összes tesztadatát, és a tesztkimenetet ugyanabban a táblában várja. Táblázatvezérelt tesztelésnek vagy paraméterezett tesztelésnek is nevezik.
#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?
Használjunk modern technikákat, például a Fetch API-t a hagyományos AJAX helyett, a jobb olvashatóság és teljesítmény érdekében.
Kezeljük a hibákat és szélsőséges eseteket, hogy zökkenőmentes felhasználói élményt nyújthass.
Optimalizáljuk a dinamikus tartalom betöltését, hogy elkerüld a teljesítménybeli bottleneck-elést.
#### ✅ Mik a mobil tesztautomatizálás kihívásai?
A különböző mobilalkalmazás típusok
Operációs rendszerek és böngészők
Kijelző méret
Hálózattípus és sebesség problémák
Gyorsan változó felhasználói követelmények
## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?
A CI/CD tesztelés egy olyan folyamat, amely automatizáltan teszteli a szoftverfejlesztés során beképzett kódváltoztatásokat. A CI (Continuous Integration) biztosítja a kódforrás automatikus integrációját és tesztelését, a CD (Continuous Delivery/Deployment) pedig automatizáltan szállítja a szoftvert, tesztkörnyezetbe vagy élő környezetbe. A cél a gyorsabb, megbízhatóbb és minőségibb szoftverfejlesztés és -szállítás.
#### ✅ Írj le egy Continuous Delivery folyamatot!
A CI folyamat után automatizáltan szállítja (Delivery) vagy telepíti (Deployment) a szoftvert egy tesztkörnyezetbe vagy a végfelhasználóknak elérhető környezetbe. A Delivery során a szoftver egy tesztkörnyezetben tesztelésre kerül, míg a Deployment során közvetlenül az élő környezetbe kerül.
#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
Jenkins egy nyílt forráskódú Continuous Integration szerver Java a folyamatos integrációs folyamat automatizált módon történő megvalósítása érdekében. A Jenkins támogatja a szoftverek teljes fejlesztési életciklusát, a szoftverfejlesztéstől, teszteléstől, dokumentálástól, telepítéstől és a szoftverfejlesztési életciklus egyéb szakaszaitól kezdve.
#### ✅ Mi a Docker és miért hasznos?
A Docker egy platform-szolgáltatási (PaaS) termékcsalád, amely operációs rendszer szintű virtualizációt használ a szoftverek konténernek nevezett csomagokban történő szállításához.A szolgáltatásnak ingyenes és prémium szintje is van. A konténereket üzemeltető szoftvert Docker Engine-nek hívják.[6] Első verzióját 2013-ban adták ki, és a Docker, Inc. fejleszti.
A Docker egy olyan eszköz, amely az alkalmazások könnyűsúlyú konténerekben történő telepítését automatizálja, így az alkalmazások különböző környezetekben elszigetelten és hatékonyan működhetnek.
https://en.wikipedia.org/wiki/Docker_(software)