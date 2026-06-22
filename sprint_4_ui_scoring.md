# Sprint 4: Scoring, UI & Visual Feedback

## Goal
Add the meta-layer of the game: tracking player progress, displaying information, and providing scoring feedback.

## Key Features
- **Score System**: Assigning points for matches and bonuses for special items.
- **User Interface**: Implementation of Score Text, Move Counter, and Progress Bar.
- **Floating Text**: `ScorePointFX` for showing points earned at the match location.
- **Game State Management**: Tracking if the player is currently moving, matching, or idle.

## Technical Components
- [GameManager.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/GameManager.cs): Primary authority for score and game flow.
- [ScorePointFX.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/ScorePointFX.cs): Visual feedback for points.
- [MatchableFXPool.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableFXPool.cs): Efficiently managing scoring and effect objects.

## Verification
- Confirm that matching items increases the total score.
- Verify UI updates in real-time as moves are made and points are earned.
