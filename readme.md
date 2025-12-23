# Read Me

## Installationen

MiKTex installieren
https://miktex.org/download

Strawberry Perl installieren
https://strawberryperl.com/releases.html

## Packages für Latex in VSCode:

- LaTeX
- LaTeX Utilities
- LaTeX Workshop

## GIT Setup:

1. Ordner lokal erstellen
2. Ordner in Terminal öffnen und folgende Befehle ausführen:
3. git init
4. git remote add origin https://github.com/Ammannmarco/Test_Bth2.git
5. git push

## Öffnen in Vs Code:

Open Folder -> Hauptordner mit Main drin öffnen
in VS-Code: linker Balken -> TEX -> View LaTeX PDF

## Tipps & Tricks

ctrl drücken und in PDF-Vorschau auf Text klicken -> öffnet Text in Code

## GIT Ablauf bei Änderungen:

### Jedes mal vor Beginn der Arbeit machen!

1. LaTeX Ordner in Visual Studio Code mit Open Folder geöffnet
2. Terminal in Visual Studio Code öffnen, kontrollieren ob korrekter Pfad (Ordner mit LaTeX)
3. folgende Befehle im Terminal ausführen:
   a. git pull

### Jedes mal vor Beenden der Arbeit machen!

1. LaTeX Ordner in Visual Studio Code mit Open Folder geöffnet
2. Terminal in Visual Studio Code öffnen, kontrollieren ob korrekter Pfad (Ordner mit LaTeX)
3. folgende Befehle im Terminal ausführen:
4. git add .
5. git commit -m "Was wurde gemacht"
6. git push

## Referenzieren:

### Tabellen:

in Text:
Text~\ref{tab:Bildflugparameter}
in Tabelle:
\begin{table}[h!]
...
\label{tab:Bildflugparameter}

### Kapitel:

in Text:
Text~\ref{subsec:Instrumentarium}
Im Titel:
\subsection{Instrumentarium}
\label{subsec:Instrumentarium}

-> Analog für Sections, Bilder mit
ref{sec:...}
ref{fig:...}
