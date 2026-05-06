# Reflectie Minor Web API

## Dagelijkse vragen

**Wat heb ik vandaag gedaan:**<br>
**Wat heb ik geleerd:**<br>
**Wat ga ik morgen doen:**<br>

---

## Week 1

### Woensdag 1 april 
**Wat heb ik vandaag gedaan:**<br>
Vandaag hebben de opdracht voor het API vak uit gelegd gekregen. Daarna hebben we een workshop over Astro gevolgd. Daarna had ik een idee bedacht voor de opdracht en gekeken naar welke API's ik daarvoor kan gebruiken. <br>
Het idee van mijn website is een soort film trivia. Je krijgt films uit de tmbd database te zien (voor nu) kan je met een multiple choice kiezen welk antwoord goed is. Ook wil ik gebruik maken van de Spotif API voor geluidsfragmenten. Verder wil ik gebruik maken van de web share API en de canvas API, voor het maken van een score kaart die je dan kan delen. <br>
Op dit moment heb ik met math random dat er verschillend film posters en namen (< voor de buttons) worden opgehaald. Cyd had aangegeven ik het met de websocket api interactief kan maken voor meerdere gebruikers. CSS quiz?!?

**Wat heb ik geleerd:**<br>
Over Astro en over hoeveel verschillend API's. Ook over het verschil van server side rendering vs client side rendering.

**Wat ga ik morgen doen:**<br>
Morgen ga ik mijn concept presenten en verder werken aan de opdracht.

---

### Donderdag 2 april
**Wat heb ik vandaag gedaan:**<br>
Ik heb mijn concept gepresenteerd, maar ik ben er nog niet helemaal onder uit wat ik van het concept vind. 
**Wat heb ik geleerd:**<br>
**Wat ga ik morgen doen:**<br>
Verder werken aan de opdracht en kijken welke apis misschien wel beter erin passen


---

## weekly nerd

Rosa 

Hackers United 

Planned obsolescene, je komt steeds slechter in je apparaten dit zorgt voor grotere afhankelijkheid  
- afhankelijk van amerikaanse big teck
Cloud is de plek om je website op te hosten, je hebt er geen invloed op

EEn server is een computer en een router die informatie opslat op afstand en naar de gebruiker stuurt

- node9.org, eco driven server

static side generators
- minder impact op de server
- if all fails is er nog een markdown
- leesbare code
- 11ty

Met een eigen server zelf hosten van
- git
- messaging platform 
-  je eigen websties

diy!DIWO
- elke donderdag avond
- lag social evening vrijdagavond

---

## Reflectie week 1 API

Tijdens de eerste week van het API vak heb ik vooral kennisgemaakt met de opdracht en onderzocht welke richting ik op wilde gaan met mijn project. Op woensdag kregen we eerst uitleg over de opdracht en wat er van ons verwacht werd. Daarna volgde een workshop over Astro. Hier leerde ik meer over hoe Astro werkt en wat de voordelen zijn van server-side rendering en client-side rendering. Dit gaf mij meer inzicht in hoe websites data kunnen ophalen en tonen.

Na de workshop begon ik met brainstormen over een concept. Mijn eerste idee was een film trivia website waarbij gebruikers vragen kregen over films. Ik wilde films uit de TMDb API gebruiken en spelers via multiple choice vragen het juiste antwoord laten kiezen. Daarnaast wilde ik de Spotify API gebruiken voor geluidsfragmenten van films of soundtracks. Ook leek het me leuk om de Web Share API en Canvas API te gebruiken zodat gebruikers een scorekaart konden genereren en delen.

Ik ben direct gaan experimenteren en kreeg het al werkend dat willekeurige filmposters en filmtitels werden opgehaald met Math.random(). Toch begon ik tijdens het testen te twijfelen aan dit concept. Ik merkte dat het idee vooral draaide om quizmechanieken en minder om het op een interessante manier gebruiken van APIs. Daarnaast was ik afhankelijk van meerdere externe APIs die niet allemaal even makkelijk toegankelijk waren. Vooral de combinatie met Spotify voelde geforceerd en maakte het concept ingewikkelder dan nodig.

Tijdens feedback kreeg ik ook de suggestie om eventueel WebSockets toe te voegen voor multiplayer functionaliteit. Hoewel dit technisch interessant klonk, besefte ik dat dit het project nog groter en complexer zou maken terwijl de basis van het concept nog niet sterk genoeg voelde.

Na mijn presentatie op donderdag werd voor mij duidelijk dat het concept wel leuk was, maar niet uniek genoeg voelde en dat de APIs vooral losse toevoegingen waren in plaats van een logisch geheel. Daarom besloot ik verder te kijken naar een concept waarbij de APIs centraler zouden staan in de ervaring van de gebruiker.

---
## Week 2

### Woensdag 8 april met mats en melvin

**Wat heb ik vandaag gedaan:**<br>
Vandaag heb de workshop Dynamic paging gevolgd. Daarna ben ik verder gegaan aan mijn concept. Ik heb nu de geolocation en osm erin gezet met leaflet.

**Wat heb ik geleerd:**<br>
Hoe ik repeatable components kan maken in astro. En functies met boolean true false

**Wat ga ik morgen doen:**<br>
Proberen de locaties zoals bij google maps

weather api toevoegen?? 

---

### donderdag 9 april
**Wat heb ik vandaag gedaan:**<br>
Een nieuw concept bedacht voor de website met welke apis ik wil gebruiken en daar heb ik een begin aan gemaakt
**Wat heb ik geleerd:**<br>
-
**Wat ga ik morgen doen:**<br>
Feedback gesprekken en verder werken aan de website

### Weekly nerd Johan

"Je gaat het pas zien als je het doorhebt" En, je hoort hert pas als je luistert

- percveivable
- operable
- understandable
- robust

WCAG is een handig hulpmiddel maar neit de enige die jehebt om oieys toeganklijk te maken
leg het voor aan echte mensen 

geen alt tekst bij een afbeelding als het niet noodzakelijk is voor de website. het moet wel een alt attr mar het mag leeg zijn

laat je informeren door iemand die al een schermlezer gebruikt, ipv onnodige aanpassingen maken, er zijn bijv. toesenbord combis die al in een screenreader zitten zoals het navigeren naar alleen koppen

wat maakt het moeilijk
- martijn: Hij kan bijna niks zien, knoppen die nier een andere weegave hebben als ze erop zit, cookie meldingen waarbij je niet kan scrollen, slecht contrast, captcha

- nauduah: ze heeft niet veel mobiliteit, velle kleuren op website, veel info doorelkaar alles in een keer geen concentratie, heel lang moten zokeen naar wat ze nodig heeft. 

- guido: heeft autisme, visuele en audio prikkels alles komt extra hard binnen hij kan dit niet filteren. bijv. luide advertenties. de teksinterpretatie moeten concreet zijn zodat hij exact weet wat hij daar moet invullen. als er teveel info staat haakt hij al af.
wat heeft persoon nodig
- martijn: tekst moet kort en duidelijk, schaalbaarheid, contrast ,info bij elkaar, visuele indicator zoals focusrand

- nauduah: duidelijke informatie bij elkaar, website die visueel toeganklijk zijn dus geen felle kleuren/laag contrast.  gegevens keunnen bewaren, donkere modus, 

- guido: niet teveel onnnodige dingen op de website , voorspelbaarheid, duidelijke instructies, rustige layout en vormgeving

eigen project waarom zou persoon afhaken
- martijn: 

---
## week 2 reflectie 

Tijdens week 2 ben ik verder gegaan met het ontwikkelen van mijn concept, maar merkte ik opnieuw dat mijn ideeën nog niet helemaal goed aansloten bij wat ik wilde maken.

Op woensdag volgde ik eerst de workshop over dynamic paging in Astro. Tijdens deze workshop leerde ik hoe ik repeatable components kan maken en hoe ik functies met boolean waarden (true en false) kan gebruiken om content dynamisch te tonen.

Na de workshop begon ik te experimenteren met geolocation en Leaflet in combinatie met OpenStreetMap. Ik vond het interessant om locatiegegevens te gebruiken en wilde kijken of ik iets kon maken dat leek op een interactieve kaart, vergelijkbaar met Google Maps. Hierdoor stapte ik eigenlijk al verder weg van mijn filmconcept.

