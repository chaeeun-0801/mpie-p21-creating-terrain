# Practical 2.2: Enhancing Your Environment with Trees, Grass and a Shelter

In this practical, you’ll build on the terrain you created in the last class. Therefore, if you’ve not completed that practical yet then please do that first. You should also continue to use the Unity project from the last class, which includes all the files you’ll need for today.

In the second lecture, you learned how to add some more advanced features to a terrain in Unity and three approaches for creating indoor scenes. In this practical, you are going to use these new skills to enhance the mountainous environment from the last practical.

By the end of this practical you will:

- Be able to add trees and billboard foliage to a Unity terrain
- Be able to model a simple indoor environment and add it to a Unity scene
- Be able to import props created in Maya into a Unity Scene

## Task 1: Adding Trees and Grass

In the first task, you are going to make the mountainous terrain that you created in the last practical look more realistic by adding some trees and grass.

When adding trees and grass to your scene, you should use the tree and billboard texture assets that are provided in the project. You can find the tree and grass assets at the following locations in the project browser once this package has been imported:

- Trees: Standard Assets/Environment/SpeedTree
- Grass: Standard Assets/Environment/TerrainAssets/BillboardTextures

To add trees:

1. In your Hierarchy tab, select the terrain you have created. The Inspector tab will now show the terrain properties.
2. In the Inspector, go to the Terrain component, and click on the tree Paint Trees icon (the tree icon next to the brush icon).
3. In the Paint Trees tool, click on Edit Trees > Add Tree.
4. By default, no tree prefab is assigned. Select the tree prefab by clicking on the circle next to the prefab name (None (Game Object) as of now)
5. This will open a list of prefabs. Find a tree you like and double click on it.
6. Click on Add
7. To put trees on the terrain, select the tree you have added (the image showing the tree in the Paint Trees menu) and paint (click on) the terrain with them.

If you want to delete trees, hold the Shift key and paint on the terrain again. If you hold Ctrl instead of Shift, only trees of the type you have selected will be deleted.

Now you can experiment with the trees settings. Change the brush size, tree density, and other random settings (height, width, rotation) to get the setup you like. You may also want to try the Mass Place Trees, which will populate the whole terrain with the amount of trees you specify.

Adding grass is quite similar to adding trees or painting the terrain with textures:

1. In your Hierarchy tab, select the terrain you have created. The Inspector tab will now show the terrain properties.
2. In the Inspector, go to the Terrain component, and click on the tree Paint Details icon (the flower icon next to the tree icon).
3. Go to Edit Details > Add Grass Texture.
4. By default, no grass prefab is assigned. Select the grass prefab by clicking on the circle next to the Detail Texture name (None (Texture 2D) as of now)
5. This will open a list of prefabs. Find a texture for the grass you like and double click on it.
6. Click on Add
7. To put grass on the terrain, select the grass you have added (the image showing the grass in the Details section of the Paint Details menu) and paint (click on) the terrain with them.

Again try to experiment with the grass paint settings. You may want to change the brush type, size, opacity. 

If the terrain that you created in the last practical is very large, you may wish to save time by only adding trees and grass to the valley route that the player will follow to reach the top of the mountain.

Again, you may want to add an FPSController (included in the Standard Assets package) to your Scene, like we did in previous practicals, so that you can explore the world you are creating.

## Task 2: Adding a Shelter

In this task you are going to add a small shelter (e.g. a small wooden hut) on top of the high mountain that the path leads to. You can choose to create and texture this shelter in the 3D modelling package Maya and then import it into your Unity scene, using the polygon modelling approach that you were taught about last year.

I often find it helps to work to a reference image when 3D modelling. You may wish to base your shack model on the following reference image, but you can choose to base it on another if you wish:

![A hut with a single door and window](https://github.com/UoY-IM-MPIE/mpie-p22-enhanced-terrain/blob/main/Instructions/hut.JPG)

## Task 3: Adding Props

To improve your environment, add some props along the valley, and in and around your shelter. Consider choosing props that tell the player who lives in the hut and why they might be living on top of the mountain.

Try sourcing props for your environment by:

- Creating them yourself in Maya
- Looking in Unity’s standard assets packages
- Downloading them from an online resource (e.g. Turbo Squid, Asset Store)

## Task 4: Adding a Cave on the Path

To finish things off, try adding a cave along the path that the user can walk into. The "Paint Holes" tool in the terrain editor will allow you to make an opening in your terrain. However, you'll notice that the edges of this opening are jagged, especically if the opening is on a steep face, and when you walk into it you fall down forever!

For this final task, think about how you might solve these issues by applying a combination of the skills you've learned for terrain creation with those you've learned for making indoor scenes. Can you make a more aesthetically pleasing cave entrance, and then a cave area that you can walk into and explore?

## Optional Extensions

If you have completed task 3, then you should consider attempting the following tasks:

- Create your own billboard grass texture in Photoshop, and import it into Unity for use in the terrain editor’s paint details tool. Tip: you will need to create a texture with a transparent background. https://www.youtube.com/watch?v=tfuzAwXmZOk
- Use Unity’s tree creator to make your own custom tree model. You can find more information on using the tree creator: https://docs.unity3d.com/2018.4/Documentation/Manual/tree-FirstTree.html 
- Explore how the ‘Add Detail Mesh’ option in the paint details tool can be used to add small rocks on and around the path up to the top of the highest mountain. See here for more details: https://docs.unity3d.com/2018.4/Documentation/Manual/terrain-Grass.html
- Create a lake in your terrain by adding a water game object to your scene. You can find a selection of prefabs for creating water in Standard Assets/Environment/Water in the project
- If you're interested in exploring terrain and environment creation further then I recommend working through this YouTube tutorial on creating an "African Environment". You'll need to install additional assets but they are all free: : https://www.youtube.com/watch?v=Sz3sNXouvCs
- In this interview, Jane Ng who was an artist on Firewatch talks about how they used Unity to create the game and the issues that they had creating the environment: https://www.youtube.com/watch?v=ZYnS3kKTcGg

