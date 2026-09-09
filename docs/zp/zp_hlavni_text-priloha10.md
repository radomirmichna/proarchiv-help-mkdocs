# PŘÍLOHY

## Příloha č. 10 Příklady entit dle jednotlivých tříd

**Struktura a formátování písma příkladů**

Preferované označení (PREF):

varianta 1: ***hlavní část jména,** vedlejší část jména, titul před a za
jménem (doplněk), stručná charakteristika*

varianta 2: ***hlavní část jména.** vedlejší část jména (doplněk),
stručná charakteristika*

varianta 3: *hlavní část jména (doplněk), stručná charakteristika*

Variantní označení (VAR):

varianta 1: *hlavní část jména*, vedlejší část jména, titul před a za
jménem

varianta 2: *hlavní část jména.* vedlejší část jména

varianta 3: *hlavní část jména*

**Poznámka k VAR**

V příkladech variantních označení entit nejsou vždy uváděny všechny
myslitelné varianty, jedná se o ilustrativní příklady možných řešení za
účelem demonstrace různého způsobu zápisu, který zabraňuje duplicitám
a usnadňuje vyhledávání, byť většinou nejde o oficiální a všeobecně
známé názvy. Smyslem VAR je především umožnit nalézt požadovanou entitu,
přestože uživatel nezná její přesné jméno, a dále pak zabránit vytváření
duplicitních archivních autoritních záznamů.

### Třída Osoba/bytost

Příklad 1 – archivní autoritní záznam entity pro ostatní role
(s výjimkou role původce – viz příklad 2)

|                                                                                                   |                                                                  |
|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| ***Potůček**, Jiří (1919-1942), protifašistický bojovník, voják, výsadkář, člen skupiny Silver A* |                                                                  |
| PREF: Hlavní část jména                                                                           | Potůček                                                          |
| PREF: Vedlejší část jména                                                                         | Jiří                                                             |
| PREF: Chronologický doplněk                                                                       | 1919-1942                                                        |
| PREF: Obecný doplněk                                                                              | *u této entity se neuvádí*                                       |
| VAR: Hlavní část jména                                                                            | Tolar                                                            |
| Stručná charakteristika                                                                           | protifašistický bojovník, voják, výsadkář, člen skupiny Silver A |
| Vznik: typ                                                                                        | narození                                                         |
| Vznik: datace                                                                                     | 12\. 7. 1919                                                     |
| Zánik: typ                                                                                        | úmrtí                                                            |
| Zánik: datace                                                                                     | 2\. 7. 1942                                                      |

Příklad 2 – archivní autoritní záznam entity jakožto původce

<table>
<colgroup>
<col style="width: 36%" />
<col style="width: 63%" />
</colgroup>
<tbody>
<tr class="odd">
<td colspan="2"><em><strong>Potůček</strong>, Jiří (1919-1942), protifašistický bojovník, voják, výsadkář, člen skupiny Silver A</em></td>
</tr>
<tr class="even">
<td>PREF: Hlavní část jména</td>
<td>Potůček</td>
</tr>
<tr class="odd">
<td>PREF: Vedlejší část jména</td>
<td>Jiří</td>
</tr>
<tr class="even">
<td>PREF: Chronologický doplněk</td>
<td>1919-1942</td>
</tr>
<tr class="odd">
<td>PREF: Typ formy jména</td>
<td>úřední</td>
</tr>
<tr class="even">
<td>VAR: Hlavní část jména</td>
<td>Tolar</td>
</tr>
<tr class="odd">
<td>VAR: Typ formy jména</td>
<td>přezdívka/zlidovělá podoba</td>
</tr>
<tr class="even">
<td>Stručná charakteristika</td>
<td>protifašistický bojovník, voják, výsadkář, člen skupiny Silver A</td>
</tr>
<tr class="odd">
<td>Vznik: způsob vzniku</td>
<td>narození</td>
</tr>
<tr class="even">
<td>Vznik: datace</td>
<td>12. 7. 1919</td>
</tr>
<tr class="odd">
<td>Vznik: vztah – specifikace „místo“</td>
<td>Brunico (Itálie)</td>
</tr>
<tr class="even">
<td>Zánik: způsob zániku</td>
<td>úmrtí</td>
</tr>
<tr class="odd">
<td>Zánik: datace</td>
<td>2. 7. 1942</td>
</tr>
<tr class="even">
<td>Zánik: vztah – specifikace „místo“</td>
<td>Trnová (Pardubice, Pardubice, Česko)</td>
</tr>
<tr class="odd">
<td>Životopis</td>
<td><p>Narodil se 12. července 1919 v Brunicu (Brunecku) v Jižním Tyrolsku. Otec Vilém Potůček byl…</p>
<p>…</p>
<p>V létě 1940 byl vybrán do výcviku pro zvláštní úkoly…</p>
<p>…</p>
<p>Krátce po půlnoci 29. prosince 1941 byl společně s velitelem skupiny Alfrédem Bartošem a Josefem Valčíkem vysazen u obce Senice poblíž Poděbrad. Na území protektorátu obsluhoval radiostanici s krycím názvem Libuše.</p>
<p>….</p>
<p>Dne 5. září 1945 byl postupně in memoriam povýšen do hodnosti podporučíka…</p></td>
</tr>
<tr class="even">
<td>Související entity – specifikace „obor působnosti“</td>
<td>odboj</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „významné aktivity“</td>
<td>Operace Silver A</td>
</tr>
</tbody>
</table>

#### Podtřída fyzická osoba

###### Standardní zápis příjmení a křestního jména osoby, preferováno první získané příjmení, pod nímž je osoba nejvíce známa:

> Příklad O1: ***Janů**, Marie (1921-2014)*, *nakladatelská redaktorka,
> překladatelka z francouzštiny a němčiny*
>
> VAR: *Veselá*, Marie; *Janů-Veselá*, Marie; *Veselá-Janů*, Marie;
> *Pluhařová-Janů*, Marie; *Pluhařová*, Marie; *Stroffová*, Marie

###### Pseudonym preferovaný před občanským jménem:

> O2: ***John**, Jaromír, prof. (1882-1952), spisovatel, novinář,
> středoškolský a vysokoškolský učitel, výtvarný estetik a kritik,
> překladatel z němčiny*
>
> VAR: *Markalous*, Bohumil, prof.

###### Občanské jméno preferované před krycím jménem:

> O3: ***Potůček**, Jiří (1919-1942), protifašistický bojovník, voják,
> výsadkář, člen skupiny Silver A*
>
> VAR: *Tolar*

###### Osoba s akademickými tituly:

> O4: ***Bechyně**, Stanislav, prof. Dr. Ing. (1887-1973), zakladatel
> betonového stavitelství, technický vedoucí u firmy Skorkovský,
> profesor ČVUT, akademik ČSAV*

###### Panovníci, příklad obecného doplňku:

> O5: ***Břetislav I.** (kníže : asi 1005-1055), český kníže z rodu
> Přemyslovců*
>
> VAR: *Achilleus Český*; *Český Achilleus*
>
> O6: ***Lucemburský**, Jan (král : 1296-1346), český král, lucemburský
> hrabě a titulární polský král*
>
> VAR: *Jan Lucemburský*; *Johann von Böhmen*; *von Luxemburg*, Johann;
> *Johannes der Blinde*; *de Luxembourg et de Bohême*, Jean; *Jean
> l'Aveugle*; *John of Bohemia*; *John the Blind*
>
> O7: ***z Poděbrad**, Jiří (král : 1420-1471), český král*
>
> VAR: *Jiří z Poděbrad*; *Jiřík z Poděbrad*; *z Kunštátu a Poděbrad*,
> Jiří; *husitský král*; *Podiebradius*, Georgius
>
> O8: ***Matyáš Korvín** (král : 1443-1490), český a uherský král*
>
> VAR: *Hunyadi*, Mátyás; *Matej Korvín*
>
> O9: ***František I. Francouzský** (král : 1494-1547), francouzský
> král*
>
> VAR: *François Ier de France*; *le Roi-Chevalier*; *Rytířský král*
>
> O10: ***Alžběta II.** (královna : 1926-2022), britská královna*
>
> VAR: *Elizabeth II*; *Elizabeth Alexandra Mary*

###### Osoba šlechtice, vládnoucího nesuverénnímu území vs. osoba šlechtice v roli panovníka suverénního státu:

> O11: ***z Lichtenštejna**, Josef Václav (1696-1772), šlechtic,
> lichtenštejnský kníže, působil v armádě*
>
> VAR: *z Lichtenštejna*, Josef Václav Karel; *von Liechtenstein*, Josef
> Wenzel; *von Liechtenstein*, Josef Wenzel Lorenz; *otec rakouského
> dělostřelectva*
>
> vs.
>
> O12: ***z Lichtenštejna**, František I. (kníže : 1853-1938), panovník
> Lichtenštejnského knížectví, diplomat*
>
> VAR: *von Liechtenstein*, Franz I.
>
> *Poznámka: Obě osoby vládly Lichtenštejnskému knížectví, které se však
> stalo suverénním státním útvarem až v roce 1806. Tudíž František I.
> z Lichtenštejna je uveden s obecným doplňkem „kníže“ jakožto titulární
> označení hlavy státu, kdežto Josef Václav nikoli, jeho knížecí titul
> je uveden až ve stručné charakteristice.*

###### Papežové – nepreferované občanské jméno, přezdívka, příklad obecného doplňku:

> O13: ***Benedikt XVI.** (papež : 1927-), emeritní papež*
>
> VAR: *Ratzinger*, Joseph; *Ratzinger*, Josef; *Benedetto XVI.*;
> *Benedict XVI.*; *Boží rotvajler*
>
> O14: ***Pius X.** (papež a svatý : 1835-1914), 257. papež katolické
> církve*
>
> VAR: *Sarto*, Giuseppe Melchiorre; *Sarto*, Josef Melchior

###### Osoba bez příjmení:

> O15: ***Klaret** (asi 1320-1370), katolický kněz, mistr pražské
> univerzity, lékař, lexikograf*
>
> VAR: *Bartoloměj z Chlumce*; *z Chlumce*, Bartoloměj; *Claretus de
> Solentia*; *de Solentia*, Claretus
>
> O16: ***Theodorik** (působnost od 1348-asi 1381), malíř*
>
> VAR: *Mistr Theodorik*

###### Osoba bez příjmení, preferována latinská podoba jména, neznámé datum narození:

> O17: ***Thomas Cisterciensis** (?-asi 1190), cisterciácký mnich,
> teolog ve Francii*
>
> VAR: *Cisterciensis,* Thomas; *Thomas of Vancelles*; *of Vancelles*,
> Thomas; *the Cistercian,* Thomas; *Thomas the Cistercian*; *Thomas of
> Perseigne*; *of Perseigne*, Thomas

###### Osoba bez příjmení, zapsaná jako „řečený“ apod.:

> O18: ***Jan ze Dvorce** (působnost 1400), poddaný na statku Borovany
> v jižních Čechách*
>
> VAR: *Jan ze Dvorce Erlick*; *Jan ze Dvorce řečený Erlick*

###### Osoba bez příjmení, šlechtic:

> O19: ***z Rožmberka**, Jan II. (asi 1429-1472), šlechtic, vrchní
> hejtman ve Slezsku, nejvyšší komorník*
>
> VAR: *Jan II. z Rožmberka*; *Jan II. Pokojný*

###### Osoby (nešlechticové) se strukturovaným jménem:

> O20: ***Vavřinec Leander Rvačovský ze Rvačova** (1525-asi 1590),
> utrakvistický kněz, písař, narozen pravděpodobně v Roudnici nad Labem*
>
> VAR: *Rvačovský ze Rvačova,* Vavřinec Leander; *ze Rvačova*, Vavřinec
> Leander Rvačovský
>
> O21: ***Havlíček Borovský**, Karel (1821-1856), básník, novinář
> a politik, literární kritik, překladatel*
>
> VAR: *Borovský*, Karel; *Havlíček-Borovský*, Karel; *Havlíček*, Karel;
> *Hawlíček Borovský*, Karel

###### Preferované označení u nobilitované osoby při upřednostnění německé jazykové varianty:

> O22: ***Rebensteiger von Blankenfeld**, August (působnost od
> 1851-působnost do 1920), svobodný pán, okresní hejtman v Poděbradech
> a Chrudimi*
>
> VAR: *von Blankenfeld*, August Rebensteiger; *Rebensteiger*, August;
> *z Blankenfeldu*, August Rebensteiger; *Rebensteiger z Blankenfeldu*,
> August

###### Česká světice:

> O23: ***Anežka Česká** (svatá : asi 1205-1282), dcera českého krále
> Přemysla Otakara I., spoluzakladatelka a abatyše kláštera klarisek
> v Praze, zemská patronka*
>
> VAR: *Anežka Přemyslovna*; *Přemyslovna,* Anežka; *svatá Anežka Česká*

###### Světec, cizinec s českou variantou jména:

> O24: ***Jan Zlatoústý** (arcibiskup a svatý : asi 347-407), patriarcha cařihradský,
> církevní učitel a spisovatel*
>
> VAR: *Zlatoústý*, Jan; *Ióannés Chrýsostomos*; *svatý Jan Zlatoústý*;
> *sanctus Johannes Chrysostomos*

###### Rozlišení více světců (pro zjednodušení nejsou vyjmenováni všichni svatí Alexandrové):

> O25: ***Alexandr** (svatý : ?-asi 305), mučedník ve středomakedonské
> Pydně, svátek 14. 3.*
>
> O26: ***Alexandr** (svatý : ?-178), lyonský mladík, umučen se svatým
> Epipodem, svátek 22. 4.*
>
> O27: ***Alexandr** (svatý : ?-asi 119), voják, zachránil svatou
> Antonii z Kardamy, svátek 3. 5.*

###### Rozlišení více osob se stejným jménem v rámci rodu, preferovaná česká jazyková varianta:

> O28: ***Schmoranz**, František (1814-1902), stavitel ve Slatiňanech,
> městský architekt v Chrudimi, krajský konzervátor památek*
>
> VAR: *Schmoranz*, Franz; *Šmoranc*, František; *Schmoranz*, František
> starší
>
> O29: ***Schmoranz**, František (1845-1892), architekt v Egyptě, ve
> Vídni a v Čechách, rakouský komisař na světové výstavě v Paříži 1878,
> inspektor textilních průmyslových škol, ředitel C. k.
> umělecko-průmyslové školy v Praze*
>
> VAR: *Schmoranz*, Franz; *Schmoranz*, František mladší
>
> O30: ***Schmoranz**, Gustav (1858-1930), architekt, pedagog C. k.
> umělecko-průmyslové školy v Praze, kunsthistorik, dramatik,
> překladatel, ředitel Národního divadla v Praze*
>
> O31: ***Schmoranz**, František (1889-1967), ředitel lihovaru
> a sportovní funkcionář v Chrudimi*

###### Cizinka s českou variantou jména, několika cizojazyčnými variantami, nepanující členka panovnického rodu:

> O32: ***Štěpánka Belgická** (1864-1945), belgická princezna,
> rakousko-uherská korunní princezna*
>
> VAR: *Stéphanie Clotilde Louise Herminie Marie Charlotte de Belgique*;
> *Stefanie Rakouská*; *Stéphanie de Belgique*; *Stéphanie de
> Saxe-Cobourg et Gotha*; *Stephanie von Belgien Kronprinzessin*;
> *Štefanie Belgická*; *Stefánie Belgická*; *Stefanie Belgická*

###### Cizinka s preferovanou českou variantou jména, šlechtickým titulem a přezdívkou:

> O33: ***Thatcherová**, Margaret (1925-2013), britská politička,
> premiérka a právnička, baronka*
>
> VAR: *Thatcher*, Margaret; *Thatcher*, Margaret Hilda; *Roberts*,
> Margaret; *Thatcherová*, Margaret; *Iron Lady*; *Železná lady*

###### Cizinka s preferovanou cizojazyčnou variantou jména:

> O34: ***Christie**, Agatha (1890-1976), anglická prozaička, autorka
> kriminálních a detektivních příběhů*
>
> VAR: *Mallowanová*, Agatha Mary Clarissa; *Miller*, Agatha Mary
> Clarissa; *Westmacott*, Mary; *Agatha Mary Clarissa lady Mallowanová*

###### Nejistá podoba příjmení známá z jediného zdroje informace, neznámé bližší životopisné údaje:

> O35: ***Stycký**, Václav (působnost 1800), řemeslník v Bělé čp. 69
> v okrese Rychnov nad Kněžnou*
>
> VAR: *Secký*, Václav

###### Nejisté pořadí jména:

> O36: ***Petr**, Pavel (působnost 1800), řemeslník v Bělé v okrese
> Rychnov nad Kněžnou*
>
> VAR: *Pavel*, Petr

###### Osoba s nejistou preferencí podoby jména:

> O37: ***Nowotny**, Georg (působnost 1800), řemeslník v Bělé v okrese
> Rychnov nad Kněžnou*
>
> VAR: *Novotný*, Jiří

###### Osoby, o nichž není známo více údajů, ale evidují se:

> O38: ***Šmíd**, Karel (působnost 1890), předseda Sportovního klubu
> Hlinsko v okrese Chrudim*
>
> O39: ***Babáček**, Kajetán Ing. (působnost 1910), profesor češtiny na
> německém gymnáziu v Karlových Varech*
>
> O40: ***Růžička**, František (působnost 1938), žadatel o vydání
> osvědčení o státním občanství, bytem v Hlinsku v okrese Chrudim*
>
> O41: ***Prokop,** Ing. (působnost 1963), autor textu mapy „Sčítání
> dopravy: celoroční průměr za 24 hodin - 03 Západočeský kraj
> 1962-1963“*

###### Ruské jméno:

> O42: ***Gorbačov**, Michail Sergejevič (prezident : 1931-), ruský
> politik, nejvyšší představitel Sovětského svazu v letech 1985-1991*
>
> VAR: *Gorbačev*, Michail Sergejevič; *Горбачёв*, Михаил Сергеевич*;
> Горбачев*, Михаил Сергеевич; *Gorbachev*, Mikhail

###### Tibetský dalajlama:

> O43: ***Gendündub** (1391-1474), první tibetský dalajlama*
>
> VAR: དགེ་འདུན་གྲུབ; *Dge-’dun-grub*; *Gendun Drup*; *Gendun Drub*;
> *Kundun Drup*; པད་མ་རྡོ་རྗེ; *Pema Dorje*

#### Podtřída fiktivní fyzická osoba

> O44: ***Achilleus** (mytologický hrdina), postava z řecké mytologie,
> syn bohyně Thetis a krále Pélea, účastník Trojské války*
>
> VAR: *Achilles*; *Achiles*; *Achilleas*; *Achil*; Άχιλλεύς
>
> O45: ***Lear** (literární postava), postava ze Shakespearovy divadelní
> hry*
>
> VAR: *Král* *Lear*

#### Podtřída bytost

> O46: ***Héra** (bohyně), nejvyšší starověká řecká bohyně*
>
> VAR: *Hera*; Ήρα
>
> O47: ***Šemík** (mytologické zvíře), kůň z české mytologie*

#### Podtřída zvíře

> O48: ***Delfín** (kůň : působnost 1937), kůň Policejního ředitelství
> v Praze*
>
> O49: ***Lajka** (pes : asi 1954-1957), fena, první živý tvor
> pocházející z planety Země vypuštěný na oběžnou dráhu*
>
> O50: ***Laky z Dače** (pes : 2017-), chovná fena plemene shetlandský
> ovčák*

### Třída Rod/větev rodu

Poznámka: V dalším textu je pro zjednodušení používáno jen slovo „rod“,
nikoli slovní spojení „rod/rodina“.

Příklad 1 – archivní autoritní záznam entity pro ostatní role
(s výjimkou role původce – viz příklad 2)

|                                                                                  |                                            |
|----------------------------------------------------------------------------------|--------------------------------------------|
| ***Rožmberkové** (rod/rodina : působnost od 12. st.-1611), český šlechtický rod* |                                            |
| PREF: Hlavní část jména                                                          | Rožmberkové                                |
| PREF: Chronologický doplněk                                                      | působnost od 12. st.-1611                  |
| PREF: na místě obecného doplňku se automaticky generuje vyjádření podtřídy       | rod/rodina                                 |
| VAR: Hlavní část jména                                                           | páni z Rožmberka                           |
| VAR: Hlavní část jména                                                           | Rosenberg                                  |
| Stručná charakteristika                                                          | český šlechtický rod                       |
| Vznik: způsob vzniku                                                             | působnost od                               |
| Vznik: datace                                                                    | 12\. století                               |
| Zánik: způsob zániku                                                             | úmrtí posledního známého člena rodu/rodiny |
| Zánik: datace                                                                    | 1611                                       |

Příklad 2 – archivní autoritní záznam entity jakožto původce

|                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                     |
|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ***Rožmberkové** (rod/rodina : působnost od 12. st.-1611), český šlechtický rod* |                                                                                                                                                                                                                                                                                                                                                                                                                     |
| PREF: Hlavní část jména                                                          | Rožmberkové                                                                                                                                                                                                                                                                                                                                                                                                         |
| PREF: Chronologický doplněk                                                      | působnost od 12. st.-1611                                                                                                                                                                                                                                                                                                                                                                                           |
| PREF: Typ formy jména                                                            | úřední                                                                                                                                                                                                                                                                                                                                                                                                              |
| VAR: Hlavní část jména                                                           | páni z Rožmberka                                                                                                                                                                                                                                                                                                                                                                                                    |
| VAR: Hlavní část jména                                                           | z Rožmberka                                                                                                                                                                                                                                                                                                                                                                                                         |
| VAR: Hlavní část jména                                                           | Rosenberg                                                                                                                                                                                                                                                                                                                                                                                                           |
| VAR: Hlavní část jména                                                           | Herren von Rosenberg                                                                                                                                                                                                                                                                                                                                                                                                |
| VAR: Hlavní část jména                                                           | Rosenberg family                                                                                                                                                                                                                                                                                                                                                                                                    |
| Stručná charakteristika                                                          | český šlechtický rod                                                                                                                                                                                                                                                                                                                                                                                                |
| Vznik: způsob vzniku                                                             | působnost od                                                                                                                                                                                                                                                                                                                                                                                                        |
| Vznik: datace                                                                    | 12\. století                                                                                                                                                                                                                                                                                                                                                                                                        |
| Zánik: způsob zániku                                                             | úmrtí posledního známého člena rodu/rodiny                                                                                                                                                                                                                                                                                                                                                                          |
| Zánik: datace                                                                    | 1611                                                                                                                                                                                                                                                                                                                                                                                                                |
| Zánik: vztah – specifikace „poslední známý člen rodu/rodiny“                     | z Rožmberka, Petr Vok (1539-1611)                                                                                                                                                                                                                                                                                                                                                                                   |
| Dějiny                                                                           | Starobylý český šlechtický rod, jehož členové zastávali významné funkce u královského a říšského císařského dvora. Znakem rodu byla červená pětilistá růže ve stříbrném poli. Rožmberkové vlastnili rozsáhlý majetek v jižních Čechách, kde jsou dodnes patrné stopy po jejich stavební a hospodářské činnosti. Rodovými sídly byly hrad v Rožmberku nad Vltavou, hrad a zámek v Českém Krumlově a zámek v Třeboni. |
| Související entity – specifikace „sídlo“                                         | Rožmberk nad Vltavou (Český Krumlov, Česko)                                                                                                                                                                                                                                                                                                                                                                         |
| Související entity – specifikace „sídlo“                                         | Český Krumlov (Český Krumlov, Česko)                                                                                                                                                                                                                                                                                                                                                                                |
| Související entity – specifikace „sídlo“                                         | Třeboň (Jindřichův Hradec, Česko)                                                                                                                                                                                                                                                                                                                                                                                   |
| Související entity – specifikace „vazba na objekt“                               | Rožmberk (Rožmberk nad Vltavou, Rožmberk nad Vltavou, Český Krumlov, Česko : hrad)                                                                                                                                                                                                                                                                                                                                  |
| Související entity – specifikace „vazba na objekt“                               | Český Krumlov (Český Krumlov, Český Krumlov, Česko : hrad a zámek)                                                                                                                                                                                                                                                                                                                                                  |
| Související entity – specifikace „vazba na objekt“                               | Třeboň (Třeboň, Jindřichův Hradec, Česko : zámek)                                                                                                                                                                                                                                                                                                                                                                   |

#### Podtřída rod, rodina

###### Český panovnický rod:

> Příklad R1: ***Přemyslovci** (rod/rodina : 9. st.-1306)*, *český
> panovnický rod*

###### Původem cizí rody s existující českou variantou jména:

> R2: ***Habsburkové** (rod/rodina : 11. st.-1740)*, *evropský
> panovnický rod*
>
> VAR: *Habsburg*; *House of Habsburg*
>
> R3: ***Habsburkové-Lotrinští** (rod/rodina : 1737-)*, *evropský
> panovnický rod*
>
> VAR: *Habsburg*; *House of Habsburg*
>
> R4: ***Buquoyové** (rod/rodina : 11. st.-)*, *šlechtický rod původem
> z Francie*
>
> VAR: *de Boucquoi*; *de Bucquoy*; *de Longueval*; *von Buquoy*

###### Původem cizí rody bez existující české varianty jména:

> R5: ***von Bülow** (rod/rodina : 13. st.-)*, *šlechtický rod původem
> ze severního Německa*
>
> R6: ***Geyer von Geyersperg** (rod/rodina : působnost od 14.
> st.-1805)*, *rakouský šlechtický rod původem z Frank*
>
> VAR: *Geier*; *Geyer von Osterburg*

###### Rod s více variantami jména:

> R7: ***Mírkové ze Solopisk** (rod/rodina : asi 1406-18. <span style="color:red">st.</span>)*,
> *šlechtický rod původem z východních Čech*
>
> VAR: *Mírkové ze Solopisk a na Plaňanech*; *Mírkové ze Solopysk*

###### Česká rodina charakterizovaná oborem působnosti:

> R8: ***Mánesovi** (rod/rodina : působnost od asi 18. st.-působnost do
> 1880)*, *rodina výtvarných umělců*

###### Rodina, o níž není známo více údajů, ale eviduje se:

> R9: ***Sommerovi** (rod/rodina : působnost 1928), objednatelé
> rozšíření domu čp. 61 v obci Úlice*

#### Podtřída větev rodu

> R10: ***Schwarzenbergové**. Orlická větev (větev rodu : 1802-)*,
> *větev šlechtického rodu s rodovým sídlem v Čechách*
>
> VAR: *orlická větev Schwarzenbergů*; *sekundogenitura Schwarzenberků*
>
> R11: ***Nosticové.** Rokytnická větev (větev rodu : 1608-1890)*,
> *větev šlechtického rodu působícího ve Slezsku a Čechách*
>
> VAR: *z Nostic-Rokytnic*; *von Nostitz-Rokytnic*; *rokytnická větev
> Nosticů*
>
> R12: ***Bourboni.** Parmská větev (větev rodu : 1720-), jedna z větví
> dynastie Bourbonů vládnoucí v Parmském vévodství*
>
> VAR: *Bourbonsko-parmská dynastie*; *Bourbon-Parma*; *Borbone di
> Parma*

#### Podtřída fiktivní rod, fiktivní rodina

> R13: ***Lannisterové** (fiktivní rod/rodina), rod z knihy a seriálu
> Hra o trůny*
>
> VAR: *Lannisterové z Casterlyovy skály*; *House Lannister*
>
> R14: ***Simpsonovi** (fiktivní rod/rodina), rodina z amerického
> animovaného seriálu*
>
> VAR: *Simpsons*; *The Simpsons*

### Třída Korporace

Poznámka: K jurisdikcím **viz dále přílohu č. 11**.

Příklad 1 – archivní autoritní záznam entity pro ostatní role
(s výjimkou role původce – viz příklad 2)

|                                                              |                                          |
| ------------------------------------------------------------ | ---------------------------------------- |
| ***Okresní úřad Karlovy Vary** (Karlovy Vary, Karlovy Vary, Česko : 1928-1938), regionální orgán politické státní správy* |                                          |
| PREF: Hlavní část jména                                      | Okresní úřad Karlovy Vary                |
| PREF: Vedlejší část jména                                    |                                          |
| PREF: Geografický doplněk                                    | Karlovy Vary, Karlovy Vary, Česko        |
| PREF: Chronologický doplněk                                  | 1928-1938                                |
| PREF: Obecný doplněk                                         |                                          |
| VAR: Hlavní část jména                                       | Okresní úřad v Karlových Varech          |
| VAR: Hlavní část jména                                       | Bezirksbehörde in Karlsbad               |
| Stručná charakteristika                                      | regionální orgán politické státní správy |
| Vznik: způsob vzniku                                         | vznik                                    |
| Vznik: datace                                                | 1\. 12. 1928                             |
| Zánik: způsob zániku                                         | zánik                                    |
| Zánik: datace                                                | 4\. 10. 1938                             |
| Vztah – specifikace „sídlo“                                  | Karlovy Vary (Karlovy Vary, Česko)       |

Příklad 2 – archivní autoritní záznam entity jakožto původce

<table>
<colgroup>
<col style="width: 36%" />
<col style="width: 63%" />
</colgroup>
<tbody>
<tr class="odd">
<td colspan="2"><em><strong>Okresní úřad Karlovy Vary</strong> (Karlovy Vary, Karlovy Vary, Česko : 1928-1938), regionální orgán politické státní správy</em></td>
</tr>
<tr class="even">
<td>PREF: Hlavní část jména</td>
<td>Okresní úřad Karlovy Vary</td>
</tr>
<tr class="odd">
<td>PREF: Vedlejší část jména</td>
<td></td>
</tr>
<tr class="even">
<td>PREF: Geografický doplněk</td>
<td>Karlovy Vary, Karlovy Vary, Česko</td>
</tr>
<tr class="odd">
<td>PREF: Chronologický doplněk</td>
<td>1928-1938</td>
</tr>
<tr class="even">
<td>PREF: Obecný doplněk</td>
<td></td>
</tr>
<tr class="odd">
<td>PREF: Typ formy jména</td>
<td>zjednodušená podoba</td>
</tr>
<tr class="even">
<td>PREF: Jazyk jména</td>
<td>čeština</td>
</tr>
<tr class="odd">
<td>VAR: Hlavní část jména</td>
<td>Okresní úřad v Karlových Varech</td>
</tr>
<tr class="even">
<td>VAR: Typ formy jména</td>
<td>úřední</td>
</tr>
<tr class="odd">
<td>VAR: Jazyk jména</td>
<td>čeština</td>
</tr>
<tr class="even">
<td>VAR: Hlavní část jména</td>
<td>Bezirksbehörde in Karlsbad</td>
</tr>
<tr class="odd">
<td>VAR: Typ formy jména</td>
<td>úřední</td>
</tr>
<tr class="even">
<td>VAR: Jazyk jména</td>
<td>němčina</td>
</tr>
<tr class="odd">
<td>Stručná charakteristika</td>
<td>regionální orgán politické státní správy</td>
</tr>
<tr class="even">
<td>Vznik: způsob vzniku</td>
<td>vznik</td>
</tr>
<tr class="odd">
<td>Vznik: typ</td>
<td>vznik změnou předchůdce</td>
</tr>
<tr class="even">
<td>Vznik: datace</td>
<td>1. 12. 1928</td>
</tr>
<tr class="odd">
<td>Vznik: vztah – specifikace „předchůdce“</td>
<td>Okresní správa politická Karlovy Vary (Karlovy Vary, Česko : 1919-1928)</td>
</tr>
<tr class="even">
<td>Vznik: vztah – specifikace „dokument“</td>
<td>Zákon č. 125/1927 Sb., o organizaci politické správy</td>
</tr>
<tr class="odd">
<td>Zánik: způsob zániku</td>
<td>zánik</td>
</tr>
<tr class="even">
<td>Zánik: typ</td>
<td>zánik zrušením/změnou</td>
</tr>
<tr class="odd">
<td>Zánik: datace</td>
<td>4. 10. 1938</td>
</tr>
<tr class="even">
<td>Zánik: vztah – specifikace „nástupce“</td>
<td>Sudetendeutsche Bezirkshauptmannschaft (Karlovy Vary, Karlovy Vary, Česko : 1938)</td>
</tr>
<tr class="odd">
<td>Kódované údaje (identifikátory)</td>
<td></td>
</tr>
<tr class="even">
<td>Dějiny</td>
<td><p>Mezníkem ve vývoji politické správy Československé republiky byl zákon o organizaci politické správy (organizační zákon) č. 125/1927 Sb., který vstoupil v českých zemích v platnost 1. 12. 1928. Do té doby samostatné okresní správní komise byly spojeny s okresními úřady…</p>
<p>…</p>
<p>Zaměstnanci okresního úřadu byli jednak státní, jednak autonomní: …</p>
<p>…</p>
<p>Okresní úřady vykonávaly působnost, která do té doby náležela okresním správám politickým. Byla však posílena jejich trestní pravomoc…</p>
<p>…</p>
<p>….</p>
<p>Na základě Mnichovské dohody byl v říjnu 1938 proveden zábor československého pohraničí nacistickým Německem. Karlovy Vary náležely do třetího záborového pásma a z něj pak do oblasti, která byla obsazena německou armádou dne 4. 10. 1938. Její zábor byl proto německou armádou zahájen tento den v 8.00. K uvedenému datu byl Okresní úřad Karlovy Vary jeho zaměstnanci vyklizen, přičemž byl na místě zanechán spisový materiál úřadu s výjimkou tajných spisů. V úřadě zůstal pouze německý personál.</p></td>
</tr>
<tr class="odd">
<td>Funkce korporace</td>
<td><p>- Dohled nad hospodařením obecní a okresní samosprávy,</p>
<p>- evidence odvodem povinných osob,</p>
<p>- výkon vodoprávní agendy,</p>
<p>- výkon agendy zdravotní a veterinární péče,</p>
<p>- výkon stavební a požární policie,</p>
<p>- výkon trestní pravomoci pro menší přestupky,</p>
<p>- dohled a organizování voleb do zastupitelských orgánů,</p>
<p>…</p></td>
</tr>
<tr class="even">
<td>Normy – konstitutivní</td>
<td><p>Zákon č. 125/1927 Sb., o organizaci politické správy</p>
<p>…</p></td>
</tr>
<tr class="odd">
<td>Normy – působnost původce</td>
<td>závazná nařízení vydaná okresním úřadem</td>
</tr>
<tr class="even">
<td>Vnitřní struktury korporace</td>
<td><p>V čele okresního úřadu stál okresní hejtman. Zaměstnanci úřadu byli jednak státní, jednak autonomní. Ke státním patřil konceptní a odborný personál.</p>
<p>….</p>
<p>Zdravotní službu zajišťoval okresní lékař, pro zvěrolékařskou péči byl určen okresní zvěrolékař, dohled nad mírami a váhami prováděl cejchovní úřad…</p></td>
</tr>
<tr class="odd">
<td>Členství</td>
<td></td>
</tr>
<tr class="even">
<td>Udělení ocenění</td>
<td></td>
</tr>
<tr class="odd">
<td>Přeřazení</td>
<td></td>
</tr>
<tr class="even">
<td>Související entity – specifikace „nadřazená korporace“</td>
<td>Země česká. Zemský úřad Praha (Praha, Česko : 1928-1945)</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „sídlo“</td>
<td>Karlovy Vary (Karlovy Vary, Česko)</td>
</tr>
<tr class="even">
<td>Poznámka k sídlu</td>
<td>Nová louka 578/23, Karlovy Vary</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „vazba na objekt“</td>
<td>dům čp. 578 (Karlovy Vary, Karlovy Vary, Karlovy Vary, Česko : dům),</td>
</tr>
<tr class="even">
<td>Poznámka k vazbě na objekt</td>
<td>sídlo Okresního úřadu Karlovy Vary</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „geografická působnost“</td>
<td>Karlovy Vary (Česko : okres : 1868-1939)</td>
</tr>
<tr class="even">
<td>Související entity – specifikace „tematický celek“</td>
<td>politická správa</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „tematický celek“</td>
<td>politické okresy</td>
</tr>
</tbody>
</table>

#### Podtřída administrativně vymezená území s vlastní správou

