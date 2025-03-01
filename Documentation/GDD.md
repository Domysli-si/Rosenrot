
---

:LiCalendar: Date : 2025-02-26
:LiClock: Time : 18:36
:LiArrowLeftSquare: Return :
:LiGlobe: Sources : 
:LiLink: List of links : 

---
# 🌹Rosenrot 🌹
## Game Design Document


Autor: Samuel Majer, Max Majer
Datum: 20. února 2025

## 1 Obecné informace
### 1.1 Žánr
- roguelike,  action-adventure rpg

### 1.2 Cílová skupina
- Casual hráči 
- Věková kategorie  18+, kvůli gore prvkům ve hře.
### 1.3 Stručný popis
(Krátký odstavec popisující koncept hry)

### 1.4 Rozsah projektu
- Singleplayer 
- Doba vývoje: 6 měsíců 
- Odhadovaná doba hraní: Více než 20 minut na jedno dohrání.
### 1.5 Inspirace a reference
- Enter the Gungeon 
- Soul Knight 
- Binding of Isaac 
- Cult of the Lamb 
- Rammstein – Rosenrot

### 1.6 Technické požadavky
- Platforma: PC (Windows a Linux)
- Engine: Godot
- Podpora multiplayeru: Ne, pouze singleplayer. 
- Grafika: 2D pixel art 
- Zvuk a hudba: Využijí se externí zvuky a hudba (volně dostupné zdroje nebo komunitní zvukové knihovny).

### 1.7 Rozdělení práce 
- Jednotlivec (all-in-one): programování, grafiku, design.

## 2 Game Play a herní mechaniky
### 2.1 Cíl hry 
- Hráč se vydává na dobrodružství s cílem získat zázračnou růži. Během hry bude muset porazit silné nepřátele, prozkoumávat nebezpečné lokace, sbírat předměty a vylepšení, aby se nakonec dostal až na konec, kde získá růži a dokončí hru.
### 2.2 Základní herní smyčka (core gameplay loop)
- Startovní lokalita: Hráč se ocitne v první oblasti, kde se seznámí se základními mechanikami (pohyb, útoky, sbírání předmětů). 
- Procházky po lokacích: Hráč projde různými náhodně generovanými úrovněmi. 
- Boj a sbírání: Získávání nových zbraní, vybavení a vylepšení. 
- Postup do těžších oblastí: Jak hráč postupuje, narazí na silnější nepřátele a složitější úkoly.
#### 2.3 Překážky pro hráče 
- Terén: Různé povrchy ovlivňují pohyb hráče. Např. bláto zpomalí pohyb. 
- Nepřátelé: Hordy rytířů, kteří mají různá vybavení a schopnosti. 
- Úroveň hráče: Hráč musí vylepšit své schopnosti, aby byl schopen čelit silnějším nepřátelům.

---
## 3 Popis herních mechanik

### 3.1 Stats

|    ikona    | zkratka | nazev           | popis                                               |
| :---------: | :-----: | --------------- | --------------------------------------------------- |
| ![[AD.png]] |   AD    | (attack damage) | Utocna sila hrace. Hodnota kolik bude davat damage. |
| ![[AS.png]] |   AS    | attack speed    |                                                     |
| ![[HP.png]] |   HP    | health          |                                                     |
| ![[AR.png]] |   AR    | armor           |                                                     |
|             |   MR    | agic resist     |                                                     |
| ![[M.png]]  |    M    | movement        |                                                     |
| ![[R.png]]  |    R    | range           |                                                     |
|             |  crit   | critical chance |                                                     |
### 3.2 Hráč
- ma inventor 
#### 3.2.1 Pohyb
- pohyb do osmi smeru 
- roll mechanica
#### 3.2.2 Systém zdraví hráče
#### 3.2.3 Výdrž hráče
#### 3.2.4 Infikace hráče
#### 3.2.5 Systém úrovní hráče a zlepšování vlastností

### 3.3 NPC 
#### 3.3.1 Enemy

|      | ![[Big Knight.png]] | ![[Ass Knight.png]] | ![[High Knight.png]] | ![[Av Knight.png]] |
| ---- | ------------------- | ------------------- | -------------------- | ------------------ |
| Name | Chonky Knight       | Ass Knight          | High Knight          | Ave. Knight        |
| ad   |                     |                     |                      |                    |
| as   |                     |                     |                      |                    |
| hp   |                     |                     |                      |                    |
| ar   |                     |                     |                      |                    |
| mr   |                     |                     |                      |                    |
| m    |                     |                     |                      |                    |
| r    |                     |                     |                      |                    |
| crit |                     |                     |                      |                    |


### 3.4 Sbírání předmětů
### 3.5 Interakce s prostředím 

### 3.6 Dialogy



## 4 Level design
### 4.1 Struktura úrovní 

### 4.2 Prostředí

### 4.3 Dynamika úrovní

## 5 Audiovizuální styl
### 5.1 Grafika
- 2D Pixel art styl, všechny grafiky budou vytvořeny vlastními silami.
### 5.2 Hudba a zvuk
- Hudba a zvukybudou z volně dostupných zdrojů nebo komunitních soundtracků. 
- Zvuky budou zahrnovat: efekty boje, ambientní zvuky (lesní šelesty), hudbu měnící se podle akce.
## 6 UI a UX
### 6.1 Hlavní menu a rozhraní

### 6.2 Ovládání hry
![[Keyboard scheme]]

## 7 Casoprostor
### 7.1 Cas
- Neni podstatne. Neni ani blize specifikovan. 
### 7.2 Prostor
- Fantaskni svet plny magie. Stredoveka tematika.
### 7.3 Shrnuti pribehu
- Zije mladik(hracova postava) a jeho slecna v jedne malebne vesnici. Po najezdu je smrtelne zranena. Mladik se tedy vydava na cestu za Rudou ruzi. On niz se vypravi, ze ma nesmerne lecive ucinky. Zaroven vsak se chce pomstit najezdnikum. Jedine voditko, ktere ma je zahady rudy plyn. 
- Neni jediny kdo prahne po Rude ruzi.
### 7.4 Postavy 
- Mladik 
- milovana 
- bandite 

# Changelog:
Kontrola 13/20. 3. 2024
Stav hry: 

Požadavky na úpravu:

Cíle na příště:
