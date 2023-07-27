ccMan is a voxelised version of the [BodyParts3D](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/desc.html) library at cubic centimeter resolution.

This repository is subject to the BodyParts3D [Licence](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html)

![ccMan](https://github.com/HenryHoward/ccman/blob/main/ccman.png)

"arrays/" contains JSON documents (each named with a fileID) each containing and origin and a 3D array of booleans representing the shape of that bodypart

"coords/" contains JSON documents (each named with a fileID) each containing a list of coordinates representing the shape of that bodypart

ccManIds.json contains a dictionary relating fileIDs with human-readable bodypart names, as well as corresponding Foundational Model of Anatomy IDs
