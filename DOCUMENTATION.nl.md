# Documentatie

Lees de documenten:[vanHeemstraSystems-REPOSITORY-NAME](https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/)

## 100 - Installeer Readthedocs

Voer de volgende opdracht uit:

    $ pip install sphinx sphinx_rtd_theme recommonmark

Volgende om de documentenrun te maken:

    $ cd docs
    $ make html

Uw documenten worden van binnen gemaakt`docs/build`.

## 200 - Autogeneratie van Readthedocs

1) Zorg ervoor dat er een`.readthedocs.yml`Bestand aan de hoofd van uw GitHub -repository.

2) Verbind uw GitHub -repository met Readthedocs op<https://readthedocs.org/>

1.  Gaan naar[Readthedocs](https://readthedocs.org/)en maak een account aan
2.  Klik op "Een project importeren"
3.  Verbind uw GitHub -account als u dat nog niet hebt gedaan
4.  Selecteer uw repository in de lijst
5.  Configureer uw projectinstellingen

## 300 - Bouw uw documentatie

1.  Duw uw wijzigingen in GitHub
2.  ReadThedocs zal uw documentatie automatisch bouwen
3.  Bezoek uw projectpagina op Readthedocs om het resultaat te zien

## 400 - Webhooks instellen (optioneel)

ReadThedocs moeten automatisch webhooks instellen, maar zo niet:

1.  Ga naar uw repository -instellingen op GitHub
2.  Ga naar Webhooks
3.  Voeg een webhook toe met de URL uit uw Readthedocs -projectinstellingen

## 500 - Problemen oplossen

-   **Build mislukt**: Controleer de buildlogboeken op Readthedocs
-   **Ontbrekende inhoud**: Zorg ervoor dat alle bestanden zijn opgenomen in uw`toctree`
-   **Formatting issues**: Controleer of uw Markdown/RestructuredText geldig is
-   **Afbeeldingen worden niet weergegeven**: Verifieer paden naar afbeeldingen zijn correct

## 600 - uw documentatie onderhouden

-   Werk uw documentatiebestanden bij indien nodig bij
-   Duw veranderingen in GitHub
-   ReadThedocs zullen automatisch opnieuw opbouwen
-   Gebruik de versie -functie van ReadThedocs om documentatie te onderhouden voor verschillende releases

## 700 - Trigger A Build on Readthedocs

Op[Readthedocs](https://readthedocs.org/), na het inloggen in navigeren naar uw GitHub -repository -invoer (bijv.`https://app.readthedocs.org/projects/YOUR-GITHUB-REPOSITOY-NAME/`) en kies uit het gestippelde menu (...)**Herbouwversie**.

## 800 - Tips

-   **Beelden**: Verplaats afbeeldingen naar`docs/source/_static/`en bijwerken referenties
-   **Codeblokken**: Zorg ervoor dat de juiste syntaxismarkering is opgegeven
-   **Kruisverwijzingen**: Update om het referentiesysteem van Sphinx te gebruiken
-   **Metadata**: Voeg de juiste metagegevens toe aan elke pagina voor betere SEO

## 900 - Gemeenschappelijke problemen

-   **Broken Links**: Controleer alle links na de conversie dubbel
-   **Ontbrekende afbeeldingen**: Zorg ervoor dat alle beeldpaden worden bijgewerkt
-   **Bouw mislukkingen**: Controleer de leesthedocs build -logs voor fouten
-   **Verschillen opmaken**: Sommige markdown -functies kunnen in Sphinx anders worden weergegeven

## 1000 - Bekijk de documentatie

Bezoek<https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/>