Hoewel dit tweede idee technisch interessanter voelde dan de filmquiz, liep ik ook hier tegen problemen aan. Het concept begon erg te lijken op bestaande map-applicaties en ik merkte dat ik nog niet echt een unieke invalshoek had. Ik gebruikte geolocation vooral omdat het technisch leuk was, maar nog niet omdat het inhoudelijk iets toevoegde aan een duidelijk concept. Daardoor voelde het alsof ik opnieuw technologie centraal zette in plaats van de gebruikerservaring.

Op donderdag besloot ik daarom opnieuw kritisch naar mijn project te kijken. Ik wilde een concept ontwikkelen waarbij de APIs niet als losse features aanvoelden, maar echt onderdeel waren van het eindproduct. Dit was frustrerend, omdat het voelde alsof ik opnieuw begon, maar achteraf was dit een belangrijke stap.

Tijdens de feedbackgesprekken werd duidelijk dat ik nog aan het zoeken was naar een concept dat zowel technisch uitdagend als inhoudelijk sterk was. Deze zoektocht leidde uiteindelijk later naar The Space Above, een concept waarin locatiegegevens en API-data veel logischer samenkwamen.



---

## Week 3
Deze week was een rommelige week. Hier had in de smashing conference. Wel was ik begonnen aan het nieuwe concept The Space Above, alleen heb ik het begin ervan niet heel goed gedocumenteerd.

---

## Week 4

### donderdag 23 april Jelle


**Wat heb ik vandaag gedaan:**<br>
Ik heb gewerkt aan de styling van de website. Ook hebben ik (met hulp van claude) de zenith arc svg erin gekregen. Verder heb ik de geolocation gebonden aan de api zodat hij echt de coords van de gebruiker pakt, en de URL: searchParams gebruikt om het op te slaan. Daarna ben ik begonnen aan de detail pagina

**Wat heb ik geleerd:**<br>
Over hoe ik de geolocation api werkend krijg, de params

**Wat ga ik morgen doen:**<br>
(In de vakantie) De details pagina afkrijgen. Ik wil van de cards op de eerste pagina flipping cards maken met de info over wat bepaalde dingen betekenen. Als detail pagina wil ik een andere api gebruiken om afbeeldingen van de maan in haar staat.

**TODO**
Andere locaties (coordinaties API), compare naast elkaar doen?, zenith op elkaar?!?!
favicon toevoegen?? 


---

## Reflectie week 4
Week 4 voelde een stuk productiever dan week 3. Omdat week 3 rommelig verliep door de Smashing Conference, had ik minder voortgang geboekt en ook niet alles goed gedocumenteerd. Hierdoor wilde ik deze week vooral weer structuur krijgen en concrete stappen zetten binnen mijn project The Space Above.

Op donderdag ben ik verder gegaan met de ontwikkeling van mijn website. Ik heb gewerkt aan de styling en geprobeerd de visuele kant sterker te maken zodat het concept beter overkomt. Een onderdeel waar ik tegenaan liep was het toevoegen van de zenith arc SVG. Dit lukte uiteindelijk met hulp van Claude, waardoor ik beter begreep hoe ik complexere SVG-elementen kan implementeren binnen mijn project.

Daarnaast heb ik grote stappen gezet met de geolocation functionaliteit. Eerst werkte mijn website nog met vaste coördinaten, maar deze week heb ik ervoor gezorgd dat de website daadwerkelijk de locatie van de gebruiker kan ophalen via de Geolocation API. Vervolgens heb ik deze gegevens opgeslagen met URLSearchParams, zodat de coördinaten meegenomen kunnen worden naar andere pagina’s. Hierdoor werd mijn project een stuk dynamischer en persoonlijker voor de gebruiker.

Ook ben ik gestart met het bouwen van de detailpagina. Op deze pagina wil ik extra informatie tonen over hemelobjecten en mogelijk een andere API gebruiken om afbeeldingen van de maan te laten zien op basis van haar huidige fase. Daarnaast wil ik de kaarten op de homepage interactiever maken door ze om te zetten naar flip cards, zodat gebruikers extra uitleg kunnen krijgen over bepaalde termen of astronomische gegevens.

Wat ik deze week vooral heb geleerd, is hoe belangrijk het is om verschillende onderdelen stap voor stap op te bouwen. Eerst voelde het project nog erg groot en onoverzichtelijk, maar door kleine onderdelen zoals geolocation en URL parameters één voor één op te lossen, werd het project steeds concreter.

