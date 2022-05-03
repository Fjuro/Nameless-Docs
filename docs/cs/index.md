![NamelessMC Banner](https://i.imgur.com/gt8uezk.png)
NamelessMC je bezplatný, snadno použitelný a výkonný webový software pro váš Minecraft server, který obsahuje spoustu funkcí.

NamelessMC verze 2.0.0 je stále předběžné vydání a není zatím doporučena k použití na produkčním webu. Sledujte vývoj v našem [Spigot vláknu](https://www.spigotmc.org/threads/nameless-minecraft-website-software.34810) a na našem [Discord serveru](https://discord.gg/nameless).

Oficiální web projektu s podporou a dalšími stahovatelnými součástmi jako doplňky a šablony, lze nalézt na [https://namelessmc.com/](https://namelessmc.com/).

## Funkce
Následující seznam je stručným shrnutím funkcí dostupných ve v2 předběžném vydání 12:
- 🙋 Fóra
- 📃 Vlastní stránky: vytvářejte si své vlastní HTML stránky a omezujte k nim přístup podle skupiny.
- 🎮 Integrace Minecraftu
  - Zobrazení stavu Java nebo Bedrock serveru
  - Ověřování účtů pomocí MCAssoc nebo pluginu
  - [Herní plugin](https://www.spigotmc.org/resources/nameless-plugin-for-v2.59032)
    - Vyžadování ověření ve hře pro NamelessMC účty
    - Umožnění registrace účtů ve hře
    - Synchronizace Vault ranků s NamelessMC skupinami (jedmosměrná, hra -> web)
    - Zobrazování webových oznámení v chatu
    - Whitelist hráčů s účtem na webu
    - Banování hráčů, kteří jsou zabanováni na webu
    - Zobrazování PlaceholderAPI placeholderů na webových uživatelských profilech nebo v žebříčcích
- 🗨️ Integrace Discordu
  - Webhook: získávejte aktualizace o nových členech, příspěvcích na fóru, zdrojích atd.
  - [Discord bot Nameless-Link](https://github.com/NamelessMC/Nameless-Link/wiki/Setup)
    - Propojte Discord účty s NamelessMC účty
    - Synchronizujte Discord role s NamelessMC skupinami (obousměrné)
- ⚙️ [API](https://docs.namelessmc.com/en/api-documentation) - Napište si vlastní integrace nebo použijte jednu z našich (viz výše)
- 🧩 Nový systém doplňků umožňující lepší integraci NamelessMC.
- ✏️ Nové systémy šablon a jazyků umožňující kompletní přizpůsobení.
- ✨ Možnost pěkných URL (requires mod_rewrite or special nginx config).
- 🎛 Widgety: doplňky mohou vytvářet widgety, které mohou být zobrazeny na většině uživatelům dostupných stránkách a mohou zobrazit téměř cokoli.
- 🚩 Přeloženo do [více než 20 jazyků](https://github.com/NamelessMC/Nameless/tree/v2/custom/languages)

#### Přizpůsobení Nameless
- Pro vývojářskou dokumentaci k doplňkům se podívejte na [tento wiki článek](https://docs.namelessmc.com/en/module-documentation) (anglicky).
- Vývojářská dokumentace pro vývoj šablon a widgetů již brzy.

## Instalace
Instrukce k instalaci naleznete v [tomto wiki článku](https://docs.namelessmc.com/cs/installation).

## Podpora
Podporu naleznete na následujících místech:
- [Discord <img src="https://discordapp.com/api/guilds/246705793066467328/widget.png?style=shield">](https://discord.gg/nameless)
- [Oficiální fórum podpory](https://namelessmc.com/forum)
- [SpigotMC](https://www.spigotmc.org/threads/nameless-minecraft-website-software.34810/)

Žádosti o funkce mohou být dávány na [fórum](https://namelessmc.com/forum/view/7-web-feature-requests/) a chyby lze nahlašovat na stránce [GitHub Issues](https://github.com/NamelessMC/Nameless/issues).

## Plugin
Pro integraci Minecraftu můžete nainstalovat Nameless Plugin na váš Spigot server. Momentálně je plugin dostupný pouze pro Spigot, pracujeme ale na tom, abychom jej přinesli i na jiný software, například Sponge či BungeeCord. Seznam funkcí a pokyny k instalaci naleznete na [této stránce](https://github.com/NamelessMC/Nameless-Plugin/blob/master/README.md).

## Překlady
Překlady NamelessMC jsou poskytovány komunitou. Aktuálně dostupné překlady lze nalézt. Upozorňujeme, že ne všechny překlady mohou být aktuální. Postup překladů je zobrazen níže.

Pokud chcete pomoct s překladem NamelessMC do vašeho jazyka, vytvořte si prosím účet na [translate.namelessmc.com](https://translate.namelessmc.com/projects/namelessmc/). Pro diskuzi s ostatními překladateli navštivte Discord server [NamelessMC Translators](https://discord.gg/7Dku3fE).

![Postup překladu](https://translate.namelessmc.com/widgets/namelessmc/cs/nameless/multi-auto.svg)

## Přispívání
Jsme rádi za jakákoli přispění do kódu a překladů. Neváhejte si forknout repozitář na GitHubu a vytvářet jakékoli pull requesty.
- Seznam úkolů obvykle vedeme na kartě Milestones na stránce Issues.
- Ke správě závislostí používáme nástroj Composer. Před instalací závislostí je třeba nainstalovat nástroj Composer do vašeho místního počítače. Pokyny k instalaci naleznete [zde](https://getcomposer.org/doc/00-intro.md).
- Pro instalaci balíčků Composeru, na kterých jsme závislí, spusťte následující příkaz v kořenovém adresáři úložiště NamelessMC:
    ```
    composer install --dev
    ```
  - Tato akce může zabrat přibližně minutu v závislosti na vašem internetovém připojení.

## Speciální poděkování
- Všem [přispěvatelům](https://github.com/NamelessMC/Nameless/graphs/contributors) NamelessMC.
- [JetBrains](https://www.jetbrains.com/), jejichž produkty jsou využívány k vývoji projektu.