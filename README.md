# KindleTweaks Repo

> [!NOTE]
> The main external repository for Kindle homebrew.

> [!IMPORTANT]
> **Licensing Notice**:
> All package manager logic, JSON metadata, webpage source and shell scripts in this repository are licensed under the GPLv3 License.
> Distributed software packages, binaries contained within Git LFS are subject to their own respective upstream licenses.
> Attribution is provided in each package (README), the repository manifest, and documented in the list below. Source links and a full LICENSE copy are included in each package (README), and documented in the list below.

## Installation

Please download `kt_repo.sh` from releases and copy it to the Kindle's `documents` folder, then run it as [scriptlet](https://kindlemodding.org/jailbreaking/whats-next/installing-homebrew.html#Scriptlets).

Alternatively, run the following command:

`/var/local/kmc/bin/kpm add-repo https://kindletweaks.github.io/Repo/manifest.json`

## Packages

All packages are made by developers part of the KindleTweaks organisation, ensuring they are maintained and safe-to-use. Run `;kpm update` before installation.

- **KUALA**: Homebrew Launcher for Kindle, Based on the Legacy KUAL.
    - Command: `;kpm install kuala`
    - Author: [Kaspar](https://github.com/kasparcode/)
    - Original Source: [Github](https://github.com/kasparcode/kuala/)
    - License: CC0
    - Supports: KindleHF

- **Gargoyle**: IF Reader Compiled for Kindle.
    - Command: `;kpm install gargoyle`
    - Author: [Barna](https://github.com/kbarni/)
    - Original Source: [Github](https://github.com/kbarni/garglk)
    - Licenses: GPLv2, Simplified 2-Clause BSD License, Artistic License 2.0, MIT, SIL Open Font License (OFL) v1.1, Liberation License.
    - Supports: KindleHF

- **KinAMP**: Music and Internet Radio Player for Kindle and KOReader.
    - Command: `;kpm install kinamp`
    - Author: [Barna](https://github.com/kbarni/)
    - Original Source: [Github](https://github.com/kbarni/KinAMP)
    - Licenses: GPLv3
    - Supports: KindleHF, KindlePW2

- **LARK**: Libre Audiobook Reader for Kindle.
    - Command: `;kpm install larkplayer`
    - Author: [Barna](https://github.com/kbarni/)
    - Original Source: [Github](https://github.com/kbarni/Larkplayer)
    - Licenses: GPLv3
    - Supports: KindleHF, KindlePW2

- **RAnki**: Anki Reviewer for Kindle.
    - Command: `;kpm install ranki`
    - Author: [CrazyElectron](https://github.com/crazy-electron/)
    - Original Source: [Github](https://github.com/crazy-electron/ranki)
    - Licenses: GPLv3
    - Supports: KindleHF, KindlePW2