Mijn project begint nu steeds meer samen te komen en ik zie duidelijker hoe alle API’s en interacties uiteindelijk één geheel kunnen vormen. In de vakantie wil ik de detailpagina verder afmaken en de interactieve onderdelen van de homepage verbeteren.

---

## week 5

### Woensdag 6 mei

Vandaag ben ik bezig geweest met het afronden van de website voor de deadline. In de vakantie heb ik nog gewerkt aan de styling en heb ik de pagina voor het vergelijken toegevoegd.


**TODO**
logo
add button
waarom niet andere concepten

---

## Reflectie overall

Aan het begin van het vak had ik moeite met het vinden van een concept dat echt klopte. Mijn eerste idee was een film trivia website waarbij gebruikers via multiple choice vragen konden beantwoorden over films uit de TMDb API. Ik wilde hier ook de Spotify API aan koppelen voor geluidsfragmenten en de Canvas API gebruiken om een deelbare scorekaart te genereren. Hoewel ik enthousiast begon en al snel werkende code had met willekeurige filmposters via Math.random(), begon ik al snel te twijfelen. De APIs voelden als losse toevoegingen die niet echt met elkaar samenhingen. Het concept draaide meer om het quizmechanisme dan om een interessante of betekenisvolle gebruikerservaring. Na de presentatie op donderdag werd dit voor mij bevestigd en besloot ik het idee los te laten.

Mijn tweede richting was een interactieve kaart met geolocation en Leaflet in combinatie met OpenStreetMap. Dit voelde technisch een stuk interessanter en ik leerde hoe ik locatiegegevens kon gebruiken binnen een webapplicatie. Toch liep ik ook hier tegen een muur op. Het concept begon te veel te lijken op bestaande kaartapplicaties zoals Google Maps en ik had nog geen unieke invalshoek gevonden. Ik gebruikte geolocation puur omdat het technisch leuk was, maar niet omdat het inhoudelijk iets toevoegde aan een duidelijk verhaal. Ook dit idee liet ik los.

Na twee concepten die niet werkten, besloot ik fundamenteel anders te denken. In plaats van te beginnen bij de technologie, wilde ik beginnen bij een vraag die ik zelf interessant vond: wat gebeurt er eigenlijk boven je hoofd op dit moment? Dit leidde tot The Space Above, een website die op basis van je locatie laat zien wat er astronomisch gezien boven je afspeelt. De zon en maan worden visueel weergegeven in een SVG arc diagram, je ziet de exacte tijden van zonsopgang en zonsondergang, de maanfase met een bijpassende SVG illustratie, en je kunt locaties vergelijken met elkaar.

Wat dit concept sterk maakte was dat alle onderdelen logisch met elkaar samenhingen. De Geolocation API geeft de coördinaten van de gebruiker, die worden via URLSearchParams doorgegeven aan de ipgeolocation Astronomy API die de astronomische data teruggeeft, de Open-Meteo Geocoding API zorgt dat gebruikers ook op steden kunnen zoeken, en de Big Data Cloud API zet coördinaten terug om naar een stadsnaam. Alles had een functie en droeg bij aan de ervaring.

Het werken met APIs vond ik over het algemeen erg interessant. Het idee dat je met een paar regels code live data van buiten je eigen applicatie kunt ophalen en direct kunt weergeven voor de gebruiker vond ik fascinerend. Elke API heeft zijn eigen structuur, documentatie en manier van authenticeren, en het uitzoeken hoe je die data precies kunt opvragen en verwerken gaf me elke keer een voldaan gevoel als het eenmaal werkte. Tegelijkertijd was het ook regelmatig moeilijk. Soms begreep ik de documentatie niet goed genoeg, waren de response objecten complex of werkte authenticatie anders dan verwacht. Het begrijpen van concepten zoals asynchrone code, promises en het verschil tussen server-side en client-side fetching vroeg veel van me. Zeker in het begin was het soms lastig om te begrijpen waarom iets niet werkte en waar het precies misging.

