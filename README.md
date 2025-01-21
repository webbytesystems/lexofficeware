# lexofficeware
Lexoffice (Lexware) Prozessoptimierung
Beschreibung

Dieses Programm bietet eine kleine Lösung für die Integration und Automatisierung von Buchhaltungs- und Zeiterfassungsprozessen mithilfe der Lexoffice API. Es ist darauf ausgelegt, tägliche Abläufe zu optimieren und wiederkehrende Aufgaben zu vereinfachen.

Hauptfunktionen

    Lexoffice (jetzt Lexware) API-Verbindung
        Abruf und Verwaltung von offenen Rechnungen.
        Gruppierung von Kunden mit offenen Rechnungen.
        Aktuell nur für Debugging-Zwecke nutzbar.

    Memtime Integration (ehemals TimeBro)
        Import von Zeiterfassungsdaten aus der Software Memtime.
        Möglichkeit, die Daten wahlweise als Lieferschein oder Rechnung nach Lexoffice zu exportieren.
        Erfordert einen Lexoffice API-Schlüssel und einen Memtime-Account.

    Lastschriften herunterladen
        Erstellung und Bearbeitung von SEPA-XML-Dateien.
        Export von Lastschriften zur weiteren Nutzung in Software wie StarMoney oder anderen Banking-Tools.
        Integration mit der Funktion „Bankverbindungen bearbeiten“, um Bankinformationen der Kunden zentral zu verwalten.

    Prozessoptimierung
        Automatische Generierung von Lastschriftdateien basierend auf offenen Rechnungen.
        Vollständige Unterstützung der Lexoffice API für Buchhaltungsaufgaben.
        Optimierte Verarbeitung von Daten aus der Zeiterfassung für Buchhaltungszwecke.

Technische Details

    Programmiersprache: Python
    Framework: Streamlit für die Benutzeroberfläche.
    Voraussetzungen:
        Ein Lexoffice-Account mit aktivierter API (API-Schlüssel hier erstellen: https://app.lexoffice.de/addons/public-api).
        Die Zeiterfassungssoftware Memtime (ehemals TimeBro) https://www.memtime.com/.
        Optional: Banking-Software wie z.B. StarMoney für den Import und Ausführung der Lastschriften https://www.starmoney.de/

Installationsanleitung

    Klone das Repository:

git clone <repository-url>

Installiere die benötigten Abhängigkeiten:

pip install -r requirements.txt (folgt)

Setze die Konfiguration für die Lexoffice-API und Memtime in den entsprechenden JSON-Dateien bzw. unter dem Menüpunkt Einstellungen.
Starte das Programm:

streamlit run main.py

EN

Lexoffice (Lexware) Process Optimization Description

This program provides a lightweight solution for integrating and automating accounting and time tracking processes using the Lexoffice API. It is designed to optimize daily workflows and simplify recurring tasks.
Key Features

    Lexoffice (now Lexware) API Connection
        Retrieve and manage open invoices.
        Group customers with open invoices.
        Currently usable only for debugging purposes.

    Memtime Integration (formerly TimeBro)
        Import time tracking data from the Memtime software.
        Option to export the data as a delivery note or invoice to Lexoffice.
        Requires a Lexoffice API key and a Memtime account.

    Download Direct Debits
        Create and edit SEPA-XML files.
        Export direct debits for use in software such as StarMoney or other banking tools.
        Integration with the "Manage Bank Details" function to centrally manage customer bank information.

    Process Optimization
        Automatic generation of direct debit files based on open invoices.
        Full support for the Lexoffice API for accounting tasks.
        Optimized processing of time tracking data for accounting purposes.

Technical Details

    Programming Language: Python
    Framework: Streamlit for the user interface.
    Requirements:
        A Lexoffice account with API access (create an API key here: Lexoffice Public API).
        The time tracking software Memtime (formerly TimeBro) https://www.memtime.com/.
        Optional: Banking software such as StarMoney for importing and executing direct debits https://www.starmoney.de/.