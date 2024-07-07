Jak vypočítat DPH a nesplést se
===============================

09/11/2015

**Prosím pozor, článek jsme aktualizovali na rok 2019. Najdete jej zde:  [Jak vypočítat DPH a nesplést se (od roku 2019)](http://zakk.cz/jak-vypocitat-dph-a-nesplest-se-2019/)**

Na první pohled jednoduché zadání, zmást ale může kdekoho. Debata se známým, který nedávno padl do podobné pasti mě inspirovala k tomuto článku. Zkuste si představit: Připravujete účet a v něm potřebujete rozepsat položky. Ke každé doplnit cenu bez daně, částku která zodpovídá DPH a cenu s daní. Máte ale jenom podklady kde jsou ceny položek již s DPH:  

cena bez DPH

částka DPH

sazba DPH

cena s DPH

Položka 1

?

?

21%

605 Kč

Položka 2

…

…

…

…

Položka 3

…

…

…

…

A tak se pustíte vypočítat cenu bez daně (základ daně) a daň (částku DPH). Vezmete celkovou cenu, vypočítáte z ní 21% a napíšete do kolonky částka DPH. Zbytek z celkové ceny pokládáte za základ daně. To bylo jednoduché, no ne? Ano. A taky nesprávně. Než si vysvětlíme proč, zapišme si, co jsme právě počítali:

Cena s DPH \* 0,21 =  částka DPH ?
 605 \* 0,21 = 127.05

Cena s DPH - částka DPH = cena bez DPH (základ daně)
 605 - 127.05 = 477,95

#### **Problém**

Problém je v tom, že cena z které vychází tento příklad již daň obsahuje. Je to tedy základ daně (oněch původních 100%) a k ní připočteno 21% daně. Místo toho s ní pracuje jako kdyby to bylo jenom původních 100%.

Nevěříte? Zkuste to zpětně zkontrolovat. Z ceny bez DPH budeme počítat cenu s DPH:

477,95 \* 1,21 = 578,3195 Kč.

#### **Řešení**

Co potřebujete, je nejdřív zjistit cenu bez DPH (základ daně), a pak z ní teprve počítat částku DPH. Třeba takhle:

Cena s DPH / 1,21 = základ daně
 605 / 1,21 = 500

Základ daně \* sazba DPH = částka DPH
 500 \* 0,21 = 105

Pro kontrolu: 500 + 105 = 605 Kč

#### **Méně přesný způsob dle zákona o DPH**

Zákon o DPH k tomu navíc nabízí alternativu pro výpočty u tzv. zjednodušeného daňového dokladu [1](#note-1377-1 "Zákon č. 235/2004 Sb., o dani z přidané hodnoty, §37 odst. 2 říká:
"Daň může plátce rovněž vypočítat z úplaty za zdanitelné plnění, která je včetně daně, nebo z částky stanovené podle § 36 odst. 6, která je včetně daně, a koeficientu, který se vypočítá jako podíl, v jehož čitateli je číslo 21 v případě základní sazby daně nebo číslo 15 v případě první snížené sazby daně nebo číslo 10 v případě druhé snížené sazby daně a ve jmenovateli součet údaje v čitateli a čísla 100, vypočtený koeficient se zaokrouhlí na čtyři desetinná místa, vypočtená daň se může zaokrouhlit podle odstavce 1. Cena bez daně se pro účely tohoto zákona dopočte jako rozdíl částky za zdanitelné plnění obsahující daň a vypočtené daně po případném zaokrouhlení.""). Ten můžete vystavit, pokud je plnění včetně daně do 10.000 Kč. Používá k výpočtu koeficient. Metoda se nehodí na výpočty větších částek, protože pak dochází k výrazné odchylce od správného výsledku.

Koeficienty jsou:

1/1,10 = 0,9091 (pro 10% DPH)
 1/1,15 = 0,8696 (pro 15% DPH)
 1/1,21 = 0,8264 (pro 21% DPH)

Tedy výše uvedený případ můžeme počítat jako:

Cena s DPH \* koeficient = základ daně
 605 \* 0,8264 = 499,972

Jak vidíte, již zde se projevuje nepřesnost této metody výpočtu.

#### **Výpočet daně dle zákona o DPH**

Mimochodem, Zákon o DPH [2](#note-1377-2 "Zákon č. 235/2004 Sb., o dani z přidané hodnoty, §37 odst. 1") pamatuje i na zaokrouhlování, když ze základu počítáte daň. Myslete na to při svých výpočtech:

"Vypočtená daň se může zaokrouhlit na celé koruny způsobem, že částka 0,50 Kč a vyšší se zaokrouhlí na celou korunu nahoru a částka nižší než 0,50 Kč se zaokrouhlí na celou korunu dolů. "

#### **O sazbě daně**

V době kdy píšu tenhle článek je základní sazba DPH 21%. S ní pracuj i v textu. Mimo ní existují í snížené sazby: 15% a 10%. Pro ně budete muset vzorec upravit. Sazby se můžou časem měnit. Aktuální můžete dohledat třeba v Zákonu o DPH v paragrafu §47 přes portál veřejné správy [3](#note-1377-3 "https://portal.gov.cz/app/zakony/zakon.jsp?page=0&nr=235~2F2004&rpp=15#seznam"). Hodně zdaru!

Poznámky:

1.  Zákon č. 235/2004 Sb., o dani z přidané hodnoty, §37 odst. 2 říká:
    
    "Daň může plátce rovněž vypočítat z úplaty za zdanitelné plnění, která je včetně daně, nebo z částky stanovené podle § 36 odst. 6, která je včetně daně, a koeficientu, který se vypočítá jako podíl, v jehož čitateli je číslo 21 v případě základní sazby daně nebo číslo 15 v případě první snížené sazby daně nebo číslo 10 v případě druhé snížené sazby daně a ve jmenovateli součet údaje v čitateli a čísla 100, vypočtený koeficient se zaokrouhlí na čtyři desetinná místa, vypočtená daň se může zaokrouhlit podle odstavce 1. Cena bez daně se pro účely tohoto zákona dopočte jako rozdíl částky za zdanitelné plnění obsahující daň a vypočtené daně po případném zaokrouhlení." [↩](#return-note-1377-1)
    
2.  Zákon č. 235/2004 Sb., o dani z přidané hodnoty, §37 odst. 1 [↩](#return-note-1377-2)
3.  [https://portal.gov.cz/app/zakony/zakon.jsp?page=0&nr=235~2F2004&rpp=15#seznam](https://portal.gov.cz/app/zakony/zakon.jsp?page=0&nr=235~2F2004&rpp=15#seznam) [↩](#return-note-1377-3)
