# Blockout Starter Pack - Release Log
Release Logs: https://github.com/xavier150/BlockoutStarterPack/wiki/Release-Logs

## Version 3.2.0
    - Still in progress...
    - Overview level update.
    - Demonstration1 level update.
    - Demonstration2 level update.

## New Blueprints
    (Interactions)
    - B_TriggerButton:
        A new base class for trigger buttons.
        Better replication with causer info when button is pressed.
        New "On Button State Change" event dispatcher.

    - B_TurnToCameraComponent:
        Fixed: Component try to access player camera when not available.

## Blueprints updates
    (Interactions)
    - B_FloorButton: Now uses B_TriggerButton as parent actor.
    - B_PushButton: Now uses B_TriggerButton as parent actor.

    (Lights)
    - B_BlockingLights: You can now control the emissive intensity.
    
    (Decals)
    - B_BlockingDecal: Tick is disabled by default.
    - B_ZoneDecal: Now supports all rotation types and corner pivot point.
    - B_SimpleBlockingDecal: Now supports corner pivot point.
        
    (Procedural)
    - B_Ladder_01: New "Horizontal Mat" and "Vertical Mat" to support custom material.
    - B_StairPlane: New "Fit Mat" option.

    (Interactions)
    - B_FloorButton: Added output to return self in Event Dispatchers.

    (Doors)
    - B_BaseAutoDoor: Added callable functions to open, close, or toggle doors.

    (Others)
    - B_DisplayPanel: Function "UpdateOnlyPanelText" renamed to "SetText".
    - B_BlockoutTooltipActor: You can now change the color of the circle.

    (BlockingTooltip)
    - B_BlockingTooltipActor: Updated functions.

## Meshes Updates
    (Primitives)
    - Fixed UV offset on all primitives.
    - Improved face subdivisions on all primitives.

    (Interactions)
    - Added root bones to interaction skeletons and updated interaction animation sequences.

## Folder Name Changes
    - Meshes/Roads/Road → Meshes/Roads (fixed asset duplication issue)

## Textures updates
    - Fixed texture types.

## Asset Name Changes
    - B_ProcedularBlockingActor -> B_ProceduralBlockoutActor
    - B_BlockingTooltipActor -> B_BlockoutTooltipActor
    - SM_FloorButtonPuch -> SM_FloorButton_Push
    - SM_ButtonPuch -> SM_Button_Push

## Asset Change
    - SK_Button_Skeleton: The bone "ButtonPuch" renamed to "ButtonPush".