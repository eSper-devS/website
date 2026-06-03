# WIP Animations

3 types of “Animations” are used in S4.
Additive animations
Looped animations
Active animations

These are terms I came up with but describe what the different types are a bit better.

Additive animations are those edited in the scn file. They add to the existing animations, by not overwriting. They don't modify single parts but the whole object. They can modify a lot, like translation (location), rotation and scaling. They also have the ability to be placed as keyframes, however all keyframes are automatically set as linear and it's not possible to have them be bezier curved.

Looped animations are animations set by the mesh / texture itself. They are triggered by something, unless it's something like the Sigmablade’s transformed state. They loop over time until destroyed, disabled, hidden or something else happens.

Active animations, are animations triggered by actions. Like locomotion (movement -> WASD, jumping, etc), shooting, attacking or other things. They are the hardest ones to edit, as they are often in .seq files or their .scn files have dozens of model data in need of extracting.

What do you need to know about Transforms?

Transforms are structures of different vector3.
Location
X
Y
Z
Rotation
X -> Roll
Y -> Pitch
Z -> Yaw
Scaling
X
Y
Z

Transforms are relative.
Yaw -> turn around
