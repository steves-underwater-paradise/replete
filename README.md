![Replete icon](docs/assets/icon/icon_128x128.png)

# Replete

Minecraft resource pack that focuses on accuracy in designs and attention to detail.  
Included in the [Venture](https://github.com/steves-underwater-paradise/venture) modpack.

## Compatibility

- PBR ([LabPBR format](https://shaderlabs.org/wiki/LabPBR_Material_Standard)): Some textures (10% complete)
- Connected textures ([OptiFine format](https://optifine.readthedocs.io/ctm.html)): Some textures
  - [Continuity](https://modrinth.com/mod/continuity)
  - [OptiFine](https://optifine.net)
  - See also [OptiFine Alternatives](https://optifine.alternatives.lambdaurora.dev)
- [Particle Rain](https://modrinth.com/mod/particle-rain): Some textures (50% complete)
- [Big Globe](https://modrinth.com/mod/big-globe): Some textures (1% complete)
- [Regions Unexplored](https://modrinth.com/mod/regions-unexplored): Some textures (1% complete)
- [Twigs](https://modrinth.com/mod/twigs): Some textures (1% complete)
- [Universal Ores](https://modrinth.com/mod/universal_ores): Some textures (1% complete)

## Incompatibilities

[Create an issue](https://github.com/steves-underwater-paradise/replete/issues/new) on the issue tracker if you've found a mod that doesn't have resource pack textures/models!

## Download

[![GitHub](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/cozy/available/github_vector.svg)](https://github.com/steves-underwater-paradise/replete)
[![Modrinth](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/cozy/available/modrinth_vector.svg)](https://modrinth.com/resourcepack/replete)
[![CurseForge](https://github.com/intergrav/devins-badges/raw/2dc967fc44dc73850eee42c133a55c8ffc5e30cb/assets/cozy/available/curseforge_vector.svg)](https://www.curseforge.com/minecraft/texture-packs/replete)

See the version info in the filename for the supported Minecraft versions.  
Client-side.

## Contributing

If you've encountered a problem or you want to suggest
features, [create an issue](https://github.com/steves-underwater-paradise/replete/issues/new) on the issue tracker.

### Development

- `git clone https://github.com/steves-underwater-paradise/replete.git`
- `cd replete`

### PBR

For packing PBR textures into the LabPBR format, you need [`lab_pbr_cli`](https://github.com/steves-underwater-paradise/lab_pbr_cli).  

- Install [Rust and Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)
- `cargo install --git https://github.com/steves-underwater-paradise/lab_pbr_cli.git`
- `lab_pbr_cli --help`

## License

This project is licensed under CC-BY-SA-4.0, see [LICENSE](LICENSE).
