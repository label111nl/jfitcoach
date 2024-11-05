# Webapp Directory voor Personal Trainers en Coaches

## Project Samenvatting
Dit project heeft als doel het ontwikkelen van een gebruiksvriendelijke webapplicatie die fungeert als een directory voor personal trainers en coaches. De applicatie stelt trainers in staat om eenvoudig hun eigen content te beheren, waaronder recepten, blogs en workouts, terwijl gebruikers toegang krijgen tot waardevolle informatie over zowel fysieke als mentale gezondheid.

## Technologieën
- **Frontend**: Svelte met Nucleus Design
- **Backend**: Directus als headless CMS

## Architectuur Overzicht
### Frontend (Svelte met Nucleus Design)
- Svelte wordt gebruikt om een dynamische en responsieve gebruikersinterface te creëren die gericht is op een soepele gebruikerservaring.
- Nucleus Design zorgt voor een moderne, consistente visuele uitstraling van de applicatie, met focus op gebruiksvriendelijkheid en esthetiek.
- De frontend maakt gebruik van een component-gebaseerde architectuur, wat het onderhoud en de uitbreiding vergemakkelijkt.

### Backend (Directus)
- Directus fungeert als een headless CMS dat verbinding maakt met een SQL-database (zoals MySQL of PostgreSQL) om content te beheren.
- Trainers kunnen eenvoudig hun content beheren via de gebruiksvriendelijke admin interface van Directus, inclusief de mogelijkheid om nieuwe recepten, blogs en workouts toe te voegen.
- Directus biedt real-time API's voor zowel REST als GraphQL, wat zorgt voor een flexibele en krachtige manier om data te ophalen en te manipuleren.

## Functionaliteiten
### Dashboard voor Trainers
- Gepersonaliseerd dashboard voor trainers om hun content te beheren.
- Mogelijkheid om recepten, blogs en workouts toe te voegen, te bewerken en te verwijderen.
- Statistieken en inzichten over de prestaties van hun content.

### Content Creatie
- Eenvoudige interface voor het toevoegen van recepten met ingrediënten, bereidingsstappen en voedingsinformatie.
- Trainers kunnen blogs schrijven over gezondheidsgerelateerde onderwerpen en trainingstips.
- Workouts kunnen worden toegevoegd met gedetailleerde beschrijvingen, sets en herhalingen.

### SEO Optimalisatie
- De structuur van de applicatie is geoptimaliseerd voor zoekmachines, waardoor trainers hun blogs en pagina's gemakkelijk kunnen toevoegen en beheren voor betere online zichtbaarheid.

## Voordelen van deze Aanpak
- **Gebruiksvriendelijkheid**: De combinatie van Svelte en Nucleus Design biedt een aantrekkelijke en intuïtieve gebruikersinterface, wat het eenvoudig maakt voor trainers om content te beheren zonder technische kennis.
- **Flexibiliteit**: Directus maakt het mogelijk om bestaande databases te gebruiken en biedt de mogelijkheid om content aan te passen aan de behoeften van de gebruikers.
- **Snelle Ontwikkeling**: Dankzij de combinatie van Svelte en Directus kan de ontwikkeling snel plaatsvinden, wat resulteert in een kortere time-to-market.

## Mogelijke Uitdagingen
- **Integratie**: Het kan enige tijd duren om Svelte en Directus naadloos met elkaar te integreren, vooral bij het opzetten van de API-communicatie.
- **Beheer van Gegevens**: Het effectief beheren van de gegevensstructuur in Directus kan aanvankelijk complex zijn, afhankelijk van de behoeften van de applicatie.

## Installatie
Volg de onderstaande stappen om het project lokaal te installeren en uit te voeren:

### Voorwaarden
- Zorg ervoor dat je [Node.js](https://nodejs.org/) en [Docker](https://www.docker.com/products/docker-desktop) hebt geïnstalleerd.

### Frontend Installatie
1. Clone de repository:
   ```bash
   git clone https://github.com/jouw-username/Personal_Trainer_App.git
   cd Personal_Trainer_App/frontend

   Installeer de benodigde pakketten:
bash
Copy code
npm install
Backend Installatie (Directus)
Ga naar de directus map:
bash
Copy code
cd ../directus
Start de Docker-container:
bash
Copy code
docker-compose up -d
Start de Frontend
Ga terug naar de frontend:
bash
Copy code
cd ../frontend
Start de Svelte-app:
bash
Copy code
npm run dev
Open je browser en ga naar http://localhost:5000.
Licentie
Dit project is gelicenseerd onder de MIT-licentie - zie het LICENSE bestand voor details.
