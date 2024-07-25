# Blocking Starter Pack - Release Log
Release Log: https://github.com/xavier150/BlockoutStarterPack/wiki/Release-Logs

## Version 3.0.0
    - Pack Rename "Blocking Starter Pack" to "Blockout Starter Pack"
    - More control in mateial for instanced use.
    - Overview level update.
    - Demonstration level update.
    - BP_DisplayPanel now use multi line text varriables.
    - More procedural materials
    - Minimal version: Unreal Engine 5.0

## New Meshs
    (Trashs)
    - SM_TrashCans_01
    - SM_TrashCansOpen_01
    - SM_TrashCansLid_01
    
    (Furnitures)
    - SM_Armchair_01
    - SM_DiningChair_01
    - SM_OfficeChair_01
    - SM_DinnerTable_01
    
    (Bedroom)
    - SM_BedDouble
    - SM_BedSingle
    
    (Vehicles)
    - SM_SimpleRims
    - SM_TruckRims
    - SM_TruckWheel
    - SM_ContainerShip_01
    - SM_ContainerShipEmpty_01
    
    (Weapons)
    - SM_Target_01
    - SM_Target_02
    - SM_TargetFoot_01
    - SM_TargetFoot_02
    - SM_ArrowTargets_01
    - SM_ArrowTargetsFloor_01
    
    (Vegetations)
    - SM_Tree_01
    
    (Primitives)
    - SM_Cube
    - SM_Ramp
    - SM_Cylinder
    - SM_CylinderQuarter
    - SM_Sphere
    - SM_SphereOctant
    - SM_Cone
    - SM_ConeQuarter
    
    (Primitives.Others)
    - SM_Cube_CenterPivot
    - SM_Ramp_CenterPivot
    - SM_Cylinder_CenterPivot
    - SM_Cube_MultiFace
    - SM_CylinderBend_50
    - SM_CylinderBend_150
    - SM_CylinderBend_250
    - SM_CylinderBend_350
    - SM_CylinderBend_450
    - SM_RectangleAngle_50
    - SM_RectangleAngle_150
    - SM_RectangleAngle_250
    - SM_RectangleAngle_350
    - SM_RectangleAngle_450
    - SM_RectangleBend_50
    - SM_RectangleBend_150
    - SM_RectangleBend_250
    - SM_RectangleBend_350
    - SM_RectangleBend_450

    (Decorations)
    - SM_Padlock_Open
    - SM_Padlock_Break
    
    (DisplayPanels)
    - SM_DisplayPanels_400x200

## Meshs Updates
    (Architecture.Floors)
    - SM_Floor_1000x1000 : Better pivot point

    (Architecture.Stairs)
    - SM_Stair_100 : Better pivot point
    - SM_Stair_200 : Better pivot point
    - SM_StairPlane_100 : Better pivot point
    - SM_StairPlane_200 : Better pivot point
    - Add underscore before the sizes infos.

    (Architecture.Barriers)
    SM_Barrier03_200cm : Fix collisions
    SM_Barrier03_500cm : Fix collisions
    
    (Vehicles)
    New wheel mesh on all models.

    (DisplayPane)
    - Better UV.
    - Use MI_DevGray and MI_DisplayPanelFace as mat. (Fit UV so you can change with a custom Texture)
    - Add underscore before the sizes infos.

    (Extra)
    - SM_SnowMan_01 : Add MI_DevBrown for arms
    - SM_Campfire : Mat switch to MI_DevBrown
	
	(BigBuildings)
	- SM_Building_02 : New collisions for balconies

    (All)
    General UV update on all meshs.

    

## Meshs Move
    - SM_SimpleWheel : Move from Extra folder to Vehicles folder
    - SM_SimpleTire : Move from Extra folder to Vehicles folder
    