> Příklad K1: ***Hroznětín** (obec : Hroznětín, Karlovy Vary, Česko :
> působnost od 1213-1850), úřad městské správy s nevyhraněným názvem*
>
> VAR: *Stadt Lichtenstadt*; *Městský soud v Hroznětíně* \[datace
> použití jména: 1791-1850\]; *Stadtgericht zu Lichtenstadt* \[datace
> použití jména: 1791-1850\]; *Rychtářský úřad v Hroznětíně* \[datace
> použití jména: 1791-1850\]; *Richteramt zu Lichtenstadt* \[datace
> použití jména: 1791-1850\]
>
> K2: ***Nejdek** (obec : Nejdek, Karlovy Vary, Česko : asi 1400-1842),
> úřad městské správy s nevyhraněným názvem*
>
> VAR: *Stadt Neudek*; *Město Nejdek*; *Bürgermeister, Richter, Rat und
> ganze Gemeinde zu Neudek* \[datace použití jména: asi 1400-asi 1700\];
> *Purkmistr, rychtář, rada a celá obec v Nejdku* \[datace použití
> jména: asi 1400-asi 1700\]; *Magistrat zu Neudek* \[datace použití
> jména: asi 1700-1792\]; *Magistrath zu Neudeckh* \[datace použití
> jména: asi 1700-1792\]; *Magistrát v Nejdku* \[datace použití jména:
> asi 1700-1792\]; *Stadtrichteramt Neudek* \[datace použití jména:
> 1792-1842\]; *Městský rychtářský úřad Nejdek* \[datace použití jména:
> 1792-1842\]; *Stadtgericht Neudek* \[datace použití jména:
> 1792-1842\]; *Městský soud Nejdek* \[datace použití jména:
> 1792-1842\]; *Neudeker Stadtgericht* \[datace použití jména:
> 1792-1842\]; *Nejdecký městský soud* \[datace použití jména:
> 1792-1842\]
>
> *Poznámka: V 18. století byl používán pro městskou správu výraz
> „magistrát“. Roku 1792 byl dosavadní magistrát změněn na rychtářský
> úřad (městský soud); roku 1842 byl ve městě Nejdek zřízen regulovaný
> magistrát.*
>
> K3: ***Plzeň** (obec : Plzeň, Plzeň-město, Česko : asi 1291-1788),
> úřad městské správy s nevyhraněným názvem*
>
> *Poznámka: Regulovaný magistrát byl v Plzni zřízen v roce 1788.*
>
> K4: ***Velkostatek Terešov** (Terešov, Rokycany, Česko : 1714-1948),
> instituce patrimoniální a hospodářské správy*
>
> VAR: *Allodial-Gut Tereschau*
>
> *Poznámka: Samostatný statek Terešov vznikl roku 1714. Předtím byl
> spojen se statkem Hřešihlavy. Zkonfiskován byl roku 1948.*
>
> K5: ***Herrschaft Theusing** (Toužim, Karlovy Vary, Česko : 12.
> st.-1854), instituce patrimoniální a hospodářské správy*
>
> VAR: *Velkostatek Toužim*; *Dominium Theusing*; *Panství Toužim*;
> *Herrschaft Theusing und Gut Pürles*; *Panství Toužim a statek
> Brložec*; *Úřad Toužim*; *Amt Theusing*; *Wirtschaftsdirectorialamt
> Theusing*; *Vereinigte k. k. Kammeralfondsherrschaft Theusing mit Gut
> Pürles* \[datace použití jména: 1804-1838\]; *Vereinigte kaiserliche
> königliche Kammeralfondsherrschaft Theusing mit Gut Pürles* \[datace
> použití jména: 1804-1838\]; *Spojené c. k. komorní panství Toužim se
> statkem Brložec* \[datace použití jména: 1804-1838\]; *Spojené
> císařsko-královské komorní panství Toužim se statkem Brložec* \[datace
> použití jména: 1804-1838\]; *Verwaltungsamt Theusing*; *Správní úřad
> Toužim*; *Directorialamt Theusing*; *Ředitelský úřad Toužim*;
> *Oberverwalteramt Theusing*; *Vrchní správní úřad Toužim; Ober- und
> Justizamt Theusing* \[datace použití jména: 1838-asi 1850\]; *Vrchní
> a justiční úřad Toužim* \[datace použití jména: 1838-asi 1850\]
>
> *Poznámka: Velkostatek Toužim byl k 1. 1. 1855 připojen k sousednímu
> velkostatku Bečov nad Teplou.*

#### Podtřída orgány, organizační složky a příspěvkové organizace veřejné správy

###### Fáze vývoje úřadu včetně opakování stejného názvu v hlavní nebo vedlejší části jména:

> K6.1: ***Československo.** Ministerstvo vnitra (Praha, Česko :
> 1918-1939), ústřední orgán pro záležitosti státní správy a samosprávy,
> vnitřní bezpečnosti a legislativy*
>
> VAR: *Ministerstvo vnitra republiky Československé*; *Ministerstvo
> vnitra RČS*; *Ministerstvo vnitra*; *MV*
>
> K6.2: ***Protektorát Čechy a Morava.** Ministerstvo vnitra (Praha,
> Česko : 1939-1945), ústřední orgán pro záležitosti státní správy
> a samosprávy, vnitřní bezpečnosti a legislativy*
>
> VAR: *Ministerium des Innern in Prag*; *Ministerstvo vnitra v Praze*
>
> K6.3: ***Československo.** Ministerstvo vnitra (Londýn, Velká Británie
> : 1940-1945), ústřední orgán pro záležitosti státní správy
> a samosprávy, vnitřní bezpečnosti a legislativy v exilu*
>
> VAR: *Ministerstvo vnitra ČSR v Londýně*
>
> K7: ***Slovensko.** Ministerstvo vnútra (Bratislava, Slovensko :
> 1939-1945), ústřední orgán pro záležitosti státní správy a samosprávy,
> vnitřní bezpečnosti a legislativy*
>
> VAR: *Slovensko.* Ministerstvo vnitra
>
> K8.1: ***Země česká.*** *Zemská správa politická Praha (Praha, Česko :
> 1918-1928), orgán státní správy na zemské úrovni*
>
> VAR: *Zemská správa politická Národního výboru*; *Zemská správa
> politická Praha*
>
> K8.2: ***Země česká.*** *Zemský úřad Praha (Praha, Česko :
> 1928-1945),* *orgán státní správy na zemské úrovni*
>
> VAR: *ZÚ Praha*; *Zemský úřad Praha*; *Zemský úřad v Praze*;
> *Landesbehörde in Prag*
>
> K9.1: ***Krajská vláda Pardubice** (Pardubice, Pardubice, Česko :
> 1850-1855),* *orgán státní správy na krajské úrovni*
>
> VAR: *Kreisregierung Pardubitz*
>
> K9.2: ***Krajský úřad Pardubického kraje** (Pardubice, Pardubice,
> Česko : 2000-), úřad krajské správy a přenesené státní správy*
>
> VAR: *Krajský úřad Pardubice*; *KÚ Pardubice*; *KÚ Pardubického kraje*
>
> K10.1: ***Okresní hejtmanství Chrudim** (Chrudim, Chrudim, Česko :
> 1850-1855), regionální orgán politické státní správy*
>
> VAR: *Podkrajský úřad Chrudim*; *Bezirkshauptmannschaft Chrudim*; *OH
> Chrudim*; *Okresní úřad Chrudim*; *OkÚ Chrudim*
>
> K10.2: ***Okresní úřad Chrudim** (Chrudim, Chrudim, Česko :
> 1855-1868), regionální orgán politické státní správy*
>
> VAR: *Bezirksamt Chrudim*; *Smíšený okresní úřad Chrudim*; *Okresní
> úřad Chrudim*; *OkÚ Chrudim*
>
> *Poznámka: Okresní soud působící v rámci smíšeného okresního úřadu má
> samostatný záznam (**viz příklad K34.2**).*
>
> K10.3: ***Okresní hejtmanství Chrudim** (Chrudim, Chrudim, Česko :
> 1868-1919),* *regionální orgán politické státní správy*
>
> VAR: *Bezirkshauptmannschaft Chrudim*; *OH Chrudim*; *Okresní úřad
> Chrudim*; *OkÚ Chrudim*
>
> K10.4: ***Okresní správa politická Chrudim** (Chrudim, Chrudim, Česko
> : 1919-1928), regionální orgán politické státní správy*
>
> VAR: *OSP Chrudim*; *Okresní úřad Chrudim*; *OkÚ Chrudim*
>
> K10.5: ***Okresní úřad Chrudim** (Chrudim, Chrudim, Česko :
> 1928-1945), regionální orgán politické státní správy*
>
> VAR: *Bezirksbehörde Chrudim*; *Okresní úřad Chrudim*; *OkÚ Chrudim*
>
> K10.6: ***Okresní národní výbor Chrudim** (Chrudim, Chrudim, Česko :
> 1945-1990), úřad okresní lidové správy a přenesené státní správy*
>
> VAR: *ONV Chrudim*; *Okresní národní výbor Chrudim*
>
> K10.7: ***Okresní úřad Chrudim** (Chrudim, Chrudim, Česko :
> 1990-2002), regionální orgán politické státní* správy
>
> VAR: *Okresní úřad Chrudim*; *OkÚ Chrudim*
>
> K11: ***Okresní národní výbor Chrudim** (Chrudim, Chrudim, Česko :
> 1918), prozatímní orgán zajišťující výkon správy*
>
> VAR: *ONV Chrudim*; *Okresní národní výbor Chrudim*
>
> K12.1: ***Landrat Luditz** (Žlutice, Karlovy Vary, Česko : 1938-1945),
> regionální orgán <span style="color:red">německé okupační</span> politické státní správy*
>
> VAR: *Landrát Žlutice*; *LR Žlutice*; *Úřad zemského rady Žlutice*
>
> K12.2: ***Okresní správní komise Žlutice** (Žlutice, Karlovy Vary,
> Česko : 1945-1946), prozatímní úřad okresní lidové správy a přenesené
> státní správy*
>
> VAR: *OSK Žlutice*
>
> K12.3: ***Okresní národní výbor Žlutice** (Žlutice, Karlovy Vary,
> Česko : 1946-1949), úřad okresní lidové správy a přenesené státní
> správy*
>
> VAR: *ONV Žlutice*
>
> K12.4: ***Okresní národní výbor Toužim** (Toužim, Karlovy Vary, Česko
> : 1949-1960), úřad okresní lidové správy a přenesené státní správy*
>
> VAR: *ONV Toužim*
>
> *Poznámka: V roce 1949 byl politický okres Žlutice zrušen a jeho
> převážná část se stala součásti nového okresu Toužim – viz zákon č.
> 3/1949 Sb., § 5, odst. 2, a příloha k tomuto zákonu, část I, bod 4,
> řadové číslo 10.*

###### Úřad s celostátní působností měnící sídlo:

> K13: ***Československo.** Nejvyšší soud (Praha, Česko : 1945-1992),
> ústřední justiční orgán*
>
> VAR: *NS*; *Nejvyšší soud (Praha, Česko : 1945-1992)* \[datace použití
> jména: 1950-1992\]; *Československo.* Nejvyšší soud *(Brno,
> Brno-město, Česko : 1945-1992)* \[datace použití jména: 1945-1949\];
> *Nejvyšší soud* *(Brno, Brno-město, Česko : 1945-1992)* \[datace
> použití jména: 1945-1949\]
>
> *Poznámky:*
>
> *Nejvyšší soud sídlil po část své existence v Brně. Sídla původce
> v sekci Vztahy proto budou:*
>
> *sídlo 1: „Praha (Česko)“* – v letech 1950–1992
>
> *sídlo 2: „Brno (Brno-město, Česko)“* – v letech 1945–1949
>
> *V geografickém doplňku je uvedeno posledně známé sídlo korporace (viz
> **kapitolu 9.3.1**).*

###### Úřad s celostátní působností sídlící mimo hlavní město:

> K14: ***Česko.** Národní úřad pro kybernetickou a informační
> bezpečnost* *(Brno, Brno-město, Česko : 2017- ), ústřední správní
> orgán pro kybernetickou bezpečnost*
>
> VAR: *NÚKIB*

###### Úřady německé okupační správy:

> K15: ***Oberlandrat Olmütz*** *(Olomouc, Olomouc, Česko : 1939-1942),
> regionální orgán německé okupační politické státní správy*
>
> VAR: *Oberlandrát Olomouc; OLR Olomouc*
>
> *Poznámka: V období protektorátu se české označení preferuje u českých
> úřadů, nikoliv u německých, jako je tento (**viz též přílohu č.
> 14**).*
>
> K16: ***Deutsches Staatsministerium für Böhmen und Mähren** (Praha,
> Česko : 1943-1945), ústřední orgán německé okupační správy*
>
> VAR: *Německé státní ministerstvo pro Čechy a Moravu*

###### Město/obec a jeho úřad:

> K17: ***Magistrát Bechyně** (Bechyně, Tábor, Česko : 1792-1850), úřad
> městské a přenesené státní správy*
>
> VAR: *Magistrat der Stadt Bechin*; *Regulovaný magistrát Bechyně*
>
> K18: ***Magistrat der Stadt Duppau*** *(Hradiště, Karlovy Vary, Česko
> : 1795-1850), úřad městské a přenesené státní správy dnes již
> zaniklého města Doupov*
>
> VAR: *Municipalstadt Duppau*; *Stadt Duppau*; *Magistrát města
> Doupov*; *Magistrat Duppau*; *Magistrát města doupovského*; *Stadt
> Duppauer Magistrat*; *Magistrát svobodného ochranného města Doupov*;
> *Magistrat der freyen Schutzstadt Duppau*; *Magistrát municipálního
> města Doupov*; *Magistrat der Municipalstadt Duppau*
>
> K19: ***Městský úřad Chrudim** (Chrudim, Chrudim, Česko : 1850-1945),
> úřad městské a přenesené státní správy*
>
> VAR: *Bürgermeisteramt Chrudim*; *Stadtamt Chrudim*; *MěÚ Chrudim*;
> *Městský úřad Chrudim*; *Město Chrudim*; *Městská obec Chrudim*
>
> *Poznámka: Korporace zahrnuje i dobu působení vládního komisaře
> v letech 1942-1945.*
>
> K20: ***Oberbürgermeister der Stadt Karlsbad** (Karlovy Vary, Karlovy
> Vary, Česko : 1939-1945), úřad komunální samosprávy a přenesené státní
> správy městského okresu Karlovy Vary*
>
> VAR: *Úřad vrchního starosty města Karlovy Vary*
>
> K21.1: ***Bürgermeisteramt Schlackenwerth** (Ostrov, Karlovy Vary,
> Česko : 1850-1945), úřad městské a přenesené státní správy*
>
> VAR: *Městský úřad Ostrov*; *Purkmistrovský úřad Ostrov*;
> *Stadtgemeinde Schlackenwerth*; *Městská obec Ostrov*
>
> K21.2: ***Revoluční národní výbor Ostrov** (Ostrov, Karlovy Vary,
> Česko : 1945), prozatímní orgán zajišťující výkon správy*
>
> VAR: *ČNV Ostrov*; *Český národní výbor Ostrov*; *RNV Ostrov*
>
> *Poznámka: Jedná se o revoluční orgán ustavený na začátku května 1945
> z iniciativy skupiny Čechů, kteří byli za války totálně nasazení na
> práci v Ostrově (něm. Schlackenwerth).*
>
> K21.3: ***Místní správní komise Ostrov** (Ostrov, Karlovy Vary, Česko
> : 1945-1946), prozatímní úřad místní lidové správy a přenesené státní
> správy*
>
> VAR: *MSK Ostrov*; *Místní správní komise v Ostrově*
>
> *Poznámka: Korporace typu místních správních komisí, které byly v Československu ustaveny po skončení druhé světové války v pohraničním území s převážnou většinou státně nespolehlivého obyvatelstva, zahrnují i působení vládního / místního správního komisaře, pokud byl pro obec jmenován v době před vznikem příslušné místní správní komise.*
>
> K21.4: ***Místní národní výbor Ostrov** (Ostrov, Karlovy Vary, Česko :
> 1946-1960), úřad místní lidové správy a přenesené státní správy*
>
> VAR: *MNV Ostrov*; *Místní národní výbor v Ostrově*
>
> K21.5: ***Městský národní výbor Ostrov** (Ostrov, Karlovy Vary, Česko
> : 1960-1990), úřad městské lidové správy a přenesené státní správy*
>
> VAR: *MěNV Ostrov*; *MěstNV Ostrov*; *Městský národní výbor v Ostrově*
>
> *Poznámka: Změna entity na základě zákona č. 65/1960 Sb., § 13, odst.
> 3: „Městské národní výbory působí ve městech, která jsou sídly krajů
> a okresů, a v ostatních velkých obcích městského charakteru, které
> určí krajský národní výbor.“*
>
> K21.6: ***Městský úřad Ostrov** (Ostrov, Karlovy Vary, Česko : 1990-),
> úřad městské správy a přenesené státní správy*
>
> VAR: *MÚ Ostrov*
>
> K22.1: ***Jednotný národní výbor Karlovy Vary** (Karlovy Vary, Karlovy
> Vary, Česko : 1949-1954), úřad okresní a městské lidové správy
> a přenesené státní správy*
>
> VAR: *JNV Karlovy Vary*; *Jednotný národní výbor v Karlových Varech*
>
> K22.2: ***Městský národní výbor Karlovy Vary** (Karlovy Vary, Karlovy
> Vary, Česko : 1954-1990),* *úřad městské lidové správy a přenesené
> státní správy*
>
> VAR: *MěstNV Karlovy Vary*; *MěNV Karlovy Vary*; *Městský národní
> výbor v Karlových Varech*
>
> K22.3: ***Úřad města Karlovy Vary** (Karlovy Vary, Karlovy Vary, Česko
> : 1990-2000), úřad městské správy a přenesené státní správy*
>
> VAR: *Městský úřad Karlovy Vary*; *Město Karlovy Vary* \[typ formy
> jména: zjednodušená podoba\]*; Město Karlovy Vary* \[typ formy jména:
> zjednodušená podoba\]
>
> *Poznámka: V České republice se až do roku 1992 úřady statutárních
> měst, které v nich plnily funkci obecního úřadu, nazývaly úřad města
> (zákon č. 367/1990 Sb., § 3, odst. 1, a § 58, odst. 4), poté bylo toto
> označení užíváno až do roku 2000 jen u obecních úřadů těch
> statutárních měst, která nebyla územně členěná (zákon č. 302/1992 Sb.,
> čl. I, bod 50).*
>
> K22.4: ***Magistrát města Karlovy Vary*** *(Karlovy Vary, Karlovy
> Vary, Česko : 2000-), úřad městské správy a přenesené státní správy*
>
> VAR: *MM Karlovy Vary*; *Město Karlovy Vary*
>
> *Poznámka: V České republice mají od roku 2000 všechna statutární
> města (členěná i nečleněná), svůj magistrát (zákon č. 128/2000 Sb., §
> 15, odst. 2).*
>
> K23: ***Gemeindeamt Ullersgrün** (Oldřiš, Merklín, Karlovy Vary, Česko
> : 1850-1945)*, *úřad obecní a přenesené státní správy*
>
> VAR: *Obecní úřad Oldřiš*; *Obec Oldřiš*; *Gemeinde Ullersloh*
>
> K24: ***Obecní úřad Bítovany** (Bítovany, Chrudim, Česko : 1904-1945),
> úřad obecní a přenesené státní správy*
>
> VAR: *OÚ Bítovany*; *Obec Bítovany*
>
> *Poznámka: Samostatná místní obec Bítovany vznikla odloučením od obce
> Žumberk v roce 1904 (vyhl. č. 31/1905 českého z. z., bod 18).*

###### Autonomní osada / část obce / čtvrť a její správní orgán:

> K25: ***Ortsgericht zu Fischern** (Rybáře, Karlovy Vary, Karlovy Vary,
> Česko : 1850-1866), úřad samosprávy části obce podléhající Obecnímu
> úřadu Sedlec*
>
> VAR: *Místní rychtářský úřad Rybáře*; *Osadní zastupitelstvo Rybáře*;
> *Ortsgemeinde Fischern*
>
> *Poznámka: Rybáře jsou nyní částí obce Karlovy Vary nikoliv obce
> Sedlec. PREF je odvozeno pouze z tištěného pramene, proto není uvedeno
> v příloze č. 14. Do svého zániku používala korporace označení
> „Ortsgericht“.*
>
> K26: ***Židovská obec Třebíč** (Třebíč, Třebíč, Česko : 1850-1931),
> úřad správy židovské obce*
>
> VAR: *Judenstadt Trebitsch*; *Judengemeinde Trebitsch*
>
> K27: ***Osadní zastupitelstvo Nerad** (Živanice, Pardubice, Česko :
> působnost od 1875-1941), úřad samosprávy části obce podléhající
> obecnímu úřadu*
>
> VAR: *Osadní úřad Nerad*; *Osadní výbor Nerad*; *OsZ Nerad*; *Osada
> Nerad*
>
> *Poznámka: Jako útvary územní samosprávy byly osady zrušeny v roce
> 1941 a jejich jmění splynulo s majetkem příslušných obcí – viz vládní
> nařízení č. 265/1941 Sb., §§ 1–3.*
>
> K28: ***Občanský výbor Čichalov** (Čichalov, Karlovy Vary, Česko :
> působnost od 1976-asi 1990), orgán lidové správy části obce
> podléhající Městskému národnímu výboru Žlutice*
>
> VAR: *Občanský výbor v Čichalově*; *OV Čichalov*; *ObV Čichalov*
>
> *Poznámka: Obec Čichalov byla místní částí města Žlutice pouze
> v letech 1975–1990.*
>
> K29: ***Místní výbor Nové Zákupy** (Zákupy, Česká Lípa, Česko :
> 2009-), úřad samosprávy městské čtvrti podléhající městskému úřadu*
>
> VAR: *Místní výbor v Nových Zákupech*
>
> *Poznámka: Jedná se pouze o městskou čtvrť (panelové sídliště);
> v RÚIAN nejsou Nové Zákupy jako „část obce“ uvedeny.*
>
> K30: ***Osadní výbor Tašovice** (Karlovy Vary, Karlovy Vary, Česko :
> 2017-), úřad samosprávy části obce podléhající magistrátu města*
>
> VAR: *Osadní výbor v Tašovicích*; *Osada Tašovice*

###### Územní samospráva hierarchicky vyšší než obec:

> K31.1: ***Český zemský sněm** (Praha, Česko : 1861-1913), orgán
> regionální samosprávy pro tehdejší Zemi českou*
>
> VAR: *Zemský sněm Království českého*; *Landtag des Königreiches*
> *Böhmen*; *Böhmischer Landtag*; *Země česká*; *Land Böhmen*
>
> K31.2: ***České království.** Zemská správní komise (Praha, Česko :
> 1913-1918), prozatímní orgán regionální samosprávy pro tehdejší Zemi
> českou*
>
> VAR: *zemská správní komise*; *Zemská správní komise království
> Českého*; *Landesverwaltungskommission des Königreiches Böhmen*; *Země
> česká*; *Land Böhmen*
>
> *Poznámka: Korporace nahradila Český zemský sněm, rozpuštěný tzv.
> anenskými patenty v roce 1913 (císařským patentem č. 36/1913 českého
> z. z.; císařský patent č. 150/1913 ř. z.). Zrušena byla zákonem č.
> 38/1918 Sb., o zřízení zemského správního výboru.*
>
> K31.3: ***Zemský správní výbor pro Čechy** (Praha, Česko : 1919-1928),
> orgán regionální samosprávy pro tehdejší Zemi českou*
>
> VAR: *Zemský správní výbor*; *Zemský správní výbor v Praze*;
> *Landesverwaltungsausschuss für Böhmen*; *Země česká; Land Böhmen*
>
> K31.4: ***Zemské zastupitelstvo v Zemi české** (Praha, Česko :
> 1928-1939), orgán regionální samosprávy*
>
> VAR: *Zemské zastupitelstvo Praha*; *Zemské zastupitelstvo v Praze*;
> *Země česká*; *Land Böhmen*; *Země česká.* Zemské zastupitelstvo
> v Praze; *Země česká.* Zemské zastupitelstvo
>
> *Poznámka: Nejedná se o původce. Korporace byla součástí Zemského
> úřadu Praha na základě zákona č. 125/1927 Sb., o organizaci politické
> správy. Byl to správní orgán korporace územní samosprávy nazývané
> „země Česká“ či „Čechy“, který byl v oboru své hospodářské působnosti
> právnickou osobou, mohl samostatně nabývat práva a zavazovat se;
> navenek zastupoval „zemi Českou“ zemský prezident, šéf zemského úřadu,
> který byl zároveň předsedou zemského zastupitelstva.*
>
> K32: ***Zemské zastupitelstvo Země moravskoslezské*** *(Brno,
> Brno-město, Česko : 1928-1939), orgán regionální samosprávy*
>
> VAR: *Zemské zastupitelstvo Brno*; *Zemské zastupitelstvo v Brně*;
> *Zemské zastupitelstvo moravsko-slezské*; *Země moravskoslezská.*
> Zemské zastupitelstvo v Brně; *Země moravskoslezská.* Zemské
> zastupitelstvo
>
> *Poznámka: Pro Zemi moravskoslezskou platí obdobně to, co je sděleno
> v poznámce k Zemskému zastupitelstvu v Zemi české (**příklad
> K31.4**).*
>
> K33.1: ***Bezirksvertretung Karlsbad** (Karlovy Vary, Karlovy Vary,
> Česko : 1865-1919), úřad regionální samosprávy pro tehdejší soudní
> okres Karlovy Vary*
>
> VAR: *Okresní zastupitelstvo Karlovy Vary*; *OZ Karlovy Vary*; *Okres
> Karlovy Vary*; *Bezirk Karlsbad*
>
> K33.2: ***Bezirksverwaltungskommission Karlsbad** (Karlovy Vary,
> Karlovy Vary, 1920-1928), úřad regionální samosprávy pro tehdejší
> politický a soudní okres Karlovy Vary*
>
> VAR: *Okres Karlovy Vary*; *Bezirk Karlsbad; Okresní správní komise
> Karlovy Vary*
>
> *Poznámka: Naposledy se Okresní zastupitelstvo Karlovy Vary sešlo 18.
> 12. 1919. První schůze Okresní správní komise Karlovy Vary proběhla 3.
> 2. 1920. Jednacím jazykem byla němčina, proto bylo zvoleno preferované
> označení v němčině.*
>
> K33.3: ***Bezirksvertretung Karlsbad** (Karlovy Vary, Karlovy Vary,
> Česko : 1928-asi 1938), orgán regionální samosprávy pro tehdejší
> politický a soudní okres Karlovy Vary*
>
> VAR: *Okresní zastupitelstvo Karlovy Vary*; *Okresní úřad Karlovy
> Vary.* Okresní zastupitelstvo Karlovy Vary; *Bezirksbehörde Karlsbad.*
> Bezirksvertretung Karlsbad; *Okres Karlovy Vary*; *Bezirk Karlsbad*
>
> *Poznámka: Nejedná se o původce. Korporace byla součástí Okresního
> úřadu Karlovy Vary na základě zákona č. 125/1927 Sb., o organizaci
> politické správy. Byl to správní orgán korporace územní samosprávy
> nazývané „okres“, který byl v oboru své hospodářské působnosti
> právnickou osobou, mohl samostatně nabývat práva a zavazovat se;
> navenek zastupoval „okres“ okresní hejtman, šéf okresního úřadu, který
> byl zároveň předsedou okresního zastupitelstva. Jednacím jazykem byla
> němčina, proto bylo zvoleno preferované označení v němčině.*
>
> K33.4: ***Nationaler Bezirksrat Karlsbad** (Karlovy Vary, Karlovy
> Vary, Česko : 1918), prozatímní orgán zajišťující výkon správy*
> \[datace použití jména: 1. 11. 1918-13. 12. 1918\]
>
> VAR: *Bezirksnationalrat Karlsbad* \[datace použití jména: 1. 11.
> 1918-13. 12. 1918\]; *Národní okresní rada Karlovy Vary* \[datace
> použití jména: 1. 11. 1918-13. 12. 1918\]; *Okresní národní rada
> Karlovy Vary* \[datace použití jména: 1. 11. 1918-13. 12. 1918\]; *ONR
> Karlovy Vary*; *Der nationale Bezirksrat für Stadt und Bezirk
> Karlsbad* \[datace použití jména: 1. 11. 1918-13. 12. 1918\]; *Národní
> okresní rada pro město a okres Karlovy Vary* \[datace použití jména:
> 1. 11. 1918-13. 12. 1918\]; *Okresní národní rada pro město a okres
> Karlovy Vary* \[datace použití jména: 1. 11. 1918-13. 12. 1918\];
> *Volksausschuß für Stadt und Bezirk Karlsbad* \[datace použití jména:
> 27. 10. 1918-31. 10. 1918\]; *Volksausschuß Karlsbad* \[datace použití
> jména: 27. 10. 1918-31. 10. 1918\]; *Nationalausschuß des Bezirkes
> Karlsbad*;
>
> *Poznámka: Jednalo se o správní orgán tzv. provincie Deutschböhmen,
> který byl dne 13. 12. 1918 zrušen podplukovníkem Slezáčkem, velitelem
> československého vojenského oddílu, který o den dříve město Karlovy
> Vary obsadil.*

###### Okresní soud – změny geografické působnosti v průběhu existence nejsou důvodem pro založení nové entity:

> K34.1: ***Okresní soud Chrudim** (Chrudim, Chrudim, Česko :
> 1850-1855), justiční orgán; obecný soud první instance*
>
> VAR: *Bezirksgericht Chrudim*; *OS Chrudim*
>
> K34.2: ***Okresní úřad jakožto Okresní soud Chrudim** (Chrudim,
> Chrudim, Česko : 1855-1868), justiční orgán; obecný soud první
> instance*
>
> VAR: *Bezirksamt Chrudim.* Bezirksgericht Chrudim; *Smíšený okresní
> úřad Chrudim*
>
> *Poznámka: **Viz** **též příklad K10.2**.*
>
> K34.3: ***Okresní soud Chrudim** (Chrudim, Chrudim, Česko :
> 1868-1952), justiční orgán; obecný soud první instance*
>
> VAR: *Bezirksgericht Chrudim*; *OS Chrudim*
>
> K34.4: ***Lidový soud Chrudim** (Chrudim, Chrudim, Česko : 1953-1961),
> justiční orgán; obecný soud první instance*
>
> VAR: *LS Chrudim*
>
> K34.5: ***Okresní soud Chrudim** (Chrudim, Chrudim, Česko : 1961-),
> justiční orgán; obecný soud první instance*
>
> VAR: *OS Chrudim*
>
> K35.1: ***Okresní soud Žlutice** (Žlutice, Karlovy Vary, Česko :
> 1868-1938),* *justiční orgán; obecný soud první instance*
>
> VAR: *Bezirksgericht Luditz*; *OS Žlutice*
>
> K35.2: ***Amtsgericht Luditz** (Žlutice, Karlovy Vary, Česko :
> 1938-1945),* *justiční orgán; obecný soud první instance*
>
> VAR: *Úřední soud Žlutice*; *ÚS Žlutice*
>
> K35.3: ***Okresní soud Žlutice** (Žlutice, Karlovy Vary, Česko :
> 1945-1949),* *justiční orgán; obecný soud první instance*
>
> VAR: *OS Žlutice*
>
> *Poznámka: Korporace zanikla se zánikem Okresního národního výboru
> Žlutice v roce 1949 (**viz příklad K12.3** a nařízení ministra
> spravedlnosti č. 11/1949 Sb., § 2, odst. 1, a příloha k tomuto
> nařízení část II, bod 4, písm B). Obvod Okresního soudu Žlutice byl
> rozdělen mezi Okresní soud Toužim a Okresní soud Podbořany.*

###### Ostatní orgány a organizační složky veřejné správy:

> K36.1: ***Moravské gubernium** (Brno, Brno-město, Česko : 1763-1783),
> orgán státní správy na zemské úrovni*
>
> VAR: *Mährisches Gubernium*; *Gubernium*
>
> K36.2: ***Moravskoslezské gubernium** (Brno, Brno-město, Česko :
> 1783-1849), orgán státní správy na zemské úrovni*
>
> VAR: *Märisch-Schlesisches Gubernium*
>
> K37: ***České místodržitelství** (Praha, Česko : 1850-1918), orgán
> státní správy na zemské úrovni*
>
> VAR: *České zemské místodržitelství*; *C. k. Místodržitelství pro
> Čechy*; *Císařsko-královské Místodržitelství pro Čechy*; *K. k.
> Statthalterei für Böhmen*; *Kaiserliche königliche Statthalterei für
> Böhmen*; *Místodržitelství království Českého*; *Statthalterei für das
> Königreich Böhmen*
>
> K38.1: ***Česko 1969-1992.** Státní fond životního prostředí (Praha,
> Česko : 1991-1992), státní instituce přispívající na projekty
> zlepšující životní prostředí v České republice*
>
> VAR: *Státní fond životního prostředí České republiky*; *SFŽP ČR*
>
> K38.2: ***Česko.** Státní fond životního prostředí (1993-), státní
> instituce přispívající na projekty zlepšující životní prostředí
> v České republice*
>
> VAR: *Státní fond životního prostředí České republiky*; *SFŽP ČR*
>
> K39: ***Česko.** Úřad vlády (1993-), ústřední orgán státní správy
> zajišťující odborné organizační a technické zabezpečení činnosti vlády
> České republiky a jejích orgánů*
>
> VAR: *Úřad vlády České republiky*; *Úřad vlády ČR*
>
> K40: ***Státní oblastní archiv v Plzni** (Plzeň, Plzeň-město, Česko :
> 2002-), státní archiv s regionální působností pro Plzeňský
> a Karlovarský kraj*
>
> VAR: *Státní oblastní archiv Plzeň*; *SOA v Plzni*; *SOA Plzeň*
>
> K41: ***Archiv Národního muzea** (Praha, Česko : 1846-),
> specializovaný archiv*
>
> VAR: *Archiv Národního musea*; *ANM*; *ANM Praha*

#### Podtřída sdružení organizací

> K42: ***UNESCO** (Paříž, Francie : 1945-), mezistátní odborná agentura
> Organizace spojených národů určená pro vzdělání, vědu a kulturu*
>
> VAR: *Organizace OSN pro vzdělání, vědu a kulturu*; *United Nations
> Educational, Scientific and Cultural Organization*
>
> K43: ***Varšavská smlouva** (vojenský pakt : Moskva, Rusko :
> 1955-1991), vojenský pakt Sovětského svazu a jeho evropských satelitů*
>
> VAR: *Smlouva o přátelství, spolupráci a vzájemné pomoci*; *Varšavský
> pakt*
>
> *Poznámka: Obecného doplňku je užito, aby byla tato korporace odlišena
> od samotné smlouvy, která patří do třídy „dílo/výtvor“.*
>
> K44: ***UITP** (Brusel, Belgie : 1985-), organizace provozovatelů
> veřejné dopravy, objednatelů dopravy, tvůrců dopravní politiky
> a výzkumných organizací a dalších významných subjektů působících
> v tomto oboru*
>
> VAR: *Mezinárodní svaz veřejné dopravy*; *L’Union internationale des
> transports publics*; *International Association of Public Transport*
>
> K45: ***Mikroregion Železné hory** (Ronov nad Doubravou, Chrudim,
> Česko : 1999-), regionální sdružení obcí*
>
> K46.1: ***Verband der deutschen Bezirke und Städte Böhmens***
> *(Teplice, Teplice, Česko : 1919), sdružení německých samosprávných
> orgánů veřejné správy*
>
> VAR: *Svaz německých okresů a měst v Čechách*
>
> K 46.2: ***Verband der deutschen Selbsverwaltungskörper in der
> Tschechoslowakischen Republik*** *(Teplice, Teplice, Česko :
> 1919-1938), sdružení německých samosprávných orgánů veřejné správy*
>
> VAR: *Svaz německých samosprávných celků v Československé republice*;
> *Verband der deutschen Selbsverwaltungskörper in der
> tschecho-slowakischen Republik*

#### Podtřída vojenské a bezpečnostní jednotky

> K47: ***Československé legie** (1914-1920), jednotky dobrovolnického
> zahraničního vojenského odboje Čechů a Slováků*
>
> VAR: *revoluční dobrovolná vojska*; *zahraniční československá vojska*
>
> K48: ***Česká družina** (1914-1916), jednotka dobrovolníků složená
> z Čechů žijících v Rusku a později též z českých válečných zajatců*
>
> K49: ***ETA** (ozbrojená organizace : 1959-2018), ozbrojená baskická
> nacionalistická a separatistická organizace*
>
> VAR: *Euskadi Ta Askatasuna*; *Baskicko a jeho svoboda*
>
> *Poznámka: Pro odlišení od podniku ETA je použit obecný doplněk.*
>
> K50: ***Četnická stanice Nasavrky** (Nasavrky, Chrudim, Česko : asi
> 1850-1945), vojensky organizovaný bezpečnostní sbor k udržování
> veřejného pořádku a bezpečnosti státu*
>
> VAR: *Gendarmerieposten Nasaberg*
>
> K51: ***Partyzánský oddíl Bořek** (1944-1945), ozbrojená jednotka pro
> vedení drobné záškodnické války působící zejména v okolí města
> Vamberk*
>
> K52: ***Vězeňská služba České republiky** (Praha, Česko : 1993-),
> ozbrojený bezpečnostní sbor zajišťující výkon vazby a trestu odnětí
> svobody a ochranu pořádku a bezpečnosti při výkonu soudnictví*
>
> VAR: *Vězeňská služba ČR*; *VS ČR*
>
> K53: ***Věznice Bory** (správa věznice : Plzeň, Plzeň-město, Česko :
> 1997-), orgán zajišťující výkon trestu*
>
> VAR: *Bory*; Vězeňská *služba České republiky*. Věznice Plzeň;
> *Věznice Plzeň*; *VS ČR*. Věznice Plzeň; *Borská věznice*
>
> *Poznámka: Obecného doplňku je užito, aby byla tato korporace odlišena
> od budovy věznice, která patří do třídy „dílo/výtvor“.*

#### Podtřída organizace založené za účelem podnikání

> K54: ***Místní dráha Otrokovice - Zlín - Vizovice, a. s.** (Zlín,
> Zlín, Česko : 1898-1945), vlastník regionální železniční trati*
>
> VAR: *OZVD*; *Localbahn Otrokowitz - Zlin - Wisowitz*; *LOZW*
>
> *Poznámka: Korporace měla v průběhu vývoje více sídel, v geografickém
> doplňku je uvedeno poslední (**viz kapitolu 9.3.1**).*
>
> K55: ***Jednotné zemědělské družstvo Bylany** (Bylany, Chrudim, Česko
> : 1954-1990), právnická osoba lidového družstevnictví zajišťující
> zemědělskou a jinou hospodářskou činnost*
>
> VAR: *JZD Bylany*; *Jednotné zemědělské družstvo 1. máj Bylany*; *JZD
> 1. máj Bylany*
>
> K56: ***Restaurace a jídelny Žďár nad Sázavou** (Žďár nad Sázavou,
> Žďár nad Sázavou, Česko : 1960-1988), nevýrobní podnik zaměřený na
> stravování*
>
> VAR: *RaJ Žďár nad Sázavou*
>
> K57: ***ČERNÁ HORA - MEDIA, s. r. o.** (Hradec Králové, Hradec
> Králové, Česko : 1995-), nevýrobní podnik provozující rozhlasové
> vysílání*

###### Zjednodušené záznamy podnikových entit:

