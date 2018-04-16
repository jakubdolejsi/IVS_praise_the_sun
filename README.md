# Matematická kalkulačka s knihovnou 
Projekt byl vytvořen skupinou lidí, kteří si říkají **Praise the sun**. Společnými silami vytvořili grafickou kalkulačku, která je propojená s jejich vlasntě vyrobenou matematickou knihovnou. V dalších kategoriích se dočtete více o projektu. 

## K čemu slouží kalkulačka?
Kalkulačka (dříve též počítačka) je typicky přenosné elektronické zařízení pro provádění výpočtů od jednoduchých aritmetických až po velmi složité matematické operace. Název kalkulačka pochází ze starověkého Řecka a Říma, kde se pro výpočty používala dřevěná nebo hliněná destička **[abakus](https://cs.wikipedia.org/wiki/Po%C4%8D%C3%ADtadlo)**, do které se vkládaly kamínky.

## Programování
Matematická knihovna je naprogramovaná v jazyce [Java](https://cs.wikipedia.org/wiki/JavaFX). Grafické zobrazení kalkulačky je provedeno za pomocí [JavaFX Scene Builder 1.1](http://www.oracle.com/technetwork/java/javafxscenebuilder-1x-archive-2199384.html), které bylo editováno v [JavaFX - NetBeans](https://netbeans.org/features/java-on-client/javafx.html). Profiler, který sleduje zatížení HW - [Profiler - NetBeans](https://profiler.netbeans.org/). 

## Instalace 
Zde bude postup, jak instalovat kalkulačku.

## API 
API (zkratka pro Application Programming Interface) označuje v informatice rozhraní pro programování aplikací. Jde o sbírku procedur, funkcí, tříd či protokolů nějaké knihovny, které může programátor využívat. API určuje, jakým způsobem jsou funkce knihovny volány ze zdrojového kódu programu.

### Příklad: 

**SYNTAXE** <br />
      #include &lt;MathLib.java&gt; <br />
      scitani (double **cislo1**, double **cislo2**); <br />
      faktorial (dlouble **cislo**); <br />
      ... <br />
      
**POPIS** <br />
      Funkce scitani() sečte **cislo1** a **cislo2** <br />
      Funkce faktorial() spočítá faktorial proměnné **cislo** <br />
      ... <br />
      
**NÁVRATOVÝ KÓD** <br />
      U fuknkce scitani() při úspěšném výpočtu sečte obě čísla ve funkci vypocet() a výsledek se zobrazí v TextFieldu - vysledek(). <br />
      U fuknkce faktorial() se vypočítá faktroiál čísla a ve funkci vypocet() zobrazí výsledek v TextFieldu - vysledek(). <br />
      ...

## Tiráž

### Prostředí 
Windows 7 64bit

### Autoři 
**Praise the sun** <br />
David Bulawa (xbulaw01) <br />
Jabub Dolejší (xdolej09) <br />
František Policar (xpolic04) <br />
Tomáš Svěrák (xsvera04)

### Licence
Tento program je poskytovan **[GNU General Public License](https://cs.wikipedia.org/wiki/GNU_General_Public_License)**
