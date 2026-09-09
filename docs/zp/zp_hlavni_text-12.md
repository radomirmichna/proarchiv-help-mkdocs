# 12. TŘÍDA GEOGRAFICKÝ OBJEKT

Geografické objekty jsou vlastním jménem pojmenované lokality na Zemi,
zeměpisné útvary, vesmír a jeho části (kromě umělých vesmírných
objektů). Základní vlastností geografických objektů je vymezení stálým
souborem geografických souřadnic, tj. identifikovatelnost na mapě.

Jedním z hlavních účelů popisu geografických objektů je správná
lokalizace geografického objektu nebo jiných souvisejících entit
(například místo narození a úmrtí, sídlo korporace, umístění stavby
atd.) současným uživatelem, a to až na nejnižší úroveň potřebnou pro
jednoznačnou identifikaci entity v hierarchii sídelních jednotek. Pro
tyto potřeby se proto při popisu preferuje aktuálně platný, obvykle
i úředně stanovený stav.

Fiktivní geografické objekty (např. Atlantida) se neevidují.

U geografických objektů často hrozí jejich záměna s entitami jiných
tříd, například s korporacemi či s díly a výtvory. Rozhodnutí o zařazení
do příslušné třídy vyplývá z účelu nebo charakteru entity uvedeného ve
zpracovávaném zdroji informace. V uživatelském označení se rozlišení
projevuje pomocí obecného doplňku a stručné charakteristiky.

> **Příklady:**
>
> **Uživatelské označení:** ***Tajanovský Mlýn** (Tajanov, Kolinec,
> Klatovy, Česko : nižší sídelní jednotka), samota u vsi Tajanov* =
> třída „geografický objekt“, podtřída „administrativně či jinak lidmi
> vymezená území“
>
> vs.
>
> **Uživatelské označení:** ***Tajanovský mlýn** (Tajanov, Kolinec,
> Klatovy, Česko : stavba), mlýn s turbínou vyrábějící elektřinu*
>
> **VAR 1:** hlavní část jména: *dům čp. 24*
>
> **VAR 2:** hlavní část jména: *mlýn Tajanov*
>
> = třída „dílo/výtvor“, podtřída „stavby, trasy, zásahy do přírodních
> útvarů s vlastním jménem nebo jinou identifikací“
>
> **Uživatelské označení:** ***Lesná** (Brno, Brno-město, Česko), část
> obce s panelovým sídlištěm* = třída „geografický objekt“, podtřída
> „administrativně či jinak lidmi vymezená území“
>
> vs.
>
> **Uživatelské označení:** ***Lesná** (Brno, Brno-město, Česko :
> sídliště), panelové sídliště ve stejnojmenné části města*
>
> = třída „dílo/výtvor“, podtřída „stavby, trasy, zásahy do přírodních
> útvarů s vlastním jménem nebo jinou identifikací“
>
> **Uživatelské označení:** ***Bory** (Jižní Předměstí, Plzeň,
> Plzeň-město, Česko : nižší sídelní jednotka), čtvrť města Plzeň* =
> třída „geografický objekt“, podtřída „administrativně či jinak lidmi
> vymezená území“.
>
> vs.
>
> **Uživatelské označení:** ***Věznice Bory** (správa věznice : Plzeň,
> Plzeň-město, Česko : 1997-), orgán zajišťující výkon trestu*
>
> **VAR 1:** hlavní část jména: *Bory*
>
> **VAR 2:** hlavní část jména: *Věznice Plzeň*
>
> **VAR 3:** hlavní část jména: *Vězeňská služba České republiky.*
> Vedlejší část jména: Věznice Plzeň
>
> **VAR 4:** hlavní část jména: *VS ČR*. Vedlejší část jména: Věznice
> Plzeň
>
> **VAR 5:** hlavní část jména: *Borská věznice*
>
> = třída „korporace“, podtřída „vojenské a bezpečnostní jednotky“
>
> vs.
>
> **PREF:** ***Věznice Bory** (Plzeň, Plzeň-město, Česko : stavba :
> 1878-)*
>
> **VAR 1:** hlavní část jména: *Bory*
>
> **VAR 2:** hlavní část jména: *Věznice Plzeň*
>
> **VAR 3:** hlavní část jména: *Borská věznice*
>
> = třída „dílo/výtvor“, podtřída „stavby, trasy, zásahy do přírodních
> útvarů s vlastním jménem nebo jinou identifikací“

## 12.1 Podtřídy geografických objektů

### 1. Administrativně či jinak lidmi vymezená území

Historická i současná území (nadnárodní i v rámci jednoho státního
útvaru) obvykle spravovaná orgány veřejné moci.

Jedná se například o:

\- kontinenty/světadíly,

\- státy a státní útvary,

\- země ve smyslu správním (např. v českých zemích do roku 1949),

\- závislá i autonomní území,

\- kraje,

\- vládní obvody (něm. „*Regierungsbezirke*“ v Sudetské župě 1939-1945),

\- okresy a jim obdobná správní území (provincie, prefektury, kantony,
obštiny, župy, vojvodství, hrabství ad.),

\- berní okresy (něm. „*Steuerbezirke*“),

\- obce, města, městské části, městské obvody, městské čtvrti, osady
(něm. „*Ortschaften*“) jako autonomní části obcí ve smyslu § 107 zák. č.
7/1864 českého z. z.,

\- místní části obcí (něm. „*Ortsbestandteile*“),

\- sčítací obvody,

\- (panelová) sídliště,

\- samoty,

\- veřejná prostranství (náměstí, ulice, nábřeží),

\- pozemkové trati,

\- území označená místními a pomístními jmény,

\- vojenské újezdy,

\- historické, tj. nyní již správně zrušené či zaniklé oblasti.

Pokud není níže uvedeno jinak, míní se hierarchickou úrovní “obec” nejen
typ “obec”, ale i “vojenský újezd” a “obec se širší působností” (blíže
viz **přílohu č. 10**).

Nepatří sem administrativně vymezená území v přírodě, která mají vlastní
podtřídu. Území správních obvodů far a škol se jako geografické objekty
netvoří, neboť je jako entity vyjadřují příslušné farní úřady a školy
z třídy korporace.

> **Příklady PREF:**
>
> ***Česko***
>
> ***Velkomoravská říše** (9. st.-asi 907)*
>
> ***Pardubický kraj** (Česko : 2000-)*
>
> ***Adolfovice** (Bělá pod Pradědem, Jeseník, Česko)*
>
> ***Antarktida** (kontinent/světadíl)*

### 2. Administrativně vymezené části přírody

Lidmi administrativně vymezená území v přírodě. Jsou to například
národní parky, přírodní rezervace, chráněné krajinné oblasti, přírodní
památky, významné krajinné prvky, ptačí oblasti, lesoparky, parky, sady,
zahrady atd.

Nepatří sem jednotlivé přírodní útvary.

> **Příklad PREF:**
>
> ***Tatranský národní park** (Slovensko)*

### 3. Další vymezené lokality, oblasti a zóny

