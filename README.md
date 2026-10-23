# MKF - Merchants and Trainers

Hold the [Modifier Key Framework](https://github.com/eXgamble/Modifier-Key-Framework) key on a
merchant to trade, or on a trainer to train, straight away.

It plays out as if you had picked "What have you got for sale?" in dialogue, without the dialogue
menu: the NPC turns to you, says their answer and stays with you while you trade. The conversation
ends when the barter or training menu closes. Activating normally stays vanilla (Talk).

- **Buy / Sell** on merchants, **Pay For Training** on trainers. Someone who does both gets both:
  Buy / Sell on Activate, Pay For Training on the second button (X on a controller, R on a keyboard).
- An action only shows while the NPC offers it: a shop closed for the night shows no Buy / Sell, a
  trainer you can't train with any more shows no Pay For Training. A load order without trainers
  just never shows it.
- Nobody trades or trains while in combat, bleeding out, unconscious, knocked down or paralyzed.
- Covers the generic merchant and trainer topics plus the special ones (Urag gro-Shub, Fort
  Dawnguard, Castle Volkihar, Sofie, Tel Mithryn, Neloth, Talvas, Solstheim merchants).
- No plugin: one rule file and a translation file.

## Requirements

- Modifier Key Framework 1.8.0 or newer

## Files

- `mod/SKSE/Plugins/ModifierKeyFramework/MKF - Merchants and Trainers.json`: the rule
- `mod/Interface/Translations/MKF - Merchants and Trainers_ENGLISH.txt`: the labels (UTF-16 LE)

## License

GPL-3.0 (see LICENSE).
