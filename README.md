Product.cs luo Product luokan, jota muut osat koodista käyttävät.

Product.cshtml luo nettisivulle Products osion, jossa näkyy tuotteiden kuvat, nimet, kuvaus ja hinta. Tiedot saadaan Product luokan avulla

Products.json tekee listan tuotteista, hyödyntäen Product luokkaa.

HomeController.cs käyttää Products.json:in luomaa listaa lisätäkseen Product.cshtml:n lisäämään Products osioon tuotteet ja niiden tiedot.