Národopisné oblasti, památkové zóny, archeologické lokality, rekreační
území (např. sportovní komplexy, rekreační areály).

> **Příklady uživatelského označení:**
>
> ***Lom Leštinka** (Skuteč, Skuteč, Chrudim, Česko : rekreační území),
> sportovní komplex*
>
> ***Výr** (Výrovice, Znojmo, Česko : rekreační území), rekreační areál
> na jižní Moravě*

### 4. Geomorfologické útvary na dně moře

Útvary na dně moří a oceánů existující nezávisle na administrativním
vymezení. Například podmořské pánve, hřbety, příkopy, hory a sopky,
pevninské šelfy, mořské útesy atd.

> **Příklady PREF:**
>
> ***Velký bariérový útes** (Korálové moře)*
>
> ***Sundský příkop** (Indický oceán)*

### 5. Geomorfologické útvary na zemském povrchu

Útvary na zemském povrchu existující nezávisle na administrativním
vymezení. Například litosférické desky, zlomová pásma, souostroví,
ostrovy, poloostrovy, atoly, mysy, horské a pobřežní útesy, sopky,
ledovce, pohoří, hory, hornatiny, pahorkatiny, kopce, vrchy, vrchoviny,
skály, údolí, průsmyky, krátery, plošiny, nížiny, jeskyně atd.

> **Příklady PREF:**
>
> ***Jižní Shetlandy** (Antarktida : souostroví)*
>
> ***Malé Karpaty** (Rakousko a Slovensko : vrchovina)*

### 6. Vodstvo a vodní plocha, vodní tok

Vodní plochy a toky, tj. oceány, moře, mořské proudy, zálivy, jezera,
ledovce, prameny, gejzíry, povodí, řeky, potoky, meandry, peřeje, plesa,
vodopády. Patří sem také umělé vodní plochy (např. rybníky, údolní
nádrže, vodní a plavební kanály, průplavy, umělé cvičné peřeje apod.),
neboť ty nejsou považovány za entity třídy „dílo/výtvor“*.*

Naopak do třídy „dílo/výtvor“, podtřída „stavby, trasy…“ patří
vodohospodářské stavby typu přehradní a rybniční hráze, zdymadla, jezy,
splavy, stavidla, kanalizace, vodovody, meliorační systémy, kašny apod.

> **Příklady PREF, resp. uživatelského označení u přírodního vodstva:**
>
> ***Štrbské pleso** (Štrba, Poprad, Slovensko : jezero), morénové
> ledovcové jezero*
>
> ***Rolava** (Česko : řeka)*
>
> ***Vřídlo** (Karlovy Vary, Karlovy Vary, Česko : pramen), pramen
> léčivé termální vody*
>
> **Příklady PREF, resp. uživatelského označení u umělých vodních
> ploch:**
>
> ***Brněnská přehrada** (Brno-město, Česko : vodní nádrž)*
>
> ***Orlík** (Česko : vodní nádrž)*
>
> ***Borecký rybník** (Borek, Košice, Tábor, Česko : rybník)*
>
> ***Suezský průplav** (Egypt : průplav)*
>
> ***Hubertus** (Sadov, Karlovy Vary, Česko : peřej), cvičná umělá
> vodácká peřej*

### 7. Pojmenované útvary

Jednotlivé přírodní útvary nepatřící do výše uvedených podtříd.
Například rašeliniště, pralesy, lesy, skupiny stromů, jednotlivé stromy,
pouště, oázy.

> **Příklady PREF:**
>
> ***Libyjská poušť** (Afrika : poušť)*
>
> ***Körnerův dub** (Dalovice, Karlovy Vary, Česko : strom)*
>
> ***Síwa** (Egypt : oáza)*

### 8. Pojmenované trvalé klimatické jevy

Pouze trvalé klimatické jevy. Naopak dočasné, jednorázové přírodní jevy
a živelné pohromy, např. „***Katrina** (hurikán)*“, „***Kyrill**
(bouře)*“, patří do třídy „událost“, podtřídy „dočasné přírodní jevy“.

> **Příklady PREF:**
>
> ***El Niño** (trvalý klimatický jev)*
>
> ***Jihovýchodní obchodní vítr** (trvalý klimatický jev)*

### 9. Vesmír a jeho části

Například mlhoviny, hvězdy, planety, měsíce, pojmenované útvary na
povrchu planet a měsíců atd.

> **Příklady PREF:**
>
> ***Enceladus** (měsíc)*
>
> ***Purkyně** (Měsíc : kráter)*

## 12.2 Zásady popisu geografického objektu

### 12.2.1 Geografické objekty vyvíjející se v čase

Pro popis se vždy preferuje současný stav. Změny vyplývající
z historického vývoje geografického objektu se zaznamenávají pomocí
datovaných vztahů a událostí. Pouze pokud je to nevyhnutelné, je některá
z etap vyčleněna do samostatného záznamu.

U podtřídy „administrativně či jinak lidmi vymezená území“ se postupuje
následovně:

**1. Pro typy geografických objektů „obec“ a hierarchicky nižších
sídelních jednotek** se preferuje současné jméno a jeho změny
v historickém vývoji se uvádějí formou VAR s případnou datací použití
jména.

Je třeba mít na paměti, že obce jako entity třídy „geografický objekt“
a podtřídy „administrativně či jinak lidmi vymezená území“, jsou
vyjadřovány svými záznamy pouze ve svém současném stavu. Rozsah velkého
množství z nich se ovšem (někdy i radikálně) zvětšil v průběhu 2.
poloviny 20. století v důsledku slučování obcí. Obec proto co do rozsahu
často nemusí být totožná s obcí/městem, jež existovala v době, ke které
se vztahuje příslušná archiválie či jiná zpracovávaná entita. Podle toho
je nutno pečlivě zvážit, zda je v dané situaci třeba použít záznam obce,
či záznam části obce, popř. záznam městské části/obvodu.

> **Příklad:**
>
> Je popisována archiválie týkající se obce Oldřiš na Karlovarsku z 1.
> poloviny 20. století. Oldřiš sice byla tehdy samostatnou obcí, ale
> nyní je součástí obce Merklín. Jako geografický objekt se proto Oldřiš
> vždy zapisuje jako osada Merklína (současný stav), tedy „***Oldřiš**
> (Merklín, Karlovy Vary, Česko)*“, a nikdy jako samostatná obec. Jako
> variantní označení se zapisuje německá verze jména „*Ullersgrün*“.
> Datace použití tohoto jména bude doba před rokem 1945. Podobně viz
> níže příklady **v kapitole 12.2.2**.

**Výjimka:** „městské části/obvody“, u kterých se jednotlivé fáze
historického vývoje evidují jako samostatné entity.

> **Příklad:** ***Praha XIV – Nusle** (Praha, Česko : správní obvod :
> 1947-1949), historický správní obvod Prahy*

