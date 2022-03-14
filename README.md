# Filesystem folder structure
Filesystem folder structure is a cross-platform, and multi-usage folder structure, and file naming convention for portable user directories, designed to help you in efficient file management. It gives a solid base for directory organization, that's open for extension, without introducing any operation system, or usage assumptions. :file_folder:

Filesystem folder structure is an extension of [project-folder-structure](https://github.com/martonlente/project-folder-structure), a folder structure, and file naming convention for design, and web development projects.

Filesystem folder structure is under construction. :construction:

## Usage
Use this folder structure layout.

```
.
├── Archive
│   └── 2101-project-name
├── Backup
│   ├── desktop
│   └── phone
├── Books
├── Desktop
├── Documents
│   ├── business
│   └── personal
├── Downloads
├── Music
├── Pictures
│   └── 2201-album-name
├── Projects
│   └── 2201-project-name
├── Public
├── Resources
│   ├── creative
│   ├── doc
│   ├── dev
│   ├── fonts
│   └── viz
├── Templates
└── Videos
```

### Archive
---
Store archive project directories in the `Archive` folder, in the according sub-folder. Name the archive directory accordingly to user language, for example `Archívum` for Hungarian users.  Move inactive project folders older than a year here, for example `2101-project-name` . Don't change files, or don't create new files in these folders.

### Backup
---
Store backup directories in the `Backup` folder, in the according sub-folder. Name the backup directory accordingly to user language, for example `Biztonsági mentés` for Hungarian users.

#### Desktop
Store desktop backup files in the `desktop` folder, for example configuration, and disk image files.

#### Phone
Store phone backup files in the `phone` folder, for example data, and message files.

### Books
---
Store book, and learning files in the `Books` folder, in the according sub-folder. Name the books directory accordingly to user language, for example `Könyvek` for Hungarian users.

### Desktop
---
Store files in the `Desktop` user folder, if needed. Name the desktop directory accordingly to user language, for example `Asztal` for Hungarian users. Link default desktop user folder to this folder.

### Documents
---
Store document directories in the `Documents` user folder, in the according sub-folder. Name the documents directory accordingly to user language, for example `Dokumentumok` for Hungarian users. Link default documents user folder to this folder.

#### Business
Store business document files in the `business` folder, for example presentation, spreadsheet, word processor, and other text document files.

#### Personal
Store personal document files in the `personal` folder, for example presentation, spreadsheet, word processor, and other text document files.

### Downloads
---
Store files in the `Downloads` user folder, if needed. Name the downloads directory accordingly to user language, for example `Letöltések` for Hungarian users. Link default downloads user folder to this folder.

### Music
---
Store music files in the `Music` user folder. Name the music directory accordingly to user language, for example `Zenék` for Hungarian users. Link default music user folder to this folder.

### Pictures
---
Store picture directories in the `Pictures` user folder, in the according sub-folder. Name the pictures directory accordingly to user language, for example `Képek` for Hungarian users. Link default pictures user folder to this folder. Organize sub-folders by date, for example store files saved in January 2021 in sub-folder `2101-album-name`.

### Projects
---
Store project directories in the `Projects` folder, in the according sub-folder. Name the projects directory accordingly to user language, for example `Projektek` for Hungarian users. Organize sub-folders by date, for example store files for project started in January 2022 in sub-folder `2201-project-name`.

Use [project-folder-structure](https://github.com/martonlente/project-folder-structure), a folder structure, and file naming convention for design, and web development projects to organize your individual project folders.

### Public
---
Store files in the `Public` user folder, if needed. Name the public directory accordingly to user language, for example `Nyilvános` for Hungarian users. Link default public user folder to this folder.

### Resources
Store resource files (third-party assets you use in your own projects) in the `Resources` folder, in the according sub-folder. Name the resources directory accordingly to user language, for example `Források` for Hungarian users.

#### Creative
Store creative resource files in the `creative` folder, for example design, photo, and publication files.

#### Documents
Store document resource files in the `doc` folder, for example presentation, spreadsheet, word processor, and other text document files.

#### Development
Store development resource files in the `dev` folder.

#### Fonts
Store font resource files in the `fonts` folder. Setup your font manager software to watch this folder.

#### Visualization
Store visualization resource files in the `viz` folder, for example 3d model, material, and other drawing files.

### Templates
---
Store files in the `Templates` user folder, if needed. Name the desktop directory accordingly to user language, for example `Sablonok` for Hungarian users. Link default templates user folder to this folder.

### Videos
---
Store video files in the `Videos` user folder. Name the videos directory accordingly to user language, for example `Videók` for Hungarian users. Link default videos user folder to this folder.

Create sub-folders, if needed, to group related files.

## Contributing
Pull requests are not yet welcome. For support requests, please open an issue first to discuss what you would like to change.

## License
[MIT](https://github.com/martonlente/filesystem-folder-structure/blob/main/LICENSE)
