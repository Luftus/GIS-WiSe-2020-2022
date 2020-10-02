## _V_ **1.4** CSS Vertiefung

### Komplexe Selektoren
<video controls width="100%"> 
    <source src="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/01_CSS_Komplexe_Selektoren.mp4" type="video/mp4"> 
    <a href="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/01_CSS_Komplexe_Selektoren.mp4">Zum Video</a>
</video>

Man kann die grundlegenden CSS-Selektoren, die in der letzten Lektion vorgestellt wurden, auch verketten, um komplexere Selektionen zu machen. So kann entweder auf einzelne, spezielle Elemente konkret zugegriffen oder auf nur ganz bestimmte Gruppen oder Folgen von Elementen selektiert werden. Mit Pseudoklassen können auch Elemente in ganz bestimmten Zuständen manipuliert werden, wie zum Beispiel bei einem Link der Zustand des Herüberfahrens mit der Maus („hovern“).

**Links im Video**

<a href="https://flukeout.github.io">https://flukeout.github.io</a>

### Positionierung, Flussverhalten und Layout
<video controls width="100%"> 
    <source src="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/02_CSS_Flussverhalten_Positionierung.mp4" type="video/mp4"> 
    <a href="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/02_CSS_Flussverhalten_Positionierung.mp4">Zum Video</a>
</video>

Aufgrund der vielen verschiedenen Ausgabegeräte kann das Thema der Positionierung sehr komplex werden, in diesem Video wurden aber die grundlegenden Herangehensweisen erklärt.
Die Positionierung der Elemente auf einer gerenderten Seite hat oft wenig mit der Position im DOM-Tree zu tun.

Das Flussverhalten beschreibt das Verhalten der Elemente im Textfluss, sodass ein Element beispielsweise von den nachfolgenden Elementen in einer Zeile umflossen werden kann oder einen Zeilenumbruch bewirkt. Dieser Textfluss kann über Float und die Positionierung auch individuell manipuliert werden.

Für differenziertere Seiten-Arrangements kann man Eigenschaften, wie Grid oder Flexbox, nutzen.

**Links im Video**

Float:

<a href="https://codepen.io/philtim/pen/KrZmdN">https://codepen.io/philtim/pen/KrZmdN</a>

Positionierung:

<a href="https://codepen.io/philtim/pen/GwyWBP">https://codepen.io/philtim/pen/GwyWBP</a>

### Responsive Design
<video controls width="100%"> 
    <source src="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/03_Responsive_Design.mp4" type="video/mp4"> 
    <a href="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/03_Responsive_Design.mp4">Zum Video</a>
</video>

Responsive Design heißt, alle (relevanten) Endgerätegrößen zu bedienen, wie Smartphones, Laptops, Tablets, Bildschirme...

Technisch gesehen bedeutet Responsive Design im Web-Kontext, dass die Darstellung der Benutzeroberfläche zwar an unterschiedliche Ausgabegeräte angepasst wird, die Datenbasis bleibt jedoch gleich. Konzeptionell bedeutet Responsive Design, dass eine interaktive Anwendung in möglichst vielen (relevanten) Anwendungsszenarien (am Schreibtisch, unterwegs im Bus usw...) genutzt werden kann. 

In CSS lässt sich eine **adaptive** (stufenweise) oder **responsive** (stufenlose) Darstellung beispielweise durch Breakpoints und Mediaqueries oder flexible Größen- und Positionierungsanweisungen realisieren.

**Links im Video**

Responsive Cat:

<a href="http://roxik.com/cat/">http://roxik.com/cat/</a>

Responsive Design Check:

<a href="http://ami.responsivedesign.is/">http://ami.responsivedesign.is/</a>

### CSS Transition und Animation
<video controls width="100%"> 
    <source src="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/04_CSS_Transition_und_Animation.mp4" type="video/mp4"> 
    <a href="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/04_CSS_Transition_und_Animation.mp4">Zum Video</a>
</video>

Mit **Übergängen** (Transitions) und **Animationen** können in Webanwendungen zeitbasierte Effekte genutzt werden, die ein Design lebendig und flüssig wirken lassen oder dem Nutzer auf narrativer Ebene den Interaktionsfluss beschreibt. Die Animation von CSS Eigenschaften lässt sich durch viele Parameter steuern, bspw. auch durch die Definition der Beschleunigung der Animation.

**Links im Video**

CSS Transition Beispiel:

