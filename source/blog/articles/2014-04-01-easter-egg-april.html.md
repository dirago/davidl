---
date: 2014-04-01
slug: easter-egg-april
title: "La mediaquery du 01 Avril"
page_title: C'est un piège
changefreq: monthly
priority: 0.8
---

Visible uniquement pour les tablettes, si vos visiteurs retournent leur appareil, le site fait une rotation. Si ils retournent leur tablettte, ...

~~~ css
    @media only screen and (min-width: 350px) and (max-width: 1025px) {
      body {
        transform : rotate(180deg);
      }
    }
~~~

Voir la [vidéo sur vine](https://vine.co/v/MeDj23XKT3T).
