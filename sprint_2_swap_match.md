# Sprint 2: Core Gameplay: Swapping & Matching

## Goal
Implement the fundamental match-three interaction: swapping adjacent items and detecting valid matches.

## Key Features
- **Input Handling**: Detection of mouse/touch clicks and drags to select items.
- **Swap Logic**: Moving items between adjacent cells with animation and rollback if no match occurs.
- **Match Detection**: Algorithms to find horizontal and vertical lines of 3 or more identical items.
- **Validation**: Ensuring only valid swaps (adjacent, resulting in a match) are permanent.

## Technical Components
- [InputReader.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/InputReader.cs): Handles player interactions.
- [Match.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/Match.cs): Contains the logic for finding and validating matches.
- [MatchableGrid.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableGrid.cs): Extended to handle swapping and coordinate validation.

## Verification
- Perform a swap and confirm items move.
- Verify that matching 3 items in a row triggers a "match found" state in the logic.
