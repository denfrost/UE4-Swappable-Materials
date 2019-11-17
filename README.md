Hello,

I work in preproduction for film using UE4 and have a trove of useful tools that I will slowly be sharing as they are ready to see the light of day. First up are a few dozen material shaders (with more to come) and a library of 1000+ PBR materials built specifically for those shaders.



## Part 1:

* A set of a few dozen material shaders that use the same parameter names so you can switch any material you make with them to another material and it will keep your textures, uv mapping and any other tweaks you made. Almost everything uses material functions, so if you want to add something novel to all of the materials that use base color, you only have to edit one file and it will propagate.
* The materials go from the basic solid material shader with UV transforms, color tints and the like, to more advanced materials that automatically add puddles, snow and ice to an object.
* Over the next few weeks I am going to be making demo materials for the shaders, tutorials and expanding the list as I have another 20 more advanced shaders (rain, terrain blending, etc.) that need converted to this system. I would love to hear suggestions for other shaders to make.



## Part 2:

* A material blutility to simplify creating materials from textures, and converting rgh met ao / packed maps into ORM maps. I need to write some documentation for this tool, but until then the curious can find it named material generator in the third party folder





## Part 3:
* 1000+ pbr materials scrounged from a few CC0 websites.
* You can download them at:http://www.mediafire.com/folder/qikyr0frd1j9k/CC0%20Materials
* To find the source files and donate to the authors of the textures: https://drive.google.com/open?id=1i8vLBtMDIwJYrpFycgAHBZV1quqaTh7iZB9vvbCohJs
* All materials are 4k to leverage mip maps and provide high fidelity
* Roughness, metallic, gloss, and ambient occlusion maps have been baked into ORM (AO, roughness, metallic) maps
* All textures have been set to an optimized compression setting. No alpha for base colors, masks for ORM, etc.
* All materials follow a naming convention that gives credit to the original author. See the spreadsheet in the google drive for short name equivalents and please go support these wonderful websites.
* Most of the materials are set to use only base color, normal and ORM by default, however, if there were any other textures, such as displacement, provided by the original source, they are included in the same folder as the material.
* The best way to use this library is to migrate only what you need into your project
* Note: I do not include any patreon textures or the source images in my downloads. Please support the websites that are giving us this wonderful resource.
* I tend to update my library of materials about once every 2 months



 
 

 
To see what I am working on:
https://trello.com/b/69Ody2Ui/ue4-vr-film-scouting-tools-roadmap

To support me in my endeavors:
https://www.buymeacoffee.com/pizWD4o
