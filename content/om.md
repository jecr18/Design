---
views:
    kursrepo:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa

    mig:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-mig
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta:
                type: single
                route: block/byline
---
Om
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/om.md`.

Skriv några kloka ord om kursen?

Lägg till en representativ bild för kursen, enligt ditt egna val.

[FIGURE src=image/car.png?w=300 caption="En fin bil som demobild."]
