---
layout: post
title:  "Jak vypočítat DPH a nesplést se (od roku 2019)"
date:   2019-04-28 12:00:00 +0200
categories: 
---

Zkuste si představit: Připravujete účet a v něm potřebujete rozepsat položky. Ke každé doplnit cenu bez daně, částku která zodpovídá DPH a cenu s daní. Máte ale jenom podklady kde jsou ceny položek již s DPH.

Na první pohled jednoduché zadání, zmást ale může kdekoho. Debata se známým, který padl do podobné pasti mě inspirovala k tomuto článku.

#### **Problém**

Zde je názorná ukážka jak takové zadání může vypadat:

|           | cena bez DPH | částka DPH | sazba DPH | cena s DPH |
|-----------|--------------|------------|-----------|------------|
| Položka 1 | ?            | ?          | 21%       | 605 Kč     |
| Položka 2 | …            | …          | …         | …          |
| Položka 3 | …            | …          | …         | …          |

A tak se pustíte vypočítat cenu bez daně (základ daně) a daň (částku DPH). Vezmete celkovou cenu, vypočítáte z ní 21% a napíšete do kolonky částka DPH. Zbytek z celkové ceny pokládáte za základ daně. To bylo jednoduché, no ne? Ano, je. ale je to taky **nesprávně**. Než si vysvětlíme proč, zapišme si, co jsme právě počítali:

Cena s DPH \* 0,21 =  částka DPH ?
 605 \* 0,21 = 127.05

Cena s DPH - částka DPH = cena bez DPH (základ daně)
 605 - 127.05 = 477,95

#### Proč je to nesprávně?

Tento postup má dva problémy. Prvním z nich je, že je to matematicky nesprávný postup výpočtu základu DPH. Druhým problémem je, že pokud DPH počítáte, nejspíš tak činíte kvůli tomu že Vám to nařizuje zákon. A ten navíc předepisuje specifický způsob jak DPH počítat. Budeme se jim tedy věnovat jeden po druhém.

#### Výpočet základu daně

Jak tedy matematicky vypočítat základ daně když známe procentní sazbu a výslední sumu s DPH?

Problém výše uvedeného postupu je v tom, že cena z které vychází tento příklad již daň obsahuje. Je to tedy základ daně (oněch původních 100%) a k ní je již připočteno 21% daně. Místo toho s ní ale v prvním příkladu pracujeme jako kdyby to bylo jenom původních 100%.

Nevěříte? Zkuste to zpětně zkontrolovat. Z ceny bez DPH budeme počítat cenu s DPH:

477,95 \* 1,21 = 578,3195 Kč.

Co ale potřebujeme, je nejdřív zjistit cenu bez DPH (základ daně), a pak z ní teprve počítat částku DPH. Třeba takto:

Cena s DPH / 1,21 = základ daně
 605 / 1,21 = 500

Základ daně \* sazba DPH = částka DPH
 500 \* 0,21 = 105

Pro kontrolu:

500 + 105 = 605 Kč

DPH je daň která je určena procentem ze základu daně a tento postup platí pro každý výpočet ze základu u kterého známe procentní sazbu a výslední sumu.

#### **Způsob dle zákona o DPH (od roku 2019)**

Zákon o DPH [1](#note-2011-1 "https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty") navíc předepisuje, jak přesně základ daně počítat. Mimochodem, v roce 2019 došlo k jeho novelizaci. Novela určila nový způsob výpočtu DPH k 1. 4. 2019 a stanovila přechodné šestiměsíčíní období počas kterého můžete ještě používat i [starý způsob výpočtu](http://zakk.cz/jak-vypocitam-zaklad-dane/). Nově se tedy DPH počítá takto:

Cena s DPH / koeficient = částka DPH

Pro DPH ve výši 21% tak určíme výši daně takto:

605 - (605 / 1.21) = 105 Kč

Z toho pak získáme základ daně:

Základ DPH = Cena s DPH - částka DPH
605 - 105 = 500 Kč

#### **O sazbě daně**

V článku pracujeme se sazbou daně DPH 21%. Mimo ní existují í snížené sazby: 15% a 10%. Zákon pro ně používá koeficienty 1.15 a 1.10 pro snížené sazby daně. Pro ně budete muset vzorec upravit.

Sazby se můžou časem měnit. Aktuální sazby můžete dohledat třeba v Zákonu o DPH v paragrafu §47 [2](#note-2011-2 "https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty?vtextu=%C2%A7%2047&timeslice=null#lema3"). Hodně zdaru!

Poznámky:

1.  [https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty](https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty) [↩](#return-note-2011-1)
2.  [https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty?vtextu=%C2%A7%2047&timeslice=null#lema3](https://www.noveaspi.cz/products/lawText/1/57849/1/2/zakon-c-235-2004-sb-o-dani-z-pridane-hodnoty?vtextu=%C2%A7%2047&timeslice=null#lema3) [↩](#return-note-2011-2)

