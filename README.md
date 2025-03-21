# dTerra Base

A collection of base terrains, created for use in Enfusion/Arma: Reforger, masks are freely available to use and modify, the source to generate these masks will not be provided; if you wish to generate different masks, tools such as World Machine, GeoGen and the entirely free option blender exist. I am unable to provide any support for the height maps, I'm mostly fedup of playing on Landlocked maps and constantly seeing the ocean below the map when flying.

All terrains were created with a 2048x2048 size and default cell settings (for screenshots)
All height maps are 2048x2048, and approximately 1/m per pixel; 
Most masks should be 4033x4033.

> [!NOTE]
> A workshop version is available to use as a dependency, you will however be unable to alter the terrain or make any changes.
> this is intended for my own use, as I do plan use these bases myself officially.
> [Here](https://reforger.armaplatform.com/workshop/64E0738C140B94D9-dTerraBase)

> [!IMPORTANT]  
> If you intend to use any of the v2 heightmaps, ensure you interpolate the range; I'm not entirely sure why the heightmaps import perfectly fine in all my other software and own mask creation tool at a 0-1 range, but for Enfusion it turns them into a hellish landscape.
>
> Alternatively, using `0.00225` as your height scale will provide the /best/ result based on the heightmap(s) provided; It is however recommended you leave this at default.
>
> The masks have been generated based on resampling the imported height map; as such the grass and shore masks will most likely be below `Y: 0` and will need to be manually adjusted, or painted. You can do this by exporting Enfusion's shore preview as a template.

### Satmaps
If you're looking to generate a satmap, using the materials from Enfusion or custom terrain materials; I recommend using [TilW's Seamless Satmap Tool](https://github.com/Til-Weimann/tilw-terrain-tools)

### Masks
As all the height maps provided are intended to be used within Enfusion/Arma: Reforger, the providede masks are directly exported from Enfusion after being imported from source, the source of these are not provided.. If you wish to modify the masks. You can do so within Enfusion itself, or an applicable application you're familiar with.

### Support

I won't provide support for any of the heightmaps available, the usage of them is solely your responsibility; If you encounter an issue related to Enfusion or any applicable software you decide to use, please use the Arma/BI discord; or the applicable support option for the software you're using.

Feel free to create issues related to missing, incomplete terrains.. If a folder does not have any supporting masks or is missing the satmap, it is most likely they are complete to a standard I'm happy with (less likely, I forgot).

# Common Issue(s)

### Help, the height is wrong!
Use the "resample" option when importing the heightmap, none of the heightmaps should require remapping beyond -15 or 200; your judgement for what is "too high" or "too low" is yours to make.

### Help, the satmap is too bright!
Disable "linear color space" when importing the Satellite Map.

# Enfusion Previews

## "Sandgamau Isle"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9e60a85d956d67a5e2a0dc8232011e5d2b04d790/assets/SandgamauIsle_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9e60a85d956d67a5e2a0dc8232011e5d2b04d790/assets/SandgamauIsle_CloseEnfusion.png)

## "Brishkesh"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/ced53ee0a2fe84c40dd6a6ecd5757f8c70e6b565/assets/Brishkesh_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/ced53ee0a2fe84c40dd6a6ecd5757f8c70e6b565/assets/Brishkesh_CloseEnfusion.png)

# "Danisnk Island"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/ced53ee0a2fe84c40dd6a6ecd5757f8c70e6b565/assets/DanisnkIsland_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/ced53ee0a2fe84c40dd6a6ecd5757f8c70e6b565/assets/DanisnkIsland_CloseEnfusion.png)

# "Marau Island"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/fe4d53f57aadcb0c9a1e7339d21d0d09fc14c917/assets/MarauIsland_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/fe4d53f57aadcb0c9a1e7339d21d0d09fc14c917/assets/MarauIsland_CloseEnfusion.png)

# "Port Regai"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/71b332a04215961be08621fdc31f2d704801cf3e/assets/PortRegai_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/71b332a04215961be08621fdc31f2d704801cf3e/assets/PortRegai_CloseEnfusion.png)

# "Sanau Hook"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/3f2148a81f9d582fe8effb6f3d919e7b43898492/assets/SanauHook_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/3f2148a81f9d582fe8effb6f3d919e7b43898492/assets/SanauHook_CloseEnfusion.png)

# "Heavens Peak"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9accc7a29f116f166eec8325a4b2bb8d7aa60d24/assets/HeavensPeak_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9accc7a29f116f166eec8325a4b2bb8d7aa60d24/assets/HeavensPeak_CloseEnfusion.png)

# "Three Valleys"
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9accc7a29f116f166eec8325a4b2bb8d7aa60d24/assets/ThreeValleys_LongEnfusion.png)
![Screenshot](https://github.com/DR0IDISTOXIC/dTerraBase/blob/9accc7a29f116f166eec8325a4b2bb8d7aa60d24/assets/ThreeValleys_CloseEnfusion.png)
