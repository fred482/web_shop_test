# web_shop_test
Webshop_for_more_elements

## Shop auf GitHub Pages veröffentlichen

Der Workflow unter `.github/workflows/deploy.yml` veröffentlicht die Shop-Seite automatisch, sobald Änderungen am Branch `main` gespeichert werden.

1. `index.html` und den Workflow nach GitHub pushen.
2. Im GitHub-Repository unter **Settings → Pages** bei **Build and deployment** als Quelle **GitHub Actions** auswählen.
3. Änderungen an `index.html` direkt auf GitHub bearbeiten und nach `main` committen. Die Veröffentlichung startet danach automatisch unter **Actions**; dort wird auch die Shop-URL angezeigt.
