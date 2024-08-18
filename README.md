# Monster Battle Game
Monster Battle Game is a turn-based strategy game where players select and command a team of elemental monsters to battle against a computer-controlled opponent. Drawing inspiration from the classic Pokémon games, players must strategically choose from a roster of 20 unique monsters, each belonging to one of five elemental types: Wind, Water, Fire, Plant, and Earth.


## Game Rules
1. **Monster Selection:**
    - The player selects 3 monsters from a pool of 20.
    - The computer also selects 3 monsters randomly from the same pool.
2. **Battle System:**
    - Battles are turn-based, where each player (human or computer) takes turns selecting a monster and using an ability.
    - Each monster has a set of abilities that deal damage or provide other effects (e.g., healing, status changes).
    - A monster is knocked out when its HP (Health Points) reaches 0.
    - The battle continues until all monsters on one side are knocked out.
3. **Turn Order:**
    - The AI starts off the game and alternates between AI and Player.
4. **Winning the Game:**
    - The game is won when all of the opponent's monsters are knocked out.

## Type Strengths and Weaknesses
The game features five elemental types: Wind, Water, Fire, Plant, and Earth. Each type has strengths and weaknesses against other types. These interactions affect how much damage an ability deals to an opponent based on their type.

**Type Interaction Table:**
- **Fire:**
  - Strong Against: Plant
  - Weak Against: Water, Earth
  - Neutral Against: Wind, Fire

- **Water:**
  - Strong Against: Fire, Earth
  - Weak Against: Plant
  - Neutral Against: Wind, Water

- **Plant:**
  - Strong Against: Water, Earth
  - Weak Against: Fire, Wind
  - Neutral Against: Plant

- **Wind:**
  - Strong Against: Plant, Fire
  - Weak Against: Earth
  - Neutral Against: Water, Wind

- **Earth:**
  - Strong Against: Fire, Wind
  - Weak Against: Water, Plant
  - Neutral Against: Earth

**Damage Modifiers:**
- **Strong Against:** Damage is doubled (2x).
- **Weak Against:** Damage is halved (0.5x).
- **Neutral Against:** Damage remains the same (1x).

## Example Interactions:
- **Fire vs. Plant:** A Fire-type attack on a Plant-type monster will deal 2x damage.
- **Water vs. Fire:** A Water-type attack on a Fire-type monster will deal 2x damage.
- **Plant vs. Earth:** A Plant-type attack on an Earth-type monster will deal 2x damage.
- **Wind vs. Earth:** A Wind-type attack on an Earth-type monster will deal 0.5x damage.
- **Earth vs. Wind:** An Earth-type attack on a Wind-type monster will deal 2x damage.

These interactions encourage strategic planning when choosing your monsters and deciding on your moves during battle. Understanding the type advantages and disadvantages is key to winning the game.