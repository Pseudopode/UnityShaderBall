# UnityShaderBall
3D model shaderball (CC0 licensed) and a demo Unity 2017.X project (MIT licensed)

The 3D model is an attempt to recreate the one that can be seen is scientific papers (like this one - Figure 3, page 5: http://old.cescg.org/CESCG-2010/papers/ElekOskar.pdf)

The ball was modeled in Blender. Starting from a cube, subdivision modifiers are iteratively added.
A ring selection is applied on all axis to model the crease. After the 6 creases are set, the model is further subdivided to be smoothed.

The UV unwrap should be clean, and an AO map (baked in Blender) is also provided.

The ball is provided in various formats (3D, OBJ, DAE, FBX), and the original Blender file is in the repository.

The associated project is done in Unity 2017.3.1f1, but should be compatible with all the 2017.X/2018 branch (and should be also retro-compatible with the 5.X branch).

The camera and the angles are roughly set to match the paper.

All ameliorations to both of them are welcomed.