> K58: ***MADETA** (Česko : působnost 1952), zjednodušená podniková
> entita; výrobní podnik*
>
> *Poznámka: Preferované označení „MADETA“ je vloženo jako variantní
> označení u níže zpřesněných archivních autoritních záznamů entity
> firmy MADETA (**viz příklady K64.1–3**), obdobně bylo postupováno
> i u následujících příkladů archivních autoritních záznamů.*
>
> K59: ***Telecom** (Česko : působnost 2000), zjednodušená podniková
> entita; poskytovatel telekomunikačních služeb*
>
> K60: ***Dopravní investorská** (Česko : působnost 1998), zjednodušená
> podniková entita; podnik zabývající se výstavbou silnic v ČR*

###### Entity s přesným označením se zjištěnou působností:

> K61: ***Jindřich Křižan, zednický mistr ve Zdounkách** (Zdounky,
> Kroměříž, Česko : působnost 1940), stavební podnik*
>
> VAR: *Křižan Jindřich*, *zednický mistr ve Zdounkách*; *zedník Křižan
> Zdounky*
>
> *Poznámka: Chronologický doplněk byl zjištěn ze spisu o zřízení dvou
> studní v obci Kostelany uvedenou firmou, pocházejícího z roku 1940 –
> uloženo ve fondu Generální ředitelství stavby dálnic, Praha
> 1938–1951.*
>
> K62: ***Höntsch & Co., Tetschen a. d. Elbe** (Děčín, Děčín, Česko :
> působnost od 1929-působnost do 1931), výrobní podnik zaměřený na
> produkci skleníků*
>
> VAR: *Höntsh & Company, Tetschen an der Elbe*; *Höntsch a spol. Děčín
> nad Labem*; *Höntsch a společníci Děčín nad Labem*; *Höntsch
> Tetschen*; *Höntsch Děčín*

###### Fáze vývoje podniku a jeho organizační začlenění:

> K63.1: ***České cementárny a vápenice, a. s. Praha.** Závod 03 Vápenný
> Podol (Vápenný Podol, Chrudim, Česko : 1946-1949), pobočka výrobního
> podniku zaměřená na těžbu a zpracování vápence a výrobu cementu*
>
> VAR: *Prachovická cementárna.* Závod Vápenný Podol; *Vápenka Vápenný
> Podol*; *České cementárny a vápenice, akciová společnost Praha.* Závod
> 03 Vápenný Podol
>
> K63.2: ***Prachovická cementárna a vápenice, n. p..** Závod Vápenný
> Podol (Vápenný Podol, Chrudim, Česko : 1950-1965), pobočka firmy
> zaměřená na těžbu a zpracování vápence a výrobu cementu*
>
> VAR: *Prachovická cementárna.* Závod Vápenný Podol; *Vápenka Vápenný
> Podol*; *Prachovická cementárna a vápenice, národní podnik.* Závod
> Vápenný Podol; *Prachovická cementárna a vápenice n. p.* Závod Vápenný
> Podol

###### Fáze vývoje podniku:

> K64.1: ***Mlékařské družstvo táborské, s. r. o.** (Tábor, Tábor, Česko
> : 1901-1951), mlékárenský výrobní podnik* \[datace použití jména:
> 1901-1945\]
>
> VAR: *Mlékařské družstvo táborské, s.r.o.* \[datace použití jména:
> 1901-1945\]; *Mlékařské družstvo táborské, s. r. o.* \[datace použití
> jména: 1901-1945\]; *Mlékařské družstvo táborské, společnost s ručením
> omezeným* \[datace použití jména: 1901-1945\]; *Mlékařské družstvo
> táborské, zapsané společenstvo s ručením obmezeným* \[datace použití
> jména: 1901-1945\]; *Mlékařské družstvo táborské z. s. s r. o.
> v Táboře* \[datace použití jména: 1901-1945\]; *Mlékařské družstvo
> táborské zapsaná společnost s ručením omezeným v Táboře* \[datace
> použití jména: 1901-1945\]; *MADETA, mlékařské družstvo táborské, s.
> r. o.* \[datace použití jména: 1945-1951\]; *MADETA, mlékařské
> družstvo táborské, společnost s ručením omezeným* \[datace použití
> jména: 1945-1951\]; *MADETA, mlékařské družstvo táborské, z. s. s r.o.
> v Táboře* \[datace použití jména: 1945-1951\]; *MADETA, mlékařské
> družstvo táborské, zapsaná společnost s ručením omezeným v Táboře*
> \[datace použití jména: 1945-1951\]; *MADETA, mlékařské družstvo
> táborské, z.s. s r.o. v Táboře* \[datace použití jména: 1945-1951\];
> *MADETA, mlékařské družstvo táborské, s.r.o.* \[datace použití jména:
> 1945-1951\]; *Made in Tábor*; *MADETA*
>
> *Poznámka k typu založení: Společnost se sama založila na ustavující
> valné hromadě 28. 4. 1901.* *Preferované označení bylo zvoleno podle
> kritéria e) jméno po dobu existence entity nejdéle používané (**viz
> kapitolu 6.3.5**)*.
>
> K64.2: ***Madeta, n. p. Tábor** (Tábor, Tábor, Česko : 1951-1960),
> mlékárenský výrobní podnik*
>
> VAR: *Madeta, n.p., Tábor*; *Madeta n.p. Tábor*; *Madeta n. p. Tábor*;
> *Madeta, národní podnik, Tábor*; *Madeta Tábor*; *Made in Tábor*;
> *MADETA*
>
> *Poznámka: Příklad řeší jen období samostatné existence podniku.*
>
> K64.3: ***MADETA a. s.** (České Budějovice, České Budějovice, Česko :
> 1995-), mlékárenský výrobní podnik* \[datace použití jména: 2006-; typ
> formy jména: úřední\]
>
> VAR: *Madeta akciová společnost* \[datace použití jména: 2006-\]*;
> MADETA Group a. s.* \[datace použití jména: 2005-2006; typ formy
> jména: úřední\]; *MADETA Group akciová společnost* \[datace použití
> jména: 2005-2006\]; *MADETA Group* \[datace použití jména: 2005-2006;
> typ formy jména: zjednodušená podoba\]; *JIHOMILK, akciová společnost*
> \[datace použití jména: 1995-2005; typ formy jména: úřední\];
> *JIHOMILK, a. s.* \[datace použití jména: 1995-2005\]*; Jihomilk*
> \[datace použití jména: 1995-2005; typ formy jména: zjednodušená
> podoba\]*; Madeta* \[datace použití jména: 2005-; typ formy jména:
> zjednodušená podoba\].
>
> *Poznámka: Preferované označení bylo zvoleno podle kritéria b) jméno,
> pod nímž je entita nejvíce známá (v současnosti a v českém prostředí)
> (**viz kapitolu 6.3.5**). Variantní označení vycházejí ze změn
> zapsaných v obchodním rejstříku. V takových případech je uveden typ
> formy jména „úřední“.*
>
> K65.1: ***Elite, n. p. Chrudim** (Chrudim, Chrudim, Česko :
> 1949-1989), výrobní podnik zaměřený na produkci textilu* \[datace
> použití jména: 1958-1989\]
>
> VAR: *Elite, n. p. Varnsdorf.* Závod Elite Chrudim \[datace použití
> jména: 1958-1989\]; *Elite, národní podnik Varnsdorf.* Závod Elite
> Chrudim \[datace použití jména: 1958-1989\]; *Elitka Chrudim* \[datace
> použití jména: 1958-1989\]; *Elite Chrudim* \[datace použití jména:
> 1958-1989\]; *Elite, národní podnik, Chrudim*; *Elite, národní podnik
> Chrudim*; *Elite, n. p.*; *Elite, národní podnik; Eva, n. p. Chrudim*
> \[datace použití jména: 1949-1958\]; *Eva Chrudim* \[datace použití
> jména: 1949-1958\]; *Eva, národní podnik Chrudim* \[datace použití
> jména: 1949-1958\]; *Eva, n. p.*; *Eva, národní podnik*
>
> *Poznámka: Preferované označení bylo zvoleno podle kritéria e) jméno
> po dobu existence entity nejdéle používané (viz kapitolu 6.3.5).*
>
> K65.2: ***Evona, s. p. Chrudim** (Chrudim, Chrudim, Česko :
> 1989-1993), výrobní podnik zaměřený na produkci textilu*
>
> VAR: *Evona Chrudim*; *Evona, s.p., Chrudim*; *Evona, s.p. Chrudim*;
> *Evona, státní podnik, Chrudim*; *Evona, státní podnik Chrudim*;
> *Evona, s.p.*; *Evona, s. p.*; *Evona, státní podnik*
>
> K65.3: ***Evona, s. p. Chrudim** (Chrudim, Chrudim, Česko :
> 1993-1994), zbytkový státní podnik pro vypořádání závazků z doby před
> privatizací*
>
> K65.4: ***Evona s.r.o.** (Chrudim, Chrudim, Česko : 1992-2002),
> výrobní podnik zaměřený na produkci textilu* \[datace použití jména:
> 1994-2002\]
>
> VAR: *Evona Chrudim*; *Evona, společnost s ručením omezeným* \[datace
> použití jména: 1994-2002\];  
> *E V O N A s.r.o.* \[datace použití jména: 1994-2002; typ formy jména:
> úřední\]; *DITEX,* *s.r.o.* \[datace použití jména: 1992-1994\]; *D
> I T E X ,* *s.r.o.* \[datace použití jména: 1992-1994; typ formy
> jména: úřední\]; *DITEX, společnost s ručením omezeným* \[datace
> použití jména: 1992-1994\]; *DITEX* \[datace použití jména: 1992-1994;
> typ formy jména: zjednodušená podoba\]; *EVONA* *DITEX s. r. o.*
> \[datace použití jména: 1994\]
>
> *Poznámka: Podnik Ditex je v obchodním rejstříku považován za
> předchůdce firmy Evona s. r. o. Management firmy privatizoval státní
> podnik, jehož vedením byl současně pověřen, proto se překrývají datace
> existence. Preferované označení bylo zvoleno podle kritéria e) jméno
> po dobu existence entity nejdéle používané (viz kapitolu 6.3.5).
> Variantní označení vycházejí ze změn zapsaných v obchodním rejstříku
> vč. tvaru „D I T E X , s.r.o.“. V takových případech je uveden typ
> formy jména „úřední“.*
>
> K65.5: ***Evona a. s.** (Chrudim, Chrudim, Česko : 2002-), výrobní
> podnik* *zaměřený na produkci textilu*
>
> VAR: *Evona Chrudim* \[typ formy jména: zjednodušená\]; *Evona, a.s.*;
> *Evona a.s.*; *Evona a. s.*; *Evona, akciová společnost*
>
> K66.1: ***SPT Praha, s. p.** (Praha, Česko : 1989-1993), poskytovatel
> telekomunikačních služeb* \[datace použití jména: 1989-1992\]
>
> VAR: *SPT Praha, státní podnik* \[datace použití jména: 1989-1992\];
> *Správa pošt a telekomunikací* *Praha,* *s. p.* \[datace použití
> jména: 1989-1992\]; *Správa pošt a telekomunikací Praha, státní
> podnik* \[datace použití jména: 1989-1992\]; *SPT Telecom, státní
> podnik* \[datace použití jména: 1993\]; *SPT Telecom*; *Telecom*; *SPT
> Telecom, s. p.* \[datace použití jména: 1993\]; *Správa pošt
> a telekomunikací Telecom, státní podnik* \[datace použití jména:
> 1993\]; *Správa pošt a telekomunikací Telecom, s. p.* \[datace použití
> jména: 1993\]; *Telecom*
>
> *Poznámka: Preferované označení bylo zvoleno podle kritéria e) jméno
> po dobu existence entity nejdéle používané (**viz kapitolu 6.3.5**).*
>
> K66.2: ***SPT Telecom, s. p.** (Praha, Česko : 1994-2005),* *zbytkový
> státní podnik pro vypořádání závazků z doby před privatizací*
>
> VAR: *Telecom*
>
> K66.3: ***SPT Telecom, s. p. v likvidaci** (Praha, Česko : 2005),*
> *zbytkový státní podnik pro vypořádání závazků z doby před
> privatizací*
>
> VAR: *Telecom*
>
> K66.4: ***O2 Czech Republic a.s.*** *(Praha, Česko : 1993-),*
> *poskytovatel telekomunikačních služeb* \[datace použití jména: 2014-;
> typ formy jména: úřední\]
>
> VAR: *SPT TELECOM, akciová společnost, zkratka: SPT TELECOM a.s.*
> \[datace použití jména: 1993-1994; typ formy jména: úřední\]; *SPT
> TELECOM, akciová společnost, zkratka: SPT TELECOM,a.s.* \[datace
> použití jména: 1994-1998; typ formy jména: úřední\]; *SPT Telecom,
> a.s.* \[datace použití jména: 1998-2000; typ formy jména: úřední\];
> *Správa pošt a telekomunikací Telecom, akciová společnost* \[datace
> použití jména: 1998-2000\]; *SPT Telecom* \[datace použití jména:
> 1993-2000; typ formy jména: zjednodušená podoba\]; *Správa pošt
> a telekomunikací Telecom* \[datace použití jména: 1993-2000; typ formy
> jména: zjednodušená podoba\]; *Telecom* \[datace použití jména:
> 1993-2000; typ formy jména: zjednodušená podoba\]; *Český Telecom,
> a.s.* \[datace použití jména: 2000-2006; typ formy jména: úřední\];
> *Telefónica O2 Czech Republic,a.s.* \[datace použití jména: 2006; typ
> formy jména: úřední\]; *Telefónica O2 Czech Republic, a.s.* \[datace
> použití jména: 2006-2011; typ formy jména: úřední\]; *Telefónica O2
> Czech Republic, akciová společnost* \[datace použití jména:
> 2006-2011\]; *Telefónica Czech Republic, a.s.* \[datace použití jména:
> 2011-2014; typ formy jména: úřední\]; *Telefónica Czech Republic,
> akciová společnost* \[datace použití jména: 2011-2014\]; *O2 Czech
> Republic akciová společnost.* \[datace použití jména: 2014-\];
> *Telecom*
>
> *Poznámka: Preferované označení bylo zvoleno podle kritéria b) jméno,
> pod nímž je entita nejvíce známá (v současnosti a v českém prostředí)
> (**viz kapitolu 6.3.5**). Variantní označení vycházejí ze změn
> zapsaných v obchodním rejstříku. V takových případech je uveden typ
> formy jména „úřední“.*
>
> K67.1: ***Max Helling, OHG** (Újezdeček, Teplice, Česko : asi
> 1892-1940),* *výrobní podnik zaměřený na textilní výrobu*
>
> VAR: *Max Helling*, *offene Handelsgesellschaft*; *Max Helling, v. o.
> s.*; *Max Helling, veřejná obchodní společnost*; *Max Helling (firma :
> Újezdeček, Teplice, Česko : asi 1892-1940)*
>
> K67.2: ***Max Helling, Wirkwarenfabrik, K. G.** (Újezdeček, Teplice,
> Česko : 1940-1945),* *výrobní podnik zaměřený na textilní výrobu*
>
> VAR: *Max Helling, Wirkwarenfabrik, Kommanditgesellschaft*; *Max
> Helling, Wirkwarenfabrik, KG*; *Max Helling, továrna na stávkové
> zboží, k. s.*; *Max Helling, továrna na stávkové zboží, komanditní
> společnost*; *Max Helling (firma : Újezdeček, Teplice, Česko :
> 1940-1945)*
>
> K67.3: ***Max Helling, k. s., národní správa** (Nové Modlany, Krupka,
> Teplice, Česko : 1945-1946),* *výrobní podnik zaměřený na textilní
> výrobu*
>
> VAR: *Max Helling, komanditní společnost, národní správa*; *Max
> Helling, kom. spol., národní správa*
>
> K67.4: ***TOSTA, továrny stávkového zboží, n. p..** Závod 7, dříve Max
> Helling (Nové Modlany, Krupka, Teplice, Česko : 1946-působnost do
> 1947),* *výrobní podnik zaměřený na textilní výrobu*
>
> VAR: *TOSTA, továrny stávkového zboží, národní podnik. Závod 7, dříve
> Max Helling*

###### Příklady korporací provozujících tentýž výrobní objekt:

> K68.1: ***Jiří Beneš, automatický mlýn Janderov v Chrudimi** (Chrudim,
> Chrudim, Česko : 1931-1948), potravinářský výrobní podnik*
>
> VAR: *mlýn Benešův*; *Benešův mlýn*; *Janderovský mlýn*; *mlýn
> Janderovský*; *mlýn Janderov*
>
> K68.2: ***Mlýn Janderov, spol. s r. o.** (Chrudim, Chrudim, Česko :
> 1996-), potravinářský výrobní podnik*
>
> VAR: *Janderovský mlýn*; *mlýn Janderovský*; *mlýn Janderov*; *Mlýn
> Janderov s.r.o.*; *Mlýn Janderov, s. r. o.*; *Mlýn Janderov, s.r.o.*;
> *Mlýn Janderov s. r. o.*; *Mlýn Janderov spol. s r. o.*; *Mlýn
> Janderov spol. s r.o.*; *Mlýn Janderov, spol. s r. o.*; *Mlýn
> Janderov, spol. s r.o.*; *Mlýn Janderov, společnost s ručením
> omezeným*

###### Fyzické osoby jako podnikatelské subjekty:

> K69.1: ***D. R. Schöniger, litographische Kunstanstalt, Buch und
> Steindruckerei** (Ostrov, Ostrov, Karlovy Vary, Česko : 1911-1945),
> tiskařský podnik*
>
> VAR: *Dominik Robert Schöniger, litografický ústav, knihtiskárna
> a kamenotisk*; *Schöniger Ostrov*; *knihtiskárna Schöniger Ostrov*;
> *tiskárna Schöniger Ostrov*
>
> K69.2: ***Dominik Schöniger, knihtiskárna, národní správa** (Ostrov,
> Ostrov, Karlovy Vary, Česko : 1945-asi 1950), tiskařský podnik*
>
> VAR: *D. Schöniger, národní správa*; *Schöniger, národní správa
> Ostrov*; *Schöniger národní správa Ostrov*; *knihtiskárna Schöniger
> Ostrov národní správa*; *knihtiskárna Schöniger Ostrov, národní
> správa*; *tiskárna Schöniger Ostrov, národní správa*; *tiskárna
> Schöniger Ostrov národní správa*
>
> K70: ***Ing. Václav Vlk** (firma : Zelený pruh, Praha, Česko : 1994-),
> podnikatel provozující nákup a prodej zboží*
>
> VAR: *Vlk Praha*; *Inženýr Václav Vlk*; *obchod Vlk Praha*
>
> *Poznámka: Fyzická osoba podnikající dle živnostenského zákona
> nezapsaná v obchodním rejstříku. Zelený pruh je jméno ulice.*
>
> K71: ***Agentura Barnum** (Chrudim, Chrudim, Česko : 1990-), reklamní
> nevýrobní podnik*
>
> VAR: *Barnum*; *Jiří Polanský*; *Polanský Jiří*; *Reklamní agentura
> Barnum*
>
> *Poznámka: Profesionální výtvarný umělec (živnostník) používající
> korporativní pseudonym.*
>
> K72: ***Bystřický a spol., s. r. o.** (Krč, Praha, Česko : 2004-),
> nevýrobní podnik poskytující software a poradenství v oblasti hardware
> a software*
>
> VAR: *Bystřický a spol., s.r.o.*; *Bystřický a spol. s. r. o*;
> *Bystřický a spol. s.r.o.*; *Bystřický a společníci, společnost
> s ručením omezeným*

#### Podtřída politické organizace

> K73: ***Panská jednota** (1394-1405),* *opoziční uskupení vysoké
> šlechty nespokojené s vládou krále Václava IV.*
>
> K74: ***Republikánská strana zemědělského a malorolnického lidu.**
> Místní organizace Hradec Králové (Hradec Králové, Hradec Králové,
> Česko : 1922-1938), místní organizace politické strany*
>
> VAR: *agrárníci.* Místní organizace Hradec Králové; *RSZML.* Místní
> organizace Hradec Králové
>
> K75: ***Strana zelených** (Praha, Česko : 1989-), politická strana*
>
> VAR: *Zelení*; *SZ*

#### Podtřída náboženské organizace a instituce

> K76: ***Arcibiskupství Praha** (římskokatolické : Praha, Česko :
> 1344-), vyšší regionální organizační jednotka římskokatolické církve*
>
> VAR: *Arcibiskupství pražské*; *Římskokatolická církev.* Arcidiecéze
> Praha; *Archiepiscopatus Pragensis*; *Erzbistum Prag*; *Horní
> konzistoř* \[datace použití jména: 1471-1561\]
>
> K77: ***Farní úřad Abertamy** (římskokatolický : Abertamy, Karlovy
> Vary, Česko : asi 1647-2004), místní organizační jednotka
> římskokatolické církve*
>
> VAR: *Pfarramt Abertham*; *Fara Abertamy*; *Farní úřad církve
> římskokatolické Abertamy*; *Römisch-Katholisch Pfarramt in Abertham*;
> *farnost Abertamy; FÚ Abertamy; Římskokatolická farnost Abertamy*
> \[datace použití jména: 2002-2004\]
>
> *Poznámka: Farnost byla zrušena k 31. 12. 2004 sloučením
> s Římskokatolickou farností Ostrov.*
>
> K78: ***Farní úřad Praha - Staré Město** (řeckokatolický : Praha,
> Česko : 1969-), místní organizační jednotka řeckokatolické církve*
>
> VAR: *Farní úřad řeckokatolické církve u svatého Klimenta Praha -
> Staré Město*; *Farní úřad u svatého Klimenta; Řeckokatolická farnost
> u svatého Klimenta v Praze* \[datace použití jména: 1994-\]*; FÚ u sv.
> Klimenta; FÚ Praha - Staré Město*
>
> K79: ***Israelitische Kultusgemeinde Eger** (Cheb, Cheb, Česko :
> 1872-1938), organizační jednotka židovské náboženské komunity*
>
> VAR: *Židovská náboženská obec Cheb*
>
> K80: ***Beerdigungsbrüderschaft Chewra Kadischa Eger** (Cheb, Cheb,
> Česko : 1899-1938), židovské náboženské sdružení*
>
> VAR: *Pohřební bratrstvo Chewra Kadischa Cheb*; *Pohřební bratrstvo
> chevra kadiša Cheb*; *Chevra kadiša Cheb*
>
> K81: ***Církev československá husitská.** Náboženská obec Karlovy Vary
> (Karlovy Vary, Karlovy Vary, Česko), místní organizační jednotka
> církve*
>
> VAR: *Náboženská obec Církve československé husitské v Karlových
> Varech*; *CČSH.* Náboženská obec Karlovy Vary
>
> K82: ***Církev bratrská** (Praha, Česko : 1967-), protestantská,
> reformovaná a evangelikální církev*
>
> VAR: *Církev bratská*; *CB*

#### Podtřída kulturní, výchovné, výzkumné a zdravotnické organizace a instituce

> K83: ***Národní divadlo** (Praha, Česko : 1881-), instituce
> provozující veřejnou kulturní produkci*
>
> VAR: *Národní divadlo v Praze*; *ND Praha*; *ND v Praze*; *ND*; *Zlatá
> kaplička*
>
> K83.1: ***Univerzita Karlova.** Pedagogická fakulta (Praha, Česko :
> 1964-), fakulta vysoké školy*
>
> VAR: *Univerzita Karlova.* PdF; *Pedagogická fakulta Univerzity
> Karlovy*; *PdF Univerzity Karlovy*; *PdF UK*; *UK.* PdF; *Universitas
> Carolina.* Facultas Paedagogica
>
> K83.2: ***Univerzita Karlova.** Pedagogická fakulta. Katedra české
> literatury (Praha, Česko : asi 1964-), katedra vysoké školy*
>
> VAR: *Katedra české literatury Pedagogické fakulty Univerzity
> Karlovy*; *UK.* PdF. Katedra české literatury
>
> K83.3: ***Univerzita Karlova.** Lékařská fakulta v Plzni (Plzeň,
> Plzeň-město, Česko : 1959-), fakulta vysoké školy*
>
> VAR: *Univerzita Karlova.* Lékařská fakulta Plzeň; *Univerzita
> Karlova.* LF Plzeň; *Univerzita Karlova.* LF v Plzni; *Lékařská
> fakulta Univerzity Karlovy v Plzni*; *Plzeňská lékařská fakulta
> Univerzity Karlovy*; *UK.* LF Plzeň; *UK.* LF v Plzni; *LF Univerzity
> Karlovy v Plzni*; *Plzeňská LF Univerzity Karlovy*; *Plzeňská LF UK*
>
> K83.4: ***Ústav dějin Univerzity Karlovy a archiv Univerzity Karlovy**
> (Praha, Česko : 1990-),* *vědecká instituce v oblasti historie
> a archiv vysoké školy*
>
> VAR: *ÚDAUK*
>
> K83.5: ***Archiv Univerzity Karlovy** (Praha, Česko : 1990-),*
> *pracoviště Ústavu dějin Univerzity Karlovy a archiv Univerzity
> Karlovy*
>
> VAR: *AUK*
>
> K83.6: ***Ústav dějin Univerzity Karlovy** (Praha, Česko : 1990-),*
> *pracoviště Ústavu dějin Univerzity Karlovy a archivu Univerzity
> Karlovy*
>
> K84: ***Národní*** ***technická knihovna** (Praha, Česko : 1960-),
> instituce zajišťující knihovnické a informační služby* \[datace
> použití jména: 2009-\]
>
> VAR: *STK* \[datace použití jména: 1960-2009\]; *Státní technická
> knihovna* \[datace použití jména: 1960-2009\]; *NTK* \[datace použití
> jména: 2009-\]
>
> K85: ***Archiv DIAMO** (Příbram, Příbram, Česko : 2005-), akreditovaný
> archiv*
>
> VAR: *Podnikový archiv DIAMO*; *Archiv podniku DIAMO; Archiv podniku
> Diuranát amonný*
>
> *Poznámka: Archiv byl v roce 2005 akreditován podle archivního zákona
> č. 499/2004 Sb.*
>
> K86: ***Správa státního hradu a zámku Horšovský Týn** (Horšovský Týn,
> Domažlice, Česko),* *místní pracoviště specializovaného orgánu pro
> památkovou péči*
>
> VAR: *Národní památkový ústav.* Územní památková správa v Českých
> Budějovicích. Správa státního hradu a zámku Horšovský Týn; *NPÚ.* ÚPS
> ČB. Správa státního hradu a zámku Horšovský Týn
>
> K87: ***Zoologická a botanická zahrada Plzeň** (Plzeň, Plzeň-město,
> Česko : 1981-), instituce pro chov a ochranu zvířat a pro pěstování
> a ochranu rostlin*
>
> VAR: *ZOO Plzeň*; *Zoologická zahrada Plzeň*; *Zoologická a botanická
> zahrada města Plzně*; *Zoologická a botanická zahrada města Plzně, p.
> o.*; *Zoologická a botanická zahrada města Plzně, p.o.*; *Zoologická
> a botanická zahrada města Plzně, příspěvková organizace*; *Botanická
> zahrada Plzeň*
>
> K88: ***Lázeňský dům Tosca** (léčebné zařízení : Karlovy Vary, Karlovy
> Vary, Česko), léčebné zařízení služeb pro ministerstvo vnitra*
>
> VAR: *Zařízení služeb pro Ministerstvo vnitra.* Lázeňský komplex
> Tosca; *Tosca*
>
> K89: ***Léčebna dlouhodobě nemocných Nejdek** (Nejdek, Karlovy Vary,
> Česko : 1980-), zdravotnické zařízení hospitalizační* \[datace použití
> jména: 1980-2013\]
>
> VAR: *Léčebna dlouhodobě nemocných v Nejdku* \[datace použití jména:
> 1980-2013\]; *Léčebna dlouhodobě nemocných, příspěvková organizace
> Nejdek*; *Léčebna dlouhodobě nemocných, p. o. Nejdek*; *LDN Nejdek*
> \[datace použití jména: 1980-2013\]; *LDN v Nejdku* \[datace použití
> jména: 1980-2013\]; *Eldéenka Nejdek; Zařízení následné rehabilitační
> a hospicové péče Nejdek* \[datace použití jména: 2013-\]; *Zařízení
> následné rehabilitační a hospicové péče v Nejdku* \[datace použití
> jména: 2013-\]; *Zařízení následné rehabilitační a hospicové péče,
> příspěvková organizace Nejdek* \[datace použití jména: 2013-\]; *REHOS
> - Zařízení následné rehabilitační a hospicové péče Nejdek* \[datace
> použití jména: 2013-\]; *REHOS Nejdek* \[datace použití jména: 2013-\]
>
> K90: ***Ústav sociální péče pro dospělé občany Horní Bříza,
> příspěvková organizace** (Horní Bříza, Plzeň-sever, Česko : 1974-),
> zařízení denní sociální péče* \[datace použití jména: 1974-2007; typ
> formy jména: úřední\]
>
> VAR: *Ústav sociální péče pro dospělé občany v Horní Bříze* \[datace
> použití jména: 1974-2007; typ formy jména: zjednodušená podoba\];
> *Ústav sociální péče pro dospělé občany Horní Bříza* \[datace použití
> jména: 1974-2007; typ formy jména: zjednodušená podoba\]; *Ústav
> sociální péče pro dospělé občany Horní Bříza, p. o.* \[datace použití
> jména: 1974-2007\]; *ÚSP Horní Bříza* \[datace použití jména:
> 1974-2007; typ formy jména: zkratka/akronym\]; *ÚSP v Horní Bříze*
> \[datace použití jména: 1974-2007; typ formy jména: zkratka/akronym\];
> *Domov pro osoby se zdravotním postižením Horní Bříza, příspěvková
> organizace* \[datace použití jména: 2007-; typ formy jména: úřední\];
> *Domov pro osoby se zdravotním postižením Horní Bříza, p. o.* \[datace
> použití jména: 2007-\]; *Domov pro seniory Horní Bříza* \[datace
> použití jména: 2007-; typ formy jména: zjednodušená podoba\]; *Domov
> Horní Bříza* \[datace použití jména: 2007-; typ formy jména:
> zjednodušená podoba\]
>
> *Poznámka: Variantní označení vycházejí ze změn zapsaných v obchodním
> rejstříku. V takových případech je uveden typ formy jména „úřední“.*

#### Podtřída nadace a nadační fondy

> K91: ***Dr. P. Maurus Pfannerer´sche Schulstiftung*** *(Krásné Údolí,
> Krásné Údolí, Karlovy Vary, Česko : 1892-asi 1938),* *nadace určená na
> podporu chudých žáků*
>
> VAR: *Doktor Pater Maurus Pfannerer´sche Schulstiftung*; *Dr. P.
> Maurus Pfannerersche Schulstiftung*; *Školní nadace Dr. Pátera Maura
> Pfannerera*; *Školní nadace Maura Pfannerera*; *Pfannererova školní
> nadace*
>
> *Poznámka: Nadace byla spravována a příspěvky z ní byly rozdělovány
> obecním zastupitelstvem města Krásné Údolí.*
>
> K92: ***Jubilejní nadace učitelstva okresu novobydžovského** (Nový
> Bydžov, Hradec Králové, Česko : 1897-působnost do 1953),* *instituce
> provozující nadační činnost*
>
> K93: ***Nadace pro záchranu a obnovu památky I. kategorie Zámek
> Horšovský Týn** (Horšovský Týn, Domažlice, Česko : 1994-1998),
> instituce provozující nadační činnost*
>
> VAR: *Nadace zámku Horšovský Týn*; *Nadace pro záchranu a obnovu zámku
> Horšovský Týn*; *Nadace pro záchranu a obnovu památky I. kategorie
> „Zámek Horšovský Týn“*
>
> K94: ***Nadační fond Českého rozhlasu** (Praha, Česko : 2000-),*
> *instituce provozující nadační činnost*

#### Podtřída profesní a zájmové organizace

> K95: ***Cech pekařů, mlynářů, krupařů Nechanice** (Nechanice, Hradec
> Králové, Česko : působnost od 1767-1860), sdružení řemeslníků
> a obchodníků*
>
> VAR: *Cech pekařů Nechanice*; *Cech mlynářů Nechanice*; *Cech krupařů
> Nechanice*; *Pekařský cech Nechanice*; *Mlynářský cech Nechanice*;
> *Krupařský cech Nechanice*; *Pekaři Nechanice*; *Mlynáři Nechanice*;
> *Krupaři Nechanice*
>
> K96: ***Lohgerberzunft Alt Zedlisch** (Staré Sedliště, Tachov, Česko :
> působnost od 1678-asi 1860), sdružení řemeslníků a obchodníků*
>
> VAR: *Cech koželuhů Staré Sedliště*; *Cech koželuhů ve Starém
> Sedlišti*; *Koželužský cech Staré Sedliště*; *Lohgerberzunft in Alt
> Zedlisch*; *Koželuzi* *Staré Sedliště*
>
> K97: ***Bäcker-, Müller- und Zimmerleute-Zunft Klentsch** (Klenčí pod
> Čerchovem, Domažlice, Česko : 1699-1860),* *sdružení řemeslníků
> a obchodníků* \[datace použití jména: 1699-1822\]
>
> VAR: *Cech pekařů, mlynářů a tesařů Klenčí pod Čerchovem* \[datace
> použití jména: 1699-1822\]; *Cech pekařů, mlynářů a tesařů v Klenčí
> pod Čerchovem* \[datace použití jména: 1699-1822\]; *Bäcker-, Müller-
> und Zimmerleute-Zunft in Klentsch* \[datace použití jména:
> 1699-1822\]; *Ehrbare Handtwerckher der Peckhen, Müller und
> Zimmerleuth in dem Hochfreyherrlichen Stadionische Markht Klenitsch*;
> *Ehrsame Becken, Müller, Zimerleuther Zunft im Marcktl Klentsch;
> Bäcker-, Müller-, Zimmerleute- und Lohgärber-Zunft in Klentsch*
> \[datace použití jména: 1822-1860\]; *Cech pekařů, mlynářů, tesařů
> a koželuhů Klenčí pod Čerchovem* \[datace použití jména: 1822-1860\];
> *Cech pekařů, mlynářů, tesařů a koželuhů v Klenčí pod Čerchovem*
> \[datace použití jména: 1822-1860\]
>
> *Poznámka: Preferované označení bylo zvoleno podle kritéria e) jméno
> po dobu existence entity nejdéle používané (**viz kap. 6.3.5**)*.
> *V únoru 1822 požádal před celým cechovním shromážděním Martin Kohout,
> koželužský tovaryš, aby směl vstoupit do cechu. Došlo proto ke změně
> jména korporace.*
>
> K98: ***Obchodní a živnostenská komora Plzeň** (Plzeň, Plzeň-město,
> Česko : 1850-1948), profesní sdružení podnikatelů*
>
> VAR: *Obchodní a živnostenská komora v Plzni*; *Handels- und
> Gewerbe-Kammer in Pilsen*; *Handels- und Gewerbekammer in Pilsen*;
> *OŽK Plzeň*; *OŽK v Plzni*
>
> K99: ***Odborový svaz kovodělníků.** Místní skupina Chlumec nad
> Cidlinou (Chlumec nad Cidlinou,* *Hradec Králové, Česko :
> 1897-působnost do 1928), místní skupina organizace zajišťující ochranu
> práv zaměstnanců*
>
> VAR: *OSK.* Místní skupina Chlumec nad Cidlinou
>
> K100: ***Republikánský svaz Československých statkářů a nájemců
> v Praze.** Odbočka Plzeň (Plzeň, Plzeň-město, Česko :
> 1928-1943), profesní sdružení zemědělců*
>
> VAR: *Svaz českých statkářů a nájemců v Praze.* Odbočka Plzeň \[datace
> použití jména: 1939-1943\]
>
> K101: ***Hospodářská komora České republiky** (Praha, Česko : 1993-),
> profesní sdružení podnikatelů*
>
> VAR: *Hospodářská komora ČR*; *HK ČR*

#### Podtřída spolky, společenské organizace

