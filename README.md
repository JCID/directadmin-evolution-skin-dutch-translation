# DirectAdmin - Evolution skin - Dutch translation

Copyright |. De vertaling is in samenwerking met DirectAdmin uitgevoerd. Leden met een DirectAdmin licentie kunnen vrijblijvend gebruik maken van de vertaling. Bug of fouten melden kan altijd naar de auteur.

|||
|-----|-----|
|Auteur|Snelwebcenter|
|E-mail|[info@snelwebcenter.nl](mailto:info@snelwebcenter.nl)|
|Versie|2.0 (vertaling) (27-01-2020)|

# Installatie van versie `v2.0.2`

```bash
curl -o /usr/local/directadmin/data/skins/evolution/lang/nl.po https://raw.githubusercontent.com/JCID/directadmin-evolution-skin-dutch-translation/v2.0.2/nl.po
chown diradmin:diradmin /usr/local/directadmin/data/skins/evolution/lang/nl.po
chmod 0755 /usr/local/directadmin/data/skins/evolution/lang/nl.po
```

```bash
curl -o /usr/local/directadmin/data/skins/evolution/lang/login-nl.po https://raw.githubusercontent.com/JCID/directadmin-evolution-skin-dutch-translation/v2.0.2/login-nl.po
chown diradmin:diradmin /usr/local/directadmin/data/skins/evolution/lang/login-nl.po
chmod 0755 /usr/local/directadmin/data/skins/evolution/lang/login-nl.po
```

# Actualiseren ten opzichte van DirectAdmin

Download [PoEdit](https://poedit.net/download). PoEdit heeft een optie om het PO-bestand bij te werken vanuit een bestaand POT-bestand. Ga vanuit het menu naar `Catalogus` -> `Bijwerken vanuit POT-bestand`.

Het POT-bestand vind je onder de directory `cd /usr/local/directadmin/data/skins/evolution/lang/` met daarin `dictionary.pot`, `login-dictionary.pot` en `vars.pot`.

```bash
scp shared02.prod.jcid.nl:/usr/local/directadmin/data/skins/evolution/lang/dictionary.pot dictionary.pot
open nl.po -a poedit
```

```bash
scp shared02.prod.jcid.nl:/usr/local/directadmin/data/skins/evolution/lang/login-dictionary.pot login-dictionary.pot
open login-nl.po -a poedit
```
