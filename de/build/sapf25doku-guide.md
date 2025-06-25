---
date: Version 0.1 (25.06.2025)
links-as-notes: true
lof: false
subtitle: KI-unterstützte Dokumentation
title: SAP Learning & Adoption Forum 2025
titlepage: true
titlepage-color: 0000ff
titlepage-rule-color: ffffff
titlepage-text-color: ffffff
toc: true
toc-depth: 3
toc-own-page: true
---



# Willkommen

Das [SAP Learning and Adoption Forum
2025](https://go4.events.sap.com/eur-learning-adoption-forum/de_de/home.html)
fand am 25. Juni 2025 in Walldorf statt. Die Inhalte dieser
Dokumentation stammen aus den Aufzeichnungen der Lightning Talks,
Knowledge Cafes und Workshops.

!!! note "Hinweis" Mit der Dokumentation könnt ihr sogar mit [diesem
Chatbot](https://chatgpt.com/g/g-68591dbd8fd081918d7be3eaef14596e-sap-learning-adoption-forum-2025)
(CustomGPT, Modell GPT-4o) "reden" ... das funktioniert sogar in
natürlicher Sprache mit dem Voice Mode. Die KI-generierten
Zusammenfassungen wurden **NICHT** nachberarbeitet. Die KI kann Fehler
machen.

*Offen: wer steht im Impressum? Unter welcher Lizenz stehen die
Inhalte?*

![](https://community.sap.com/t5/image/serverpage/image-id/239155iA5FD44DFCBCAB58F/image-size/large?v=v2&px=999)

# Programm

  -----------------------------------------------------------------------------------------
  ID                Programmpunkt               Referent:innen    Affiliation
  ----------------- --------------------------- ----------------- -------------------------
  0-1               [Interview mit Yemisi                         
                    Ogunleye](0-1.md)                             

  1                 **Lightning Talks**                           

  1-1               [Appet-ai-te for            Timo Deiner       Head of Innovation &
                    disruption](1-1.md)                           Technology MEE, SAP

  1-2               [Trends in Corporate        Jochen Robes      Hochschullehrer und
                    Learning - mehr als                           Gründungsmitglied
                    KI!](1-2.md)                                  Corporate Learning
                                                                  Community

  1-3               [Superkräfte bei            Eva Stock         Chief People & Marketing
                    Mitarbeitenden - Was ist                      Officer, comspace
                    wichtig aus HR und People                     
                    Sicht?](1-3.md)                               

  2                 **Knowledge Cafes**                           

  2-1               [Collaborative Learning im  Frédéric          Head of SAP
                    SAP-Ecosystem: Key-User als Heinemann         Transformation Portfolio,
                    Mentoren der                                  Kyndryl
                    Zukunft](2-1.md)                              

  2-2               [12 Freunde müsst ihr       Bernhard Rupp,    Kreislead HR-IT &
                    sein](2-2.md)               Andreas Kübli     Support,
                                                                  Transformationsmanager,
                                                                  BLS AG

  2-3               [Weichenstellung fürs       Florence Streif   Senior Change Consultant
                    digitale Zeitalter:                           & systemisches Coaching,
                    Zwischen Bahnhof und                          ÖBB
                    Besprechungsraum](2-3.md)                     

  2-4               [KI im Lern-Lifecycle: PoC  Moritz Huber      Head of SAP Learning
                    für KI-gestütztes                             Services MEE, SAP
                    Anwenderlernen](2-4.md)                       

  2-5               [SAP Enable Now trifft auf  Mike Fritz,       Product Expert Enable
                    WalkMe und die SAP          Christoph Kernke  Now, Head of Integrated
                    Integrated                                    Toolchain Services, SAP
                    Toolchain](2-5.md)                            

  2-6               [Von der Einführung zur     Patrick Fueldner  Senior IT Product Manager
                    Skalierung: Nestlés Digital                   Digital Enablement,
                    Adoption-Strategie mit                        Nestlé
                    WalkMe](2-6.md)                               

  2-7               [Big Bang - 40 Länder, 800  Katja Sommerer    Leading IT Project
                    neue Mitarbeitende -                          Manager, Endress+Hauser
                    Herausforderungen des                         Gruppe
                    Trainings in einem                            
                    M+A-Projekt](2-7.md)                          

  2-8               [HR neu gedacht: BARMERs    Andrea Flöth      Manager HR
                    digitale Evolution mit                        Transformation, BARMER
                    Hilfe von SAP Preferred                       
                    Success](2-8.md)                              

  2-9               [Übersetzer der Moderne:    Mareike Muth      Gruppenleitung
                    Das Learning Team als                         Wissensmanagement, MEWA
                    Katalysator zwischen                          
                    Fachbereich und                               
                    Enduser](2-9.md)                              

  2-10              [State of GenAI - was in    Simon Dückert     Spezial-Experte
                    meiner Wissensarbeit                          Wissensmanagement &
                    wirklich, wirklich                            Lernende Organisationen,
                    funktioniert](2-10.md)                        Scholarch Cogneon
                                                                  Akademie

  3                 **Hands-on Workshops**                        

  3-1               [Promptathon](3-1.md)                         

  3-2               [Discovery Workshop AI                        
                    UseCases im                                   
                    Learning](3-2.md)                             

  3-3               [Good Practices & Lessons                     
                    Learned SAP S/4HANA                           
                    Transformationen](3-3.md)                     
  -----------------------------------------------------------------------------------------

# Workflow der KI-generierten Zusammenfassung

Um die KI-basierte Dokumentation den Teilnehmenden schon während der
Veranstaltung bereitstellen zu können, wurde die Auswertung und
Bereitstellnug der Inhalte weitgehend automatisiert:

![](./images/ai-documentation-chain.png)

1.  Die **Aufzeichnungen** (*Format: mp4*) der Beiträge werden von den
    Room Buddies in einen zentralen Onedrive-Ordner hochgeladen.
2.  Die Aufzeichnungen werden aus einem von
    [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) (Modell:
    whister-large-v3-turbo) beobachteten Ordner automatisch
    **transkribiert** (*Format: txt*).
3.  Die Transkripte werden mit der App [Chatbox](https://chatboxai.app/)
    mit einem dort angelegten Copilot (nicht Microsoft Copilot) nach
    einheitlichem Schema **zusammengefasst** (Format: md). *(noch
    festzulegen, aktuell: Zusammenfassung, Gliederung, Kernaussagen,
    Offene Fragestellungen, Handlungsempfehlungen, Thesen, Abschluss)*.
4.  Die Zusammenfassungen werden in der **Repo-Struktur** von
    [lernOS](https://lernos.org) in einem Github-Repository abgelegt.
5.  Mit der **lernOS Produktionskette** wird aus den Markdown-Dateien
    automatisch diese Web-Version sowie weitere Formate zum Download
    (pdf, html, docx, md) erzeugt.
6.  Die Markdown-Version (mit allen Zusammenfassungen) wird als
    **"Wissensbasis" für einen Chatbot** auf Basis eines
    [CustomGPT](https://help.openai.com/en/articles/8554397-creating-a-gpt)
    verwendet. Nutzende können so mit der Zusammenfassung der
    Veranstaltung "sprechen".
7.  Interessenten können sich eine **Markdown-Version der
    Dokumentation** unter *Download* zusätzlich herunterladen, um sie in
    eigenen KI-Tools wie z.B. [Microsoft
    Copilot](https://www.microsoft.com/de-de/microsoft-copilot/organizations),
    [SAP
    Joule](https://www.sap.com/germany/products/artificial-intelligence/ai-assistant.html),
    [Gemini](https://gemini.google.com/),
    [NotebookLM](https://notebooklm.google/), [Le
    Chat](https://chat.mistral.ai/) (europäisch) oder lokalen KI-Tools
    ([LM Studio](https://lmstudio.ai/),
    [Chatbox](https://chatboxai.app/),
    [GPT4All](https://www.nomic.ai/gpt4all), [Open
    WebUI](https://openwebui.com/)) zu verwenden.

## Interview mit Yemisi Ogunleye

> Am Vorabend des Forums führten Thomas Jenewein und Seyde Sosnovski ein
> Interview mit der Olympiasiegering im Kugelstoßen [Yemisi
> Ogunleye](https://de.wikipedia.org/wiki/Yemisi_Ogunleye).

**Das Interview mit Yemisi Ogunleye, der amtierenden Olympiasiegerin im
Kugelstoßen, zeigt eindrucksvoll auf, wie Prinzipien und Methoden aus
dem Spitzensport erfolgreich auf die Unternehmenswelt übertragen werden
können. Die Athletin teilt ihre Erfahrungen zu Veränderungsmanagement,
mentaler Stärke, Teamarbeit und kontinuierlichem Lernen und bietet dabei
konkrete Handlungsempfehlungen für Führungskräfte und Teams in der
Wirtschaft.**

### Aufbau und Struktur des Interviews

Das Gespräch gliederte sich in mehrere thematische Schwerpunkte:

- **Umgang mit Veränderungen**: Ogunleye erklärt ihre Herangehensweise
  an berufliche und persönliche Wendepunkte. Sie betont die Wichtigkeit,
  Veränderungen als Chancen zu begreifen und positiv anzunehmen.
- **Aktivierung von "Superkräften" und mentalem Training**: Die
  Olympiasiegerin teilt ihre Methoden zur mentalen Vorbereitung und
  Visualisierung. Sie beschreibt konkrete Techniken, um in
  entscheidenden Momenten Höchstleistungen abzurufen.
- **Rolle von Emotionen und Authentizität**: Ein zentrales Thema ist die
  Bedeutung emotionaler Offenheit im professionellen Umfeld. Ogunleye
  plädiert für mehr Authentizität und das Zulassen von Freude am
  Arbeitsplatz.
- **Lernen und Entwicklung im Spitzensport**: Die Athletin erläutert
  ihre Lernstrategien und betont besonders den Wert des Scheiterns. Sie
  zeigt auf, wie Rückschläge als wichtige Entwicklungschancen genutzt
  werden können.
- **Teamarbeit und Wertschätzung**: Trotz ihrer individuellen Erfolge
  hebt Ogunleye die Bedeutung ihres Unterstützungsteams hervor. Sie gibt
  konkrete Tipps zur praktischen Wertschätzung von Teammitgliedern.
- **Umgang mit Erfolg und Misserfolg**: Die Olympiasiegerin teilt ihre
  Strategien für den Umgang mit Höhen und Tiefen. Sie erklärt, wie sie
  sowohl Siege als auch Niederlagen konstruktiv verarbeitet.

### Kernaussagen

#### Veränderungen als Chance begreifen

Ogunleye betont die fundamentale Bedeutung der richtigen Einstellung zu
Veränderungen: *"Veränderungen sind nicht immer unbedingt was Negatives
und ich versuche Veränderungen erstmal mit einer positiven Art und Weise
anzunehmen."* Ihre eigene Karriere illustriert dies eindrucksvoll -- der
verletzungsbedingte Wechsel vom Siebenkampf zum Kugelstoßen führte
letztendlich zu olympischem Gold.

Die Athletin beschreibt ihre anfänglichen Ängste vor der
Spezialisierung: *"Von sieben Disziplinen plötzlich nur noch eine
Disziplin und dann ausgerechnet Kugelstoßen."* Doch sie erkannte, dass
*"Kugelstoßen an sich auch so viele Facetten hat und eine extrem schöne,
aber gleichzeitig auch eine sehr herausfordernde Disziplin ist."*

#### Mentale Stärke als entscheidender Erfolgsfaktor

Der Schlüssel zu Höchstleistungen liegt laut Ogunleye in der mentalen
Vorbereitung: *"Man kann so fit sein, wie man will und so gut sein im
Kraftraum, wie man will. Aber wenn ich an Tag X nicht in der Lage bin,
meinen Körper so zu steuern, dass ich an dem Tag Höchstleistungen
bringe, bringt mir auch die ganze harte Arbeit nichts."*

Ihre Visualisierungstechniken umfassen sowohl positive als auch negative
Szenarien: *"Ich stelle mir oft vor, wie ich auch auf Versagen reagiere.
Es gehört auch dazu, dass im Wettkampf nicht immer alles läuft."* Diese
mentale Vorbereitung bewährte sich bei den Olympischen Spielen, als sie
im ersten Versuch ausrutschte, aber dennoch Gold gewann.

#### Emotionen als Erfolgskatalysator

Ogunleye plädiert für mehr Authentizität und emotionale Offenheit: *"Die
Freude, die man hat, auch mit in die Arbeitswelt zu nehmen, auch in die
Sportlerwelt mit reinzunehmen."* Sie empfiehlt, sich an den
ursprünglichen Grund der Begeisterung zu erinnern: *"Mir hilft es immer
wieder, mich an den Punkt zurückzuerinnern, wo ich mich das erste Mal in
diesen Sport verliebt habe."*

#### Lernen durch Scheitern

Ein zentraler Baustein ihrer Entwicklung ist der konstruktive Umgang mit
Rückschlägen: *"Was wirklich der größte Lerneffekt für mich in den
letzten Jahren war, ist das Versagen."* Sie betont: *"Ich finde, dass
auch Herausforderungen oder auch Verletzungen oder wie auch immer man
das nennt, Teil von dem Prozess sind, Teil des Lernprozesses, der
Entwicklung sind, die man aktiv annehmen sollte."*

#### Teamarbeit und Wertschätzung

Trotz ihrer individuellen Erfolge hebt Ogunleye die Bedeutung ihres
Teams hervor: *"Ich sage immer nicht, ich bin Olympiasiegerin geworden,
sondern das war eine Teamarbeit. Wir haben das gemeinsam auf die Beine
gestellt und hinbekommen."*

Konkrete Wertschätzung zeigt sie durch: *"Ganz praktisch, nach jedem
Training mich zu bedanken"* und *"ein einfaches Dankeschön wird, glaube
ich, einfach auch oftmals unterschätzt und wird einfach so sehr
gebraucht."*

### Offene Fragestellungen

Während des Interviews wurden mehrere wichtige Fragen aufgeworfen:

- **Nachhaltigkeit von Motivation**: Wie können Teams langfristig ihre
  Begeisterung aufrechterhalten, besonders in schwierigen Phasen?
- **Balance zwischen Individualität und Teamleistung**: Wie lassen sich
  persönliche Emotionen und Authentizität in teamorientierten
  Arbeitsumgebungen optimal einsetzen?
- **Übertragbarkeit von Visualisierungstechniken**: Welche Anpassungen
  brauchen mentale Trainingsmethoden für verschiedene
  Unternehmensbereiche?
- **Messbarkeit von "weichen" Faktoren**: Wie können Unternehmen den
  Erfolg von emotionaler Intelligenz und mentaler Stärke quantifizieren?

### Handlungsempfehlungen für die Unternehmenspraxis

**Sofortige Umsetzungsmaßnahmen:**

- **Tägliche Dankbarkeitsrituale einführen**: *"Ein einfaches
  Dankeschön"* nach Meetings oder Projektabschlüssen etablieren
- **Visualisierungstechniken implementieren**: 5-10 Minuten täglich für
  mentale Vorbereitung auf wichtige Termine oder Herausforderungen
  einplanen
- **Positive Selbstgespräche fördern**: *"Morgen wird ein besserer Tag,
  die Sonne wird wieder scheinen"* als Grundhaltung in schwierigen
  Situationen

**Strategische Entwicklungsansätze:**

- **Scheitern als Lernchance etablieren**: Eine Unternehmenskultur
  schaffen, die Fehler als wertvollen Teil des Entwicklungsprozesses
  betrachtet
- **Emotionale Authentizität fördern**: *"Zu sein, wie man einfach ist"*
  und Freude am Arbeitsplatz zulassen
- **Teamziele gemeinsam definieren**: *"Als Team zusammenzuarbeiten,
  sich gewisse Ziele als Team zu stecken"*
- **Langfristige Vision entwickeln**: Das große Ziel im Blick behalten,
  auch wenn einzelne Tage nicht optimal verlaufen

**Führungsempfehlungen:**

- **Regelmäßige Wertschätzung ausdrücken**: Nicht nur bei großen
  Erfolgen, sondern auch für tägliche Beiträge danken
- **Mentale Gesundheit priorisieren**: Zeit und Ressourcen für die
  psychische Vorbereitung und Regeneration einplanen
- **Diversität in Herangehensweisen fördern**: Verschiedene Methoden der
  Zielerreichung respektieren und unterstützen

Die Erkenntnisse aus Ogunleyes Spitzensport-Erfahrung zeigen, dass
erfolgreiche Unternehmensführung weit über fachliche Kompetenz
hinausgeht. Mentale Stärke, emotionale Intelligenz und authentische
Teamarbeit sind entscheidende Faktoren für nachhaltigen Erfolg -- sowohl
im Sport als auch in der Wirtschaft.

# Impulsvorträge

## Timo Deiner: Appet-ai-te for disruption

Timo präsentierte in seinem Vortrag eine eindringliche Analyse der
exponentiellen Entwicklung von Technologien, insbesondere der
Künstlichen Intelligenz. Mit kreativen Analogien zu Guns N' Roses und
historischen Beispielen verdeutlichte er die Notwendigkeit,
traditionelle Denkweisen zu überwinden und die disruptive Kraft neuer
Technologien zu verstehen. Der Vortrag fokussierte auf SAPs AI-Strategie
mit Joule als zentralem Interface und betonte die Bedeutung der
menschlichen Komponente bei der technologischen Transformation.

### Gliederung und Aufbau des Vortrags

#### Exponentielles vs. lineares Denken

Deiner begann mit einer fundamentalen Unterscheidung zwischen linearem
und exponentiellem Wachstum. Er verdeutlichte dies durch ein
einprägsames Beispiel: *"Wenn jetzt aber 30 exponentielle Schritte
vorangeht, dann geht ihr quasi erst ein Meter, dann zwei Meter, dann
vier, acht, 16 und so weiter und so fort. Am Ende seid ihr nach diesen
30 exponentiellen Schritten 26 Mal um die Welt gelaufen."*

#### Historische Perspektive auf AI

Der Referent verwies auf die historischen Wurzeln der AI-Entwicklung,
beginnend mit Alan Turing und dem Turing-Test von 1950 sowie Josef
Weizenbaum und dem ersten Chatbot "Elisa" in den 1960er Jahren. Diese
historische Einordnung unterstrich, dass der Wunsch nach
menschenähnlichen Maschinenfähigkeiten kein neues Phänomen ist.

#### SAPs AI-Strategie und Joule

Ein zentraler Teil des Vortrags widmete sich SAPs konkreter
AI-Implementierung. Deiner stellte Joule als einheitliches Interface
vor, das als *"euer UI der Zukunft"* fungiert und die Komplexität
verschiedener Systeme für den Anwender reduziert.

#### Von Hype zur Realität: Agenten als Game-Changer

Der Referent identifizierte 2025 als das Jahr des Übergangs vom AI-Hype
zur praktischen Anwendung. Besonders betonte er die Bedeutung von
AI-Agenten: *"Agenten sind letztendlich wie Mitarbeitende für mich, wie
extrem gute Werkstudenten, vielleicht New Hires etc., die einfach
selbstständig die Arbeit finden und selbstständig Lösungen erarbeiten."*

### Kernaussagen des Vortrags

- **Exponentielles Wachstum verstehen**: *"Das ist typisches lineares
  Denken, das ist ganz, ganz normal. In Wahrheit sieht die Welt aber
  halt vor allem bei Technologie eigentlich eher so aus."* Deiner warnte
  vor der Unterschätzung exponentieller Entwicklungen.
- **SAPs rasante AI-Entwicklung**: Die Zahlen sprechen für sich - von 90
  AI Use Cases im Oktober auf über 230 im Mai bis zu geplanten 430 Ende
  des Jahres.
- **Der iPhone-Moment**: *"Nur irgendwann, weil es ja immer wieder
  besser wird \[...\] kommt dieser berühmte iPhone-Moment. Dann kommt
  was, wo keiner damit gerechnet hat."*
- **Technologie und Mensch vereinen**: *"Alles, was wir machen, sollte
  nie rein aus einer IT-Perspektive betrachtet werden, sondern immer IT
  und End-User zusammen."*
- **Zeit für Kreativität gewinnen**: AI sollte helfen, *"dass wir wieder
  ein bisschen mehr Zeit haben, Dinge zu tun, kreativ zu werden, Dinge
  neu zu denken."*

### Offene Fragestellungen

#### Strategische Herausforderungen

- Wie können Unternehmen den Übergang von linearem zu exponentiellem
  Denken erfolgreich vollziehen?
- Welche Rolle spielt die menschliche Komponente bei der zunehmenden
  Automatisierung durch AI-Agenten?
- Wie kann die Balance zwischen technologischer Innovation und
  Anwenderakzeptanz gewährleistet werden?

#### Technische Implementierung

- Wie entwickelt sich die Integration verschiedener AI-Systeme in einer
  einheitlichen Plattform?
- Welche neuen Kompetenzanforderungen entstehen für Mitarbeitende im
  Umgang mit AI-Agenten?
- Wie kann die Komplexität der IT-Infrastruktur trotz vereinfachter
  Benutzeroberflächen bewältigt werden?

### Handlungsempfehlungen

#### Sofortmaßnahmen

- **Aktive Auseinandersetzung beginnen**: *"Jetzt ist die Zeit
  loszulegen, auch wenn noch nicht alles perfekt ist, aber jetzt ist die
  Zeit, sich mit diesen Sachen zu beschäftigen."*
- **Praxisorientierung statt Hype**: *"Wir sollten aufhören,
  irgendwelche Actionfiguren auf LinkedIn zu posten und dafür Ressourcen
  zu verschwenden, sondern jetzt mal wirklich gucken, wo kann uns AI im
  Alltag dann eben helfen."*

#### Strategische Ansätze

- **Doppelte Transformation**: Sowohl technologische als auch
  menschliche Transformation vorantreiben, da *"alle Mitarbeitenden"*
  mitgenommen werden müssen
- **Challenge-Mentalität entwickeln**: Wie Gutenberg mit seinem
  *"Challenge accepted"* sollten Unternehmen weniger Energie darauf
  verwenden zu erklären, *"warum was nicht funktioniert"*
- **Ganzheitlicher Ansatz**: Integration von IT und
  End-User-Perspektiven von Beginn an

#### Langfristige Positionierung

- Vorbereitung auf die Ära der AI-Agenten als *"nächster Hot Shit"*
- Aufbau einer einheitlichen Plattformstrategie zur Vermeidung der
  *"Welcome to the Jungle"*-Komplexität
- Fokus auf die Aktivierung menschlicher Superkräfte durch
  AI-Unterstützung

Der Vortrag schloss mit einem eindringlichen Appell: Die Zeit des reinen
Experimentierens mit AI ist vorbei - jetzt geht es um die praktische
Umsetzung und die Nutzung von AI als Werkzeug zur Befreiung menschlicher
Kreativität und Produktivität.

## Jochen Robes - Trends in Corporate Learning - mehr als KI!

Jochen Robes, bekannt für seinen Weiterbildungsblog und
Gründungsmitglied der Corporate Learning Community, präsentierte in
seinem Vortrag aktuelle Trends im Corporate Learning mit einem
spezifischen Fokus auf zwei zentrale Bereiche: KI-Kompetenzen und
Peer-Learning. Der Vortrag beleuchtete die Diskrepanz zwischen
theoretisch vorhandenen KI-Kompetenzmodellen und der praktischen
Umsetzung in Unternehmen und stellte Peer-Learning als mögliche Lösung
zur Schließung dieser Lücke vor.

#### Gliederung und Aufbau des Vortrags

**KI-Kompetenzen im Kontext von Future Skills**

Robes ordnete KI-Kompetenzen zunächst in den größeren Rahmen der Future
Skills ein und betonte deren nahtlose Integration in bestehende
Kompetenzmodelle. Er stellte fest: *"Wir haben ein relativ klares Bild
davon, was hinter KI-Kompetenzen steckt"* und verwies auf bereits
vorhandene, prominente Kompetenzmodelle für KI-Kompetenzen.

Ein zentraler Aspekt war die Verbindung zu Handlungskompetenzen. Der
Referent betonte: *"Es muss darum gehen, KI-Kompetenzen in der Praxis zu
erwerben"*, wodurch deutlich wurde, dass es nicht um reine
Wissensansammlung geht, sondern um praktische Anwendungskompetenz.

**Die Kompetenzlücke in der Praxis**

Trotz vorhandener theoretischer Konzepte diagnostizierte Robes eine
erhebliche Lücke zwischen Theorie und Praxis. Er verwies auf aktuelle
Studien, die zeigen, dass *"es mit der KI-Kompetenz, was Schulung,
Entwicklung, Praxis angeht, noch nicht so gut bestellt ist"*.

Besonders problematisch sei die Diskrepanz zwischen zwei
Geschwindigkeiten: - Einerseits die Integration von KI in
Geschäftsmodelle und -strategien - Andererseits Mitarbeitende, die *"da
einfach noch deutlich hinterherhinken"*

**L&D und der Fokus auf Effizienz**

Im Bereich Learning & Development (L&D) beobachtete Robes eine starke
Konzentration auf Effizienzsteigerung. KI-Tools werden primär genutzt,
um *"bestehende Prozesse effizienter zu machen"*, beispielsweise bei der
Herstellung, Übersetzung und Individualisierung von Lernmaterialien.

Kritisch merkte er an, dass Experten dazu raten, *"nicht nur auf diese
Automatisierungsschiene"* zu schauen, sondern KI-Möglichkeiten zu
nutzen, um *"Weiterbildung auch mal ganz anders zu denken"*.

**Peer-Learning als Lösungsansatz**

Als Alternative zu traditionellen Trainingsformaten stellte Robes
Peer-Learning vor. Er definierte es als Lernen *"voneinander und
miteinander, ohne dass Trainerinnen, Expertinnen, Referentinnen eine
tragende Rolle haben"*.

Das Praxisbeispiel der Deutschen Telekom verdeutlichte die Umsetzung:
Eine Plattform, auf der Mitarbeitende eigenständig 45-minütige
Wissenssessions anbieten können, ohne dass eine Trainingsabteilung
involviert ist. *"Jeder kann dort den Kalender nutzen und kann sagen,
ich habe Wissen zum Thema XY und möchte das gerne mit anderen teilen."*

#### Kernaussagen des Vortrags

- **Theorie-Praxis-Gap**: *"Wir haben einen großen Gap, was das Thema
  KI-Kompetenzen angeht, was Schulungen angeht"*
- **Handlungsorientierung**: *"Es kann nicht darum gehen, Wissen in
  diesem Gebiet anzusammeln, sondern es muss darum gehen, KI-Kompetenzen
  in der Praxis zu erwerben"*
- **Peer-Learning als Brücke**: *"Aus meiner Sicht könnte Peer-Learning
  hier eine Lücke schließen"*
- **Vielfalt der Formate**: Robes präsentierte eine breite Palette an
  Peer-Learning-Formaten, von Communities of Practice über Working Out
  Loud bis hin zu Learning Circles und Promptatons

#### Offene Fragestellungen

Während des Vortrags wurden mehrere zentrale Fragen aufgeworfen:

- Wie kann die Lücke zwischen vorhandenen KI-Kompetenzmodellen und der
  praktischen Umsetzung in Unternehmen geschlossen werden?
- Wie können Mitarbeitende ohne traditionelle Trainingsformate an
  KI-Kompetenzen herangeführt werden?
- Welche Rolle sollte L&D jenseits der reinen Effizienzsteigerung bei
  der KI-Integration spielen?
- Wie kann Peer-Learning systematisch in Unternehmen verschiedener
  Größen implementiert werden?

#### Handlungsempfehlungen

Aus dem Vortrag lassen sich folgende konkrete Handlungsempfehlungen
ableiten:

- **Praxisorientierung fördern**: Unternehmen sollten KI-Kompetenzen
  durch praktische Anwendung entwickeln, nicht durch reine
  Wissensvermittlung
- **Peer-Learning-Formate einführen**: Implementation von einfachen
  Formaten wie Kalender-basierten Wissenssessions nach dem
  Telekom-Vorbild
- **Über Effizienz hinausdenken**: L&D sollte KI nicht nur zur
  Prozessoptimierung nutzen, sondern grundsätzlich neue Lernansätze
  entwickeln
- **Niedrigschwellige Angebote schaffen**: Peer-Learning-Formate mit
  geringen Einstiegshürden etablieren, die Mitarbeitende eigenständig
  nutzen können
- **Vielfalt der Formate nutzen**: Verschiedene Peer-Learning-Methoden
  (Barcamps, Learning Circles, Working Out Loud) je nach
  Unternehmenskontext einsetzen
- **Kontinuierliche Weiterbildung**: Regelmäßige Beschäftigung mit
  aktuellen Trends durch Newsletter und Fachpublikationen

Der Vortrag verdeutlichte, dass die Zukunft des Corporate Learning in
der Kombination aus technologischer Innovation und menschenzentrierten,
kollaborativen Lernformaten liegt. Peer-Learning bietet dabei einen
vielversprechenden Ansatz, um die Kluft zwischen theoretischen
KI-Kompetenzmodellen und praktischer Anwendung zu überbrücken.

## Eva Stock: Superkräfte bei Mitarbeitenden - Was ist wichtig aus HR und People Sicht?

Eva thematisiert in ihrem Vortrag die Bedeutung individueller
menschlicher Stärken - sogenannte "Superkräfte" - im Arbeitskontext. Sie
plädiert für einen Paradigmenwechsel von der traditionellen
Schwächenfokussierung hin zur bewussten Wahrnehmung und Förderung der
einzigartigen Qualitäten jedes Mitarbeitenden. Dabei betont sie die
zentrale Rolle von HR und Führungskräften als "Superkräfte-Scouts" und
fordert eine Unternehmenskultur, die Menschen als Ganzes sieht und
wertschätzt.

### Gliederung und Aufbau des Vortrags

Der Vortrag gliedert sich in vier wesentliche Themenbereiche:

- **Definition und Abgrenzung von "Superkräften"** - Klärung des
  Begriffs jenseits übermenschlicher Fähigkeiten
- **Problematik der aktuellen Bewertungssysteme** - Kritik am
  Schwächenfokus in Unternehmen
- **Rolle von HR und Führungskräften** - Verantwortlichkeiten bei der
  Erkennung und Förderung
- **Kulturelle Voraussetzungen und Handlungsempfehlungen** - Notwendige
  Rahmenbedingungen für erfolgreiche Umsetzung

### Kernaussagen des Vortrags

**Definition von Superkräften:** *"Wenn wir hier jetzt über Superkräfte
sprechen, dann meine ich nicht übermenschliche Kräfte... sondern mir
geht es vor allem um individuelle menschliche Stärken."* Stock definiert
Superkräfte als Qualitäten wie Empathie, Klarheit, Humor, Geduld,
Beharrlichkeit, strukturelles Denken oder Konfliktfähigkeit.

**Ganzheitliche Betrachtung des Menschen:** *"Menschen wollen als Ganzes
gesehen werden... Es geht ja nicht nur darum, eine Rolle zu erfüllen, zu
funktionieren, irgendwie abzuarbeiten, Haken zu machen, sondern ich bin
ja auch ein Individuum."* Die Referentin betont die Wichtigkeit,
Mitarbeitende nicht nur in ihrer beruflichen Rolle zu sehen.

**Kritik am Schwächenfokus:** *"Wir rutschen in Feedback oder
Bewertungsgesprächen quasi fast automatisch... in den Schwächenfokus.
Also es geht immer darum, was fehlt eigentlich noch... als zu gucken,
was kannst du eigentlich wirklich gut."* Stock kritisiert die
traditionelle Fokussierung auf Defizite statt auf Stärken.

**Führungskräfte als Schlüsselakteure:** *"Führungskräfte sind für mich
schon auch diese Superkräfte-Scouts."* Sie sieht Führungskräfte in einer
zentralen Position bei der Identifikation individueller Stärken.

**Psychologische Sicherheit als Grundvoraussetzung:** *"Es braucht
natürlich psychologische Sicherheit... damit man überhaupt in diese
Gespräche gehen kann, weil wenn ich Angst habe, mich zu zeigen, auch
vielleicht mit meinen Schwächen, kann das Gespräch überhaupt nicht in
diese Richtung geleitet werden."*

### Offene Fragestellungen

Während des Vortrags werden mehrere zentrale Fragen aufgeworfen, die zur
Reflexion anregen:

- *"Was gelingt dir eigentlich gut, was anderen schwerfällt?"*
- *"Was macht dir Freude? Wo kommst du in den Flow rein?"*
- *"Was fällt dir leicht, was anderen schwerfällt?"*
- *"Welche Superkräfte habe ich eigentlich selbst, die eben nicht auf
  meinem CV stehen?"*

Diese Fragen zielen darauf ab, sowohl bei Führungskräften als auch bei
Mitarbeitenden ein Bewusstsein für verborgene Stärken zu schaffen und
neue Gesprächsräume zu öffnen.

### Handlungsempfehlungen

**Für HR-Verantwortliche:** - Entwicklung guter Prozesse, Frageformate
und Instrumente zur Stärkenerkennung - Schaffung von Awareness für die
Existenz und Bedeutung individueller Stärken - Bereitstellung von Tools
und Systemen zur Aufbereitung und Messbarmachung der Erkenntnisse -
Implementierung von Peer-Feedback-Systemen

**Für Führungskräfte:** - Anwendung stärkenorientierter Fragetechniken
in One-on-One-Gesprächen - Entwicklung einer Sensibilität für
individuelle Verhaltensweisen und Stimmungen - Übernahme der Rolle als
"Superkräfte-Scout" im Team - Praktizierung individueller Führung je
nach Bedürfnissen der Mitarbeitenden

**Für die Unternehmenskultur:** - Schaffung psychologischer Sicherheit
als Grundvoraussetzung - Ermöglichung einer Kultur der Entwicklung statt
reiner Skill-Verwaltung - Akzeptanz, dass *"es okay ist, mal nicht zu
funktionieren... und nicht immer High Potential zu sein"* - Offenheit
für Entwicklungsmöglichkeiten auch außerhalb des Unternehmens

**Für alle Beteiligten:** - Regelmäßige Selbstreflexion über eigene
Superkräfte - Aktive Kommunikation über individuelle Bedürfnisse und
Stärken - Wertschätzender Umgang mit unterschiedlichen
Persönlichkeitstypen

Stock schließt mit einem eindringlichen Appell: *"Ich würde mir einfach
wünschen, dass ihr rausgeht und merkt, es gibt diese Superkräfte
überall."* Sie fordert eine grundlegende Veränderung in der Art, wie
Unternehmen mit ihren Mitarbeitenden umgehen - weg von standardisierten
Bewertungsschablonen hin zu einer individuellen, wertschätzenden
Betrachtung jedes Menschen mit seinen einzigartigen Stärken und
Potenzialen.

# Lightning Talks

## Frédéric Heinemann - Collaborative Learning im SAP-Ecosystem - Key-User als Mentoren der Zukunft

Frederik von Kyndril präsentierte in diesem Knowledge Café innovative
Ansätze zur Transformation der Key User-Rolle in SAP-Projekten. Der
Vortrag beleuchtete die chronischen Herausforderungen traditioneller Key
User-Konzepte und stellte collaborative Learning-Methoden als Lösung
vor. Dabei stand die Aktivierung der "Human Superpowers" im
Mittelpunkt - ein Paradigmenwechsel von passiven Trainingsempfängern hin
zu aktiven Mentoren und Multiplikatoren der Transformation.

### Gliederung und Aufbau des Vortrags

**Problemanalyse traditioneller Key User-Ansätze** Frederik begann mit
einer ehrlichen Bestandsaufnahme der aktuellen Situation: *"Ich
beobachte das Thema Key User schon die ganze Zeit. Ich weiß nicht, wie
es anderen hier geht, aber ich habe so das Gefühl, dass sich das nicht
wirklich weiterentwickelt."* Er identifizierte strukturelle Probleme,
die seit Jahrzehnten bestehen.

**Ursachenforschung und Symptome** Der Vortrag analysierte systematisch
die Gründe für das Scheitern von Key User-Konzepten, von mangelnder
Freistellung bis hin zu fehlender Wertschätzung durch Führungskräfte.

**Lösungsansätze durch Collaborative Learning** Frederik stellte
konkrete Methoden vor, wie Key User zu echten Mentoren entwickelt werden
können, einschließlich praktischer Beispiele wie dem "Mitmachmittwoch"
bei Kyndril.

**Implementierungsstrategien** Abschließend wurden konkrete
Handlungsempfehlungen für die Praxis vorgestellt, mit Fokus auf
Empowerment, Sichtbarkeit und nachhaltiger Wissensverankerung.

### Kernaussagen des Vortrags

**Die Tool-Falle vermeiden** *"Ich versteige mich jetzt mal, auch wenn
ich mich in den SAP-Hallen befinde, aber ich behaupte, es liegt nicht an
den Tools."* Frederik betonte, dass technologische Lösungen ohne den
Menschen nicht funktionieren können.

**Key User als Schlüssel zum Erfolg** *"Die Key-User sind einfach der
Schlüssel zum Erfolg"* - diese Erkenntnis zog sich wie ein roter Faden
durch den Vortrag. Dabei ging es nicht nur um fachliche Kompetenz,
sondern um die Rolle als Multiplikatoren und Mentoren.

**Motivation durch Sinn und Zweck** Ein zentraler Punkt war die
Erkenntnis: *"Wenn ich selber nicht hinter der Lösung stehe, wie soll
ich dann die Motivation auf andere übertragen?"* Frederik verwies auf
aktuelle Studien zur Mitarbeitermotivation, die zeigen, dass Sinn und
Zweckhaftigkeit wichtiger sind als reine monetäre Anreize.

**Frühzeitige Einbindung als Erfolgsfaktor** *"Key User frühzeitig
einbinden"* wurde als fundamentale Voraussetzung identifiziert. Dabei
ging es nicht nur um Information, sondern um aktive Mitgestaltung der
Lösung.

**Demos statt Diktat** Eine besonders prägnante Formulierung war: *"Die
Key-User, die sollen selbst den Fortschritt des Projektes demonstrieren.
Und zwar gegenüber den eigenen Verantwortlichen, den Stakeholders, den
Fachbereichen."*

### Offene Fragestellungen

Während des Vortrags wurden mehrere wichtige Fragestellungen
aufgeworfen, die zur weiteren Diskussion anregen:

- Wie kann die Balance zwischen Tagesgeschäft und Projektarbeit für Key
  User optimal gestaltet werden?
- Welche Rolle spielen Führungskräfte bei der Unterstützung von Key
  User-Initiativen?
- Wie können gewerbliche Mitarbeiter ohne Büroarbeitsplatz effektiv in
  collaborative Learning-Prozesse eingebunden werden?
- Wann ist der richtige Zeitpunkt, um unfertige Lösungen zu
  präsentieren, ohne Verwirrung zu stiften?
- Wie kann die Kontinuität des Wissens nach Projektabschluss
  sichergestellt werden?

### Handlungsempfehlungen

**Neue Rollendefinition etablieren** Frederik empfahl eine grundlegende
Neudefinition der Key User-Rolle: *"Key User als Dolmetscher,
Fachbereich, IT, Dolmetscher, aber auch zu den Unternehmenszielen."*
Diese erweiterte Rolle umfasst: - Vermittlung zwischen IT und
Fachbereich - Hinterfragen von Standards und Lösungsansätzen - Aktive
Teilnahme an Entscheidungsprozessen

**Implementierung regelmäßiger Formate** Als praktisches Beispiel wurde
der "Mitmachmittwoch" vorgestellt - ein regelmäßiges Format, bei dem Key
User ihre Themen präsentieren und Fachbereiche zur Beteiligung einladen.
Dies schafft Sichtbarkeit und Einfluss für die Key User.

**Empowerment durch Eigenverantwortung** - Key User sollen selbst
Implementierungspiloten durchführen - Frühzeitige Einbindung in
Workshops und Ideation-Prozesse - Transparenz über Projektfortschritte
und Entscheidungen

**Führungskräfte-Enablement** Ein wichtiger Punkt war die Notwendigkeit,
Führungskräfte zu sensibilisieren: *"Die Führungskräfte müssen
verstehen, dass die Mitarbeiter, die sie da jetzt haben, die Key-User,
nach dem Projekt noch sehr viel wertvoller sind in ihren Abteilungen."*

**Adoption als Erfolgsmessung** Frederik betonte abschließend:
*"Adoption, Adoption, Adoption, das ist unser Megamonster KPI, wenn ich
die Keyuser rankriege, dann habe ich schon mal die erste Schlacht
gewonnen."*

Der Vortrag machte deutlich, dass erfolgreiche Transformation nicht
durch bessere Tools, sondern durch bessere Einbindung und Entwicklung
der Menschen erreicht wird. Die vorgestellten collaborative
Learning-Ansätze bieten einen vielversprechenden Weg, um Key User von
passiven Trainingsempfängern zu aktiven Mentoren der digitalen
Transformation zu entwickeln.

## Simon Dückert - State of GenAI - was in meiner Wissensarbeit wirklich, wirklich funktioniert

...

## Bernhard Rupp und Andreas Kübli - 12 Freunde müsst ihr sein

Bernhard Rupp und Andreas Kübli von der BLS AG präsentierten ihre
Erfolgsstory der SAP SuccessFactors-Einführung unter dem Titel "FC HR
Pro". Anhand einer kreativen Fußball-Metapher zeigten sie auf, wie ein
erfolgreiches Projektteam funktioniert und welche Learnings sie während
der dreijährigen Systemeinführung gesammelt haben. Der Vortrag
verdeutlichte, dass erfolgreiche Transformationsprojekte vor allem auf
Teamwork, klarer Kommunikation und der richtigen Vorbereitung basieren.

### Gliederung und Aufbau des Vortrags

Der Vortrag folgte einer durchdachten Struktur entlang der
Fußball-Metapher:

- **Vorstellung des "Vereins"** (BLS AG als Unternehmen)
- **Saisonvorbereitung** (Projektplanung nach dem Golden Circle)
- **Zusammenstellung der Startelf** (Teamaufbau und Rollen)
- **Der Anpfiff** (Projektstart und erste Phase)
- **Das Spiel** (Projektumsetzung mit Halbzeitpause)
- **Spielanalyse** (Learnings und Erkenntnisse)
- **Ausblick** (Aktuelle Situation und zukünftige Pläne)

### Kernaussagen

**Zur Projektzielsetzung:** *"Wir wollten die ganzen Personalprozesse
vereinfachen, professionalisieren, auch optimieren und standardisieren"*
und dabei *"die enormen Medienbrüche eliminieren"*, die im bestehenden
System vorhanden waren.

**Zur Bedeutung des Teamworks:** *"Es braucht Vertrauen. Also das Team
muss einander vertrauen können. Es muss auch ein gemeinsames Ziel
haben"* und *"eine offene Gesprächskultur"*.

**Zur Systemkomplexität:** *"SAP ist nicht SAP, weil Success Factors ist
zwar das gleiche Spiel, aber es ist ein anderer Boden"* - eine zentrale
Erkenntnis über die Unterschiede zwischen SAP HCM und SuccessFactors.

**Zur Zeitplanung:** Die ursprünglich geplanten drei Jahre wurden von
SAP-Beratern auf ein Jahr reduziert, am Ende benötigte das Projekt
tatsächlich drei Jahre. *"Als SAP dann die Berater das erste Mal vor Ort
waren und unsere Planung gesehen haben, haben sie gelacht und gesagt, in
einem Jahr haben wir es alles durch. Am Schluss haben wir drei Jahre
gebraucht."*

**Zu den Erfolgen:** *"Wir haben heute von der Rekrutierung bis zum
Austritt alles integriert"* und erhielten den *"Cloud Transformation
Award 2023"* von SAP für das erfolgreiche Projekt.

### Offene Fragestellungen

Während des Vortrags wurden verschiedene Herausforderungen und offene
Punkte angesprochen:

- Wie kann die Balance zwischen kontinuierlicher Weiterentwicklung und
  Stabilisierungsphasen optimal gestaltet werden?
- Welche Strategien helfen dabei, den Fokus zu behalten, wenn das System
  *"sehr viel zu machen"* einlädt?
- Wie lassen sich Wissensabgänge von Schlüsselpersonen während
  kritischer Projektphasen vermeiden?
- Wie kann die Belastung für Mitarbeitende bei der Einführung mehrerer
  Module optimal gesteuert werden?

### Handlungsempfehlungen

**Teamzusammenstellung und -führung:** - Klare Rollenverteilung
etablieren mit bewährten Positionen wie Projektleiter als "Torwart",
Fach und IT als "Sturmduo" - Auswechselspieler und Stellvertreter
definieren, da *"wir während des Projektes auch gewisse Abgänge"*
hatten - *"Never Change a Winning Team"* - Kernteam möglichst stabil
halten

**Projektplanung und -durchführung:** - Realistische Zeitplanung
basierend auf der eigenen Organisationskenntnis - 80/20-Regel befolgen:
80% Standardfunktionen, nur 20% Anpassungen - Schrittweise Annäherung an
das System ermöglichen - Regelmäßige Retrospektiven und Halbzeitpausen
einplanen

**Change Management und Kommunikation:** - *"Kommunikation,
Kommunikation, Kommunikation"* als zentrales Element - Frühzeitige
Einbindung der Anwender durch Systemzugang - AbleNow für Schulungen
nutzen statt umfangreicher Handbücher - *"Verbindlichkeit schaffen, dass
der Einführungstermin klar verbindlich kommuniziert wird"*

**Betrieb und Weiterentwicklung:** - Fokus behalten und nicht in zu
viele parallele Aktivitäten verzetteln - *"Durchschnaufen, das Tool
wirken lassen"* zwischen den Moduleinführungen - Modulverantwortliche
für koordinierte Weiterentwicklung etablieren - Release-Management für
halbjährliche Updates implementieren

**Erfolgsfaktoren:** - Erfolge gemeinsam feiern und das Team würdigen -
Kontinuierliches Lernen durch externe Unterstützung (SAP Preferred
Success als "Personaltrainer") - Integration aller Module für maximalen
Nutzen anstreben

Der Vortrag schloss mit dem inspirierenden Zitat von Michael Jordan:
*"Talente Spieler gewinnen, aber das Teamwork und Diligenz dann die
Meisterschaft"* - eine treffende Zusammenfassung der zentralen Botschaft
über die Bedeutung erfolgreicher Teamarbeit in Transformationsprojekten.

## Florence Streif - Weichenstellung fürs digitale Zeitalter - Zwischen Bahnhof und Besprechungsraum

...

## Moritz Huber - KI im Lern-Lifecycle - PoC für KI-gestütztes Anwenderlernen

Moritz von SAP Learning Services stellte einen innovativen Proof of
Concept vor, der Künstliche Intelligenz zur automatisierten Erstellung
von Schulungsunterlagen und Lernbedarfsanalysen einsetzt. Das System
integriert verschiedene Datenquellen wie SAP-Standarddokumentation,
Signavio-Prozessinformationen und kundenspezifische Daten, um den
Aufwand für die Schulungsunterlagenerstellung erheblich zu reduzieren.
Erste Pilotprojekte zeigen vielversprechende Zeitersparnisse von bis zu
60%.

### Gliederung und Aufbau des Vortrags

**Problemstellung und Motivation** - Herausforderungen der manuellen
Schulungsunterlagenerstellung - Zeitdruck in Projektphasen und
Aktualisierungsproblematik

**Lösungsansatz mit KI** - Integration verschiedener Input-Quellen -
Automatisierte Content-Generierung - Beibehaltung des Human Factors

**Technische Demonstration** - Live-Demo der Plattform - Prozess von der
Lernbedarfsanalyse bis zum fertigen Content - Integration mit
Drittsystemen wie Synthesia

**Ausblick und Verfügbarkeit** - Aktueller Entwicklungsstand - Pricing
und Markteinführung

### Kernaussagen

**Zielsetzung der KI-Lösung:** *"Es geht mir nicht darum, dass die KI
unsere Arbeit im Thema Lerncontent-Erstellung wegnimmt, sondern
erleichtert. Es geht darum, Effort zu reduzieren, Aufwand zu reduzieren,
Zeit bis zum Go-Live zu reduzieren."*

**Qualitätsfaktor Input:** *"Je mehr Input ich vom Projekt habe, umso
besser wird die Qualität des AI-Outputs. Je mehr wir von SAP Standard
ausgehen, umso mehr standardisiert ist der Endanwender-Content."*

**Praxiserfahrung:** *"Einer der größten Kunden, mit denen wir jetzt
gerade machen, Schneider Electric in Frankreich, die haben selbst von
sich aus gesagt, dass sie 60% ihrer Zeit für
Schulungsunterlagenerstellung dadurch sparen."*

**Human Factor:** *"Es wird immer einen Human Factor im Learning geben
und das ist umstrittig, da bin ich dabei."*

**Methodische Unterstützung:** *"Wir machen in der Lösung nicht nur die
Content-Erstellung, sondern der Hintergrund ist auch, dass wir die
Lernbedarfsanalyse mit einbauen wollen."*

### Technische Funktionsweise

**Input-Quellen:** - SAP-Standarddokumentation (Subhelp,
Learning.sap.com) - Signavio-Prozessinformationen - Kundenspezifische
Konfigurationsdaten - Master- und Transaktionsdaten für Übungsbeispiele

**Output-Formate:** - Textbasierte Inhalte für verschiedene
Lernformate - Automatische Zuordnung von Delivery-Methoden - Integration
mit Video-Tools wie Synthesia - HTML-Export für verschiedene Plattformen

**Technische Basis:** Das System basiert auf SAP AI-Core und nutzt
Prompting-Technologien zur Content-Generierung.

### Offene Fragestellungen

- **Skalierbarkeit:** Wie verhält sich das System bei sehr großen,
  internationalen Rollout-Projekten?
- **Customizing-Grenzen:** Welche Grenzen gibt es bei stark
  kundenindividuellen Anpassungen?
- **Learning-Capabilities:** Kann das System aus Kundenfeedback lernen
  und sich kontinuierlich verbessern?
- **Content-Type-Flexibilität:** Wie flexibel ist die Anpassung an
  unternehmensspezifische Trainingsstrategien?
- **Qualitätssicherung:** Welche Mechanismen gewährleisten die fachliche
  Korrektheit der generierten Inhalte?

### Handlungsempfehlungen

**Für Projektverantwortliche:** - Frühzeitige Einbindung der KI-Lösung
in die Projektplanung - Sicherstellung qualitativ hochwertiger
Input-Daten aus Signavio und anderen Quellen - Definition einer klaren
Trainingsstrategie vor Systemnutzung

**Für Learning-Experten:** - Kontinuierliches Review und Nachbearbeitung
der AI-generierten Inhalte - Nutzung der Challenge-Funktionen zur
Verfeinerung der Ergebnisse - Integration der Lösung in bestehende
Autorensysteme wie EnableNow

**Für Unternehmen:** - Evaluation der Lösung in Pilotprojekten vor
Vollimplementierung - Berücksichtigung der Standalone-Architektur bei
der Tool-Landschaft - Vorbereitung auf Change Management Integration in
zukünftigen Versionen

**Strategische Überlegungen:** - Aufbau interner Kompetenzen für
KI-gestützte Content-Erstellung - Definition von Qualitätsstandards für
automatisch generierte Lerninhalte - Planung für kontinuierliche Updates
und Maintenance

Die vorgestellte Lösung zeigt das Potenzial von KI zur Transformation
traditioneller Schulungserstellungsprozesse, wobei der Fokus auf
Effizienzsteigerung bei gleichzeitiger Beibehaltung menschlicher
Expertise liegt.

## Mike Fritz und Christoph Kernke - SAP Enable Now trifft auf WalkMe und die SAP Integrated Toolchain

Der Vortrag behandelt die Herausforderungen und Lösungsansätze für
kontinuierliche Transformationen in Unternehmen im Zeitalter der
Künstlichen Intelligenz. Die Referenten Christoph und Maik erläutern,
wie sich Transformationszyklen drastisch verkürzen und warum
traditionelle Ansätze nicht mehr ausreichen. Sie stellen das Konzept der
"Human Superpowers" vor, das durch die Integration von Menschen,
Prozessen, Daten und Technologie entstehen soll. Ein zentraler Punkt ist
die SAP Integrated Toolchain, die verschiedene SAP-Tools miteinander
verbindet, um Transformationen zu digitalisieren. Zusätzlich wird die
strategische Neuausrichtung von EnableNow und die Integration von WalkMe
als neue Digital Adoption Platform erläutert.

### Gliederung und Aufbau des Vortrags

**1. Einführung: Die neue Realität der Transformationen** - Zunehmende
Komplexität und verkürzte Transformationsintervalle - Historischer
Rückblick auf SAP-Generationen (R1, R2, R3) - Zeitdruck durch
AI-Innovationen

**2. Die vier Säulen der Continuous Transformation** - People:
Individueller Content und Bildschirmhilfen - Process: Umgang mit 160.000
Transaktionen in S/4HANA - Data: Intelligenz aus bestehenden Systemen
ziehen - Technology: Planerisches Vorgehen und permanente Transparenz

**3. SAP Integrated Toolchain** - Integration verschiedener SAP-Tools -
Praktische Anwendungsbeispiele - Umfrage zur aktuellen Tool-Integration
bei Kunden

**4. EnableNow und WalkMe: Strategische Neuausrichtung** - Feature
Freeze für EnableNow - Entwicklung von WalkMe Learning - Migrationspfade
und Wartungsgarantien

### Kernaussagen

**Zur Transformation der Zukunft:** *"Wenn ich irgendeine AI-Innovation
habe und eine Firma, ein Konkurrent von Ihnen lässt das laufen für sechs
Monate oder für ein Jahr, kann der so viel Savings generieren in dem
Bereich, dass man einfach nicht mehr diese Iterationen von
Transformationszyklen aus der Vergangenheit anwenden kann in der
Gegenwart und in der Zukunft."*

**Zur Bedeutung des Menschen:** *"Der Erfolg einer Transformation ist
ungefähr zwischen 59 und 64 Prozent abhängig von Personen."* Diese
Aussage basiert auf einer Studie der Boston Consulting Group und
unterstreicht die zentrale Rolle des Faktors Mensch.

**Zur technologischen Entwicklung:** *"Ein ECC-System hatte 90.000
Transaktionen. Es sind \[in S/4HANA\] 160.000 da. Das ist der
Innovationssprung, den wir ausgeführt haben."*

**Zum Paradox aktueller Transformationen:** *"Wir machen
Transformationen, um AI zu haben, um in der Cloud zu sein, um die coolen
Dinge zu machen. Aber den Weg dahin machen wir noch immer mit Steinen
und Meißel."*

**Zur EnableNow-Zukunft:** *"Die Wartung von EnableNow Cloud läuft
uneingeschränkt bis 2030 weiter. Da gibt es Gerüchte im Markt, die sind
schlicht unwahr."*

### Offene Fragestellungen

Während des Vortrags wurden mehrere wichtige Fragestellungen
aufgeworfen:

- Wie können Unternehmen den Innovationszyklen der SAP folgen und dabei
  alle verfügbaren Features nutzen?
- Welche konkreten Schritte sind notwendig, um von traditionellen
  Transformationsansätzen zu Continuous Transformation überzugehen?
- Wie lassen sich bestehende Investitionen in EnableNow-Content bei der
  Migration zu neuen Plattformen schützen?
- Wann ist der optimale Zeitpunkt für den Umstieg von EnableNow auf
  WalkMe Learning?
- Wie können Unternehmen die Value-Leakage vermeiden, die durch nicht
  konsumierte Innovationen entsteht?

### Handlungsempfehlungen

#### Sofortige Maßnahmen:

- Akzeptanz, dass Transformationen selbst digitalisiert werden müssen
- Beginn der Integration vorhandener SAP-Tools zur Schaffung einer
  "Transformationsmaschine"
- Nutzung von AI zur Analyse von Systemdaten und Prozessen statt
  manueller Erfassung

#### Mittelfristige Strategien:

- Aufbau einer SAP Integrated Toolchain mit mindestens 14 verfügbaren
  Integrationen
- Implementierung von Tools zur automatischen Erkennung von Prozess- und
  UI-Problemen
- Entwicklung einer Governance-Struktur für kontinuierliche
  Transformationen

#### Langfristige Planung:

- Vorbereitung auf einen Zeithorizont von maximal drei bis vier Jahren
  für Continuous Transformation
- Investition in die Verbindung von AI und menschlichen Fähigkeiten zu
  "Human Superpowers"
- Strategische Planung für die Migration von EnableNow zu WalkMe
  Learning

#### Konkrete Tool-Empfehlungen:

- Integration von Signavio mit LeanIX für automatische
  Prozessmodell-Generierung
- Verknüpfung von Cloud ALM mit EnableNow für strukturierte
  Dokumentation
- Nutzung von WalkMe für erweiterte Digital Adoption
  Platform-Funktionalitäten

#### Für EnableNow-Bestandskunden:

- Fortsetzung der Content-Erstellung bis 2030 ohne Bedenken
- Vorbereitung auf Migrationspfade, die voraussichtlich Q1/Q2 2025
  verfügbar werden
- Nutzung der bestehenden Integrationen zur Maximierung des ROI

Der Vortrag macht deutlich, dass Unternehmen nicht nur ihre
Geschäftsprozesse, sondern auch ihre Transformationsansätze grundlegend
überdenken müssen, um in der beschleunigten digitalen Welt erfolgreich
zu sein.

## Patrick Fueldner - Von der Einführung zur Skalierung - Nestlés Digital Adoption-Strategie mit WalkMe

...

## Katja Sommerer - Big Bang - 40 Länder, 800 neue Mitarbeitende - Herausforderungen des Trainings in einem M+A-Projekt

...

## Andrea Flöth - HR neu gedacht - BARMERs digitale Evolution mit Hilfe von SAP Preferred Success

...

## Mareike Muth - Übersetzer der Moderne - Das Learning Team als Katalysator zwischen Fachbereich und Enduser

...

# Sessions & Workshops

## Promptathon

> Entwicklung und Optimierung von KI-Prompts für Herausforderungen und
> Use Cases in Weiterbildung und Change Management im SAP-Bereich.

## Discovery Workshop AI UseCases im Learning

> Exploration und Identifizierung von relevanten Use Cases für den
> Einsatz von KI für Change Management und Training in SAP Projekten.

## Good Practices & Lessons Learned SAP S/4HANA Transformationen

> Strategien für erfolgreiches OCM und Learning - Wichtige Do's & Dont's
> und deren Umsetzung mit dem SAP Activate Framework.