Technisch heb ik in dit project veel nieuwe dingen geleerd. Het werken met URLSearchParams om data tussen pagina's door te geven was voor mij nieuw en opende een manier van denken over hoe je state kunt bewaren zonder een backend. Het koppelen van de Geolocation API aan een externe API via een redirect op de URL was een elegante oplossing voor een probleem dat ik in het begin te ingewikkeld vond. Ook het werken met SVG voor de zenith arc en de maanfase was iets wat ik nog nooit eerder had gedaan. Het berekenen van de positie van de zon en maan op basis van azimuth en altitude en dit omzetten naar coördinaten in een SVG viewBox gaf me inzicht in hoe wiskundige berekeningen en visuele output samen kunnen werken.

---

# Bronnen
- 1 Gebruikte apis: 
    ipgeolocation https://ipgeolocation.io/documentation/astronomy-api.html
    Big Data Cloud https://www.bigdatacloud.com/free-api/free-reverse-geocode-to-city-api
    Open-Meteo https://open-meteo.com/en/docs/geocoding-api
 
- 2 Favicon: can you generate an image that would be nice for the favicon


    Claude responded: I can make you an SVG favicon that fits your space theme perfectly — SVGs work as favicons and need no external tools:

    Add this file as public/favicon.svg:

    svg
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
    <circle cx="16" cy="16" r="16" fill="#060812"/>
    
    <circle cx="6"  cy="7"  r="0.8" fill="white" opacity="0.8"/>
    <circle cx="24" cy="5"  r="0.6" fill="white" opacity="0.6"/>
    <circle cx="28" cy="12" r="0.8" fill="white" opacity="0.7"/>
    <circle cx="4"  cy="20" r="0.6" fill="white" opacity="0.5"/>
    <circle cx="26" cy="24" r="0.7" fill="white" opacity="0.6"/>
    <circle cx="10" cy="26" r="0.5" fill="white" opacity="0.4"/>

    <line x1="4" y1="22" x2="28" y2="22" stroke="rgba(120,160,255,0.4)" stroke-width="0.8"/>
    <path d="M 4 22 A 12 12 0 0 1 28 22" fill="none" stroke="rgba(245,199,106,0.4)" stroke-width="0.8" stroke-dasharray="2 2"/>

    <circle cx="20" cy="14" r="3" fill="rgba(245,199,106,0.9)"/>

    <circle cx="10" cy="16" r="3" fill="rgba(200,216,248,0.85)"/>
    <circle cx="11.5" cy="16" r="2.4" fill="#060812"/>
    </svg>
    Then link it in your <head> on both pages:

    astro
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    It shows the arc diagram with a little sun and crescent moon — matches your site perfectly.



- 3 encodeURIComponent
    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURIComponent

- 4 Geolocation
    https://www.youtube.com/watch?v=KIQShH4b_oQ

- 5 Params
    https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams

- 6 Parralel fetching
    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all

- 7 Flipcard cyd
    https://codepen.io/Sidstumple/pen/ByjXVLw?editors=1100

- 8 Moon phase svg 
    is there a way to add an svg of the moon in its phase based the api data 

        <div class="card">
            <p class="card-title">Moon Phase</p>
            <p class="card-main">{sky.moon_phase.replace("_"," ")}</p>
            <p class="card-sub">{sky.moon_illumination_percentage}% illuminated</p>
            <p class="card-sub">Moonrise {sky.moonrise} · Moonset {sky.moonset}</p>
        </div>
    13:25
    Claude responded: Yes — you can draw it with pure SVG math based on the illumination percentage and whether it's waxing or waning.
    Yes — you can draw it with pure SVG math based on the illumination percentage and whether it's waxing or waning. Add this to your frontmatter:

    astro
    // calculate moon phase SVG shadow offset
    const illumination = sky ? Math.abs(parseFloat(sky.moon_illumination_percentage)) / 100 : 0;
    const isWaning = sky?.moon_phase?.toLowerCase().includes('waning') || sky?.moon_phase?.toLowerCase().includes('last');
    const shadowX = isWaning
    ? 22 - (illumination * 44)
    : (illumination * 44) - 22;
    Then in your card:

    astro
    <div class="card">
    <svg viewBox="0 0 44 44" width="48" height="48" style="margin-bottom:10px">
        <defs>
        <clipPath id="moon-clip">
            <circle cx="22" cy="22" r="20"/>
        </clipPath>
        </defs>
        <!-- moon disc -->
        <circle cx="22" cy="22" r="20" fill="rgba(200,216,248,0.15)" stroke="rgba(200,216,248,0.3)" stroke-width="0.5"/>
        <!-- lit part -->
        <circle cx="22" cy="22" r="20" fill="rgba(200,216,248,0.75)" clip-path="url(#moon-clip)"/>
        <!-- shadow overlay -->
        <circle cx={22 + shadowX} cy="22" r="20" fill="#060812" clip-path="url(#moon-clip)"/>
    </svg>
    <p class="card-title">Moon Phase</p>
    <p class="card-main">{sky.moon_phase.replace("_", " ")}</p>
    <p class="card-sub">{Math.round(Math.abs(sky.moon_illumination_percentage))}% illuminated</p>
    <p class="card-sub">Moonrise {sky.moonrise} · Moonset {sky.moonset}</p>
    </div>

