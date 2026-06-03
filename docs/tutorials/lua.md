# WIP .lua files

Explain how these work, how to edit them and all.

Function	Parameters	Description 
CreateCAttack	()	Creates an Object of Type CAttack
InitAttack1	(WEAPONTYPE, ATTACKATTRIB, int, int, int)	Initialize Attack with the Type, attributes and some values
InitAttack2	(RayTrace, int, int, bool)	Continue the Initialization of the  Attack with RayTrace two integers and a bool flag.
SetCollisionRangeAdjust	(bool, bool)	Set if the collision range should adjust
SetGhostCalcCollisionRange	(bool)	Set if ghost calculates collision range
AddPushCondition	(int, int, int)	Add a push condition with XYZ
AddBlowCondition	(int, int)	add a blow condition with XY
SetCameraShakeEnable	(bool, bool, int)	Set if camera shake is enabled
SetCameraShakeFactor1	(int, int, int)	??
SetCameraShakeFactor2	(int, int, int, int)	??
SetCritical	(double, int)	Set the critical hit rate and damage
SetCheckBodyPartsByThickray	(bool)	??
SetConsumeAmmo	(int)	Set how much ammo the single attack consumes
SetCameraShakeRandomDir	(bool)	Set if the camera shakes in random directions
SetPiercingReduceRate	(int)	Set piercing rate
SetCameraShakeWhenSuccess	(bool)	Set if the camera shakes when the hit connects
SetPlaySound	(bool)	Set if it plays the sound
SetFullCharge	(bool)	Set if the attack counts as fully charged
SetCameraShakeReiteration	(bool)	??
SetAttackSuccessCondition	(CONDITION_ACTOR)	Set which condition counts as an attack success
SetDistanceDamageLength	(int)	Set the distance length of the damage
SetDamageApplyType	(Int)	
SetGhostCalcCollisionRange	(bool)	
SetCollisionRangeAdjust	(bool, bool)	