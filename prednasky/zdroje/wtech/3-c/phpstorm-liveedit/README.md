# Cvičenie 3 - PhpStorm Live Edit

PhpStorm poskytuje funkcionalitu živého náhľadu zmien vykonaných v HTML, CSS a JavaScripte, napr. keď nastavíme v css súbore nadpisu červenú farbu,  môžeme priamo v prehliadači vidieť ako vyzerá zmena - samotná stránka - bez potreby jej znovunačítania (angl. page reload), jednoducho pri akejkoľvek zmene rovno vidíme, ako to vyzerá.

## LiveEdit plugin
* V PhpStorm sa cez hlavné menu navigujte do *Settings* -> *Plugins*.
* Kliknite na tlačidlo *Browse repositories*.
* Do vyhľadávacieho pola napíšte "liveedit".
* Kliknutím na tlačidlo *Install* nainštalujte plugin.
* Po nainštalovaní reštartujte PhpStorm.

## Nastavenie v PhpStorm
* Cez hlavné menu sa navigujte v PhpStorm do *Settings* -> *Build, Execution, Deployment* -> *Debugger* -> *Live Edit*.
* V nastaveniach "Update" prepnite prepínač na *Auto*.
* Uložte nastavenie.


## Rozšírenie do Chromu
Z Chrome Web Store si nainštalujte rozšírenie do prehliadača - [JetBrains IDE Support](https://chrome.google.com/webstore/detail/jetbrains-ide-support/hmhgeddbohgjknpmjagkdomcpobmllji)

## Hotovo, editujme naživo...

* Vytvorte si v projekte HTML dokument, napr. *hokuspokus.html*.
* V PhpStorm sa cez hlavné menu navigujte do  *Run* -> *Edit Configurations...*.
* V dialógovom okne vľavo hore je "zelené plus" - kliknutím pridajte novú konfiguráciu - vyberte *JavaScript Debug*.
* V poli "Name" zadajte nejaký názov konfigurácie, ďalej v poli URL vyberte vytvorený súbor v projekte - *hokuspokus.html*.
* Uložte nastavenie.
*  V PhpStorm sa cez hlavné menu navigujte do  *Run* -> *Debug...* a spustite vytvorenú konfiguráciu.

*Otvorí sa prehliadač a akúkoľvek zmenu v danom súbore môžete priamo vidieť v prehliadači. Skúste pripojiť aj CSS a JS súbory...*


