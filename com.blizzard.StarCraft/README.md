# StarCraft
The Ultimate Real-time Strategy Game

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | N/A      | N/A  |       |
| 64bit | NeedsTest      | NeedsTest  | NeedsTest |

## Build & Install
### Repo
#### 32bit

    flatpak-builder --arch=i386 --force-clean builds --repo=winepak com.blizzard.StarCraft.yml
    flatpak --user install winepak com.blizzard.StarCraft

#### 64bit

    flatpak-builder --arch=x86_64 --force-clean builds --repo=winepak com.blizzard.StarCraft.yml
    flatpak --user install winepak com.blizzard.StarCraft

### Direct
#### 32bit

    flatpak-builder --user --arch=i386 --force-clean --install builds com.blizzard.StarCraft.yml

#### 64bit

    flatpak-builder --user --arch=x86_64 --force-clean --install builds com.blizzard.StarCraft.yml

## Run

    flatpak run com.blizzard.StarCraft

