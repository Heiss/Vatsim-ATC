# VFR

## kontrollierter Flugplatz

Rollen: P - Pilot, G - Ground, T - Tower

### Abflug
| Pos. | Nachricht                                                                                                                             |
|------|---------------------------------------------------------------------------------------------------------------------------------------|
| P    | `Münster Rollkontrolle` , `DEPHS`, Guten Tag.                                                                                         |
| G    | `DEPHS`, `Münster Rollkontrolle`, Moin.                                                                                               |
| P    | `DEPHS`, `Cessna 172`, `Abstellplatz allgemeinen Luftfahrt`, `<VFR über Tango / Platzrunden>`, `Information Charlie`, erbitte Rollen. |
| G    | `DHS`, *Wind 180/8 Knoten*, Qnh `1011`, rollen Sie zum Rollhalt Piste `25` über `Alpha`.                                              |
| P    | `DHS`, Qnh `1011`, rolle zum Rollhalt Piste `25` über `Alpha`.                                                                        |
| P    | `DHS`, abflugbereit.                                                                                                                  |
| G    | `DHS`, verstanden, rufen Sie Turm auf Frequenz `126,85`.                                                                              |
| P    | `DHS`, rufe Turm auf Frequenz `126,85`.                                                                                               |
| P    | `Münster Turm`, `DEPHS`, Rollhalt Piste `25`, auf Rollbahn `Alpha`, abflugbereit.                                                     |
| T    | `DEPHS`, `Münster Turm`, `<hinter landender Cessna 172 im Queranflug>` rollen Sie zum Abflugpunkt Piste `25`.                         |
| P    | `DEPHS`, `<hinter landender Cessna 172>` rolle zum Abflugpunkt `25`.                                                                  |
| T    | `DHS`, verlassen Sie die Kontrollzone über `Tango`, fliegen Sie rechte Platzrunde, *Wind 190/7 Knoten*, Start frei Piste `25`         |
| P    | `DHS`, verlasse Kontrollzone über `Tango`, fliege rechte Platzrunde, Start frei Piste `25`                                            |
| P    | `DHS`, Pos. `Tango`, Flughöhe `2000` Fuss.                                                                                            |
| T    | `DHS`, verstanden, verlassen der Frequenz genehmigt                                                                                   |
| P    | `DHS`, Verlassen der Frequenz genehmigt, *Schönen Tag.*                                                                               |

### Anflug

| Pos. | Nachricht                                                                                                                                 |
|------|-------------------------------------------------------------------------------------------------------------------------------------------|
| P    | `Münster Turm`, `DEPHS`, Guten Tag                                                                                                        |
| T    | `DEPHS`, `Münster Turm`, Guten Tag                                                                                                        |
| P    | `DEPHS`, `Cessna 172`, VFR, `5 Meilen nördlich Tango`, Flughöhe `2000` Fuss, `<zur Landung | zum Aufsetzen und durchstarten | Tiefflug>`. |
| T    | `DEPHS`, fliegen Sie in die Kontrollzone über `Tango`, *Wind 270/6 Knoten*, Piste `25`, Qnh `1012`.                                       |
| P    | `DEPHS`, fliege in die Kontrollzone über `Tango`, Piste `25`, Qnh `1012`.                                                                 |
| P    | `DEPHS`, Pos. `Tango`, Flughöhe `2000` Fuss.                                                                                              |
| T    | `DHS`, verstanden, `<Verkehr eine Beech Bonanza auf Gegenkurs>`                                                                           |
| P    | `DHS`, `<Verkehr in Sicht, halte Ausschau>`                                                                                               |
| T    | `DHS`, fliegen Sie in die rechte Platzrunde Piste `25`, *melden Sie rechten Gegenanflug*.                                                 |
| P    | `DHS`, fliege in die rechte Platzrunde Piste `25`.                                                                                        |
| P    | `DHS`, rechter Gegenanflug Piste `25`.                                                                                                    |
| T    | `DHS`, verstanden, Nummer 2 *folgen Sie Lufthansa A747, 2 Meilen Endanflug, Vorsicht Wirbelschleppen*.                                    |
| P    | `DHS`, verstanden, Nummer 2, Verkehr in Sicht.                                                                                            |
| T    | `DHS`, machen Sie lange Landung, *Wind 280/8 Knoten*, Landung frei Piste `25`.                                                            |
| P    | `DHS`, mache lange Landung, Landung frei Piste `25`.                                                                                      |
| T    | `DHS`, verlassen Sie Piste `25` über Rollbahn `Alpha`, nach verlassen rufen Sie Rollkontrolle auf Frequenz `121,9`.                       |
| P    | `DHS`, verlasse Piste `25` über Rollbahn `Alpha`, nach Verlassen rufe Rollkontrolle auf `121,9`.                                          |
| P    | `Münster Rollkontrolle`, `DEPHS`, Piste `25` über Rollbahn `Alpha` verlassen, erbitte Rollen zum Abstellplatz allgemeinen Luftfahrt.      |
| G    | `DEPHS`, `Münster Rollkontrolle`, rollen Sie zum Abstellplatz Allgemeiner Luftfahrt über Rollbahn `Alpha`.                                |
| P    | `DEPHS`, rolle zum Abstellplatz Allgemeiner Luftfahrt.                                                                                    |

