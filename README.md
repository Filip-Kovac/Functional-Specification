# To-Do list #
## Verze 1.0 ##
## 15. 05. 2021 ##
## Filip Kováč ##

### 1. Úvod ###
#### 1.1 Účel ####
Do programu bude možno přidat či odebrat úkol, vložit požadovaný datum splnění, stav (otevřený, hotový).
Možnost vytvoření/smazání skupiny, do kterých půjde jednotlivé úkoly vložit.
Seznam se bude ukáldat do txt souboru, ze kterého to bude možnost opět načíst.

#### 1.2 Pro koho je dokument určený ####



### 2. Scénáře ###
#### 2.1 Všechny reálné způsoby použití ####
Zápis věcí, které si člověk nemusí pamatovat. Uspořádání úkolů.

#### 2.2 Typy uživatelských rolí, „personas“ ####
Budou dvě možnosti rolí. <br>
První možnost je pouze uživatel - vytváří si úkoly pouze pro sebe. <br>
Druhá možnost je administrátor a uživatel - administrátor vytváří úkoly pro uživatele

#### 2.3 Detaily, motivace, „živé“ příklady ####
Mívám problémy s uspořádáním dne.

#### 2.4 Vymezení rozsahu – co v sw NEbude ####
Propojení s jiným zařízením. 

#### 2.5 Na co se NEbude klást důraz(výkonnost) ####
Na grafické zpracování sw.


### 3. Celková hrubá architektura ###
#### 3.1 Pracovní tok ####
Soustředit se budu hlavně na vytváření skupin. Poté přidávání úkolů do jednotlivých skupin.
Nejmenší důraz bude na grafiku.

#### 3.2 Hlavní moduly ####
V apilikaci budou 2 moduly - přehled úkolů, přidání úkolů <br>
Jestliže bude pouze uživatel, tak bude mít přístup do obou modulů.
Když bude administrátor a uživatel, tak administrátor bude mít přístup do obou modulů ,ale uživatel pouze do přehledu.

