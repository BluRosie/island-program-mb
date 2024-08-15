This repository builds one of the Animal Crossing Multiboot images which comes compressed within the GameCube Animal Crossing entry. This is done to assist in [the decompilation of the overall game](https://github.com/Prakxo/ac-decomp/).

Requires agbcc.  Need to install it like the Pokémon Decompilations, i.e.:

```
git clone https://github.com/pret/agbcc.git
cd agbcc
./build.sh
./install.sh path/to/island_loader_mb
```

It builds the following image:

    19066f9b168dc10581206faaf32b3a1e72e584b7  island-program-mb.gba
