# Speedcube Timer

A cstimer-style speedcubing timer that installs to your phone's home screen and runs full screen, offline.

**Open it:** https://eito-okada.github.io/speedcube-timer/

- Random-state 3x3 and 2x2 scrambles (two-phase solver), scramble previews for 14 WCA events
- Sessions, WCA-rule averages (mo3, ao5, ao12, ao50, ao100), charts
- Optional WCA inspection with +2 / DNF, voice or beep alerts
- Themes, timer fonts, sizes; cstimer import and JSON export

## Add it to your home screen
- **iPhone:** open the link in Safari → Share → *Add to Home Screen*
- **Android:** open the link in Chrome → menu → *Add to Home screen* (or *Install app*)

## Sign in with Google
Signing in syncs your solves and settings across devices and lets you join the friends board,
which shows each person's best single, ao5 and ao12 per puzzle. Solves are saved on the device when signed out.
Sign-in and storage use Firebase (Authentication + Cloud Firestore); each person can only read and change their own solves.
