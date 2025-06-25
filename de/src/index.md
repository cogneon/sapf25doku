# Willkommen 

Das [SAP Learning and Adoption Forum 2025](https://go4.events.sap.com/eur-learning-adoption-forum/de_de/home.html) fand am 25. Juni 2025 in Walldorf statt. Die Inhalte dieser Dokumentation stammen aus den Aufzeichnungen der Lightning Talks, Knowledge Cafes und Workshops.

!!! note "Hinweis"
    Mit der Dokumentation könnt ihr sogar mit [diesem Chatbot](https://chatgpt.com/g/g-68591dbd8fd081918d7be3eaef14596e-sap-learning-adoption-forum-2025) (CustomGPT, Modell GPT-4o) "reden" ... das funktioniert sogar in natürlicher Sprache mit dem Voice Mode. Die KI-generierten Zusammenfassungen wurden **NICHT** nachberarbeitet. Die KI kann Fehler machen.

*Offen: wer steht im Impressum? Unter welcher Lizenz stehen die Inhalte?*

![](https://community.sap.com/t5/image/serverpage/image-id/239155iA5FD44DFCBCAB58F/image-size/large?v=v2&px=999)

# Programm

| ID | Programmpunkt | Referent:innen | Affiliation |
| --- | --- | --- | --- |
| 0-1 | [Interview mit Yemisi Ogunleye](0-1.md) | | |
| 1 | **Lightning Talks** | | |
| 1-1 | [Appet-ai-te for disruption](1-1.md) | Timo Deiner | Head of Innovation & Technology MEE, SAP |
| 1-2 | [Trends in Corporate Learning - mehr als KI!](1-2.md) | Jochen Robes | Hochschullehrer und Gründungsmitglied Corporate Learning Community |
| 1-3 | [Superkräfte bei Mitarbeitenden - Was ist wichtig aus HR und People Sicht?](1-3.md) | Eva Stock | Chief People & Marketing Officer, comspace |
| 2 | **Knowledge Cafes** | | |
| 2-1 | [Collaborative Learning im SAP-Ecosystem: Key-User als Mentoren der Zukunft](2-1.md) | Frédéric Heinemann | Head of SAP Transformation Portfolio, Kyndryl |
| 2-2 |[12 Freunde müsst ihr sein](2-2.md) | Bernhard Rupp, Andreas Kübli | Kreislead HR-IT & Support, Transformationsmanager, BLS AG |
| 2-3 | [Weichenstellung fürs digitale Zeitalter: Zwischen Bahnhof und Besprechungsraum](2-3.md) | Florence Streif | Senior Change Consultant & systemisches Coaching, ÖBB |
| 2-4 | [KI im Lern-Lifecycle: PoC für KI-gestütztes Anwenderlernen](2-4.md) | Moritz Huber | Head of SAP Learning Services MEE, SAP |
| 2-5 | [SAP Enable Now trifft auf WalkMe und die SAP Integrated Toolchain](2-5.md) | Mike Fritz, Christoph Kernke | Product Expert Enable Now, Head of Integrated Toolchain Services, SAP |
| 2-6 | [Von der Einführung zur Skalierung: Nestlés Digital Adoption-Strategie mit WalkMe](2-6.md) | Patrick Fueldner | Senior IT Product Manager Digital Enablement, Nestlé |
| 2-7 | [Big Bang - 40 Länder, 800 neue Mitarbeitende - Herausforderungen des Trainings in einem M+A-Projekt](2-7.md) | Katja Sommerer | Leading IT Project Manager, Endress+Hauser Gruppe |
| 2-8 | [HR neu gedacht: BARMERs digitale Evolution mit Hilfe von SAP Preferred Success](2-8.md) | Andrea Flöth | Manager HR Transformation, BARMER |
| 2-9 | [Übersetzer der Moderne: Das Learning Team als Katalysator zwischen Fachbereich und Enduser](2-9.md) | Mareike Muth | Gruppenleitung Wissensmanagement, MEWA |
| 2-10 | [State of GenAI - was in meiner Wissensarbeit wirklich, wirklich funktioniert](2-10.md) | Simon Dückert | Spezial-Experte Wissensmanagement & Lernende Organisationen, Scholarch Cogneon Akademie |
| 3 | **Hands-on Workshops** | | |
| 3-1 | [Promptathon](3-1.md) | | |
| 3-2 | [Discovery Workshop AI UseCases im Learning](3-2.md) | | |
| 3-3 | [Good Practices & Lessons Learned SAP S/4HANA Transformationen](3-3.md) | | |

# Workflow der KI-generierten Zusammenfassung
Um die KI-basierte Dokumentation den Teilnehmenden schon während der Veranstaltung bereitstellen zu können, wurde die Auswertung und Bereitstellnug der Inhalte weitgehend automatisiert:

![](./images/ai-documentation-chain.png)

1. Die **Aufzeichnungen** (*Format: mp4*) der Beiträge werden von den Room Buddies in einen zentralen Onedrive-Ordner hochgeladen.
1. Die Aufzeichnungen werden aus einem von [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) (Modell: whister-large-v3-turbo) beobachteten Ordner automatisch **transkribiert** (*Format: txt*).
1. Die Transkripte werden mit der App [Chatbox](https://chatboxai.app/) mit einem dort angelegten Copilot (nicht Microsoft Copilot) nach einheitlichem Schema **zusammengefasst** (Format: md). *(noch festzulegen, aktuell: Zusammenfassung, Gliederung, Kernaussagen, Offene Fragestellungen, Handlungsempfehlungen, Thesen, Abschluss)*.
1. Die Zusammenfassungen werden in der **Repo-Struktur** von [lernOS](https://lernos.org) in einem Github-Repository abgelegt.
1. Mit der **lernOS Produktionskette** wird aus den Markdown-Dateien automatisch diese Web-Version sowie weitere Formate zum Download (pdf, html, docx, md) erzeugt.
1. Die Markdown-Version (mit allen Zusammenfassungen) wird als **"Wissensbasis" für einen Chatbot** auf Basis eines [CustomGPT](https://help.openai.com/en/articles/8554397-creating-a-gpt) verwendet. Nutzende können so mit der Zusammenfassung der Veranstaltung "sprechen".
1. Interessenten können sich eine **Markdown-Version der Dokumentation** unter *Download* zusätzlich herunterladen, um sie in eigenen KI-Tools wie z.B. [Microsoft Copilot](https://www.microsoft.com/de-de/microsoft-copilot/organizations), [SAP Joule](https://www.sap.com/germany/products/artificial-intelligence/ai-assistant.html), [Gemini](https://gemini.google.com/), [NotebookLM](https://notebooklm.google/), [Le Chat](https://chat.mistral.ai/) (europäisch) oder lokalen KI-Tools ([LM Studio](https://lmstudio.ai/), [Chatbox](https://chatboxai.app/), [GPT4All](https://www.nomic.ai/gpt4all), [Open WebUI](https://openwebui.com/)) zu verwenden. 