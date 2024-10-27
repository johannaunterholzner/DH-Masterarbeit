# DH-Masterarbeit
Repository für alle Jupyter Notebooks, die im Laufe der Masterarbeit für das Studium Digital Humanities an der Universität Wien von Johanna Unterholzner erstellt wurden.
Der Titel lautet: "Möglichkeiten und Methoden zur Untersuchung von Textgenese mithilfe quantitativer Textanalyse am Beispiel von Parts-of-Speech-Tagging ausgewählter Gedichte von Friederike Mayröcker."

Anhand der Jupyter Notebooks ist der Prozess der Aufbereitung und Analyse von Gedichten mit ihren Textzeugen nachzuverfolgen. Beginnend mit dem POS-Tagging der Transkripte in einer XML-Datei, der Erstellung einer Confusion Matrix zur Qualitätsüberprüfung des Taggings, der Extrahierung von Textstufen aus den Textzeugen (sofern handschriftliche Eingriffe vorzufinden sind) und der Überführung der Textstufen von XML in ein CSV-Format hin zur Auswertung der modellierten und extrahierten Texte in Hinblick auf die Art der Eingriffe und insbesondere der POS-Häufigkeitsverteilungen über alle Textstufen hinweg. 

Alle jene Python-Skripts mit individuellen Outputs für ein Gedicht ("2_Confusion matrix" und "5_Auswertung") sind im Ordner für das jeweilige Gedicht zu finden. Die Python-Skripts ohne spezifischen Output ("1_POS Tagging" - "3_Extrahieren der Textstufen" und "4_Token+POS zu CSV") befinden sich einmalig im Repository. 

Die Ordnernamen stellen Kürzel für die bearbeiteten Gedichte dar: 

aptrm: "Alp-Traum" (12.01.1981)

nwtrg: "Newtonringe" (03.03.1981)

rsfrgmt: "Rosenfragment" (02./03.10.1981)

vwdazb: "vielleicht weil das Auge zuerst bricht" (11.10.1981)

wsnmp: "Wassersachen, nach Mimmo Paladino" (23./25.10.1981)

Alle zugrundeliegenden Materialien sind gemeinsam mit den Scans der Textzeugen in Collections des internen Repositoriums PHAIDRA der Universität Wien gesichert, begrenzt zugänglich: 
- Textzeugen. Collection für alle Textzeugen der Gedichte von Friederike Mayröcker. Eingeschränkter Zugang unter https://phaidra-local.univie.ac.at/o:45688
- XML-Dokumente. Collection für alle XML-Dokumente zu den Textzeugen der Gedichte von Friederike Mayröcker. Eingeschränkter Zugang unter https://phaidra-local.univie.ac.at/view/o:45808
- Sequenzen. Collection für alle CSV-Dokumente zu den Sequenzen der Textzeugen der folgenden Gedichte von Friederike Mayröcker. Eingeschränkter Zugang unter https://phaidra-local.univie.ac.at/view/o:45816
