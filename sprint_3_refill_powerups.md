# Sprint 3: Refill Mechanism & Special Items

## Goal
Enable dynamic board behavior where cleared items are replaced by falling items, and introduce special gameplay variants.

## Key Features
- **Gravity Implementation**: Logic for items to move down into empty cells.
- **Grid Refilling**: Spawning new items at the top of the grid to maintain board density.
- **Cascading Matches**: Automatic detection of matches formed after items fall.
- **Special Matchables**: Implementation of Striped, Wrapped, and Color Bomb variants when matching 4 or more items.

## Technical Components
- [MatchableGrid.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableGrid.cs): Enhanced with `Refill` and `MoveItem` logic.
- [MatchableVariant.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableVariant.cs): Defines different types of special candies.
- [MatchablePool.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchablePool.cs): Managing the lifecycle of special items.

## Verification
- Clear a match and confirm items above it fall down correctly.
- Verify that new items spawn at the top and settle in the correct cells.
- Create a match of 4 and verify a special item is spawned.
