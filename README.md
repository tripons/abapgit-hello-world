# abapGit Hello World

Mini-Repository für Übungen mit abapGit für ADT: Pull, Stage and Push und Switch Branch.

## Inhalt

| Objekt | Rolle |
|---|---|
| Paket, `src/package.devc.xml` | Wurzelpaket. Den Namen wählst du beim Verknüpfen, etwa `$HELLO_ABAPGIT` |
| Klasse `ZCL_HELLO_ABAPGIT` | gibt "Hello World" in der Konsole von ADT aus |

## Verwenden

1. In ADT unter abapGit Repositories das Repository verknüpfen: diese URL, ein lokales Paket wie `$HELLO_ABAPGIT`, Branch `main`.
2. Pull ausführen und die Objekte aktivieren.
3. `ZCL_HELLO_ABAPGIT` öffnen und mit F9 ausführen. Die Konsole zeigt "Hello World".

Ein lokales Paket mit `$` braucht keinen Transportauftrag. Nichts davon erreicht Test oder Prod.

abapGit nimmt ein Git-Repository je System nur einmal auf. Wer auf demselben System selbst üben will, legt eine eigene Kopie dieses Repositorys an und verknüpft sie mit einem eigenen Paket.