## unkontrollierter Flugplatz

Rollen: P = Pilot, I = Info

### Abflug
| Pos. | Nachricht                                                       |
|------|-----------------------------------------------------------------|
| P    | `Speyer Info`, `DEPHS`, Guten Tag.                              |
| I    | `DEPHS`, `Speyer Info`, Hallo.                                  |
| P    | `DEPHS`, `<zur Platzrunde | VFR über Sierra | Rundflug | ...>`. |
| I    | `DHS`, Piste `17` in Betrieb, Qnh `1017`.                       |
| P    | `DHS`, Piste `17` in Betrieb, Qnh `1017`.                       |
| P    | `DHS`, Rollhalt `17`, abflugbereit.                             |
| I    | `DHS`, *Wind 170, 12 Knoten*.                                   |
| P    | `DHS`, Starte auf Piste `17`.                                   |

Verlässt man die Platzrunde, so meldet man sich ab.

| Pos. | Nachricht                                                     |
|------|---------------------------------------------------------------|
| P    | `DHS`, verlässt die Platzrunde in Richtung Süden, Tschüss.    |
| I    | `DHS`, verstanden, Verlassen der Frequenz genehmigt, Tschüss. |

Verlässt man nicht die Platzrunde, sondern will Platzrunden drehen, so meldet man sich einfach wieder im Gegenanflug.

| Pos. | Nachricht                                                                                                                     |
|------|-------------------------------------------------------------------------------------------------------------------------------|
| P    | `DHS`, im Gegenanflug zur Piste `17`, `<zum Aufsetzen und Durchstarten | zur Landung>.`                                       |
| I    | `DHS`, verstanden, melden Sie Queranflug, `<achten Sie auf Segelflugzeug | Fallschirmspringer | Maschine im Startlauf | ...>` |
| P    | `DHS`, Queranflug Piste `17`.                                                                                                 |
| I    | `DHS`, verstanden, melden Sie den Endanflug Piste `17`.                                                                       |
| P    | `DHS`, Endanflug Piste `17`.                                                                                                  |
| I    | `DHS`, *Wind 240, 6 Knoten*                                                                                                   |



### Anflug
| Pos. | Nachricht                                                                                                                       |
|------|---------------------------------------------------------------------------------------------------------------------------------|
| P    | `Speyer Info`, `DEPHS`, Guten Tag.                                                                                              |
| I    | `DEPHS`, `Speyer Info`, Hallo.                                                                                                  |
| P    | `DEPHS`, `<Cessna 172, VFR-Flug, 5 Minuten westlich Speyer>`, erbitte Landeinformationen.                                       |
| I    | `DHS`, Piste `35` in Betrib, Qnh `1016`, melden Sie den rechten Gegenanflug zur Piste `35`.                                     |
| P    | `DHS`, Piste `35` in Betrieb und Qnh `1016`, werden uns im rechten Gegenanflug zur Piste `35` melden.                           |
| P    | `DHS`, im rechten Gegenanflug zur Piste `35`.                                                                                   |
| I    | `DHS`, verstanden, melden Sie rechten Queranflug, `<achten Sie auf Segelflug | Fallschirmspringer | ...>.`                      |
| P    | `DHS`, im rechten Quernanflug Piste `35`.                                                                                       |
| I    | `DHS`, verstanden, melden Sie den Endanflug Piste `35`.                                                                         |
| P    | `DHS`, Endanflug Piste `35`.                                                                                                    |
| I    | `DHS`, *Wind 020 mit 9 Knoten.*                                                                                                 |
| P    | `DHS`, vor Piste 17, zum Überqueren.                                                                                            |
| I    | `DHS`, `<kein gemeldeter Verkehr in der Platzrunde | Cessna 172 im Queranflug zu Piste 17 | Überqueren nach eigenem Ermessen>`. |
| P    | `DHS`, verstanden.                                                                                                              |