> K102: ***Vlastenecko-hospodářská společnost** (Praha, Česko :
> 1788-1872), zájmové zemědělské sdružení*
>
> VAR: *C. k. Vlastenecko-hospodářská společnost v království Českém*;
> *Císařsko-královská* *Vlastenecko-hospodářská společnost v království
> Českém*; *K. k. Ökonomisch-Patriotische Gesellschaft im Königreiche
> Böhmen; Kaiserliche königliche Ökonomisch-Patriotische Gesellschaft im
> Königreiche Böhmen*
>
> K103.1: ***Sokol (<span style="color:red;text-decoration:line-through">Praha, Česko : </span>1889-1952), <span style="color:red">zájmové tělovýchovné sdružení</span>***
>
> VAR: *Česká obec sokolská*; *Československá obec sokolská*; *Č.O.S.*;
> *Č. O. S.*; *ČOS*
>
> K103.2: ***Sokol (<span style="color:red;text-decoration:line-through">Praha, Česko : </span>1990-), <span style="color:red">zájmové tělovýchovné sdružení</span>***
>
> VAR: *Česká obec sokolská*; *Č.O.S*.; *Č. O. S*.; *ČOS*
>
> <span style="color:red">K103.3: ***Sokol. Předsednictvo České obce sokolské (Praha, Česko : 1990-), nejvyšší řídící orgán zájmového tělovýchovného sdružení***</span>
>
> <span style="color:red">VAR: Česká obec Sokolská; Sokol. Předsednictvo ČOS; Česká obec
> sokolská. Předsednictvo; Č.O.S. Předsednictvo; Č. O. S.
> Předsednictvo; ČOS. Předsednictvo</span>
>
> K104.1: ***Sokol.** Tělocvičná jednota Karlovy Vary (Karlovy Vary,
> Karlovy Vary, Česko : 1919-1952), místní organizace zájmového
> tělovýchovného sdružení*
>
> VAR: *T. J. Karlovy Vary*; *T.J. Karlovy Vary*; *TJ Karlovy Vary*;
> *Československá obec Sokolská.* Tělocvičná jednota Karlovy Vary
>
> K104.2: ***Sokol.** Tělocvičná jednota Karlovy Vary (Karlovy Vary,
> Karlovy Vary, Česko : 1990-), místní organizace zájmového
> tělovýchovného sdružení*
>
> VAR: *T. J. Karlovy Vary*; *T.J. Karlovy Vary*; *TJ Karlovy Vary*;
> *Česká obec Sokolská.* Tělocvičná jednota Karlovy Vary
>
> K105: ***Výbor pro postavení památníku padlým Nový Hradec Králové**
> (Nový Hradec Králové, Hradec Králové, Hradec Králové, Česko : 1923),
> místní zájmové sdružení pro podporu konkrétního záměru*
>
> K106: ***Česká archivní společnost** (Praha, Česko : 1990-), odborné
> sdružení*
>
> VAR: *Česká archivní společnost, o. s.*; *Česká archivní společnost,
> občanské sdružení*; *Česká archivní společnost, z. s.* \[doba
> používání jména od: 13. 5. 2016\]; *Česká archivní společnost, zapsaný
> spolek* \[doba používání jména od: 13. 5. 2016\]; *ČAS*
>
> *Poznámka: Změna z občanského sdružení na zapsaný spolek nepatří mezi
> ty změny korporativnosti, v jejichž případě se vytváří nový archivní
> autoritní záznam (**viz kapitolu 9.2.1**).*
>
> K107: ***Svaz knihovníků a informačních pracovníků České republiky**
> (Praha, Česko : 1990-),* *odborné sdružení*
>
> VAR: *Svaz knihovníků a informačních pracovníků České republiky z.s.*
> \[doba používání jména od: 18. 2. 2020\]; *Svaz knihovníků
> a informačních pracovníků České republiky zapsaný spolek* \[doba
> používání jména od: 18. 2. 2020\]; *SKIP*
>
> K108: ***Sdružení hasičů Čech*, *Moravy a Slezska*** *(Praha, Česko :
> 1991-), ústřední řídící organizace zájmového hasičského sdružení*
>
> VAR: *SH ČMS*
>
> K109: ***Sbor dobrovolných hasičů Žilina*** *(Žilina, Kladno, Česko :
> 1996-), místní organizace zájmového hasičského sdružení*
>
> VAR: *SDH Žilina*; *SH ČMS.* Sbor dobrovolných hasičů Žilina;
> *Sdružení hasičů Čech, Moravy a Slezska.* Sbor dobrovolných hasičů
> Žilina; *SH ČMS.* SDH Žilina
>
> K110: ***Společenství vlastníků jednotek domu č.p. 708 a č.p. 709,
> Majakovského 31 a 33, Karlovy Vary** (Rybáře, Karlovy Vary, Karlovy
> Vary, Česko : 2000-), organizace vlastníků bytů*
>
> VAR: *SVJ domu č.p. 708 a č.p. 709, Majakovského 31 a 33*;
> *Společenství vlastníků jednotek domu čp. 708 a čp. 709, Majakovského
> 31 a 33, Karlovy Vary*; *SVJ Majakovského 31 a 33*

###### Vnitřní organizační jednotka (pobočný spolek) uváděná s nadřízenou korporací:

> K111: ***Sportovní klub Chrudim.** Fotografický odbor (Chrudim,
> Chrudim, Česko : působnost 1901),* *odbor místního zájmového
> sportovního sdružení*
>
> VAR: *SK Chrudim.* Fotografický odbor; *Fotografický odbor SK
> Chrudim*; *Fotografický odbor Sportovního klubu Chrudim*
>
> K112: ***Československá obec legionářská.** Místní jednota Skuteč
> (Skuteč, Chrudim, Česko : 1921-1948), místní organizace sdružení
> vojenských veteránů*
>
> VAR: *Místní jednota Československé obce legionářské ve Skutči*;
> *ČSOL.* Místní jednota Skuteč; *ČSOL Skuteč*

#### Další příklady z třídy korporace

###### Vnitřní organizační jednotky uváděné v preferovaném označení s nadřízenými korporacemi a bez nich:

Poznámka: Vnitřní organizační jednotky se uvádějí bez hierarchicky
nadřazených celků pouze, pokud je jejich samostatné označení
srozumitelné, nezaměnitelné a obecně vžité.

> K113.1: ***Rakousko 1867-1918.** K. k. Handelsministerium.
> Lokalbahnamt (Vídeň, Rakousko : 1894-1896), organizační součást
> ministerstva obchodu pro záležitostí místních drah*
>
> VAR: *Úřad místních drah*; *C. k. Ministerstvo obchodu.* Úřad místních
> drah; *Ministerstvo obchodu.* Úřad místních drah; *Císařsko-královské
> Ministerstvo obchodu*. Úřad místních drah; *Kaiserlich-königliches
> Handelsministerium.* Lokalbahnamt
>
> K113.2: ***Rakousko 1867-1918.** K. k. Eisenbahnministerium.
> Lokalbahnamt (Vídeň, Rakousko : 1896-?), organizační součást
> ministerstva železnic pro záležitostí místních drah*
>
> VAR: *Úřad místních drah*; *C. k. Ministerstvo železnic.* Úřad
> místních drah; *Ministerstvo železnic Vídeň.* Úřad místních drah;
> *Císařsko-královské Ministerstvo železnic*. Úřad místních drah;
> *Kaiserlich-königliches Eisenbahnministerium.* Lokalbahnamt
>
> K114: ***Česko.** Úřad pro zastupování státu ve věcech majetkových.
> Referát Chrudim (Chrudim, Chrudim, Česko : 2002-2010), regionální
> orgán pro správu majetku státu; zastupování státu, resp. jeho
> organizačních složek před soudy, rozhodci nebo stálými rozhodčími
> soudy, jinými správními úřady a dalšími orgány*
>
> VAR: *Úřad pro zastupování státu ve věcech majetkových.* Územní
> pracoviště Hradec Králové. Odbor Odloučené pracoviště Pardubice.
> Referát Chrudim; *Česko.* Úřad pro zastupování státu ve věcech
> majetkových. Územní pracoviště Hradec Králové. Odbor Odloučené
> pracoviště Pardubice. Referát Chrudim; ÚZSVM *Hradec Králové.* Odbor
> Odloučené pracoviště Pardubice. Referát Chrudim
>
> K115: ***Státní okresní archiv Pardubice** (Pardubice, Pardubice,
> Česko : 2002-), státní archiv s regionální působností*
>
> VAR: *Česká republika – Státní oblastní archiv v Hradci Králové.* Státní
> okresní archiv Pardubice; *ČR – Státní oblastní archiv v Hradci Králové.*
> Státní okresní archiv Pardubice; *SOA Hradec Králové.* SOkA Pardubice; *SOkA
> Pardubice*
>
> *Poznámka: „Česká republika“, resp. „ČR“ není v případě státních
> oblastních archivů jurisdikce, nýbrž část jména používaná ve
> specifických případech.*

###### Korporace s totožnými názvy:

> K116.1: ***Místní národní výbor Lhotka** (Lhotka, Frýdek-Místek, Česko
> : 1945-1990),* *úřad místní lidové správy a přenesené státní správy*
>
> VAR: *MNV Lhotka*
>
> K116.2: ***Místní národní výbor Lhotka** (Lhotka, Přerov, Česko :
> 1945-1975), úřad místní lidové správy a přenesené státní správy*
>
> VAR: *MNV Lhotka*

###### Korporace se dvěma sídly:

> K117: ***Místní národní výbor Nová Ves** (Diana, Rozvadov, Tachov,
> Česko : 1946-1960), úřad místní lidové správy a přenesené státní
> správy*
>
> VAR: *MNV Nová Ves*
>
> *Poznámky:*
>
> *Po požáru obce v roce 1946 sídlil MNV Nová Ves trvale v osadě Diana,
> která byla v té době místní částí Nové Vsi. Sídla původce v sekci
> Vztahy proto budou:*
>
> *sídlo 1: „Nová Ves (Třemešné, Tachov, Česko)“*
>
> *sídlo 2: „Diana (Rozvadov, Tachov, Česko)“ – od roku 1946.*
>
> *V geografickém doplňku je uvedeno posledně známé sídlo korporace (viz
> **kapitolu 9.3.1**).*

###### Pověřená úřední fyzická osoba korporativního charakteru:

> K118: ***Městský lékař Rybáře** (Karlovy Vary, Karlovy Vary, Česko :
> 1891-asi 1946), orgán zdravotního a epidemiologického dohledu*
>
> VAR: *Stadtarzt Fischern*

###### Fáze vývoje korporace:

> K119.1: ***Farní škola Přibyslavice** (Přibyslavice, Třebíč, Česko :
> působnost od 17. st.-1774), škola základního všeobecného vzdělávání*
>
> VAR: *Pfarrschule Přibyslavice*; *Pfarrschule Przibislawitz*
>
> K119.2: ***Triviální škola Přibyslavice** (Přibyslavice, Třebíč, Česko
> : 1774-1869), škola základního všeobecného vzdělávání*
>
> VAR: *Trivialschule Přibyslavice*; *Trivialschule Przibislawitz*;
> *Farní škola Přibyslavice*; *Triviální farní škola Přibyslavice*
>
> K119.3: ***Obecná škola Přibyslavice** (Přibyslavice, Třebíč, Česko :
> 1869-1948), škola základního všeobecného vzdělávání*
>
> VAR: *Volksschule Přibyslavice*; *Volksschule Przibislawitz*
>
> K119.4: ***Národní škola Přibyslavice** (Přibyslavice, Třebíč, Česko :
> 1948-1961), škola základního všeobecného vzdělávání*
>
> K119.5: ***Základní devítiletá škola Přibyslavice** (Přibyslavice,
> Třebíč, Česko : 1961-1978), škola základního všeobecného vzdělávání*
>
> VAR: *ZDŠ Přibyslavice*
>
> K119.6: ***Základní škola Přibyslavice** (Přibyslavice, Třebíč, Česko
> : 1978-1990), škola základního všeobecného vzdělávání*
>
> VAR: *ZŠ Přibyslavice*
>
> *Poznámka: Škola s osmiletou docházkou.*
>
> K119.7: ***Základní škola Přibyslavice** (Přibyslavice, Třebíč, Česko
> : 1990-2002), škola základního všeobecného vzdělávání*
>
> VAR: *ZŠ Přibyslavice*
>
> *Poznámka: Škola s devítiletou docházkou.*
>
> K119.8: ***Základní škola Přibyslavice, p. o.** (Přibyslavice, Třebíč,
> Česko : 2003-), škola základního všeobecného vzdělávání*
>
> VAR: *ZŠ Přibyslavice*; *Základní škola Přibyslavice, příspěvková
> organizace*
>
> K120.1: ***Exponirte Unterlehrerstation** **Fischern** (Rybáře,
> Karlovy Vary, Karlovy Vary, Česko : 1848-1863), zařízení základního
> všeobecného vzdělávání*
>
> VAR: *Školní expozitura Rybáře*; *Školní expozitura v Rybářích*;
> *Exponirte Schulgehilfenstation Fischern*; *Pfarrschul-Expositur in
> Fischern*; *Schul-Expositur Fischern*; *Schulexpositur in Fischern*;
> *Farní škola Sedlec*. Expozitura Rybáře; *Pfarrschule Zettlitz*.
> Exponirte Unterlehrerstation Fischern; *Odloučené podučitelské místo
> v Rybářích*; *Wanderschule in Fischern* \[datace použití jména:
> 1848-1858\]; *Putovní škola v Rybářích* \[datace použití jména:
> 1848-1858\]
>
> *Poznámka: Jako putovní škola (něm. Wanderschule) byla korporace
> označována v době před výstavbou samostatné školní budovy v roce 1858.
> Do té doby se totiž výuka prováděla v jednotlivých soukromých domech,
> které byly po týdnu vždy střídány.*
>
> K120.2: ***Filialschule Fischern** (Rybáře, Karlovy Vary, Karlovy
> Vary, Česko : 1863-1870), škola základního všeobecného vzdělávání*
>
> VAR: *Filialschule in Fischern*; *Filiální škola Rybáře*; *Filiální
> škola v Rybářích*; *Farní škola Sedlec*. Filiální škola Rybáře;
> *Triviální škola Rybáře*; *Trivialschule Fischern*; *Trivialschule in
> Fischern*
>
> K120.3: ***Volksschule Fischern** (Rybáře, Karlovy Vary, Karlovy Vary,
> Česko : 1870-1897), škola základního všeobecného vzdělávání*
>
> VAR: *Obecná škola Rybáře*; *Obecná škola v Rybářích*; *Národní škola
> Rybáře*; *Národní škola v Rybářích*; *Volksschule in Fischern*;
> *gemischte Volksschule in Fischern*; *smíšená Obecná škola v Rybářích*
>
> *Poznámka: Tehdy platný zemský školní zákon č. 22/1870 českého z. z.,
> překládá německý termín „Volksschule“ označením „škola národní“.*
>
> K120.4: ***Mädchen-Volksschule Fischern** (Rybáře, Karlovy Vary,
> Karlovy Vary, Česko : 1897-1910), škola základního všeobecného
> vzdělávání pro dívky*
>
> VAR: *Dívčí obecná škola Rybáře*; *Dívčí obecná škola v Rybářích*;
> *Obecná dívčí škola v Rybářích*; *Mädchen-Volksschule in Fischern*;
> *Mädchenvolksschule in Fischern*
>
> *Poznámka: Od 1. 9. 1897 byla tehdejší smíšená Obecná škola v Rybářích
> rozdělena na dvě samostatné korporace – chlapeckou obecnou školu
> a dívčí obecnou školu. Výše uvedená dívčí obecná škola zůstala
> v původní budově v Rybářích-Staré Město, kdežto chlapecká obecná škola
> (**viz příklad K120.5**) byla záhy nato přestěhována do nové školní
> budovy v Rybářích-Nové Město.*
>
> K120.4.1: ***I. Volksschule Fischern** (Rybáře, Karlovy Vary, Karlovy
> Vary, Česko : 1910-1920), škola základního všeobecného vzdělávání*
>
> VAR: *I. Obecná škola Rybáře*; *I. Obecná škola v Rybářích*; *I.*
> *Volksschule in Fischern*; *gemischte I.* *Volksschule in Fischern*
>
> *Poznámka: V roce 1910 byl školní obvod celého tehdejšího města Rybáře
> rozdělen do dvou celků – I. školní obvod (Rybáře-Staré Město
> a Rybáře-Horní Nové Město) a II. školní obvod (Rybáře-Nové Město).
> Dosavadní Dívčí obecná škola Rybáře, která sídlila v Rybářích-Staré
> Město a byla určena pro žákyně z celého původního školního obvodu,
> byla změněna na smíšenou (chlapeckou a dívčí) školu a sloužila pouze
> pro žáky a žákyně pouze z I. školního obvodu (odtud i označení
> korporace).*
>
> K120.4.1.1: ***I. Mädchen-Volksschule Fischern** (Rybáře, Karlovy
> Vary, Karlovy Vary, Česko : 1921-1945), škola základního všeobecného
> vzdělávání pro dívky*
>
> VAR: *I. Dívčí obecná škola Rybáře*; *I. Dívčí obecná škola
> v Rybářích*; *I. Obecná dívčí škola v Rybářích*; *I.*
> *Mädchen-Volksschule in Fischern*; *I.* *Mädchenvolksschule in
> Fischern*; *1. Mädchen-Volksschule in Fischern*; *1.
> Mädchen-Volksschule in Karlsbad-Fischern* \[datace použití jména:
> 1939-1945\]
>
> *Poznámka: Od 1. 1. 1921 byla tehdejší smíšená I. Obecná škola
> v Rybářích rozdělena na dvě samostatné korporace – I. Chlapeckou
> obecnou školu a I. Dívčí obecnou školu. V roce 1939 bylo město Rybáře
> připojeno k sousednímu městu Karlovy Vary, proto je v označení
> korporace doložen i název sídla „Karlsbad-Fischern“.*
>
> K120.4.1.2: ***I. Knaben-Volksschule Fischern** (Rybáře, Karlovy Vary,
> Karlovy Vary, Česko : 1921-1945), škola základního všeobecného
> vzdělávání pro chlapce*
>
> VAR: *I. Chlapecká obecná škola Rybáře*; *I. Chlapecká obecná škola
> v Rybářích*; *I. Obecná chlapecká škola v Rybářích*; *I.*
> *Knaben-Volksschule in Fischern*; *I.* *Knabenvolksschule in Fischern*
>
> *Poznámka: Viz poznámku v předcházejícím příkladě.*
>
> K120.5: ***Knaben-Volksschule Fischern** (Rybáře, Karlovy Vary,
> Karlovy Vary, Česko : 1897-1910), škola základního všeobecného
> vzdělávání pro chlapce*
>
> VAR: *Chlapecká obecná škola Rybáře*; *Chlapecká obecná škola
> v Rybářích*; *Knaben-Volksschule in Fischern*; *Knabenvolksschule in
> Fischern*
>
> *Poznámka: Od 1. 9. 1897 byla tehdejší smíšená Obecná škola v Rybářích
> rozdělena na dvě samostatné korporace – chlapeckou obecnou školu
> a dívčí obecnou školu. Dívčí obecná škola zůstala v původní budově
> v Rybářích-Staré Město, kdežto chlapecká obecná škola byla záhy nato
> přestěhována do novostavby školy v Rybářích-Nové Město. Následující
> fáze vývoje této korporace jsou obdobné jako **v příkladech K120.4.1,
> K120.4.1.1, K120.4.1.2.**, tedy II. Volksschule Fischern v letech
> 1910-1920, II. Mädchen-Volksschule Fischern v letech 1921-1945 a II.
> Knaben-Volksschule Fischern v letech 1921-1945.*
>
> K121.1: ***Bürgerschule Fischern*** *(Rybáře, Karlovy Vary, Karlovy
> Vary, Česko : 1903-1940), škola základního všeobecného vzdělávání*
>
> VAR: *Měšťanská škola Rybáře*; *Měšťanská škola v Rybářích*;
> *Bürgerschule in Fischern*; *gemischte Bürgerschule in Fischern*;
> *Bürgerschule in Karlsbad-Fischern* \[datace použití jména:
> 1939-1945\]; *gemischte Bürgerschule in Karlsbad-Fischern* \[datace
> použití jména: 1939-1945\]; *Měšťanská škola v Karlových
> Varech-Rybářích*; *smíšená* *Měšťanská škola v Karlových
> Varech-Rybářích*
>
> *Poznámka: V roce 1939 bylo tehdejší město Rybáře připojeno
> k sousednímu městu Karlovy Vary, proto je v označení korporace doložen
> i název sídla „Karlsbad-Fischern“.*
>
> K121.1.1: ***Mädchen***-***Bürgerschule Karlsbad-Fischern*** *(Rybáře,
> Karlovy Vary, Karlovy Vary, Česko : 1940-1941), škola základního
> všeobecného vzdělávání pro dívky*
>
> VAR: *Dívčí měšťanská škola Karlovy Vary-Rybáře*; *Dívčí* *měšťanská
> škola v Karlových Varech-Rybářích*; *Mädchenbürgerschule in
> Karlsbad-Fischern*; *Mädchenbürgerschule in Fischern*; *Měšťanská
> dívčí* *škola v Karlových Varech-Rybářích*
>
> *Poznámka: Od 1. 10. 1940 byla tehdejší smíšená Měšťanská škola
> v Karlových Varech-Rybářích rozdělena na dvě samostatné korporace –
> chlapeckou měšťanskou školu a dívčí měšťanskou školu.*
>
> K121.1.2: ***Hauptschule für Mädchen Karlsbad-Fischern*** *(Rybáře,
> Karlovy Vary, Karlovy Vary, Česko : 1941-1945), škola základního
> všeobecného vzdělávání pro dívky*
>
> VAR: *Hlavní škola pro dívky Karlovy Vary-Rybáře*; *Hlavní škola pro
> dívky v Karlových Varech-Rybářích*; *Hauptschule für Mädchen in
> Karlsbad-Fischern*; *Hauptschule für Mädchen in Fischern*; *Hlavní
> škola pro dívky v Rybářích*; *Dívčí hlavní škola v Rybářích*; *Hlavní
> dívčí škola v Rybářích*
>
> *Poznámka: Hlavní školy byly zavedeny od počátku školního roku (11. 9.
> 1941) na základě Zákona o změně říšského zákona o povinné školní
> docházce (něm. „Gesetz zur Änderung des Reichsschulpflichtgesetzes“)
> z 16. 5. 1941, vydáno v Reichsgesetzblatt I, 1941, s. 282.*
>
> K121.2.1: ***Knaben***-***Bürgerschule Karlsbad-Fischern*** *(Rybáře,
> Karlovy Vary, Karlovy Vary, Česko : 1940-1941), škola základního
> všeobecného vzdělávání pro chlapce*
>
> VAR: *Chlapecká měšťanská škola Karlovy Vary-Rybáře*; *Chlapecká
> měšťanská škola v Karlových Varech-Rybářích*; *Knabenbürgerschule in
> Karlsbad-Fischern*
>
> *Poznámka: **Viz příklad K121.1.1**.*
>
> K121.2.2: ***Hauptschule für Jungen Karlsbad-Fischern*** *(Rybáře,
> Karlovy Vary, Karlovy Vary, Česko : 1941-1945), škola základního
> všeobecného vzdělávání pro dívky*
>
> VAR: *Hlavní škola pro chlapce Karlovy Vary-Rybáře*; *Hlavní škola pro
> chlapce v Karlových Varech-Rybářích*; *Hauptschule für Knaben in
> Karlsbad-Fischern*; *Hauptschule für Knaben in Fischern*; *Hlavní
> škola pro chlapce v v Rybářích*; *Chlapecká hlavní škola v Rybářích*;
> *Hlavní chlapecká škola v Rybářích*; *6 kl. Hauptchule für Knaben in
> Fischern*; *6-klassige Hauptschule für Knaben in Fischern*; *6-třídní
> hlavní škola pro chlapce v Rybářích*; *III. Hauptschule für Jungen in
> Karlsbad-Fischern*; *III. Hlavní škola pro chlapce v Karlových
> Varech-Rybářích*; *Hauptschule für Jungen in Karlsbad-Fischern*;
> *Hauptschule für J. in Karlsbad-Fischern*
>
> *Poznámka: **Viz příklad K121.1.2**.*
>
> K122.1: ***Obecná škola Mnichov** (Mnichov, Cheb, Česko : 1945-1948),
> škola základního všeobecného vzdělávání*
>
> VAR: *Obecná škola v Mnichově*
>
> K122.2: ***Národní škola Mnichov** (Mnichov, Cheb, Česko : 1948-1961),
> škola základního všeobecného vzdělávání*
>
> VAR: *Národní škola v Mnichově*
>
> K122.3: ***Základní devítiletá škola Mnichov** (Mnichov, Cheb, Česko :
> 1961-1979), škola základního všeobecného vzdělávání*
>
> VAR: *Základní devítiletá škola v Mnichově*; *ZDŠ Mnichov*; *ZDŠ
> v Mnichově*
>
> K123.1: ***Výzkumný ústav Silva Taroucy pro krajinu a okrasné
> zahradnictví, příspěvková organizace** (Průhonice, Praha-západ, Česko
> : 2000-2006), botanické vědeckovýzkumné zařízení*
>
> VAR: *Výzkumný ústav Silva Taroucy pro krajinu a okrasné zahradnictví,
> p. o.*; *Výzkumný ústav Silva Taroucy pro krajinu a okrasné
> zahradnictví, přísp.o.*; *Výzkumný ústav Silva Taroucy pro krajinu
> a okrasné zahradnictví*; *Výzkumný ústav Silva Taroucy pro krajinu
> a okrasné zahradnictví Průhonice*; *VÚKOZ*; *VÚKOZ Průhonice*
>
> K123.2: ***Výzkumný ústav Silva Taroucy pro krajinu a okrasné
> zahradnictví, v. v. i.** (Průhonice, Praha-západ, Česko : 2007-),
> botanické vědeckovýzkumné zařízení*
>
> VAR: *Výzkumný ústav Silva Taroucy pro krajinu a okrasné
> zahradnictví*; *Výzkumný ústav Silva Taroucy pro krajinu a okrasné
> zahradnictví Průhonice*; *Výzkumný ústav Silva Taroucy pro krajinu
> a okrasné zahradnictví, v.v.i.*; *Výzkumný ústav Silva Taroucy pro
> krajinu a okrasné zahradnictví, veřejná výzkumná instituce*; *VÚKOZ*;
> *VÚKOZ Průhonice*

###### Shoda jména korporace se jménem jiné entity:

> K124: ***Budovatel** (<span style="color:red">redakce : </span>Chrudim, Chrudim, Česko : 1950-1990),
> orgán pro řízení obsahové a věcné náplně periodika*
>
> VAR: *Budovatel: orgán chrudimského OV KSČ a ONV* \[datace použití
> jména: 1965-1990\]; *Budovatel: orgán chrudimského okresního výboru
> Komunistické strany Československa a okresního národního výboru*
> \[datace použití jména: 1965-1990\]; *Budovatel chrudimského okresu:
> orgán chrudimského OV KSČ a rady ONV* \[datace použití jména:
> 1960-1964\]; *Budovatel chrudimského okresu: orgán chrudimského
> okresního výboru Komunistické strany Československa a rady okresního
> národního výboru* \[datace použití jména: 1960-1964\]; *Budovatel
> chrudimského okresu* \[datace použití jména: 1960-1964\]; *Budovatel
> chrudimského venkova: týdenní vesnické noviny* \[datace použití jména:
> 1950-1959\]; *Budovatel chrudimského venkova* \[datace použití jména:
> 1950-1959\]

###### Korporace, která nevznikla:

> K125: ***Vyšší průmyslová škola kožešnická Hlinsko** (Hlinsko,
> Chrudim, Česko), škola středního vzdělávání, kterou se přes snahy
> v letech 1890-1899 nepodařilo založit*

###### Zahraniční korporace:

> K126: ***Sicherheitsdienst*** *(Berlín, Německo : 1931-1945), vnitřní
> zpravodajská služba*
>
> VAR: *SD*; *Bezpečnostní služba*
>
> *Poznámka: V českém prostředí je tato korporace všeobecně známa pod
> německým označením.*
>
> K127: ***Koncentrační tábor Buchenwald*** *(Výmar, Německo :
> 1937-1945), zařízení k internaci vězňů*
>
> VAR: *Konzentrationslager Buchenwald*; *KL Buchenwald*; *KZ
> Buchenwald*; *Buchenwald concentration camp*
>
> *Poznámka: V českém prostředí je tato korporace všeobecně známa pod
> českým označením. Buchenwald jako nižší sídelní jednotka je uvedena
> **v příkladu G159**.*
>
> K128: ***Německo.** Spolkový úřad pro ochranu ústavy* *(Kolín nad
> Rýnem, Německo : 1950-), civilní vnitřní zpravodajská služba*
>
> VAR: *Bundesamt für Verfassungsschutz*; *BfV*
>
> *Poznámka: V českém prostředí je tato korporace známa pod českým
> označením.*
>
> K129: ***Deutsche Bank** (Frankfurt nad Mohanem, Německo : 1957-),
> peněžní ústav*
>
> VAR: *Deutsche Bank Aktiengesellschaft; Deutsche Bank AG; Německá
> banka a. s.; Německá banka akciová společnost*
>
> *Poznámka: V českém prostředí je tato korporace všeobecně známa pod
> německým označením.*

###### Fiktivní korporace:

> K130: ***Jafeta**, fiktivní podnik zaměřený na produkci oděvů v románu
> Lidé na křižovatce*

### Třída Událost

Příklad 1 – archivní autoritní záznam entity pro ostatní role
(s výjimkou role původce – viz příklad 2)

|                                                                                                                             |                                                   |
|-----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| ***sjezd Komunistické strany Československa** (9 : 1949 : Praha, Česko), stranický sjezd vládnoucí strany v Československu* |                                                   |
| PREF: Hlavní část jména                                                                                                     | sjezd Komunistické strany Československa          |
| PREF: Pořadí události                                                                                                       | 9                                                 |
| PREF: Chronologický doplněk                                                                                                 | 1949                                              |
| PREF: Geografický doplněk                                                                                                   | Praha, Česko                                      |
| PREF: Obecný doplněk                                                                                                        | neuvádí se                                        |
| VAR: Hlavní část jména                                                                                                      | IX\. sjezd KSČ                                    |
| VAR: Hlavní část jména                                                                                                      | 9\. sjezd KSČ                                     |
| Stručná charakteristika                                                                                                     | stranický sjezd vládnoucí strany v Československu |
| Vznik: způsob vzniku                                                                                                        | začátek                                           |
| Vznik: datace                                                                                                               | 25.5.1949                                         |
| Zánik: způsob zániku                                                                                                        | konec                                             |
| Zánik: datace                                                                                                               | 29.5.1949                                         |

Příklad 2 – archivní autoritní záznam entity jakožto původce

|                                                                                                                             |                                                                                                                                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ***sjezd Komunistické strany Československa** (9 : 1949 : Praha, Česko), stranický sjezd vládnoucí strany v Československu* |                                                                                                                                                                                                                                                                                              |
| PREF: Hlavní část jména                                                                                                     | sjezd Komunistické strany Československa                                                                                                                                                                                                                                                     |
| PREF: Pořadí události                                                                                                       | 9                                                                                                                                                                                                                                                                                            |
| PREF: Chronologický doplněk                                                                                                 | 1949                                                                                                                                                                                                                                                                                         |
| PREF: Geografický doplněk                                                                                                   | Praha, Česko                                                                                                                                                                                                                                                                                 |
| PREF: Obecný doplněk                                                                                                        | neuvádí se                                                                                                                                                                                                                                                                                   |
| PREF: Typ formy jména                                                                                                       | úřední                                                                                                                                                                                                                                                                                       |
| VAR: Hlavní část jména                                                                                                      | IX\. sjezd KSČ                                                                                                                                                                                                                                                                               |
| VAR: Hlavní část jména                                                                                                      | 9\. sjezd KSČ                                                                                                                                                                                                                                                                                |
| VAR: Typ formy jména                                                                                                        | zkratka/akronym                                                                                                                                                                                                                                                                              |
| Stručná charakteristika                                                                                                     | stranický sjezd vládnoucí strany v Československu                                                                                                                                                                                                                                            |
| Vznik: způsob vzniku                                                                                                        | začátek                                                                                                                                                                                                                                                                                      |
| Vznik: typ                                                                                                                  | vznik zahájením činnosti                                                                                                                                                                                                                                                                     |
| Vznik: datace                                                                                                               | 25.5.1949                                                                                                                                                                                                                                                                                    |
| Vznik: vztah – specifikace „místo“                                                                                          | Praha, Česko                                                                                                                                                                                                                                                                                 |
| Vznik: vztah – specifikace „organizátor, svolavatel“                                                                        | Komunistická strana Československa                                                                                                                                                                                                                                                           |
| Zánik: způsob zániku                                                                                                        | konec                                                                                                                                                                                                                                                                                        |
| Zánik: typ                                                                                                                  | zánik ukončením činnosti                                                                                                                                                                                                                                                                     |
| Zánik: datace                                                                                                               | 29.5.1949                                                                                                                                                                                                                                                                                    |
| Zánik: vztah – specifikace „místo“                                                                                          | Praha, Česko                                                                                                                                                                                                                                                                                 |
| Dějiny                                                                                                                      | Sjezd se konal ve dnech 25. – 29. května 1949 v Průmyslovém paláci v Praze. Zúčastnilo se ho 2346 delegátů. Předsedou strany byl zvolen Klement Gottwald, generálním tajemníkem Rudolf Slánský. Jednalo se o první sjezd Komunistické strany Československa po převzetí moci v únoru 1948... |
| Související entity – specifikace „místo konání“                                                                             | Praha, Česko                                                                                                                                                                                                                                                                                 |
| Související entity – specifikace „vazba na objekt“                                                                          | Průmyslový palác (Praha, Česko : stavba)                                                                                                                                                                                                                                                     |
| Související entity – specifikace „souborná událost, celek“                                                                  | sjezdy Komunistické strany Československa                                                                                                                                                                                                                                                    |
| Související entity – specifikace „tematický celek“                                                                          | sjezdy (setkání)                                                                                                                                                                                                                                                                             |

#### Podtřída organizované akce a události

###### Jednorázové akce:

> Příklad U1: ***války růží** (1455-1485 : Velká Británie), občanská
> válka v Anglii mezi spojenci rodů Lancasterů a Yorků*
>
> VAR: *válka růží*; *Wars of the Roses*
>
> U2: ***třicetiletá válka** (1618-1648 : Evropa), evropský ozbrojený
> konflikt*
>
> VAR: *30letá válka*
>
> U3: ***staroměstská exekuce** (1621 : Praha, Česko), hromadná poprava
> dvaceti sedmi vůdců stavovského povstání*
>
> VAR: *staroměstská poprava*, *poprava 27 českých pánů*
>
> U4: ***Francouzská revoluce** (1789-1799 : Francie), radikální změna
> politického režimu ve Francii*
>
> VAR: *revoluce velká francouzská*; *Révolution française de 1789*;
> *Velká francouzská revoluce*; *Velká francouzská buržoazní revoluce*
>
> U5: ***bitva na Marně** (1914 : Francie), bitva první světové války*
>
> VAR: *první bitva na Marně*; *první bitva na řece Marně*; *1. bitva na
> Marně*
>
> U6: ***bitva u Zborova** (1917 : Zborov, Tarnopol, Ukrajina), bitva
> československých legionářů s rakousko-uherskými a německými vojsky na
> východní frontě první světové války*
>
> VAR: *Zborovská bitva*; *Zborov, bitva*; Зборовское сражение
>
> U7: ***letní olympijské hry** (14 : 1948 : Londýn, Velká Británie),
> 14. ročník novodobých letních olympijských her*
>
> VAR: *14. letní olympijské hry*; *XIV. letní olympijské hry*
>
> U8: ***akce Z **(1964 : Most, Most, Česko), výpomoc občanů při
> rekonstrukci veřejného osvětlení*
>
> VAR: *akce Z Most*; *akce Z v Mostě*
>
> U9: ***Jízda králů** (2008 : Kunovice, Uherské Hradiště, Česko :
> slavnost), lidová slavnost konaná ve městě Kunovice*
>
> U10: ***INFORUM 2013** (19 : Praha, Česko : konference), 19. ročník
> konference o profesionálních informačních zdrojích*
>
> U11: ***Celostátní archivní konference. Archivy, člověk a krajina**
> (16 : 2015 : Poděbrady, Poděbrady, Česko), konference s tématem
> historické prameny a životní prostředí*
>
> U12.1: ***Jeden svět** (21 : 2019 : Česko : filmový festival), 21.
> ročník českého festivalu dokumentárních filmů věnovaných problematice
> lidských práv*
>
> VAR: *filmový festival Jeden svět*; *One world*
>
> U12.2: ***Jeden svět. Festivalové místo kino Atlas Praha** (2019 :
> Praha, Česko : filmový festival), část festivalu dokumentárních filmů
> věnovaných problematice lidských práv konaná v Praze*
>
> U12.3: ***Jeden svět. Festivalové místo Městské divadlo Benešov**
> (2019 : Benešov, Benešov, Česko : filmový festival), část festivalu
> dokumentárních filmů věnovaných problematice lidských práv konaná
> v Benešově*

###### Zastřešující události:

> U13.1: ***olympijské hry** (8. st. př. n. l.-5. st. : Olympie, Řecko),
> původní sportovní hry v antickém Řecku*
>
> VAR: *olympiády*; *hry olympijské*; *antické olympijské hry*;
> *starověké olympijské hry*; *Ολύμπια*
>
> U13.2: ***olympijské hry** (1896-), novodobé sportovní hry navazující
> na tradici antických olympijských her*
>
> VAR: *olympiády*; *hry olympijské*; *Jeux olympiques*
>
> U13.3: ***letní olympijské hry** (1896-), novodobé sportovní hry
> navazující na tradici antických olympijských her*
>
> VAR: *letní* *olympiády*; *LOH*
>
> U14: ***Zahrada Čech** (1972- : Předměstí, Litoměřice, Litoměřice,
> Česko : veletrh), veletrh zemědělských produktů, zemědělských strojů a
> potřeb pro zemědělce a zahrádkáře*
>
> U15: ***sjezdy Komunistické strany Československa** (1921-1990 :
> Praha, Česko), stranické sjezdy KSČ*
>
> VAR: *Sjezdy KSČ*
>
> U16: ***Mezinárodní filmový festival Karlovy Vary** (1946- : Karlovy
> Vary, Karlovy Vary, Česko), největší filmový festival v České
> republice*
>
> VAR: *Filmový festival Karlovy Vary*; *MFF Karlovy Vary*; *MFFKV*;
> *Karlovy Vary International Film Festival*; *KVIFF*
>
> U17: ***Mapový okruh Vysočina** (1957- : Česko : fotografická soutěž),
> soutěž fotografických klubů z Česka a Slovenska*
>
> VAR: *Vysočina*
>
> U18: ***Jeden svět** (1999- : Česko : filmový festival), český
> festival dokumentárních filmů věnovaných problematice lidských práv*
>
> VAR: *filmový festival Jeden svět*; *One world*

#### Podtřída lidové zvyky, významné dny a svátky

###### Významné dny, svátky:

> U19: ***Velikonoce** (asi 50- : svátek), křesťanský svátek na oslavu
> zmrtvýchvstání Ježíše Krista*
>
> VAR: *pascha*
>
> U20: ***První máj** (1889- : svátek), mezinárodní dělnický svátek*
>
> VAR: *Svátek práce*; *International Workers‘ Day*; *May Day*; *1. máj*
>
> U21: ***Hromnice** (svátek), lidový svátek slavený 2. února*
>
> VAR: *Hypapante*; *Lichtmess*

###### Lidové zvyky:

> U22: ***Jízda králů** (asi 19. st.- : slavnost), lidový obyčej
> udržovaný na Slovácku a Hané*

#### Podtřída dočasné přírodní jevy

