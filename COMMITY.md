# Jak nahrát web na GitHub (min. 10 commitů)

Soubory jsou hotové, ale učitel chce vidět postupnou práci. Nahrávej je po částech
a po každém kroku udělej commit. Doporučené pořadí:

1. README.md (vytvoř při zakládání repozitáře)              "Vytvoření repozitáře"
2. index.html                                              "Přidána hlavní stránka"
3. style.css                                               "Přidán externí styl"
4. img/vetrelec.svg                                        "Přidán první obrázek"
5. historie.html                                           "Přidána podstránka Historie"
6. galerie.html                                            "Přidána podstránka Galerie"
7. img/joystick.svg                                        "Přidán obrázek joysticku"
8. img/srdce.svg                                           "Přidán obrázek srdce"
9. zdroje.html                                             "Přidána stránka se zdroji a citací AI"
10. malá úprava (např. barva v style.css nebo text v index.html)  "Doladění vzhledu"

## Rychle přes web GitHubu
Repozitář -> Add file -> Upload files -> přetáhni JEDEN soubor -> Commit changes.
(Složka img: při nahrávání obrázků napiš do názvu img/vetrelec.svg nebo přetáhni složku s jedním souborem.)

## Nebo přes terminál
git init
git add index.html && git commit -m "Přidána hlavní stránka"
git add style.css && git commit -m "Přidán externí styl"
... a tak dál
git branch -M main
git remote add origin https://github.com/TVUJ-UZIVATEL/JMENO-REPOZITARE.git
git push -u origin main

## Pak zapnout Pages
Settings -> Pages -> Branch: main, složka / (root) -> Save.
Odevzdáš odkaz https://TVUJ-UZIVATEL.github.io/JMENO-REPOZITARE/
