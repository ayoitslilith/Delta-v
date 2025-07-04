<div class="header" align="center">  
<!--<img alt="Delta-V Logo" width="128" height="128" src="https://raw.githubusercontent.com/DeltaV-Station/Delta-v/master/Resources/Textures/Logo/logo.png" />
<!-- <img alt="Delta-V Banner" width="512" height="126" src="https://raw.githubusercontent.com/DeltaV-Station/Delta-v/master/Resources/Textures/Logo/banner.png" /> -->
</div>

All Access is a fork of Delta-V. Will explain later, but you already know the gist if you're here, don'tcha?

Delta-V is a fork of [Space Station 14](https://github.com/space-wizards/space-station-14), embracing a mixture of classic SS13 chaos and experimentation only possible with the new engine.

Space Station 14 is a remake of SS13 that runs on [Robust Toolbox](https://github.com/space-wizards/RobustToolbox), a homegrown engine written in C#.

### Delta-V is a continuation of the [Nyanotrasen](https://www.nyanotrasen.moe/) fork. Any work done in a non-base namespace may contain incorrect attributes due to rewrites and recommitting.

## Links

#### DeltaV
<div class="header" align="center">  
[Website](https://deltav.gay/) | [Wiki](https://wiki.deltav.gay/view/Main_Page) | [Discord](https://discord.gg/deltav)
</div>

#### Space Station 14
<div class="header" align="center">  

[Website](https://spacestation14.io/) | [Discord](https://discord.ss14.io/) | [Forum](https://forum.spacestation14.io/) | [Steam](https://store.steampowered.com/app/1255460/Space_Station_14/) | [Standalone Download](https://spacestation14.io/about/nightlies/)

</div>

## Documentation/Wiki

The [docs site](https://docs.spacestation14.io/) has documentation on SS14s content, engine, game design and more.
Additionally, see these resources for license and attribution information:  
- [Robust Generic Attribution](https://docs.spacestation14.com/en/specifications/robust-generic-attribution.html)  
- [Robust Station Image](https://docs.spacestation14.com/en/specifications/robust-station-image.html)

## Contributing

We are happy to accept contributions from anybody. Get in Discord if you want to help. We've got a [list of issues](https://github.com/DeltaV-Station/Delta-v/issues) that need to be done and anybody can pick them up. Don't be afraid to ask for help either!

Make sure to read [CONTRIBUTING.md](/CONTRIBUTING.md) if you are new to Delta-V!

## Building

1. Clone this repo:
```shell
git clone https://github.com/DeltaV-Station/Delta-v.git
```
2. Go to the project folder and run `RUN_THIS.py` to initialize the submodules and load the engine:
```shell
cd Delta-v
python RUN_THIS.py
```
3. Compile the solution:  

Build the server using `dotnet build`.

[More detailed instructions on building the project.](https://docs.spacestation14.com/en/general-development/setup.html)

## License

Content contributed to this repository after commit 87c70a89a67d0521a56388e6b1c3f2cb947943e4 is licensed under the GNU Affero General Public License version 3.0, unless otherwise stated. See `LICENSE-AGPLv3.txt`.
Content contributed to this repository before commit 87c70a89a67d0521a56388e6b1c3f2cb947943e4 is licensed under the MIT license, unless otherwise stated. See `LICENSE-MIT.txt`.

To be more specific, code in `Content.*/_DV`, `Resources/*/_DV` and any Delta-V specific scripts in `Tools` are licensed under AGPLv3. Other files are originally from other codebases and are not owned by Delta-V, though any code must be relicensable to AGPLv3. SS14 is MIT licensed so this forking is possible.

[87c70a89a67d0521a56388e6b1c3f2cb947943e4](https://github.com/DeltaV-Station/Delta-v/commit/87c70a89a67d0521a56388e6b1c3f2cb947943e4) was pushed on February 17th 2024 at 21:48 UTC

Most assets are licensed under [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) unless stated otherwise. Assets have their license and the copyright in the metadata file. [Example](https://github.com/DeltaV-Station/Delta-v/blob/master/Resources/Textures/Objects/Tools/crowbar.rsi/meta.json).

Code taken from [Project Starlight](https://github.com/ss14Starlight/space-station-14) was taken in accordance with the [Starlight License](./LICENSE-Starlight.txt).

> [!NOTE]
> Some assets are licensed under the non-commercial [CC-BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) or similar non-commercial licenses and will need to be removed if you wish to use this project commercially.
