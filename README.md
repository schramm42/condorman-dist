# condorman-dist

Artefakte zu [Condorman](https://github.com/schramm42/condorman). Hier liegt kein
Quellcode.

Der Release-Workflow des Hauptprojekts legt zu jedem stabilen Release ab:

- die gebauten Dateien als GitHub-Release,
- `update-manifest.json` auf diesem Branch — die Datei, die das Autoupdate der
  App abfragt.

Feste Adresse des Manifests:

```
https://raw.githubusercontent.com/schramm42/condorman-dist/main/update-manifest.json
```

Das Hauptprojekt ist privat, seine Release-Assets sind damit nicht anonym
ladbar. Dieses Repo ist öffentlich, damit das Autoupdate ohne Anmeldung
auskommt.

Änderungen von Hand sind nicht vorgesehen: der Workflow überschreibt das
Manifest bei jedem Release.
