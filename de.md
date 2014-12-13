# Eine Einführung in *Markdown*

Markdown ist eine **gut les- und schreibbare Auszeichnungsform**, die es ermöglicht, die **Struktur eines Textes für Menschen und Maschinen lesbar** zu machen.

Die Idee ist, Markdown-formatierte **Dokumente in ihrer Ursprungsform veröffentlichen** zu können, ohne dass sie durch komplizierte Formatierungsbefehle unleserlich gemacht werden oder spezielle Werkzeuge zur Ansicht benötigt werden.

Diese Übersicht zeigt die grundlegenden Funktionen von *Markdown*. Die [Dokumentation von Markdown (englisch)](http://daringfireball.net/projects/markdown/syntax) deckt alle Funktionen ab.


## 1. Überschriften

Schreibe für eine Überschrift eine Raute (`#`) vor eine Zeile:

```markdown
# Dies ist eine Überschrift höchster Ebene
```

In *Markdown* lassen sich durch hinzufügen weiterer `#`-Zeichen Überschriften von bis zu sechs Ebenen ausdrücken:

```markdown
# Überschrift in Ebene 1
## Überschrift in Ebene 2
### Überschrift in Ebene 3
#### Überschrift in Ebene 4
##### Überschrift in Ebene 5
###### Überschrift in Ebene 6
```


## 2. Absätze

Absätze werden durch Leerzeilen getrennt:

```markdown
# Dies ist die Überschrift

Dies ist ein einleitender Absatz. bla bla

Dies ist der zweite Absatz. Und wenn sie nicht gestorben sind, dann lesen sie noch heute.
```


## 3. Betonung

Teile von Texten können *betont* oder **als wichtig markiert** werden, so zum Beispiel:

```markdown
Teile von Texten können *betont* oder **als wichtig markiert** werden.
```


## 4. Aufzählungen

Listen werden wie folgt notiert:

```markdown
- Dies ist eine
- ungeordnete Liste,
- bestehend aus
- mehreren Punkten.

* Sternchen können auch benutzt werden,
* um ungeordnete Listen zu bilden.

1. Geordnete (nummerierte) Listen sind so einfach wie Eins,
2. Zwei,
3. Drei.

1. Verschachtelte Listen sind auch möglich.
    1. Rücke einfach mit
    2. vier Leerzeichen ein.
2. Weiter geht's!
```


## 5. Links

Hyperlinks solltest du auch schreiben können. Sie sehen so aus:

```markdown
Mehr zum Thema auf [Wikipedia](https://en.wikipedia.org).
```