# Lern-Bericht
Joel Freitas

## Einleitung

Cross-Site-Scripting (XSS) ist eine Sicherheitslücke, die es Angreifern ermöglicht, bösartigen Code auf Webseiten einzuschleusen und auszuführen. Dies könnte dazu führen, dass vertrauliche Informationen gestohlen werden oder die Website für Benutzer nicht verfügbar ist. XSS-Escape ist eine Technik, die verwendet wird, um zu verhindern, dass diese Art von bösartigem Code in Webseiten eingeschleust wird. Dies geschieht, indem sichergestellt wird, dass Benutzereingaben ordnungsgemäß codiert werden, bevor sie auf der Webseite angezeigt werden. Dadurch wird sichergestellt, dass kein bösartiger Code ausgeführt wird und die Sicherheit der Website aufrechterhalten wird.

## Was habe ich gelernt?

Ich habe gelernt, wie man eine Website vor XSS Angriffe schützt und wie man sich im besten Fall verhalten sollte. Ausserdem habe ich die gelernt, dass das Wissen den ich mir angeeignet habe, rechtliche Konsequenzen hat.

## Beschreibung

Das unten zu sehende Video, präsentiert uns, was passieren kann, wenn man die Webseite nicht vor XSS geschützt ist:

https://user-images.githubusercontent.com/69576108/207670007-118b0287-32b9-4ec8-af61-8d79384c6c7c.mp4

Code:

![Unbenannt](https://user-images.githubusercontent.com/69576108/207671226-f00a79bc-1789-49dc-8a7e-18a694434b09.PNG)

Wie man bei der Codestelle sehen kann, ist "escape" auf "false" gesetzt. Dies bedeute, dass escaping nicht betrieben wird. Für uns bedeutet es dann, dass die "Tags" als "Tags" anerkannt werden und nicht bloss als ein normaler Buchstabe. JSF sowie die meisten Technologien betreiben automatisch escaping, wenn wir es nicht absichtlich abstellen. Dennoch muss man sicher sein, dass man davor geschützt ist. Mit einer solchen Sicherheitslücke kann viel Unfug betrieben werden.

Das unten zu sehende Video präsentiert uns, wie unsere Webseite im besten Fall auf die Eingabe reagieren soll:

https://user-images.githubusercontent.com/69576108/207672542-a8cd1fb6-738e-44f0-8eaa-8218a8029ca2.mp4

Code:

![Unbenannt](https://user-images.githubusercontent.com/69576108/207672811-c1a0478f-9cb7-42d3-bcf0-55e3064de0b5.PNG)

Nun ist "escape" auf "true" gesetzt. Ab sofort werden die "Tags" als ein normaler Buchstabe anerkannt. Ab sofort ist unsere Webseite zumindest vor dieser Sicherheitslücke geschützt.

## Verifikation

XSS-Escaping ist eine Technik, die verwendet wird, um zu verhindern, dass schädlicher Code in einer Webseite eingeschleust wird. Dies geschieht, indem sichergestellt wird, dass die Eingaben von Nutzern ordnungsgemäß codiert werden, bevor sie auf der Webseite angezeigt werden. Auf diese Weise kann verhindert werden, dass schädlicher Code ausgeführt wird und die Sicherheit der Webseite gewahrt bleibt.

# Reflektion zum Arbeitsprozess

👍 Ich finde, dass ich mich im Unterricht gut konzentrieren konnte. Sofern ich den Auftrag verstanden habe, bin ich motiviert und konzentriert an die Aufgabe gegangen und versucht, die so gut es geht, zu lösen. Dies bedeutet, dass ich im gross und ganzen ziemlich zufrieden mit meiner Leistung bin, obwohl ich den Einstieg etwas verpasst haben.

👎 Für mich wahr es nicht immer leicht, die Konzentration und Motivation im Online-Unterricht zu finden. Ich verlor oft den Fokus, da ich mich in eine wohlfühlende Umgebung arbeitete. Dies bedeutet im Umkehrschluss, dass ich mit den Aufträgen ab und zu hinterher war.

**VBV**: Ich möchte mich im Online-Unterricht besser konzentrieren und nicht den Fokus verlieren. Um dies zu erreichen werde ich in Zukunft mein Handy auf nicht Stören umstellen und jegliche Sachen, die mich ablenken abstellen.