<a href="https://codepen.io/grausch/pen/XWWeZXW">https://codepen.io/grausch/pen/XWWeZXW</a>

CSS Animationen:

<a href="https://codepen.io/ajerez/pen/EaEEOW">https://codepen.io/ajerez/pen/EaEEOW</a>

Eigene Bezierkurve zeichnen:

<a href="http://cubic-bezier.com/">http://cubic-bezier.com/</a>

### Take Aways
<video controls width="100%"> 
    <source src="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/05_Take_Aways.mp4" type="video/mp4"> 
    <a href="https://lehre.gabriel-rausch.de/HFU/EIA1_static/L04/05_Take_Aways.mp4">Zum Video</a>
</video>

* Komplex verkettete Selektoren ermöglichen es, spezifischere Auswahlpfade zu erstellen.
* Elemente haben individuelle Positionen und Flussverhalten, die manipuliert werden können.
* Über Responsive Design lassen sich viele relevante Endgeräte bedienen.
* Über Transition und Animation lassen sich Elemente, oder deren Eigenschaften, animieren.


---

#### CSS Inspiration

[CSS Zen Garden](http://csszengarden.com/), eine Seite welche über 200 verschiedene CSS Styles für den gleichen HTML Inhalt gesammelt hat. Zeigt die Power von CSS sehr schön und ist gegebenenfalls auch inspirierend.

---

## **?!** Fragen und Antworten

(die Publikation der Zusammenfassung erfolgt nach dem Q&A-Termin)

Zusammenfassung von: [&lt;TawsTm&gt;](https://github.com/TawsTm)

### W3-Error wegen Id-Tag duplicate?
Jede Id sollte nur einem Objekt zugeordnet werden. Das Class-Attribut ist perfekt für mehrfache Verwendung, da man hier mehrere Objekte zuweisen kann.

### Was ist mit 6 verschiedenen komplexen Selektoren gemeint?
Eine Kombination aus verschiedenen einfachen Selektoren (Child-Selektoren, Sibling-Selektoren, Zähl-Selektoren etc.).

### Wie stellt ihr euch die Kategorisierung vor?
Die Aufgabenstellung ist mit Absicht offen gestellt. Es ist eure Styling-Entscheidung wie ihr die Kategorien aufteilt. In späteren Aufgaben werden wir den Seiteninhalt dynamisch durch JavaScript aufbauen.

### Welche Kategorien sind erlaubt?
Welche Art von Kategorie ist völlig egal. Ihr habt hier Freiheiten, damit nicht alle das gleiche machen. Es wäre natürlich schön, wenn nicht alle einen Klamottenshop machen.

### Was bedeutet „Verwenden Sie min. 2 Media-Queries?“
Es sind drei verschiedene Größen gemeint! Ein Default und zwei andere Größen. Z.B. Desktop, Tablet und Mobile, wobei Mobile eine andere Darstellung als die Desktopvariante hat. Hier können durch Media-Queries CSS-Eigenschaften überschrieben werden.

### Kann man JavaScript, wenn man TypeScript kann?
An sich ist es einfach JavaScript zu lernen, wenn man TypeScript schon kann. TypeScript wird im Endeffekt auch nur zu JavaScript-Code umgeschrieben. 

### Was haltet ihr von Bootstrap und Co.?
An sich können wir alle Aufgaben ohne Drittsoftware bearbeiten. Wahrscheinlich spart ihr dadurch auch keine Zeit. Wenn ihr Bootstrap verwenden wollt könnt ihr das gerne, sofern ihr trotzdem alle Bedingungen der Aufgabe erfüllt.

### Machen wir was mit Content-Management-Systemen?
Ihr könnt gerne Fragen dazu stellen, aber CMS werden wir nicht explicit lernen. Wir lernen hier die Grundlagen, damit ihr auch die Grundlagen, auf denen CMS aufbaut, versteht. Damit habt ihr große Vorteile um sich schnell in Programme wie Wordpress einzuarbeiten.

### PHP wird im Praktikum verlangt, was soll ich tun?
PHP ist wie Java eine Objektorientierte Sprache. Da ihr Java schon könnt sollte es relativ leicht für euch sein, PHP zu lernen.

### Wie ist PHP einzuordnen zwischen HTML, CSS und JavaScript?
Da beides Logikprogrammierung ist, kommt es am ähnlichsten an JavaScript heran. Ein Beispiel ist ein Warenkorb, welcher gefüllt wird.
