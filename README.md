# DEPRECATED

[![No Maintenance Intended](https://unmaintained.tech/badge.svg)](https://unmaintained.tech)

Deze Github repository wordt niet langer door JCID bijgewerkt. Overweeg in plaats daarvan het [DirectAdmin translation platform][directadmin-translation-evolution-skin] te gebruiken.

# Download vanaf [DirectAdmin translation platform][directadmin-translation-evolution-skin]

Evolution skin (`nl.po`)

    curl -o /usr/local/directadmin/data/skins/evolution/lang/nl.po https://translate.directadmin.com/download/directadmin/evolution-skin/nl/?format=po

Evolution login page (`login-nl.po`)

    curl -o /usr/local/directadmin/data/skins/evolution/lang/login-nl.po https://translate.directadmin.com/download/directadmin/evolution-login/nl/?format=po

# Download vanaf [Github][github-evolution-skin] *versie `v2.0.2`*

Evolution skin (`nl.po`)

    curl -o /usr/local/directadmin/data/skins/evolution/lang/nl.po https://raw.githubusercontent.com/JCID/directadmin-evolution-skin-dutch-translation/v2.0.2/nl.po
    
Evolution login page (`login-nl.po`)

    curl -o /usr/local/directadmin/data/skins/evolution/lang/login-nl.po https://raw.githubusercontent.com/JCID/directadmin-evolution-skin-dutch-translation/v2.0.2/login-nl.po

# Rechten herstellen

Evolution skin (`nl.po`)

    chown diradmin:diradmin /usr/local/directadmin/data/skins/evolution/lang/login-nl.po
    chmod 0755 /usr/local/directadmin/data/skins/evolution/lang/login-nl.po

Evolution login page (`login-nl.po`)

    chown diradmin:diradmin /usr/local/directadmin/data/skins/evolution/lang/login-nl.po
    chmod 0755 /usr/local/directadmin/data/skins/evolution/lang/login-nl.po

[directadmin-translation-evolution-skin]: https://translate.directadmin.com/projects/directadmin/evolution-skin/nl/
[github-evolution-skin]: https://github.com/JCID/directadmin-evolution-skin-dutch-translation/releases
