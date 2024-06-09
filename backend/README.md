<div align="center">
<h1><img src="https://raw.githubusercontent.com/unikino-gegenlicht/mldb/main/branding/backend.svg" alt="KoRMa — Kommunales (Film-)Rechte Management — Backend"></h1>
<img alt="Backend Build Status" src="https://img.shields.io/github/actions/workflow/status/unikino-gegenlicht/mldb/build-backend.yaml?branch=main&style=for-the-badge&logo=github-actions&logoColor=white&logoSize=auto&label=Backend%20Build">
<img alt="License" src="https://img.shields.io/github/license/unikino-gegenlicht/mldb?style=for-the-badge">
<img alt="Latest Version" src="https://img.shields.io/github/v/release/unikino-gegenlicht/mldb?sort=semver&display_name=tag&style=for-the-badge&label=Latest%20Version"><br/>
<img alt="Current Go Version" src="https://img.shields.io/github/go-mod/go-version/unikino-gegenlicht/mldb?filename=backend%2Fgo.mod&style=for-the-badge&logo=go&logoColor=white&logoSize=auto&label=Version">
</div>

## Entwicklung
Um am Backend entwickeln zu können wir nur die aktuelle Version von Go benötigt
und der Zugang zu einer PostgeSQL Datenbank benötigt.
Die PostgreSQL Datenbank sollte eine lokale Instanz sein, um die Daten in einem
möglichen Live-System nicht zu gefährden.
Während der lokalen Entwicklung erkennt die Software dies selbstständig und
deaktiviert die Authentifizierung, sodass kein Login benötigt wird um das
Backend zu testen.
Jedoch ist ein Login grundsätzlich möglich, sodass auch dies möglich ist.