# OS-level keymaps

My primary keymaps live in keyboard firmware ([zmk-config](https://github.com/CarsonDavis/zmk-config) for the Corne). This repository holds the OS-level layouts I install so that the laptop's built-in keyboard, and any plain keyboard, type the same way: **Colemak-DH, ANSI, with the angle mod**.

Both layouts below are vendored unmodified from the [Colemak Mod-DH project](https://github.com/ColemakMods/mod-dh) so a fresh machine can be set up without hunting for the right download.

| OS | What to install | Instructions |
|---|---|---|
| macOS | `macOS/Colemak DH.bundle`, pick **Colemak DH ANSI** | [macOS/README.md](macOS/README.md) |
| Windows | `windows/colemak_dh_ansi_us.zip`, run `setup.exe` | [windows/README.md](windows/README.md) |

## Which variant

- **ANSI** is the right one for US keyboards (and every laptop I own). On an ANSI board the Mod-DH layout includes the angle mod: the bottom-left row becomes `x c d v z` and the right side `k h , . /`.
- **ISO** is for UK/European boards with the tall Enter key.
- **Matrix** is for ortholinear or column-staggered boards. The Corne doesn't need an OS layout at all, its firmware already emits Colemak-DH, so leave the OS set to QWERTY for it or just don't plug it into a machine running this layout.

## Known difference from the Corne firmware

The Corne firmware swaps `'` and `;`. These OS layouts keep the vanilla positions. One day the OS layouts should be edited to match.
