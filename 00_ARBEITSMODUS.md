# HERZkompass – Arbeitsmodus

Dieses Dokument fasst zusammen, **wie** am HERZkompass gearbeitet wird. Es enthält
keine inhaltlichen Grundsätze und begründet keine neuen: Jede Angabe ist eine
Wiedergabe bereits bestehender Festlegungen, die Herkunft ist jeweils angegeben.
Weicht diese Zusammenfassung an einer Stelle von ihrem Ursprung ab, gilt der
Ursprung.

Dieses Dokument ist selbst kein Ursprung. Es darf nicht als Beleg für eine Regel
dienen, die es nur zusammenfasst. Als *Ableitung* gekennzeichnete Sätze folgen
aus den Quellen, sind aber nicht beschlossen.

## 1. Arbeitsreihenfolge

`Grundlagen → Konstruktion → Prüfung → Entscheidung → Anwendung`

(→ `README.md`, Repository-Prinzip)

*Ableitung:* Arbeit an einer Stufe öffnet nicht automatisch eine frühere Stufe.

## 2. Aktuelle Phase

Konsolidierung / Übergang in Anwendung.

Als Schritte 1–6 der nächsten Phase genannt: Dokumentation konsolidieren →
praktische Anwendung → Produktentwicklung → technische Umsetzung → externe
Prüfung → Veröffentlichung.

(→ `00_PROJEKTSTATUS.md`)

## 3. Konstruktions- und Prüfraum sind getrennt

Grundentscheidung 5: „Konstruktions- und Prüfraum methodisch trennen.“
(→ `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`)

Im Prüfraum gilt: „Eine Prüfung darf keine neue Konstruktion erzeugen, wenn der
Befund die bestehende Konstruktion trägt.“ (→ `05_PRUEFUNG/PRUEFREGELN.md`)

*Ableitung:* Konstruktionsraum = setzen von Grundlagen, Begriffen und
Zusammenhängen; Prüfraum = prüfen, ob das Gesetzte trägt, mit einem Befund als
Ergebnis statt eines neuen Entwurfs.

## 4. Prüfkriterien

Ableitungsprüfung · Kohärenzprüfung · Abgrenzungsprüfung · Tragfähigkeitsprüfung ·
Prüfung des eigenständigen Beitrags · Gesamtprüfung.

(→ `05_PRUEFUNG/PRUEFARCHITEKTUR.md`)

## 5. Prüfbefunde

Ein Prüfprozess unterscheidet zwischen: `bestätigt` · `Änderung erforderlich` ·
`offen` · `archiviert`.

(→ `05_PRUEFUNG/PRUEFREGELN.md`)

„Prüfen bedeutet nicht automatisch verändern.“
(→ `05_PRUEFUNG/PRUEFARCHITEKTUR.md`)

## 6. Rückkehr zur Konstruktion

Grundentscheidung 6: „Grundkonstruktion nicht ohne sachlichen Grund wieder
öffnen.“ (→ `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`)

Der Projektstatus stellt dieselbe Bedingung an einen anderen Gegenstand: „Die
weitere Arbeit soll nicht ohne sachlichen Grund zur Neukonstruktion
zurückkehren.“ (→ `00_PROJEKTSTATUS.md`)

*Ableitung:* Was ein sachlicher Grund ist, definieren beide Quellen nicht. Belegt ist nur die
Gegenseite: eine Prüfung darf keine neue Konstruktion erzeugen, wenn der Befund
die bestehende Konstruktion trägt. Daraus folgt, dass ein tragender Befund die
Öffnung sperrt – nicht, dass ein Befund `Änderung erforderlich` sie auslöst, und
nicht, dass es keinen anderen Grund geben kann. Für neuere Formulierungsideen
weist die Archivregel den Weg: „Archiviert werden können verworfene Formulierungen,
ältere Konstruktionen, Zwischenstände, alternative Modelle und historische
Diskussionen.“
(→ `05_PRUEFUNG/PRUEFREGELN.md`, `ARCHIV/ARCHIVREGELN.md`)

*Offen und nicht Gegenstand dieses Dokuments:* ob ein Öffnungsgrund festgestellt,
und ob und wo er festgehalten werden muss.

## 7. Korrektur

„Erkannte Fehler und Widersprüche dürfen und sollen korrigiert werden.“
(Artikel 13 → `03_VERFASSUNG/VERFASSUNG_1.0.md`)

Grundentscheidung 10 hält schwächer fest, dass Erkanntes „zu Änderungen führen“
darf (→ `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`). *Ableitung:* Nach Artikel 13 ist der
Auslöser das Erkennen selbst; ein vorausgehender Prüfbefund ist dort nicht
gefordert.

## 8. Unterscheidung in der Sprache

Artikel 4 setzt den Tatbestand: „Wahrnehmung, Gefühl, Interpretation, Annahme
und Tatsache sind unterscheidbar.“ Grundentscheidung 4 formuliert die daraus
folgende Pflicht: „Wahrnehmung, Gefühl, Interpretation, Annahme und Tatsache
unterscheiden.“
(→ `03_VERFASSUNG/VERFASSUNG_1.0.md`, `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`)

Die Unterscheidung der fünf Ebenen ist in `04_ERKENNTNIS/` ausgearbeitet
(→ `04_ERKENNTNIS/WAHRNEHMUNG_GEFUEHL_INTERPRETATION.md`).

