# Cooked-Virtual-Texture-Importer
An Unreal Engine 5.5 Plugin For Importing Cooked Virtual Textures ( From FModel Primarily )

This is primarily made due to FModel's current issues with Virtual Textures, but even when fixed, this can be adapted later for creating Virtual Textures easily in Unreal Engine from Atlased Maps.

To Install
- Inside Unreal 5.5 Project, Create Plugins Folder ( If Needed )
- Save ZIP To Plugins Folder
- Extract ZIP Contents To Plugins Folder
- Load Up Unreal 5.5 Project

To Use
- Tools > Cooked VT Importer

// Single Import
- Pick JSON To Use From FModel ( Must Match PNG Name )
- Pick PNG To Use From FModel ( Must Match JSON Name )

// Mass Import
- Pick Folder To Use From FModel ( Must Have Texture JSON & PNG Both For Import To Work )

// Universal
- Optionally Change Stack Direction ( For Now, Top To Bottom Is What FModel Exports VT Images As )
- Optionally Change Skip Existing ( Check - Skip Existing UE File , No Check - Overwrite All UE Files )

- Hit Import

* Intermediary Textures Are Created At PNG Path
* Virtual Textures Are Created With A Path From JSON Data ( You Can Move Textures After Creation & Delete Folders )

Python Packages Used
- PIL / Pillow ( Comes With Plugin )

If you wish to support the work I do and allow me to keep making these things for free, then donate to my Ko-Fi if you so wish, it is appreciated:
https://ko-fi.com/gamebreaker

<img width="1454" height="774" alt="image" src="https://raw.githubusercontent.com/GameOverloads/Cooked-Virtual-Texture-Importer/refs/heads/main/CookedVTImporter_Window.png" />
