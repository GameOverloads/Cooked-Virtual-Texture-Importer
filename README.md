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
- Pick JSON To Use From FModel ( Must Match PNG Name )
- Pick PNG To Use From FModel ( Must Match JSON Name )
- Optionally Change Stack Direction ( For Now, Top To Bottom Is What FModel Exports VT Images As )
- Hit Import

* Intermediary Textures Are Created At PNG Path
* Virtual Textures Are Created With A Path From JSON Data ( You Can Move Textures After Creation & Delete Folders )

Python Packages Used
- PIL / Pillow ( Comes With Plugin )

If you wish to support the work I do and allow me to keep making these things for free, then donate to my Ko-Fi if you so wish, it is appreciated:
https://ko-fi.com/gamebreaker
