# Yatzy Game

## Overview
Yatzy is a popular dice game where players take turns rolling dice and trying to achieve various scoring combinations. The goal is to maximize your score by strategically selecting which dice to keep and which to re-roll.

## Rules
1. **Number of Players:** 2 or more players.
2. **Dice:** The game uses 5 dice.
3. **Turns:** Each player has up to three rolls per turn. After rolling, the player can choose to keep some dice and re-roll the others.
4. **Scoring Categories:**
   - Three-of-a-kind
   - Four-of-a-kind
   - Full house
   - Small straight
   - Large straight
   - Yatzy (five of a kind)
   - Chance (sum of all dice)
5. **Winning:** The game ends after all players have filled in all scoring categories. The player with the highest total score wins.

## Design System Documentation

### Color Scheme
- **Primary Color:** #1D4E89 (Dark Blue)
- **Secondary Color:** #F0A500 (Bright Orange)

### Fonts
- **Headings:** 'Arial Black', sans-serif
- **Subheadings:** 'Arial', sans-serif
- **Body Text:** 'Georgia', serif

### Rationale
- **Color Choices:** The dark blue provides a calming background, while the bright orange adds a pop of color for important elements.
- **Font Choices:** Arial is clean and easy to read, suitable for headings, while Georgia offers a classic feel for body text.

Dice Representation:
+-------+
|   *   |  <-- Dot (pip)
| *   * |
|   *   |
+-------+

## Additional Documentation

### Layout and Flow
- The game layout consists of a scorecard and a dice rolling area.
- Players roll the dice and score based on the categories in the scorecard.

### User Interactions
- Clicking the "Roll Dice" button will simulate rolling the dice and updating the scorecard.

### Design Choices
- The use of color contrasts makes important elements stand out, enhancing the user experience.
