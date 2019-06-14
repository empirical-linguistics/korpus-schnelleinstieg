# Und nun...?

Fassen wir kurz die wesentlichen Schritte zusammen, die wir uns in diesem Tutorial näher angeschaut haben:

- Zunächst haben wir eine Fragestellung formuliert und sie korpuslinguistisch operationalisiert.
- Wir haben Daten erhoben, indem wir im DWDS-Kernkorpus nach den beiden Wortformen, die uns interessieren, gesucht haben. Wir haben diese Daten exportiert und haben gesehen, wie man sie in ein Tabellenkalkulationsprogramm einliest.
- Anschließend haben wir die Daten mit grammatischen und semantischen Annotationen versehen. 
- Zuletzt haben wir die Daten ausgewertet und visualisiert.

Das allein macht natürlich noch keine gute linguistische Studie aus. Wir müssen uns jezt überlegen, wie die Daten zu interpretieren sind. Nicht zuletzt müssen wir aber auch unser Vorgehen kritisch hinterfragen und überlegen, welche Unzulänglichkeiten es möglicherweise mit sich bringt.


## Interpretation und Einordnung

Fangen wir mit dem ersten Punkt an, der Interpretation: In unseren Daten wird *vorprogrammiert* ausschließlich im metaphorischen Sinn verwendet und nur dann, wenn auf Resultate Bezug genommen wird. Das untermauert unsere Annahme, dass *vorpgrogrammiert* gegenüber *programmiert* eine bestimmte semantische Nische einnimmt (wenngleich es in dieser Nische durchaus stark mit der Variante ohne die Partikel *vor-* konkurriert).

Auch werden Sie sich gefragt haben, ob denn das hier durchgearbeitete Beispiel wirklich Stoff für z.B. eine ganze Seminararbeit bietet, wo wir doch am Ende der langwierigen Korpusrecherche nicht viel mehr bekommen haben als ein relativ simples Balkendiagramm. (Formulieren Sie diesen Satz gerne etwas griffiger, damit Sie ihn sich auf ein T-Shirt drucken lassen können.)

Auch wenn das hier besprochene Beispiel durchaus noch ausbaufähig ist (siehe [Methodenkritik][Methodenkritik und offene Fragen]), bietet es meines Erachtens doch genug Stoff für eine gute Hausarbeit, sofern man die Korpusanalyse in eine gute theoretische Diskussion einbettet und die hier vorgenommene quantitative Analyse vielleicht noch durch die qualitative Analyse von Einzelbelegen ergänzt. Das könnte zum Beispiel so aussehen, dass man sich zunächst in einem Theorieteil mit der semantischen Entwicklung von (nahe-)synonymen Wörtern befasst und dann am Beispiel von *(vor)programmiert* der Frage nachgeht, ob die Varianten mit und ohne Partikel unterschiedlich gebraucht werden, also unterschiedliche semantische "Nischen" ausfüllen. In einem Methodenteil kann man dann die Annotationskriterien offenlegen, ggf. Problemfälle schildern und aufzeigen, wie sie gelöst wurden. Hier kann man auch schon die Grenzen des gewählten Vorgehens ansprechen, auf die wir im nächsten Abschnitt noch näher eingehen werden. Es folgen die quantitative Analyse und die Diskussion der Ergebnisse vor dem Hintergrund der Forschungsfrage, die gerne mit der qualitativen Analyse von Korpusbelegen gespickt sein darf. In einem Schlussteil werden dann die Ergebnisse zusammengefasst, und es werden Desiderata für zukünftige Forschungen aufgezeigt – ein Punkt, auf den wir ebenfalls im nächsten Abschnitt noch eingehen werden.



## Methodenkritik und offene Fragen

Das führt uns zur Methodenkritik: Wie belastbar sind unsere Ergebnisse? Hier ist als möglicherweise problematischer Punkt zunächst die Stichprobengröße zu nennen. Im DWDS-Kernkorpus haben wir gerade einmal 88 Treffer gefunden, von denen nur rund 50 die prädikative Verwendung instanziieren, die uns interessiert. Insofern wäre zu fragen, ob wir möglicherweise besser ein anderes Korpus wählen sollten.

