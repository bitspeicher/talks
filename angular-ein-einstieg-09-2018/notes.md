* Style anpassen
* Component info-box hinzufügen
* Component info-box stylen (shadow-dom)
* Button hinzufügen
* Button mit Click versehen (isVisible)
* Gutes SCSS-Setup einrichten:
```
            "stylePreprocessorOptions": {
              "includePaths": [
                "src/styles"
              ]
            },
```     
  in angular.json. An zwei stellen einfügen projects -> x -> architect -> ... -> unter style
* /styles/_settings.colors.scss anlegen
* /syles.scss @import 
* in info-box @import settings.color benutzen
* in app.component ein Array anlegen und mit ngFor mehrere Infoboxes ausgeben.