**2. Pro typy geografických objektů hierarchicky vyšších než „obec“** se
jednotlivé fáze historického vývoje evidují jako samostatné entity,
např. „***Toužim** (Česko : okres : 1949-1960)*“.

Uvedené zaniklé územní útvary jsou primárně evidovány kvůli potřebě
vyjádřit územní působnost dnes již zaniklého administrativního území ve
vztahu ke korporacím. Dále slouží k tomu, aby se dalo přesněji vyjádřit
určité výrazně změněné nebo zaniklé administrativní území zachycené
v obsahu popisované archiválie. Pokud tato přesnost není potřebná,
upřednostňuje se napojení archivního autoritního záznamu současného
administrativního území (stát, okres atd.).

> **Příklady:**
>
> U entity „***Československo.** Ministerstvo techniky*“ z třídy
> „korporace“ se ve vztahu „geografická působnost“ použije napojení na
> archivní autoritní záznam entity „***Československo** (1918-1992)*“
> z třídy „geografický objekt“, nikoli na záznam entity „***Česko***“
> z téže třídy.
>
> U archivního popisu týkajícího se písemností konkrétního soudního
> okresu je vhodnější napojení archivního autoritního záznamu entity
> reprezentující onen historický soudní okres, nikoli napojení záznamu
> dnešního okresu, neboť takové vymezení obvodu je přesnější.
>
> U archivního popisu vztahujícího se k blíže neurčenému území v Česku
> v roce 1980 se napojí archivní autoritní záznam entity reprezentující
> současné „***Česko**“*, nikoli záznam entity „***Česko** (Česko :
> 1969-1992)*“. V tomto případě je důležitější určení polohy, a nikoli
> historické správní uspořádání.

### 12.2.2 Problematika slučování sídel

Původní sídelní lokality, které fyzicky nezanikly, nýbrž se sloučily
s další lokalitou nebo došlo k jejich územnímu zvětšení a změně statutu,
se nepovažují za zaniklé. Popisují se jako administrativní část
současného většího celku, tj. jako nižší sídelní jednotka obce, jejíž
součástí se staly.

Pro původní historická sídla či jejich části se po agregaci do
současných sídelních jednotek samostatné záznamy nezakládají, ale
použijí se záznamy současných geografických objektů, které na jejich
místě leží.

> **Příklady:**
>
> **Původní samostatná obec, jež je nyní administrativní částí jiné
> obce**
>
> ***Frýdek** (Frýdek-Místek, Frýdek-Místek, Česko)* – současná část
> obce se používá i pro historické samostatné město Frýdek, které bylo
> v roce 1943 sloučeno s Místkem do jednoho města.
>
> **Původní samostatná obec, jež není nyní administrativní částí jiné
> obce**
>
> ***Mezimostí** (Veselí nad Lužnicí, Tábor, Česko : nižší sídelní
> jednotka)* – jako současná nižší sídelní jednotka se používá i pro
> původní samostatnou obec, která byla v roce 1943 sloučena s Veselím
> nad Lužnicí. Entita byla založena jako nová, neboť RÚIAN tuto lokalitu
> neobsahuje.
>
> **Původní historická lokalita vs. současné administrativní části
> různého jména**
>
> Původní historické centrum města Děčína, tzn. tehdejší město uvnitř
> městských hradeb, dnes spadá teritoriálně pod dvě části obce: „Děčín
> I-Děčín“ a „Děčín II-Nové Město“.
>
> Na archivní popis (například u středověké listiny) se napojí archivní
> autoritní záznam entity reprezentující současné město „***Děčín**
> (Děčín, Česko)*“. Napojení záznamů dvou výše zmíněných částí obce by
> sice bylo teritoriálně přesnější, ale neodpovídalo by kontinuitě jména
> lokality, která je v tomto případě upřednostněna. Navíc je entita
> současného města Děčín nejbližší hierarchickou úrovní geografického
> objektu, která původní historické centrum města obsáhne.

### 12.2.3 Problematika rozlučování lokalit / bývalé uměle vytvořené obce

Jde zpravidla o obce, které vznikaly v 60. až 80. letech 20. století
jako uměle sdružené (střediskové) obce, ke spojení však docházelo
i v minulosti (po roce 1850). Jelikož na jejich teritoriu nedošlo
k fyzickému zániku osídlení, pouze k územně správním změnám, nelze tyto
entity považovat za zaniklé geografické objekty a zakládat pro ně
archivní autoritní záznamy. Jak správně postupovat při propojování
archivního popisu s archivními autoritními záznamy je vysvětleno na
následujících příkladech:

> **Příklady:**
>
> **Středisková obec**
>
> V letech 1961–1979 byly sloučeny obce Vinary, Lýsky a Popovice v obec
> se jménem „Viničná“. Od roku 1980 se tyto tři lokality staly součástí
> Přerova jako jeho části obce: „Přerov XI-Vinary“, „Přerov IX-Lýsky“
> a „Přerov X-Popovice“.
>
> Na archivní popis vztahující se k obci Viničná se napojí zároveň tři
> archivní autoritní záznamy všech tří současných částí obce. Ve všech
> záznamech uvedených tří částí obce bude jako variantní označení
> uvedeno Viničná (s datací použití jména od 1961 do 1979). Napojení
> archivního autoritního záznamu entity reprezentující celé město Přerov
> by bylo v daném případě nepřesné.
>
> **Stejnojmenná lokalita se složitějším územně správním vývojem
> a přejmenováním**
>
> Dnešní obec „***Hukvaldy** (Frýdek-Místek, Česko)*“ se skládá z pěti
> částí obce: „Hukvaldy“, „Horní Sklenov“, „Dolní Sklenov“, „Rychaltice“
> a „Krnalovice“ (poslední jmenovaná od roku 2016).
>
> Stručná historie jednotlivých částí:
>
> • Sklenov – do roku 1960 samostatná obec. V pramenech se vyskytují dvě
> části obce Sklenov, a to „Dolní Sklenov“ (zvaný také „Velký Sklenov“)
> a „Horní Sklenov“ (zvaný též „Malý Sklenov“).
>
> • Hukvaldy – po roce 1849 osada Sklenova.
>
> • Rychaltice – do roku 1960 samostatná obec.
>
> V roce 1960 došlo ke sloučení výše zmíněných lokalit do jedné obce se
> společným jménem „Sklenov“.
>
> K 1. 7. 1982 došlo k přejmenování sloučené obce „Sklenov“ na
> „Hukvaldy“. V roce 2016 byly k Hukvaldům připojeny „Krnalovice“ jako
> samostatná část obce. Část území Krnalovic dříve patřila
> k Rychalticím, část k sousední obci Fryčovice.
>
> Na archivní popis dokumentu vztahujícího se ke Sklenovu z období před
> sloučením v roce 1960 se napojí dva archivní autoritní záznamy obou
> současných částí obce, tj. „***Dolní Sklenov** (Hukvaldy,
> Frýdek-Místek, Česko)*“ a „***Horní Sklenov** (Hukvaldy,
> Frýdek-Místek, Česko)*“.
>
> Obdobně se záznamy stejnojmenných částí nynější obce Hukvaldy napojí
> i na archivní popisy, které se vztahují k Hukvaldům, Rychalticím
> a Krnalovicím. Na archivní popis vážící se k celé obci po sloučení
> v roce 1960 se ovšem napojí archivní autoritní záznam entity
> „Hukvaldy“, tj. „***Hukvaldy** (Frýdek-Místek, Česko)*“, který bude
> obsahovat variantní označení „*Sklenov*“ s datací použití jména od
> 1960 do 1982.