- 9 Zenith Arc
    I have an SVG arc diagram showing sun and moon positions. The viewBox is 300x160, the horizon line is at y=145, and positions are calculated by mapping azimuth to x (east=10, west=290) and altitude to y (0°=145, 90°=10). How do I draw a vertical dotted line from the horizon to the zenith point, and what x coordinate should it be at?. Using the ipgeoloction api

    Claude responded: Add this to you frontmatter:
    let sunX = 150, sunY = 145, moonX = 150, moonY = 145;
    let sunOpacity = '0', moonOpacity = '0';
    let arcNote = '';

    if (sky) {
    const toXY = (alt, az) => {
        const x = 10 + ((parseFloat(az) - 60) / 240) * 280;
        const y = 145 - (Math.max(0, parseFloat(alt)) / 90) * 135;
        return { x: Math.max(10, Math.min(290, x)), y: Math.max(10, Math.min(145, y)) };
    };

    const sun  = toXY(sky.sun_altitude,  sky.sun_azimuth);
    const moon = toXY(sky.moon_altitude, sky.moon_azimuth);

    sunX  = sun.x;  sunY  = sun.y;
    moonX = moon.x; moonY = moon.y;

    sunOpacity  = parseFloat(sky.sun_altitude)  > 0 ? '1' : '0.25';
    moonOpacity = parseFloat(sky.moon_altitude) > 0 ? '1' : '0.25';

    arcNote =
        (parseFloat(sky.sun_altitude)  > 0 ? `Sun ${parseFloat(sky.sun_altitude).toFixed(1)}° above horizon`  : 'Sun below horizon') +
        '  ·  ' +
        (parseFloat(sky.moon_altitude) > 0 ? `Moon ${parseFloat(sky.moon_altitude).toFixed(1)}° above horizon` : 'Moon below horizon');
    }

    Add this to your index.astro:
    <div>
    <p class="arc-label">Sky Arc</p>
    <svg viewBox="0 0 300 160" style="width:100%;display:block;overflow:visible">
        <line x1="10" y1="145" x2="290" y2="145" stroke="rgba(120,160,255,0.50)" stroke-width="1"/>
        <path d="M 10 145 A 140 140 0 0 1 290 145" fill="none" stroke="rgba(245,199,106,0.50)" stroke-width="1" stroke-dasharray="4 4"/>
        <text x="6"   y="155" font-family="Space Mono" font-size="9" fill="rgba(120,160,255,0.4)">E</text>
        <text x="148" y="16"  font-family="Space Mono" font-size="9" fill="rgba(120,160,255,0.4)" text-anchor="middle">Zenith</text>
        <text x="286" y="155" font-family="Space Mono" font-size="9" fill="rgba(120,160,255,0.4)" text-anchor="end">W</text>
        <circle cx={city.sunX}  cy={city.sunY}      r="8" fill="rgba(245,199,106,0.8)" opacity={city.sunOpacity}/>
        <text   x={city.sunX}   y={city.sunY - 12}  font-family="Space Mono" font-size="8" fill="#f5c76a" text-anchor="middle" opacity={city.sunOpacity}>Sun</text>
        <circle cx={city.moonX} cy={city.moonY}     r="6" fill="rgba(200,216,248,0.7)" opacity={city.moonOpacity}/>
        <text   x={city.moonX}  y={city.moonY - 10} font-family="Space Mono" font-size="8" fill="#c8d8f8" text-anchor="middle" opacity={city.moonOpacity}>Moon</text>
    </svg>
    <p class="arc-note">{city.arcNote}</p>
    </div>

