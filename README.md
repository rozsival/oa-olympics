# SŠ Olympiáda na OA TGM - Tvorba webu

Zadání úloh pro účastníky **Olympiády ve tvorbě webu** na OA TGM dne **23.3.2018**.

Pro vypracování jednotlivých úloh použij IDE nebo editor dle vlastního uvážení. Dbej však na základní přehlednost a čitelnost kódu, indentaci apod.

Časový limit na vypracování je **4 hodiny**.
Během práce můžeš používat Google, StackOverflow apod. **bez omezení**.

**Důležitá je kvalita, nikoliv rychlost vypracování!**
Nepoužívej v kódu Češtinu, díky!

## Úloha č. 1

Vytvoř jednoduchou stránku s HTML5 layoutem. Stránka bude obsahovat:

* záhlaví s libovolným názvem stránky
* obsah s libovolným textem (pro vygenerování odstavců můžeš použít [tento generátor](https://cs.lipsum.com/)).
* zápatí s copyrightem

Stránka bude mít nastavený `title`. V obsahu bude hlavní nadpis a dále:

* alespoň dva odstavce textu za sebou
* alespoň jeden podnadpis a přidružený odstavec textu
* alespoň jeden nečíslovaný seznam
* alespoň jeden odkaz na libovlný web
* alespoň jedna tabulka s libovolnými daty

**Použij sémanticky správné tagy pro vytvoření a strukturování obsahu.**

## Úloha č. 2

Stránce, kterou jsi vytvořil v rámci předchozí úlohy, přiřaď následující styly:

* celá stránka bude horizontálně vycentrovaná
* záhlaví a zápatí budou mít libovolnou barvu pozadí a k tomu kontrastní barvu textu
* název stránky v záhlaví bude vycentrovaný vertikálně i horizontálně
* hlavní nadpis obsahu bude mít velikost `36px`, výšku řádku o polovinu vyšší, řez `bold`
* podnapisy budou o `10px` menší, než hlavní nadpis, řez stejný, řádkování taktéž o polvinu větší, než je velikost textu
* hlavní text bude mít velikost `16px`, výšku řádku `24px`, řez `normal`
* odstavec textu bude od nadpisu odsazen vždy o `24px`, mezi sebou však odstavce budou odsazeny jen o `14px`
* seznam bude zalamovat obsah uvnitř odrážky a styl bude mít stejný jako odstavec
* odkazy budou mít libovolnou barvu, která se po najetí myšší změní na jinou libovolnou barvu
* tabulka bude mít rámečky pouze mezi jednotlivými řádky, nikoliv po stranách, její záhlaví bude mít libovolné pozadí a tučný text s kontrastní barvou, každý sudý řádek bude mít libovolou barvu pozadí, obsah bude zarovnaný vlevo

**Všechny texty v obsahu budou zarovnány vlevo.**

## Úloha č. 3

V rámci již hotové stránky vytvoř novou podstránku, která použije již vytvořený layout. Místo textového obsahu však bude jednoduchá galerie libovolných obrázků.

Obrázky budou řazeny dlaždicově vedle sebe, vždy 3 obrázky v jednom řádku. Budou mít stejné rozměry. Při najetí na obrázek se kolem něj zobrazí libovolný rámeček. Udělej ho však tak, aby nerozšiřoval prostor, který obrázek zabírá a aby neodskakovaly okolní obrázky. Po kliknutí na obrázek se v novém okně otevře zdrojový odkaz obrázku.

**Při vypracování úlohy neřeš vytváření miniatur ani optimalizaci obrázků. Používej rovnou zdroj.**

Do záhlaví stránky přidej pod hlavní název jednoduchou **navigaci**, která bude obsahovat odkaz na právě vytvořenou podstránku a také odkaz na hlavní stránku s textovým obsahem z první úlohy. Styl navigace je čistě na tobě.

**Stránku pojmenuj Galerie, nezapomeň nastavit správný `title`.**

## Úloha č. 4

Vytvoř další podstránku, podobně jako v předchozí úloze. Stránka bude tentokrát obsahovat jednoduchý kontaktní formulář. Formulář bude mít tyto náležitosti:

* jméno (povinné pole)
* e-mail (povinné pole)
* důvod kontaktování (`select` s libovolnými důvody)
* zpráva

Za pomoci JavaScriptu zvaliduj, že jsou vyplněna povinná pole a že text v poli pro e-mail je skutečně e-mailová adresa. Při jakékoliv chybě vyvolej `alert` s hláškou, která popíše uživateli daný problém. Pokud je formulář validní, zajisti, aby se při jeho odeslání stalo následující:

* stránka se neobnoví
* pole formuláře budou vyprázdněná do původního stavu
* zadané hodnoty se vypíšou do konzole prohlížeče, pokud uživatel nevyplnil zprávu, nastav její fallback hodnotu na `Kontaktujte mě prosím.`
* uživateli se zobrazí `alert` s informací o odeslání formuláře

**Stránku pojmenuj Kontakt a přidej ji do hlavní navigace.**

## Úloha č. 5

Pokus se vytvořené stránky upravit tak, aby byly responzivní, a to především takto:

* položky v navigaci budou na mobilu pod sebou, na desktopu vedle sebe
* obrázky v galerii budou na mobilu pod sebou, na desktopu dle původního zadání
* kontaktní formulář bude mít na mobilu vždy `label` a pod ním `input` využívající plnou dostupnou šířku, na desktopu budou `label` a `input` vedle sebe, labely budou vzájmně zarovnány, aby byla vždy mezera mezi labelem a inputem stejná
* submit tlačítko formuláře bude na mobilu na celou šířku, na desktopu jen na šířku jeho popisku + nějaké rozumné odsazení od stran

**Pro simulaci zařízení používej [Chrome DevTools](https://developer.chrome.com/devtools).**
