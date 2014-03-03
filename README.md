equitable
=========
Restaurant Equitable Webseite


### Wie publiziere ich einen Artikel auf equi-table.ch?


Auf der Equi-Table Seite ist es als Benutzer möglich 3 verschiedene Artikel zu veröffentlichen: Neuigkeiten, Food-Stories und Presse-Meldungen.

In allen 3 Fällen braucht es die Vorarbeit, dass eine Grafik in der Grösse 320x320 Pixel vorbereitet ist. Mit dieser wird auf der Webseite auf den Artikel verwiesen.

**Wichtig**: Benennt man die Grafik, dürfen im Namen keine Lehrzeichen oder Sonderzeichen verwendet werden. Am besten schreibt man ohne Umlaute (äüö) und verwendet anstatt " " den Mittelstrich "-".

Meldet man sich auf der Seite http://prose.io an (man benötigt hierfür zuerst einen Zugang bei github.com) bekommt man die Übersicht über aller bestehende Artikel aufgeführt. Über "New File" kann man einen neuen Artikel erstellen. Diesen benennt man am besten, indem man anstatt "your-filename.md" einen sinnvollen Namen vergibt z.B. "NZZ-Artikel.md". Beachte: auch hier keine Lehrzeilen oder Sonderzeichen.

Verwendet man Safari als Browser kann man das 320x320 Bild nun direkt vom Schreibtisch in den Text ziehen (drag&drop). Es braucht eine kurze Weile und es kommt leider keine Rückmeldung - aber im Hintergrund wird das Bild nun auf dem Server an der richtigen Stelle gespeichert. (In der Regel um weiterarbeiten zu können muss man die Seite jetzt ein weiteres mal aufrufen, hier gibt es noch einen kleinen Fehler im Programm)

Den inhaltlichen Text im Artikel kann man ohne weiteres frei (auch mit weiteren Bildern) gestalten. Unterschiede und Vorsicht gibt es jedoch zwischen den 3 Artikel-Typen bei den Meta-Informationen:

#### Presse-Mitteilung

Hier ist es notwendig ein Pdf vorzubereiten (Achtung: es muss ein PDF sein und keine Grafik - und es sollte nicht allzu gross sein (max. 2MB)) - dieses muss im Vorab im Ordner "assets/images/presse/" gespeichert werden. Die Meta-Informationen sehen entsprechend aus:

    ---
    layout: post
    published: true
    category: presse
    title: Tagesanzeiger
    tagline: "Der Irrtum"
    asset: "Tagesanzeiger-Magazin.pdf"
    square: "Tagesanzeiger-Magazin_square.jpg"
    ---
    ### Toller Artikel



#### Foodstory

Hier wirkt es gut neben dem 320x320 ein weiteres Bild vorzubereiten mit der Breite 1140 Pixel. Dieses kann ebenso per drag&drop hochgeladen werden. Die Meta-Informationen sehen entsprechend aus:

    ---
    layout: post
    published: true
    category: galerie
    tagline: Einer unserer Entdeckungen in 2013
    square: eatgreen_logo_square.png
    image: galerie/eatgreen_logo_1140.png
    ---
    ### go wild



#### Neuigkeit

Hier gibt es nichts Besonderes. Die Meta-Informationen sehen entsprechend aus:

    ---
    layout: post
    published: true
    category: news
    title: Unserer neuen Öffnungszeiten
    square: oeffnungszeiten.png
    ---
    ## Neue Öffnungszeiten



**Abspeichern**: Nach jeder Änderungen klickt man den Speicher Knopf. Hier werden alle gemachten Änderungen angezeigt. Stimmen diese nicht, ist etwas falsch gelaufen. Manchmal hilft es die Seite neu aufzurufen. Bilder-Uploads und Text-Änderungen getrennt und nacheinander zu speichern.

**Wichtig**: Bei den Meta-Informationen muss man sehr vorsichtig sein. z.B.: funktioniert es nicht zwei verschiedene Kategorien unter "category:" anzugeben. Auch darf man nirgendwo das ":" Doppelpunkt Zeichen im Titel oder Graphik-Namen verwenden.


Weitere Änderungen an der Webseite sind auch möglich - jedoch nicht mit prose.io - sondern direkt über github.com/equitable. Hier findet man in der Regel unter der Ordnerstruktur "_posts" die jeweiligen anderen Seiten um direkt Änderungen einzuarbeiten.








