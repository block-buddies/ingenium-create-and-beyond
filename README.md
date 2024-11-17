![Ingenium: Create & Beyond](docs/title.png)

`Ingenium: Create & Beyond` is a modpack centered around the mod `Create` and it's various addons, enhanced with many 
quality of life mods and some additional gameplay mechanics while still keeping a mostly vanilla+ experience.

<details> 
  <summary>What's about to come?</summary>
  <p>
    <ul>
        <li>Questbook</li>
    </ul>
    </p>
</details>

# Installation
> The installation guide needs more refinement, so there might be additional steps necessary or you might have to do your own research

> This modpack is distributed using the packwiz format, so you should be able to install this modpack with PrismLauncher, ATLauncher, MultiMC, etc.
> However the official method is through modrinth.

Follow [Pack Installation using packwiz-installer](https://packwiz.infra.link/tutorials/installing/packwiz-installer/).
Although the guide says it can be used with MultiMC/ATLauncher, Modrinth works too. Use the following pre launch task
```
java -jar packwiz-installer-bootstrap.jar -g -s both https://raw.githubusercontent.com/block-buddies/ingenium-create-and-beyond/refs/heads/main/pack.toml
```

# Development

1. Make Changes
2. Update version
3. commit
4. push
5. build

## Commands
```shell
packwiz serve
packwiz mr install <name>
packwiz remove <name>
packwiz mr export -o dist/ingenium.mrpack
packwiz refresh
packwiz update -a
packwiz pin <name>
```
