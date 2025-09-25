## Toets – Hoofdstuk 1 t.e.m. 4 C# (Totaal: 40 punten)

Naam:								Klas:						Datum:



1. **Accepteer** de GitHub Classroom‑uitnodiging (link krijg je via Smartschool).
2. Wanneer je repository is aangemaakt, **clone** je die naar je computer.
3. Open de map van je repository en maak **twee mappen** aan:
   - `Oefening1`
   - `Oefening2`
4. **Open Visual Studio**.
5. **Maak in `Oefening1` een Console App** (C#) aan met de naam **KrokanteKrabBestelling**.
6. **Maak in `Oefening2` een Console App** (C#) aan met de naam **BierfeestToegang**.
7. **Commit & push** je volledige repository (code).
8. Controleer op GitHub of alle bestanden zichtbaar zijn in de juiste mappen.

------

<div style="page-break-after: always;"></div>

### **Oefening 1 – De Krokante Krab (SpongeBob‑thema)**

*Projectnaam: KrokanteKrabBestelling*
 **Totaal: 20 punten**

**Wat je moet bouwen**
 Een console‑app waarmee een klant een bestelling kan plaatsen bij de Krokante Krab.

**Stap‑voor‑stap bouwen**

1. **Start** het programma en toon een korte titel (bv. "Krokante Krab – Bestelling").
2. **Vraag**: naam van de klant.
3. **Vraag**: aantal Krabburger‑menu’s (geen negatieve aantallen).
4. **Vraag**: heeft de klant een kortingskaart? (antwoord: ja/nee).
5. **Controleer** de invoer op basiszaken (bv. aantal kan niet negatief zijn).
6. **Bereken** de **basisprijs**: aantal × €5,50.
7. **Pas korting toe**: **enkel** als (kortingskaart = ja) **en** (aantal > 3) ⇒ **10% korting** op de basisprijs.
8. **Toon overzicht** in duidelijke regels:
   - naam
   - aantal menu’s
   - korting toegepast: ja/nee
   - eindbedrag
9. **Test** met verschillende gevallen (bv. 0, 2 en 5 menu’s; met/zonder kortingskaart).

**Puntenverdeling**

- Correcte invoer (naam, aantal, kortingskaart ja/nee) *(3p)*
- Basiscontroles/validatie *(3p)*
- **Basisprijsberekening correct** *(5p)*
- **Korting correct toegepast** *(6p)*
- Duidelijk **overzicht** met eindbedrag *(3p)*

**Checklist vóór indienen (Oef. 1)**
 ☐ Invoer gevraagd: naam, aantal, kortingskaart
 ☐ Geen negatieve aantallen
 ☐ Prijs = aantal × 5,50
 ☐ Korting 10% **alleen** bij kaart **en** aantal > 3
 ☐ Overzicht netjes en volledig

------

<div style="page-break-after: always;"></div>

### **Oefening 2 – FC De Kampioenen – Bierfeest voor Xavier**

*Projectnaam: BierfeestToegang*
 **Totaal: 20 punten**

**Wat je moet bouwen**
 Een console‑app die beslist of iemand **toegang** krijgt tot het bierfeest van Xavier (FC De Kampioenen).

**Stap‑voor‑stap bouwen**

1. **Start** het programma en toon een korte titel (bv. "FC De Kampioenen – Bierfeest").
2. **Vraag**: naam van de bezoeker.
3. **Vraag**: leeftijd.
4. **Vraag**: lengte in cm.
5. **Vraag**: wachtwoord (hint aan de gebruiker: "dagschotel").
6. **Bepaal toegang**: toegang **alleen** als
   - leeftijd ≥ 18 **en**
   - lengte ≥ 140 **en**
   - wachtwoord juist is.
7. **Toon**
   - bij succes: **“Welkom [naam], veel plezier op het bierfeest van Xavier!”**
   - bij weigering: **een specifieke reden** (te jong / te klein / verkeerd wachtwoord).
8. **Maak** de controle logisch met een passende `if / else if / else`‑structuur.
9. **Test** verschillende combinaties (bv. 17 jaar, 139 cm, fout wachtwoord; allemaal juist).

**Puntenverdeling**

- Correcte invoer (naam, leeftijd, lengte, wachtwoord) *(4p)*
- **Kernlogica correct**: alle 3 voorwaarden moeten waar zijn *(8p)*
- **Specifieke reden** van weigering tonen *(4p)*
- Succesboodschap correct *(2p)*
- Basisrobustheid (bv. spaties trimmen, case‑insensitieve wachtwoordcheck) *(2p)*

**Checklist vóór indienen (Oef. 2)**
 ☐ Invoer gevraagd: naam, leeftijd, lengte, wachtwoord
 ☐ Toegang **alleen** bij leeftijd ≥ 18 **en** lengte ≥ 140 **en** wachtwoord juist
 ☐ Bij weigering: **concrete reden** tonen
 ☐ Succesboodschap correct
 ☐ Basisrobustheid toegepast

------

<div style="page-break-after: always;"></div>

**Eindtotaal en indienen**

- **Eindtotaal** = 20 (Oef. 1) + 20 (Oef. 2) = **40 punten**.
- **Dien in** door je laatste wijzigingen te **committen & pushen**.
- Controleer op GitHub of:
  ☐ `Oefening1/` en `Oefening2/` bestaan
  ☐ De projecten **KrokanteKrabBestelling** en **BierfeestToegang** in de juiste map staan
  ☐ De applicaties **runnen** en de gevraagde output geven

## Ruimte voor analyse:
