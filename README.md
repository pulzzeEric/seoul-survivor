# Makcha: Seoul Survivor

> **Survive until the last train leaves.**

*Makcha* (막차) is Korean for "the last train of the night." This game is a pixel-art **survivors-like roguelite** set in real Seoul landmarks. Hold out against waves of very Seoul-specific enemies, like rush-hour crowds, rolling-suitcase stampedes and people who missed the last train, until the final departure.

The game is **open source and community-built**. Players suggest the maps, enemies, weapons and items for their own neighborhoods, the community votes, and the winners go into the game.

> **Status:** Pre-alpha / planning. No playable build yet. The name is a working title.

---

## Why this project?

**K-culture is having a moment.** K-pop, K-dramas, Korean films, food and webtoons have made Seoul a place that people around the world recognize and want to experience. We started this project to ride that wave with a game that lets players explore Seoul as locals know it: the crowded transfer stations, the late-night street food and the last-train dash, not just the postcard views.

- **For players abroad:** a playful, recognizable tour of the Seoul they've seen on screen
- **For Koreans:** the fun of seeing your own neighborhood, and its everyday chaos, turned into a game
- **For everyone:** a chance to put your corner of Seoul into the game yourself

## Concept

| | |
|---|---|
| **Genre** | Survivors-like roguelite: auto-attacks, endless waves, pick an upgrade on every level-up. One run takes 10–15 minutes. |
| **Setting** | Real Seoul landmarks, lightly parodied. The fun of seeing places you actually know. |
| **Art** | Pixel art. Gameplay uses a quarter-view (angled top-down) arena. Stage intros and boss scenes use side-view pixel illustrations with "living" backgrounds: moving crowds, flickering neon, steam from street stalls. |
| **Humor** | Everyday Seoul life turned into enemies and power-ups. |
| **Platform** | Web browser first, so there is nothing to install and runs are easy to share. |

## Stages

| Stage | Mood | Enemies | Items |
|---|---|---|---|
| **Seoul Station** *(first release)* | Night, last-train hour. The red-brick old station, the glass new station, and the Seoullo 7017 skygarden | Suitcase-dragging travelers, transfer crowds, people who missed the last train | Train lunchbox (heal), express-train dash (speed), departure board (extra time) |
| Hongdae | Night, neon, street buskers | Party zombies, flyer storms | Busker soundwave (area attack) |
| Gwanghwamun & Gyeongbokgung | Daytime, palace and plaza | Pigeon flocks, tour-group conga lines | Hanbok buff (speed) |
| Gangnam Station | Morning rush hour | Commuter crowds, late office workers | Iced Americano (attack speed) |
| Hangang Park | Sunset | Mosquito swarms, delivery scooters | Fried chicken (heal), ramyeon |
| Myeongdong | Street food and shopping crowds | Street hawkers, shopping-bag legions | Street-food combo |
| Namsan *(boss)* | Night, tower skyline | Giant Love-Lock Golem | — |

Future idea: link stations along Seoul Subway **Line 2**, a loop around the city, one stage per station.

## Roadmap

- [ ] **Phase 0 – Setup:** repo, licenses, contribution and content guidelines, choose a tech stack (candidates: Phaser 3 or plain Canvas)
- [ ] **Phase 1 – Prototype:** movement, auto-attack, enemy waves, XP and level-up choices, all with placeholder shapes. First question: is it fun?
- [ ] **Phase 2 – MVP: Seoul Station, Last Train:**
  - One pixel-art arena (station plaza, old station building, Seoullo 7017)
  - 1 character, 5 weapons, 5 enemies, 1 boss
  - The last-train departure time is the run timer
  - A side-view stage intro screen
  - Web release with an in-game **"Suggest your neighborhood"** button
- [ ] **Phase 3 – Community:** a weekly suggest → vote → ship cycle. The community picks the next stage.

## How content gets made

1. **Suggest:** open an issue using a content template (stage, enemy, weapon or item), or use the in-game suggestion button.
2. **Vote:** the community votes with 👍 reactions on the issue.
3. **Build:** accepted ideas are implemented with [build.interactor](https://build.interactor.com), an AI-driven software development tool, and through regular pull requests.
4. **Credit:** every accepted contributor is listed in the in-game credits and in [`CREDITS.md`](CREDITS.md).

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Original work only

This is an original game. Genre mechanics (auto-attacks, waves, level-up picks) are fair game. **Names, characters, art, sprites, music and sound from other games are not**, and tracing or editing them doesn't count as original. Real brand names and logos are replaced with parodies. See [CONTRIBUTING.md](CONTRIBUTING.md#original-work--ip-rules).

## License (proposed)

- **Code:** [MIT](LICENSE)
- **Art, audio and other assets:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Credit the creator and share alike.

## Getting started

_Coming in Phase 1._ Build and run instructions will be added once the tech stack is chosen.
