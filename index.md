---
layout: layouts/home.njk
eleventyNavigation:
  key: Home
  order: 1
---

> Wer nur seine eigene Seite der Sache kennt, weiß wenig über diese. 
> 
> (J.S. Mill, Über die Freiheit)

[Coverbild] [Inhaltsverzeichnis] [Einleitung]

Argumente zu verstehen ist kein Kinderspiel. Einige sind schlicht verworren. Andere sind lückenhaft. Wiederum andere sind von trügerischer Klarheit — und erst bei einem zweiten Blick erahnt man, dass sie ganz anders funktionieren, als gedacht.

In dem Buch "Argumentationsanalyse" (G. Betz, Metzler 2020, [Link]) lernen Sie, wie man undurchsichtige Argumente verständlich macht. Drei ausführliche und praxisnahe Fallstudien (Analyse einer Pro-Kontra-Liste, Analyse eines philosophischen Klassikers, Analyse einer juristischen Urteilsbegründung) setzen Methoden der Argumentrekonstruktion gewinnbringend ein.

**argumentationsanalyse.online** soll Sie dabei unterstützen, aktiv mit dem Buch zu arbeiten und sich selbst an der Rekonstruktion von Argumenten zu versuchen. Hier finden Sie:

* [Verweise auf die in den Fallstudien rekonstruierten Texte](#texte%2C-die-in-den-fallstudien-rekonstruiert-werden)
* [Grafische Darstellungen der rekonstruierten Argumente](#grafische-darstellungen-der-rekonstruierten-argumente-(%22tafeln%22))
* [Weiterführende Lektürehinweise ("Handapparat Argumentationsanalyse")](#weiterf%C3%BChrende-lekt%C3%BCrehinweise-(%22handapparat-argumentationsanalyse%22))
* [Notizen zur Argdown-Syntax](#notizen-und-verweise-zur-argdown-syntax)
* [Hinweise für die Verwendung von Argumentationsanalyse](#hinweise-f%C3%BCr-die-verwendung-von-argumentationsanalyse)


## Texte, die in den Fallstudien rekonstruiert werden

**Kapitel 1** analysiert das Pro und Kontra staatliche Zensur. Die rekonstruierten Gründe sind vollständig im Lehrbuch abgedruckt. Sie sind dem *"Debater's Handbook"* entnommen, das erstmals 1896 erschienen und inzwischen in der 19. Auflage herausgegeben ist. In tabellarischer Form stellt das "Debater's Handbook" die je wichtigsten Argumente zeitgenössischer Debatten dar. 

**Kapitel 2** analysiert das zweite Kapitel aus John Stuart Mills klassischer Abhandlung "Über die Freiheit" (1859). Diesen Text gibt das Lehrbuch nur in Ausschnitten wieder. Folgende Ausgaben sind frei verfügbar:

* [*On Liberty* (Wikisource)](https://en.wikisource.org/wiki/On_Liberty)
* [*On Liberty* (Facsimile, Internet Archive)](https://archive.org/details/onlibertyxero00milluoft)
* [*Über die Freiheit* (Fraktur, Bayrische Staatsbibliothek)](https://reader.digitale-sammlungen.de/de/fs1/object/display/bsb10769966_00010.html)
* [*Über die Freiheit* (Fraktur, Google Books)](https://books.google.de/books?id=YMRLAAAAcAAJ&redir_esc=y)

Das Lehrbuch zitiert aus der von Michael Schefcyk und Christoph Schmidt-Petri herausgegebenen [Ausgabe](http://www.mill-institut.de/praesenz/publikationen/john-stuart-mill-band-iii1/). 

**Kapitel 3** analysiert die Entscheidungsbegründung des Bundesverfassungsgerichts im wegweisenden Lüth-Urteil. Der vollständige Beschluss ist hier verfügbar:

* [BVerfG, Beschluss des Ersten Senats vom 15. Januar 1958 - 1 BvR 400/51 -, Rn. 1-75](http://www.bverfg.de/e/rs19580115_1bvr040051.html)



## Grafische Darstellungen der rekonstruierten Argumente

Eine komplexe Argumentation, in der sich verschiedene Argumente stützend und angreifend aufeinander beziehen, lässt sich übersichtlich als sogenannte *Argumentkarte* darstellen. Ergänzend zum Buch finden Sie auf dieser Seite nicht nur alle **"Tafeln"** mit Argumentrekonstruktionen, sondern auch die entsprechenden grafischen Darstellungen (s. <a href="{{ '/posts/' | url }}">Verzeichnis der Rekonstruktionstafeln</a>). 

So zeigt etwa die folgende Argumentkarte, die auf den Tafeln <a href="{{ 'posts/tafel_01-11/' | url }}">1.11</a>, <a href="{{ 'posts/tafel_01-13/' | url }}">1.13</a> sowie <a href="{{ 'posts/tafel_01-16/' | url }}">1.16</a> beruht, wie sich die Zusammenspiel der Pro- / Kontra-Gründe aus dem Debater's Handbook nach einer vorläufigen & informellen Analyse darstellt:

```argdown-map
[Zensurgebot]: Es gibt Fälle, in denen Gesetzgebung, die bestimmte
Formen der Meinungsäußerung und -wiedergabe untersagt und 
sanktioniert, geboten ist. #pro
  <+ <Kriminalisierung>: Bestimmte Literaturformen oder visuelle 
      Darstellungen sind auf überzeugende Weise mit Kriminalität in 
      Verbindung gebracht worden. #pro {quelle: Pro2}
      <- <Kritik an Studien>: Tatsächlich ist der Zusammenhang zwischen 
        Sex und Gewalt auf der Mattscheibe und im echten Leben alles 
        andere als klar. #con {quelle: Con2}
  <+ <Jugendschutz>: Wir akzeptieren auch staatliche Zensur im Kontext der 
    Altersfreigaben für Filme, Videos und einige Computerspiele, so dass Kinder 
    unterhalb eines bestimmten Alters nicht unangemessenen Sex- und 
    Gewaltszenen ausgesetzt sind. Wir sollten den Staat, als unseren 
    moralischen Wächter, mit der Regulierung derartigen Materials – sowie 
    weiterer im Internet verfügbarer Inhalte – betrauen, um einen 
    konsistenten Schutz all unserer Kinder zu gewährleisten. #pro {quelle: Pro3}
  <+ <Schutz vor Kinder- und Hardcore-Pornografie>: Staatliche
    Zensur ist im Kontext von Kinder- und Hardcore-Pornografie
    erforderlich. Kinder sowie junge Frauen und Männer müssen vor
    der Ausbeutung durch Pornografen geschützt werden. Und die
    Gesellschaft als Ganzes sollte vor den schäbigen, ungesunden,
    unterdrückerischen und objektifizierenden Einstellungen zu
    Frauen und Sex geschützt werden, die von der Pornographie
    aufrechterhalten werden. #pro {quelle: Pro4}
    <- <Zensur unwirksam>: Nochmals: Leute werden Pornographie in 
      die Hände bekommen, sodenn sie es wollen. Zensur wird die 
      Anzahl derer, die Pornographie nutzen, nicht verändern. #con 
      {quelle: Con4}
      -> <Jugendschutz>
    <- <Erziehung effektiver>: Selbst wenn staatliche Zensur nicht
      gänzlich wirkungslos sein sollte, so gibt es doch einen viel
      effektiveren Schutz der (potentiellen) Rezipienten von
      Pornographie: Erziehung durch Eltern und Gemeinschaft. #con
      {quelle: Con4}
      -> <Jugendschutz>
      <+ <Immunisierung durch Erziehung>: Letztendlich werden
        pornographische Bilder und Filme keinen wirklich schädlichen
        Einfluss auf einen ausgeglichenen Geist haben, sondern nur
        auf diejenigen, die ohnehin aus anderen Gründen 
        unausgeglichen sind. Die Eltern und die Gemeinschaft können
        Kinder aber so erziehen, dass sie gesunde Einstellungen
        haben und so vor Pornographie geschützt sind. #con {quelle: Con4}
    <- <Kinderpornographie ohnehin illegal>: Bezüglich der
      schädlichen Auswirkungen der Produktion von Pornografie gilt:
      Der Verweis auf Kinderpornographie führt hier in die Irre – 
      denn Kinderpornografie ist bereits gesetzlich untersagt und
      wir benötigen keine weiteren Zensurgesetze, um sie zu 
      bekämpfen. #con {quelle: Con4} 
```

Die Makrostruktur der Entscheidungsbegründung im Urteil des Bundesverfassungsgerichts visualisiert die folgende Karte (vgl. insbes. Tafel <a href="{{ 'posts/tafel_03-33/' | url }}">3.33</a>):

```argdown-map
[Aufhebung und Zurückweisung]
  /* Entscheidungsbegründung aus B.II.1.,   */
  /* teils im weiteren Verlauf entfaltet    */
  <+ <Zentrale Entscheidungsbegründung>
    <+ <Sinn der Bindung der Rechtsprechung an Grundrechte>
                                                 /* +>(GS3) */
      <+ [Bindung an Grundrechte (Art. 1, Abs. 3 GG)]
      <+ [Grundrechte als objektive Wertordnung] /* (GS1)   */
    <+ <Besonders starke Grundrechte-Einwirkung>
      <+ <Verwandtschaft bürgerliches und öffentliches Recht>
                                                 /* <+(GS2) */
      <+ <Generalklauseln als Einbruchstellen>   /* <+(GS2) */
      <+ [Bedeutung Meinungsfreiheit]
  /* Einwand aus B.II.2. und Entkräftung */
    <- <Keine Wirkung außerhalb der Schranken>
      <- <Keine folgerichtige Interpretation des Verfassungssystems>
        <+  [Bedeutung Meinungsfreiheit]
  /* Einwand aus B.II.3. und Entkräftung */
    <- <Intendierte Wirkung nicht durch Grundrecht geschützt>
      <+ [Enge Auslegung Meinungsfreiheit]
        <- <Schutz der kollektiven Meinungsbildung>  
                                                 /* +>(GS6) */
        <- <Wirkung wesentlich für Werturteile>  /* +>(GS6) */
        <- <Bedeutung der allgemeinen Gesetze>   /* +>(GS6) */
  /* Einwände aus B.II.4. und Entkräftung */
    <+ [Allgemeine Gesetze im LGUrteil]
      +> [Allgemeine Gesetze privatrechtlicher Art]   
                                                 /* (GS4)   */
        <- <Experten-Argument>
          <- <Falsche Voraussetzung der Literatur>
        <+ <Symmetrie-Argument>
        <- <Gefährdung der Diskursfreiheit>
          <- <Sicherung Diskursfreiheit durch Drittwirkung>
            <+ <Besonders starke Grundrechte-Einwirkung>
```



## Weiterführende Lektürehinweise ("Handapparat Argumentationsanalyse")

::: info

Erste Anlaufstelle im Web für alldiejenigen, die Fragen zum Argumentieren haben oder auf der Suche nach Beispielen, Übungen und Lernmaterial rund um das Thema "Kritisches Denken" sind, ist das von Joe Lau (U Hong Kong) betriebene

**[Critical Thinking Web](https://philosophy.hku.hk/think/)**! 

:::


Empfehlenswerte Einführungen in die argumentative Textanalyse und die logische Rekonstruktion von Argumenten, die das Lehrbuch "Argumentationsanalyse" trefflich ergänzen: 

* **Bowell**, T. & **Kemp**, G. 2014, *Critical Thinking: A Concise Guide*, Routledge, London. [[bei genialokal]](https://www.genialokal.de/Produkt/Tracy-Bowell-Gary-Kemp-Robert-Cowan/Critical-Thinking_lid_41149758.html) 
* **Brun**, G. & **Hirsch-Hadorn**, G. 2014, *Textanalyse in den Wissenschaften: Inhalte und Argumente analysieren und verstehen*, vdf Hochschulverlag, Zürich. [[bei genialokal]](https://www.genialokal.de/Produkt/Georg-Brun-Gertrude-Hirsch-Hadorn/Textanalyse-in-den-Wissenschaften_lid_34582293.html)
* **Feldman**, R. 2014, *Reason and Argument*, Pearson, Harlow. [[bei genialokal]](https://www.genialokal.de/Produkt/Richard-Feldman/Reason-and-Argument-Pearson-New-International-Edition_lid_34221151.html) 
* **Löwenstein**, D. (im Erscheinen), *Was begründet das alles? Einführung in die logische Argumentanalyse*, Reclam, Stuttgart.

Wer sich -- mit dem Ziel, noch sicherer in der *logischen* Detailanalyse von Argumenten zu werden  -- genauer mit formaler Logik befassen möchte, greift beispielsweise zu folgenden anwendungsorientierten Lehrbüchern:

* **Hoyningen-Huene**, P. 1998, *Formale Logik*, Reclam, Stuttgart. [[bei genialokal]](https://www.genialokal.de/Produkt/Paul-Hoyningen-Huene/Formale-Logik_lid_1341852.html)
* **Salmon**, W. C. 1983, *Logik*, Reclam, Stuttgart. [[bei genialokal]](https://www.genialokal.de/Produkt/Wesley-C-Salmon/Logik_lid_1431970.html)

Welche weiteren Konzepte und Analysewerkzeuge die Philosophie bereit stellt, um Gedanken zu klären, und wie sich die Argumentanalyse in diesen Werkzeugkasten einreiht, lernt man bei: 

* **Pfister**, J. 2013, *Werkzeuge des Philosophierens*, Reclam, Stuttgart. [[bei genialokal]](https://www.genialokal.de/Produkt/Jonas-Pfister/Werkzeuge-des-Philosophierens_lid_20671008.html)

Der Argumentationsanalyse liegt das normative Ideal des logisch korrekten und widerspruchsfreien Schlussfolgerns zugrunde. Wieso aber ist es überhaupt ein Fehler, nicht folgerichtig oder gar widersprüchlich zu argumentieren? Und wer legt diese Beurteilungsstandards fest? Wie sich die Regeln des folgerichtigen und widerspruchsfreien Denkens schlicht aus dem Gebrauch unserer Sprache ergeben, das zeigen 

* **Tugendhat**, E. & **Wolf**, U. 1983, *Logisch-semantische Propädeutik*, Reclam, Stuttgart. [[bei genialokal]](https://www.genialokal.de/Produkt/Ernst-Tugendhat-Ursula-Wolf/Logisch-semantische-Propaedeutik_lid_1466460.html)

Neben den grundlegenden und sogenannten topikneutralen Gesichtspunkten des Argumentierens weisen Argumentationen auch themen- und diskursspezifische Besonderheiten auf. Diese Besonderheiten können sich etwa daraus ergeben, dass bestimmte Typen von Argumenten (Argumentationsmuster) häufig auftreten, dass eine einschlägige Begrifflichkeit mit einer ganz eigenen Logik verwendet wird oder dass komplexe Argumentationen charakteristische Makrostrukturen aufweisen. Auf derartige Besonderheiten des Argumentierens in bestimmten thematisch umrissenen Diskursen gehen ein: 

* **Alexy**, R. 1983, *Theorie der juristischen Argumentation*, Suhrkamp, Frankfurt a.M. [[bei genialokal]](https://www.genialokal.de/Produkt/Robert-Alexy/Theorie-der-juristischen-Argumentation_lid_1243350.html)
* **Hansson**, S. O. & **Hirsch-Hadorn**, G. 2016, *The Argumentative Turn in Policy Analysis. Reasoning about Uncertainty*, Springer, Cham. [[bei genialokal]](https://www.genialokal.de/Produkt/The-Argumentative-Turn-in-Policy-Analysis_lid_37686672.html)
* **Schurz**, G. 2008, *Einführung in die Wissenschaftstheorie*, WBG Wiss. Buchges., Darmstadt. [[bei genialokal]](https://www.genialokal.de/Produkt/Gerhard-Schurz/Einfuehrung-in-die-Wissenschaftstheorie_lid_25209649.html)
* **Tetens**, H. 2004, *Philosophisches Argumentieren*, Beck, München. [[bei genialokal]](https://www.genialokal.de/Produkt/Holm-Tetens/Philosophisches-Argumentieren_lid_26246791.html)


## Notizen und Verweise zur Argdown-Syntax

[Argdown](http://argdown.org) normiert die Darstellung von Argumentationsanalysen. Stützungs- und Angriffsbeziehungen zwischen Gründen und Thesen lassen sich etwa wie folgt skizzieren:

```argdown
[Erste These]
  <+ Pro-Grund A, stützt erste These
     <+ Pro-Grund B, stützt Pro-Grund A
  <+ Pro-Grund C, stützt erste These
     <- Kontra-Grund D, hinterfragt Pro-Grund C
```

Argdown unterscheidet zwischen Thesen (eckige Klammern) und Argumenten (spitze Klammern). Thesen sind Aussagen. Argumente können detailliert rekonstruiert werden und weisen dann eine Prämissen-Konklusion-Struktur auf, wobei Thesen wiederum als Prämissen oder Konklusion fungieren können. 

```argdown
// Eine These
[Dostojewskis Diktum]: Wenn Gott nicht existiert, dann ist alles erlaubt.

// Ein Argument mit der These [Dostojewskis Diktum] als Prämisse
<Moralischer Gottesbeweis>

  (1) [Dostojewskis Diktum]
  (2) Es ist nicht alles erlaubt.
  ----
  (3) Gott existiert.
```

Text, der mit zwei Schrägstrichen beginnt, wird als Kommentar interpretiert.

```argdown
// Kommentar, nützlich etwa für die Erläuterung einer Rekonstruktion
```

Eine vollständige Dokumentation der Argdown-Syntax mit zahlreichen Beispielen finden Sie auf der [Argdown-Homepage](http://argdown.org).


## Hinweise für die Verwendung von Argumentationsanalyse

Ich habe eine Argumentation rekonstruiert. Was kann ich mit der Analyse nun  anfangen? Wo ist sie nützlich? 

* In dieser <a href="{{ '/anleitung/' | url }}">**Anleitung**</a> finden Sie erste handwerkliche Vorschläge und Empfehlungen zum Verfassen argumentativer Texte. 
* Der **Showcase Climate Engineering** führt exemplarisch vor, wie sich Resultate von Argumentationsanalysen vielfältig und gewinnbringend verwenden lassen. 

::: info

In der **Climate Engineering Debatte** streiten Aktivist:innen, Politiker:innen und Wissenschaftler:innen im Kern um folgende Frage: Ist es zulässig, mit großtechnischen Eingriffe in das Klimasystem die menschengemachte Erderwärmung zu kompensieren? Betz und Cacean haben diese Debatte im Rahmen verschiedener Forschungsprojekte seit 2009 analysiert. Die Gesamtstruktur der Rekonstruktion ist als *großformatiges Poster* veröffentlicht; der Forschungsbericht ["Ethical Aspects of Climate Engineering"](http://dx.doi.org/10.5445/KSP/1000028245) zeigt exemplarisch, wie man *Argumentanalysen in Texten* präsentieren, diskutieren und auswerten kann. Hier kommen u.a. folgende Techniken zum Einsatz: Hochggregierte Makrokarte der Gesamtdebatte; feinauflösende Mikrokarten von Teildebatten; argumentative Textstrukturierung; Klassifikation von Argumenten; Darstellung und Analyse exemplarischer Positionen. Die Argumentanalyse liegt auch im interdisziplinären ["Scoping Report Climate Engineering"](https://www.kiel-earth-institute.de/scoping-report-climate-engineering.html) zugrunde; dabei bildet die Argumentkarte den gemeinsamen Bezugspunkt der ganz verschiedenen fachlichen Kapitel. Teile der Analyse sind ferner in [Videos](https://www.youtube.com/watch?v=1ETYgACfK6Y) und [interaktiven Webtools](https://www.iass-potsdam.de/modules/custom/iass_eutrace_apps/resources/ArgunetBrowser/) veröffentlicht worden.

Eine ausführlichere Präsentation des Showcases findet sich im Blog-Eintrag [Mapping the Climate Engineering Controversy](http://www.argunet.org/2013/05/13/mapping-the-climate-engineering-controversy-a-case-of-argument-analysis-driven-policy-advice/).

:::