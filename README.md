<div align="center">

<img src="assets/hero.webp" width="100%" alt="A walk through the minos3D labyrinth, ending on the name Adrien">

<sub>Rendered from <a href="https://github.com/4drie2/minos3D">minos3D</a>'s own map and textures, same DDA raycasting.</sub>

</div>

<br>

Work-study student at 42 Le Havre. C and C++ for school; TypeScript for two products that run on a server I administer.

<br>

## I. Shipped

<img src="assets/plate-league.jpg" width="100%" alt="One League">

<a href="https://oneleague.fr"><img src="https://img.shields.io/website?url=https%3A%2F%2Foneleague.fr&label=oneleague.fr&style=flat-square&labelColor=0B0B0E&color=B48C28&up_message=online&down_message=down" alt="oneleague.fr status"></a>

An unofficial ranked foosball league for 42 students, now also chess, Smash, Street Fighter and darts. You sign in with the 42 intranet, declare a match from a browser extension that lives inside intra.42.fr, and both players confirm the score. Elo with an anti-farming rule, live updates over SSE, tournaments, seasons, a GDPR export and delete.

I administer the project's GitHub organisation and its server. Production and staging deploy from GitHub Actions, and a security audit runs every morning. The repository is private; the site is open to every 42 student.

<img src="assets/arch-league.svg" width="100%" alt="One League architecture: extension and web app, Caddy, Hono API, PostgreSQL, GitHub Actions, staging">

<br>

<img src="assets/plate-routine.jpg" width="100%" alt="routine">

A budget and food coach I built for myself. A photo of a receipt goes through OCR, a nutrition audit, then a reconciliation engine that pairs it with the bank transaction (amount within 2 %, date within 4 days). The audit model depends on what the month has already cost: the larger model up to 4 €, a lighter one up to 5 €, then the audit stops while OCR keeps running. The coach runs on Vertex AI in Paris. Private, self-hosted next to One League.

<img src="assets/arch-routine.svg" width="100%" alt="routine pipeline: receipt photo, OCR, nutrition audit, bank feed, reconciliation, PostgreSQL, coach, AI spend gauge">

<br>

<img src="assets/plate-musicroom.jpg" width="100%" alt="Music Room">

Collaborative listening rooms, a 42 subject built in a team. NestJS on Fastify, Drizzle, PostgreSQL, socket.io, React. My part: Spotify sign-in and account linking with token refresh, fixes on the Google flow, most of the front end. 85 of the repository's 105 commits, written in one week.

<br>

## II. The labyrinth

<img src="assets/labyrinth.svg" width="100%" alt="The 42 curriculum as a path through the minos3D labyrinth, 21 steps from the Piscine to KFS-1">

<sub>
<a href="https://github.com/4drie2/libft">libft</a> ·
<a href="https://github.com/4drie2/get_next_line">get_next_line</a> ·
<a href="https://github.com/4drie2/ft_printf">ft_printf</a> ·
<a href="https://github.com/4drie2/pipex">pipex</a> ·
<a href="https://github.com/4drie2/push_swap">push_swap</a> ·
<a href="https://github.com/4drie2/fractol">fract-ol</a> ·
<a href="https://github.com/4drie2/philosophers">philosophers</a> ·
minishell (private) ·
<a href="https://github.com/4drie2/minos3D">minos3D</a> ·
<a href="https://github.com/4drie2/CPP00">CPP 00</a>–<a href="https://github.com/4drie2/cpp09">09</a> ·
<a href="https://github.com/4drie2/inception">Inception</a> ·
<a href="https://github.com/4drie2/python_data_science-0-starting">Python</a>
</sub>

<br><br>

## III. Workshop

- [healthcheck](https://github.com/4drie2/healthcheck): a phone notification when a school session drops, without touching the lock screen. Written so classmates can set it up on their own.
- [csv-to-poster-room-pdf](https://github.com/4drie2/csv-to-poster-room-pdf): a CSV of room assignments in, one printable door card per room out.
- [SuperTripMaster](https://github.com/4drie2/SuperTripMaster): vehicle dashboard on an ESP32 with a 320×240 screen (speed, RPM, trip, temperatures, battery). LVGL, plus an SDL build to work without the board.
- [logtime](https://github.com/4drie2/logtime) and [WhoConnected](https://github.com/4drie2/WhoConnected): small tools on the 42 API, monthly log time and who is on campus right now.
- [kfs-1](https://github.com/4drie2/kfs1): Kernel From Scratch, part one, in progress. The course I write alongside the code is eleven chapters in.
- [42calculator](https://github.com/lucas-ht/42calculator/pull/71): a small fix proposed upstream to the 42 level calculator.

<br>

## IV. Ledger

<img src="assets/ledger.svg" width="100%" alt="Every commit on main branches from October 2024 to October 2026, public and private, as a 3D skyline">

<br>

<div align="center">

<a href="https://42lehavre.fr"><img src="assets/chip-42lehavre.svg" height="34" alt="42 Le Havre"></a>
<a href="https://42.fr/en/42-in-paris/42-start-up-club/"><img src="assets/chip-startupclub.svg" height="34" alt="42 Start'up Club"></a>
<a href="https://www.linkedin.com/company/42entrepreneurs/"><img src="assets/chip-entrepreneurs.svg" height="34" alt="42 Entrepreneurs"></a>
<a href="https://42blockchain.com/"><img src="assets/chip-blockchain.svg" height="34" alt="42 Blockchain"></a>

<sub><a href="https://www.linkedin.com/in/adrien-bidaux">LinkedIn</a> · <a href="https://www.flickr.com/photos/195770192@N05/">photographs</a></sub>

</div>
