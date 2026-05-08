<p align="center">
<img src="logo.png" alt="DigiWise Invaders logo" width="1000"/>
</p>



# Language
#### [English README - Angol nyelvű readme](#english-version)
#### [Magyar nyelvű README - Hungarian README](#hungarian-version)

# Magyar verzió
<div align="center">
  <h2>Egy Space Invaders játék - A CrunchyBytes csapatától</h2>
</div>

## Mi is ez a játék?
Ez a játék a Space Invaders újragondolt változata, a DigiWise Challenge döntőjére a CrunchyBytes csapattól, multiplatform és többfajta irányítási támogatással.

#### Főbb jellemzők
* **Multiplatformos működés** - bármilyen HTML megtekintővel, vagy (saját hostolás esetén) bármilyen böngészővel kompatibilis
* **4 fajta irányítási mód** - Játszható billentyűzettel, érintve, kontrollerrel, vagy akár a hangerő gombokkal. Részletesebben az [irányítás](#irányítás) részben.
* **Kétnyelvű játék** - A leíráshoz hasonlóan a játék natívan támogatja az angol és a magyar nyelvet
* **Egyedi ellenségek speciális tulajdonságokkal** - Részletesebben a [karakterek](#karakterek) részben

## Karakterek
A játék 3 karaktertípussal rendelkezik, melyek meghatározott logika szerint támadnak, bírják az ütéseket és jutalmaznak haláluk esetén
#### Általános robotok
Ők csak sima robotok. Logikátlanul lőnek, legyőzésük pedig egyszerű. Egy találat után kipurcannak.
#### Digit robotok
Digit már egy kicsit más tészta. Ő egy hiperaktív, fiatalos robot. Fiataslos energiái miatt sokat tud lőni, de sajnos mindig elragadja a hév, így a célzásra már nem jut memóriakapacitás. Friss design-a miatt viszont strapabíró, 5 lövést képes kibírni mielőtt rövid zárlatot kapna.
#### Wise robotok
Wise egy újabb változó. Ő még tudja, milyenek voltak a régi szép idők, mikor még egy gémkapocstól kérdeztek az emberek és csoda volt, ha 3D kártyával tudták képezni. Pont emiatt tudja, hogy többet ésszel, mint tűzerővel. Ő nem használja feleslegesen lövedékeit, mivel tudja, hogy az pazarlás. Ehelyett megpróbálja úgy kialakítani a lövéseit, hogy azok nagyobb eséllyel találjanak és ki tudja, lehet, hogy még irányt is váltanak. Tervezésben egy régebbi modell, pont ezért nem bír annyit, mint barátja Digit.Az ő rendszere 3 lövés után már kék halált kap.


## Játékmódok
A játék 3 nehézséggel rendelkezik. Könnyű, közepes és nehéz.
#### Könnyű játékmód
A könnyű játékmódban megjelenen az általános robot, valamint Digit robotok. A két fajta robotokat kell legyőzni a pontszerzéshez
#### Közepes játékmód
A közepes játékmódban megjelennek az általános robot, valamint Wise robotok. A két fajta robotokat kell legyőzni a pontszerzéshez
#### Nehéz Játékmód
A nehéz játékmódban megjelennek az általános robotok, valamint a Digit és a Wise robotok összeállnak. Így mind a sima robotokat, valamint a DigiWise duót is le kell győzni a pontszerzéshez

## Irányítás
Tekintve, hogy a játék bárhonnan játszható, így az irányítás is ehhez igazokdik.
| Eszköz | Mozgás (Bal/Jobb) | Lövés |
| :--- | :--- | :--- |
| **Billentyűzet** | Nyilak | `Space` |
| **Kontroller** | Right Joy / D-Pad | `RT` (Right Trigger) |
| **Érintőképernyő** | Képernyő oldalai | Alsó sarkok |
| **Mobil (Extra)** | Hangerő gombok (+ / -) | Képernyő gombok |

## Telepítés és játék
A játék a döntő idjeére elérhető [online játék formájában](https://digiwise.bence0327.hu/), valalmint a játék megtekinthető és játszható az [index.html](https://github.com/QuaternionDev/crunchybytes-space-invaders/blob/main/index.html) fájl letöltésével bármilyen HTML megtekintőből.

# English version
<div align="center">
  <h2>A Space Invaders game by the CrunchyBytes team</h2>
</div>

## What is this game?
This is a reimagined version of Space Invaders with multiplatform support and a wide range of control options, created by the CrunchyBytes team for the DigiWise Challenge final 

#### Key Features
* **Multiplatform Compatibility** – Runs in any HTML viewer or modern web browser (when self-hosted).
* **4 Control Schemes** – Play with a keyboard, touch screen, controller, or even your device's volume buttons. Detailed in the [Controls](#controls) section.
* **Bilingual Support** – Just like this documentation, the game natively supports both English and Hungarian.
* **Unique Enemies with Special Abilities** – Detailed in the [Characters](#characters) section.

## Characters
The game features 3 types of characters, each with its own attack logic, durability, and point value.
#### Generic Robots
They are just simple bots. They shoot sporadically and are easy to defeat. They go down after a single hit.
#### Digit Robots
Digit is a different story. He is a hyperactive, youthful robot. Thanks to his high energy, he can fire rapidly, but he always gets carried away, leaving no memory capacity for actual aiming. However, his modern design makes him durable: he can withstand 5 hits before short-circuiting.
#### Wise Robots
Wise represents a higher level of intelligence. He remembers the "good old days" when people asked a paperclip for help and 3D graphics were a miracle when he got trained. Because of this, he prefers brains over brawn. He doesn't waste ammunition; instead, he tries to predict the player's movement to ensure his shots land. Being an older model, he isn't as tough as his friend Digit—his system hits a "Blue Screen of Death" after only 3 hits.

## Game Modes
The game features 3 difficulty levels: Easy, Medium, and Hard.
#### Easy Mode
In Easy mode, Generic robots and Digit robots appear. You must defeat these two types to earn points.
#### Medium Mode
In Medium mode, Generic robots are joined by Wise robots.
#### Hard Mode
In Hard mode, Generic robots, Digit, and Wise all team up. You must face both the basic bots and the DigiWise duo to survive.

## Controls
Since the game is designed to be played anywhere, the controls are adapted to every platform.

| Device | Movement (Left/Right) | Shoot |
| :--- | :--- | :--- |
| **Keyboard** | Arrow Keys | `Space` |
| **Controller** | Right Joy / D-Pad | `RT` (Right Trigger) |
| **Touch Screen** | Screen Sides | Bottom Corners |
| **Mobile (Extra)** | Volume Buttons (`+` / `-`) | On-screen Buttons |

## Installation and Play
During the challenge, the game is available as an [online web game](https://digiwise.bence0327.hu/spaceinvaders). You can also view and play it offline by downloading the [index.html](https://github.com/QuaternionDev/crunchybytes-space-invaders/blob/main/index.html) file and opening it in any HTML-compatible viewer.