## New Blueprints
    (Decal Class)
    - B_BlockingDecal
    - B_SimpleBlockingDecal
    - B_ZoneDecal
    - BlockingDecalData
    - BlockingDecalMaterialParameters_Struct
    
    (Decal)
    - B_SquareZone_Decal
    - B_CircleZoneDecal
    - B_OctagonZoneDecal
    
    - B_CrossDecal
    - B_LessDecal
    - B_SquareDecal
    - B_ZoneDecal

    - B_SquareZoneBlue_Decal
    - B_SquareZoneGreen_Decal
    - B_SquareZoneRed_Decal
    - B_SquareZoneYellow_Decal

    - B_SripeZoneBlue_Decal
    - B_SripeZoneGreen_Decal
    - B_SripeZoneRed_Decal
    - B_SripeZoneWhite_Decal
    - B_SripeZoneYellow_Decal

    (Light Class)
    - B_BlockingLights

    (Light)
    - B_CeilingLight01
    - B_CeilingLight02a
    - B_CeilingLight03a
    - B_CeilingLight03b
    - B_CeilingLightBulb
    - B_CeilingLightFlat02a
    - B_FlamingTorchWithSupport
    - B_RoadLamp_01
    - B_RoadLight

    (Interactions)
    - B_FloorButton
    - B_PushButton

    (Procedular Class)
    - B_ProcedularBlockingActor

    (Procedular)
    - B_StairPlane
    - B_BarrierWall
    - B_Ladder_01
    - B_Ladder_02

    (Other)
    - B_BlockingTooltipActor

## New Decal and BP Decals
    - B_SquareZoneYellow_Decal

## Blueprints updates
    - B_SimpleCameraPreview : Camera component replaced by a simple scene component.

    (DisplayPanels)
    - B_DisplayPanel : TextPosition and TextRotation replaced by TextTransform
    - B_DisplayPanel : DefaultText replaced by Text
    - B_DisplayPanel : DefaultTextSize replaced by TextSize
    - B_DisplayPanel : DefaultTextColor replaced by TextColor

    (Doors)
     - B_BaseAutoDoor : TriggerClass replaced by TriggerClassList

     (Decal)
     - B_CustomDeferedDecal : Decal actor now use default actor orientation and now decal orientation
     
    
## New Materials.
    - MI_FullyWhite

## New Instanced Materials.
    - MI_DevYellow
    - MI_LightGreen
    - MI_Devpurple
    - MI_DevBrown
    - MI_DevPink
    - MI_DevBlue
    - MI_DevBlack
    - MI_DevTriPlanarOrange
    - MI_TriPlanarDevGray
    - MI_DevTriPlanarWhite
    
    (Lights)
    - MI_DevLight_NaturalOrange
    - MI_DevLight_NaturalBlue
    - MI_DevLight_NaturalYellow
    
    (Glass)
    - MI_DevGlassWhite
    - MI_DevGlassMetalBlue
    - MI_DevGlassMetalGreen
    - MI_DevGlassMetalRed
    - MI_DevGlassMetalWhite
    - MI_DevGlassMetalWhiteSoft

## Asset Replace
    - M_DevOrange -> MI_DevOrange
    - M_DevBlack -> MI_DevGray
    - M_DevWhite -> MI_DevWhite
    - MI_DevGlass_b -> MI_DevGlassWhiteSoft

## Asset Name Changes
    - Props_AssetMap -> Overview
    - Blocking_ExempleMap -> Demonstration
    - M_DevBlack -> M_DevGray
    - MI_StainDecalColorBlue -> MI_StainDecalColorSkyBlue
    - SM_Player -> SM_PlayerCharacter
    
    - BP_DisplayPanel -> B_DisplayPanel
    - BP_SimpleArrow -> B_SplineArrow
    - BP_TurnToTheCamera -> B_TurnToCameraComponent
    - BP_FakeCharacter -> B_HumanScaleReference
    - BP_SimpleCameraPreview -> B_SimpleCameraPreview

    (Interactions)
    SM_FlootButtonSupport -> SM_FloorButtonSupport
    
    (StaticDoor)
    - BP_StaticDoor -> B_StaticDoor
    - BP_StaticDoorDouble -> B_StaticDoorDouble

    (AutomaticDoor)
    - BP_BaseAutoDoor -> B_BaseAutoDoor
    - BP_AutoDoor -> B_AutoDoor
    - BP_AutoDoorDouble -> B_AutoDoorDouble
    - BP_AutoLateralDoor -> B_AutoLateralDoor
    - BP_AutoLateralDoorDouble -> B_AutoLateralDoorDouble
    
    (Road)
    - BP_RoadSpeedBump -> B_RoadSpeedBump

    (Decal)
    - BP_CustomDeferedDecal -> B_SimpleBlockingDecal
    - BP_ArrowDecal -> B_ArrowDecal
    - BP_SripeDecal -> B_SripeDecal

    (Material)
    - M_Mirror -> M_DevMirror


## Folder Name Changes
    - Model -> Meshes
    - SmallObject -> Decorations

