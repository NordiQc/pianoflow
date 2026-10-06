# PianoFlow

PianoFlow t'aide à apprendre des pièces au piano à partir d'un fichier MIDI : les notes descendent vers le clavier, tu les joues à ton rythme, et l'app sépare elle-même la main droite et la main gauche. Gratuit, pour Windows et Android, sans connexion.

**[Télécharger la dernière version](https://github.com/NordiQc/pianoflow/releases/latest)**

| Pour | Fichier |
| --- | --- |
| Windows | `PianoFlow-Windows.msi` (ou `PianoFlow-Windows-setup.exe`) |
| Android | `PianoFlow-Android.apk` |

L'app n'est pas encore signée : Windows affiche « Windows a protégé votre ordinateur ». Clique sur *Informations complémentaires*, puis sur *Exécuter quand même*.

Pour vérifier ton téléchargement, compare sa somme SHA-256 avec la ligne du fichier dans `SHA256SUMS.txt` (version de la page des versions). Dans PowerShell : `Get-FileHash .\PianoFlow-Windows.msi -Algorithm SHA256`.

Un problème, une idée, un fichier MIDI qui se sépare mal ? [Ouvre un ticket](https://github.com/NordiQc/pianoflow/issues).

Ce dépôt ne contient que les versions à télécharger, pas le code source.

---

**English.** PianoFlow helps you learn piano pieces from any MIDI file: notes fall toward the keyboard, and the app splits the right and left hands for you. Free, for Windows and Android, works offline. The interface is available in English (Settings, Interface language). Grab the latest `.msi` or `.apk` from the [releases page](https://github.com/NordiQc/pianoflow/releases/latest). This repository only hosts downloads, not the source code.
