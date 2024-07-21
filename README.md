# Pico-Theme-NOS

Ein fabelhaftes und bildorientiertes Pico Theme, basierend auf dem Bootstrap-CSS Framework. Die Größe der Teaserbilder kann je Beitrag individuell eingestellt werden.

![NOS](https://repository-images.githubusercontent.com/831752170/24e5b24a-954b-4826-a05f-d291401a9334)

## Einstellungen

In der Datei `pico-theme.yml` können die folgenden exemplarischen Einstellungen vorgenommen werden:

    global_author:        Kontakt@...
    logo_weights:         [3,3,3,3,4,4,4,3, ...]
    logo_position:        ['center','center','center', ...]
    background_image:
        overlay:          blende.png
        sticky:           bg-1.jpg
        content:          bigcity-2.jpg

- `global_author` ein globaler Autor, der für alle Beiträge angezeigt wird
- `logo_weights` die Breite der Darstellung des Artikelbildes auf der Startseite (1 bis 12)
- `logo_position` Ausrichtung des Bildes innerhalb des Containers (CSS Style)
- `background_image` Angaben zum Teaser
- `overlay` Überlagerung mit transparentem PNG (im Beispiel lila nach transparent)
- `sticky` Hintergrundgrafik für das Sticky Area
- `content` Hintergrundbild für Content Bereich