### 12.2.4 Sídla obnovená či se změněnou polohou

Jako jedna entita se popisuje vždy:

1\. Obec či jiná sídelní jednotka, která sice fyzicky přestala
existovat, avšak později byla **znovu obnovena**. Oba dva celky (zaniklý
a znovu postavený) jsou chápány jako jedna entita. O přerušení osídlení
(dočasném zániku) informují příslušné prvky popisu.

2\. Geografický objekt stejného jména **nepatrně měnící polohu** na
základě vnějších okolností, jakými jsou například změna koryta vodního
toku, vynucené přemisťování lokalit související s důlní, průmyslovou
a vodohospodářskou činností, válečnými či přírodními katastrofami apod.

> **Příklady:**
>
> **PREF:** ***Lidice** (Kladno, Česko)*
>
> **Stručná charakteristika:** *obec vyhlazená nacisty a poté opět
> obnovená*
>
> **PREF: *Most*** *(Most, Česko)*
>
> **Stručná charakteristika:** *město postižené důlní činností a zároveň
> město navazující na původní historické sídlo zničené kvůli dolování*
>
> **PREF: *Dolní Kralovice*** *(Benešov, Česko)*
>
> **Stručná charakteristika:** *zatopená obec a zároveň obec navazující
> na původní sídlo*

Pokud je třeba přesněji určit například původní historické centrum
zatopené obce, může se nově vytvořit entita typu geografického objektu
„nižší sídelní jednotka“. Do stručné charakteristiky se uvede „původní
historické centrum zatopené obce XY“ a zároveň se uvedou souřadnice
původního centra obce.

### 12.2.5 Samoty na místě zaniklých vesnic s totožným jménem

Pokud na místě zaniklé obce zůstane torzo osídlení, vytváří se pouze
jeden archivní autoritní záznam pro samotu či osadu, místní název apod.
(typ geografického objektu „nižší sídelní jednotka“), popř. pro část
obce, či pro jiný typ geografického objektu, podle toho, jaký status
torzo osídlení v současnosti má. Na archivní popis k zaniklé obci se
napojí archivní autoritní záznam této entity.

> **Příklad:**
>
> **PREF:** ***Ryžovna** (Boží Dar, Karlovy Vary, Česko)*
>
> **Stručná charakteristika:** *část obce Boží Dar v okrese Karlovy
> Vary, torzo zaniklé, dříve samostatné obce*
>
> **Typ geografického objektu:** *část obce*

### 12.2.6 Zaniklá sídla

Jako zaniklé sídlo je chápána pouze taková lokalita (vojenský újezd,
obec a hierarchicky nižší), která zanikla fyzicky, jako sídelní jednotka
již nebyla nikdy obnovena a v případě území Česka zároveň není evidována
jako část obce v RÚIAN. Fyzický zánik je ověřován s pomocí aktuálních
map nebo dostupných satelitních či leteckých snímků.

U zaniklých sídel je potřeba vždy vytvořit událost „Zánik“. Ve spojení
s chronologickým doplňkem „*zaniklo*“, se tak vyjadřuje, že sídlo již
neexistuje. Kvůli možným komplikacím při zjišťování informací o zániku
nemusí být v události Zánik uvedena datace, související entita či
poznámka, nejsou-li známy. Povinně se u této události však vždy vyplňuje
alespoň typ zániku (přinejmenším hodnota „jiný typ zániku“).

Jako typ geografického objektu se volí ten, který byl platný v době
zániku. Nelze-li jej určit, použije se typ „nižší sídelní jednotka“.
Další skutečnosti se vysvětlí ve stručné charakteristice.

> **Příklady:**
>
> **PREF: *Skryje*** *(Dukovany, Třebíč, Česko : zaniklo)*
>
> **Stručná charakteristika:** *část obce Dukovany zaniklá z důvodu
> výstavby Jaderné elektrárny Dukovany, původně samostatná obec* –
> v době zániku už nebyla samostatnou obcí; v roce 1976 se stala částí
> obce Dukovany; v roce 1980 byla oficiálně zrušena; není vedena
> v RÚIAN.
>
> **Typ geografického objektu:** *část obce*
>
> **PREF: *Víckovský dvůr*** *(Petrovice, Třebíč, Česko : nižší sídelní
> jednotka : zaniklo)*
>
> **Stručná charakteristika:** *samota zaniklá v důsledku třicetileté
> války*
>
> **Typ geografického objektu:** *nižší sídelní jednotka*
>
> **PREF: *Dunkelsberg*** *(Hradiště, Karlovy Vary, Česko : nižší
> sídelní jednotka : zaniklo)*
>
> **Stručná charakteristika:** *zaniklá osada zaniklé obce Zakšov na
> území dnešního vojenského újezdu Hradiště*
>
> **Typ geografického objektu:** *nižší sídelní jednotka*
>
> **PREF:** ***Doupov** (Hradiště, Karlovy Vary, Česko : zaniklo)*
>
> **VAR:** *Duppau*
>
> **Stručná charakteristika:** *město zaniklé následkem zřízení
> vojenského výcvikového prostoru Hradiště*
>
> **Typ geografického objektu:** *obec*

U ostatních typů geografických objektů podtřídy „administrativně či
jinak lidmi vymezená území“, ani u ostatních podtříd se chronologický
doplněk „zaniklo“ nepoužívá. Není-li známo přesné datum či rok vzniku
a zániku, uplatňuje se odhad či první/poslední zmínka (tj. uváděno
od/do).

> **Příklad uživatelského označení:** ***Kreuzteich** (Rybáře, Karlovy
> Vary, Karlovy Vary, Česko : rybník : uváděno od 1842-uváděno do 1947),
> zaniklý rybník v katastrálním území Rybáře*

### 12.2.7 Anonymní, blíže neznámé a fiktivní geografické objekty

Není-li známo jméno ani dostatek údajů o geografickém objektu, záznam
takové entity se nezakládá.

Není přípustné vytvářet archivní autoritní záznamy typu „*neznámá Lhota
v Česku*“, „*Albrechtice (Česko)*“ apod., pokud nelze geografický objekt
přesně lokalizovat.

Jsou-li sousedící sídla (obce) obdobného jména v archiválii blíže
nerozlišeny, je řešením připojit oba, nebo více přístupových bodů.

