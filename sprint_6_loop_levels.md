# Sprint 6: Game Loop, Levels & Optimization

## Goal
Finalize the game structure with win/loss conditions, level goals, and ensure smooth performance across devices.

## Key Features
- **Win/Loss Conditions**: Implementing level objectives (e.g., reach X score in Y moves) and the game over screen.
- **Level Progression**: Transitioning between different levels or resetting the board with new goals.
- **Optimization**: Finalizing object pooling (`MatchablePool`, `MatchableFXPool`) to prevent memory spikes.
- **Bug Scrub**: Polishing edge cases like simultaneous matches or rapid user input during animations.

## Technical Components
- [GameManager.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/GameManager.cs): Handles level logic and win/loss states.
- [MatchablePool.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchablePool.cs) & [MatchableFXPool.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableFXPool.cs): Optimized for production performance.

## Verification
- Complete a level objective and verify the "Victory" state is triggered.
- Run out of moves and verify the "Game Over" screen appears.
- Monitor console for any performance warnings or errors during heavy cascades.
