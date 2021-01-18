#Kayttoliittymaharjoitus-IVT-autokorjaamo
Kyseessä on 1. vuosikurssin Ihminen ja vuorovaikutteinen teknologia -kurssin harjoitustyö. Fokus työssä oli käyttäjäystävällisen käyttöliittymän suunnittelussa.

##Autokorjaamo IVT:n sivujen suunnitteluprototyypin suunnitteluvalintojen perustelut

Tätä suunnitteluprototyyppiä varten loin käyttöliittymän, joka voidaan liittää jo olemassa oleville nettisivuille. Käyttöliittymä avautuu uuteen ikkunaan, kun käyttäjä klikkaa sivulla olevaa ”Varaa huolto”-nappulaa.

Käyttöliittymän käyttömahdollisuudet on pyritty tuomaan mahdollisimman hyvin esiin käyttäen yleisesti tuttuja nappuloita, valintalaatikoita ja tekstilaatikoita. Kaikki objektit, joiden kanssa käyttäjä voi olla vuorovaikutuksessa on tuotu esille tummemmalla taustavärillä. Lisäksi jokaisessa ikkunassa on pieni teksti ohjeena, mitä tuolla sivulla käyttäjän on tarkoitus tehdä. Käyttöliittymän alareunassa on palkki, joka kuvaa käyttäjän edistymistä varausprosessissa. Palkki kasvaa sitä mukaa kun edetään ja yläpuolella on teksti, joka ilmaisee, missä vaiheessa ollaan menossa ja monta vaihetta on jäljellä.

Rajoituksia on hyödynnetty näyttämällä käyttäjälle yksi vaihe kerrallaan. Näin käyttöliittymä pysyy selkeänä ja syötteiden oikeellisuutta on helppo kontrolloida. Tällä pyritään myös vähentämään käyttäjän tekemiä virheitä. Käyttäjää ei päästetä seuraavalle sivulle ennen kuin kaikki tarvittavat tiedot on syötetty oikeassa muodossa. Seuraavalle sivulle siirtymisen nappula siihen asti harmaana ja sitä ei voi klikata. Virheistä ilmoitetaan käyttäjälle sen objektin vieressä, jossa virhe huomataan. Viimeisellä sivulla käyttäjä voi tarkistaa vielä itse syöttämiensä tietojen oikeuden ennen varauspyynnön lähettämistä.

Toimintojen näkyvyydessä on otettu huomioon palvelun skaalautuminen eri kokoisille näytöille. Tekstit ja nappulat ovat sen verran isoja ja niitä on sivulla vain sen verran vähän, että käyttö onnistuu myös mobiililaitteilla. Painikkeilla ja tekstikentillä on yksiselitteiset tehtävät, jotka pystytään nopeasti omaksumaan ilman käyttöohjetta.

Käyttöliittymässä hyödynnetyt kytkennät ovat luonnollisia. Punaisesta rastista varaus lopetetaan, vihreästä ok-merkistä varaus lähetetään, kysymysmerkistä saa tarvittaessa apua, nuolesta eteenpäin siirrytään seuraavaan vaiheeseen ja nuolesta taaksepäin palataan edelliseen vaiheeseen. Näitä toimintoja on havainnollistettu vielä tekstillä objektien välittömässä läheisyydessä.

Palautteen käyttäjä saa välittömästi. Jos tarvittavat valinnat on tehty, päästään siirtymään seuraavalle sivulle. Virheen sattuessa punainen teksti ilmaantuu sen objektin viereen, jossa virhe havaitaan. Nappuloiden painaminen toistaa tietokoneella tutun ”klik”-äänen ja mobiililaitteella äänen lisäksi laite tärähtää. Näin tulee selväksi, että nappulan painaminen on rekisteröitynyt, vaikka seuraavan sivun lataamiseen menisi hetki. Varauspyynnön onnistuneesta lähetyksestä ilmoitetaan käyttäjälle, kun ollaan palattu huoltoliikkeen sivulle, josta alun perin painettiin ”Varaa huolto”-nappulaa.

Hahmolait on suunnittelussa otettu huomioon. Ohjetekstit on sijoitettu aina sen objektin viereen, jota tuo ohje koskee. Sivut on tehty luettavaksi ylhäältä alaspäin, jossa ylhäällä on aina otsikko, mitä tällä sivulla käsitellään. Otsikon alla seuraa heti lyhyt ohje, kuinka sivun objektien kanssa tulee toimia. Sitten tehdään valinnat, täytetään tarvittavat tekstikentät ja sivun alareunasta päästään jatkamaan seuraavaan vaiheeseen. Samoja asioita tekevät nappulat, valintaikkunat ja tekstikentät on pidetty samannäköisinä koko käyttöliittymän läpi sekä ne on sijoiteltu samoille joka sivulla samoille paikoille.

-Ville Kyytinen-
