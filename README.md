# Viström

## Frågor att besvara

#### Varför är det generellt en bra idé att placera CSS \<link>s mellan \<head>\</head> och JS \<script>s precis innan \</body>? Känner du till några undantag?
CCS läggs mellan head för att ladda stylen innan den börjar rendera html elementen. Man undivker en blank laddningssida samt att webbläsaren inte behöver rendera om element.

Scriptet läggs precis innan \</body> för att det ska ladda in Javascripten sist, annars kan det upplevas som väldigt slött om man har mycket Javascript och det laddas in före html & css.

Nej jag känner inte till några undantag.

#### Beskriv skillnaderna mellan en cookie, sessionStorage och localStorage.
Storage är mer till för klientsidan där sessionStorage endast sparar data för pågående session och localStorage sparar data utan utgångsdatum och försvinner först när man rensar cachen.
Cookies sparas för att snabba upp kommunikationen mellan klient och server och har alltid ett bäst före datum där dom raderas.

#### Kan du förklara skillnaden mellan att koda en webbplats för att vara responsiv i jämförelse med att använda en mobile-first-strategi?
Responsiv så börjar man med maxupplösningen för att jobba sig nedåt i skärmstorlek och tvärtom för mobile-first.
Jag kan tänka mig att mobilversionen inte blir helt optimerade vid responsiv design och desktopversioner lite lidande vid mobile-first.

#### Om du vill kolla hur en viss funktions (t.ex. CSS Flexible Box Layout) stöd ser ut i olika webbläsare, vilken tjänst använder du?
Vet ej, aldrig provat men ett cross browser testing verktyg kanske? :)

#### När det kommer till styling med CSS så ska du inte använda ID’n som selektorer. Redogör gärna varför, och varför det är bättre att använda klasser istället.
Generellt sett är väl ID'n till för att märka endast ett element medans klasser kan användas till en eller flera.

#### Vissa bildfiler är i “fel” filformat. Byt gärna filformat till det du anser är bäst samt redogör varför.