Pokud se jedná o reálně existující entitu neznámého jména, která si
s ohledem na svůj význam zaslouží vlastní přístupový bod (zaniklá
hradiště apod.), je možno ji zařadit do podtřídy „další vymezené
lokality, oblasti a zóny“ jako typ geografického objektu „archeologická
lokalita“. U sídla neznámého jména doloženého archeologickým průzkumem
lze např. použít jméno nejbližšího geografického objektu s místním nebo
pomístním jménem.

> **Příklad:**
>
> **PREF: *Mukov*** *(Mukov, Hrobčice, Teplice, Česko : archeologická
> lokalita)* – místo, kde se nacházelo pravěké hradiště.

Záznamy fiktivních geografických objektů (např. „Atlantida“,
„Středozem“, „Sluneční město“, „Kvítečkov“, „Katan“, „Kocourkov“,
„Rukapáně“) se nezakládají. Maximálně lze vytvořit přístupový bod ve
formě archivního autoritního záznamu entity třídy „dílo/výtvor“, ve
které je fiktivní geografický objekt obsažen, např. „***U nás
v Kocourkově** (film)*“, „***Neználek ve Slunečním městě** (Nikolaj
Nikolajevič Nosov : kniha)*“, „***Osadníci z Katanu** (Klaus Teuber :
společenská hra)*“.

## 12.3 Součásti a prvky popisu geografického objektu

Společným prvkem popisu pro všechny geografické objekty je správné
začlenění do třídy a podtřídy na základě výběru z číselníku (povinný
PP).

### 12.3.1 Označení

Označení se vytváří analogicky podle příkladů uvedených **v příloze č.
10**.

#### Preferované označení

##### Hlavní část jména

**Povinnost:** povinný PP.

**Pravidla:**

Jméno geografického objektu (území, sídla, geomorfologického útvaru nebo
části vesmíru ad.).

Pokud jde o reálně existující entitu neznámého jména, která si s ohledem
na svůj význam vyžaduje evidování, zvolí se vhodný způsob identifikace.
Například u vesnice neznámého jména doložené archeologickým průzkumem se
použije jméno místní trati, nejbližšího geografického objektu s místním
nebo pomístním jménem apod.

Pokud se u současných států a s nimi souvisejících území liší formální
jméno od oficiální zjednodušené podoby jména (pod nímž je entita obvykle
nejvíce známá), jako preferované označení se používá oficiální
zjednodušená podoba jména dle oficiální databáze zeměpisných (krátkých)
jmen zemí OSN, spravované ČSÚ. Například „***Česko***“ místo „*Česká
republika*“.

V preferovaném označení lze zkratku použít pouze pokud:

a\) je zkratka součástí hlavní části úředního jména (např. „*Nám. T. G.
Masaryka*“, „*Washington, D. C.*“),

b\) se v geografickém doplňku uvádí katastrální území („*k. ú.*“).

###### Geografické objekty ležící mimo ČR

Při tvorbě preferovaného označení aktuálně existujících sídel mimo ČR
(typ geografického objektu „obec s rozšířenou působností“ a nižší
z podtřídy „administrativně či jinak lidmi vymezená území“) je primárním
zdrojem aplikace „Jména světa“, spravovaná Českým úřadem zeměměřickým
a katastrálním (<https://ags.cuzk.cz/jmenasveta>). Pro tento účel se
však nepoužívají ta exonyma, která jsou v uvedené aplikaci označena jako
historická. Pokud se v aplikaci české exonymum nenachází, přistoupí se
k transkripci či transliteraci platného názvu.

Pro ostatní entity třídy „geografický objekt“ (aktuálně existující
i zaniklé) se jako zdroj pro preferované označení použije výše uvedená
aplikace, resp. se doporučují další důvěryhodné a hojně využívané zdroje
(např. mapy.cz, Google Maps, Wikipedie). Takto zjištěné české názvy jsou
používány jak v hlavní části jména, tak i v geografickém doplňku. Jsou
povoleny i kombinované varianty, pokud se v těchto zdrojích vyskytují
(např. francouzský region Burgundsko-Franche-Comté). Původní cizojazyčné
jméno entity se uvádí vždy jako variantní označení.

Názvy okresu se zapisují formou jmen jejich center/sídel s výjimkou
případů, kdy v úředním jméně centrum/sídlo okresu uvedeno není. Název
okresu se zapisuje českým ekvivalentem, pakliže i u archivního
autoritního záznamu entity reprezentující toto centrum/sídlo je rovněž
v preferovaném označení použita čeština – například u okresu Mnichov
v Bavorsku se uvádí „***Mnichov** (Německo : okres)“*. Důvodem je
používání jména okresu v rámci geografického doplňku, u něhož je žádoucí
zkrácená forma. Dále **viz přílohu č. 10, typ geografického objektu
Okres**.

##### Doplněk

**Pravidla:**

Doplněk není opakovatelný.

Pro každý typ doplňku existuje samostatný prvek popisu.

Typy doplňků a jejich pořadí:

###### 1. Obecný doplněk

**Povinnost:** povinný PP za určitých okolností, v ostatních případech
se neuvádí.

**Pravidla:** povinnost je definována dle konkrétního typu geografického
objektu – **viz přílohu č. 10**.

###### 2. Geografický doplněk

**Povinnost:** povinný PP za určitých okolností, v ostatních případech
se neuvádí.

**Pravidla:**

Povinnost je definována dle konkrétního typu geografického objektu –
**viz přílohu č. 10**.

Navrhuje se ze vztahů „administrativní zařazení“.

Nezobrazuje historický vývoj; skládá se ze současných jmen geografických
objektů.

Pokud se v záznamech entit ležících mimo ČR uvádí v jejich geografickém
doplňku takové jméno okresu, které je odvozené od jména jeho
centra/sídla (**viz přílohu č. 10**, typ geografického objektu Okres),
zapisuje se zde tento okres českým ekvivalentem – např. Markersdorf
(Zhořelec, Německo), pakliže i v záznamu entity tohoto centra/sídla je v
preferovaném označení použita čeština, např. **PREF:** *Zhořelec
(Zhořelec, Německo)*, **VAR**: *Görlitz*, **VAR:** *Gorlitium*; na
rozdíl od např. **PREF:** *Baracs (Dunaújváros, Maďarsko)*.

**Způsoby zápisu:**

**1. Pro entity v Česku** se doplněk vytváří postupným řetězením
informací o části obce, obci či vojenském újezdu, okrese a státu. Zadává
se nejnižší úroveň potřebná pro jednoznačnou identifikaci entity, a to
vždy v současném označení a administrativním zařazení. V případě, že
tato konstrukce není dostatečná pro rozlišení entit, lze před obec nebo
i část obce předřadit ještě katastrální území nebo některý typ ze
skupiny nižších sídelních jednotek (ulice apod.).

Okres se v geografickém doplňku povinně zapisuje ve všech případech, tj.
i u okresních měst, např. „*Pardubice (Pardubice, Česko)*“. Tím je bez
pochybností a zcela jasné, že v geografickém doplňku:

a\) první pozice před výrazem „Česko“ znamená vždy okres,

b\) druhá pozice před „Česko“ znamená vždy obec nebo vojenský újezd,

