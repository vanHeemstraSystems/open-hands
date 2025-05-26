# Dokumentation

Lesen Sie die Dokumente:[VanHeemStrasyStems-Repository](https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/)

## 100 - Readthedocs installieren

Führen Sie den folgenden Befehl aus:

    $ pip install sphinx sphinx_rtd_theme recommonmark

Als nächstes erstellen Sie den DOCS -Lauf:

    $ cd docs
    $ make html

Ihre Dokumente werden im Inneren erstellt`docs/build`.

## 200 - Autogeneration von Rededhedocs

1) Stellen Sie sicher, dass es eine gibt`.readthedocs.yml`Datei am Root Ihres Github -Repositorys.

2) Verbinden Sie Ihr Github -Repository mit Redethedocs unter<https://readthedocs.org/>

1.  Gehen zu[Readthedocs](https://readthedocs.org/)und ein Konto erstellen
2.  Klicken Sie auf "Ein Projekt importieren"
3.  Schließen Sie Ihr GitHub -Konto an, wenn Sie es noch nicht getan haben
4.  Wählen Sie Ihr Repository aus der Liste aus
5.  Konfigurieren Sie Ihre Projekteinstellungen

## 300 - Erstellen Sie Ihre Dokumentation

1.  Drücken Sie Ihre Änderungen in GitHub
2.  Readthedocs erstellen automatisch Ihre Dokumentation
3.  Besuchen Sie Ihre Projektseite auf Redethedocs, um das Ergebnis anzuzeigen

## 400 - Webhooks einrichten (optional)

Readthedocs sollten automatisch Webhooks einrichten, aber wenn nicht:

1.  Gehen Sie zu Ihren Repository -Einstellungen auf GitHub
2.  Gehen Sie zu Webhooks
3.  Fügen Sie einen Webhook mit der URL aus Ihren Redethedocs -Projekteinstellungen hinzu

## 500 - Troubleshooting

-   **Build schlägt fehl**: Überprüfen Sie die Build -Protokolle auf Redethedocs
-   **Fehlende Inhalte**: Stellen Sie sicher, dass alle Dateien in Ihrem enthalten sind`toctree`
-   **Probleme formatieren**: Überprüfen Sie, ob Ihr Markdown/Umstrukturiertertext gültig ist
-   **Bilder nicht anzeigen**: Überprüfen Sie, ob die Pfade zu Bildern korrekt sind

## 600 - Pflege Ihrer Dokumentation

-   Aktualisieren Sie Ihre Dokumentationsdateien nach Bedarf
-   Veränderungen in GitHub drücken
-   Redethedocs werden automatisch wieder aufgebaut
-   Verwenden

## 700 - Auslösen Sie einen Build auf Redethedocs

An[Readthedocs](https://readthedocs.org/)Nach Anmelde bei der Navigation zu Ihrem Github -Repository -Eintrag (z. B.,,,`https://app.readthedocs.org/projects/YOUR-GITHUB-REPOSITOY-NAME/`) und aus dem gepunkteten Menü (...) wählen Sie**Version neu aufbauen**.

## 800 - Tipps

-   **Bilder**: Verschieben Sie Bilder auf`docs/source/_static/`und aktualisieren Sie Referenzen
-   **Codeblöcke**: Stellen Sie sicher
-   **Cross-Referenzen**: Update, um das Referenzsystem von Sphinx zu verwenden
-   **Metadaten**: Fügen Sie jeder Seite geeignete Metadaten hinzu, um bessere SEO zu finden

## 900 - Häufige Probleme

-   **Kaputte Links**: DOUBEN
-   **Fehlende Bilder**: Stellen Sie sicher, dass alle Bildwege aktualisiert werden
-   **Fehler aufbauen**: Überprüfen Sie die Redethedocs Build -Protokolle auf Fehler
-   **Formatierende Unterschiede**: Einige Markdown -Funktionen können in Sphinx unterschiedlich sein

## 1000 - Die Dokumentation anzeigen

Besuchen<https://vanHeemstraSystems-REPOSITORY-NAME.readthedocs.io/en/latest/>
