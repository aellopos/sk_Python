# Samostatné cvičení

## Cvičení - základy 
---
## 1 - Jednoduchý výstup
Náš vůbec první program nebude dělat nic víc, než vypisovat text na obrazovku.

Založte si program **vstup-vystup.py**. V tomto programu pomocí funkce print() vypište na obrazovku Divadlo Pěst na oko. Program spusťte na konzoli a vyzkoušejte, že dělá co má.

Upravte tento program tak, že do proměnné nazev uložíte název nějakého divadelního představení a do proměnné cas uložte čas konání tohoto představení. Nyní pomocí funkce print() nechte program vypsat na obrazovku na jeden řádek název představení a čas konání, např. Zkrocení zlé ženy - 19:30.

Upravte dále program tak, že do proměnné hodina uložíte hodinu konání představení (jako celé číslo) a do proměnné minuta minutu konání, také jako celé číslo. Zařiďte, aby výstup programu vypadal takto: Zkrocení zlé ženy - 19:30.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 2 - Házení kostkami
Napište program **kostky.py**, který bude simulovat hod dvěma klasickými šestistěnnými kostkami. Jeho výstupu bude součet bodů na těchto dvou kostkách.

Nápověda:

- Generování náhodných čísel dělá funkce random.randint().
- Pokud chcete ve vašem programu použít modul random, musíte na jeho úplném začátku napsat příkaz import random

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 3 - Generátor čísel
Napište program **generator.py**, kde zadáte dolní mez a horní mez do proměnné - a vypíše na výstup náhodné číslo v zadaných mezích.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 4 - Jednoduchý vstup
Teď už budeme chtít, aby náš program dokázal získat vstup od uživatele.

Napište program **jmeno.py**, který získá jméno a příjmení od uživatele voláním funkce input(). Vypište je na obrazovku podobně jako v předchozím cvičení.
Nechte uživatele zadat také věk. Pozor na to, že funkce input() vždy vrací řetězec, ale my chceme v proměnné vek mít číslo. Použijte tedy funkci int(), abyste převedli uživatelem zadaný řetězec na číslo. Opět vypište na obrazovku jméno, příjmení a věk tak jako v předchozí verzi.

<details>
<summary><b>Řešení</b></summary>


```Python
Tady zatím nic není :)
```



</details>

## Cvičení - podmínky 
---

## 1 - Jednoduché podmínky
Založte si program **prihlaseni.py**. V tomto nechte uživatele zadat svoje uživatelské jméno a poté heslo. Pokud se heslo neshoduje s heslem simsalabim, vypište na výstup **Vstup nepovolen** a zavolejte funkci exit(), aby uživatel neznalý hesla nemohl s programem dál pracovat.

Na konec programu vlož příkaz, který se uživatele zeptá na věk. Pokud je uživatel starší 18 let, vypište na výstup **Smíš vstoupit** Pokud je mladší, vypiš **Vstup povolen od 18 let**

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 2 - Cena vstupenky

Vytvořte program **vstupenky01.py**, vytvořte si proměnnou plnaCena, do které uložte hodnotu 12.
Vytvořte podmínku, která do proměnné cena uloží cenu spočítanou podle věku uživatele dle následujících pravidel
- 0 euro pro návštěvníky mladší 6 let,
- 65% ze základní ceny pro návštěvníky 6 až 26 let (žák, student),
- 100% ze základní ceny pro návštěvníky 27 až 64 let (dospělý),
- 50% ze základní ceny pro ostatní (senior).
Nezapomeňte na zaokrouhlování, ať nám cena vyjde v celých centech. (využijte funkci round())

Nakonec spočtenou cenu vypište s nějakou hezkou zprávou na výstup.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 3 - Registrace

Založte si program **registrace.py**. Program nechá uživatele, aby si zvolil uživatelské jméno a heslo. Heslo jej nechejte zadat dvakrát a ověřte, že jej uživatel zadal dvakrát stejně. V opačném případě vypište varování, že hesla nejsou stejná. Při prvním zadávání ověřte, že heslo je bezpečné, což v tomto případě znamená, že je delší než 8 znaků (využijte funkci len()).

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## Cvičení - sekvenční hodnoty
---

## 1 - Řetězce jako sekvence
Vytvořte nový program **jmeno.py**. Do proměnné jmeno uložte svoje celé jméno a nechte vypsat jeho třetí, pátý a sedmý znak. Vyzkoušejte, co se stane, když budete chtít znak na pozici, která překračuje délku řetězce.

<details>
<summary><b>Řešení</b></summary>

```Python
jmeno = "František Novák"

print(f"Třetí znak: {jmeno[2]}")  # 'a'
print(f"Pátý znak: {jmeno[4]}")  # 't'
print(f"Sedmý znak: {jmeno[6]}")  # 'š'

```


</details>