Erkenntniszugänge – Erfahrung, Wahrnehmung, Intuition, Logik, wissenschaftliche
Erkenntnis – werden nicht automatisch gleichgesetzt. Entscheidend sind Kontext,
Begründung, Evidenz, Unterscheidung, Korrekturfähigkeit.
(→ `04_ERKENNTNIS/ERKENNTNISGRUNDLAGEN.md`)

## 9. Umgang mit Nichtwissen

„Nichtwissen verpflichtet nicht automatisch zur Passivität. Verantwortliche
Entscheidung kann unter Unsicherheit möglich sein, wenn ausreichende Klarheit
besteht.“ (Artikel 14 → `03_VERFASSUNG/VERFASSUNG_1.0.md`; Grundentscheidung 9
→ `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`)

Eine KI soll insbesondere Unsicherheit benennen.
(→ `07_METAEBENE/METAEBENE.md`)

## 10. Trennung der Materialarten

„Historisches Arbeitsmaterial wird vom aktuellen Projektstand getrennt.“
(→ `README.md`)

„Das Archiv enthält historische Arbeitsstände und ist nicht automatisch aktueller
Projektstand.“ Archiviert werden können verworfene Formulierungen, ältere
Konstruktionen, Zwischenstände, alternative Modelle und historische Diskussionen.
„Ein archivierter Stand darf nur nach erneuter Prüfung zum aktuellen Stand
werden.“ (→ `ARCHIV/ARCHIVREGELN.md`)

## 11. Selbstanwendung

„Die Verfassung gilt auch für den HERZkompass selbst.“
(Artikel 11 → `03_VERFASSUNG/VERFASSUNG_1.0.md`)

Die Schutzprinzipien nennen Selbstanwendung als Punkt 8 und ziehen die Grenze:
„Der HERZkompass darf selbst nicht zu dem werden, wovor er schützen soll.“
(→ `03_VERFASSUNG/SCHUTZPRINZIPIEN.md`)

Die Metaebene prüft, wie Orientierung erzeugt wird, wie mit Nichtwissen
umgegangen wird, wie Macht begrenzt wird und wie Korrektur möglich bleibt.
(→ `07_METAEBENE/METAEBENE.md`)

Unverhandelbare Grenzen: kein Wahrheitsmonopol, keine erzwungene Zustimmung,
keine Ersetzung eigener Urteilskraft, keine Dogmatisierung, keine Manipulation
durch Angst, keine künstliche Vereinfachung, die entscheidende Differenzen
zerstört, Korrekturfähigkeit, Selbstanwendung.
(→ `03_VERFASSUNG/SCHUTZPRINZIPIEN.md`)

## 12. Kinderschutzvorrang

„Bei möglicher Gefährdung endet die reine Reflexion. Die Schutzverantwortung
bleibt beim Erwachsenen.“ Der Kinder-HERZkompass ist „eine eigenständige
entwicklungsangemessene Übersetzung und keine bloße Vereinfachung der
Erwachsenenfassung.“
(→ `06_KINDER_HERZKOMPASS/KINDER_HERZKOMPASS_1.0.md`, Grundentscheidungen 7 und 8
→ `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md`)

## 13. KI-Mitarbeit am Repository

„HERZkompass aktivieren“ bezeichnet einen Arbeitsmodus; „HERZkompass
deaktivieren“ beendet ihn. Im aktivierten Modus gilt: „Die KI verwendet den
HERZkompass als Orientierungs- und Prüfrahmen für ihre Arbeitsweise.“
„Wahrhaftigkeit und Sicherheit bleiben unabhängig davon bestehen.“
(→ `07_METAEBENE/AKTIVIERUNG.md`, `07_METAEBENE/METAEBENE.md`)

„Eine KI soll insbesondere unterscheiden, Unsicherheit benennen, Widersprüche
sichtbar machen, alternative Erklärungen zulassen, unbegründete Gewissheit
vermeiden und die Entscheidungshoheit beim Menschen belassen.“
(→ `07_METAEBENE/METAEBENE.md`)

## 14. Ablagekonventionen

*Dieser Abschnitt beschreibt die tatsächliche Struktur. Er ist aus ihr
abgeleitet, nicht ausdrücklich beschlossen, begründet keine Regel gegenüber den
Abschnitten 1–13 und kann ersetzt werden.*

- Dokumente als Markdown (`.md`).
- Ordnernamen numeriert und großgeschrieben, Dateinamen ebenso; Worttrenner ist
  der Unterstrich. Beispiel: `03_VERFASSUNG/VERFASSUNG_1.0.md`.
- Die Zuordnung folgt den Ordnern. Eine Datei kann mehrere Grundgedanken füllen
  (`03_VERFASSUNG/VERFASSUNG_1.0.md` mit 14 Artikeln) und ein Ordner mehrere Dateien.
- Versionierte Texte tragen die Version im Dateinamen; bisher zwei Dateien
  (`03_VERFASSUNG/VERFASSUNG_1.0.md`, `06_KINDER_HERZKOMPASS/KINDER_HERZKOMPASS_1.0.md`).
- `INDEX.md` bildet die Struktur ab.
- `10_ENTSCHEIDUNGEN/ENTSCHEIDUNGSLOG.md` ist die Stelle, an der beschlossene
  Grundentscheidungen stehen.