> U23: ***Katrina** (2005 : Amerika : hurikán), tropická cyklóna, která
> zasáhla jih Spojených států amerických a Mexický záliv*
>
> VAR: *hurikán Katrina*; *Hurricane Katrina*
>
> U24: ***Kyrill** (2007 : Evropa : bouře), tlaková níže vzniklá nad
> Atlantským oceánem, která se rozvinula do ničivé bouře se sílou orkánu
> a zasáhla Evropu*
>
> VAR: *orkán Kyrill*; *storm Kyrill*

### Třída Dílo/výtvor

Příklad 1 – základní údaje o entitě

|                                                                                                                                                                                             |                                                                       |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| ***svatí Cyril a Metoděj** (Ludvík Šimek a Bedřich Otto Seeling : Karlovo náměstí, Třebíč, Třebíč, Česko : sousoší), sousoší světců pořízené k 1 000. výročí příchodu věrozvěstů na Moravu* |                                                                       |
| PREF: Hlavní část jména                                                                                                                                                                     | svatí Cyril a Metoděj                                                 |
| PREF: Autor/tvůrce                                                                                                                                                                          | Ludvík Šimek a Bedřich Otto Seeling                                   |
| PREF: Geografický doplněk                                                                                                                                                                   | Karlovo náměstí, Třebíč, Třebíč, Česko                                |
| PREF: Obecný doplněk                                                                                                                                                                        | sousoší                                                               |
| PREF: Chronologický doplněk                                                                                                                                                                 | neuvádí se                                                            |
| VAR: Hlavní část jména                                                                                                                                                                      | sousoší svatých Cyrila a Metoděje                                     |
| VAR: Hlavní část jména                                                                                                                                                                      | sv. Cyril a Metoděj                                                   |
| Stručná charakteristika                                                                                                                                                                     | sousoší světců pořízené k 1 000. výročí příchodu věrozvěstů na Moravu |
| Vznik: způsob vzniku                                                                                                                                                                        | vznik                                                                 |
| Vznik: datace                                                                                                                                                                               | 1885                                                                  |

Příklad 2 – komplexní archivní autoritní záznam entity

<table>
<colgroup>
<col style="width: 38%" />
<col style="width: 61%" />
</colgroup>
<tbody>
<tr class="odd">
<td colspan="2"><em><strong>svatí Cyril a Metoděj</strong> (Ludvík Šimek a Bedřich Otto Seeling : Karlovo náměstí, Třebíč, Třebíč, Česko : sousoší), sousoší světců pořízené k 1 000. výročí příchodu věrozvěstů na Moravu</em></td>
</tr>
<tr class="even">
<td>PREF: Hlavní část jména</td>
<td>svatí Cyril a Metoděj</td>
</tr>
<tr class="odd">
<td>PREF: Autor/tvůrce</td>
<td>Ludvík Šimek a Bedřich Otto Seeling</td>
</tr>
<tr class="even">
<td>PREF: Geografický doplněk</td>
<td>Karlovo náměstí, Třebíč, Třebíč, Česko</td>
</tr>
<tr class="odd">
<td>PREF: Obecný doplněk</td>
<td>sousoší</td>
</tr>
<tr class="even">
<td>PREF: Chronologický doplněk</td>
<td>neuvádí se</td>
</tr>
<tr class="odd">
<td>PREF: Typ formy jména</td>
<td>uměle vytvořené</td>
</tr>
<tr class="even">
<td>VAR: Hlavní část jména</td>
<td>sousoší svatých Cyrila a Metoděje</td>
</tr>
<tr class="odd">
<td>VAR: Hlavní část jména</td>
<td>sv. Cyril a Metoděj</td>
</tr>
<tr class="even">
<td>VAR: Typ formy jména</td>
<td>zkratka/akronym</td>
</tr>
<tr class="odd">
<td>Stručná charakteristika</td>
<td>sousoší světců pořízené k 1 000. výročí příchodu věrozvěstů na Moravu</td>
</tr>
<tr class="even">
<td>Vznik: způsob vzniku</td>
<td>vznik</td>
</tr>
<tr class="odd">
<td>Vznik: typ</td>
<td>první realizace</td>
</tr>
<tr class="even">
<td>Vznik: datace</td>
<td>1885</td>
</tr>
<tr class="odd">
<td>Vznik: vztah – specifikace „autor/tvůrce“</td>
<td>Šimek, Ludvík (1837-1886), sochař a figuralista</td>
</tr>
<tr class="even">
<td>Vznik: vztah – specifikace „autor/tvůrce“ – poznámka</td>
<td>L. Šimek je autor návrhu sousoší</td>
</tr>
<tr class="odd">
<td>Vznik: vztah – specifikace „autor/tvůrce“</td>
<td>Seeling, Bernard Otto (1850-1895), sochař a restaurátor</td>
</tr>
<tr class="even">
<td>Vznik: vztah – specifikace „autor/tvůrce“ – poznámka</td>
<td>B. O. Seeling je tvůrce sousoší podle návrhu Ludvíka Šimka</td>
</tr>
<tr class="odd">
<td>Vznik: vztah – specifikace „dokument“</td>
<td>Pamětní spis k odhalení sousoší svatých Cyrila a Metoděje (Vilém Nikodém : rukopis)</td>
</tr>
<tr class="even">
<td>Dějiny</td>
<td>Sousoší svatých Cyrila a Metoděje, na které byla vyhlášena i veřejná sbírka, objednal organizační výbor u sochaře Ludvíka Šimka. Slavnostního odhalení a posvěcení se zúčastnil brněnský biskup František Saleský Bauer.</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „umístění“</td>
<td>Karlovo náměstí (Třebíč, Třebíč, Česko)</td>
</tr>
<tr class="even">
<td>Související entity – specifikace „vazba na objekt“</td>
<td>podstavec k sousoší svatých Cyrila a Metoděje (Josef Hraba : Karlovo náměstí, Třebíč, Třebíč, Česko)</td>
</tr>
<tr class="odd">
<td>Související entity – specifikace „majitel/držitel“</td>
<td>Městský úřad Třebíč (Třebíč, Třebíč, Česko : 1990-)</td>
</tr>
<tr class="even">
<td>Související entity – specifikace „pojmenováno po“</td>
<td><p>Cyril (svatý : 827-869)</p>
<p>Metoděj (arcibiskup a svatý : asi 813-885)</p></td>
</tr>
<tr class="odd">
<td>Souřadnice</td>
<td><em>zapisují se dle konkrétní implementace v IS</em></td>
</tr>
</tbody>
</table>


#### Podtřída autorská a umělecká díla

> Příklad D1.1: ***David** (Michelangelo Buonarroti : Via Ricasoli,
> Florencie, Itálie : socha), originál renesančního sochařského díla*
>
> VAR: *Michelangelův David*
>
> Příklad D1.2: ***David** (Michelangelo Buonarroti : Piazzale
> Michelangelo, Florencie, Itálie : socha), kopie renesančního
> sochařského díla*
>
> VAR: *Michelangelův David*
>
> Příklad D1.3: ***David** (Michelangelo Buonarroti : Piazza della
> Signoria, Florencie, Itálie : socha), kopie renesančního sochařského
> díla*
>
> VAR: *Michelangelův David*
>
> D2: ***svatý Jan Nepomucký** (Kožichovice, Třebíč, Česko : socha),
> socha umístěná na návsi obce*
>
> D3: ***Hlava muže v cylindru** (Emil Filla : obraz), kubistické dílo*
>
> D4: ***Bible svatá***
>
> D5: ***Bible kralická***
>
> D6.1: ***Kosmova kronika,** nejstarší kronika věnovaná historii
> českého státu*
>
> VAR: *Kronika česká*; *Kosmova kronika česká*; *Chronica Boemorum*
>
> D6.2: ***Třebíčský opis Kosmovy kroniky,** jeden z nejmladších opisů
> Kosmovy kroniky vzniklý ve skriptoriu benediktinského kláštera
> v Třebíči*
>
> D7: ***Libri citationum et sententiarum seu Knihy půhonné a nálezové**
> (Vincenc Brandl a Bertold Bretholz : kniha), edice historických
> pramenů*
>
> D8: ***S hrdostí nošený. Sokolský kroj, úbor a scénický kostým**
> (Šárka Rámišová : kniha), monografie o kroji a dalších typech oblečení
> organizace Sokol*
>
> D9: ***Archiv města Karlovy Vary** (Antonín Mařík : archivní pomůcka),
> inventář fondu*
>
> D10.1: ***Lidové noviny** (1893-1945), deník vydávaný v Brně
> a v Praze*
>
> VAR: *Lidovky*
>
> D10.2: ***Lidové noviny** (1948-1952), deník vydávaný v Praze*
>
> VAR: *Lidovky*
>
> D10.3: ***Lidové noviny** (1987-), samizdatové noviny, od roku 1990
> deník vydávaný v Praze*
>
> VAR: *Lidovky*
>
> D11: ***Zaklínač** (Andrzej Sapkowski : vícedílná kniha), literární
> dílo z fantasy žánru*
>
> VAR: *Witcher*; *Wiedźmin*
>
> D12: ***Louskáček** (Petr Iljič Čajkovskij : balet), baletní pohádka
> s vánoční tématikou*
>
> D13: ***Prodaná nevěsta** (Bedřich Smetana : opera), komická opera
> o třech dějstvích*
>
> VAR: *Prodanka*
>
> D14: ***Televarieté** (televizní pořad), televizní hudebně zábavný
> pořad Československé televize a České televize*

###### Díly, části, pořadí, vydání, překlady:

> D15: ***Časopis Národního musea. Oddíl přírodovědný, rok 1976, ročník
> 145, číslo 1**, odborný časopis*
>
> D16: ***Televarieté, 26. díl** (televizní pořad), televizní hudebně
> zábavný pořad Československé televize z roku 1977*
>
> D17: ***Zaklínač, VII. Paní jezera, pátý román o Geraltovi a Ciri**
> (Andrzej Sapkowski : kniha : 2017-), literární dílo z fantasy žánru*
>
> *Poznámka: Vyskytují se i vydání s jiným názvem (např. „Paní jezera.
> Pátá část ságy o Zaklínači“, vydání z roku 2003).*
>
> D18.1: ***La guerra de las salamandras** (Karel Čapek : kniha :
> 1978-), překlad českého románu Válka s mloky*
>
> D18.2: ***La guerra de las salamandras** (Karel Čapek : kniha :
> 2010-), překlad českého románu Válka s mloky*

###### Fáze vývoje periodika:

> D19.1.: ***Listy Hudební matice**, hudební časopis vycházející
> v letech 1921-1927*
>
> *Poznámka: Pod tímto jménem vycházel 1. – 6. ročník časopisu.*
>
> D19.2.: ***Tempo** (1927-1948), hudební časopis*
>
> VAR: *Tempo. Listy Hudební matice* \[datace použití jména:
> 1927-1935\]; *Tempo. List pro hudební kulturu* \[datace použití jména:
> 1935-1938\]; *Tempo. Hudební měsíčník* \[datace použití jména:
> 1946-1948\]
>
> *Poznámky:*
>
> *Pod těmito názvy vycházel 7. – 17. ročník časopisu.*
>
> *Rozlišení entit bylo provedeno podle Souborného katalogu ČR.*
>
> *Existovaly i další časopisy stejného jména.*
>
> D20: ***Západní Morava** (1997-), periodikum věnované regionální
> historii okresů Žďár nad Sázavou a Třebíč*
>
> VAR: *Západní Morava. Vlastivědný sborník* \[datace použití jména:
> 1997-2016\]; *Západní Morava. Vlastivědná revue* \[datace použití
> jména: 2017-\]

#### Podtřída všeobecně známé dokumenty, smlouvy, zákony, předpisy, normy

> D21: ***Zlatá bula sicilská,** listina vydaná Fridrichem II. českému
> králi Přemyslu Otakarovi I.*
>
> VAR: *Bulla Aurea Siciliæ*
>
> D22: ***Mírová smlouva mezi mocnostmi spojenými a sdruženými
> a Rakouskem podepsaná v Saint-Germain-en-Laye dne 10. září 1919,**
> smlouva formálně ukončující válečný stav*
>
> VAR: *Saintgermainská smlouva*; *Traité de Saint-Germain-en-Laye*
> \[francouzština\]; *Vertrag von Saint-Germain* \[němčina\]; *Treaty of
> Saint-Germain-en-Laye* \[angličtina\]
>
> D23: ***Smlouva o přátelství, spolupráci a vzájemné pomoci** (Varšava,
> Polsko : dokument), smlouva, na jejímž základě vznikl vojenský pakt
> zvaný Varšavská smlouva*
>
> VAR: *Varšavská smlouva*
>
> D24.1: ***Zákon č. 71/1967 Sb., o správním řízení /správní řád/,**
> procesní předpis upravující řízení před správním úřadem*
>
> VAR: *Správní řád*
>
> D24.2: ***Zákon č. 500/2004 Sb., správní řád,** základní procesní
> předpis upravující řízení před správním úřadem*
>
> VAR: *Správní řád*
>
> D24.3: ***Zákon č. 176/2018 Sb., zákon, kterým se mění zákon č.
> 500/2004 Sb., správní řád, ve znění pozdějších předpisů,** novela
> správního řádu*
>
> VAR: *Správní řád*
>
> D25: ***Management kvality. ČSN EN ISO 9001** (2009-), norma
> specifikující požadavky na řízení kvality*
>
> D26: ***Oznámení, kterým se zveřejňuje národní standard pro
> elektronické systémy spisové služby. Věstník Ministerstva vnitra,
> částka 64/2012***
>
> D27: ***Služební předpis č. 10 ředitele Státního oblastního archivu
> v Zámrsku ze dne 15. prosince 2016 Organizační řád Státního oblastního
> archivu v Zámrsku***
>
> VAR: *Organizační řád Státního oblastního archivu Zámrsk*;
> *Organizační řád Státního oblastního archivu v Zámrsku*; *Organizační
> řád SOA Zámrsk*

#### Podtřída vyznamenání, ceny, soutěžní trofeje

> D28.1: ***Nobelova cena**, ocenění Nobelovy nadace každoročně
> udělované za zásadní vědecký výzkum, technické objevy či za přínos
> lidské společnosti*
>
> VAR: *cena Nobelova*; *Nobelpriset*
>
> D28.2: ***Nobelova cena za fyziku**, ocenění Nobelovy nadace*
>
> VAR: *cena Nobelova za fyziku*; *Nobelpriset i fysik*
>
> D28.3: ***Nobelova cena** (Erik Lindberg : medaile : 1901-), medaile
> předávaná laureátům Nobelovy ceny za fyziku, chemii, lékařství
> a literaturu bez vyobrazení na zadní straně*
>
> D28.4: ***Nobelova cena** (Erik Lindberg : medaile : 1902-), medaile
> předávaná laureátům Nobelovy ceny za fyziku, chemii, lékařství
> a literaturu s oboustranným vyobrazením*
>
> D28.5: ***Nobelova cena za mír** (Gustav Vigeland : medaile), medaile
> předávaná laureátům Nobelovy ceny za mír*
>
> D29.1: ***Řád Bílého lva**, nejvyšší státní vyznamenání České
> republiky*
>
> VAR: *Československý řád Bílého lva*
>
> D29.2: ***Řád Bílého lva** (Michal Vitanovský : předmět : 1994-),
> insignie Řádu Bílého lva udělovaná oceněným od roku 1994*
>
> D30: ***Cena Alfréda Radoka**, výroční cena udělovaná za umělecké
> výkony v rámci českého divadla*

#### Podtřída výrobky a jejich typová označení, obchodní značky, odrůdy, plemena vytvořená člověkem

> D31.1: ***Supermarine Spitfire** (letadlo), stíhací letoun vyvinutý ve
> Velké Británii*
>
> VAR: *Spitfire*; *Spitfire Supermarine*; *Seafire*; *Spiteful*;
> *Seafang*
>
> D31.2: ***Supermarine Spitfire Mk. VB** (letadlo), výzbrojní varianta
> britského stíhacího letounu Supermarine Spitfire, verze Mk. V*
>
> VAR: *Spitfire Mk. V*; *Spitfire V*; *Spitfire Supermarine Mk. V*
>
> D32: ***Merkur** (stavebnice)*
>
> D33: ***Sharp** (televizní přístroj)*
>
> D34: ***Karlsbader Mineralwasser** (ochranná známka)*
>
> D35: ***Mattoni Karlovarské minerální vody** (ochranná známka)*
>
> D36: ***Becherovka** (likér), bylinný alkoholický nápoj vyráběný
> v Karlových Varech*
>
> D37: ***Tatranky Opavia***
>
> D38: ***Hitrádio Černá Hora** (rozhlasový program)*
>
> D39: ***Zlatá reneta** (odrůda), odrůda jablka*
>
> VAR: *reneta zlatá*
>
> D40: ***Shetlandský ovčák** (plemeno), plemeno psa vyšlechtěné na
> Shetlandských ostrovech*
>
> VAR: *sheltie*
>
> D41: ***Anglický plnokrevník** (plemeno), nejrychlejší plemeno koně*

#### Podtřída názvy společenských, dětských her

> D42: ***šachy** (desková hra), hra pro dva hráče*
>
> D43: ***mariáš** (hra), karetní hra původem z Německa*
>
> D44: ***slepá bába** (hra)*
>
> D45: ***Dostihy a sázky,** desková hra vytvořená v Československu
> inspirovaná celosvětovou deskovou hrou Monopoly*
>
> D46: ***Zaklínač** (počítačová hra)*

#### Podtřída programy, projekty, granty, rozvojové plány, kampaně, nemají-li charakter korporace

> D47: ***Marshallův plán** (rozvojový plán), organizovaná americká
> pomoc poválečné Evropě*
>
> VAR: *Plán evropské obnovy*
>
> D48: ***Lánská akce** (kampaň), organizovaný nábor pracovních sil*
>
> D49: ***Ani zrno nazmar** (kampaň)*
>
> D50: ***INTERPI** (výzkumný projekt), projekt vědecké a technologické
> infrastruktury pro podporu zpracování, sdílení a využívání kulturního
> obsahu*
>
> VAR: *Interoperabilita v paměťových institucích*
>
> D51: ***Zelená úsporám** (dotační program), program Ministerstva
> životního prostředí České republiky pro energetické úspory*
>
> D52: ***Ty to zvládneš** (kampaň), kampaň zaměřená na podání první
> pomoci*

#### Podtřída stavby, trasy, zásahy do přírodních útvarů s vlastním jménem nebo jinou identifikací

###### Existující dům:

> D53: ***Mydlářovský dům** (Břetislavova, Chrudim, Chrudim, Česko :
> stavba), renesanční existující dům, od roku 1972 sídlo Muzea
> loutkářských kultur Chrudim*
>
> VAR: *dům čp. 74/I*; *Mydlářovský dům Chrudim*; *Hytlovský dům
> Chrudim*; *Muzeum loutkářských kultur Chrudim*; *muzeum loutek
> Chrudim*

###### Zaniklý dům:

> D54: ***dům čp. 37/I (Filištínská, Chrudim, Chrudim, Česko : dům :
> asi 14. <span style="color:red">st.</span>-1995), zaniklý středověký dům***

###### Dům se stejným číslem popisným jako měl zaniklý dům:

> D55: ***dům čp. 37/I (Filištínská, Chrudim, Chrudim, Česko : dům :
> 1999-), existující dům postavený na místě zbořených domů čp. 37/I až
> 42/I***

###### Stadion známý pod různými jmény:

> D56: ***Letní stadion čp. 831/IV** (V Průhonech, Chrudim, Chrudim,
> Česko : stavba), všesportovní stadion*
>
> VAR: *Stadion Emila Zátopka Chrudim*; *Letní stadion Chrudim*;
> *Stadion MFK Chrudim*; *Stadion AFK Chrudim*; *Letní stadion AFK
> Chrudim*; *Atletický stadion Chrudim*; *Transporťácký stadion
> Chrudim*; *Stadion Transporty Chrudim*

###### Stavby:

> D57: ***Pražský hrad** (Hradčany, Praha, Česko : stavba), komplex
> budov; sídlo hlavy českého státu*
>
> D58: ***Bečov nad Teplou** (Bečov nad Teplou, Karlovy Vary, Česko :
> hrad a zámek), soubor historických staveb*
>
> VAR: *hrad a zámek Bečov nad Teplou*; *zámek a hrad Bečov nad Teplou*
>
> *Poznámka: Pro hrad a zámek mohou být též založeny samostatné archivní
> autoritní záznamy.*
>
> D59: ***Český Krumlov** (Český Krumlov, Český Krumlov, Česko : zámek),
> zámecký areál*
>
> VAR: *zámek Český Krumlov*
>
> *Poznámka: Jde o součást souboru staveb, k nimž patří i hrad.*
>
> D60: ***Točník** (Točník, Beroun, Česko : hrad), zřícenina hradu*
>
> VAR: *hrad Točník*; *zřícenina Točník*; *zřícenina hradu Točník*
>
> D61: ***Hradčany** (náměstí U svatého Jiří, Hradčany, Praha, Česko :
> klášter), areál bývalého ženského benediktinského kláštera na Pražském
> hradě*
>
> VAR: *klášter svatého Jiří*
>
> D62: ***Cheb** (Františkánské náměstí, Cheb, Cheb, Česko : klášter),
> areál bývalého františkánského kláštera*
>
> VAR: *klášter Cheb*; *františkánský klášter Cheb*
>
> D63: ***Plasy** (Plasy, Plzeň-sever, Česko : klášter), areál bývalého
> cisterciáckého kláštera*
>
> VAR: *klášter Plasy*
>
> D64: ***kostel Narození Panny Marie** (Přibyslavice, Třebíč, Česko :
> kostel), farní a poutní kostel*
>
> VAR: *přibyslavický kostel Narození Panny Marie*; *kostel Narození
> Panny Marie v Přibyslavicích*; *kostel Narození Panny Marie
> Přibyslavice*
>
> D65: ***kostel svaté Anny** (Přibyslavice, Třebíč, Česko : kostel),
> filiální raně románský kostel*
>
> VAR: *přibyslavický kostel svaté Anny*; *přibyslavický kostel sv.
> Anny*; *kostel svaté Anny v Přibyslavicích*; *kostel sv. Anny
> v Přibyslavicích*; *kostel svaté Anny Přibyslavice*; *kostel sv. Anny
> Přibyslavice*
>
> D66: ***kaple svaté Anny** (Opatov, Třebíč, Česko : kaple), samostatně
> stojící drobná sakrální stavba v pseudogotickém slohu*
>
> VAR: *opatovská kaple svaté Anny*; *opatovská kaple sv. Anny*; *kaple
> svaté Anny v Opatově*; *kaple sv. Anny v Opatově*; *kaple svaté Anny
> Opatov*; *kaple sv. Anny Opatov*
>
> D67: ***Mahenovo divadlo** (Brno, Brno-město, Česko : stavba), budova
> v eklektickém slohu*
>
> VAR: *budova Mahenova divadla*; *Mahenovo divadlo v Brně*; *Mahenovo
> divadlo Brno*; *brněnské Mahenovo divadlo*
>
> D68: ***Husa na provázku** (Brno, Brno-město, Česko : budova divadla)*
>
> VAR: *divadlo Husa na provázku*; *budova divadla Husa na provázku*
>
> D69: ***Oko** (Jejkov, Třebíč, Třebíč, Česko : budova kina)*
>
> VAR: *kino Oko Třebíč*; *třebíčské kino Oko*; *budova kina Oko
> Třebíč*; *budova kina Oko v Třebíči*
>
> D70: ***Paříž** (Staré Město, Praha, Česko : budova hotelu), raně
> secesní budova*
>
> VAR: *hotel Paříž Praha*; *hotel Paříž v Praze*; *pražský hotel Paříž*
>
> D71: ***Hajnišův mlýn** (Třebechovice pod Orebem, Třebechovice pod
> Orebem, Hradec Králové, Česko : stavba)*
>
> VAR: *třebechovický Hajnišův mlýn*
>
> D72: ***Tosca** (Karlovy Vary, Karlovy Vary, Česko : lázeňský
> komplex)*
>
> VAR: *lázně Tosca*
>
> D73: ***Lesná** (Brno, Brno-město, Česko : sídliště), panelové
> sídliště ve stejnojmenné části města*
>
> VAR: *sídliště Lesná*; *sídliště Lesná Brno*; *sídliště Lesná v Brně*;
> *brněnské sídliště Lesná*
>
> D74: ***Dalešice** (Dalešice, Třebíč, Česko : hráz), sypaná hráz
> k vodnímu dílu Dalešice*
>
> VAR: *Dalešická hráz*; *hráz Dalešice*

###### Části staveb:

> D75: ***kaple svatého Kříže** (Karlštejn, Beroun, Česko : kaple),
> kaple na hradě Karlštejn*
>
> VAR: *kaple svatého Kříže na Karlštejně*; *kaple sv. Kříže na
> Karlštejně*; *karlštejnská kaple svatého Kříže*; *karlštejnská kaple
> sv. Kříže*; *Svatokřížská kaple*; *Svatokřížská kaple Karlštejn*;
> *kaple svatého Kříže na Karlově Týně*
>
> D76: ***kaple v domě U Kamenného zvonu** (Staroměstské náměstí, Praha,
> Česko : kaple), kaple umístěná v přízemí domu*
>
> VAR: *kaple U Kamenného zvonu v Praze*; *kaple U Kamenného zvonu
> Praha*
>
> D77: ***Zlatá brána** (Hradčany, Praha, Česko : stavba), arkádová
> předsíň jižního vstupu do katedrály svatého Víta na Pražském hradě*
>
> VAR: *Zlatá brána Praha*; *Zlatá brána v Praze*; *svatovítská Zlatá
> brána*

###### Trasy:

> D78: ***Po stopách opatů a rabínů** (Podklášteří, Třebíč, Třebíč,
> Česko : naučná stezka), trasa vedoucí po památkách zapsaných na seznam
> UNESCO*
>
> D79: ***Veselské pískovny** (Veselí nad Lužnicí, Tábor, Česko : naučná
> stezka), trasa vedoucí oblastí štěrkových jezer*
>
> D80: ***linka 155** (Praha, Česko : autobusová linka)*
>
> D81: ***trasa C** (Praha, Česko : metro)*
>
> VAR: *trasa metra C Praha*; *trasa metra C v Praze*; *metro C*; *metro
> C v Praze*; *céčko*

###### Železniční trať na území dvou krajů:

> D82: ***Havlíčkův Brod - Pardubice** (Česko : železniční trať),
> železniční trať postavená společností Rakouská severozápadní dráha*
>
> VAR: *Pardubice - Havlíčkův Brod*; *Deutsch Brod - Pardubitz*;
> *Pardubitz - Deutsch Brod*; *železniční trať č. 238 Havlíčkův Brod -
> Pardubice*; *železniční trať Havlíčkův Brod - Pardubice*; želez*niční
> trať Pardubice - Havlíčkův Brod*; *železnice Havlíčkův
> Brod-Pardubice*; *železnice Pardubice-Havlíčkův Brod*

###### Skupinový vodovod na území dvou krajů:

> D83: ***Havlíčkův Brod - Pardubice** (Česko : vodovod), skupinový
> vodovod budovaný od šedesátých let 20. století*
>
> VAR: *Pardubice - Havlíčkův Brod*; *vodovod Pardubice - Havlíčkův
> Brod*; *vodovod Havlíčkův Brod - Pardubice*

###### Silnice na území jednoho okresu:

> D84: ***Rosice - Dědová - Dolní Bezděkov** (Chrudim, Česko : silnice),
> silnice č. II/343 budovaná od třicátých let 20. století*
>
> VAR: *silnice Rosice - Dědová - Dolní Bezděkov*; *silnice Dolní
> Bezděkov - Dědová - Rosice; II/343*

###### Zásahy do přírodních útvarů:

> D85: ***Lazy** (Karviná, Česko : důlní dílo), nečinný hlubinný důl na
> černé uhlí*
>
> VAR: *důl Lazy*; *důl Lazy u Orlové*
>
> D86: ***Kamenná** (Kamenná, Třebíč, Česko : kamenolom)*
>
> VAR: *kamenolom Kamenná*; *kamenolom Kamenná u Třebíče*

### Třída Geografický objekt

#### Vysvětlení k zápisu geografických doplňků

V zápisech geografických doplňků nejsou zohledněny všechny přípustné
varianty uvedené v textu Základních pravidel. Primárním účelem je
rozlišit případy, kdy se v geografickém doplňku zapisuje okres (v ČR,
SR, Polsku, Německu, Maďarsku, Rakousku a na Ukrajině) a kdy ne (v
ostatních případech). Například v Základních pravidlech a dále v této
příloze (závěr přílohy v části „Geografické objekty – hierarchie
administrativního zařazení“) se připouští napojit „nižší sídelní
jednotku“ na obec, obec se širší působností, část obce nebo vojenský
újezd. Tomu se následně přizpůsobí i podoba zápisu geografického
doplňku.

#### Podtřída administrativně či jinak lidmi vymezená území

##### Kontinent/světadíl

Obecný doplněk: kontinent/světadíl

Geografický doplněk: *neuvádí se*

Doplňující vysvětlení: Vzhledem k zjednodušení, tzn. ztotožnění
kontinentu se světadílem, byly geografické objekty tohoto typu zařazeny
do podtřídy „administrativně či jinak lidmi vymezená území“.

> Příklady:
>
> ***Afrika** (kontinent/světadíl)*
>
> ***Antarktida** (kontinent/světadíl)*
>
> ***Austrálie a Oceánie** (kontinent/světadíl)*
>
> ***Eurasie** (kontinent/světadíl)*
>
> ***Evropa** (kontinent/světadíl), západní část Eurasie*
>
> ***Asie** (kontinent/světadíl), východní část Eurasie*
>
> ***Amerika** (kontinent/světadíl)*
>
> ***Severní Amerika** (kontinent/světadíl), severní část Ameriky*
>
> ***Jižní Amerika** (kontinent/světadíl), jižní část Ameriky*

##### Stát

Obecný doplněk: *neuvádí se*

Geografický doplněk: *neuvádí se*

Doplňující vysvětlení: Současné i zaniklé suverénní státní útvary.

###### Příklady PREF současných států:

> ***Česko***
>
> ***Německo***
>
> ***Polsko***
>
> ***Slovensko***
>
> ***Spojené státy americké***
>
> ***Andorra***
>
> ***Monako***

###### Ukázky různých typů geografického objektu nesoucích stejné jméno:

> ***Irsko*** \[stát\] = podtřída „administrativně či jinak lidmi
> vymezená území“
>
> vs.
>
> ***Irsko** (Irsko a Velká Británie : ostrov)* = podtřída
> „geomorfologické útvary na zemském povrchu“
>
> ***Austrálie*** \[stát\]
>
> vs.
>
> ***Austrálie a Oceánie** (kontinent/světadíl)* = obojí podtřída
> „administrativně či jinak lidmi vymezená území“

###### Předchůdci České a částečně i Slovenské republiky:

Poznámka: Čechy, Morava nebo Slezsko (nedatovaná historická území) jsou
evidována jako typ geografického objektu „jiná vymezená území“.
Markrabství moravské (1182-1918) nebo Země moravská (1918-1928) a další
podobná území jakožto dílčí správní části státního útvaru jsou evidované
jako „země“. Obojí viz níže.

> G1.1: ***Velkomoravská říše** (9. st.-asi 907), historický státní
> útvar rozkládající se především na území Česka a Slovenska*
>
> VAR: *Velká Morava*
>
> G1.2: ***České knížectví** (9. st.-1198), historický státní útvar
> rozkládající se především na území Česka*
>
> VAR: *knížectví České*
>
> *Poznámka: O knížectví šlo s výjimkou let 1085–1092 a 1158–1172.*
>
> G1.3: ***České království** (1198-1918), historický státní útvar
> rozkládající se především na území Čech*
>
> VAR: *království České*
>
> *Poznámka: Nezaměňovat se jménem země Koruny české.*
>
> G1.4: ***země Koruny české** (1348-1918), historický státní útvar,
> který byl tvořen svazkem zemí pod svrchovaností českého krále – České
> království, Moravské markrabství, Opavské knížectví a jednotlivá
> slezská knížectví a Lužice*
>
> VAR: *Koruna česká*
>
> G1.5: ***Československo** (1918-1992), historický státní útvar
> rozkládající se především na území Česka a Slovenska*
>
> VAR: *Republika československá* \[datace použití jména: 1918-1960\];
> *stát československý* \[datace použití jména: 1918-1938\];
> *Československá republika* \[datace použití jména: 1918-1960\];
> *Česko-Slovenská republika* \[datace použití jména: 1938-1939\];
> *Československá socialistická republika* \[datace použití jména:
> 1960-1990\]; *Česká a Slovenská Federativní republika* \[datace
> použití jména: 1990-1992\]; *Česká a Slovenská Federatívna Republika*
> \[datace použití jména: 1990-1992\]; *RČS* \[datace použití jména:
> 1919-1939\]; *ČSR* \[datace použití jména: 1919-1939\]; *ČSSR*
> \[datace použití jména: 1960-1990\]; *ČSFR* \[datace použití jména:
> 1990-1992\]; *první republika* \[datace použití jména: 1918-1938\];
> *druhá republika* \[datace použití jména: 1938-1939\]; *třetí
> republika* \[datace použití jména: 1945-1948\], *Česko-Slovensko*
> \[datace použití jména: 1938-1939\]
>
> *Poznámka: Období protektorátní správy v letech 1939-1945, tzn. území
> Protektorátu Čechy a Morava, je evidováno jako typ geografického
> objektu „jiné vymezené území“ – viz dále.*

###### Současné Česko (státní útvar) od roku 1993:

> G2: ***Česko***
>
> VAR: *Česká republika*; *ČR*; *Czechia*

###### Doplnění předchůdců Slovenské republiky:

> G3.1: ***Uhersko** (895-1000), historický státní útvar*, *jemuž vládla
> knížata z dynastie Arpádovců*
>
> VAR: *Uherské knížectví*; *Uhry*
>
> G3.2: ***Uhersko** (1000-1867), historický státní útvar pod vládou
> králů z rodu Arpádovců, Anjouovců a Habsburků*
>
> VAR: *Uherské království*; *Uhry*
>
> G3.3: ***Uhersko** (1867-1918), historický státní útvar*
>
> VAR: *Zalitavsko*; *Uhry*
>
> G3.4: ***Slovenská republika** (1939-1945), historický státní útvar*
>
> VAR: *Slovenský štát* \[slovenština\]; *Slovensko*

###### Současné Slovensko od roku 1993:

> G4: ***Slovensko***
>
> VAR: *Slovenská republika*; *SR*

###### Vývoj státních útvarů jakožto předchůdců Rakouska:

> G5.1: ***Rakouské markrabství** (976-1156), historický státní útvar
> pod vládou dynastie Babenberků*
>
> VAR: *Östliche Mark* \[němčina\]; *Ostmark* \[němčina\]; *Marcha
> orientalis* \[latina\]
>
> G5.2: ***Rakouské vévodství** (1156-1453), historický státní útvar,
> který vznikl povýšením Rakouského markrabství pod vládou Babenberků
> a později Habsburků*
>
> VAR: *Herzogtum Österreich* \[němčina\]
>
> G5.3: ***Rakouské arcivévodství** (1453-1806), historický státní
> útvar, který vznikl povýšením Rakouského vévodství pod vládou
> habsburské dynastie a jejich následnické habsbursko-lotrinské
> dynastie*
>
> VAR: *Erzherzogtum Österreich* \[němčina\]
>
> G5.4: ***Rakousko** (1526-1804), historický státní útvar, jemuž vládla
> rakouská větev habsburské dynastie a následnická habsbursko-lotrinská
> dynastie*
>
> VAR: *Habsburská monarchie*
>
> G5.5: ***Rakousko** (1804-1867), historický státní útvar, známý také
> pod poloúředním názvem Rakouské císařství*
>
> VAR: *Kaisertum Österreich* \[němčina\]; *Rakouské císařství*;
> *Habsburská monarchie*
>
> G5.6: ***Rakousko-Uhersko** (1867-1918), historický státní útvar,
> reálná a personální unie, která vznikla po rakousko-uherském
> vyrovnání*
>
> VAR: *Österreich-Ungarn* \[němčina\]; *Rakousko-uherská monarchie*;
> *Österreichisch-Ungarische Monarchie* \[němčina\]; *Osztrák-Magyar
> Monarchia* \[maďarština\]; *Habsburská monarchie*
>
> G5.7: ***Rakousko** (1867-1918), historický státní útvar, který vznikl
> po rakousko-uherském vyrovnání*
>
> VAR: *Österreich* \[němčina\]; *Předlitavsko*; *Království a země na
> říšské radě zastoupené*; *Habsburská monarchie*

###### Současné Rakousko od roku 1918:

> G6: ***Rakousko***
>
> VAR: *Österreich* \[němčina\]; *Německé Rakousko* \[datace použití
> jména: 1918-1919\]; *Rakouská republika*; *Republik Österreich*
> \[němčina\]; *První Rakouská republika* \[1919-1934\]; *Rakouský
> stát*; *Spolkový stát Rakousko* \[1934-1938\]; *Druhá rakouská
> republika* \[1955-\]
>
> *Poznámka: Období nacistické okupační správy (Východní marka)
> a okupační zóny Rakouska v letech 1945-1955 jsou evidována jako typ
> geografického objektu „jiná vymezená území“ – viz dále.*

###### Vývoj státních útvarů jakožto předchůdců Německa:

Poznámka: Příklady konfederačních státních útvarů, k nimž tehdy náleželo
území dnešního Německa, jsou evidovány jako typ geografického objektu
„jiná vymezená území“ – viz dále.

###### Příklad státních útvarů po sjednocení Německa v roce 1871:

> G7.1: ***Německé císařství** (1871-1918), historický státní útvar*
>
> VAR: *Německá říše*; *Deutsches Reich* \[němčina\]; *Imperiální
> Německo*; *Německo*
>
> G7.2: ***Výmarská republika** (1918-1933), historický státní útvar pro
> Německo od roku 1918 do nástupu nacistů k moci*
>
> VAR: *Weimarer Republik* \[němčina\]; *Německá říše*; *Německo*
>
> G7.3: ***Třetí říše** (1933-1945), historický státní útvar pro Německo
> pod nacistickým vedením*
>
> VAR: *Nacistické Německo*; *Německá říše* \[datace použití jména:
> 1933–1943\]; *Deutsches Reich* \[1933–1943; němčina\]; *Velkoněmecká
> říše* \[1943–1945\]; *Großdeutsches Reich* \[1943–1945; němčina\];
> *Tisíciletá říše*; *Německo*
>
> G7.4: ***Německá demokratická republika** (1949-1990), historický
> státní útvar na území Německa*
>
> VAR: *Deutsche Demokratische Republik* \[němčina\]; *DDR*; *Východní
> Německo* \[datace použití jména: 1949-1990\]; *Ostdeutschland*
> \[1949-1990, němčina\]; *NDR* \[1949-1990\]
>
> G7.5: ***Německo,** současné Německo a zároveň Západní Německo
> v letech 1949-1990*
>
> VAR: *Spolková republika Německo*; *Bundesrepublik Deutschland*
> \[němčina\]; *BRD* \[němčina\]; *SRN*; *Západní Německo* \[datace
> použití jména: 1949-1990\]; *Westdeutschland* \[1949-1990; němčina\];
> *NSR* \[1949-1990\]
>
> *Poznámka: Okupační zóny Německa v letech 1945-1949 jsou evidovány
> jako typ geografického objektu „jiná vymezená území“ – viz dále.*

###### Příklady dílčích německých státních útvarů:

> G8.1: ***Pruské vévodství** (1525-1618), historický státní útvar*
>
> VAR: *Herzogtum Preußen* \[němčina\]; *Ducatus Prussiae* \[latina\];
> *Prusy vévodské*; *Prusy knížecí*; *Prusko*
>
> G8.2: ***Braniborsko-Prusko** (1618-1701), historický státní útvar*
>
> VAR: *Brandenburg-Preußen* \[němčina\]; *Prusko*; *Braniborsko*
>
> G8.3: ***Pruské království** (1701-1918), historický státní útvar*
>
> VAR: *Königreich Preußen* \[němčina\]; *Königreich Preussen*
> \[němčina\]; *Prusko*
>
> G8.4: ***Bavorské vévodství** (1623-1806), historický státní útvar,
> jedno z kurfiřtství Svaté říše římské*
>
> VAR: *Bavorské kurfiřtství*; *Herzogtum Bayern* \[němčina\];
> *Bavorsko*
>
> G8.5: ***Bavorské království** (1806-1918), historický státní útvar*
>
> VAR: *Königreich Bayern* \[němčina\]; *Bavorsko*
>
> *Poznámka: Bavorsko, resp. Svobodný stát Bavorsko jako současná
> spolková země SRN je entita s typem geografického objektu „země“ – viz
> níže.*
>
> G8.6: ***Sasko** (1356-1806), historický státní útvar, jedno
> z kurfiřtství Svaté říše římské*
>
> VAR: *Saské kurfiřtství*; *Saské vévodství*; *Kurfürstentum Sachsen*
> \[němčina\]; *Saxonia Electoralis* \[latina\]
>
> G8.7: ***Saské království** (1806-1918), historický státní útvar*
>
> VAR: *Königreich Sachsen* \[němčina\]; *Sasko*
>
> *Poznámka: Sasko, resp. Svobodný stát Sasko jako současná spolková
> země SRN je entita s typem geografického objektu „země“ – viz níže.*

###### Vývoj státních útvarů jakožto předchůdců Polska:

> G9.1: ***Polské knížectví** (10. st.-1025), historický státní útvar*
>
> VAR: *Polsko*
>
> G9.2: ***Polské království** (1025-1569), historický státní útvar za
> vlády Piastovců a Jagellonců*
>
> VAR: *Polsko*
>
> G9.3: ***Polské království** (1569-1795), historický státní útvar jako
> součást Polsko-litevské unie*
>
> VAR: *Polsko*
>
> G9.4: ***Polské království** (1815-1864), historický státní útvar
> v unii s Ruským impériem*
>
> VAR: *Kongresovka*; *Kongresové Polsko*; *Ruské Polsko*; *Polsko*
>
> G9.5: ***Polské království** (1916-1918), satelitní stát na území
> dobytém centrálními mocnostmi na Ruském impériu*
>
> VAR: *Regentské království*; *Polsko*

###### Současné Polsko vnímané kontinuálně od roku 1918:

> G10: ***Polsko***
>
> VAR: *Druhá polská republika* \[s datací použití jména: 1918-1939\];
> *Polská republika* \[1945-1952\]; *Polská lidová republika*
> \[1952-1989\]; *Třetí polská republika* \[1989-2005\]; *Čtvrtá polská
> republika* \[2005-\]
>
> *Poznámka: Období nacistické okupační správy (Generální gouvernement)
> je evidováno jako typ geografického objektu „jiná vymezená území“ –
> viz dále.*

###### Příklady dílčích polských knížectví:

> G11.1: ***Opolské knížectví** (1173-1742), jedno ze slezských
> knížectví s centrem v Opolí*
>
> G11.2: ***Ratibořské knížectví** (1172-1521), jedno ze slezských
> knížectví s centrem v Ratiboři*

###### Vývoj státních útvarů jakožto předchůdců Francie:

> G12.1: ***Francouzské království** (987-1848), historický stát
> v západní Evropě existující v letech 987-1792 a 1815-1848*
>
> VAR: *Royaume de France* \[francouzština\]; *Monarchie
> constitutionnelle française* \[datace použití jména: 1791-1792;
> francouzština\]; *Červencová monarchie* \[1830-1848\]; *Monarchie de
> Juillet* \[francouzština\]; *Království Francouzů*; *Royaume français*
> \[francouzština\]; *Francie*
>
> G12.2: ***První francouzská republika** (1792-1804), historický státní
> útvar*
>
> VAR: *Première République* \[francouzština\]; *Francie*
>
> G12.3: ***První francouzské císařství** (1804-1815), historický státní
> útvar*
>
> VAR: *Empire Français* \[francouzština\]; *Napoleonská Francie*;
> *Stodenní císařství* \[datace použití jména 1815\]; *Francie*
>
> G12.4: ***Druhá francouzská republika** (1848-1852), historický státní
> útvar*
>
> VAR: *Deuxième République* \[francouzština\]; *Francie*
>
> G12.5: ***Druhé francouzské císařství** (1852-1870), historický státní
> útvar*
>
> VAR: *Second Empire* \[francouzština\]; *Francie*
>
> G12.6: ***Vichistická Francie** (1940-1944), historický státní útvar*
>
> VAR: *Vichistický režim*; *Régime de Vichy* \[francouzština\];
> *Francouzský stát*; *État Français* \[francouzština\]; *Francie*

###### Současná Francie od roku 1870:

> G13: ***Francie***
>
> VAR: *Třetí republika* \[datace použití jména: 1870-1940\]; *Svobodná
> Francie* \[1940-1944\]; *France Libre*; *Prozatímní vláda Francouzské
> republiky* \[1944-1946\]; *Gouvernement provisoire de la République
> française* \[francouzština\]; *Čtvrtá francouzská republika*
> \[1946-1958\]; *Quatrième République française* \[francouzština\];
> *Pátá francouzská republika* \[1958-\]; *Cinquième République
> française* \[francouzština\]

###### Vývoj státních útvarů jakožto předchůdců Ruska:

> G14.1: ***Moskevské knížectví** (1276-1547), historický státní útvar*
>
> VAR: *Moskevské velkoknížectví*; Великое Княжество Московское
> \[ruština\]; *Velikoje Kňažestvo Moskovskoje* \[ruština\]
>
> G14.2: ***Ruské carství** (1547-1721), historický státní útvar*
>
> VAR: Русское Царство \[ruština\]; *Russkoje tsarstvo* \[ruština\];
> *Moskevské carství*; Московское Царство \[ruština\]; *Rusko*
>
> G14.3: ***Ruské impérium** (1721-1917), historický státní útvar*
>
> VAR: Российская Империя \[ruština\]; *Rossijskaja imperija*
> \[ruština\]; *Rossiyskaya imperiya* \[ruština\]; *Rusko*
>
> G14.4: ***Ruská republika** (1917), historický státní útvar*
>
> VAR: Российская республика \[ruština\]; *Rossijskaja respublika*
> \[ruština\]; *Rossiyskaya republika* \[ruština\]; *Rusko*
>
> G14.5: ***Ruská sovětská federativní socialistická republika**
> (1917-1991), historický státní útvar*
>
> VAR: Российская Советская Федеративная Социалистическая Республика
> \[ruština\]; *Ruská socialistická federativní sovětská republika*;
> Российская Социалистическая Федеративная Советская Республика
> \[ruština\]; *RSFSR*; *Rusko*
>
> *Poznámka: Od roku 1922 chápána jako největší svazová republika
> Sovětského svazu.*
>
> G14.6: ***Sovětský svaz** (1922-1991), historický státní útvar*
>
> VAR: Советский Союз \[ruština\]; *Sovětskij Sojuz* \[ruština\]; *Svaz
> sovětských socialistických republik*; *SSSR*; Сою́з Сове́тских
> Социалисти́ческих Респу́блик \[ruština\]; СССР \[ruština\]; *Sojuz
> Sovětskich Socialističeskich Respublik* \[ruština\]; *Sovětské Rusko*;
> *Rusko*
>
> *Poznámka: Jednotlivé svazové republiky SSSR se evidují jako typ
> geografického objektu „stát“.*

###### Současné Rusko od roku 1991:

> G15: ***Rusko***
>
> VAR: *Ruská federace*; Россия \[ruština\]; *Rossija* \[ruština\];
> Российская Федерация \[ruština\]; *Rossijskaja feděracija* \[ruština\]

##### Autonomní část státu

Obecný doplněk: autonomní část

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklad:
>
> G16: ***Katalánsko** (Španělsko : autonomní část), autonomní
> společenství na severovýchodě Španělska při pobřeží Středozemního
> moře*
>
> VAR: *Catalunya* \[katalánština\]*; Cataluña* \[španělština\];
> *Catalonha* \[okcitánština\]

###### Ukázky různých typů geografického objektu nesoucích stejné jméno:

> G17: ***Azory** (Portugalsko : autonomní část), zámořské autonomní
> území Portugalska nacházející se v Atlantském oceánu v oblasti
> Makaronésie* = podtřída „administrativně či jinak lidmi vymezená
> území“
>
> vs.
>
> ***Azory** (Portugalsko : souostroví)* = podtřída „geomorfologické
> útvary na zemském povrchu“
>
> G18: ***Grónsko** (Dánsko : autonomní část), dánské autonomní území
> ležící severovýchodně od Kanady* = podtřída „administrativně či jinak
> lidmi vymezená území“
>
> vs.
>
> ***Grónsko** (Dánsko: ostrov)* = podtřída „geomorfologické útvary na
> zemském povrchu“

##### Země

Obecný doplněk: *neuvádí se*

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklady:
>
> G19.1: ***Markrabství moravské** (Česko : 1182-1918), historický útvar
> na území Moravy*
>
> VAR: *Morava*; *Moravské markrabství*
>
> G19.2: ***Země moravská** (Česko : 1918-1928), historická země
> Československa na území Moravy*
>
> VAR: *Moravská země*; *Morava*
>
> G19.3: ***Země moravskoslezská** (Česko : 1928-1948), historická země
> Československa na území Moravy a Slezska*
>
> VAR: *Moravskoslezská země*; *Moravsko-slezská země*; *Země
> moravsko-slezská*
>
> G20: ***Česko** (Česko : 1969-1992), území Česka v období federálního
> Československa*
>
> VAR: *Česká socialistická republika* \[datace použití jména:
> 1969-1990\]; *ČSR* \[datace použití jména: 1969-1990\]; *Česká
> republika* \[datace použití jména: 1990-1992\]
>
> G21: ***Slovensko** (Slovensko : 1969-1992), území Slovenska po
> federalizaci Československa*
>
> VAR: *Slovenská socialistická republika* \[datace použití jména:
> 1969-1990\]; *SSR* \[datace použití jména: 1969-1990\]; *Slovenská
> republika* \[datace použití jména: 1990-1992\]
>
> G22: ***Bavorsko** (Německo), současná spolková země*
>
> VAR: *Svobodný stát Bavorsko*; *Freistaat Bayern* \[němčina\]
>
> G23: ***Federace Bosna a Hercegovina** (Bosna a Hercegovina), správní
> území Bosny a Hercegoviny*
>
> VAR: *Federacija Bosne i Hercegovine* \[bosenština; chorvatština;
> srbština\]; Федерација Босне и Херцеговине \[bosenština; srbština\]
>
> G24: ***Republika srbská** (Bosna a Hercegovina), správní území Bosny
> a Hercegoviny*
>
> VAR: *Republika Srpska* \[bosenština; chorvatština; srbština\];
> Република Српска \[srbština\]
>
> G25: ***Sasko** (Německo), současná spolková země*
>
> VAR: *Svobodný stát Sasko*; *Freistaat Sachsen* \[němčina\]
>
> G26: ***Utah** (Spojené státy americké), současný stát USA*

##### Departement

Obecný doplněk: departement

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklad:
>
> G27: ***Ariège** (Francie : departement), správní území v regionu
> Okcitánie*

##### Hrabství

Obecný doplněk: hrabství

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklad:
>
> G28: ***Essex** (Velká Británie : hrabství), správní území ve východní
> Anglii*

##### Kanton

Obecný doplněk: kanton

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklady:
>
> G29: ***Lucern** (Švýcarsko : kanton), správní území v německojazyčné
> části Švýcarska*
>
> VAR: *Luzern* \[němčina\], *Lucerne* \[angličtina, francouzština\],
> *Lucerna* \[italština; rétorománština\]
>
> G30: ***Saint-Girons** (Francie : kanton), správní území
> v departementu Ariège*

##### Oblast

Obecný doplněk: oblast

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklady:
>
> G31: ***Brestská oblast** (Bělorusko : oblast), správní území na
> jihozápadě Běloruska*
>
> VAR: Брэсцкая вобласць \[běloruština\]
>
> G32: ***Leningradská oblast** (Rusko : oblast), správní území na
> severozápadě Ruska se sídlem administrativních úřadů v Petrohradě,
> který není součástí oblasti*
>
> VAR: Ленинградская область \[ruština\]
>
> G33: ***Loveč** (Bulharsko : oblast), správní území na severozápadě
> Bulharska*
>
> VAR: Ловеч \[bulharština\]; *Lovečská oblast*
>
> G34: ***Východokazašská oblast** (Kazachstán : oblast), správní území
> Kazachstánu s centrem* *Öskemen*
>
> VAR: *Východokazachstánská oblast*; Шығыс Қазақстан облысы
> \[kazaština\]; Восточно-Казахстанская область \[ruština\]
>
> G35: ***Zakarpatská oblast** (Ukrajina : oblast), správní území na
> jihozápadě Ukrajiny s centrem Užhorod*
>
> VAR: Закарпатська область \[ukrajinština\]

##### Okruh

Obecný doplněk: okruh

Geografický doplněk: stát

Doplňující vysvětlení: Administrativně vymezená vnitřní část suverénního
státního útvaru. Vojenské okruhy bývalých států Varšavské smlouvy
a současného Ruska se evidují v podtřídě „další vymezené lokality,
oblasti a zóny“.

> Příklady:
>
> G36: ***Něnecký autonomní okruh** (Rusko : okruh), správní území
> v Archangelské oblasti, součást Severozápadního federálního okruhu*
>
> VAR: Нeнецкий автонoмный oкруг \[ruština\]
>
> G37: ***Nišavský okruh** (Srbsko : okruh), správní území na
> jihovýchodě Srbska s centrem Niš*
>
> VAR: Нишавски округ \[srbština\]; *Nišavski okrug* \[srbština\]
>
> G38: ***Severozápadní federální okruh** (Rusko : okruh), správní území
> v severní části evropského Ruska s centrem Petrohrad*
>
> VAR: *Severozápadní federální okruh Ruské federace*; Северо-Западный
> федеральный округ Российской Федерации \[ruština\]

##### Vojvodství

Obecný doplněk: *neuvádí se*

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklad:
>
> G39: ***Slezské vojvodství** (Polsko), správní území na jihu Polska,
> sousedí s Českem a Slovenskem*
>
> VAR: *Województwo śląskie* \[polština\]

##### Župa

Obecný doplněk: župa

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklady:
>
> G40: ***Mladoboleslavská župa** (Česko : župa : 1920-1927), historické
> správní území v Československu, které nebylo uvedeno do praxe*
>
> VAR: *župa IV*
>
> G41: ***Sudetská župa** (Česko : župa : 1939-1945), zaniklé správní
> území z období německé okupace podléhající Třetí říši s centrem
> Liberec*
>
> VAR: *Sudetengau* \[němčina\]; *Říšská župa Sudety*; *Reichsgau
> Sudetenland* \[němčina\]
>
> G42: ***Brašov** (Rumunsko : župa), správní území v rumunském
> Sedmihradsku se stejnojmenným centrem*
>
> VAR: *Județul Brașov* \[rumunština\]; *Brașov* \[rumunština\];
> *Brašovská župa*
>
> G43: ***Dubrovnicko-neretvanská župa** (Chorvatsko : župa), správní
> území na jihu Chorvatska s centrem Dubrovník*
>
> VAR: *Dubrovačko-neretvanska županija* \[chorvatština\];
> *Dubrovník-Neretva*
>
> G44: ***Komárensko-ostřihomská župa** (Maďarsko : župa), správní území
> v severním Maďarsku s centrem Tatabánya*
>
> VAR: *Komárom-Esztergom megye* \[maďarština\]; *Komárno-Ostřihom*
>
> G45: ***Liptovská župa** (Slovensko : župa : 1849-1922), historické
> správní území na Slovensku*

##### Provincie

Obecný doplněk: provincie

Geografický doplněk: stát

Doplňující vysvětlení: administrativně vymezená vnitřní část suverénního
státního útvaru.

> Příklady:
>
> G46: ***Alberta** (Kanada : provincie), správní území v západní části
> Kanady s centrem Edmonton*
>
> G47: ***Barcelona** (Španělsko : provincie), správní území se
> stejnojmenným centrem, součást autonomního území Katalánska*
>
> G48: ***Bari** (Itálie : provincie), metropolitní město na úrovni
> provincie*
>
> *Poznámka: Vzniklo v roce 2015 z bývalé provincie.*
>
> G49: ***Frísko** (Nizozemsko : provincie), správní území na severu
> Nizozemska s centrem Leeuwarden*
>
> VAR: *Friesland* \[holandština\]
>
> G50: ***Jižní Karélie** (Finsko : provincie), správní území
> v jihovýchodní části Finska s centrem Lappeenranta*
>
> VAR: *Etelä Karjala* \[finština\]
>
> G51: ***Livorno** (Itálie : provincie), správní území v oblasti
> Toskánska se stejnojmenným centrem*
>
> G52: ***Syrakusy** (Itálie : provincie), volné sdružení obcí na úrovni
> provincie*
>
> VAR: *Libero consorzio comunale di Siracusa* \[italština\]; *Siracusa*
> \[italština\]
>
> *Poznámka: Vzniklo v roce 2015 z bývalé provincie.*

##### Region

Obecný doplněk: region

Geografický doplněk: stát

Doplňující vysvětlení: Administrativně vymezená vnitřní část suverénního
státního útvaru dle normalizované klasifikace územních celků pro potřeby
Eurostatu a ČSÚ. V ČR regiony soudržnosti (NUTS 2).

Chápáno jen jako administrativní jednotka, nikoli území vzniklá
přirozeně jako kulturní, či národnostní nebo náboženský celek. Takové
pojetí regionu se klasifikuje jako „jiné vymezené území“ (např. Morava).

> Příklady:
>
> G53: ***Severovýchod** (Česko : region), region soudržnosti, tvořený
> Královéhradeckým, Pardubickým a Libereckým krajem*
>
> G54: ***Střední Morava** (Česko : region), region soudržnosti, tvořený
> Olomouckým a Zlínským krajem*
>
> G55: ***Dolní Normandie** (Francie : region : 1956-2016), historické
> správní území v severozápadní Francii, od roku 2016 součást regionu
> Normandie*
>
> VAR: *Basse-Normandie* \[francouzština\]
>
> G56: ***Lombardie** (Itálie : region), správní území v severní Itálii
> s centrem Milán*
>
> VAR: *Lombardia* \[italština\]
>
> G57: ***Normandie** (Francie : region : 2016-), správní území
> v severní Francii s centrem Rouen*
>
> G58: ***Vlámský region** (Belgie : region), správní území v severní
> části Belgie*
>
> VAR: *Vlaanderen* \[holandština (nizozemština)\]; *Vlaams Gewest*
> \[holandština (nizozemština)\]

###### Ukázky různých typů geografického objektu nesoucích stejné jméno:

> G59: ***Korsika** (Francie : region), správní území Francie ve
> Středozemním moři* = podtřída „administrativně či jinak lidmi vymezená
> území“
>
> VAR: *Corse* \[francouzština\]; *Korzika*
>
> vs.
>
> ***Korsika** (Francie : ostrov)* = podtřída „geomorfologické útvary na
> zemském povrchu“
>
> G60: ***Sicílie** (Itálie : region), autonomní region Itálie* =
> podtřída „administrativně či jinak lidmi vymezená území“
>
> VAR: *Sicilia* \[italština\]
>
> vs.
>
> ***Sicílie** (Itálie : ostrov)* = podtřída „geomorfologické útvary na
> zemském povrchu“

###### Ukázka geografického objektu, jehož VAR obsahuje české standardizované exonymum i cizojazyčnou formu:

> G61: ***Burgundsko-Franche-Comté** (Francie : region), správní území
> ve východní Francii*
>
> VAR: *Bourgogne-Franche-Comté*

##### Kraj

Obecný doplněk: kraj

Geografický doplněk: stát

Doplňující vysvětlení: Administrativně vymezená vnitřní část suverénního
státního útvaru. V ČR se rozlišují jednotlivé fáze správního a územního
vývoje.

###### Kritéria pro vytváření nových archivních autoritních záznamů entit typu „kraj“ v ČR:

a\) respektovat správní vývoj (mezníky 1751 pro Čechy a Moravu, 1783 pro
Slezsko, 1850, 1855, 1949, 1960, 2000); pro období mezi roky 1990 až
2000 se archivní autoritní záznamy pro kraje nevytvářejí,

b\) při územních změnách s výjimkou sloučení dvou krajů nevytvářet nové
archivní autoritní záznamy,

c\) při změně jména nevytvářet nový archivní autoritní záznam entity,
pouze ji uvést jako variantní označení.

> Příklady:
>
> G62: ***Severomoravský kraj** (Česko : kraj : 1960-1990), historické
> správní území Československa s centrem Ostrava*
>
> *Poznámka: Úředně kraj zanikl až na základě zákona č. 51/2020 Sb.,
> přesto je doba zániku stanovena na rok 1990.*
>
> G63: ***Moravskoslezský kraj** (Česko : kraj : 2000-), správní území
> na severovýchodě Česka s centrem Ostrava*
>
> G64: ***Harju maakond** (Estonsko : kraj), správní území v severní
> části Estonska s centrem Tallinn*
>
> VAR: *Harju* \[estonština\]; *Harjumaa* \[estonština\]
>
> G65: ***Nordland** (Norsko : kraj), správní území na severu Norska
> s centrem Bodø*
>
> VAR: *Nordland Fylke* \[norština\]
>
> G66: ***Stavropolský kraj** (Rusko : kraj), správní území na
> jihozápadě Ruska s centrem Stavropol*
>
> VAR: Ставропо́льский край \[ruština\]
>
> G67: ***Střední Makedonie** (Řecko : kraj), správní území na severu
> Řecka s centrem Soluň*
>
> VAR: Περιφέρεια Κεντρικής Μακεδονίας \[řečtina\]; *Perifereia
> Kentrikis Makedonias* \[řečtina\]
>
> G68: ***Žilinský kraj** (Slovensko : kraj), správní území na severu
> Slovenska s centrem Žilina*

###### Příklady zaniklých krajů v ČR:

> G69: ***Bechyňsko** (Česko : kraj : 9. st.-1751), zaniklý hradský
> obvod, později kraj, v jižních Čechách*
>
> VAR: *Bechyňský kraj*; *kraj Bechyňský*; *circulus Bechinensis*
> \[latina\]; *Bechiner Kreis* \[němčina\]
>
> G70: ***Chebsko** (Česko a Německo : kraj : uváděno od 1135-1869),
> historické území v nejzápadnější části Čech a v přilehlém pohraničí
> Německa*
>
> VAR: *regio Egere* \[latina\]; *regio Egrensis* \[latina\]; *regio
> Egrana* \[latina\]; *provincia Egrensis* \[latina\]; *districtus
> Egranus* \[latina\]; *territorium Egrensis* \[latina\]; *terra
> Egrensis* \[latina\]; *Egerland* \[němčina\]; *Egrischer District*
> \[angličtina\]; *Egerischer Kreis* \[němčina\]; *Egerischer Bezirk*
> \[němčina\]; *okres Chebský*
>
> G71.1: ***Chebský kraj** (Česko : kraj : 1850-1855), bývalý správní
> obvod v západních Čechách spravovaný Krajskou vládou v Chebu*
>
> VAR: *kraj Chebský*; *Egerer Kreis* \[němčina\]
>
> G71.2: ***Chebský kraj** (Česko : kraj : 1855-1868), bývalý kraj
> v západních Čechách*
>
> VAR: *kraj Chebský*; *Egerer Kreis* \[němčina\]
>
> G72: ***Těšínský kraj** (Česko a Polsko : kraj : 1783-1850),
> historické správní území s centrem v Těšíně*
>
> VAR: *Teschner Kreis* \[němčina\]; *Těšínsko*

##### Okres

Obecný doplněk: okres

Geografický doplněk: stát

Doplňující vysvětlení: Administrativně vymezená vnitřní část suverénního
státního útvaru. Uplatňuje se pro současné okresy; v ČR a SR také pro
zaniklé politické okresy (do roku 1949), pro smíšené okresy z let
1855-1868, a dále i pro venkovské okresy v letech 1939–1945 na území
odstoupeném Německu po Mnichovské dohodě. Ve stručné charakteristice se
uvede, zda šlo o politický, smíšený či venkovský okres.

Naproti tomu městské okresy na území odstoupeném Německu v letech
1939–1945 se vyjadřují typem geografického objektu obec podle současného
správního členění, přičemž se jedná o město, podle kterého byl městský
okres pojmenován, např. Stadtkreis Karlsbad = Karlovy Vary (Karlovy
Vary, Česko).

###### Kritéria pro vytváření nových archivních autoritních záznamů entit typu „okres“ v ČR:

a\) respektovat správní vývoj (mezníky 1855, 1868, 1949, 1960; na území
odstoupeném Německu v říjnu 1938 na základě Mnichovské dohody také
mezníky 1939 a 1945); legislativní změna v podobě zákona č. 51/2020 Sb.
není důvodem k vytváření nových záznamů,

b\) při územních změnách s výjimkou sloučení dvou politických okresů
nevytvářet nový záznam,

c\) při změně jména nevytvářet nový záznam, pouze ji uvést jako
variantní označení.

###### V zahraničí pro lokality odpovídající stejné administrativní úrovni.

Konkrétně:

• <u>v Polsku</u> = powiat; města s právy okresu (miasto na prawach
powiatu) se evidují jako „obec se širší působností“;

• <u>v Německu</u> = Landkreis (Bádensko-Württembersko, Bavorsko,
Braniborsko, Hesensko, Meklenbursko-Přední Pomořansko, Dolní Sasko,
Porýní-Falc, Sársko, Sasko-Anhaltsko, Sasko, Durynsko) nebo Kreis (jen
v Porýní-Vestfálsko, Šlesvicko-Holštýnsko) nebo Kreisfreie Stadt
(Bavorsko, Braniborsko, Svobodné hanzovní město Brémy \[Bremerhaven\],
Hesensko, Meklenbursko-Přední Pomořansko, Dolní Sasko,
Porýní-Vestfálsko, Porýní-Falc, Šlesvicko-Holštýnsko, Sasko-Anhaltsko,
Sasko, Durynsko) nebo Stadtkreis (jen v Bádensku-Württembersku) nebo
Stadtgemeinde (Svobodné hanzovní město Brémy) nebo Region Hannover
(Dolní Sasko) nebo Regionalverband Saarbrücken (Sársko) nebo
Städteregion Aachen (Porýní-Vestfálsko); městské okresy (kreisfreie
Stadt) se evidují jako „obec se širší působností“

• <u>v Rakousk</u>u = Bezirk; statutární města (Statutarstadt) se
evidují jako „obec se širší působností“

• <u>na Ukrajině, v Rusku, Bělorusku, Lotyšsku, Moldavsku
a Ázerbájdžánu</u> = rajon;

• <u>v Maďarsku</u> = járás;

• v <u>Bulharsku</u> se takto evidují obštiny, jež jsou napojené na
oblasti. Jednotlivá sídla obštin včetně centra se evidují jako
samostatné obce. Obdobně se postupuje u opštin v <u>Černé Hoře</u>
a <u>Severní Makedonii</u> (napojené na stát), v <u>Srbsku</u> (napojené
na okruhy), v <u>Bosně a Hercegovině</u> (zde v části/zemi „Federace
Bosny a Hercegoviny“ napojené na kantony, na zbylém území na stát).

U větších měst se tradičně nazývané městské okresy evidují jako „městská
část/obvod“ (např. ve Vídni, Berlíně). Výjimku tvoří bratislavské
a košické okresy, ze kterých netvoříme městské části/obvody, nýbrž je
evidujeme jako „okresy“ napojené přímo na Bratislavský, resp. Košický
kraj.

Názvy okresu se zapisují formou jmen jejich center/sídel s výjimkou
případů, kdy v úředním jméně centrum/sídlo okresu uvedeno není. U entit
mimo ČR se název okresu zapisuje českým ekvivalentem, pakliže
i u archivního autoritního záznamu entity reprezentující toto
centrum/sídlo je rovněž v preferovaném označení použita čeština (např.
u okresů Mnichov v Bavorsku, Zhořelec v Sasku ad.).

Jestliže sídlo okresu uvedené není, použije se v hlavní části jména
úřední jméno okresu s vynecháním samostatných slov „Landkreis“ nebo
„Kreis“ (Německo), „powiat“ (Polsko) nebo obdobně u jiných států, pokud
je uvedeno formou samostatného obecného pojmu před nebo za vlastním
jménem. To tedy neplatí pro případy, kdy jsou tato označení součástí
složeného jména okresu, např. „*Ilm-Kreis*“, „*Rhein-Sieg-Kreis*“ či
„*Ostalbkreis*“ v Německu<span style="color:red;text-decoration:line-through">; „*Krasnogvardějský rajón*“ v Rusku</span>.

Důvodem je používání jména okresu v rámci geografického doplňku, u něhož
je žádoucí zkrácená forma.

> Příklady:
>
> G73: ***Frýdek-Místek** (Česko : okres : 1960-), správní území na
> východě Česka*
>
> G74: ***Žlutice** (Česko : okres : 1939-1945), venkovský okres v roli
> politického okresu v západních Čechách na území připojeném v říjnu
> 1938 k nacistickému Německu*

###### Vývoj dvou politických okresů a jejich sloučení:

> G75.1: ***Frýdek** (Česko : okres : 1850-1855), politický okres*
>
> G75.2: ***Frýdek** (Česko : okres : 1855-1868), smíšený
> politicko-soudní okres*
>
> G75.3: ***Frýdek** (Česko : okres : 1901-1942), politický okres*
>
> *Poznámka: Mezi léty 1868-1901 nebyl politický okres Frýdek zřízen.*
>
> \+ paralelně
>
> G75.4: ***Místek** (Česko : okres : 1850-1855), politický okres*
>
> G75.5: ***Místek** (Česko : okres : 1855-1868), smíšený
> politicko-soudní okres*
>
> G75.6: ***Místek** (Česko : okres : 1868-1942), politický okres*
>
> V roce 1942 došlo k zrušení politického okresu Frýdek a začlenění
> příslušného soudního okresu do politického okresu Místek:
>
> G75.7: ***Místek** (Česko : okres : 1942-1949), historický politický
> okres vzniklý sloučením okresu Frýdek a Místek*
>
> VAR: *Frýdek* \[datace použití jména: „*1943-1945*“, neboť došlo
> k záměně jmen\]
>
> G75.8: ***Frýdek-Místek** (Česko : okres : 1949-1960), historický
> okres Československa*
>
> VAR: *Místek* \[datace použití jména: „*1949-1956*“, neboť byl nejprve
> pojmenován jako Místek\]
>
> G75.9: ***Frýdek-Místek** (Česko : okres : 1960-), správní území na
> východě Česka*

###### Příklady v zahraničí:

> G76: ***Bansko** (Bulharsko : okres), obština v jihozápadním
> Bulharsku*
>
> VAR: Банско \[bulharština\]
>
> G77.1: ***Benton** (Iowa, Spojené státy americké : okres),
> okres ve státě Iowa*
>
> G77.2: ***Benton** (Arkansas, Spojené státy americké :
> okres), okres ve státě Arkansas*
>
> *Poznámka: Okres Benton se v USA nachází ve více státech, pro jejich
> odlišení v preferovaném označení je proto nutné ručně dopsat do
> geografického doplňku nadřazenou administrativní jednotku, v tomto
> případě tedy daný stát (Iowa, Arkansas, Indiana, Missouri atd.).*
>
> G78: ***Budva** (Černá Hora : okres), opština při jaderském pobřeží*
>
> VAR: Будва \[srbština\]
>
> G79: ***Doboj** (Bosna a Hercegovina : okres), opština v jižní části
> Bosny a Hercegoviny*
>
> VAR: Добој \[srbština\]
>
> G80: ***Gornji Milanovac** (Srbsko : okres), opština v centrální části
> Srbska*
>
> VAR: Горњи Милановац \[srbština\]
>
> G81: ***Krasnogvardějský<span style="color:red;text-decoration:line-through"> rajón</span>** (Rusko : okres), správní území
> v Bělgorodské oblasti s centrem Birjuč*
>
> VAR: Красногвардейский район \[ruština\]; <span style="color:red">Krasnogvardějský
> rajón</span>
>
> *Poznámka: Upřednostněno úřední jméno „Krasnogvardějský rajón“, neboť
> se liší jméno centra okresu (Birjuč) od jména okresu.*
>
> G82: ***Ljachavičy** (Bělorusko : okres), správní území na severu
> Brestské oblasti*
>
> VAR: *Ljachavický rajón*; Ляхавіцкі раён \[běloruština\]
>
> G83: ***Mukačevo** (Ukrajina : okres), správní území v Zakarpatské
> oblasti*
>
> VAR: Мукачево \[ukrajinština\]; Мукачеве \[ukrajinština\]; *Munkács*
> \[maďarština\]
>
> G84: ***Probištip** (Severní Makedonie : okres), opština ve východní
> části Severní Makedonie*
>
> VAR: Општина Пробиштип \[makedonština\]
>
> G85: ***Waidhofen an der Thaya** (Rakousko : okres), správní území
> v Dolním Rakousku*
>
> VAR: *Bejdov nad Dyjí* \[čeština\]
>
> G86.1: ***Wodzisław Śląski** (Polsko : okres), správní území ve
> Slezském vojvodství*
>
> VAR: *Vladislav* \[čeština\]; *powiat wodzisławski* \[polština\]
>
> *Poznámka: Oficiální název okresu je powiat wodzisławski / okres
> Wodzisław. Bylo však uplatněno pravidlo, kdy pro název okresu bylo
> použito jméno jeho sídla/centra. Tedy nikoli zkráceně Wodzisław, ale
> Wodzisław Śląski.*
>
> G86.2 ***Ratiboř** (Polsko : okres), správní území ve Slezském
> vojvodství*
>
> VAR: *powiat raciborski* \[polština\]*; Racibórz* \[polština\]
>
> G87: ***Görlitz** (Německo : okres), správní území v saské části Horní
> Lužice*
>
> VAR: *Zhořelec* \[<span style="color:red">čeština</span>\]

##### Soudní okres

Obecný doplněk: soudní okres

Geografický doplněk: stát (případně současný okres, pokud celý bývalý
soudní okres obsáhne).

Doplňující vysvětlení: Administrativně vymezená vnitřní část suverénního
státního útvaru. V ČR se uplatňuje pro soudní okresy v období 1850–1949.

> Příklady:
>
> G88: ***Horní Blatná** (Karlovy Vary, Česko : soudní okres :
> 1850-1949), historické území justiční správy*
>
> G89: ***Javorník** (Jeseník, Česko : soudní okres : 1850-1949),
> historické území justiční správy*
>
> G90: ***Místek** (Frýdek-Místek, Česko : soudní okres : 1850-1949),
> historické území justiční správy*
>
> G91: ***Eisenstadt** (Rakousko : soudní okres), území justiční správy*

##### Jiná část státu

Obecný doplněk: část státu

Geografický doplněk: stát

Doplňující vysvětlení: Pro současné i zaniklé administrativně vymezené
vnitřní části suverénního státního útvaru, které nejdou ztotožnit
s jiným typem geografického objektu ze skupiny „vnitřní část státu“ (viz
níže kapitolu Geografické objekty – hierarchie administrativního
zařazení). Konkrétní typ části státu (např. arrondissement, prefektura)
se uvede do stručné charakteristiky, výjimkou je německá okupační správa
v českých zemích.