## 2 - Seznamy
Vytvořte nový program **seznam.py**. V tomto programu vytvořte následující:
- Vytvořte nějaký seznam celých čísel, například počty diváků na několika po sobě jdoucích představeních.
- Vytvořte nějaký seznam desetinných čísel, například zaplněnost divadla v několika po sobě jdoucích představeních.
- Vytvořte nějaký seznam řetězců, například seznam názvů několika divadelních představení, která divadlo hraje. Uložte tento   seznam do proměnné hry. Uložte do nějaké proměnné druhou položku tohoto seznamu.
- Do proměnné hodnoceni uložte seznam hodnocení, které obdržela divadelní hra "Plyšáci na útěku" v různých recenzních časopisech. Hodnocení je vždy dvouprvkový seznam obsahující název recenzního časopisu jako řetězec a samotné hodnocení jako číslo mezi 1 až 10

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 3 - Ověřování hesla
Založte si program **heslo.py**. Ověřování hesla se někdy dělá tak, že se vás systém ptá pouze na některé jeho znaky. Napište program, který má uloženo heslo, které musí uživatel zadat. Pak se jej postupně zeptejte například na druhý, pátý a sedmý znak hesla. Propusťte uživatele pouze tehdy, zadá-li všechny tyto znaky správně.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## Cvičení - cykly 
---

## 1 - Seznam hodnocení

Mějme seznam hodnocení divadelní hry Plyšáci na útěku , který vypadá takto: 

```python
hodnoceni = [7, 9, 6, 7, 9, 8]
```

- Vytvořte program, který projde tento seznam a vypíše každé hodnocení na nový řádek.
- Upravte program tak, aby vypisoval výstup v tomto formátu

```python
7/10
9/10
6/10
7/10
9/10
8/10
```

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 2 - Procházení seznamu
Založte si program **hesla.py** a na jeho začátek vložte následující kód obsahující seznam hesel pro přihlášení do nějakého systému

```python
hesla = [
    "xyz101",
    "punťa",
    "razor-blade",
    "1234",
    "12011986",
    "martin111",
    "trhnisi",
    "hokuspokus",
    "jeník15",
    "kristus-te-spasi",
    "beruška",
    "strčprstskrzkrk",
]
```

- Pomocí cyklu vypište všechny hesla na obrazovku, každé na jeden řádek.
- Upravte váš program tak, aby vypisoval jen bezpečná hesla, tedy taková, jež jsou delší než 8 znaků.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 3 - Složitější seznam
Založte si program **cykly02.py** a použijte v něm následující seznam měsíců v roce, Všimněte si, že je to seznam seznamů.

```python
mesice = [
    ["leden", 31],
    ["únor", 28],
    ["březen", 31],
    ["duben", 30],
    ["květen", 31],
    ["červen", 30],
    ["červenec", 31],
    ["srpen", 31],
    ["září", 30],
    ["říjen", 31],
    ["listopad", 30],
    ["prosinec", 31],
]
```

- Pomocí cyklu projděte tento seznam a vypište na výstup názvy jednotlivých měsíců.
- Pomocí dalšího cyklu vypište na výstup počty dní v jednotlivých měsících.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 4 - Průměr
Napište cyklus, který projde zadaný seznam desetinných čísel a spočítá jejich průměr. Seznam čísel si vytvořte na začátku programu.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 5 - Hry
Následující seznam obsahuje seznam všech divadelních her, které se hrají v divadle Pěst na oko. Každá hra má svůj název a trvání v minutách.

```python
hry = [
    ["Ňadro na ňadru na nádru", 180],
    ["Útok plyšových krokodýlů", 95],
    ["Cesta do říše zelí", 128],
    ["Romance na zdymadle", 144],
    ["Zátiší s mimozemšťanem", 135],
    ["Čtyři facky a dortík", 100],
    ["Motorová okurka", 165],
    ["Johnny Noir", 140],
    ["Pražská kavárna vrací úder", 130],
    ["Pět sester ve vratech", 111],
    ["Stařec a krajta", 187],
    ["Růžová nemoc", 210],
    ["Smrt v přímém přenosu", 265],
]
```

- Pomocí cyklu projděte tento seznam a vypište na výstup názvy všech her.
- Vypište na výstup názvy všech her, které trvají více než 120 minut.
- Vypište na výstup názvy všech her spolu s jejich trváním v hodinách a minutách.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## Cvičení - funkce 
---

## 1 - Násobení
Napiš funkci mult, která bude mít dva číselné parametry. Funkce oba parametry vynásobí a vrátí výsledek.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 2 - Hotel
Napiš funkci total_price, která vypočte cenu noci v hotelu. Funkce bude mít dva parametry - persons a breakfast. Cena za noc za osobu je 850 Kč a cena za snídani za osobu je 125 Kč. Funkce vrátí výslednou cenu. Parametr breakfast je nepovinný a výchozí hodnota je False.

Funkci vyzkoušej se zadáním dvou i jedné hodnoty, např. total_price(3), total_price(2, True).

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 3 - Faktoriál
Vytvoř program, který obsahuje funkci pro výpočet libovolného faktoriál. (https://cs.wikipedia.org/wiki/Faktori%C3%A1l) 

Využij funkci z matematického modulu.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>

## 4 - Rámeček
Napiš funkci, která jako parametr převezme řetězec a vytiskne jej obalen hvězdičkami.

```
Zadej slovo: ahoj
********
* ahoj *
********
```

Nápověda: 8 * '*' == '********'

Bonus: Znak, kterým se má text obalit, bude zadán také jako parametr.

<details>
<summary><b>Řešení</b></summary>

```Python
Tady zatím nic není :)
```

</details>