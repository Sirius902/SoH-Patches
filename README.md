# SoH Patches

Patches for [Ship of Harkinian](https://github.com/HarbourMasters/Shipwright).

## Usage

To apply these patches, clone [Ship of Harkinian](https://github.com/HarbourMasters/Shipwright) using git and run the following command
in the root directory of the repository where `<path>` is the file path to the patch file.

```
git apply --reject --whitespace=fix <path>
```

## Patches

| Name               | Description                                                                                                            |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| `hookable-reticle` | Adds a reticle to indicate a surface pointed to with the hookshot is hookable, similar to OoT 3D.                      |
| `n64-weirdshot`    | Makes [weirdshots](https://www.zeldaspeedruns.com/oot/tech/weirdshot) behave the same as on N64 and Virtual Console.   |
| `oob-bombchu-fix`  | Makes Bombchu explosions out of bounds not crash the game and instead explode twice, similarly to GameCube and Wii VC. |
| `super-hookshot`   | Makes the hookshot extend farther and move faster, also makes every surface hookable.                                  |