c\) třetí pozice před „Česko“ znamená část obce, popř. hierarchicky
nižší část, např. ulici, katastrální území apod.,

d\) čtvrtá pozice před „Česko“ znamená další, hierarchicky ještě nižší
část, tj. nižší sídelní jednotku (viz blíže **přílohu č. 10**),

Výjimku tvoří geografické objekty na území hlavního města Prahy. Ty
včetně Prahy samotné v doplňku nemají okres uveden.

**2. Pro entity na Slovensku, v Polsku, Rakousku, Německu, Maďarsku a na
Ukrajině** se doplněk vytváří řetězením informací o části obce, obci,
okrese a státu (vždy v současném znění).

Výjimku tvoří geografické objekty typu „obec se širší působností“,
u kterých se okres v doplňku neuvádí, např. „***Mnichov** (Německo),
hlavní město Bavorska“*.

**3. Pro entity z ostatních zemí** se doplněk vytváří řetězením
informací pouze o části obce, obci / obci se širší působností a státu
(vždy v současném znění). Příslušná, zpravidla nejbližší nadřazená,
vnitřní část státu (**blíže viz přílohu č. 10, kapitolu Geografické
objekty – hierarchie administrativního zařazení**) se do doplňku uvede,
jen pokud je potřeba odlišit v daném státě dvě entity se stejným jménem.
Přitom je třeba mít na zřeteli, že i nadřazené části mohou mít stejné
označení a v takovém případě se uvádí i další nadřazená část (např.
u stejnojmenných okresů v USA se uvádí i část „země“).

Z hlediska použití českých nebo cizojazyčných jmen u entit mimo ČR se
při tvorbě geografického doplňku postupuje podle stejných pravidel,
která jsou stanovena pro tvorbu preferovaného označení **(viz výše –
hlavní část jména)**.

Pokud se entita rozkládá na území dvou a více států, píše se geografický
doplněk následovně:

a\) dva státy – uvedou se oba státy oddělené spojkou „*a*“, např.
„***Krkonoše** (Česko a Polsko : pohoří)*“; „***Sněžka** (Česko a Polsko
: hora)*“*.* Jména států se v geografickém doplňku řadí abecedně.

b\) více států – uvede se kontinent/světadíl, např. „***Šumava** (Evropa
: pohoří)*“

Pokud nelze entitu zařadit pod konkrétní stát, lze jako geografický
doplněk použít jméno kontinentu/světadílu nebo jméno objektu ve vesmíru
(planety, měsíce, hvězdy). U geografických objektů mimo pevninu,
u kterých není možné určit příslušnost ke státu či kontinentu/světadílu,
je možné použít moře či oceán.

Jednotlivé hierarchické části geografického doplňku se oddělují čárkou
následovanou mezerou.

> **Příklady geografického doplňku v PREF:**
>
> ***Andělská Hora** (Karlovy Vary, Česko)* – obec ležící v ČR v okrese
> Karlovy Vary
>
> ***Andělská Hora** (Bruntál, Česko)* – obec ležící v ČR v okrese
> Bruntál
>
> ***Andělská Hora** (Chrastava, Liberec, Česko)* – část obce Chrastava
> v ČR v okrese Liberec
>
> ***Podmilesy** (Domašín, Domašín, Chomutov, Česko : zaniklo)* –
> zaniklá ves Podmilesy, která se nacházela na území dnešní části obce
> Domašín
>
> ***Podmilesy** (Domašín, Chomutov, Česko : přírodní památka)* –
> přírodní památka Podmilesy ležící v obci Domašín, resp. v částech obce
> Domašín a Louchov; nejbližší nadřazenou lokalitou je proto obec
> Domašín
>
> ***Havraňák** (Čakovice, Praha, Česko : lesopark)* – lesopark v části
> obce Čakovice, která je součástí hlavního města Prahy
>
> ***Tomanova** (Plzeň, Plzeň-město, Česko : ulice)* – entita se sice
> celá nalézá v části obce Jižní Předměstí, ale v případě ulic, náměstí
> a nábřeží je nejnižší možná úroveň v geografickém doplňku pouze obec.
> Proto se zde uvedená část obce nezapisuje tímto způsobem:
> ***Tomanova** (Jižní Předměstí, Plzeň, Plzeň-město, Česko : ulice)*.

Dále **viz přílohu č. 10**.

###### 3. Chronologický doplněk

**Povinnost:** povinný PP za určitých okolností, v ostatních případech
se neuvádí.

**Pravidla:**

Používá se pouze v podtřídě „administrativně či jinak lidmi vymezená
území“, a to jen v následujících případech:

1\. U současných okresů a krajů na území ČR – uvádí se otevřeným časovým
intervalem, např. „***Karlovy Vary** (Česko : okres : 1960-)*“,
„***Karlovarský kraj** (Česko : kraj : 2000-)*“*.*

2\. U zaniklých geografických objektů z podtřídy „administrativně či
jinak lidmi vymezená území“:

a\) v případě zaniklých entit typu geografického objektu „obec“, „obec
se širší působností“, „vojenský újezd“ a hierarchicky níže – zapisuje se
jako „*zaniklo*“ (s výjimkou městských částí, u nichž se uvádí časový
rozsah existence – viz **přílohu č. 10**, Typ geografického objektu,
Městská část/obvod),

> **Příklad**:
>
> ***Zakšov** (Hradiště, Karlovy Vary, Česko : katastrální území :
> zaniklo), zrušené katastrální území ve vojenském újezdu Hradiště*

b\) u zaniklých entit s typem geografického objektu hierarchicky vyšším
než „obec“, „obec se širší působností“ a „vojenský újezd“ – uvádí se dle
datačních hodnot obsažených v událostech „Vznik“ a „Zánik“ či pouze ve
zjednodušené formě těchto údajů (století apod.).

> **Příklad**:
>
> ***Bechyňsko** (Česko : kraj : 9. st.-1751), zaniklý hradský obvod,
> později kraj, v jižních Čechách*

U ostatních geografických objektů této podtřídy (např. u současných
nezaniklých sídel a oblastí – kraje, státy ad.) se chronologický doplněk
neuvádí bez ohledu na to, zda je v události „Vznik“ vyplněna „datace
vzniku/první písemné zmínky“, či nikoliv.

Pouze výjimečně je možné chronologický doplněk uvést i u ostatních
podtříd, pokud je to účelné, například při zániku přírodního útvaru
(ledovce, útesy aj.).

##### Typ formy jména

**Povinnost:** nepovinný PP.

**Pravidla:** V případě nejistoty se neuvádí. V opačném případě se
provádí výběr z číselníkové nabídky:

a\) úřední,

b\) uměle vytvořené,

c\) ekvivalent,

d\) jediný známý tvar,

e\) zkratka/akronym,

f\) historická/dřívější podoba,

g\) přezdívka/zlidovělá podoba,

h\) zjednodušená podoba,

i\) zkomolená podoba,

j\) podoba s čestným názvem,

