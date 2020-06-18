# Teori 2

###  1.  Vad är skillnaden mellan backend och databas? Beskriv vad respektive ansvarar för.
Backend är kombinationen av en server applikation och en databas.

Medans databasen sköter all data för din backend, som t.ex. en Användarlista eller en varulista.

###  2. Varför är det viktigt att vara konsekvent i sin API-design för att skapa ett användarvänligt API?
    
Därför att det ska vara snabbt och enkelt att jobba med, så att du inte ska behöva slösa onödig tid på att hitta resurser och vart allting ligger.

Samt att du ska kunna återanvända kod på andra ställen i ditt API.


###  3. Vad är autentisering vs. auktorisering?
Autentisering är att du verifierar att du är du, eller i detta fall att en användare är en viss person. I detta fall kan det vara att användaren är Oscar.

Medans auktorisering är om du har vissa rättigheter. Som t.ex. en roll. Denna roll kan vara t.ex. Admin.

###  4. Vad är skillnaden mellan "Private Cloud" och "Public Cloud". Vilka typer av tjänster erbjuder public cloud?
**Private Cloud:**
Ägs och används exklusivt utav ett företag eller en organisation.

*Fördelar:*
-   Mer flexibelt, din organisation kan ändra sitt cloud beroende på vad företaget har för behov.
    
-   Högre säkerhet. Eftersom att företaget är de enda som har tillgång till resurserna. Vilket även ger dig högre kontroll.
    
-   Hög skalbarhet. Även om du har private cloud så kan du fortfarande ha samma skalbarhet och effektivitet som ett public cloud.
    
**Public Cloud:**
Ägs och opereras av en third party service provider och levereras över nätet.

*Fördelar:*

-   Lägre kostnader, du betalar endast för servicen du köpt.
    
-   Ingen maintenance - din provider sköter det åt dig.
    
-   Nästintill oändlig skalbarhet.
    
-   Hög pålitlighet.

*Vilka typer av tjänster erbjuder public cloud?*
Olika typer av tjänster som public cloud kan erbjuda är att bl.a:
-   Spara data och filer.
-   Visa filer dynamiskt på en sida.
-   Information och Applikationer(t.ex. google docs/drive, gmail)
###  5. Varför testar vi mjukvara?
Varför det är viktigt att testa mjukvara är därför att vi ska kunna identifiera och hitta fel. Vilket ska i sin tur leda till en ökad produkt kvalité utan fel som våra användare kan njuta av utan frustration.

Med test kan vi även öka säkerheten och försöka “bryta ner” vår mjukvara och hitta svaga punkter som vi kan motarbeta senare för att få en ökad säkerhet på vår produkt.

###  6. Vad är fördelarna med API:er jämfört med en webblösning som går direkt mot en databas?

API:n sätter regler på vad som kan göras mot din databas. Om du strukturerar upp allting genom att ha en applikation och sedan ett API mot din databas så är allting mer agilt och strukturerat. Vilket gör att du senare kan återanvända din kod i framtiden, men även enkelt kunna ändra, flytta och byta kod smidigare ifall någonting behöver fixas. Det sparar dig även tid och ger dig mer scalability.

###  7. Vad innebär OAUTH?
OAUTH är ett säkert sätt att låta andra komma åt och skapa data åt dig. Ett exempel är att du kan logga in med gmail eller facebook på vissa sidor. Vad OAUTH då gör är att om jag loggar in med Facebook och sedan blir example.com hackad, så kommer inte min Facebook information att läckas ut. Alltså dem kan inte komma åt den datan eftersom att de har bara tillgång till min Facebook men inte den vitala informationen som t.ex. mitt lösenord etc.

###  8. Vilka typer av managed services erbjuds av Public Cloud och vad innebär de?

De finns fyra olika services och de är:

**On Premises:** är att du äger allting från infrastruktur, till plattform och mjukvara.

**Infrastruktur:** är att du äger infrastrukturen, men du outsourcar servern till public cloud. Du betalar alltså någon för att ha din server och fixa allting däremellan.

**Plattform:** är att du äger mjukvaran och outsourcar basically allting annat som kan tänkas använda public cloud i din produkt. Med detta kan du då fokusera på att endast utveckla din applikation och din provider sköter allt däremellan.

**Software:** Du outsourcar allting, även din applikation(mjukvaran) till **public cloud.** T.ex. Gmail. Du använder produkten, men du jobbar inte på eller för Gmail.

###  9. Vad innebär TDD och BDD?

**Test Driven Development:** är att du programmerar med att du skriver testerna först, och sedan bygger själva projektet. Alltså du får inte börja koda förens testerna är klara.

Så ett exempel på hur man gör TDD Cykeln kan vara:
*1.  Skriv ett test.*
*2.  Få det att fungera.*
*3.  Ändra koden så att det blir “rätt”.*
*4.  Börja om cykeln.*

**Behavior Driven Development:** Kan nyttja agila projektmetoder under development och testing.

Testerna ska vara skrivna i ett språk så att folk ska kunna förstå vad det innebär och vad det står.

BDD gör sammanhållningen mellan användare, produktutvecklare, produktägare och shareholders enkel och smidig. Så att alla förstår vad som ska hända och vad/hur features ska fungera. T.ex. du identifierar features som är viktiga och skriver ner dem. Sedan skapar du user scenarios för dessa features. Skriver ner tydliga steg för varje scenario och sedan försöker koda detta och gör det tills det funkar som det ska.

*Ett bra exempelschema på hur ett scenario ser ut är:*

**As [role]
I want [feature]
So that [benefit/business reason]**


