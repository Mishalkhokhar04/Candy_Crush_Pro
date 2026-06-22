# Sprint 1: Project Setup & Core Grid System

## Goal
Establish the project foundation and implement the logical grid structure that will hold and manage the matchable items.

## Key Features
- **Project Infrastructure**: Unity project setup, folder structure (Assets/Scripts, Prefabs, etc.).
- **Grid Logical Layer**: Implementation of `MatchableGrid` to manage a 2D array of positions.
- **Item Spawning**: Initial spawning logic to fill the grid with random `Matchable` prefabs.
- **Coordinate Mapping**: Converting grid coordinates to world space positions.

## Technical Components
- [MatchableGrid.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableGrid.cs): Primary controller for the 2D grid logic.
- [Matchable.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/Matchable.cs): Base class for all items on the grid.
- [MatchablePool.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchablePool.cs): Object pooling for efficient item management.

## Verification
- Run the scene and ensure the grid fills with items.
- Verify through logs that the `MatchableGrid` correctly identifies empty and filled cells.
