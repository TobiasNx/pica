# Einführung in die Verarbeitung von PICA-Daten

Dieses Skript bietet eine kurze Einführung in die Verarbeitung von Daten im und aus dem **PICA-Format**.

## Vorwort

> During a relatively long period of research, an advanced format was developed for the storage of bibliographic information; the PICA format. — Look Costers (1979)

Das PICA-Format ist seit mehr als 40 Jahren im Einsatz und konnte bisher nicht durch modernere Techniken wie relationale Datenbanksysteme oder Wissensgraphen ersetzt werden. PICA ist einerseits zentral für die Datenhaltung in dein meisten Bibliotheken in Deutschland, andererseits wird das Format nicht außerhalb des Bibliothekswesens benutzt. Um sich mit der Verarbeitung von PICA-Daten vertraut zu machen, ist daher Dokumentation notwendig, wozu das vorliegende Skript beitragen soll. Schwerpunkt ist die Verarbeitung von PICA-Daten außerhalb der nicht-offenen PICA-Systeme wie CBS, LBS und WinIBW.

## Inhalt

- [Grundlagen](grundlagen.md)
   - Geschichtlicher Hintergrund
   - Arten von Datenformaten
- [PICA-Formate](formate.md)
   - Aufbau des PICA-Formats
   - Serialisierungen
   - Abfragesprache
   - Anwendungsprofile und Schemas
- Verarbeitung
   - Konvertierung
   - Auswertung
   - Tools (PICA::Data, Catmandu...)
- [Schnittstellen](schnittstellen.md)
   - Zugriff auf PICA-Daten (OPAC, WinIBW, SRU, unAPI...)
- Ausblick und Alternativen
   - MARC, RDF, JSON...
   - BIBFRAME, Folio...

## Literatur

* Becker et. al (1992): *Das PICA-System. Bericht über die im Auftrag des Niedersächsischen Ministeriums für Wissenschaft und Kunst durchgeführte Funktionsprüfung (Stand Mitte 1990).* In: Bibliothek Forschung und Praxis, Band 16, Heft 3. <https://doi.org/10.1515/bfup.1992.16.3.307>
* Costers (1979): *The PICA Catalogue System.* In: Proceedings of the IATUL Conferences. Paper 26. <https://docs.lib.purdue.edu/iatul/1979/papers/26>
* Eversberg (1999): *Was sind und was sollen Bibliothekarische Datenformate* <http://www.allegro-c.de/formate/formate.htm>
* Klute (2018): *ETL-Prozesse für bibliothekarische Metadaten: Die Migration lokaler Katalogisate im GBV.* <https://doi.org/10.15771/MA_2018_3>
* Schneiders (1997): *Nederlandse bibliotheekgeschiedenis: van librije tot virtuele bibliotheek*. NBLC Uitg.
* Tennant (2002): *MARC Must Die.* In: Library Journal.
