# Générateur MIDI 3 Pistes — v13

Nouveautés par rapport à la v12 :

## 19 nouveaux styles depuis fichiers MIDI analysés
- **Traditionnel** : Nigun (3/8), Horo (5/8), Macédonien (7/8), Kopanica (11/8), Kolo (4/4)
- **Latin** : Boléro (remplacé), Bossa Ts, Cumbia Ts, Forró Ts (2/4), Milonga Ts, Samba 2, Tombo (7/4), Xote Ts, Latin 2, Latin 3
- **Jazz** : Swing (remplacé), Blues Swing
- **Pop** : Funk 1, Funk 2

## Moteur (buildTracks)
- Support des **motifs sur 2 mesures** : champ `m: 2` dans un style ; la 2e mesure porte la variation (basse, accords ou les deux) ; chaque événement prend l'accord de sa propre mesure dans la grille.
- Nouveaux codes de basse : `'4'` (quarte) et `'3M'` (tierce majeure fixe, pour les chromatiques sur accords mineurs).
- Les styles 1 mesure existants sont inchangés.

Fichier : `generateur_midi_3_pistes_v13.html` (fonctionne hors ligne, un seul fichier).
