# Kleur uitzetten & kleurenblindheid testen

### Normaal zicht
<img width="438" alt="Schermafbeelding 2022-04-07 om 19 21 37" src="https://user-images.githubusercontent.com/66092262/162260894-2ef0247c-03c0-4916-8c5f-9575fbe3b3af.png">

### Protanopie
<img width="440" alt="Schermafbeelding 2022-04-07 om 19 22 25" src="https://user-images.githubusercontent.com/66092262/162261040-0d482251-4f26-4327-87b9-05d51cf4a0c6.png">

### Deuteranopie
<img width="439" alt="Schermafbeelding 2022-04-07 om 19 23 12" src="https://user-images.githubusercontent.com/66092262/162261171-e781a333-7d3d-41c8-bc1b-3baa345f48d3.png">

### Tritanopie
<img width="441" alt="Schermafbeelding 2022-04-07 om 19 23 49" src="https://user-images.githubusercontent.com/66092262/162261274-613db14c-40ee-4af0-ac1c-c8b3c81cca7d.png">

### Achromatopie
<img width="454" alt="Schermafbeelding 2022-04-07 om 19 24 36" src="https://user-images.githubusercontent.com/66092262/162261410-5eedcee2-f915-4088-be09-3f4c28526339.png">

### Hoeveel mensen hebben er last van?
* Ongeveer 1 op de 12 mannen hebben last van een vorm van kleurblindheid. Bij de vrouwen hebben maar 1 op de 200 er last van.
* De meest voorkomende vorm is protanopie. Hierbij zien mensen de kleur rood niet of minder goed.
* De meest zeldzame vorm is achromatopsie. Hierbij zien mensen helemaal geen kleur meer. Deze mensen zijn daarbij ook heel erg schuw voor licht.

## Hoe kun je rekening houden met je gebruikers?
### Test je site op kleurenblindheid
<img width="328" alt="Schermafbeelding 2022-04-07 om 19 31 33" src="https://user-images.githubusercontent.com/66092262/162262491-bc4eed38-73ac-47f4-bccf-e6e3a4c19836.png">

### Contrastverhouding tool
<img width="233" alt="Schermafbeelding 2022-04-07 om 19 31 49" src="https://user-images.githubusercontent.com/66092262/162262522-34a4cfef-44ef-4a11-8756-4e602c03a053.png">

## Javascript uitzetten
<img width="602" alt="Schermafbeelding 2022-04-07 om 19 40 45" src="https://user-images.githubusercontent.com/66092262/162264081-ad9b06d0-63cb-4edf-8288-b7e1e21c6236.png">
<img width="603" alt="Schermafbeelding 2022-04-07 om 19 40 55" src="https://user-images.githubusercontent.com/66092262/162264111-19203af7-0ac3-4fd5-a827-2f2b3d7f0bf9.png">

Gemiddeld 1.3% van de internetgebruikers heeft javascript uit staan.

### Waarom zetten gebruikers javascript uit?
* Beveiliging: Client browsers kunnen kwaadaardige code in je computer zetten die je computer verslechteren. Door javascript uit te zetten gebeurd dit niet.
* Browser support: Niet elke browser kan javascript zo goed mogelijk uitvoeren, omdat het bepaalde code andere interperteert dan andere browsers. Hierdoor krijg je inconsistentie in functionaliteiten. Door javascript uit te zetten weet je zeker dat de webpagina laad, zoals hij bedoeld is.
* PLug-ins en cookies: Veel gebruikers zijn bang dat bedrijven hun internetgebruik kunnen tracken. Door Javascript uit te zitten zullen de cookies die bijhouden wat je op internet doet niet meer functioneren.

### Hoe kun je JavaScript uitzetten?
<img width="402" alt="Schermafbeelding 2022-04-07 om 19 41 09" src="https://user-images.githubusercontent.com/66092262/162264148-66699e46-c26a-4e90-9572-383dde0b1215.png">

### Wat voor problemen kan het opleveren?
Als je een website volledig met bijvoorbeeld React gaat bouwen, dan zal de gehele website het niet meer doen op het moment dat je gebruiker Javascript heeft uitgeschakeld.

<img width="602" alt="Schermafbeelding 2022-04-07 om 19 41 24" src="https://user-images.githubusercontent.com/66092262/162264181-61a786ca-0d9f-4248-addf-81ec388ae2b6.png">

Ook zullen formulieren die door javascript worden gevalideerd niet meer worden gevalideerd en kan de gebruiker invullen wat hij/zij wilt.
</br>
</br>
Als je met javascript een API fetch doet, dan zullen de resultaten uit deze fetch ook niet meer getoond worden. Deze resultaten kunnen wel belangrijk zijn voor je website.

