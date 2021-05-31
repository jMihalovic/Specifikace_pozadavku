# Specifikace požadavků
## Verze 1

Jakub Mihalovič <br/>
mihalovic.jakub.2018@skola.ssps.cz <br/>
26. 5. 2021

Úvod
  * Tento dokument slouží ke specifikaci požadavků programu
  * Kontakt
    * Jakub Mihalovič mihalovic.jakub.2018@skola.ssps.cz
  * Odkazy na související dokumenty 
    * https://github.com/jMihalovic/Uzitecny_software/edit/main/README.md

  * Scénáře
    * Způsoby využití
      * V aplikaci může uživatel projíždět záznamy a prohlížet si jejich detaily. Může také záznamy přidávat, upravovat, mazat a přidávat jim osobní hodnocení.
      * Při větším množství záznamů bude možné použít filtry.
    * Typy uživatelských rolí
      * Aplikace nebude rozlišovat jednotlivé uživatele
    * Vymezení rozsahu
      * Aplikace nebude obsahovat jiné databáze( např. režisérů, herců apod.).
      * Hodnocení ani záznamy a jejich data nebudou sdílena s jinými uživateli.
  * Celková hrubá architektura
    * Pracovní tok
      * Zapnutí aplikace
      * Zobrazení databáze
      * Uživatel pracuje se záznamy
      * Konec aplikace
    * Detaily
      * 4 WPF okna
        * Okno s databází a tlačítky (pro úpravu,přidávání,mazání a filtry)
         ![obrázek 1](https://github.com/jMihalovic/Specifikace_pozadavku/blob/main/1.png "Obrázek 1")
        * Okno pro přidávání a upravování záznamů (Textová a výběrová pole pro editaci dat a tlačítko pro odsouhlasení)
        * Okno pro filtry (Výběrové okno pro typ seřazení a filtrování pomocí detailů záznamů)
        * Potvrzovací okna (např. po úpravě dat nebo před smazáním záznamu)

