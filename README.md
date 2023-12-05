
# FlyStats DCS

**FlyStats DCS** is a Windows application for viewing and analysis of your gameplay statistics from the DCS World game. This app uses **.acmi** files from Tacview for data import.

## Downloads
- You can download executable file from this repository releases tab
- Later on you will be able to download app from website: [flystats.io](https://www.flystats.io/) (Under construction...)

## App Features
- Detailed player, aircraft, sortie and missile statistics
- Match score table, supports filtering, sorting and export to image
- Authorization and ability to save player statistics, as well as match statistics
- Authorized users can track their data across all of their matches, supports date filtering
- Tracking of destroyed air and ground targets, guns kills, launched missiles and other munitions
- Graphs for missile statistics: Splashes/Distance, Splashes/Launch_altitude, Accuracy/Launch_altitude

## How to import replays data
- Open your original **.acmi** file in Tacview
- In Tacview app Select File -> Export Flight Log
- Save file to any location, make sure file format is "XML Flight Log"
- In FlyStats app press "Import" and select your created file in .XML format

Don't have tacview? You can download it here: [Tacview Website](https://www.tacview.net/)

## Screenshots
<details>

<summary>Match scoreboard</summary>

![Match scoreboard](screenshots/screenshot_scoreboard.png)

</details>

<details>

<summary>Player saved matches </summary>

![Player saved matches ](screenshots/screenshot_matches.png)

</details>

<details>

<summary>Player statistics</summary>

![Player statistics](screenshots/screenshot_player.png)

</details>

<details>

<summary>Aircraft statistics</summary>

![Aircraft statistics](screenshots/screenshot_airframe.png)

</details>

<details>

<summary>Aircraft sorties statistics</summary>

![Aircraft sorties statistics](screenshots/screenshot_airframe_sorties.png)

</details>

<details>

<summary>Sortie statistics</summary>

![Sortie statistics](screenshots/screenshot_sortie.png)

</details>

## Statistics notes
- Due to Fligh Log limitations missile travel distance is calculated as distance between launch point and hit point in 3D space and can be referenced as "Estimate missile travel distance".
- Accuracy parameter only includes data gathered from missiles, bombs and other launchable munitions, excluding gun kills.
- Missiles that hit other missiles are not counted in hits, accuracy, or kills statistics.
- If player switched teams in a match, the last one of them will be displayed in the match score table. However, in the player's sortie statistics you can see which team exactly he played.
- If player damaged ground target, but it has not been destroyed - it will be marked as "damaged" in sortie killfeed.

## Feedback & Bug Reports

If you have any feedback, please reach out to me in Discord [dorvex.](https://discordapp.com/users/dorvex.) (With .)\
You can also create feature request or bug report at the repo [GitHub Issues](https://github.com/Dorvex/FlyStats-DCS-Public/issues)