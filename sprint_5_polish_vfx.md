# Sprint 5: Sound, Juice & VFX

## Goal
Enhance the player experience through auditory and visual feedback, making the game feel "juicy" and responsive.

## Key Features
- **Sound Integration**: Implementation of sound effects for swapping, matching, and cascades.
- **Visual Effects (VFX)**: Adding particle systems for candy explosions and special item activations.
- **Matching Animations**: Smooth scaling or rotation animations when items match.
- **Board Juice**: Subtle camera shakes or UI bounces for significant events.

## Technical Components
- [SoundManager.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/SoundManager.cs): Controls all audio playback.
- [MatchableFX.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/MatchableFX.cs): Manages the lifecycle of visual effects.
- [ColorExplodeFX.cs](file:///f:/CandyCrushSagaClone-Unity-main/CandyCrushSagaClone-Unity-main/MatchThree/Assets/Scripts/Core/ColorExplodeFX.cs): Specialized effect for color bomb explosions.

## Verification
- Perform a match and confirm both sound and visual effects trigger simultaneously.
- Verify that special item matches produce more intense visual feedback than standard matches.
