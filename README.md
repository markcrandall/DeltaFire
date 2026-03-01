# DeltaFire

An addition and subtraction tower-defense game built as a single HTML file. Solve math problems to fire weapons at alien invaders before they reach your tower.

A sibling game to [MultiFire](../MultiFire/) — same tower-defense gameplay, different math operations.

## How to Play

- Answer addition and subtraction questions by clicking one of four choices
- Correct answers fire a projectile at the nearest alien
- Wrong answers let all aliens advance closer to your tower
- If an alien reaches the tower, game over

## Weapon Tiers

Build a streak of correct answers to unlock more powerful weapons:

| Streak | Weapon | Effect |
|--------|--------|--------|
| 0+ | Bullet | Small homing projectile |
| 5+ | Fireball | Homing fireball with particle trail |
| 10+ | Lightning | Instant bolt with electric arc |
| 20+ | Laser | Instant beam, destroys on contact |

## Difficulty Scaling

Problems get harder as your streak grows:

| Streak | Problems |
|--------|----------|
| 0-4 | Single + single, single - single |
| 5-9 | Double + single, double - single |
| 10-19 | Double + double, double - double (10-50) |
| 20+ | Double + double, double - double (10-99) |

## Run It

Open `index.html` in any modern browser. No build step, no dependencies, no server required.

Works on desktop and mobile.

## Click this link to play online now:

[DeltaFire](https://htmlpreview.github.io/?https://github.com/markcrandall/DeltaFire/blob/main/index.html)
