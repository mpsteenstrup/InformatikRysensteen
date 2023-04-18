# Farver
Verden er i farver, hvilket man godt kan glemme en decemberdag i Danmark. Farver bliver brugt kreativt og det kan være svært at sætte faste regler og retningslinjer for hvordan man skal bruge dem. Vi vil bruge teori beskrevet at "Interaction Design Foundation" kaldet "Color Theory"
* [Color Theory](https://www.interaction-design.org/literature/topics/color-theory)

### Øvelse
* Se filmen på siden, [Color Theory](https://www.interaction-design.org/literature/topics/color-theory).
* Hvilken dos and don't nævner filmen?
* Brug figuren The Color Wheel til at beskrive primære og sekundære farver.
* Brug figuren Color Schemes til at beskrive de forskellige farve temaer.
* Hvad er Complementary Color Scheme og hvordan gør man det mindre simpelt at se på?

Adobe har udviklet et website hvor man kan lege med farver og farvetemaer, [Adobe color-wheel](https://color.adobe.com/create/color-wheel). Bemærk at Adobe bruger HSB som ikke kan bruges direkte i html, hvor man bruger HSL. Hvis I bruger RGB så er de kompertible.

### Øvelse
* Prøv jer frem med de forskellige farvetemaer how Adobe, start simpelt og få en fornemmelse af hvad siden viser.

## Teori og praksis
Vi skal undersøge websider for deres farvetemaer. Hvis der er meget eksternt indhold, reklamer, videoer osv. kan det være svært at se farvetemaet, men måske derfor endnu vigtigere at være klar i sit valg. Man kan bruge Chrome extension, **colorZilla** til at undersøge RGB og HSL værdierne.

### Øvelse
Undersøg følgende websider for deres farvevalg, hvad har de valgt og hvordan virker det. Er siderne konsekvente i deres valg og kan man bruge farveteorien med farvetemaer til at forstå dem.
* [Facebook](https://www.facebook.com/)
* [Danske bank](https://danskebank.dk/privat)
* [Bonbonland](https://www.bonbonland.dk/)
* [Tivoli](https://www.tivoli.dk)
* [Rysensteen](https://rysensteen.dk)
* Find et par stykker selv.


## RGB farver
Vores computerskærme er bygget op med pixels som kan udsende lys med farverne, rød, grøn og blå. Det kaldes RGB farver og svarer til de tre receptorer i øjet, tappene, som netop også kan se rødt, grønt og blåt lys. Hvis vi vil sætte baggrundsfarvent til blå skal vi i html skrive,
```background: rgb(0,0,255)```
mens gul skærm er en blanding af grøn og rød.
```background: rgb(255,255,0)```
Kombinationen af de tre farver giver omkring 17 milloner farvemulighedermuligheder. Farverne kommer af at vores hjerne fortolker signalet fra receptorerne til eks. at give orange hvis vi modtager signal mest rød og lidt grøn men intet signal fra de blå receptorer. Her er en meget kort introduktion til farver på en computerskærm, [Farver på en computerskærm](https://www.chem.purdue.edu/gchelp/cchem/RGBColors/body_rgbcolors.html#:~:text=A%20monitor%20or%20TV%20screen,surrounded%20by%20a%20black%20mask.).

## HSL farver
Man har udviklet mange andre måder at beskrive farver på end RGB. En er HSL som står for Hue, Saturation og Lightness. Her vælger man farven, H, hvor mættet den skal være, S og hvor lys den skal være L. Det giver en mere naturlig tilgang til at vælge og ændrer farver. Hvis man vil gøre en farve mere støvet skruer man op for Saturation og skal den være mørkere skruer man ned for Lightness. Der er en direkte oversættelse mellem HSL og RGB og man kan bruge begge i html kode. HSL visualiseres med farvehjulet og farven H går fra 0-360, mens S og L går fra 0-100. W3schools har et simpelt værktøj til at afprøve HSL farver, [html_colors_hsl](https://www.w3schools.com/html/html_colors_hsl.asp).

 ### Øvelse
 * Eksperimenter med farverne på, [html_colors_hsl](https://www.w3schools.com/html/html_colors_hsl.asp) ved hjælp af skyderne.
 * Prøv et eksempel hvor du redigere i html koden.

### Øvelse, farver og CSS
Det er bedst at holde styling delen til en separat fil, eks. ```styles.css```. På den måde bliver det mere overskueligt hvor styling er og hvor indholdet er. Hvis man har flere undersider kan man henvise til samme ```.css``` fil og der er kun ét sted man skal ændre for at hele hjemmesiden ændrer sig.

Hvis ```.css```filen ligger i samme mappe som ```.html``` filerne skal man henvise til filen i headeres,
```
<head>
<link rel="stylesheet" href="styles.css">
</head>
```

Selv om det ikke er anbefalet så skal I nu arbejde med én fil hvor styling og indhold ligger sammen. I skal arbejde med siden, [farverCSS1.html](/introduktion/farverCSS1.html).
* Gem siden lokalt og åben den i browseren.
* Hvilke problemer er der?
* Se i koden og find det i ```<style></style>``` taggene.
* Vælg et farvetema og implementer det.
* Tilføj en farve til underoverskriften ```h1```.

 ## Farver på jeres webside
 I skal vælge et farvetema for jeres egen webside. Overvej hvem I vil kommunikerer til og hvad I gerne vil signalerer og vælg et farvetema som I kan bruge i implementeringen.

## Links
* [additive og substractive farver](http://mpsteenstrup.dk/farveblanding_js/farveblanding_js.html)
*[temavælger](https://coolors.co/d62839-ba324f-175676-4ba3c3-cce6f4)
