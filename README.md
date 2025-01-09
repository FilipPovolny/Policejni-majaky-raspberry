# Policejní majáky- Raspberry pi pico wh

## Informace: 

Autor: Filip Povolný

Třída: T3A

Školní rok: 2024/2025

## O co se jedná

Tento projekt se zaměřuje na ovládání čtyř NeoPixel LED pásků pomocí mikrokontroléru Raspberry Pi Pico, a dvou tlačítek. Použil jsem čtyři neopixelové led pásky WS2812B a dvě tlačítka.

## Cíl

Mým cílem je vytvořit systém, který umožňuje řídit čtyři NeoPixel LED pásky připojené k mikrokontroléru, přičemž tento systém ovládám pomocí dvou tlačítek. Tato tlačítka slouží k přepínání mezi různými režimy svícení LED pásků a také k zapínání a vypínání celého systému LED pásků. Každý LED pásek je připojen k jinému GPIO pinu, což umožňuje nezávislé řízení každého pásku. Režimy ovládání zahrnují různé vzory svícení, například blikání LED nebo pevné barvy, které se střídají mezi modrou a červenou na různých pásech. První tlačítko slouží k přepínání mezi těmito režimy, přičemž režimy mění způsob svícení LED pásků podle specifických vzorců. Druhé tlačítko slouží k zapnutí nebo vypnutí celého systému, což umožňuje snadnou kontrolu, zda LED pásky budou svítit, nebo zda budou zcela vypnuté. Celkovým cílem je vytvořit jednoduchý a intuitivní systém pro ovládání světelných efektů, který je ovládán dvěma tlačítky, a to bez potřeby složitějšího uživatelského rozhraní. Tento systém je ideální pro aplikace, kde je potřeba měnit osvětlení a dynamiku barev podle aktuálních potřeb.

## Použité komponenty: 
Led pásek:

![ledpasek](https://github.com/user-attachments/assets/7038b9df-7b9b-4bf3-ba79-3a7c936efe83)

Tlačítko:

![491_491-tlacitko-6x6x5mm](https://github.com/user-attachments/assets/95909073-9334-48d3-a901-f5d6f2b0cccd)

Raspberry: 

![23490-Raspberry-Pi-Pico-WH](https://github.com/user-attachments/assets/0d46ea63-b2f9-4d99-a086-247decbe25e7)


## Aktuální stav:

Základní kód je napsaný, zatím jen tři módy:   

                                                -blikání modrá led pásek 1 a 3 a červená led pásek 2 a 4
                                                
                                                -blikání čerená led pásek 1 a 3 a modrá led pásek 2 a 4
                                                
                                                -blikání červená led pásek 1 a 2 a modrá led pásek 3 a 4

Zapojení na breadboardu (jen dva led pásky a bez tlačítek- z první verze, kde jsem zkoušel jak led pásky fungují):

![IMG_1019](https://github.com/user-attachments/assets/9fbe8bbf-74a1-47d9-9879-b721da2939d6)

Zkoušení jak majáky blikají:

https://github.com/user-attachments/assets/9053972b-640d-48e0-ab2d-deb96a53a766

Led pásky připravené na instalaci do auta (jen dva, protože mi dva nefungují, protože shořeli): 

![IMG_1030](https://github.com/user-attachments/assets/ad3b9ced-bb54-436e-a345-7c3a08fa5a74)

![IMG_1032](https://github.com/user-attachments/assets/d746d139-b02b-4d9d-9d96-3c06f60f6dce)
# Popis:
1. Zkoušel jsem jestli led pásky fungují a jak fungují
2. Zkusil jsem naprogramovat jednoduché blikání: Dostupné z: https://github.com/FilipPovolny/Policejni-majaky-raspberry/blob/main/Prvni%20kod.
3. Naprogramoval jsem aktuální kód: https://github.com/FilipPovolny/Policejni-majaky-raspberry/blob/main/Kod%20pro%20majaky
4. Napájel jsem led pásky na delší kabely
5. Zkontroloval jsem jestli mi led pásky fungují a prřestali mi dva fungovat


## Schéma zapojení: 

![Snímek obrazovky (134)](https://github.com/user-attachments/assets/fe4ec755-6786-4e0a-b681-79d3a7bd5de7)


## Citace:

[1] Adafruit guide. Online. Dostupné z: https://learn.adafruit.com/adafruit-neopixel-uberguide/the-magic-of-neopixels. [cit. 2025-01-06].

[2] CoreElectronics. Online. Dostupné z: https://www.youtube.com/watch?v=aNlaj1r7NKc&t=334s. [cit. 2025-01-06].
