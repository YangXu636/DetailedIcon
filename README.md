# DetailedIcon

一个让雨世界的图标更细致的轻量mod

[中文](README.md) | [English](README_en.md)

## 如何兼容你的mod猫

每只猫都可以加载两张资源：用于替换Kill_Slugcat和Multiplayer_Death

兼容方法（针对SlugBase单mod单猫）：资源命名分别为 "Kill_Slugcat_{MOD_ID}" 和 "Multiplayer_Death_{MOD_ID}"

更普遍的一般形式："Kill_Slugcat_{你的猫的id}" 和 "Multiplayer_Death_{你的猫的id}"

用Futile.atlasManager.LoadAtlas加载资源后即可正常显示。

注：如果不知道自己的猫的id的话，可以在控制台输出player.slugcatStats.name.value查看id（这个输出的内容就是用来替换上文中“你的猫的id”/“MOD_ID”的）

注：此外，控制台输出中“Texture state”后的两个字符串正是您需要添加的两个纹理的名称。

## 特别鸣谢

Owl ：提供了在下游类中找到玩家对应的Player实例的思路与方法

## 联系方式

Outlook：XuYangJerry@outlook.com