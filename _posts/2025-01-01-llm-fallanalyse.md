---
title: 'Üben durch Korrigieren von KI-Antworten'
date: 2025-01-01
category: tools
---

## Hintergrund

In einem früheren Post haben wir mit [LLM Chat-Anwendungen Übungsfälle
erstellt]({{ site.baseurl }}{% link
_posts/2024-12-19-fallbeispiele-selbst-erstellen.md %}). KI-Anwendungen eignen
sich **nicht** (ohne vorherige Überarbeitung) für die Erstellung von
Musterlösungen in PäPsy, da sie auch Inhalte halluzinieren, Schwerpunkte
ungünstig setzen, Konzepte falsch anwenden oder nicht in die geforderte Tiefe
gehen.

Allerdings kann es eine hilfreiche Übung sein, sich eine "Lösung" von einer
KI-Anwendung erstellen zu lassen, und die Antwort dann zu beurteilen:

- Inhaltliche Korrektheit: Welche Teile sind halbwahr oder gänzlich falsch?
- Überflüssige Anteile: Wo sollten Schwerpunkte anders gesetzt werden oder sind
  Teile der KI-Antwort für den vorliegenden Fall nebensächlich sind?
- Fehlende Inhalte: Was fehlt in der Antwort gänzlich oder wo fehlt es an
  Tiefe?
- Bezüge: Wo könnten Bezüge und Zusammenhänge deutlicher gemacht werden?
- (Alternativen: Wo gibt es Alternativen zur KI-Antwort, auch wenn die
  KI-Antwort die Anforderungen erfüllt?)

Eine solche Übung ist anspruchsvoll, da LLMs Ergebnisse plausibel klingen
lassen, auch wenn sie halbwahr oder falsch sind. Sie kann aber zur Elaboration
der Lerninhalte beitragen.

Unten finden Sie ein Beispiel für Assistenten, mit denen Sie Ausarbeitungen
erstellen können. Das Beispiel ist für die zweite Schulaufgabe in PP12. Mit
leichten Veränderungen lassen sich ähnliche Prompts auch auf andere Prüfungen
anwenden.

Das Beispielprompt unten weist die KI an, sich auf die Inhalte aus einer
angehängten Zusammenfassung zu beschränken, damit die Antwort Inhalte
verwendet, die Sie auch tatsächlich im Unterricht behandelt haben. (Die Qualität
Ihrer Zusammenfassung hat damit einen Einfluss auf die Qualität der Antwort.)

Es empfiehlt sich, bei besonders umfangreichem Lernstoff, nach Inhalten zu
unterteilen, da das **Kontextfenster** (wie viele Informationen die KI
berücksichtigen kann) begrenzt ist. Ist Ihre Zusammenfassung lang, stößt sie
vermutlich an die Grenzen des Kontextfensters.

Wir halten uns wieder an das Akronym PREP[^AIclassroom] um gute Prompts zu
entwerfen. Wenn Sie PREP noch nicht kennen, lesen Sie im [vorangegangenen
Post]({{ site.baseurl }}{% link
_posts/2024-12-19-fallbeispiele-selbst-erstellen.md %}).

Die Prompts unten sind nicht annähernd perfekt aber ein guter Ausgangspunkt,
und für die Aufgabenstellung, die KI-Antworten zu bewerten, reichen sie aus.

## Beispiel

Erkläre mir aus Sicht der Psychoanalyse wie die psychische Erkrankung in dem
Fall entwickelt wurde, den ich dir schildere. Dann erkläre, wie du in der
Beratung oder Therapie in dem Fall vorgehen würdest.

Du bist ein Experte für den Ansatz der Psychoanalyse nach Sigmund Freud.

Gehe bei jedem Ansatzpunkt der Erklärung oder den Lösungskonzepten in zwei
Schritten vor. Erkläre im ersten Schritt die Theorie (Fachbegriffe, Konzepte,
Zusammenhänge). Zentrale Fachbegriffe sollest du definieren. Im zweiten
Schritt, wende die Theorie auf das Fallbeispiel an, um entweder die Pathogenese
zu erklären oder Lösungsansätze für Beratung und Therapie zu entwickeln. In der
Anwendung sollte der Rückbezug zur Theorie hergestellt werden. Verwende in der
Theorie ausschließlich Konzepte, die in der angehängten Zusammenfassung
auftauchen. Treffe eine für die Erklärung und Lösung relevante Auswahl der
Konzepte aus der Zusammenfassung. Auch wenn du unterschiedliche Ansatzpunkte
ansprichst, sollte eine kohärente Erklärung der psychischen Erkrankung und ein
kohärentes Therapiekonzept entstehen, in die sich die einzelnen Ansatzpunkte
einfügen. Falls der Fall zu wenige Informationen enthält für eine Erklärung aus
deiner Perspektive, mache Zusatzannahmen über den Fall (z.B. bestimmte
Ereignisse in der Vergangenheit), die eine Erklärung aus deiner Perspektive
ermöglichen. Weise darauf hin, wenn du Zusatzannahmen machst und über die in
der Fallbeschreibung gebotenen Informationen hinaus gehst. Gehe erst auf
Lösungsvorschläge ein, wenn du die Pathogenese im Detail erklärt hast.

Strukturiere die Antwort mit Spiegelstrichen. Formatiere die Theorieteile der
Antwort kursiv, damit sie sich von den Anwendungsteilen abheben.

*Für andere Perspektiven müssen Sie nur die ersten Sätze und die
Zusammenfassung austauschen:*

- ... aus Sicht der Theorie der operanten Konditionierung, ... Experte für die
  Theorien von Thorndike und Skinner ...

- ... aus Sicht der sozial-kognitiven Theorie, ... ein Experte für die
  Theorien von Albert Bandura.

- ... aus Sicht der personenzentrierten Theorie ... Experte für die Theorie
  von Rogers.

*Bei meinen Versuchen mit einem Assistenten zur klassischen Konditionierung habe
ich festgestellt, dass hier ein zusätzlicher Satz zur Rolle nützlich war, sonst
waren die Anwendungsabschnitte teils gänzlich unbrauchbar.*

... aus Sicht der Theorie der klassischen Konditionierung ... Experte für die
Theorie der klassischen Konditionierung unter anderem nach Iwan Pawlow oder
John B. Watson. Du legst bei der Erklärung von psychischen Störungen mit der
Theorie der klassischen Konditionierung besonderen Wert darauf, dass sie nur so
angewendet wird, wie im Rahmen gängiger Störungsmodelle der klinischen
Psychologie üblich z.B. im Rahmen von Furchtkonditionierun.

[^AIclassroom]: Fitzpatrick, D. (2023). *The AI classroom: The ultimate guide to artificial intelligence in education.* TeacherGoals Publishing.
