# Evidence MTH – vozíky a baterie (verze 2)

Webová aplikace pro evidenci MTH vozíků, trakčních baterií, technických kontrol a revizí.

## Funkce
- Přehled s prošlými a blížícími se lhůtami (TK, revize baterií)
- Vozíky: evidenční číslo, druh, výrobce, model, fotka, popis, vlastník, servis, TK, přidělené baterie, historie
- Baterie: typ, napětí, kapacita, vlastník, servis, přidělení k vozíku, revize
- Tisk evidenční karty vozíku (A4)
- Export do Excelu (listy Vozíky, Baterie, Revize a kontroly)
- Záloha a obnova dat (soubor .json)

## Důležité – kde jsou data
Data se ukládají **v prohlížeči na daném počítači** (IndexedDB), ne na GitHubu.
- Jiný počítač nebo jiný prohlížeč = prázdná evidence → použijte **💾 Záloha → Načíst zálohu**.
- Vymazání dat prohlížeče (historie, cookies a data webů) smaže i evidenci → **pravidelně stahujte zálohu**.
- Zálohy neukládejte do veřejného repozitáře.

Pro export do Excelu je potřeba připojení k internetu.
