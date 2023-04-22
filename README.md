# A Shigure Kira HI3 Blender Shader Preset

A Shigure Kira Blender Shader Preset for a dead game.

Developed on Blender 3.2, and modified upon [崩坏三渲染预设——格蕾修丨小二今天吃啥啊丨爱发电 (afdian.net)](https://afdian.net/p/7bde3106e7cf11ecab9452540025c377), making it suitable for datamined `.fbx` models instead of `.pmx` MMD ones.

![1681037911173](image/README/1681037911173.png)

![1681127851727](image/README/1681127851727.png)

### Known Issues

- The color of edges of the body skin cannot be seperated from the clothes. (tried festivity's Genshin outline shader, still need some working to make it matched with the Honkai's LightMap)
- ~~Some edges are broken around the hair.~~ Now it's slightly fixed (not completely kek)
- ~~Haven't made a seperate shader for the metal accessories yet.~~ (Done!)
- ~~The specular light of her eyes and the highlight for her hair has not been made yet.~~ (Tried my best, should work now)
- The armatures for the shadow of her hair, face, upper body, and lower body can only be seperatly rotated for now.
- ~~The translucent effect of Seele's flower on the head is not accomplished yet.~~ (See the NewFace one)

### To Do (or Maybe Not If I Don't Have Time, Energy, and Mood)

- ~~Fix the edges.~~
- Re-organize the nodetree since it's so messy.
- ~~Make a shader for the metal part.~~
- ~~Fix the specular and highlight.~~

### Acknowledgement

Thank the following:

- [小二今天吃啥啊的所有作品集 | 爱发电 (afdian.net)](https://afdian.net/a/xiaoer/album) for their remarkable Genshin blender presets. (Too bad that no one cares about a dead game).
- [festivize/Blender-miHoYo-Shaders: Shaders for Blender attempting to replicate the shading of games developed by miHoYo. These are for datamined assets, not custom-made ones nor the MMD variants. (github.com)](https://github.com/festivize/Blender-miHoYo-Shaders) for their pioneer works in the opensourced Genshin shaders, though I have not used their works and hope that they can release the shader for a certain dead game in the future.
- [blender用虚拟灯光向量做出崩坏三展示柜阴影随相机视角变化效果](https://www.bilibili.com/video/BV1ua4y1M7v2) whose shader is even better but I have not taken a look yet.
- [Blender还原原神嘴部描边细节](https://www.bilibili.com/video/BV15Y411A7LB), [关于实体化修改器描边断线问题的修正方法](https://www.bilibili.com/video/BV1iP4y1M7dm) for methods to fix the edges, though not very ideal.
- [【blender材质教程】动漫角色材质进阶提升课 闪亮大眼睛材质教学 mmd通用进阶教程](https://www.bilibili.com/video/BV16b4y1s7UU) for the shading method of eyes, though turned out to be useless.
