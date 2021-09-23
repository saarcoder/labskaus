# ✨ labskaus ✨

<img src="/public/images/labskaus-demo-1024x559.png" width="600">

[Next.js](https://nextjs.org/)-Seite mit Git als [CMS](https://en.wikipedia.org/wiki/Content_management_system). Seiten-Editor: [Stackbit](https://www.stackbit.com?utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes). Vorlage: Podcast, Build-Zeit: unter einer Minute.

Mit Stackbit lassen sich verschiedene [Vorlagen](https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/exto-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes) wie diese benutzen. Wie wäre es mit einer anderen?

<details>
        <summary>🎨 &nbsp;<strong>Vorlagen</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/fresh-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Persönliche Seite mit Blog</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/azimuth-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Schickes SaaS Theme</a></li>
                <li><a href="https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/starter-unibit&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Ultra anpassbarer Starter. Der Favorit bei Entwicklern.</a></li>
                </ul>
</details>

<details>
        <summary>✏️ &nbsp;<strong>CMS-Auswahl</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?cms=contentful&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Contentful</a></li>
                <li><a href="https://app.stackbit.com/create?cms=sanity&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Sanity</a></li>
                <li><a href="https://app.stackbit.com/create?cms=datocms&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Dato CMS</a></li>
                </ul>
</details>

<details>
        <summary>⚙️ &nbsp;<strong>Static-Site-Generatoren</strong></summary>
        <ul>
                <li><a href="https://app.stackbit.com/create?ssg=gatsby&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Gatsby</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=nextjs&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Next.js</a></li>
                <li><a href="https://app.stackbit.com/create?ssg=hugo&utm_source=project-readme&utm_medium=referral&utm_campaign=user_themes">Hugo</a></li>
                </ul>
</details>

## Lokal entwickeln

1. [Nach dieser Vorlage](https://app.stackbit.com/create?theme=https://github.com/stackbit-themes/podcaster-nextjs&utm_source=theme-readme&utm_medium=referral&utm_campaign=stackbit_themes) aus Stackbit heraus eine Seite erzeugen.

2. Danach in Stackbit Studio den Inhalt direkt auf der Seite editieren und neue Versionen veröffentlichen.

3. Zur Weiterentwicklung das erzeugte GitHub-Repository klonen.

4. Abhängigkeiten installieren:

       npm install
       
4. Einen lokalen Next.js Entwicklungs-Server starten:

        npm run develop

5. Im Browser die Adresse [http://localhost:3000/](http://localhost:3000/) öffnen, um die Entwicklungs-Seite zu sehen. Seite in einem Code-Editor bearbeiten, der Browser aktualisiert die Seite automatisch. 🎉


## Veröffentlichen 🏗

Für den Produktiv-Code oder einen lokalen Test den folgenden Befehl eingeben:

    npm run build

Die exportierte Seite wird in das `out`-Verzeichnis geschrieben. Die Inhalte dieses Verzeichnisses können an eine Serverless-Distributionsplattform wie [Netlify](https://www.netlify.com) geschickt werden.
Ein lokaler Server zur Ausgabe zur Ausgabe der statischen Dateien des `out`-Verzeichnisses im Browser kann z.B. durch Installation und Ausführung von `http-server`gestartet werden:

    npm install http-server -g
    http-server out


Hier ein paar Ressourcen zum Start:

- 📺 &nbsp; [Content editieren](https://stackbit.link/project-readme-editing-video)
- 📺 &nbsp; [Einträge hinzufügen, neu anordnen und löschen](https://stackbit.link/project-readme-adding-video)
- 📺 &nbsp; [Zusammenarbeit](https://stackbit.link/project-readme-collaboration-video)
- 📺 &nbsp; [Veröffentlichen](https://stackbit.link/project-readme-publishing-video)
- 📚 &nbsp; [Stackbit Dokumentation](https://stackbit.link/project-readme-documentation)

Wenn Du Hilfe benötigst, schau am besten zuerst auf unserer [Stackbit Support-Seite](https://stackbit.link/project-readme-support) nach.

## Colophon

Generated at `2021-07-22T14:12:10.735Z` by Stackbit version `0.3.53`.
