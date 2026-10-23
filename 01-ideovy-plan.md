# PROJECT-GAME
Název projektu je Cyber-Runner

# ÚVOD
Každé patro je těžší, ale ty jsi s každým patrem silnější. Cyber-Runner by měla být 2D akční plošinovka, která otestuje tvoje reflexy i taktické myšlení. 
Přeskakuj smrtící laserové pasti, zabíjej monstra i stráže a sbírej datové čipy ve stráženém megakomplexu. 
Na konci každé úrovně tě čeká černý trh, tam si můžeš vyměmit nasbírané čipy pro předměty, který ti zvedají statistiky a mají taky unikátní efekty.

# CORE LOOP
Cyber-Runner je 2D akční skákačka rozdělená na samostatné úrovně (patra věže), mezi kterými se nachází interaktivní obrazovka obchodu a vylepšení.
Mapa je náhodně generována a má různé režimy:
**Příběhový** - Hráč hraje cca 10 levelů věže ke konci levelu je mini-bossfight a na 10 úrovni je velký bossfight. Každý boss dává unikátní negativní efekt.
**Nekonečný** - Hráč může hrát nekonečno levelů a hra se mů uloží mezi levelami, každých pár levelů je bossfight.
**Trénink** - Hráč si zde může vyzkoušet různé upgrady a předměty proti nepřátelům a taky pohyb
Hráč běží zleva doprava i vertikálně, překováná propasti, pohyblivé plošiny a pasti. Zabíjí nepřátele a jako odměnu dostane herní měnu (datové čipy)
Na konci úrovně ve výtahu se otevře menu vylepšení, objeví se 3 ikony, zbraň, armor a rychlost, hráč si vybere jednu a pak to ukáže co by mohl vylepšit.
Vylepšení jsou levnější na začátku a dražší ke konci.
Poté hráč má možnost si vybrat jeden ze tří perků před vstupem do dalšího težšího levelu. Perky jsou speciální a dražší než základní statistiky.

# FUNKČNOST
**Pohybový systém**: Běh, skok, wall-jump a dash
Systém vylepšování mezi levely:
**Zbraň**: Zvýšení poškození, rychlosti střelby a střel, odemknutí speciálník efektů jako atd..
**Brnění**: Zvýšení počtu životů, redukce poškožení od pastí nebo nepřátel, zrychlení regenerace, regenerujicí se štít na který neplatí redukce poškození.
**Mobilita**: Zvýšení rychlosti, zkrácení cooldownu na Dash a vyšší skok atd..
**Speciál**: Unikátní vylepšení - Life steal, větší poškození pro nepřátele s vyšším zdravím, odraz nábojů od stěn nebo prúrazné náboje, atd..

# CÍL HRÁČE
Probojovat se přes všechna připravená patra komplexu, kombinovat nakoupené upgrady zbraní, brnění a rychlosti, porazit finálního bosse na brcholu věže a dokončit hru co v nejlepším čase.

# POPIS AUDIOVIZUÁLU
## Vizuál:
2D Pixel Art ve sci-fi / indrustriálním prostředí. Výrazné odlišení plošin a nebezpežných prvků. (červené lasery, modré plošiny)
Tmavší pozadí s paralaxním efektem (více vrstev pozadí pohybujících se různou rychlostí).
Změny barvy projektilů při vylepšení zbraně speciálním perkem a světelné stopy za projektilem.
UI obchodu by měla mít technologické rozhraní po skončení levelu s ikonami pro Zbraň, Armor a Rychlost. Poté UI perk obchodu by měl mít třpytivější efekt. 

## Audio stránka
**Hudba**: Elektronický a rockový podrkes během akčního levelu, který se po vstupu do obchodu na konci kola ztiší do klidnější ambietní variace (synth).
**SFX**: Elektrický/8-Bit styl zvuku pro skok, dopad, výstřel, zásah nepřítele a potvrzovací zvuk pri nákupu.

# CHYSTANÉ POUŽITÉ TECHNOLOGIE
**Herní engine**: Godot
**Ukládání dat**: JSON
**Grafika a Level Design**: Tiled / Unity Tilemap, Aseprite / Photoshop
**Audio**: Suno AI, Audacity a custom IRL zvuky.
**Verzování**: GitHub

# HYPOTÉZY
1. Na začátku Hráči nebudou umět multitaskovat střílení, chození a soustředění se na okolí
2. Hráči budou chtít speedrunovat Cyber-runner ale moc jim to nepůjde







