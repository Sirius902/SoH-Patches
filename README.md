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