k\) podle jiných pravidel – náleží sem i invertovaná podoba jména.

#### Variantní označení

**Povinnost:** doporučená část archivního autoritního záznamu.

**Pravidla:**

Uvádějí se všechna další zjištěná jména včetně jazykových a gramatických
variant jména a změn jména.

Struktura je stejná jako u preferovaného označení.

> **Příklady:**
>
> **PREF: *Rybáře*** *(Karlovy Vary, Karlovy Vary, Česko)*
>
> jazyk: *čeština*
>
> datace použití jména od: *1922*
>
> poznámka: *k zavedení úředního českého jména viz vyhlášku ministerstva
> vnitra č. 13/1923 Sb., bod 4.*
>
> **VAR:** hlavní část jména: *Fischern*
>
> jazyk: *němčina*
>
> **PREF: *Boží Dar*** *(Karlovy Vary, Česko)*
>
> jazyk: *čeština*
>
> **VAR 1:** hlavní část jména: *Gottesgab*
>
> jazyk: *němčina*
>
> **VAR 2:** hlavní část jména: *Theodosium*
>
> jazyk: *latina*

V případě jména, které se vyskytuje pouze v jednom dokumentu, přičemž
z textu nelze s jistotou stanovit znění daného výrazu v 1. pádě, je
možné přepsat jméno přímo z příslušného pramene ve tvaru, v jakém je
v tomto zdroji uveden, to znamená i v jiném než v 1. pádu
a s předložkou. Totéž platí i pro preferované označení, pokud se jméno
vyskytuje jen v jednom známém prameni.

> **Příklad:**
>
> **PREF: *Babice*** *(Praha-východ, Česko)*
>
> typ formy jména: *úřední*
>
> jazyk: *čeština*
>
> **VAR 1:** hlavní část jména: *de Babicz*
>
> typ formy jména: *historická/dřívější podoba*
>
> jazyk: *latina*
>
> datace použití jména od: *1381*
>
> datace použití jména do: *1381*
>
> **VAR 2:** hlavní část jména: *in villa Babiczich*
>
> typ formy jména: *historická/dřívější podoba*
>
> jazyk: *latina*
>
> datace použití jména od: *1381*
>
> datace použití jména do: *1381*
>
> zdroje informací (PP společný pro celou entitu): *Archiv český čili
> staré písemné památky české i moravské sebrané z archivů domácích
> i cizích. Díl XXXI. - První kniha provolací desk dvorských z let
> 1380-1394. Vyd. Gustav Friedrich. V Praze, 1921, s. 38 (zápis z roku
> 1381).*

#### Označení jako generovaný údaj

Jednotlivé části označení jsou do souhrnného „Označení“ generovány
automaticky dle následujícího pořadí spolu s oddělovači (hranaté závorky
označují prvky popisu):

**PREF i VAR:** \[hlavní část jména\] (\[geografický doplněk\] :
\[obecný doplněk\] : \[chronologický doplněk\])

### 12.3.2 Typ geografického objektu

**Povinnost:** povinný PP.

**Pravidla:** Provádí se výběr z číselníkové nabídky, který určuje
základní charakteristiku geografického objektu. Blíže **viz přílohu č.
10**.

### 12.3.3 Administrativní zařazení (hierarchická struktura)

**Povinnost:** povinný vztah za určitých okolností, v ostatních
případech doporučený.

**Pravidla:**

Vyjadřuje se formou vztahu/reference na jiný geografický objekt.

Nadřazená entita („administrativní zařazení“) slouží k vyjádření
primární hierarchie, není opakovatelná a zároveň nesmí být zaniklá.

Jako nadřazená entita se vždy určuje nejnižší identifikovatelná úroveň
v hierarchii entit podtřídy „administrativně či jinak lidmi vymezená
území“ či „vesmír a jeho části“, která plně popisovanou entitu obsáhne.
Detailněji je použití, včetně přesného vymezení typu geografických
objektů, které mohou být v rámci prvku popisu „administrativní zařazení“
uplatněny, popsáno **v příloze č. 10, kapitole Geografické objekty –
hierarchie administrativního zařazení**.

Uplatňuje se povinně pro všechny entity podtřídy „administrativně či
jinak lidmi vymezená území“.

Hierarchická struktura je přitom řešena následovně:

**1. Pro entity v Česku a na Slovensku** mohou být použity následující
typy geografických objektů v této hierarchii: stát \> kraj \> okres \>
obec nebo vojenský újezd \> část obce. V případě, že existuje pouze
jedna část obce totožného jména jako obec, záznam části obce se
nezakládá.

**2. U zahraničních entit buď:**

a\) mohou být použity následující typy geografických objektů v této
hierarchii: planeta Země \> kontinent/světadíl \> stát \>
administrativně vymezená vnitřní část státu \> obec \> část obce,

**nebo**

b\) je umožněno navázat archivní autoritní záznam obce nebo nižší
sídelní jednotky přímo na archivní autoritní záznam státu bez nutnosti
zadávat administrativně vymezenou vnitřní část státu, avšak za
předpokladu, že jsou vyplněny souřadnice. Archivní autoritní záznamy
ulice, nábřeží a náměstí musí být ve vztahu „administrativní zařazení“
napojeny na záznam geografického objektu typu obec.

**3. U zaniklých lokalit** (v Česku i v zahraničí) je umožněno navázat
archivní autoritní záznam entity na archivní autoritní záznam nejblíže
určitelné nadřazené entity bez ohledu na požadavek přesněji definovat
hierarchii.

U ostatních podtříd z této třídy je „administrativní zařazení“, na
rozdíl od geografického doplňku, doporučené.

### 12.3.4 Souřadnice

**Povinnost:** povinná část archivního autoritního záznamu za určitých
okolností, v ostatních případech doporučená.

**Pravidla:**

Uplatňuje se ve formě zápisu jako PP „Definiční bod“ nebo „Hranice“,
přičemž je možné použít obojí.

Vyplnění alespoň jedné z forem je povinné u entit podtřídy
„administrativně či jinak lidmi vymezená území“ mimo ČR, jejichž
archivní autoritní záznamy jsou ve vztahu „administrativní zařazení“
napojeny na archivní autoritní záznam geografického objektu typu „stát“.

U všech geografických entit je vyplnění tohoto PP důrazně doporučeno
(postačuje PP „Definiční bod“).

### 12.3.5 Vznik

**Povinnost:** doporučená část archivního autoritního záznamu.

**  
**

**Pravidla:**

U archivního autoritního záznamu entity třídy „geografický objekt“ se
dle způsobu vzniku volí mezi dvěma možnostmi:

a\) vznik,

b\) první písemná zmínka.

Pro výběr způsobu vzniku (dále též zjednodušeně „událost“) jsou
rozhodující tato kritéria: pokud je známo datum vzniku geografického
objektu nebo jej lze odhadnout, použije se událost „Vznik“. Pokud jde
o dataci formou první písemné zmínky, použije se událost „První písemná
zmínka“.

#### Událost Vznik