> Příklady:
>
> G92: ***Vládní obvod Cheb** (Česko : část státu : 1939-1945), jeden ze
> tří správních obvodů Sudetské župy*
>
> VAR: *Regierungsbezirk Eger* \[němčina\]
>
> G93: ***Oberlandrát Pardubice** (Česko : část státu : 1940-1942)*,
> *správní obvod německé okupační správy*
>
> VAR: *Oberlandratsbezirk Pardubitz* \[němčina\]; *Obvod oberlandrátu
> Pardubice; Obvod vrchního zemského rady Pardubice*
>
> G94: ***Belfort** (Francie : část státu), arrondissement v regionu
> Burgundsko-Franche-Comté*
>
> G95: ***Okajama** (Japonsko : část státu), prefektura v regionu Čúgoku
> na ostrově Honšú*
>
> VAR: *Okayama-shi* \[japonština\]; 岡山市 \[japonština\]
>
> G96: ***Severní distrikt** (Izrael : část státu), administrativní
> jednotka v severním Izraeli*
>
> VAR: *Mechoz ha-Cafon*; <span dir="rtl">מחוז הצפון</span>
> \[hebrejština\]; <span dir="rtl">منطقة الشمال</span> \[arabština\];
> *mintaqatu-š-Šamál* \[arabština\]

##### Vojenský újezd

Obecný doplněk: vojenský újezd

Geografický doplněk: stát (případně současný okres, pokud celý vojenský
újezd obsáhne).

Doplňující vysvětlení: Vojenské újezdy v ČR. U nezaniklých entit se
chronologický doplněk neuvádí. V případě, že má entita vyplněnou událost
zánik, jako chronologický doplněk se uvádí „zaniklo“.

> Příklady:
>
> G97: ***Libavá** (Olomouc, Česko : vojenský újezd), území pod
> vojenskou správou*
>
> G98: ***Ralsko** (Česko : vojenský újezd : zaniklo), historické území
> pod vojenskou správou*

##### Obec se širší působností

Obecný doplněk: *neuvádí se*

Geografický doplněk: stát

Doplňující vysvětlení: Obce, které nejsou součástí okresů a zpravidla
mají i širší působnost (geografickou, kompetenční). V ČR je tímto typem
evidována pouze Praha (nikoli obce s rozšířenou působností, tzv. ORP).
Na Slovensku jsou to Bratislava a Košice. V Polsku jde o „města s právy
okresu“, v Německu města typu „městský okres (kreisfreie Stadt)“,
v Rakousku statutární města (Statutarstädte) aj. Ve Slovinsku se takto
evidují občiny, respektive jejich centra. Občiny jsou napojené přímo na
stát, jejich podřízená sídla pak jako „část obce“.

> Příklady:
>
> G99: ***Praha** (Česko), hlavní město České republiky*
>
> VAR: *Praga* \[latina\]; *Prag* \[němčina\]; *Prague* \[angličtina,
> francouzština\]
>
> G100: ***Bratislava** (Slovensko), hlavní město Slovenské republiky*
>
> VAR: *Prešpurk* \[čeština\]; *Posonium* \[latina\]; *Pressburg*
> \[němčina\]; *Preßburg* \[němčina\]; *Pozsony* \[maďarština\];
> *Prešporok* \[slovenština\]; *Prešporek* \[slovenština\]
>
> G101: ***Košice** (Slovensko), město na východě Slovenska*
>
> VAR: *Cassovia* \[latina\]; *Kaschau* \[němčina\]; *Kassa*
> \[maďarština\]; *Koszyce* \[polština\]
>
> G102: ***Berlín** (Německo), spolková země a hlavní město Německa*
>
> VAR: *Berlin* \[němčina\]; *Berolinum* \[latina\]
>
> G103: ***Drážďany** (Německo), hlavní město spolkové země Sasko*
>
> VAR: *Dresden* \[němčina\]; *Dresda* \[latina\]; *Drježdźany*
> \[hornolužičtina\]; *Drezno* \[polština\]
>
> G104: ***Gdaňsk** (Polsko), přístavní město na severu Polska*
>
> VAR: *Gdańsk* \[polština\]; *Danzig* \[němčina\]; *Gedania*
> \[latina\]; *Gedanum* \[latina\]; *Dantiscum* \[latina\]
>
> G105: ***Innsbruck** (Rakousko), hlavní město spolkové země Tyrolsko*
>
> VAR: *Inšpruk* \[čeština\]; *Inomostí* \[čeština\]; *Oenipontum*
> \[latina\]
>
> G106: ***Vídeň** (Rakousko), spolková země a hlavní město Rakouska*
>
> VAR: *Wien* \[němčina\]; *Vindobona* \[latina\]; *Vienna*
> \[angličtina\]; *Vienne* \[francouzština\]; *Bécs* \[maďarština\];
> *Viedeň* \[slovenština\]; *Wiedeń* \[polština\]
>
> G107: ***Braslovče** (Slovinsko), vesnice, centrum stejnojmenné občiny
> ve středním Slovinsku*
>
> VAR: *Občina Braslovče* \[slovinština\]

##### Obec

Obecný doplněk: *neuvádí se*

Geografický doplněk: okres, stát (v ČR, SR, Polsku, Německu, Maďarsku,
Rakousku a na Ukrajině) NEBO JEN stát (u obcí mimo zmíněné státy).

Doplňující vysvětlení:

• Obce, městečka a města v ČR a SR. V zahraničí sídelní lokality
odpovídající stejné úrovni.

• V případě Polska se zde evidují skutečné sídelní lokality
(miejscowości), tedy města a vesnice, nikoli gminy (které se v našem
pojetí blíží spíše střediskovým obcím či malým okresům). Příslušnost ke
gmině se uvádí ve stručné charakteristice*.* Jako zdroj pro územně
správní členění Polska slouží Krajowy rejestr urzędowy podziału
terytorialnego kraju (TERYT) – **viz přílohu č. 13**. Sídelní lokality
(miejscowości) s typem "miasto" nebo "wieś"se v IS CAM zapisují jako typ
geografického objektu "obec". Jejich nižší úroveň ("część miasta" nebo
"część") pak jako typ "část obce". Další nižší úrovně jako typ "nižší
sídelní jednotka".

• V Chorvatsku se takto evidují opčiny, respektive jejich centra. Další
podřízená sídla opčin pak jako jejich „část obce“. Opčiny jsou napojené
na župy nebo město Záhřeb.

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

> Příklady:
>
> G108: ***Baška** (Frýdek-Místek, Česko), obec v okrese Frýdek-Místek*
>
> VAR: *Baschka* \[němčina\]
>
> *Poznámka: Tato entita vyjadřuje obec Bašku v současném stavu. To
> znamená, že zahrnuje nejenom dřívější obec Bašku, ale i někdejší
> samostané obce Hodoňovice a Kunčičky u Bašky, jež byly v roce 1960
> s obcí Baška sloučeny – **viz příklad G127**.*
>
> G109: ***Třebíč** (Třebíč, Česko), město ve stejnojmenném okrese*
>
> VAR: *Trebitsch* \[němčina\]
>
> G110: ***Bukovac** (Bosna a Hercegovina), vesnice v opštině Doboj
> v severní části Bosny a Hercegoviny*
>
> VAR: Буковац \[srbština\]
>
> G111: ***Doboj** (Bosna a Hercegovina), město, centrum stejnojmenné
> opštiny v jižní části Bosny a Hercegoviny*
>
> VAR: Добој \[srbština\]
>
> G112: ***Bansko** (Bulharsko), město, centrum stejnojmenné obštiny
> v jihozápadním Bulharsku*
>
> VAR: Банско \[bulharština\]
>
> G113: ***Budva** (Černá Hora), město, centrum stejnojmenné opštiny při
> jaderském pobřeží*
>
> VAR: Будва \[srbština\]
>
> G114: ***Wu-chan** (Čína), centrum čínské provincie Chu-pej
> a nejlidnatější město ve střední Číně*
>
> VAR: *Wuhan*; 武汉 \[čínština\]
>
> *Poznámka: Wuhan je jméno v mezinárodním přepisu pinyin (zdroj:
> anglická Wikipedie).*
>
> G115: ***Zagvozd** (Chorvatsko), obec, centrum stejnojmenné opčiny ve
> Splitsko-dalmatské župě na jihu Chorvatska*
>
> G116: ***Aiello del Friuli** (Itálie), obec v provincii Udine*
>
> G117: ***Abensberg** (Kelheim, Německo), město ve spolkové zemi
> Bavorsko*
>
> G118: ***Regenstauf** (Řezno, Německo), obec ve venkovském okrese
> Řezno v Bavorsku*
>
> G119.1: ***Drogomyśl** (Těšín, Polsko), vesnice městsko-vesnické gminy
> Strumień ve Slezském vojvodství*
>
> VAR: *Drahomyšl* \[čeština\]; *Drahomischl* \[němčina\]
>
> G119.2: ***Buczkowice** (Bielsko-Biała, Polsko), vesnice, sídlo
> stejnojmenné vesnické gminy ve Slezském vojvodství*
>
> G119.3: ***Wodzisław Śląski** (Wodzisław Śląski, Polsko), město ve
> Slezském vojvodství, sídlo stejnojmenného okresu a městské gminy*
>
> VAR: *Vladislav* \[čeština\]
>
> G119.4: ***Gryfów Śląski** (Lwówek Śląski, Polsko), město
> v Dolnoslezském vojvodství, sídlo stejnojmenné městsko-vesnické gminy*
>
> G120: ***Abtenau** (Hallein, Rakousko), obec v okrese Hallein ve
> spolkové zemi Salcbursko*
>
> G121: ***Probištip** (Severní Makedonie), obec, centrum stejnojmenné
> opštiny ve východní části Severní Makedonie*
>
> VAR: Пробиштип \[makedonština\]
>
> G122: ***Terchová** (Žilina, Slovensko), obec v okrese Žilina*
>
> G123: ***Gornji Milanovac** (Srbsko), město, centrum stejnojmenné
> opštiny v centrální části Srbska*
>
> VAR: Горњи Милановац \[srbština\]

###### Speciální případy – dvě obce se stejným jménem v jednom okrese (rozlišeno pomocí k. ú.):

> G124.1: ***Mezholezy** (k. ú. Mezholezy u Černíkova, Domažlice,
> Česko), obec v okrese Domažlice*
>
> G124.2: ***Mezholezy** (k. ú. Mezholezy u Horšovského Týna, Domažlice,
> Česko), obec v okrese Domažlice*
>
> G125.1: ***Březina** (k. ú. Březina u Tišnova, Brno-venkov, Česko),
> obec v okrese Brno-venkov*
>
> G125.2: ***Březina** (k. ú. Březina u Křtin, Brno-venkov, Česko), obec
> v okrese Brno-venkov*

###### Zaniklé obce:

> G126: ***Doupov** (Hradiště, Karlovy Vary, Česko : zaniklo), město
> zaniklé následkem zřízení vojenského výcvikového prostoru Hradiště*
>
> VAR: *Duppau* \[němčina\]

##### Část obce

Obecný doplněk: *neuvádí se*

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností).

Doplňující vysvětlení:

• Části obce v ČR (dle RÚIAN) a SR. V zahraničí lokality odpovídající
stejné administrativní úrovni.

• Neevidují se zde městské čtvrti, které nejsou administrativně
vymezenými částmi obce, nýbrž spadají pod nižší sídelní jednotky.

• Pokud není jisté, zda jde o skutečnou administrativně vymezenou část
obce, archivní autoritní záznam entity je založen jako typ geografického
objektu „nižší sídelní jednotka“.

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

> Příklady:
>
> G127: ***Baška** (Baška, Frýdek-Místek, Česko), část obce Baška
> v okrese Frýdek-Místek*
>
> *Poznámka: Tato entita vyjadřuje i dřívější obec Bašku z doby před
> tím, co k ní byly v roce 1960 připojeny sousední obce Hodoňovice
> a Kunčičky u Bašky – **viz příklad G108**.*
>
> G128: ***Jejkov** (Třebíč, Třebíč, Česko), část obce Třebíč v okrese
> Třebíč*
>
> G129: ***Vinohrady** (Praha, Česko), část obce Praha, dříve samostatné
> město*
>
> VAR: *Královské Vinohrady*; *Viničné Hory*; *Königliche Weinberge*
> \[němčina\]
>
> *Poznámka: Okres není v doplňku uveden, neboť Praha patří pod typ
> geografického objektu „obec se širší působností“.*
>
> G130: ***Bad Kösen** (Naumburg, Burgenlandkreis, Německo), část města
> Naumburg ve spolkové zemi Sasko-Anhaltsko*
>
> G131: ***Bobrek** (Těšín, Těšín, Polsko), část města Těšín*
>
> G132: ***Alt-Nagelberg** (Brand-Nagelberg, Gmünd, Rakousko), část obce
> Brand-Nagelberg v okrese Gmünd*
>
> G133: ***Bardejovské Kúpele** (Bardejov, Bardejov, Slovensko), část
> města Bardejov na Slovensku*

###### Zaniklá část obce:

> G134: ***Skryje** (Dukovany, Třebíč, Česko : zaniklo), část obce
> Dukovany zaniklá z důvodu výstavby Jaderné elektrárny Dukovany,
> původně samostatná obec*

##### Městská část/obvod

Obecný doplněk: městská část NEBO městský obvod NEBO obvod hlavního
města Prahy NEBO správní obvod (upřesňuje se ručně).

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností).

Doplňující vysvětlení:

• V ČR dle RÚIAN. V zahraničí lokality odpovídající stejné
administrativní úrovni.

• Vzhledem k tomu, že tento typ geografického objektu se používá
společně pro městskou část i obvod, je potřeba dbát na to, aby byl
obecný doplněk patřičně upraven: buď „městská část“ nebo „městský
obvod“; v Praze se uplatňuje rovněž „obvod hlavního města Prahy“
a „správní obvod“.

• Neevidují se zde městské čtvrti, které nejsou administrativně
vymezenými částmi nebo obvody, nýbrž spadají pod „nižší sídelní
jednotky“.

• U nezaniklých entit se chronologický doplněk neuvádí. U zaniklých
entit se uvádí dle datačních hodnot obsažených v událostech „Vznik“ a
„Zánik“ či pouze ve zjednodušené formě těchto údajů (století apod.).

> Příklady:
>
> G135: ***Komárov** (Opava, Opava, Česko : městská část), jednotka
> místní samosprávy územně členěného statutárního města Opavy*
>
> G136: ***Moravská Ostrava a Přívoz** (Ostrava, Ostrava-město Česko :
> městský obvod), jednotka místní samosprávy územně členěného
> statutárního města Ostravy*
>
> G137: ***Plzeň 3** (Plzeň, Plzeň-město, Česko : městský obvod),
> jednotka místní samosprávy územně členěného statutárního města Plzně*

###### Členění Prahy na části a obvody:

> G138.1: ***Praha 9** (Praha, Česko : městská část), jednotka místní
> samosprávy územně členěného hlavního města Prahy*
>
> G138.2: ***Praha 9** (Praha, Česko : obvod hlavního města Prahy),
> jednotka územního členění státu na podobné úrovni jako okres*
>
> G138.3: ***Praha 9** (Praha, Česko : správní obvod), území, na kterém
> vykonává městská část Praha 9 coby jednotka územní samosprávy určitý
> rozsah státní správy v přenesené působnosti*
>
> G139.1: ***Praha XIV – Nusle** (Praha, Česko : správní obvod :
> 1947-1949), historický správní obvod Prahy*
>
> G139.2: ***Praha 14** (Praha, Česko : správní obvod : 1949-1960),
> historický správní obvod Prahy*

###### Příklady v zahraničí:

> G140: ***Pankow** (Berlín, Německo : městský obvod), třetí městský
> obvod Berlína*
>
> VAR: *Bezirk Pankow* \[němčina\]
>
> G141: ***Mariahilf** (Vídeň, Rakousko : městský obvod), 6. vídeňský
> obvod tradičně označovaný i jako městský okres*
>
> VAR: *VI. Wiener Gemeindebezirk* \[němčina\]

##### Katastrální území

Obecný doplněk: katastrální území

Geografický doplněk: obec, okres, stát

Doplňující vysvětlení: uplatňuje se pouze v ČR.

> Příklad:
>
> G142: ***Baška** (Baška, Frýdek-Místek, Česko : katastrální území)*

##### Ulice

Obecný doplněk: ulice

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností).

Doplňující vysvětlení:

• Uplatňuje se jen tam, kde je zavedena uliční síť.

• V rámci administrativního zařazení se napojují na geografický objekt
typu „obec“ či „obec se širší působností“.

• Preferované je vždy úřední jméno (RÚIAN, mapy.cz).

• Zkratky se používají, pokud jsou v úředním jméně.

• Doplněk „ulice“ se píše vždy.

• Přejmenování ulic se řeší ve variantním označení.

• Změna rozsahu ulice nezakládá důvod k tvorbě nové entity.

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

> Příklady:
>
> G143: ***Bělská** (Paskov, Frýdek-Místek, Česko : ulice)*
>
> G144: ***Podkrušnohorská** (Litvínov, Most, Česko : ulice)*
>
> G145: ***tř. T. G. Masaryka** (Frýdek-Místek, Frýdek-Místek, Česko :
> ulice), ulice ve Frýdku-Místku*
>
> VAR: *Wilsonova tř.* \[datace použití jména: 1918-1948; poznámka ke
> jménu: vyjma 1939-1945\]; *tř. H. Göringa* \[datace použití jména:
> 1939-1945\]; *tř. Rudé armády* \[datace použití jména: 1948-1990\]

###### Příklad ulic stejného jména s jinou polohou ve stejné obci:

> G146.1: ***Hanělova** (Třebíč, Třebíč, Česko : ulice : zaniklo),
> ulice, která se nacházela v horní části dnešního Komenského náměstí*
>
> G146.2: ***Hanělova** (Třebíč, Třebíč, Česko : ulice)* \[datace
> použití jména: 1991-\]
>
> VAR: *Zdeňka Nejedlého* \[datace použití jména: 1954-1991\]

###### Zaniklá ulice:

> G147: ***Josefská** (Frýdek-Místek, Frýdek-Místek, Česko : ulice :
> zaniklo), ulice, která se nacházela v místě jižní části dnešní
> Ostravské ulice*

##### Náměstí

Obecný doplněk: *neuvádí se*

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností).

Doplňující vysvětlení:

• Uplatňuje se jen tam, kde je zavedena uliční síť.

• V rámci administrativního zařazení se napojují na geografický objekt
typu „obec“ či „obec se širší působností“.

• Preferované je vždy úřední jméno (RÚIAN, mapy.cz).

• Zkratky se používají, pokud jsou v úředním jméně.

• Přejmenování náměstí se řeší ve variantním označení.

• Změna rozsahu náměstí nezakládá důvod k tvorbě nové entity.

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

> Příklady:
>
> G148: ***Náměstí Svobody** (Frýdek-Místek, Frýdek-Místek, Česko)*
>
> G149: ***Nám. T. G. Masaryka** (Frýdlant nad Ostravicí, Frýdek-Místek,
> Česko), náměstí ve Frýdlantě nad Ostravicí*

##### Nábřeží

Obecný doplněk: *neuvádí se*

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností).

Doplňující vysvětlení:

• Uplatňuje se jen tam, kde je zavedena uliční síť.

• V rámci administrativního zařazení se napojují na geografický objekt
typu „obec“ či „obec se širší působností“.

• Preferované je vždy úřední jméno (RÚIAN, mapy.cz).

• Zkratky se používají, pokud jsou v úředním jméně.

<span style="color:red;text-decoration:line-through">• Doplněk „nábřeží“ se píše vždy.</span>

• Přejmenování nábřeží se řeší ve variantním označení.

• Změna rozsahu nábřeží nezakládá důvod k tvorbě nové entity.

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

> Příklady:
>
> G150: ***Komenského nábřeží** (Paskov, Frýdek-Místek, Česko)*
>
> G151: ***Nábřeží Karla Čapka** (Chrudim, Chrudim, Česko)*

##### Nižší sídelní jednotka

Obecný doplněk: nižší sídelní jednotka

Geografický doplněk: obec, okres, stát, případně část obce, obec, okres,
stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na Ukrajině) NEBO
JEN obec, stát, případně část obce, obec, stát (mimo zmíněné státy
a u obcí se širší působností).

Doplňující vysvětlení:

• U nezaniklých entit se chronologický doplněk neuvádí. V případě, že má
entita vyplněnou událost zánik, jako chronologický doplněk se uvádí
„zaniklo“.

• Ve stručné charakteristice se blíže specifikuje typ osídlení (místní
název, osada, samota, městská čtvrť apod.). Nejedná se o současné úřední
názvy a nejsou tedy obsaženy v RÚIAN.

• Jako **místní název** se rozumí pojmenovaná lokalita v intravilánu
obce, může se jednat např. o dříve samostatné sídlo integrované do
zástavby, které se nestalo částí obce či jinou neoficiálně pojmenovanou
lokalitu.

• **Městská čtvrť** je označení pro část města, která rovněž není
současnou administrativní částí obce, ale je neformálně vnímána jako
čtvrť.

• **Samota** je izolovaný geografický objekt ležící mimo plynulou
zástavbu tvořený jednou stavbou či areálem. Tento typ geografického
objektu mnohdy evokuje stavby, nesmí se ale zaměnit za entity třídy
dílo/výtvor typu tvrz, hrad, zřícenina, zámek, hospodářský dvůr,
usedlost, mlýn, hamr, hájovna apod. Jako geografický objekt se vytváří
tehdy, je-li třeba vyjádřit sídelní jednotku – nejčastěji se používá
v souvislosti se sčítáním obyvatel, zápisy do matrik a pozemkových knih
apod.

• Jako **osada** je vnímáno menší sídlo (malá skupina domů), větší než
samota, která nemá status obce ani části obce. Osada může být
urbanistický celek oddělený od obce nebo být její integrovanou součástí
(v takovém případě ji lze vnímat i jako místní název).

> Příklady:
>
> G152: ***Dolský Mlýn** (Kamenická Stráň, Růžová, Děčín, Česko : nižší
> sídelní jednotka : zaniklo), osamoceně stojící zaniklý mlýn
> v minulosti evidovaný jako sídelní jednotka*
>
> *Poznámka:* *Entita „**Dolský mlýn** (Kamenická Stráň, Růžová, Děčín,
> Česko : stavba), zřícenina mlýna“ = stavba ve třídě „dílo/výtvor“.*
>
> G153: ***Mezimostí** (Veselí nad Lužnicí, Tábor, Česko : nižší sídelní
> jednotka), místní název*
>
> G154: ***Königsmühle** (Loučná pod Klínovcem, Chomutov, Česko : nižší
> sídelní jednotka : zaniklo), osada*
>
> VAR: *Königův mlýn*
>
> G155: ***Pankrác** (Nusle, Praha, Česko : nižší sídelní jednotka),
> městská čtvrť*
>
> G156: ***Petřiny** (Praha, Česko : nižší sídelní jednotka), sídliště
> a městská čtvrť*
>
> G157: ***U Veličků** (Malenovice, Frýdek-Místek, Česko : nižší sídelní
> jednotka), osada*
>
> G158: ***Zadky** (Vratimov, Ostrava-město, Česko : nižší sídelní
> jednotka), místní název*
>
> G159: ***Buchenwald** (Výmar, Německo : nižší sídelní jednotka),
> umístění koncentračního tábora*
>
> *Poznámka: Buchenwald jako korporace je uveden **v příkladu K127**.*

##### Panství

Obecný doplněk: panství

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností) NEBO JEN kontinent – používá se
variabilně, tzn. nejnižší úroveň tvoří vždy jméno entity, která
popisovanou entitu plně obsáhne.

Doplňující vysvětlení: Tento typ geografického objektu není součástí
hierarchické struktury (byť musí mít určeno administrativní zařazení).
Panství jako geografický objekt se vymezuje pouze do roku 1850. Takto se
evidují i území statků s vlastní vrchnostenskou správou do roku 1850.

> Příklady:
>
> G160: ***Dukovany** (Dukovany, Třebíč, Česko : panství : ?-1850),
> historický statek s vlastní vrchnostenskou správou*
>
> G161: ***Brtnice** (Česko : panství : asi 1410-1850), historické území
> vrchnostenské správy na jihozápadní Moravě*
>
> *Poznámka: Entita „**Velkostatek Brtnice** (Brtnice, Jihlava, Česko :
> asi 1410-1945)“ = třída korporace.*

##### Jiné vymezené území

Obecný doplněk se zpravidla neuvádí; výjimkou jsou případy, kdy je
potřeba odlišit různé entity.

Geografický doplněk: obec, okres, stát (v ČR, SR, Polsku, Německu,
Maďarsku, Rakousku a na Ukrajině) NEBO JEN obec, stát (mimo zmíněné
státy a u obcí se širší působností) NEBO JEN kontinent – používá se
variabilně, tzn. nejnižší úroveň tvoří vždy jméno entity, která
popisovanou entitu plně obsáhne.

Doplňující vysvětlení: Tento typ geografického objektu není součástí
hierarchické struktury (byť musí mít určeno administrativní zařazení).
Jeho bližší specifikaci je nutno vyjádřit podrobněji ve stručné
charakteristice. Užití tohoto typu geografického objektu je velice
rozmanité. Následující příklady jsou rozděleny do několika tematických
skupin.

###### Příklady konfederačních, nadstátních útvarů:

Jde o administrativně vymezená území, která ve větší míře přesahují
rámec použití typu geografického objektu „stát“.

> Příklady:
>
> G162.1: ***Svatá říše římská** (Evropa : 800-1806), historický státní
> útvar, konfederační volená monarchie, mnohonárodnostní svazek*
>
> VAR: *Římská říše*; *Svatá říše římská národa německého*
>
> G162.2: ***Rýnský spolek** (Evropa : 1806-1813), historický státní
> útvar*
>
> VAR: *Konfederované státy rýnské*; *Rheinbund* \[němčina\];
> *Confédération du Rhin* \[francouzština\]
>
> G162.3: ***Německý spolek** (Evropa : 1815-1866), historický státní
> útvar*
>
> VAR: *Deutscher Bund* \[němčina\]
>
> G162.4: ***Severoněmecký spolek** (Evropa : 1867-1871), historický
> státní útvar*
>
> VAR: *Severoněmecká konfederace*; *Norddeutscher Bund* \[němčina\]
>
> G163: ***Království polské a Velkoknížectví litevské** (Evropa :
> 1569-1795), polsko-litevské soustátí*
>
> VAR: *Polsko-litevská unie*; *Królestwo Polskie i Wielkie Księstwo
> Litewskie* \[polština\]; *Lenkijos Karalystė ir Lietuvos Didžioji
> Kunigaikštystė* \[litevština\]; *Regnum Poloniae Magnusque Ducatus
> Lithuaniae* \[latina\]
>
> G164: ***Commonwealth,** volné sdružení Spojeného království Velké
> Británie a Severního Irska a jeho bývalých dominií a kolonií*
>
> VAR: *Commonwealth of Nations* \[angličtina\]; *Společenství národů*;
> *Britské impérium* \[datace použití jména: do 1931\]; *Britské
> společenství národů* \[1931-1947\]
>
> *Poznámka: Geografický doplněk není vyplněn, neboť zahrnuje území na
> více kontinentech; v „administrativním zařazení“ vztah na entitu
> „Země“.*
>
> G165: ***Evropská unie*** - geografický doplněk není vyplněn, některé
> státy EU mají území i mimo Evropu; v „administrativním zařazení“ vztah
> na entitu „Země“
>
> VAR: *EU*

###### Příklady administrativně vymezených území:

Jde o administrativně vymezená území, která nelze popsat výše uvedenými
typy geografických objektů.

> Příklady:
>
> G166: ***Jejkov** (Třebíč, Třebíč, Česko : sčítací obvod : 1869)*
>
> *Poznámka: Uveden specifický obecný doplněk kvůli odlišení od entity
> reprezentující stejnojmennou část obce.*
>
> G167: ***Petrohradská gubernie** (Estonsko a Rusko : 1708-1927)*

###### Příklady neadministrativně vymezených území:

Jde o neadministrativně vymezená území, v současnosti chápaná jako:

a\) historická území, jejichž jméno sice může evokovat nějaký historický
státní útvar, nicméně se s ním nemusí plně shodovat,

b\) oblasti, regiony a části jiných větších území.

Ve všech případech nejsou tato území vymezována chronologicky
a nepoužívají se k vyjádření jurisdikce. Slouží k určení polohy, pokud
tato není určitelná přesněji (na úrovni sídel a níže).

> Příklady:
>
> G168: ***Bechyňsko** (Česko), Bechyně a její okolí bez vazby na
> administrativně určené jednotky*
>
> vs.
>
> entity „***Bechyňsko** (Česko : kraj : 9. st.-1751)*“, „***Bechyně**
> (Česko : okres : 1960-)*“ ad.
>
> G169.1: ***Praha** **a okolí** (Česko), Praha a její okolí bez vazby
> na administrativně určené jednotky*
>
> *Poznámka: Případ, kdy entitu nelze vyjádřit jednoduše jednoslovným
> výrazem.*
>
> G169.2: ***Praha** (Česko : okolí), okolí Prahy vyjma samotného města
> bez vazby na administrativně určené jednotky*
>
> *Poznámka: Případ, kdy entitu nelze vyjádřit jednoduše jednoslovným
> výrazem.*
>
> G170: ***Špindlerův Mlýn a okolí** (Trutnov, Česko), Špindlerův Mlýn
> a jeho okolí bez vazby na administrativně určené jednotky*
>
> G171: ***New York a okolí** (Spojené státy americké), město New York
> a jeho okolí bez vazby na administrativně určené jednotky*
>
> *Poznámka: Případ, kdy entitu nelze vyjádřit jednoduše jednoslovným
> výrazem.*
>
> G172: ***Euroregion Egrensis** (Česko a Německo), oblast
> přeshraničního styku a spolupráce obcí Česka a Německa*
>
> *Poznámka: Nejde o administrativně vymezené území státu či Evropské
> unie.*
>
> G173: ***jižní Čechy** (Česko), jižní část Čech bez vazby na
> administrativně určené jednotky*
>
> vs.
>
> ***Jihočeský kraj** (Česko : kraj : 1960-1990)*
>
> G174: ***Morava** (Česko), území Moravy bez vazby na administrativně
> určené jednotky*
>
> vs.
>
> entity „***Země moravská** (Česko : 1918-1928)*“, „***Země
> moravskoslezská** (Česko : 1928-1948)*“ a „***Markrabství moravské**
> (Česko : 1182-1918)*“
>
> G175: ***Normandie** (Francie), historické území*
>
> G176.1: ***Prusko** (Evropa), historické území v Evropě bez vazby na
> administrativně určené jednotky*
>
> vs.
>
> ***Pruské království** (1701-1918)*
>
> G176.2: ***Východní Prusko** (Evropa), historické území mezi řekami
> Visla a Němen u pobřeží Baltského moře*
>
> VAR: *Prusy*; *Prusko*
>
> G177: ***Slezsko** (Evropa), historické území*
>
> *Poznámka: Historické území, rozkládající se v současnosti převážně
> v Polsku, zčásti v Česku a z malé části v Německu. Může být dále
> děleno na Dolní a Horní Slezsko.*

###### Okupovaná území:

> G178: ***Protektorát Čechy a Morava** (Česko : 1939-1945), historický
> státní útvar vytvořený nacistickým Německem*
>
> VAR: *Protektorat Böhmen und Mähren* \[němčina\]; *Protektorát*
>
> G179: ***Generální gouvernement** (Polsko : 1939-1945), územně-správní
> jednotka jako autonomní část Třetí říše zahrnující část okupovaného
> území původního meziválečného Polska*
>
> VAR: *Generalgouvernement für die besetzten polnischen Gebiete*
> \[němčina\]; *Generalne Gubernatorstwo* \[polština\]; *Generalna
> Gubernia* \[polština\]
>
> G180.1: ***Východní marka** (1938-1945), území Rakouska po anexi
> nacistickým Německem*
>
> VAR: *Land Österreich* \[datace použití jména 1938-1940; němčina\];
> *Reichsgaue der Ostmark* \[1940-1942; němčina\]; *Alpen- und
> Donau-Reichsgaue* \[1942-1945; němčina\]; *Ostmark* \[němčina\];
> *Rakousko*
>
> G180.2: ***Rakousko** (1945-1955), území Rakouska rozdělené po druhé
> světové válce na okupační zóny*
>
> VAR: *Österreichische Besatzungszonen* \[němčina\]; *Besatzungszonen
> Österreichs* \[němčina\]
>
> G181.1: ***Německo** (1945-1949), území Německa rozdělené po druhé
> světové válce na okupační zóny*
>
> G181.2: ***Bizónie** (1947-1948), sloučená britská a americká okupační
> zóna Německa*
>
> G181.3: ***Trizónie** (1948-1949), sloučená britská, americká
> a francouzská okupační zóna Německa*
>
> G181.4: ***Sovětská okupační zóna** (1945-1949), okupační zóna Německa
> spravovaná Sovětským svazem*

#### Podtřída „administrativně vymezené části přírody“

Geografický doplněk (obecné pravidlo pro celou podtřídu): část obce,
obec, okres, stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na
Ukrajině) NEBO JEN část obce, obec, stát (mimo zmíněné státy a u obcí se
širší působností) NEBO JEN kontinent – používá se variabilně, tzn.
nejnižší úroveň tvoří vždy jméno entity, která popisovanou entitu plně
obsáhne.

##### Chráněná část přírody

Obecný doplněk je potřeba samostatně specifikovat, pokud specifikace
není součástí jména: např. přírodní památka, ptačí oblast, evropsky
významná lokalita.

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Ptačí oblasti, Evropsky významné lokality dle
nařízení vlády č. 318/2013 Sb., Významný krajinný prvek podle zákona č.
114/1992 Sb. apod. Eviduje se vždy pod příslušným konkrétním typem
geografického objektu (rašeliniště, les, zahrady atd.).

> Příklady:
>
> G182: ***Blatov a Xaverovský háj** (Praha, Česko : evropsky významná
> lokalita)*
>
> VAR: *evropsky významná lokalita Blatov a Xaverovský háj*; evr*opsky
> významná lokalita Xaverovský háj a Blatov*; *Xaverovský háj a Blatov*
>
> G183: ***Heřmanský stav - Odra - Poolzí** (Karviná, Česko : ptačí
> oblast)*
>
> VAR: *ptačí oblast Heřmanský stav*; *ptačí oblast Heřmanský stav –
> Odra – Poolzí*
>
> G184: ***Chráněná krajinná oblast Beskydy** (Česko)*
>
> VAR: *CHKO Beskydy*
>
> G185: ***Chráněná krajinná oblast Pálava** (Břeclav, Česko)*
>
> VAR: *CHKO Pálava*
>
> G186: ***Kamenec** (Dobrá, Frýdek-Místek, Česko : přírodní památka)*
>
> VAR: *přírodní památka Kamenec*
>
> G187: ***Krkonošský národní park** (Česko)*
>
> VAR: *KRNAP*
>
> G188: ***Sočský národní park** (Rusko)*
>
> VAR: *Sočinskij nacionalnyj park* \[ruština\]*;* Сочинский
> национальный парк \[ruština\]
>
> G189.1: ***Tatranský národní park** (Polsko)*
>
> VAR: *polský Tatranský národní park*; *TRNAP*; *polský TRNAP*
>
> G189.2: ***Tatranský národní park** (Slovensko)*
>
> VAR: *slovenský Tatranský národní park*; *TRNAP*; *slovenský TRNAP*
>
> G190: ***Yellowstonský národní park** (Spojené státy americké)*
>
> VAR: *Yellowstonský park*; *park Yellowstone*; *Yellowstone National
> Park* \[angličtina\]

###### Ukázky různých typů geografického objektu nesoucích stejné jméno:

> G191: ***Adršpašsko-teplické skály** (Česko : přírodní rezervace)*
>
> VAR: *přírodní rezervace Adršpašsko-teplické skály*
>
> vs.
>
> ***Adršpašsko-teplické skály** (Česko : skalní město)*
>
> VAR: *skalní město Adršpašsko-teplické skály*
>
> G192: ***Bohdanečský rybník** (Lázně Bohdaneč, Pardubice, Česko :
> přírodní rezervace)*
>
> VAR: *přírodní rezervace Bohdanečský rybník*
>
> vs.
>
> ***Bohdanečský rybník** (Lázně Bohdaneč, Pardubice, Česko : rybník)*
>
> G193: ***Čeřínek** (Jihlava, Česko : přírodní park)*
>
> VAR: *přírodní park Čeřínek*; *PP Čeřínek*
>
> vs.
>
> ***Čeřínek** (Jihlava, Česko : hora)*
>
> VAR: *hora Čeřínek*
>
> G194: ***Dehtář** (Dehtáře, Žabovřesky, České Budějovice, Česko :
> ptačí oblast)*
>
> VAR: *ptačí oblast Dehtář*
>
> vs.
>
> ***Dehtář** (Dehtáře, Žabovřesky, České Budějovice, Česko : rybník)*
>
> VAR: *rybník Dehtář*
>
> G195: ***Oderské vrchy** (Česko : přírodní park)*
>
> VAR: *přírodní park Oderské vrchy*; *PP Oderské vrchy*
>
> vs.
>
> ***Oderské vrchy** (Česko : vrchovina)*
>
> G196: ***Panská skála** (Kamenický Šenov, Česká Lípa, Česko : národní
> přírodní památka)*
>
> VAR: *národní přírodní památka Panská skála*; *NPM Panská skála*
>
> vs.
>
> ***Panská skála** (Kamenický Šenov, Česká Lípa, Česko : skalní útvar)*

##### Lesopark/park/sad

Obecný doplněk je potřeba zapsat ručně dle přesného typu: lesopark,
park, sad.

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G197: ***Havraňák** (Čakovice, Praha, Česko : lesopark)*
>
> VAR: *lesopark Havraňák*; *lesopark Havraňák Čakovice*
>
> G198: ***Lesopark Jiřího Potůčka** (Pardubice, Pardubice, Česko :
> lesopark)*
>
> G199: ***Lesopark Třinec** (Třinec, Frýdek-Místek, Česko : lesopark)*
>
> G200: ***Park Puškinova** (Frýdek, Frýdek-Místek, Frýdek-Místek, Česko
> : park)*
>
> VAR: *Puškinův park*; *Puškinův park Frýdek*; *Puškinův park
> Frýdek-Místek*
>
> G201: ***Vonešovy sady** (Hradec Králové, Hradec Králové, Česko :
> park)*

