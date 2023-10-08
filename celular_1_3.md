## Kapitola: Základní Koncepty a Terminologie

Celulární automaty (CA) vyvolávají fascinaci především svou schopností generovat složité a pestré vzory vycházející z jednoduchých pravidel. Abstraktní, a přesto s obdivuhodnou blízkostí odrážejíce některé aspekty přírodních systémů, se staly nástrojem v široké škále disciplín, od informatiky přes fyziku až po biologii.

### Definice Celulárního Automatu

Celulární automat je diskrétní model používaný v komputační teorii a matematických simulacích. Skládá se z mřížky buněk, kde každá buňka může nabývat určitého stavu, a sada pravidel, která určují, jak se stavy buněk budou vyvíjet v čase na základě stavů jejich sousedů. Buňky jsou obvykle uspořádány v jedné, dvou nebo více dimenzích a každá z nich interaguje s omezeným počtem svých sousedů.

### Buněčný Stav a Sousedství

**Buněčný stav** je konkrétní situace nebo kondice buňky v určitém časovém kroku, která může být například „živá“ nebo „mrtvá“, „0“ nebo „1“. Soubor všech možných stavů buňky tvoří stavový prostor automatu.

**Sousedství** buňky jsou ostatní buňky, jejichž stavy ovlivňují chování vybrané buňky v následujícím časovém kroku. Velikost a forma sousedství jsou definovány konkrétním modelem celulárního automatu a jsou nezbytné pro definici přechodové funkce.

### Přechodová Funkce

Klíčovým konceptem v CA je **přechodová funkce**, která definuje, jak se buňka a její stav mění od jednoho časového kroku k dalšímu v závislosti na svém aktuálním stavu a stavech svého sousedství. Pravidla, která tuto funkci definují, mohou být deterministická (výsledný stav je jednoznačně určen současným stavem a stavem sousedství) nebo stochastická (existuje náhodný element ovlivňující výběr budoucího stavu).

### Časový Krok a Generace

CA se vyvíjí v **časových krocích**. V každém kroku se stavy všech buněk aktualizují synchronně, což znamená, že před výpočtem následujících stavů všech buněk jsou použity pouze stavy z předchozího kroku. Sekvence všech buněk a jejich stavů v určitém časovém kroku se často nazývá **generace**.

### Pravidla a Komplexita

Přestože pravidla CA mohou být na první pohled jednoduchá, produkují občas nesmírně složité a nepředvídatelné vzory. To vede k konceptům, jako jsou **emergentní chování** a **komplexita**, které budou v následujících kapitolách zkoumány více do hloubky.

Zajímavostí CA je, že i přes zdánlivou jednoduchost a přímost konceptu, jsou schopny generovat neuvěřitelně složité a promyšlené vzory a dynamiky, což ukazuje na širokou škálu aplikací a možností dalšího výzkumu a objevování. V příští kapitole prozkoumáme několik základních typů CA a pravidel, která vedou k fascinujícím a často protichůdným výsledkům.
