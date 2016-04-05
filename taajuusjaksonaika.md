# Amplitudi, taajuus ja jaksonaika

![Kuva 2.1](scope2.jpg)

*Kuva 2.1. Oskilloskoopin kuvaputki*

Yleismittarilla voidaan tutkia hitaasti muuttuvia signaaleja, mutta kun
signaali muuttuu satoja, tuhansia tai miljoonia kertoja sekunnissa, tarvitaan
*oskilloskooppia*. Oskilloskoopilla voidaan piirtää jännitteen vaihtelu ajan
suhteen ruudulle (*kuva 2.1*). Aloittakaamme tutustumalla oskilloskooppiin.

**Tehtävä 2.1:** *Kytke funktiogeneraattorin MAIN OUT oskilloskoopin
kanavaan 1. Yritä saada signaali näkymään ruudulla.*

![Kuva 2.2](scope3.jpg)

*Kuva 2.2. Liipaisusäätimet*

Tehtävää 2.1 varten oskilloskoopin liipaisu (*trigger*) sekä amplitudi-
ja taajuusalueet tulee säätää kohdilleen. Aloita kääntämällä
liipaisutasonuppia (*kuva 2.2*) edestakaisin, kunnes signaali on näkyvissä ja
paikallaan. Jos et saa analogisella oskilloskoopilla signaalia näkyviin,
voit käyttää LINE-lähdettä liipaisulle, käydä seuraavat kohdat
läpi ja säätää liipaisun lopuksi kohdalleen.  LINE-lähde käyttää
sähköverkon 50Hz vaihtovirtaa liipaisuun, joten sitä käyttäen signaali ei
pysy paikallaan. **HUOM:** varmista, että oskilloskoopissa on valittuna oikea
kanava (*ks. kuva 2.4*), ja että sama kanava on myös liipaisulähteenä
(*source*).

![Kuva 2.3](scope4.jpg)

*Kuva 2.3. Pyyhkäisysäätimet*

Säädä seuraavaksi taajuusalue kohdilleen pyörittämällä taajuusalueen
valintanuppia (*kuva 2.3*). Nupin *TIME/DIV*-teksti tarkoittaa sitä ajanjaksoa,
jota yksi oskilloskoopin näytön viivaväli (*kuva 2.1*) vastaa. Jos
signaali näyttää vaakasuoralta viivalta, käännä nuppia vastapäivään
(kohti pienempiä taajuuksia); jos se liikkuu ylösalaisin niin nopeasti,
että se muodostaa palkin, käännä nuppia myötäpäivään. Jos signaali on
vieläkin vaakasuora viiva, on amplitudialue todennäköisesti väärä &mdash;
käymme sen läpi seuraavaksi.

![Kuva 2.4](scope5.jpg)

*Kuva 2.4. Kanavasäätimet*

Amplitudialueen valinta tapahtuu siihen tarkoitetulla nupilla (*kuva 2.4*).
Nupin yhteydessä oleva teksti *VOLTS/DIV* tarkoittaa sitä jännite-eroa,
jota yksi viivaväli oskilloskoopin ruudulla vastaa.  Jos signaali
näyttää suoralta viivalta, on amplitudialue liian suuri, joten käännä
nuppia myötäpäivään. Jos signaali leikkautuu ylä- ja alareunoihin,
on alue liian pieni, joten nuppia käännetään vastapäivään. Kanavan
valintasäätimellä voidaan valita ruudulla näytettävä kanava (tai kanavat);
tässä tehtävässä käytämme kanavaa A. DC-erotus &ndash;säätimellä
voidaan suodattaa tasavirtakomponentti pois signaalista, jolloin signaalia ei
tarvitse erikseen käsin asemoida.

**Tehtävä 2.2:** *Aseta funktiogeneraattorin taajuudeksi
(frequency) 1MHz ja peak-to-peak amplitudiksi (amplitude) 1V käyttäen
signaaligeneraattorin säätimiä ja näyttöä. Käytä aaltomuotona
siniaaltoa (&#8767;). Tarkista arvot mittaamalla ne oskilloskoopilla.*

![Kuva 2.5](aaltomuoto.svg)

| Suure                             | Englanniksi           | Yksikkö       |
| --------------------------------- | --------------------- | --------------|
| Taajuus                           | Frequency             | Hertsi (*Hz*) |
| Jaksonaika &#8308;                | Period                | Sekunti (*s*) |
| Huipusta huippuun-amplitudi &sup2;| Peak-to-peak amplitude| Voltti (*V*) &#8309;|
| Huippuamplitudi &sup1;            | Peak amplitude        | Voltti (*V*) &#8309;|

> *1,2,4) katso kuva 2.5*                                                    
> *5) jännitesignaalien tapauksessa*

*Taulukko 2.1. Muutamia suureita*