<details>
<summary>‣ **Zur Stichprobengröße**</summary>

Zur Frage nach der Stichprobengröße zitiere ich mich ausnahmsweise mal selbst:

> Die wahrscheinlich am häufigsten gestellte Frage von Studierenden, die zum ersten Mal korpuslinguistisch arbeiten, ist: „Wie groß muss meine Stichprobe sein?“ Darauf gibt es leider keine pauschale Antwort. Es gibt keine feste Untergrenze, ab der eine Stichprobe repräsentativ ist (zumal es „echte“ Repräsentativität in dem Sinne, dass die Stichprobe ein ganz genaues Abbild der Grundgesamtheit, nur eben im Kleinen, darstellt, ohnehin nicht geben kann). 
Die Wahl der Stichprobengröße ist also von mehreren ganz praktischen Faktoren abhängig, unter anderem: 

> a) Wie werden die Daten annotiert? Sehr viele Annotationen, die noch dazu erfordern, dass der Kontext mit einbezogen wird, sind zeitaufwendig und rechtfertigen eine kleinere Stichprobe. Arbeitet man dagegen nur mit den reinen Type- und Tokenfrequenzen, ohne eigene Annotationen hinzuzufügen, gibt es keinen Grund, überhaupt eine Stichprobe zu nehmen. In diesem Fall kann man gleich alle Daten mit einbeziehen.
> b) Wie werden die Daten ausgewertet? In manchen Fällen kann man schon mit 100 Belegen aussagekräftige Ergebnisse erzielen. Aber wenn man ein Korpus diachron auswerten möchte, das in 10 Zeitschnitte unterteilt ist, sind 100 Belege offensichtlich zu wenig – denn dann hat man bei gleicher Verteilung gerade einmal 10 Belege pro Zeitschnitt!

> Für die ersten Gehversuche z.B. in Seminararbeiten empfehle ich in der Regel, mit 100 bis 500 Belegen zu arbeiten. In den meisten Fällen genügt das, um Tendenzen aufzuzeigen, und ist vom Arbeitsaufwand her auch für AnfägerInnen bewältigbar. Aus den obigen Überlegungen sollte jedoch klar geworden sein, dass diese Zahlen völlig willkürlich sind.

<footer>--- aus: Hartmann, Stefan. 2018. Deutsche Sprachgeschichte. Grundzüge und Methoden. Tübingen: Francke, S. 206</footer>

</details>

Weiterhin müssen wir bedenken, dass wir die Verteilung der Daten nur relativ oberflächlich ausgewertet haben. Streng genommen müssten wir eine Reihe von möglicherweise problematischen Aspekten zusätzlich bedenken, denn bei Korpusdaten gibt es immer viele Faktoren, die zu unerwünschten Verzerrungen führen können. So können viele verschiedene Belege von der gleichen Person oder gar aus dem gleichen Text stammen. Tab. \@ref(tab:textverteilung) zeigt, dass 16 Belege in unserer Konkordanz, wenig überraschend, aus dem "Lexikon der Informatik" stammen... In der modernen Korpuslinguistik tendiert man daher dazu, statistische Methoden zu verwenden, mit denen man solche Variablen mit einbeziehen kann.