Vyplňuje se:

##### 1. Datace vzniku

**Povinnost:** doporučený PP.

**Pravidla:** Přesné datum vzniku geografického objektu. Není-li přesné
datum známo, může se uvést kvalifikovaný odhad.

##### 2. Vztahy spojené s událostí Vznik

**Povinnost:** nepovinné.

**Pravidla:**

a\) zakladatel/zřizovatel (vztah) – vazba na archivní autoritní záznam
(dále též jen „záznam“) zakladatele/zřizovatele,

b\) dokument (vztah) – vazba na záznam dokumentu, který se týká vzniku,

c\) entita související se vznikem (vztah) – vazba na záznam entit ze
všech tříd souvisejících se vznikem.

##### 3. Poznámka k události Vznik

**Povinnost:** nepovinný PP.

#### Událost První písemná zmínka

Vyplňuje se:

##### 1. Datace první písemné zmínky

**Povinnost:** doporučený PP.

**Pravidla:** datum první písemné zmínky o geografickém objektu.

##### 2. Vztahy spojené s událostí První písemná zmínka

**Povinnost:** nepovinné.

**Pravidla:** dokument (vztah) – vazba na záznam dokumentu, který
obsahuje první zmínku o geografickém objektu.

##### 3. Poznámka k události První písemná zmínka

**Povinnost:** nepovinný PP.

### 12.3.6 Zánik

**Povinnost:** povinná část archivního autoritního záznamu u zaniklých
geografických objektů.

**Pravidla:**

U archivního autoritního záznamu entity třídy „geografický objekt“ se
dle způsobu zániku volí mezi dvěma událostmi:

a\) zánik,

b\) poslední písemná zmínka.

Pro výběr události je rozhodující: pokud je známo datum zániku
geografického objektu nebo jej lze odhadnout, použije se událost
„Zánik“. Pokud jde o dataci formou poslední písemné zmínky, použije se
událost „Poslední písemná zmínka“.

#### Událost Zánik

Vyplňuje se:

##### 1. Datace Zániku

**Povinnost:** doporučený PP.

**Pravidla:** Přesné datum zániku geografického objektu. Není-li přesné
datum známo, může se uvést kvalifikovaný odhad.

##### 2. Vztahy spojené s událostí Zánik

**Povinnost:** nepovinný PP.

**Pravidla:**

a\) dokument (vztah) – vazba na záznam dokumentu, který se týká zániku,

b\) entita související se zánikem (vztah) – vazba na záznam entit ze
všech tříd souvisejících se zánikem.

##### 3. Typ zániku

**Povinnost:** povinný PP u zaniklých objektů v případě, že není
vyplněna ani datace zániku, ani vztah spojený se zánikem, ani poznámka
k zániku , v ostatních případech doporučený.

**Pravidla:** Výběr z číselníkové nabídky:

a\) zánik změnou; např. sloučení, rozdělení – nepoužívá se u sídel, tj.
geografických objektů typu „obec“ a hierarchicky nižších,

b\) zánik zrušením – nepoužívá se u sídel, tj. geografických objektů
typu „obec“ a hierarchicky nižších,

c\) zánik z důvodu vysídlení po roce 1945,

d\) zánik z důvodu výstavby vodního díla,

e\) zánik z důvodu zřízení vojenského prostoru,

f\) zánik z důvodu průmyslové činnosti,

g\) zánik z důvodu důlní činnosti,

h\) zánik z důvodu vojenského konfliktu,

i\) zánik z důvodu živelní pohromy,

j\) jiný typ zániku – do poznámky se uvede bližší určení; bez poznámky
je tato hodnota chápána jako nespecifikovaný zánik.

##### 4. Poznámka k události Zánik

**Povinnost:** nepovinný PP.

#### Událost Poslední písemná zmínka

Vyplňuje se:

##### 1. Datace poslední písemné zmínky

**Povinnost:** doporučený PP.

**Pravidla:** datum poslední písemné zmínky o geografickém objektu.

##### 2. Vztahy spojené s událostí Poslední písemná zmínka

**Povinnost:** nepovinné.

**Pravidla:** dokument (vztah) – vazba na záznam dokumentu, který
obsahuje poslední zmínku o geografickém objektu.

##### 3. Poznámka k události Poslední písemná zmínka

**Povinnost:** nepovinný PP.

### 12.3.7 Stručná charakteristika

**Povinnost:** doporučený PP.

**Pravidla:**

Slovní charakteristika entity, eventuálně upřesňující výše uvedené
údaje.

Znění stručné charakteristiky se vytváří analogicky podle příkladů
obsažených **v příloze č. 10**.

### 12.3.8 Popis (geografického objektu)

**Povinnost:** nepovinný PP.

**Pravidla:** popis současného stavu geografického objektu v širším
rozsahu než umožňuje stručná charakteristika.

### 12.3.9 Dějiny (geografického objektu)

**Povinnost:** nepovinný PP.

**Pravidla:** popis historie geografického objektu, například správního
vývoje.

### 12.3.10 Události a vztahy (geografické objekty)

**Povinnost:** nepovinné.

**Pravidla:**

Vyplňuje se:

##### 1. historické milníky (událost):

a\) historický milník (vztah) – vazba na záznam jiné entity, která
charakterizuje historický milník (požár, udělení práva, např. trhů,
městských práv, novodobé povýšení obce na městys či na město apod.).

##### 2. udělení ocenění (událost):

a\) ceremoniál ocenění (vztah) – vazba na záznam události ocenění,

b\) udělovatel (vztah) – vazba na záznam entity, která udělila ocenění,

c\) ocenění (vztah) – vazba na záznam díla/výtvoru představujícího
ocenění.

##### 3. související entity (vztahy mimo událost):

a\) příslušnost k (vztah) – vazba na záznam geografického objektu; pro
vytváření paralelních hierarchií (např. historických v případě napojení
záznamu obce na záznam historického okresu či kraje), nebo současných –
v případě napojení záznamu části obce na záznam katastrálního území,
obdobně napojení hory na pohoří (Sněžka → Krkonoše), ostrova na
souostroví (Tenerife → Kanárské ostrovy) apod.,

b\) majitel, držitel (vztah) – vazba na záznam majitele, držitele, např.
feudálního majitele ze třídy „osoba/bytost“ nebo „rod/rodina“
u poddanské vesnice, městečka apod.,

c\) partner (vztah) – vazba na záznam partnerské entity (družba
a partnerství měst a obcí),

d\) pojmenováno po (vztah) – vazba na záznam entity, po které byla nebo
je popisovaná entita pojmenována,

e\) tematický celek (vztah) – vazba na záznam entity typu obecný pojem.

### 12.3.11 Kódované údaje (identifikátory)

**Povinnost:** povinná část záznamu entity za určitých okolností,
v ostatních případech doporučená.

**Pravidla:** u současných administrativně vymezených geografických
objektů v ČR je povinné uvádět kód RÚIAN pouze do úrovně „část obce“;
u nižších úrovní je doporučen.