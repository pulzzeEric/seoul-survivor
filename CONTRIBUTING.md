# Contributing to Makcha: Seoul Survivor

Thanks for helping build Seoul's last-train survival game! You don't need to be a programmer to contribute. The most valuable thing you can bring is **knowledge of your own neighborhood**.

## Ways to contribute

| You are… | You can… |
|---|---|
| **A player / local** | Suggest stages, enemies, weapons and items. Vote on ideas. Report bugs. |
| **A pixel artist** | Draw sprites, tiles, stage backgrounds and intro illustrations. |
| **A sound designer** | Make sound effects, ambient city sounds and music. |
| **A developer** | Implement gameplay, fix bugs, improve performance and tooling. |
| **A translator** | Translate in-game text. The game ships in Korean and English first. |

## Suggesting content

1. Search existing issues to avoid duplicates.
2. Open a new issue using the matching template: **Stage**, **Enemy**, **Weapon**, or **Item**.
3. Fill in:
   - **Name** (Korean and/or English)
   - **Where in Seoul** (landmark or neighborhood)
   - **What it does** (behavior, effect, or stage gimmick)
   - **Why it's funny or recognizable to locals**
   - Optional: a rough sketch or reference photo **you took yourself**
4. The community votes with 👍. Top-voted ideas are reviewed each week, and accepted ones get the `accepted` label.

**Good example**

> **Enemy: Transfer Crowd (환승 인파)**. Seoul Station. A wall of commuters that moves in one direction and pushes the player along. Anyone who has transferred at rush hour knows it.

## Content guidelines

Contributions should be playful, not hurtful. We do **not** accept content that:

- Demeans or mocks any region, neighborhood or group of people
- Targets vulnerable people (homeless people, people with disabilities, the elderly, migrants and others) as enemies or as jokes. **Enemies should be situations and phenomena** (crowds, noise, being late, weather), not kinds of people.
- Depicts real, identifiable people
- Uses real brand names or logos. Use a parody or fictional name instead.
- Is sexual, hateful, or excessively violent

Maintainers may edit or decline suggestions that don't fit these guidelines.

## Original work & IP rules

- ✅ Genre mechanics (auto-attack, waves, level-up choices) are free to use.
- ✅ Original art inspired by real Seoul places.
- ❌ Names, characters, sprites, art, music or sound effects from other games, including traced, recolored or edited versions.
- ❌ Assets you don't have the rights to. Third-party assets must have a compatible license (CC0, CC BY, CC BY-SA, MIT) and be recorded in [`CREDITS.md`](CREDITS.md) with their source and license.
- ❌ Photos or reference images you didn't take yourself, unless their license allows it.

When in doubt, ask in the issue before starting.

## Asset guidelines (draft)

These will be finalized during Phase 1.

- **Style:** pixel art with a limited palette. Gameplay uses a quarter-view (angled top-down) perspective. Stage intros and boss scenes are side-view illustrations.
- **Sprites:** base tile size and sprite dimensions are TBD.
- **Format:** keep SVG source art where available; use PNG with transparency for gameplay. Separate animation frames or a sprite sheet with a frame list.
- **Audio:** OGG and/or MP3, normalized volume.
- **File naming:** `lowercase-with-dashes`, e.g. `seoul-station-transfer-crowd-walk.png`.

## Code contributions

1. Fork the repo and create a branch: `feature/<short-name>` or `fix/<short-name>`.
2. Keep pull requests focused, one feature or fix each.
3. Describe what changed and how to test it. Add screenshots or GIFs for visual changes.
4. Link the related issue (`Closes #123`).
5. A maintainer will review it. Be ready for some back-and-forth.

The chosen stack is **TypeScript** with strict type checking, **Phaser 4** (prototype validation starts with 4.2.1), and **Vite**. See the [technical direction](README.md#technical-direction) for code structure and prototype acceptance criteria. Build steps and code style will be documented when the Phase 1 development environment is implemented.

### AI-assisted contributions

Accepted ideas may be implemented with [build.interactor](https://build.interactor.com) or other AI tools. AI-assisted code and assets are welcome, as long as you:

- Review and test what you submit
- Make sure generated assets don't copy or closely imitate existing copyrighted work
- Say in the PR that it was AI-assisted

## Licensing of contributions

By contributing, you agree that:

- **Code** you submit is licensed under the [MIT License](LICENSE).
- **Art, audio and other assets** you submit are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- You have the right to submit what you contribute.

## Credits

Every accepted contribution, whether an idea, art, sound, code or translation, is credited in the game and in [`CREDITS.md`](CREDITS.md). Tell us in your issue or PR how you'd like your name to appear.

## Code of conduct

Be kind, be constructive, and remember everyone here is volunteering their time. Harassment of any kind isn't tolerated. A full code of conduct will be added before public launch.