Table: (\#tab:textverteilung)Texte in der Konkordanz, die mehr als einen Beleg für (vor)programmiert enthalten

Text                                                                                                                                                                                                        Belege
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  -------
Rechenberg, Peter: Was ist Informatik?, München: Hanser 1994 [1991]                                                                                                                                             16
Klee, Ernst: Behinderten-Report, Frankfurt a. M.: Fischer Taschenbuch-Verl. 1981 [1974]                                                                                                                          3
Alt, Franz: Liebe ist möglich, München: Piper 1985                                                                                                                                                               2
Archiv der Gegenwart, 2001 [1975]                                                                                                                                                                                2
Bädekerl, Klaus: Werthers Freundin. In: Hoffmann, Raoul (Hg.) Auf Live und Tod, München: Dt. Taschenbuch-Verl. 1983 [1979]                                                                                       2
Die Zeit, 22.07.1999, Nr. 30                                                                                                                                                                                     2
Jung, Mathias: Der militärisch-industrielle Komplex. In: Haug, Hans-Jürgen u. Maessen, Hubert (Hgg.) Kriegsdienstverweigerer - Gegen die Militarisierung der Gesellschaft, Frankfurt a. M.: Fischer 1971         2
Ketman, Per u. Wissmach, Andreas: DDR - ein Reisebuch in den Alltag, Reinbek bei Hamburg: Rowohlt 1986                                                                                                           2
Loriot [d.i. Vicco von Bülow]: Sehr verehrte Damen und Herren ..., Zürich: Diogenes 1993                                                                                                                         2
Wilberg, Gerlinde M.: Zeit für uns, München: Frauenbuchverl. 1979                                                                                                                                                2

Das Stichwort "statistische Methoden" bringt uns zu einem weiteren Punkt, den wir hier explizit **nicht** behandelt haben: Wir haben uns nicht mit der Frage beschäftigt, ob der Unterschied zwischen den untersuchten Variablen in irgendeiner Weise statistisch signifikant ist (und was statistische Signifikanz überhaupt bedeutet). In unserem Beispiel war der Unterschied zwischen *programmiert* und *vorprogrammiert* erfreulicherweise so klar und offensichtlich, dass es einer statistischen Analyse nicht wirklich bedarf. Wenn Sie sich weiter damit beschäftigen wollen, empfehle ich die Lektüre einer der einschlägigen Einführungen.

<details>
<summary>‣ **Zum Weiterlesen: Statistik für LinguistInnen**</summary>

Hier eine Auswahl an deutsch- und englischsprachigen Einführungswerken in die Statistik, die sich explizit an Linguist*innen richten (chronologisch geordnet):

- Vanhove, Jan. 2018. Statistische Grundlagen. Eine Einführung mit Beispielen aus der Sprachforschung. https://homeweb.unifr.ch/VanhoveJ/Pub/Statistikkurs2/StatistischeGrundlagen.pdf. (zuletzt abgerufen am 14.06.2019)

- Desagulier, Guillaume. 2017. Corpus linguistics and statistics with R: introduction to quantitative methods in linguistics. New York, NY: Springer.

- Levshina, Natalia. 2015. How to do linguistics with R. Data exploration and statistical analysis. Amsterdam, Philadelphia: John Benjamins.

- Gries, Stefan Th. 2013. Statistics for Linguistics with R: A Practical Introduction. 2nd ed. Berlin, New York: De Gruyter.

- Meindl, Claudia. 2011. Methodik für Linguisten: Eine Einführung in Statistik und Versuchsplanung. Tübingen: Narr.

- Baayen, R. H. 2008. Analyzing Linguistic Data. A Practical Introduction to Statistics using R. Cambridge: Cambridge University Press.

- Butler, Christopher. 1985. Statistics in Linguistics. Oxford: Blackwell.

</details>

Über die Methodenkritik hinaus können wir natürlich auch Desiderata formulieren, also fragen, in welche Richtung wir weiterforschen können. So haben wir uns in unserem Beispiel auf prädikative Verwendungen von *(vor)programmiert* beschränkt. Das war eine sinnvolle und gut begründbare Vorentscheidung, um den Skopus der Untersuchung einzugrenzen, und deshalb nichts, was wir im Rahmen der Methodenkritik hinterfragen sollten. Gleichwohl können wir die Frage stellen, wie sich wohl die flektierten Formen von *(vor)programmieren* verhalten und ob sich ähnliche Tendenzen auch hier aufzeigen lassen. 

Es bietet sich immer an, eine Arbeit mit solchen Desiderata abzuschließen, denn keine Forschungsfrage ist je vollständig beantwortet, und jede (Teil-)Antwort wirft nahezu zwangsläufig neue Fragen auf.
