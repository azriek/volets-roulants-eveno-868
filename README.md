# volets-roulants-eveno-868
Projet de domotisation de volets roulant eveno 868 MHz (également Profalux ? Bubendorff ? ), multi zone à partir d'une seule télécommande

En bref, l'idée à étudier:
- Contrôle sur les boutons d'une télécommande officielle avec des optocoupleur
- Lecture de la trame émise (via rtl-sdr ou cc1101)
- Altération du numéro de série dans la partie non chiffrée, sur les bits non utilisés dans le discriminant
- Emission de la trame modifiée
