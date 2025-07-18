# Minecraft Inventory Editor
A simple visual inventory editor for latest Minecraft Java edition versions - free and open source.

![Starting Page](https://raw.githubusercontent.com/corv1njano/minecraft-iventory-editor/refs/heads/main/docs/img/start041.png)

## World Selection
Select a Minecraft Java world from folder or directly from the saves directory.

![World Selection Menu](https://raw.githubusercontent.com/corv1njano/minecraft-iventory-editor/refs/heads/main/docs/img/select372.png)

## Errors
Common errors and how to fix them:

**Inavlid World data**: Some Minecraft worlds that you try to open are invalid. This may because the level.dat file is missing, there are no player entries or the world file itself is too old.

![Inavlid Data Error](https://raw.githubusercontent.com/corv1njano/minecraft-iventory-editor/refs/heads/main/docs/img/invalid990.png)

**No Worlds found**: The program will automatically search for Minecraft worlds under `C:\Users\<name>\AppData\Roaming\.minecraft\saves`. If the folder is empty or doesn't exist, there will be the following message.

![No Worlds found](https://raw.githubusercontent.com/corv1njano/minecraft-iventory-editor/refs/heads/main/docs/img/missing162.png)

## Technical Info
- written in C#
- used libraries: NBTLib (own library for parsing NBT data), corvLib (own library with helper methods)
