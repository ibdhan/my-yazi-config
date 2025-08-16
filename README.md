# Step by step Install & Setup yazi on Windows 11

## prerequisites
- Git

## Installation
- Install yazi
```
winget install sxyazi.yazi
```

- Install optional 
```
winget install Gyan.FFmpeg 7zip.7zip jqlang.jq sharkdp.fd BurntSushi.ripgrep.MSVC junegunn.fzf ajeetdsouza.zoxide ImageMagick.ImageMagick
```

## Setup windows variable
- Locate `file.exe` that comes with git, usually in `C:\Program Files\Git\usr\bin\file.exe`.
- run this command in powersheell
```
setx YAZI_FILE_ONE "C:\Program Files\Git\usr\bin\file.exe"
```