##### Zahrada

Obecný doplněk: zahrada

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: botanické a jiné pojmenované zahrady.

> Příklady:
>
> G202: ***Akademická zahrada** (Lednice, Břeclav, Česko : zahrada)*
>
> VAR: *Akademická zahrada Lednice*; *Akademická zahrada v Lednici*;
> *Akademická zahrada v Lednicích*
>
> G203: ***Pivovarské zahrady** (Český Krumlov, Český Krumlov, Česko :
> zahrada)*
>
> VAR: *Pivovarské zahrady Český Krumlov*; *Pivovarské zahrady v Českém
> Krumlově*

##### Jiné administrativně vymezené části přírody

Obecný doplněk je potřeba zapsat ručně dle přesného typu: polesí,
rybářský revír, obora, honitba, viniční trať aj.

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: polesí, rybářské revíry, obory, honitby, viniční
tratě (vyhláška 254/2010 Sb.).

> Příklady:
>
> G204: ***Baštice 1 A - MO Frýdek-Místek** (Baška, Frýdek-Místek, Česko
> : rybářský revír)*
>
> VAR: *rybářský revír Baštice 1 A*; *rybářský revír Baštice*; *rybářský
> revír Baška*
>
> G205: ***Mírov** (Šumperk, Česko : polesí)*
>
> VAR: *polesí Mírov*
>
> G206: ***Šárka** (Praha, Česko : honitba)*
>
> VAR: *honitba Šárka*; *honitba Šárka Praha*; *honitba Šárka v Praze*
>
> G207: ***Šibeniční vrch** (Drnholec, Břeclav, Česko : viniční trať)*
>
> VAR: *viniční trať Šibeniční vrch*
>
> G208: ***Žehušice** (Žehušice, Kutná Hora, Česko : obora)*
>
> VAR: *obora Žehušice*; *obora v Žehušicích*; *obora bílých jelenů
> Žehušice*; *Žehušická obora*

#### Podtřída „další vymezené lokality, oblasti a zóny“

Geografický doplněk (obecné pravidlo pro celou podtřídu): část obce,
obec, okres, stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na
Ukrajině) NEBO JEN část obce, obec, stát (mimo zmíněné státy a u obcí se
širší působností) NEBO JEN kontinent – používá se variabilně, tzn.
nejnižší úroveň tvoří vždy jméno entity, která popisovanou entitu plně
obsáhne.

##### Archeologická lokalita

Obecný doplněk: archeologická lokalita

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: archeologické lokality či naleziště.

> Příklady:
>
> G209: ***Albrechtice - hrad neznámého jména** (Horní Jiřetín, Most,
> Česko : archeologická lokalita)*
>
> VAR: *archeologická lokalita Albrechtice*; *zaniklý hrad Albrechtice*;
> *zaniklý hrad u Albrechtic*
>
> G210: ***Šipka** (Štramberk, Nový Jičín, Česko : archeologická
> lokalita)*
>
> VAR: *archeologická lokalita Šipka*

##### Národopisná oblast

Obecný doplněk: národopisná oblast

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G211: ***Doudlebsko** (Česko : národopisná oblast)*
>
> VAR: *národopisná oblast Doudlebsko*
>
> G212: ***Valašsko** (Česko : národopisná oblast)*
>
> VAR: *národopisná oblast Valašsko*

##### Památková zóna

Obecný doplněk: památková zóna

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Oficiální názvy z památkového katalogu je vhodné
upravit tak, aby jméno entity začínalo vždy jménem lokality. Zdroj
informací: <https://pamatkovykatalog.cz/>. Je vždy potřeba odlišit
areály/území od jednotlivých objektů, které patří do třídy
„dílo/výtvor“.

> Příklady:
>
> G213: ***Český Krumlov - Plešivec** (Český Krumlov, Český Krumlov,
> Česko : památková zóna)*
>
> VAR: *památková zóna Český Krumlov - Plešivec*; *památková zóna
> Plešivec*; *památková zóna Český Krumlov*; *PZ Český Krumlov -
> Plešivec*; *PZ Plešivec*; *PZ Český Krumlov*
>
> G214: ***Kladruby nad Labem - areál hřebčína** (Kladruby nad Labem,
> Pardubice, Česko : památková zóna), areál s kmenovým chovným stádem
> starokladrubského koně*
>
> VAR: *památková zóna Kladruby nad Labem - Hřebčín*; *památková zóna
> Kladruby nad Labem*; *památková zóna Hřebčín Kladruby nad Labem*; *PZ
> Kladruby nad Labem - Hřebčín*; *PZ Hřebčín*; *PZ Kladruby nad Labem*

##### Rekreační území

Obecný doplněk: rekreační území

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G215: ***Lom Leštinka** (Skuteč, Skuteč, Chrudim, Česko : rekreační
> území), sportovní komplex*
>
> VAR: *rekreační území Leštinka*; *rekreační území Lom Leštinka*
>
> G216: ***Výr** (Výrovice, Znojmo, Česko : rekreační území), rekreační
> areál na jižní Moravě*
>
> VAR: *rekreační území Výr*

#### Podtřída „geomorfologické útvary na dně moře“

##### Útvar na dně moře/oceánu

Obecný doplněk: *neuvádí se*

Geografický doplněk: moře NEBO oceán.

> Příklady:
>
> G217: ***Velký bariérový útes** (Korálové moře)*
>
> VAR: *Great Barrier Reef* \[angličtina\]
>
> G218: ***Sundský příkop** (Indický oceán), hlubokooceánský příkop
> v Indickém oceánu poblíž Sumatry*
>
> VAR: *Jávský příkop*; *Sunda Trench*

#### Podtřída „geomorfologické útvary na zemském povrchu“

Geografický doplněk (obecné pravidlo pro celou podtřídu): část obce,
obec, okres, stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na
Ukrajině) NEBO JEN část obce, obec, stát (mimo zmíněné státy a u obcí se
širší působností) NEBO JEN kontinent NEBO JEN moře NEBO JEN oceán –
používá se variabilně, tzn. nejnižší úroveň tvoří vždy jméno entity,
která popisovanou entitu plně obsáhne.

##### Ostrov

Obecný doplněk: ostrov

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: ostrovy včetně atolů.

> Příklady:
>
> G219: ***Štvanice** (Holešovice, Praha, Česko : ostrov)*
>
> VAR: *ostrov Štvanice*
>
> G220: ***Bikini** (Marshallovy ostrovy : ostrov), atol*
>
> VAR: *atol Bikiny*; *ostrov Bikiny*
>
> G221: ***Öland** (Švédsko : ostrov)*
>
> VAR: *ostrov Öland*

###### Ukázky různých typů geografického objektu nesoucích stejné jméno:

> G222: ***Grónsko** (Dánsko : ostrov)*
>
> VAR: *ostrov Grónsko*; *Grønland* \[dánština\]; *Kalaallit Nunaat*
> \[grónština\]; *Greenland* \[angličtina\]
>
> vs.
>
> ***Grónsko** (Dánsko : autonomní část)* = podtřída „administrativně či
> jinak lidmi vymezená území“
>
> G223: ***Irsko** (Irsko a Velká Británie : ostrov)*
>
> VAR: *ostrov Irsko*; *Ireland* \[angličtina\]; *Éire* \[irština\]
>
> vs.
>
> ***Irsko*** \[stát\] = podtřída „administrativně či jinak lidmi
> vymezená území“
>
> G224: ***Madagaskar** (Madagaskar : ostrov)*
>
> VAR: *ostrov Madagaskar*; *Madagascar* \[angličtina\]
>
> vs.
>
> ***Madagaskar*** \[stát\] = podtřída „administrativně či jinak lidmi
> vymezená území“

##### Poloostrov

Obecný doplněk: poloostrov

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G225: ***Apeninský poloostrov** (Evropa : poloostrov)*
>
> VAR: *Penisola appenninica* \[italština\]; *Penisola italiana*
> \[italština\]; *Penisola italica* \[italština\]
>
> G226: ***Cornwall** (Velká Británie : poloostrov)*
>
> VAR: *poloostrov Cornwall*
>
> G227: ***Čukotský poloostrov** (Rusko : poloostrov)*
>
> VAR: *Čukotskij poluostrov* \[ruština\]; Чукотский полуостров
> \[ruština\]
>
> G228: ***Peloponés** (Řecko : poloostrov)*
>
> VAR: *Peloponéský poloostrov*; *poloostrov Peloponés*; *Pelopónnīsos*
> \[řečtina\]; Πελοπόννησος \[řečtina\]

##### Souostroví

Obecný doplněk: souostroví

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G229: ***Azory** (Portugalsko : souostroví)*
>
> VAR: *Azorské souostroví*; *souostroví Azory; Açores*
> \[portugalština\]*; ilhas dos Açores* \[portugalština\]
>
> vs.
>
> ***Azory** (Portugalsko : autonomní část)* = podtřída „administrativně
> či jinak lidmi vymezená území“
>
> G230: ***Jižní Shetlandy** (Antarktida : souostroví)*
>
> VAR: *souostroví Jižní Shetlandy*; *islas Shetland del Sur*
> \[španělština\]; *South Shetland Islands* \[angličtina\]; *îles
> Shetland du Sud* \[francouzština\]; *Južnyje Šetlandskije ostrova*
> \[ruština\]
>
> G231: ***Kanárské ostrovy** (Španělsko : souostroví)*
>
> VAR: *Kanárské souostroví*
>
> vs.
>
> ***Kanárské ostrovy** (Španělsko : autonomní část)* = podtřída
> „administrativně či jinak lidmi vymezená území“
>
> G232: ***Kurily** (Tichý oceán : souostroví), sporné území mezi
> Japonskem a Ruskem*
>
> VAR: *Kurilské souostroví*; *souostroví Kurily*; *Kurilské ostrovy*;
> *Chishima rettō* \[japonština\]; 千島列島\[japonština\]; *Kuriru
> rettō* \[japonština\]; クリル列島 \[japonština\]; *Kurilskije ostrova*
> \[ruština\]; *Курильские острова* \[ruština\]

##### Nížina

Obecný doplněk: nížina

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Úvaly, kotliny, brázdy a brány. Nadmořská výška
do 200 (případně 300) m n. m.

> Příklady:
>
> G233: ***Dolnomoravský úval** (Česko a Slovensko : nížina)*
>
> G234: ***Dyjsko-svratecký úval** (Česko : nížina)*
>
> G235: ***Hornomoravský úval** (Česko : nížina)*
>
> G236: ***Ostravská pánev** (Česko : nížina)*
>
> G237: ***Polabí** (Česko : nížina)*
>
> G238: ***Středomoravská niva** (Česko : nížina)*

##### Pahorkatina

Obecný doplněk: pahorkatina

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: typ vysočiny s nadmořskou výškou od 200 až 600 m
n. m.

> Příklady:
>
> G239: ***Opavská pahorkatina** (Česko : pahorkatina)*
>
> G240: ***Středočeská pahorkatina** (Česko : pahorkatina)*
>
> G240: ***Táborská pahorkatina** (Česko : pahorkatina)*

##### Vrchovina

Obecný doplněk: vrchovina

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: typ vysočiny s nadmořskou výškou od 600 až 900 m
n. m.

> Příklady:
>
> G241: ***Brdy** (Česko : vrchovina)*
>
> G242: ***Českomoravská vrchovina** (Česko : vrchovina)*
>
> VAR: *Vysočina*; *Českomoravská vysočina*
>
> G243: ***Malé Karpaty** (Slovensko a Rakousko : vrchovina)*
>
> G243: ***Nízký Jeseník** (Česko : vrchovina)*
>
> G244: ***Železné hory** (Česko : vrchovina)*

##### Pohoří

Obecný doplněk: pohoří

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: typ vysočiny s nadmořskou výškou nad 900 m n. m.

> Příklady:
>
> G245: ***Beskydy** (Evropa : pohoří)*
>
> G246: ***Hrubý Jeseník** (Česko : pohoří)*
>
> G247: ***Krkonoše** (Česko a Polsko : pohoří)*
>
> G248: ***Moravskoslezské Beskydy** (Česko a Slovensko : pohoří)*
>
> G249: ***Šumava** (Evropa : pohoří)*

##### Plošina

Obecný doplněk: plošina

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: výrazná plochá část krajiny: plošina nebo
planina.

> Příklady:
>
> G250: ***Ostrovská plošina** (Ostrov u Macochy, Blansko, Česko :
> plošina)*
>
> G251: ***Meklenburská jezerní plošina** (Německo : plošina)*
>
> VAR: *Mecklenburger Seenplatte* \[němčina\]
>
> G252: ***Tibetská náhorní plošina** (Čína : plošina)*
>
> VAR: Tibetská plošina; Bod sa mtho \[tibetština\]; བོད་ས་མཐོ
> \[tibetština\]; Qingzang Gaoyuan \[čínština\]; 青藏高原 \[čínština\]

##### Údolí

Obecný doplněk: údolí

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G253: ***Babiččino údolí** (Náchod, Česko : údolí)*
>
> G254: ***Prokopské údolí** (Praha, Česko : údolí)*
>
> G255: ***Ptáčovský žleb** (Třebíč, Třebíč, Česko : údolí)*
>
> VAR: *údolí Ptáčovský žleb*

##### Kopec

Obecný doplněk: kopec

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Povrchové tvary se zřetelně patrným vrcholem,
který vystupuje nad okolní terén, a to do nadmořské výšky 600 m n. m.
Pro určení geografického doplňku se nezohledňuje pouze vrchol, ale kopec
jako celek (u kopců v ČR tedy většinou okres).

> Příklady:
>
> G256: ***Bílá hora** (Ruzyně, Praha, Česko : kopec)*
>
> G257: ***Pekelný kopec** (Třebíč, Česko : kopec)*

##### Hora

Obecný doplněk: hora

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Povrchové tvary se zřetelně patrným vrcholem,
který vystupuje nad okolní terén, a to s nadmořskou výškou nad 600 m n.
m. Pro určení geografického doplňku se nezohledňuje pouze vrchol, ale
hora jako celek (v ČR tedy většinou okres).

> Příklady:
>
> G258: ***Lysá hora** (Frýdek-Místek, Česko : hora)*
>
> G259: ***Milešovka** (Česko : hora)*
>
> *Poznámka: Hora nacházející se na území dvou okresů.*
>
> G260: ***Sněžka** (Česko a Polsko : hora)*
>
> *Poznámka: Hora nacházející se na území dvou států.*

##### Soutěska

Obecný doplněk: soutěska

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: soutěsky, rokle, strže, rokliny, kaňony.

> Příklady:
>
> G261: ***Černá rokle** (Nový Kostel, Cheb, Česko : soutěska)*
>
> G262: ***Edmundova soutěska** (Hřensko, Děčín, Česko : soutěska)*
>
> G263: ***Velký kaňon** (Arizona, Spojené státy americké : soutěska)*
>
> VAR: *Grand Canyon* \[angličtina\]

##### Průsmyk

Obecný doplněk: průsmyk

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: průsmyky a horská sedla.

> Příklady:
>
> G264: ***Červenohorské sedlo** (Česko : průsmyk)*
>
> G265: ***Jablunkovský průsmyk** (Mosty u Jablunkova, Frýdek-Místek,
> Česko : průsmyk)*
>
> G266: ***Ramzovské sedlo** (Jeseník, Česko : průsmyk)*
>
> G267: ***Brennerský průsmyk** (Rakousko : průsmyk)*
>
> VAR: *Brennerpass* \[němčina\]; *Passo del Brennero* \[italština\]
>
> G268: ***Paškapole** (Velemín, Litoměřice, Česko : průsmyk)*
>
> VAR: *průsmyk Paškapole*
>
> G269: ***Stelvio** (Itálie : průsmyk)*
>
> VAR: *průsmyk Stelvio*

##### Propast

Obecný doplněk: propast

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: propasti a propadliny.

> Příklady:
>
> G270: ***Hranická propast** (Hranice, Přerov, Česko : propast)*
>
> G271: ***Macocha** (Vilémovice, Blansko, Česko : propast)*
>
> VAR: *propast Macocha*
>
> G272: ***Schnödův peň** (Krásno, Sokolov, Česko : propast),
> propadlina*

##### Sopka

Obecný doplněk: sopka

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: pouze aktivní sopky.

> Příklad:
>
> G273: ***Etna** (Itálie : sopka)*

##### Jeskyně

Obecný doplněk: jeskyně

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G274: ***Býčí skála** (Hrabůvka, Blansko, Česko : jeskyně)*
>
> VAR: *jeskyně Býčí skála*
>
> G275: ***Šipka** (Štramberk, Nový Jičín, Česko : jeskyně)*
>
> VAR: *jeskyně Šipka*
>
> G276: ***Javoříčské jeskyně** (Březina, Luká, Olomouc, Česko :
> jeskyně)*

##### Skalní útvar

Obecný doplněk: skalní útvar

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: solitérní skalní útvary nebo konkrétní skalní
útvar v rámci skalního města.

> Příklady:
>
> G277: ***Bílá skála** (Blansko, Blansko, Česko : skalní útvar)*
>
> G278: ***Čapská palice** (Zátyní, Dubá, Česká Lípa, Česko : skalní
> útvar)*
>
> G279: ***Panská skála** (Kamenický Šenov, Česká Lípa, Česko : skalní
> útvar)*
>
> vs.
>
> ***Panská skála** (Kamenický Šenov, Česká Lípa, Česko : národní
> přírodní památka)*
>
> G280: ***Petrovy kameny** (Malá Morávka, Bruntál, Česko : skalní
> útvar)*

##### Skalní město

Obecný doplněk: skalní město

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: skupina skalních útvarů.

> Příklad:
>
> G281: ***Adršpašsko-teplické skály** (Česko : skalní město)*

##### Útes

Obecný doplněk: útes

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: pobřežní a horské útesy. Mořské a oceánské útesy
(např. Velký bariérový útes) = útvary na dně moře.

> Příklady:
>
> G282: ***Seven Sisters** (Velká Británie : útes), pobřežní útes*
>
> VAR: *útes Seven Sisters*
>
> G283: ***Trango Towers** (Pakistán : útes), horský útes*
>
> VAR: *útes Trango Towers*

##### Mys

Obecný doplněk: mys

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G284: ***Mys Dobré naděje** (Jihoafrická republika : mys)*
>
> VAR: *Kaap die Goeie Hoop* \[afrikánština\]; *Cape of Good Hope*
> \[angličtina\]
>
> G285: ***Ponta do Seixas** (Brazílie : mys)*
>
> VAR: *mys Ponta da Seixas*

##### Jiný přírodní útvar

Obecný doplněk je potřeba specifikovat ručně.

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: například lidsky nevyužívané uhelné sloje je
potřeba odlišovat od dolů (= dílo/výtvor).

> Příklad:
>
> G286: ***Uhelná sloj v Landeku** (Petřkovice, Ostrava, Ostrava-město,
> Česko : sloj)*

#### Podtřída „vodstvo a vodní plocha, vodní tok“

Geografický doplněk (obecné pravidlo pro celou podtřídu): část obce,
obec, okres, stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na
Ukrajině) NEBO JEN část obce, obec, stát (mimo zmíněné státy a u obcí se
širší působností) NEBO JEN kontinent NEBO JEN moře NEBO JEN oceán –
používá se variabilně, tzn. nejnižší úroveň tvoří vždy jméno entity,
která popisovanou entitu plně obsáhne.

##### Oceán

Obecný doplněk: oceán

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G287: ***Atlantský oceán** (oceán)*
>
> VAR: *Atlantik*; *Atlantic Ocean* \[angličtina\]
>
> G288: ***Tichý oceán** (oceán)*
>
> VAR: *Pacifik*; *Pacific Ocean* \[angličtina\]

##### Moře

Obecný doplněk: moře

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G289: ***Barentsovo moře** (moře)*
>
> VAR: *Barents Sea* \[angličtina\]; *Barentshavet* \[norština\]
>
> G290: ***Středozemní moře** (moře)*
>
> VAR: *Mediterranean Sea* \[angličtina\]

##### Záliv

Obecný doplněk: záliv

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: zálivy, fjordy.

> Příklady:
>
> G291: ***Boka Kotorska** (Černá Hora : záliv)*
>
> G292: ***Botnický záliv** (Evropa : záliv)*
>
> VAR: *Pohjanlahti* \[finština\]; *Bottniska viken* \[švédština\];
> *Gulf of Bothnia* \[angličtina\]
>
> G293: ***Geirangerfjord** (Norsko : záliv)*
>
> VAR: *záliv Geirangerfjord*; *fjord Geirangerfjord*
>
> G294: ***Mexický záliv** (Severní Amerika : záliv)*
>
> VAR: *Gulf of Mexico* \[angličtina\]; *golfo de México*
> \[španělština\]

##### Jezero

Obecný doplněk: jezero

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Jezera, plesa. Máchovo jezero je rybník.

> Příklady:
>
> G295: ***Černé jezero** (Železná Ruda, Klatovy, Česko : jezero)*
>
> G296: ***Bajkal** (Rusko : jezero)*
>
> VAR: *jezero Bajkal*; *Bajgal dalaj* \[blíže neurčený mongolský
> jazyk\]; Байгал далай \[blíže neurčený mongolský jazyk\]; *Bajkal*
> \[ruština\]; Байкал \[ruština\]
>
> G297: ***Kaspické moře** (Eurasie : jezero)*
>
> VAR: *Xazar dənizi* \[azerbajdžánština\]; *Daryā-ye Māzandarān*
> \[perština\]; دریای مازندران \[perština\]; *Daryye Ḫazar*
> \[perština\]; دریای خزر \[perština\]; *Kaspiı teńizi* \[kazaština\];
> Каспий теңізі \[kazaština\]; *Kaspijskoje morе* \[ruština\];
> Каспийское море \[ruština\]; *Hazar deňzi* \[turkménština\]; *Kaspi
> deňzi* \[turkménština\]
>
> G298: ***Štrbské pleso** (Štrba, Poprad, Slovensko : jezero)*

##### Vodní nádrž

Obecný doplněk: vodní nádrž

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G299.1: ***Lipno** (Český Krumlov, Česko : vodní nádrž)*
>
> VAR: *Lipno I*; *vodní nádrž Lipno*; *vodní nádrž Lipno I*; *přehrada
> Lipno*; *přehrada Lipno I*
>
> G299.2: ***Lipno II** (Vyšší Brod, Český Krumlov, Česko : vodní
> nádrž)*
>
> VAR: *Lipno II*; *vodní nádrž Lipno*; *vodní nádrž Lipno II*;
> *přehrada Lipno*; *přehrada Lipno II*
>
> G300: ***Orlík** (Česko : vodní nádrž)*
>
> VAR: *vodní nádrž Orlík*; *přehrada Orlík*
>
> *Poznámka: V geografickém doplňku je pouze Česko, neboť nádrž se
> nachází ve dvou okresech: Písek a Příbram.*
>
> G301: ***Šance** (Staré Hamry, Frýdek-Místek, Česko : vodní nádrž)*
>
> VAR: *vodní nádrž Šance*; *přehrada Šance*
>
> G302: ***Brněnská přehrada** (Brno-město, Česko : vodní nádrž)*
>
> VAR: *Prýgl*; *Prygl*; *Prigl*; *Prígl*

##### Rybník

Obecný doplněk: rybník

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G303: ***Bohdanečský rybník** (Lázně Bohdaneč, Pardubice, Česko :
> rybník)*
>
> G304: ***Kreuzteich** (Rybáře, Karlovy Vary, Karlovy Vary, Česko :
> rybník : uváděno od 1842-uváděno do 1947), zaniklý rybník
> v katastrálním území Rybáře*
>
> VAR: *rybník Kreuzteich*; *zaniklý rybník Kreuzteich*
>
> G305: ***Máchovo jezero** (Doksy, Česká Lípa, Česko : rybník)*
>
> G306: ***Rožmberk** (Třeboň, Jindřichův Hradec, Česko : rybník)*
>
> VAR: *rybník Rožmberk*

##### Povodí

Obecný doplněk: povodí

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G307: ***Labe** (povodí)*
>
> VAR: *povodí Labe*; *labské povodí*
>
> G308: ***Odra** (povodí)*
>
> VAR: *povodí Odry*; *oderské povodí*

##### Řeka

Obecný doplněk: řeka

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: řeky se nedělí na části, jako například horní,
střední a dolní toky.

> Příklady:
>
> G309: ***Labe** (Česko a Německo : řeka)*
>
> VAR: *řeka Labe*; *Elbe* \[němčina\]
>
> G310: ***Morávka** (Frýdek-Místek, Česko : řeka)*
>
> VAR: *řeka Morávka*
>
> G311: ***Vltava** (Česko : řeka)*
>
> VAR: *řeka Vltava*
>
> G312: ***Dunaj** (Evropa : řeka)*
>
> VAR: *řeka Dunaj*; *Donau* \[němčina\]; *Duna* \[maďarština\];
> *Dunărea* \[rumunština\]

##### Potok

Obecný doplněk: potok

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G313: ***Bašnický potok** (Česko : potok)*
>
> *Poznámka: V geografickém doplňku pouze Česko, neboť potok protéká
> dvěma okresy: Hradec Králové a Jičín.*
>
> G314: ***Skaličník** (Frýdek-Místek, Česko : potok)*
>
> VAR: *potok Skaličník*
>
> G315: ***Židova strouha** (Česko : potok)*
>
> VAR: *potok Židova strouha*

##### Pramen

Obecný doplněk: pramen

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: prameny, tůně, studánky.

> Příklady:
>
> G316: ***Labe** (Špindlerův Mlýn, Trutnov, Česko : pramen)*
>
> VAR: *pramen Labe*
>
> vs.
>
> ***Labe** (Česko a Německo : řeka)*
>
> G317: ***V Hájku** (Lískovec, Frýdek-Místek, Frýdek-Místek, Česko :
> pramen)*
>
> VAR: *pramen V Hájku*
>
> G318: ***Vltava** (Kvilda, Prachatice, Česko : pramen)*
>
> VAR: *pramen Vltavy*
>
> vs.
>
> ***Vltava** (Česko : řeka)*

##### Vodopád

Obecný doplněk: vodopád

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklad:
>
> G319: ***Pančavský vodopád** (Špindlerův Mlýn, Trutnov, Česko :
> vodopád)*

##### Kanál

Obecný doplněk: kanál

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Kanály, náhony, přivaděče. Průplavy tvoří
samostatný typ geografického objektu.

> Příklady:
>
> G320: ***Baťův kanál** (Česko a Slovensko : kanál)*
>
> G321: ***Degárka** (Veselí nad Lužnicí, Tábor, Česko : kanál),
> spojovací kanál mezi Nežárkou a Lužnicí*
>
> VAR: *kanál Degárka*
>
> G322: ***Morávka - Žermanice** (Frýdek-Místek, Česko : kanál),
> přivaděč pro vodní nádrž Žermanice*
>
> VAR: *kanál Morávka - Žermanice*; *kanál Morávka - Žermanice*
>
> G323: ***Odlehčovaci rameno Dyje** (Břeclav, Břeclav, Česko : kanál)*
>
> G324: ***Přetokový kanál z Mlýnského potoka do Dyje** (Oleksovičky,
> Slup, Znojmo, Česko : kanál)*
>
> G325: ***Sopřečský kanál** (Břehy, Pardubice, Česko : kanál)*
>
> G326: ***Trojský kanál** (Troja, <span style="color:red;text-decoration:line-through">Praha, </span>Praha, Česko : kanál),
> sportoviště určené pro vodní slalom a rafting*

##### Průplav

Obecný doplněk: průplav

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G327: ***Bělomořsko-baltský kanál** (Rusko : průplav)*
>
> VAR: *Bělomořsko-baltský průplav*; *Belomorsko-Baltijskij kanal*
> \[ruština\]; Беломорско-Балтийский канал \[ruština\]
>
> G328: ***Korintský průplav** (Řecko : průplav)*
>
> VAR: *Diṓryga tīs Korínthou* \[řečtina\]; Διώρυγα της Κορίνθου
> \[řečtina\]
>
> G329: ***Panamský průplav** (Panama : průplav)*
>
> VAR: *canal de Panamá* \[španělština\]
>
> G330: ***Suezský průplav** (Egypt : průplav)*
>
> VAR: *Qanāt as-Suways* \[arabština\]; قناة السويس \[arabština\]

##### Peřej

Obecný doplněk: peřej

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: peřeje, katarakty.

> Příklady:
>
> G331: ***Otava, km 56,6 - peřej** (Strakonice, Strakonice, Česko :
> peřej), cvičná peřej*
>
> VAR: *peřej Otava*; *cvičná peřej Otava*
>
> G332: ***Stvořidla** (Havlíčkův Brod, Česko : peřej)*
>
> VAR: *peřej Stvořidla*
>
> G333: ***Nilské katarakty** (Egypt a Súdán : peřej)*
>
> VAR: *Nilské peřeje; Šalālāt an-*Nīl; شلالات النيل \[arabština\];
> *Cataracts of the Nile* \[angličtina\]

##### Jiná vodní plocha/tok

Obecný doplněk je potřeba specifikovat ručně.

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: Vše, co nelze v rámci podtřídy „vodstvo a vodní
plocha, vodní tok“ vyjádřit jiným konkrétním typem (např. delty).
Vodohospodářské stavby typu přehradní a rybniční hráze, zdymadla, jezy,
splavy, stavidla se evidují jako archivní autoritní záznamy entit třídy
„dílo/výtvor“.

> Příklady:
>
> G334: ***Dunaj** (Rumunsko a Ukrajina : delta)*
>
> VAR: *delta Dunaje*; *dunajská delta*
>
> vs.
>
> ***Dunaj** (Evropa : řeka)*
>
> G335: ***Mississippi** (Spojené státy americké : delta)*
>
> VAR: *delta Mississippi*
>
> vs.
>
> ***Mississippi** (Spojené státy americké : řeka)*

#### Podtřída „pojmenované útvary“

Geografický doplněk (obecné pravidlo pro celou podtřídu): část obce,
obec, okres, stát (v ČR, SR, Polsku, Německu, Maďarsku, Rakousku a na
Ukrajině) NEBO JEN část obce, obec, stát (mimo zmíněné státy a u obcí se
širší působností) NEBO JEN kontinent - používá se variabilně, tzn.
nejnižší úroveň tvoří vždy jméno entity, která popisovanou entitu plně
obsáhne.

##### Poušť

Obecný doplněk: poušť

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G336: ***Libyjská poušť** (Afrika : poušť)*
>
> VAR: *aṣ-Ṣaḥrāʾ al-Lībiya* \[arabština\]; الصحراء الليبية
> \[arabština\]
>
> G337: ***Negevská poušť** (Izrael : poušť)*
>
> VAR: *Negev*; *poušť Negev*
>
> G338: ***Sahara** (Afrika : poušť)*
>
> VAR: *saharská poušť*; *aṣ-Ṣaḥrāʾ*; الصحراء \[arabština\]; *aṣ-Ṣaḥrāʾ
> al-Kubrā* \[arabština\]; الصحراء الكبرى \[arabština\]

##### Oáza

Obecný doplněk: oáza

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklad:
>
> G339: ***Fajjúm** (Egypt : oáza)*
>
> VAR: *oáza Fajjúm*; <span dir="rtl">واحة الفيوم</span>
> \[arabština\]*‎; Waḥet El Fayyum* \[arabština\]

##### Les

Obecný doplněk: les

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G340: ***Koráb** (Příbram VI-Březové Hory, Příbram, Příbram, Česko :
> les)*
>
> VAR: *les Koráb*
>
> G341: ***Robotka** (Dubeč, Praha, Česko : les)*
>
> VAR: *les Robotka*

##### Prales

Obecný doplněk: prales

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

> Příklady:
>
> G342: ***Boubínský prales** (Prachatice, Česko : prales)*
>
> G343: ***Mionší** (Frýdek-Místek, Česko : prales)*
>
> VAR: *prales Mionší*

##### Skupina stromů

Obecný doplněk: skupina stromů

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: skupiny stromů, aleje.

> Příklady:
>
> G344: ***Platanová alej u pivovaru v Protivíně** (Protivín, Písek,
> Česko : skupina stromů)*
>
> G345: ***Skupina stromů na Šafářce** (Říčky v Orlických horách,
> Rychnov nad Kněžnou, Česko : skupina stromů)*

##### Strom

Obecný doplněk: strom

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: památné stromy.

> Příklady:
>
> G346: ***Czerninova douglaska** (Chudenice, Klatovy, Česko : strom)*
>
> G347: ***Klokočovská lípa** (Klokočov, Havlíčkův Brod, Česko : strom)*

##### Mokřad

Obecný doplněk: mokřad

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: rašeliniště, slatě, bažiny, močály.

> Příklady:
>
> G348: ***Jezerní slať** (Kvilda, Prachatice, Česko : mokřad)*
>
> G349: ***Rejvízské rašeliniště** (Rejvíz, Zlaté Hory, Jeseník, Česko :
> mokřad)*

##### Jiný pojmenovaný útvar

Obecný doplněk je potřeba specifikovat ručně

Geografický doplněk: viz výše obecné pravidlo pro celou podtřídu.

Doplňující vysvětlení: například pole a louky, které nejsou chráněným
územím.

> Příklad:
>
> G350: ***U Psárců** (Semice, Nymburk, Česko : pole)*
>
> VAR: *pole U Psárců*

#### Podtřída „pojmenované trvalé klimatické jevy“

##### Trvalý klimatický jev

Obecný doplněk: trvalý klimatický jev

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G351: ***El Niño** (trvalý klimatický jev)*
>
> G352: ***Jihovýchodní obchodní vítr** (trvalý klimatický jev)*

#### Podtřída „vesmír a jeho části“

##### Galaxie

Obecný doplněk: galaxie

Geografický doplněk: *neuvádí se*

> Příklad:
>
> G353: ***Mléčná dráha** (galaxie)*
>
> VAR: *galaxie Mléčná dráha*

##### Hvězda

Obecný doplněk: hvězda

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G354: ***Proxima Centauri** (hvězda)*
>
> G355: ***Slunce** (hvězda), centrum sluneční soustavy*

##### Jiná část vesmíru

Obecný doplněk je potřeba specifikovat ručně

Geografický doplněk je v případě části pojmenovaných vesmírných objektů
potřeba ručně upřesnit

Doplňující vysvětlení: komety, asteroidy, pojmenované útvary na
planetách apod.

> Příklad:
>
> G356: ***Olympus Mons** (Mars : hora), nejvyšší známá hora sluneční
> soustavy*
>
> VAR: *hora Olympus Mons*

##### Kráter

Obecný doplněk: kráter

Geografický doplněk: *neuvádí se*

> Příklad:
>
> G357: ***Tycho** (Měsíc : kráter)*
>
> VAR: *kráter Tycho*

##### Měsíc

Obecný doplněk: měsíc

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G358: ***Enceladus** (měsíc), měsíc planety Saturn*
>
> VAR: *měsíc Enceladus*
>
> G359: ***Europa** (měsíc), měsíc planety Jupiter*
>
> VAR: *měsíc Europa*
>
> G360: ***Měsíc** (měsíc), měsíc planety Země*

##### Planeta

Obecný doplněk: planeta

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G361: ***Mars** (planeta)*
>
> VAR: *planeta Mars*
>
> G362: ***Proxima Centauri b** (planeta), exoplaneta*
>
> VAR: *exoplaneta Proxima Centauri b*
>
> G363: ***Země** (planeta)*

##### Souhvězdí

Obecný doplněk: souhvězdí

Geografický doplněk: *neuvádí se*

> Příklady:
>
> G364: ***Kozoroh** (souhvězdí)*
>
> VAR: *souhvězdí Kozoroh*; *souhvězdí Kozoroha*
>
> G365: ***Velká medvědice** (souhvězdí), součástí je Velký vůz*
>
> VAR: *souhvězdí Velká medvědice*; *souhvězdí Velké medvědice*

#### Geografické objekty – hierarchie administrativního zařazení

Možnosti napojení geografických objektů v rámci administrativního
zařazení

**1. Kontinent/světadíl** lze napojit na: planeta, kontinent/světadíl.

**2. Nezaniklé entity v ČR a SR:**

**Stát** lze napojit na: kontinent/světadíl.

**Kraj** lze napojit na: stát.

**Okres** lze napojit na: kraj.

**Obec se širší působností** lze napojit na: stát, kraj.

**Obec** lze napojit na: okres.

**Vojenský újezd** lze napojit na: okres.

**Městskou část/obvod** lze napojit na: obec, obec se širší působností.

**Část obce** lze napojit na: obec, obec se širší působností.

**Katastrální území** lze napojit na: obec, obec se širší působností
nebo vojenský újezd.

**Ulici** lze napojit na: obec, obec se širší působností.

**Náměstí** lze napojit na: obec, obec se širší působností.

**Nábřeží** lze napojit na: obec, obec se širší působností.

**Nižší sídelní jednotku** lze napojit na: část obce, obec, obec se
širší působností, část obce nebo vojenský újezd.

**3. Nezaniklé entity mimo ČR a SR**

Skupina vnitřní část státu obsahuje následující typy geografických
objektů: kraj, okres, autonomní část státu, země, oblast, region,
kanton, okruh, župa, provincie, vojvodství, departement, hrabství, jiná
část státu

**Stát** lze napojit na: kontinent/světadíl, stát.

**Vnitřní část státu (skupina)** lze napojit na: stát, vnitřní část
státu (skupina)

**Obec** lze napojit na: stát *(pouze při uvedení souřadnic)*, vnitřní
část státu (skupina).

**Obec se širší působností** lze napojit na: stát, vnitřní část státu
(skupina).

**Nižší sídelní jednotku** lze napojit na: stát *(pouze při uvedení
souřadnic)*, vnitřní část státu (skupina), obec, obec se širší
působností, část obce.

**Městskou část/obvod** lze napojit na: obec, obec se širší působností.

**Část obce** lze napojit na: obec, obec se širší působností.

**Ulici** lze napojit na: obec, obec se širší působností.

**Náměstí** lze napojit na: obec, obec se širší působností.

**Nábřeží** lze napojit na: obec, obec se širší působností.
