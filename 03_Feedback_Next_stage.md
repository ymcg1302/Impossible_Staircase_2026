# CGI-Tools Project 2026

**Ysabel Maria Cartago Garcia** BU 5700252

**16/11/26, 16:07 pm**

## Feedback and Next Steps
* another potential application = move pieces, toggle visibility
* download chess pieces = compare against the revolve first
* extra chessboards as the env = museum like setup
* camera angle and structure are set, now play with the ball bounce and the chess pieces

<div align="center">
  
**Pipeline Adjustment**

(Stage 1) staircase procedural modelling test [Houdini or Maya]

↓
                            
(Stage 2) camera angle fix [Houdini or Maya] → export camera + staircase

↓
                            
(Stage 3) bouncing ball animation test [Maya], revolve method for the chess pieces [Houdini or Maya], or SketchFab

↓
                            
(Stage 4) animation, code, environment setup refinement

↓
                            
(Stage 5) ai toon shader [Arnold Maya] 

↓

(Stage 6) Final render [Maya or Unreal]
</div>

<ins>**Chess Piece 3D Sources**</ins>
* https://sketchfab.com/search?q=chess+pieces&type=models
* https://sketchfab.com/3d-models/chess-kit-94f58cabfc0044acb83c28f5b70c79f9 = favorite = _chosen one_
* https://sketchfab.com/3d-models/3d-chess-ab202418ab7f4266b356e0e22eb23eb6 = good form, high poly
* https://sketchfab.com/3d-models/chess-set-dc104d4f62e34cb5bb948cf80f546cff = good poly level
* https://sketchfab.com/3d-models/chess-pieces-d2d7fec42d0a405d910b3ef751b30f38 = 2nd favorite
* https://sketchfab.com/3d-models/chess-pieces-ee1d62f4f1ec4e939ecc5b561af4d9e1 = high poly
* https://sketchfab.com/3d-models/chess-a115419222b84d698c83964a92fc27e0
* https://sketchfab.com/3d-models/realistic-3d-chess-pieces-blender-fbb81d5dc8854f41b6e2db6673daefb3
* https://sketchfab.com/3d-models/chess-pieces-214e3890c29749d58753c91a03ab6136
* https://sketchfab.com/3d-models/chess-pieces-1a47120c405645f69f46ccada352a4ac
* https://sketchfab.com/3d-models/chess-pieces-b8c92b9848f042c491b1e1605556b580
* https://sketchfab.com/3d-models/chess-pieces-951dca68ae9f4b50a8c1f56a25f4f398

---

### Chess Piece Considerations 

* Removal of the revolve step
* Comparing the different 3D Models:
  
  * Polygon density
  * Scale and design
  * Compatibility for texturing and UV Mapping (if need be)
  * Scene compatibility

Final choice: credit the Artist .... changes to the design of the Queen, faceting even if it is far away, proportion changes to the king = focusing on silhouette and readability

<img width="853" height="511" alt="image" src="https://github.com/user-attachments/assets/31387fb1-3720-4c96-8b35-8a9344094c69" />

<img width="575" height="455" alt="image" src="https://github.com/user-attachments/assets/35703ebb-1aef-47ff-9c08-329bd9be12ef" />

<img width="260" height="322" alt="image" src="https://github.com/user-attachments/assets/ae590b9c-334f-415d-9eec-595f60bc5c05" />

<img width="853" height="509" alt="Screenshot 2026-11-18 140710" src="https://github.com/user-attachments/assets/b91043ab-afc7-4e17-86c4-6d0c0dee8217" />

<img width="379" height="371" alt="image" src="https://github.com/user-attachments/assets/f55c34e8-ace6-48e5-aed9-27e9e8147b09" />

<img width="381" height="375" alt="image" src="https://github.com/user-attachments/assets/871051bf-b766-4fa8-9b47-9e89b131cc24" />

<img width="386" height="404" alt="image" src="https://github.com/user-attachments/assets/8a99a4a6-bf7c-4dfd-9444-30864760b268" />

---

### Texture Considerations
<img width="400" height="464" alt="image" src="https://github.com/user-attachments/assets/c3f603f9-8a01-40f4-868d-c87193411ef1" />

* https://youtu.be/h1ue5qJAjXI?si=ycFKUNQNUZHuXcKt
* https://www.youtube.com/watch?v=UAoAiY8NZIk&t=230s
* https://www.youtube.com/watch?v=mRlP15QV27E
* https://www.youtube.com/watch?v=QXhqnM2r3Qc
* https://help.autodesk.com/view/ARNOL/ENU/?guid=arnold_user_guide_ac_surface_shaders_ac_toon_html
* https://help.autodesk.com/view/ARNOL/ENU/?guid=arnold_core_ac_facing_ratio_html
* https://u.osu.edu/arnoldtoonshaderdocumentation/getting-started/setting-up/
* https://help.autodesk.com/view/MAYAUL/2025/ENU/?guid=arnold_for_maya_am_Arnold_for_Maya_User_Guide_html
* https://leegriggs.com/toon-shader
* https://www.3dart.it/cross-section-using-the-toon-shader-and-clip_geo-shader/
* https://www.3dart.it/how-to-create-robot-toon-shader-in-arnold/
* https://www.3dart.it/toon-hatching-in-maya-and-arnold-tutorial/?utm_source=Pinterest&utm_medium=organic

