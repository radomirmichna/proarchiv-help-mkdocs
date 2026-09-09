# Systém nápověd ProArchiv

Systém nápověd je řešen v prostředí MkDocs. Samostatné zdrojové soubory nápověd se zapisují ve formátu markdown. Existuje mnoho editorů, které umí s tímto formátem pracovat, např. Typora.

## MkDocs
(https://www.mkdocs.org/).

Instalace ve Windows: MkDocs vyžaduje Python. Viz https://www.mkdocs.org/#installation

MkDocs funguje tak, že soubory, editované ve formátu markdown, se online zobrazují dle zvolené šablony jako html/webové stránky. Jako statické html se taktéž výsledně exportují a nahrávají do zvoleného adresáře na server s aplikací ProArchiv. Navíc při tom probíhá indexace obsahu a výsledný web je poměrně dobře prohledávatelný bez nutnosti použití databáze.

### Zjištění aktuální verze

```
mkdocs --version
```

### Upgrade verze

```
pip install -U mkdocs
```

## Material for MkDocs

ProArchiv využívá v MkDocs šablonu Material (https://squidfunk.github.io/mkdocs-material/) kvůli velkému množství užitečných rozšíření.

<ins>Nastavení:</ins>
Určuje ho obsah souboru mkdocs.yml:

https://www.mkdocs.org/#getting-started
https://squidfunk.github.io/mkdocs-material/getting-started/#full-example

### Zjištění aktuální verze

```
pip show mkdocs-material
```

### Upgrade verze

```
pip install --upgrade mkdocs-material
```

## Typora

Pro editaci zdrojových souborů (.md) je vhodný editor Typora (https://typora.io/).
Pozor! Stable verze je nyní placená; dev/beta verze jsou stále free.

Vše stačí nainstalovat a poprvé nastavit a pak se jen edituje text, provede export do html, html nahrajete do domluveného adresáře někam na server a je to.

## Postup běžné práce při aktualizaci nápovědy:

1. Spustit MkDocs v režimu serve – mám vytvořený spustitelný script s příkazem:
```
start mkdocs serve 
/wait
```
2. Poté lze aktivovat aktuální náhled ve webovém prohlížeči na adrese http://localhost:8000/
3. Otevřít dokument nápovědy ve formátu .md v programu Typora
4. Po meziuložení změn lze provádět kontrolu vzhledu v webovém prohlížeči na výše zmíněné adrese
5. Pro vyexportování výsledku editace je potřeba spustit příkaz build – mám vytvořený spustitelný script s příkazem:
```
start mkdocs build
/wait
```
6. Výsledek se uloží do adresáře site v domovské složce projektu
7. Pro online publikaci na serveru s aplikací ProArchiv je jej tam potřeba přenést. Umístění nápovědy je definováno v /home/proarchiv/etc/proarchiv.properties
```
# COMMONS
app.help=https://proarchiv.archives.cz/proarchiv-help
```
8. Pro přenos vyexportované nápovědy lze využít třeba WinSCP.
<ins>Možné řešení:</ins> uživatel, který je za tvorbu nápověd zodpovědný, má zřízený účet na serveru ProArchiv. Zde má ve svém domovském adresáři /home/usersname zřízen adresář /proarchiv-help. Do něj má zápis a sem nahraje (zaktualizuje) pomocí WinSCP soubory nápověd. Tento adresář je pomocí symlinku automaticky směřován do /usr/local/tomcat/webapps/proarchiv-help, odkud je nápověda skutečně spouštěna (závisí na konfiguraci tomcatu).
Konkrétní možné řešení dle vzoru ZAO

Je možno používat komplexní soubor nápověd používaný v ZAO. Za jeho obsah (adresář docs) je zodpovědný administrátor ZAO Radomír Michna.

Obsah adresáře docs pro využití v klientských instalacích ProArchiv:

* <span style="color:red">interni_metodika\attachments\ – obsahuje přílohy pro klientskou část (metodika_zao.md)</span>
* <span style="color:red">interni_metodika\img\ – obsahuje obrázky pro klientskou část (metodika_zao.md)</span>
* <span style="color:red">interni_metodika\metodika_zao.md – zdrojový soubor klientskou část, konkrétně Metodická kuchařka pro popis archiválií v Zemském archivu v Opavě</span>
* metodika\attachments\ – obsahuje přílohy pro společnou část, konkrétně celostátní metodiku
* metodika\metodika.md – zdrojový soubor společné části, konkrétně pro popis celostátní metodiky
* proarchiv\attachments\ – obsahuje přílohy pro společnou část, konkrétně manuály / uživatelské příručky k aplikaci ProArchiv17
* proarchiv\img\ – obsahuje obrázky pro společnou část, konkrétně manuály / uživatelské příručky k aplikaci ProArchiv17
* proarchiv\index.md – zdrojový soubor společné části, konkrétně pro manuály / uživatelské příručky k aplikaci ProArchiv17 – základní info
* proarchiv\manual_modul_ap.md – zdrojový soubor společné části, konkrétně pro manuály / uživatelské příručky k aplikaci ProArchiv17 – manuál k modulu pro správu přístupových bodů – prozatím ve výstavbě, připraveno pro spuštění chystaného modulu
* proarchiv\manual_proarchiv.md – zdrojový soubor společné části, konkrétně pro manuály / uživatelské příručky k aplikaci ProArchiv17 – manuál k pořádací aplikaci
* stylesheets\ – společné, obsahuje stylovací soubory css
* zp\attachments\ – obsahuje přílohy pro společnou část, konkrétně základní pravidla
* zp\img\– obsahuje obrázky pro společnou část, konkrétně základní pravidla
* zp\index.md a zp_hlavni_text-xy.md – zdrojový soubor společné části, konkrétně pro základní pravidla
* <span style="color:red">index.md</span> – zdrojový soubor společné části, konkrétně pro vstupní informační stránku. Zde je třeba upravit obsah a odkaz zmiňující klientskou část (Metodickou kuchařku ZAO).
* <span style="color:red">Červené části si nahraďte za vlastní</span>, zbylé můžeme považovat za společné. Jsou upraveny tak, aby obsahovaly jen obecné informace.

Jakmile dojde v ZAO k aktualizacím společných částí, budou sdíleny zde.
