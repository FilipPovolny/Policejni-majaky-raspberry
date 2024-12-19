# Policejní majáky- Raspberry pi pico wh

## Informace: 

Autor: Filip Povolný

Třída: T3A

Školní rok: 2024/2025

## O co se jedná

Tento projekt se zaměřuje na ovládání čtyř NeoPixel LED pásků pomocí mikrokontroléru Raspberry Pi Pico, a dvou tlačítek. Použil jsem čtyři led pásky WS2812B a dvě tlačítka.

## Cíl

Mým cílem je vytvořit systém, který umožňuje řídit čtyři NeoPixel LED pásky připojené k mikrokontroléru, přičemž tento systém ovládám pomocí dvou tlačítek. Tato tlačítka slouží k přepínání mezi různými režimy svícení LED pásků a také k zapínání a vypínání celého systému LED pásků. Každý LED pásek je připojen k jinému GPIO pinu, což umožňuje nezávislé řízení každého pásku. Režimy ovládání zahrnují různé vzory svícení, například blikání LED nebo pevné barvy, které se střídají mezi modrou a červenou na různých pásech. První tlačítko slouží k přepínání mezi těmito režimy, přičemž režimy mění způsob svícení LED pásků podle specifických vzorců. Druhé tlačítko slouží k zapnutí nebo vypnutí celého systému, což umožňuje snadnou kontrolu, zda LED pásky budou svítit, nebo zda budou zcela vypnuté. Celkovým cílem je vytvořit jednoduchý a intuitivní systém pro ovládání světelných efektů, který je ovládán dvěma tlačítky, a to bez potřeby složitějšího uživatelského rozhraní. Tento systém je ideální pro aplikace, kde je potřeba měnit osvětlení a dynamiku barev podle aktuálních potřeb.

## Aktuální stav:

Základní mód je napsaný, zatím jen čtyři módy:   
                                                -blikání modrá led pásek 1 a 3 a červená led pásek 2 a 4

                                                -blikání čerená led pásek 1 a 3 a modrá led pásek 2 a 4
                                                
                                                -blikání červená led pásek 1 a 2 a modrá led pásek 3 a 4
