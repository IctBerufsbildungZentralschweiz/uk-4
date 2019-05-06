# Content Management System
> Ein Content-Management-System (kurz CMS, deutsch Inhaltsverwaltungssystem) ist eine Software zur gemeinschaftlichen Erstellung, Bearbeitung und Organisation von Inhalten (Content) zumeist in Webseiten, aber auch in anderen Medienformen. Diese können aus Text- und Multimedia-Dokumenten bestehen. Ein Autor mit Zugriffsrechten kann ein solches System in vielen Fällen mit wenig Programmier- oder HTML-Kenntnissen bedienen, da die Mehrzahl der Systeme über eine grafische Benutzeroberfläche verfügt.

[Definition auf Wikipedia - 2019](https://de.wikipedia.org/wiki/Content-Management-System)

## Komponenten eines CMS
| Komponente            | Beschreibung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Backend               | Das Backend ist die Administratorenoberfläche zum Erstellen und Pflegen von Inhalten (Content). Das Backend ermöglicht es   dem Administrator Informationen (Texte, Bilder, Videos etc.) einzutragen und   in das vorgesehene Speichermedium (Dateien, Datenbank etc.) zu speichern oder   diese davon abzurufen und anzuzeigen. Durch die Vereinfachung der   Datenverwaltung in grafischen Bedienoberflächen, ermöglicht es das Backend   auch für Administratoren ohne erweiterte Programmierkenntnisse,   Website-Inhalte zu erfassen und zu verwalten. |
| Frontend              | Das Frontend ist das Gegenstück des Backends und bezeichnet die   Darstellung der fertig generierten Website an den Endnutzer/Besucher. Das   Inhaltsverwaltungssystem füllt dazu die erfassten Inhalte in das vorgesehene   Template ab und zeigt die damit erstelle Seite an.                                                                                                                                                                                                                                                                                |
| Rechteverwaltung      | Da nur Administratoren Zugriff auf den Verwaltungsbereich haben dürfen,   wird dieser durch eine Authentifikation (Passwort, Code etc.) geschützt.   Jedoch auch innerhalb der Administratorengruppe, haben die einzelnen   Benutzergruppen (Superadmin, Redateur etc.) unterschiedliche Berechtigungen.   Was für Rechte (erstellen, lesen, bearbeiten, kommentieren etc.) eine   bestimmte Benutzergruppe für gewisse Inhalte hat, wird in der   Rechteverwaltung festgelegt.                                                                               |
| CMS Core              | Der CMS Core ist das technische Herzstück des Inhaltsverwaltungssystem.   Der Core deckt die Grundfunktionen (Inhalte speichern, Rechteverwaltung,   Templates verwalten, Plugins installieren etc.) ab, welche für den Betrieb   einer einfachen Website notwenig sind.                                                                                                                                                                                                                                                                                       |
| Plugins/Erweiterungen | Plugins und Erweiterungen erweitern die Basisfunktionen des CMS Core um   spezifische Eigenschaften. Die Plugins können meistens einfach installiert   werden und erweitern die Funktionalität des Backends und des Frontends.                                                                                                                                                                                                                                                                                                                                 |
| Datenspeicherung      | Die Datenspeicherung übernimmt die Speicherung der Daten, welche im   Backend oder im Frontend erfasst wurden. Typischerweise handelt es sich hier um eine Datenbank oder um ein Filesystem.                                                                                                                                                                                                                                                                                                                                                                       |
| Template              | Das Template ist gleichwertig mit einer Seitenvorlage. Das Template   definiert das Aussehen und die Struktur der jeweiligen Seite, jedoch nicht   den Inhalt. Erst das CMS nimmt die jeweiligen Inhalte und füllt diese in die   Seitenvorlage ein und zeigt diese im Frontend an.                                                                                                                                                                                                                                                                            |

![Komponente eines CMS](res/06.jpg)

## Marktanteil der Content Management Systeme

|             | Anteil Einsatz insgesamt Websites | Anteil Einsatz bei Websites mit CMS |
|-------------|---------------------------------:|------------------------------------:|
| WordPress   |                           33.8%  |                        60.6%        |
| Joomla      |                            2.9%  |                         5.2%        |
| Drupal      |                            1.9%  |                         3.4%        |
| Squarespace |                            1.5%  |                         2.7%        |
| Wix         |                            1.1%  |                         1.9%        |
| TYPO3       |                            0.7%  |                         1.2%        |
| October CMS |                            0.1%  |                         0.1%        |


Quelle: [https://w3techs.com/technologies/overview/content_management/all/](https://w3techs.com/technologies/overview/content_management/all/)